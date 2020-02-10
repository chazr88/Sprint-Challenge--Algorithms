#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)O(n). This is because the number of operations is in direct proportion to the increase in the input


b)O(n2) "O of n squared". This is doing a loop to check if j is smaller than the input. If so it doubles and the counter goes up by 1. This is another example of the number of operations being a direct
proportion to the input, but is made up of 2 O(n). O(n) + O(n) = O(n2)


c)O(n^2). This is because the the number of operations get increase quadratic of the input. For each time you increase the input number the function has to do many more steps. 

## Exercise II

The runtime complexity of this would be O(n).

if floor is greater than or equal to f
    danger_floor = f
    current_floor = danger_floor
    if we want to move to a safer floor
        while current_floor >= f
            current_floor - 1
    if we want to safely throw the egg
        if current_floor > f
            throw_egg


