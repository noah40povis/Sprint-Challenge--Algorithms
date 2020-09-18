#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) because a will porportionally increase as the input n increases. 


b)  O(n log n)
The runtime is O(n log n) because the outer loop is looping through "n" while the inner loop is loop through log "n" since the data is split and compared.

c) 0(2^n)
    Because we are using a recursive we need to run through the function everytime we dont meet our base case and evrytime we get to the second return we are make exponentially more results our function needs to go through. 

## Exercise II

Given that there are levels where, if the egg was dropped from, will break the egg and floors where the egg will safely land I will recommend using a binary search algorithm. So the threshold we are looking for we could find by dividing up the floors by starting with presumed 'medium' floor. 

First we would define a binary_search_egg function with the parameters building and floor. 
Next we would set a variable bottom_f = 0 and set top_floor equal to length of building minus one. 
While the bottom <= top_floor 
find the middle_f 
if the eggs break at floor_f  
check the floors between the bottom_f and middle_f 
if the eggs dont break at floor_f 
check the floors between the middle_f and the top_f 


