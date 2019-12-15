# brainteaser_problem

For given n and α, determine the smallest number k for which n can be expressed as a sum of k numbers each of which is a perfect α-th power.




# brainteaser_problem2

The user input consists of a positive integer n≥5 and a sequence x1, x2, …, xn−1 of n−1 positive real numbers. 
There are n airports arranged on a straight line. Their names are A0, A1, …, An−1. 
Every two adjacent airports are 100 miles apart.
A small airplane is located at the airport A0 and needs to fly to the airport An−1. Once it takes off, the range of the airplane is 300 miles. 
The landing fee for the airport A1 is x1, the landing fee for A2 is x2, …, the landing fee for the airport An−1 is xn−1. 


Create the program that calculates the smallest amount of money that the airplane needs to be able to complete the journey from A0 to An−1.

The airplane does not have to pay the fee for the airport A0 since it came there on a boat or by some other transportation method that avoided landing.

Example:

Input:

12

1 2 9 1 9 9 1 2 9 9 5

Output:

10

Explanation: The cheapest route involves landing at the airports 1, 4, 7, 8, and 11. The total fee is
.....................................x[1]+x[4]+x[7]+x[8]+x[11]=1+1+1+2+5=10.
