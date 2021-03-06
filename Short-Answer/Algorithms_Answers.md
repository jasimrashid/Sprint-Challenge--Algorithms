#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) Big(O) ~ O(n^3)

For *each unit increase* in n, the number of iterations increases ~n^3 fold. For example, If we increase n from 1 to 2, the number of iterations increases from 1*1*1 = 1 to 2*2*2 = 8, an increase of 7 which approximates to 8. 


b) Big(O) ~ O(n^2)
 
The number of iterations approximates n^2, as the first loop iterates n times, and for each of these loops there is a second loop that iterates (n-1)^2 times. Therefore, with each increase in n, the increase in iteration approximates O(n^2)


c) BigO ~ O(n) or linear
For each increase in n, the number of recurions incrases by 1. Another way to look at this is to take an example: If bunnies = 2, then the process runs thrice. If it is 3, then it runs four times. 

## Exercise II




Algorithm:
1. Start from the top floor. Throw an egg. 

Does it break?

2. If NO: Then set f equal to the floor you threw it from.
3. If YES: move down to the floor that is half of the number of floors you previously ascended/descended. 
4. Throw the egg again. 
Does it break?
5. If NO: Move up by half the number of floors you previously descended/ascended
6. If YES: repeat step 3
Does it break?
7. If NO: repeat step 5
6. If YES: repeat step 3
.....
eventually you will converge to the floor from which the egg won't break if you throw the egg from it, but it will from the floor above. This will be your final value of f.

