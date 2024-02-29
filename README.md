def fun1(numbers):
    # Check if there is at least one number provided
    if not numbers:
        print("No numbers provided.")
        return
    
    # Extract the last number from the sequence
    last_number = numbers[-1]
    
    # Validate that the last number is not zero
    if last_number == 0:
        print("The last number cannot be zero.")
        return
    
    # Find the divisors of the last number

    for i in range(1,last_number+1):
        if(last_number%i==0):
            print(i)
    

# Sample input
fun1([6, 7, 8])
