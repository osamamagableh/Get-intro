# Comparison Operators

Comparison operators are used in logical statements to determine equality or difference between variables or values.

**in this table we will find the Operators:

![operators table](https://upload-images.jianshu.io/upload_images/2204783-0fd37794d93859bb.JPG)

**How Can it be Used**

Comparison operators can be used in conditional statements to compare values and take action depending on the result:

if (age < 18) text = "Too young";

**Comparing data of different types may give unexpected results.**

When comparing a string with a number, JavaScript will convert the string to a number when doing the comparison. An empty string converts to 0. A non-numeric string converts to NaN which is always false


# JavaScript Loops

Loops has two tayps:
1. **For loop** :

The for loop has the following **syntax**:

for (statement 1; statement 2; statement 3) {
  // code block to be executed
}

Statement 1 is executed (one time) before the execution of the code block.

Statement 2 defines the condition for executing the code block.

Statement 3 is executed (every time) after the code block has been executed.

Ex:

for (i = 0; i < 5; i++) 
{
  text += "The number is " + i + "<br>";
}

The for loop work like this 

1. statment 1 wil done fist one (initial the counter)

2. statment 2 will do second one (The condition that will apply)

3. Now the code will executed if the condition return true 

4. statment 3 will do last one (update the counter)



2. **while loop**:

The while loop loops through a block of code as long as a specified condition is true.

**Syntax**

while (condition) {
  // code block to be executed
}

Ex : 

while (i < 10) {
  text += "The number is " + i;
  i++;
}

The while loop will work like this :

1. firstly will check the condition if ture then will go to code to be executed the will recheck if the 
condition is still true until the condition eill return false .



