#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) O(n) -- This appears to be linear as run time will increase based on the input.


b) O(n^2) -- This has a nested while loop in the for loop.


c) O(n) -- The number of bunnyEars is the same as the number of bunnies entered which cause the number of steps required to complete to grow linearly with the number of bunnies. 

## Exercise II

U - In an building with n stories, eggs thrown off the building at f story or higher will break. Eggs thrown off the building from floors below f will not break. 

P - Binary search seems to be a good first pass option here. Runtime complexity for binary search is O(log n).

E - To find the point at which eggs will not break (all the floors blow f), I would start by throwing an egg off the middle floor. If it breaks, I would go down to the floor that is half way between the middle floor and the ground floor. I would go up or down from that floor based on what happened to the egg when thrown from that floor. 

R - While fewer eggs would be used to find the sweet spot, I may not be able to us my legs after this project. Maybe use linear search next time, and hope we get lucky!

..........

