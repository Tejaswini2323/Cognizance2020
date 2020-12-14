#Pseudo code for Armstrong number:

1. Declare integers sum, number, x, digit.
2. Use x to get the input from the user.
3. Assign x to variable number(x=number)
4. Assign the variable sum as 0 (sum =0)
5. Assign while loop with a condition number>0
6. Inside the while loop:
   * Assign digit = number%10
   * Sum = sum + (digit *digit* digit)
   * Number = number/10
8. If the while condition is false then:
   * If sum ==x is true, then it is an Armstrong number.
   * If the sum ==x is false, then it is not an Armstrong number.
   
![Screenshot](armstrong.png)
