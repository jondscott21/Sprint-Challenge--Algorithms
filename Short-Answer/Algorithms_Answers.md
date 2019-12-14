#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n) since it's dependant on the size of n * n * n * for number of operations and each step is n * n

b)
O(log n) it's two nested looped dependant on 'n' as a end point

c)
O(n) where 'n' is bunnies
## Exercise II

<!-- this will change the length of n in binary search fashion adjusting to middle as needed -->
check_floor(n, f, low=0)
    middle = n - low // 2
    if f == middle:
        return middle
    else if f > middle:
        check_floor(middle, f, low)    
    else 
        check_floor(n, f, middle)

should have an O(log n) runtime since it's binary search