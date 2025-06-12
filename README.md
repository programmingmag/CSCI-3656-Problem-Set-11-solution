# CSCI-3656-Problem-Set-11-solution

Download Here: [CSCI 3656 Problem Set 11 solution](https://jarviscodinghub.com/assignment/csci-3656-problem-set-11-solution/)

For Custom/Original Work email jarviscodinghub@gmail.com/whatsapp +1(541)423-7793

1. [10 pts] Apply Richardson extrapolation starting from h = 0.1 to get f
0
(1) for
f(x) = e
x + 0.5 and using center differences. Compare the resulting estimate to
the true value and to the results that you obtained for this function with that
method in PS10.
2. In your favorite programming language, write a program that uses the trapezoid
rule to compute R x2
x1
f(x)dx from a data set.
Your program should take the following inputs:
• a series of (evenly spaced) values for x
• a series of values for f(x) at those x values
• a lower bound x1 for the integration
• an upper bound x2 for the integration
• a step size h, which must be a multiple of the sample interval in the data table
The x and f(x) can be in individual lists, or together in a table or matrix or
whatever data structure you want, but please explain your choice in a comment.
Your program should complain if the data are not evenly spaced, and it should
not allow the user to specify bound values that fall between the table entries —
i.e., x = 1.03 is not a legal lower-bound argument for the table in part (a) below
(otherwise the integration gets difficult).
The output should be a single number: the value R x2
x1
f(x)dx computed using panels
built from points that are h apart. Please turn in a copy of your code.
(a) [10 pts] Use your code to compute R 1.8
1.0
f(x)dx from the table at the top of the
next page using h = 0.1. (These data are in a file on the course webpage if you
don’t want to type them in.)
1
x f(x) x f(x)
0.9000 2.9596 1.4000 4.5552
0.9500 3.0857 1.4500 4.7631
1.0000 3.2183 1.5000 4.9817
1.0500 3.3577 1.5500 5.2115
1.1000 3.5042 1.6000 5.4530
1.1500 3.6582 1.6500 5.7070
1.2000 3.8201 1.7000 5.9739
1.2500 3.9903 1.7500 6.2546
1.3000 4.1693 1.8000 6.5496
1.3500 4.3547 1.8500 6.8598
1.9000 7.1859
(b) [10 pts] Repeat part (a) of this problem with h = 0.2.
3. [10 pts] Repeat the previous problem using Simpson’s 1/3 rule. This should only
require a few minor modifications of the code. Don’t forget to handle the problem
that arises if you don’t have the right number of data points to divide neatly into
the three-point-wide panels (with points spaced h apart) that this method uses.
Please also turn in a copy of this code.
4. [10 pts] The function tabulated above is actually the same one as in the first
problem above (f(x) = e
x + 0.5).
(a) Using calculus, figure out what R 1.8
1.0
f(x)dx should be.
(b) Comment on how close your four answers from parts (a) and (b) of problems
2 and 3 are to this number. Which one of each (a)/(b) pair is better? Why? Is
Simpson’s 1/3 rule generally better than trapezoidal, for the same h?

