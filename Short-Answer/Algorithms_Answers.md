#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a)
O(n) since it's dependant on the size of n * n * n * for number of operations and each step is n * n

b)
O(n^2) it's two nested looped dependant on 'n' as a end point

c)
O(n) where 'n' is bunnies
## Exercise II

check_floor(n, f, low=0)
    middle = n - low // 2
    if f == middle:
        return middle
    else if f > middle:
        n = middle
        
    else 
        low = middle
        check_floor(n, f, low)

should have an O(log n) runtime since it's binary search