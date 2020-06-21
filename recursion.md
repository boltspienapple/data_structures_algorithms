# Recursion
The function calling itself again and again is called Recursion.</br>
It helps us lot during coding.</br>
Infinite loop can also be called as a recursion.</br>
    
    function recursive(input):
        if input <= 0:
            return input
        else:
            output = recursive(input - 1)
            return output
**Example**</br>

    Getting power of 2^n

        def power_of_2(n):
            if n= 0:
                return 1

            return 2 * power_of_2(n-1)
        
        print(power_of_2(n))

        In the above example we get the power of 2 power any number and once the n becomes equal to zero then the it return value 1. Otherwise the condition runs again and again untill the condition is met.