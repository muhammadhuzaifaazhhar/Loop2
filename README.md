# Loop2
# Problem 2: Display Numbers with User Input

# Get user input for start, stop, and increment values
start = int(input("Enter start value: "))
stop = int(input("Enter stop value: "))
increment = int(input("Enter increment value: "))

# Use a while loop to display numbers based on user input
while start <= stop:
    print(start)
    start += increment
