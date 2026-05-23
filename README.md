# code# Program to check for weekend discounts
day = input("Enter the current day of the week: ").strip().lower()

# Using multiple OR statements in a single IF condition
if day == "friday" or day == "saturday" or day == "sunday":
    print("Congratulations! You qualify for the weekend discount.")
else:
    print("Today is a standard pricing day.")

# Pro Tip: A cleaner way to write multiple ORs for the same variable:
# if day in ["friday", "saturday", "sunday"]:
#     print("Congratulations! You qualify for the weekend discount.")
-python
