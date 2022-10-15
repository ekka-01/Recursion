Recursion Examples -



(A) FACTORIAL -



We know that the factorial of a positive integers n can be found out by multiplying all integers from 1 to n.
                                n! = 1 * 2 * 3 * ....... * (n-1) * n

This is the iterative approach.

Now, we will try out the solution of this factorial problem recursively.

We know that -                  4! = 4 * 3 * 2 * 1

We can write it as -            4! = 4 * 3!

Similarly we can write -        3! = 3 * 2!
                                2! = 2 * 1!
                                1! = 1 * 0!
                               
In general we can write -       n! = n * (n-1)!

So the recursive definition of factorial can be written as  
                                n!  =  1    ,   n = 0                                                                                                         
                                n * (n-1)!  ,   n > 0



(B) FIBONNACI SERIES -



Fibonnaci series is a sequence of numbers in which the first two numbers are 1, and after that each number is the sum of previous two numbers.
1, 1, 2, 3, 5, 8, 13, 21, 34, 55, 89, .......

The problem of finding the nth Fibonnaci number can be recursively defined as -                                                                                                                                                                      
                                fib(n) = 1                   ,   n=0 or n=1 (Base case)                                                                       
                                         fib(n-1) + fib(n-2) ,   n>1 (Recursive case)
