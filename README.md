Factorial using recursion -

We know that -                 4! = 4 * 3 * 2 * 1

We can write it as -           4! = 4 * 3!

Similarly we can write -       3! = 3 * 2!
                               2! = 2 * 1!
                               1! = 1 * 0!
                               
In general we can write -       n! = n * (n-1)!

So the recursive definition
of factorial can be written as  n!  =  1           ,   n = 0
                                       n * (n-1)!  ,   n > 0
