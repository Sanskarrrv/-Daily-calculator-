class ShopTracker:
    def __init__(self):
        # Lists to store the history of transactions
        self.sales = []
        self.expenses = []

    def add_sale(self, item_name, amount):
        """Records a sale."""
        try:
            amount = float(amount)
            if amount < 0:
                print("Error: Amount cannot be negative.")
                return
            self.sales.append({"item": item_name, "amount": amount})
            print(f"✅ Sale recorded: {item_name} for ${amount:.2f}")
        except ValueError:
            print("❌ Error: Please enter a valid number for the amount.")

    def add_expense(self, description, amount):
        """Records an expense (rent, stock, bills)."""
        try:
            amount = float(amount)
            if amount < 0:
                print("Error: Amount cannot be negative.")
                return
            self.expenses.append({"description": description, "amount": amount})
            print(f"📉 Expense recorded: {description} for ${amount:.2f}")
        except ValueError:
            print("❌ Error: Please enter a valid number for the amount.")

    def show_report(self):
        """Calculates and prints the financial summary."""
        total_sales = sum(item['amount'] for item in self.sales)
        total_expenses = sum(item['amount'] for item in self.expenses)
        net_profit = total_sales - total_expenses

        print("\n" + "="*30)
        print("     FINANCIAL REPORT     ")
        print("="*30)
        print(f"Total Revenue (Sales):  ${total_sales:.2f}")
        print(f"Total Expenses:         ${total_expenses:.2f}")
        print("-" * 30)
        
        if net_profit >= 0:
            print(f"NET PROFIT:             ${net_profit:.2f}")
        else:
            print(f"NET LOSS:               ${abs(net_profit):.2f}")
        print("="*30 + "\n")

    def show_history(self):
        """Shows detailed list of all transactions."""
        print("\n--- Sales History ---")
        for s in self.sales:
            print(f" + {s['item']}: ${s['amount']:.2f}")
            
        print("\n--- Expense History ---")
        for e in self.expenses:
            print(f" - {e['description']}: ${e['amount']:.2f}")
        print("")

# --- Main Program Loop ---
def main():
    tracker = ShopTracker()
    
    while True:
        print("1. Add Sale")
        print("2. Add Expense")
        print("3. View Financial Report")
        print("4. View Transaction History")
        print("5. Exit")
        
        choice = input("\nSelect an option (1-5): ")

        if choice == '1':
            item = input("Enter item name: ")
            price = input("Enter sale amount: ")
            tracker.add_sale(item, price)
        elif choice == '2':
            desc = input("Enter expense description (e.g., Rent, Stock): ")
            cost = input("Enter expense cost: ")
            tracker.add_expense(desc, cost)
        elif choice == '3':
            tracker.show_report()
        elif choice == '4':
            tracker.show_history()
        elif choice == '5':
            print("Exiting program. Goodbye!")
            break
        else:
            print("Invalid choice, please try again.")

if __name__ == "__main__":
    main()
