## Encapsulation

### Description

A bank has decided to renew its policy; according to the new policy, you can only own a savings account with minimum savings of Rs.1000. Construct a class <b>SavingAmount</b> with only one integer instance variable <b>saving</b>. The class will have the following methods in it:

1. A setter method that will take an integer as a parameter and set the value of savings equal to that of the integer.
2. A getter method that will return the <b>saving</b>.
3. An increment method that will increase the savings by Rs.1000.
4. A decrement method that will decrease the savings by Rs.100.
5. A method to check the savings of a person say <b>checkSaving</b>. If the savings amount is greater than or equal to Rs.1000, print “Congratulations! You have saved a good amount”. If the amount is less than Rs.1000 and greater than or equal to 0, print “Insufficient saving!”. If the savings amount is less than 0, print “You are in debt”.

### Input

Your program should take the integer amount.

### Output

The output should be in the following format.

1. Call the decrement method once and then print the value returned by the getter method in the class.
2. Call the increment method once and then print the value returned by the getter method in the class.
3. Call the 'checkSavings' method.
4. Display the total savings.

### Sample Input

2000

### Sample Output

Congratulations! You have saved a good amount<br>
Your current savings are Rs 20900

### Sample Input

-1000

### Sample Output

You are in debt<br>
Your current savings are Rs -100

### Sample Input

-100

### Sample Output

Insufficient saving!
Your current savings are Rs 800
