# comp163-assignment-5
# Challenge 1: Collatz sequence - while loop for unknown iterations
print("=== Challenge 1: Collatz Conjecture ===")

current_number = int(input("Enter starting number: "))
step_count = 0

print("Sequence:", end=" ")
print(current_number, end=" ")

while current_number != 1:
    if current_number % 2 == 0:
        current_number //= 2
    else:
        current_number = 3 * current_number + 1
    print(current_number, end=" ")
    step_count += 1

print(f"\nSteps: {step_count}")
