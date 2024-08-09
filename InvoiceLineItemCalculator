print("The Invoice Line Item Calculator.\n")

def get_price():
    while True:
        try:
            price = float(input("\nPlease enter a price: "))
            return price
        except ValueError:
            print("Invalid decimal number. Please try again.")

def get_quantity():
    while True:
        try:
            quantity = int(input("Please enter a quantity: "))
            return quantity
        except ValueError:
            print("Invalid integer. Please try again")

def main():
    while True:
        # Get price and quantity from the user
        price = get_price()
        quantity = get_quantity()

        # Calculate the total
        total = price * quantity

        print(f"The entered price is: {price}")
        print(f"The entered quantity is: {quantity}")
        print(f"The total is: {total}")

        # Ask if the user wants to enter another line
        another = input("Enter another line item? (y/n): ").lower()
        if another == 'n':
            print("Program ended.")
            break
        elif another != 'y':
            print("Invalid input. Program ended.")
            break

# Run the main program loop
main()

