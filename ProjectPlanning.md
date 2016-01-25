CollatzTesting
Author: shadowfox23xxv
Date: 01/25/2016
Last edited: 01/25/2016

Overview:
	The Collatz Conjecture states that for any natural number n, if n is even divide by two(n/2), if n is odd multiply by three then add one(3n+1), if this is repeated, will always eventually reach 1.  In order to test this, a program will be written that must perform the following tasks:

-Start with a number to test and hold this number in a varible
-copy the test number to a new varible
-determine if the number is even or odd
-add one to a running count of steps required to reach 1
-perform the proper calculation on the test number and assign this new number to the testing variable
-repeat step 3 and down until number reaches one
-print to screen and/or a file the inital number of the test, and the number of steps needed to reach 1
-set testing variable to test number + 1
-repeat from step two down

This testing will obviously be limited, as tests have already been performed with starting numbers up into the millions.  A method of handling calculations with digits larger than the normal data types allowed may be necessary. Another improvement to speed up processing of the tests involving storing the number of steps to complete the test for the various test digits, and checking the testing variable against this list to short cut actually performing the remaining calculations on each step is also a possibility, and should be examined in terms of the memory overhead and speed reduction achievable. 
