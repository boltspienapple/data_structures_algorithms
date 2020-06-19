# Space and Time
    Efficiency also called as Complexity.
    It defines how well we use the resources of a Computer to get the particular job done.
    Space : How much storage space required to run the program
    Time : How much time does it takes to run the program
    Generally complexity depend on space and time.
    Processor runs ~Billion instructions per second
## Algorithm
    Series of steps described to solve a problem
    It is the rough flow process to solve a problem
*For a problem there may be different algorithms but some are more efficient than others*

## Time Complexity

### Quantifying Effieciency
    def example(n):
        for i in range(2):
            n += 100
        return n

    def example_1(n):
        for i in range(100):
            n += 2
        return n
From the above example and example_1 returns same output</br>
But the **example** is faster than **example_1**</br>
The reason is *example* function *adds 100 twice* but *example_1* function *adds 2, 100 times*</br>
This is called Quantifing Efficiency</br>
### Input Size and Efficiency
    Order : Rate of increase of an algorithm is called as Order
As Input size increases to an algorithm  the required time to run an algorithm also increases</br>
It may also increase in different rate sometimes based on the algorithms used.</br>

### Notation O(n)
**O(n) -- Big O of n notaion**</br>
O - Order of the function</br>
n - represents the length of your function</br>


    for i in range(n):
        print("Hello")
    the for loop runs only once so the Order is n
    if n = 1 hello is printed 1 time
    if n = 2 hello is printed 2 times
    if n = 3 hello is printed 3 times

    for i in range(n):
        for i in range(n):
            print("hello")

    here there are 2 for loops that means we will run it twice so the Order is n^2(n square)
    here the output would be 
    if n = 1 hello is printed 1 time
    if n = 2 hello is printed 4 times
    if n = 3 hello is printed 9 times

*n is always an algebraic expession*</br>

    examples of  some algebraic functions
    O(n)
    O(n^2)
    O(n^3)
    O(log(n))
    O(nlog(n))
### Scenarios
There are three cases for any problem.</br>
**Best Case**</br>
**Average Case**</br>
**Worst Case**</br>
Example</br>

    If we want to find a letter in the Alphabets then these are the following cases.
    We can find starting itself means first search -- O(1) This is the best case
    If we are running out of luck then we would search 26 times -- O(26) The worst case
    The remaing would be the average - O(n)

### Cheat Sheet
    https://www.bigocheatsheet.com/
    https://wiki.python.org/moin/TimeComplexity

## Space Efficiency
Same notation is used for space efficiency also.
In space efficiency **datatypes of the variables we use and their allocated space requirments**</br>

Examples</br>
    
    char   - 1 byte
    bool   - 1 byte
    int    - 4 bytes
    float  - 4 bytes
    double - 8 bytes