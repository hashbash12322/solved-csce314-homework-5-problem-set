Download Link: https://assignmentchef.com/product/solved-csce314-homework-5-problem-set
<br>
<strong>Problem 1. </strong> Explain in a readme file (just .txt file) how to compile and execute your codes, and what is the expected output of your codes when tested. It should be detailed enough so that whoever grades your codes can understand what you were doing with your code clearly and should be able to reproduce your tests following what you wrote in it.

<strong>Problem 2. </strong> Section 1.6. Modify ImprovedFibonacci on pages 9–10 as instructed below. Name your modified class SubsetOutputFib, and place it in a file named

Fibonacci.java.

Let <em>f<sub>n </sub></em>denote the <em>n</em>-th Fibonacci number. The SubsetOutputFib will accept two integer values as command line input, assign the first one to be (meaning begin) and the second one to en (meaning end), and print out only those Fibonacci numbers from <em>f</em><sub>be </sub>to <em>f</em><sub>en</sub>. For example, if the two command line arguments are given as 4 and 7 in this order, then the output should be:

4: 3

5: 5

6: 8 *

7: 13

1

Make sure that you do the error checking whether both be and en are positive integers, and be≤en.

<strong>Problem 3.</strong> Section 1.10, Exercise 1.13 on page 24. Modify the ImprovedFibonacci on pages 9–10 (not the modified version in Problem 2). Place the modified ImprovedFibonacci implementation in the same file as Problem 2 (Fibonacci.java).

<strong>Problem 4. </strong>Section 2.1, Exercise 2.1 on page 44, Section 2.2, Exercise 2.3 on page 46, and Section 2.6, Exercise 2.13 on page 68. Work in a file Vehicle.java.

Use the following types for the fields: int for current speed, int for current direction in degrees (consider straight north as 0 degrees and the degree increments clockwise up to 359 degrees, thus for example, straight east is 90 degrees, straight south 180 degrees, and straight west 270 degrees), and String for owner name.

For Exercise 2.3, use int for both of the vehicle ID number fields. The static field for the next vehicle ID number should be simply incremented by one each time a vehicle instance is created.

<strong>Problem 5</strong>Section 2.4, Exercise 2.5 on page 50. Write the main method within a new class named VehicleTestP4. Create 5 vehicles and print their field values. To do so, create the vehicles (using the default constructor since you have not implemented any constructor of your own yet), set the values using the accessor (setter) methods that you implemented in Exercise 2.13 in the previous problem, and use the getter methods to print their field values.

<strong>Problem 6. </strong> Section 2.5, Exercise 2.7 on page 54, and Section 2.6, Exercise 2.9 on page 58. You will continue working on your Vehicle class from Problem 4, but the modified main needs to be in a different class, named VehicleTest since in the new main, you will now create the five vehicles using the constructor you added to the Vehicle class. Keep both VehicleTestP4 and VehicleTest in the same file Vehicle.java. From now on, whenever you add new functionalities to Vehicle, you will add the test code for the new functionalities in the main method of VehicleTest.

<strong>Problem 7. </strong> Section 2.6, Exercise 2.10 on page 60. Add test code of your toString method in the main method of VehicleTest.

<strong>Problem 8. </strong> Section 2.6, Exercise 2.15 on page 68. Add test code of those methods in the main method of VehicleTest.

<strong>Problem 9. </strong>Section 2.8, Exercise 2.17 on page 71. Add test code of those methods in the main method of VehicleTest.