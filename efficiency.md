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

### Quantifying Effieciency
Example
    def example(n):
        for i in range(2):
            n += 100
        return n
Example_1
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
