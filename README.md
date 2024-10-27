Net income code below, plus additional file with same code in the repository. 

# Define the earnings from various items
earnings = {
    "Bubblegum": 202,
    "Toffee": 118,
    "Ice cream": 2250,
    "Milk chocolate": 1680,
    "Doughnut": 1075,
    "Pancake": 80
}

# Calculate total income
total_income = sum(earnings.values())

# Print the earned amounts
print("Earned amount:")
for item, amount in earnings.items():
    print(f"{item}: ${amount}")

print(f"\nIncome: ${total_income}")

# Get user input for expenses
staff_expenses = int(input("Staff expenses:\n"))
other_expenses = int(input("Other expenses:\n"))

# Calculate net income
net_income = total_income - (staff_expenses + other_expenses)

# Print the net income
print(f"Net income: ${net_income}")
