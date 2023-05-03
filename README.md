Download Link: https://assignmentchef.com/product/solved-cs135-project-2
<br>
<u>Project [2]: Logical Expressions and Branching Statements</u>




<h1>Project Goals</h1>

The goals of this project are to:

<ol>

 <li>Get students familiar with evaluating logical expressions</li>

 <li>Get students familiar with if – else statements</li>

 <li>Get students familiar with if – else if – else statements</li>

</ol>




<strong><u>Important Notes:</u> </strong>

<ol>

 <li><strong>Formatting: </strong>Make sure that you follow the precise recommendations for the output content and formatting: for example, do not change the text of the problem from “Enter volumes and price per volume for collection 1: ” to “Enter volume, price: ”. Your assignment will be auto-graded and any change in formatting will result in a loss in the grade.</li>

 <li><strong>Comments: </strong>Header comments are required on all files and recommended for the rest of the program. Points will be deducted if no header comments are included.</li>

</ol>

<strong> </strong>

<h1>Problem 1</h1>

Write a program that asks the user to enter information about three book collections. Each collection has a number of volumes and a price per volume (same for each volume in the collection). The program should ask how many volumes and what is the price per volume for each collection, as well as a budget available for a buyer named Bob. All values entered should be integers. The program should evaluate a set of logical expressions and print out specific messages based on the truth value of those expressions. The expressions are as follows:

<ul>

 <li><em>Bob has money</em>.</li>

</ul>

If the condition is true (budget is greater than 0) the program should print:

(1) Bob has some money to buy collections.

If the condition is false, the program should print:

(1) Bob does not have money to buy anything.




<ul>

 <li><em>At least two collections are more expensive than Bob’s Budget.</em></li>

</ul>

If the condition is true the program should print:

<ul>

 <li>At least two collections are more expensive than Bob’s budget.</li>

</ul>

If the condition is false, the program should print:

(3) At least two collections are cheaper than or equal to Bob’s budget.




<ul>

 <li><em>All the collections cost the same, only two collections cost the same, or no collections cost the same.</em></li>

</ul>

If all the collections cost the same, the program should print:

<ul>

 <li>All the collections cost the same.</li>

</ul>

If only two collections cost the same, the program should print:

(4) Only two collections cost the same amount of money.

If none of the collections cost the same, the program should print:

(4) No collections have the same price.




<ul>

 <li><em>Only one collection is cheaper than or equal to Bob’s budget</em>.</li>

</ul>

If the condition is true, the program should print:

<ul>

 <li>Only one collection is cheaper than or equal to Bob’s budget.</li>

</ul>

If the condition is false, the program should print:

(4) More than one collection is cheaper than or equal to Bob’s budget or they are all more expensive.




<ul>

 <li><em>The maximum number of collections that Bob can buy.</em></li>

</ul>

If Bob can buy all the collections, the program should print:

<ul>

 <li>Bob can buy all three collections.</li>

</ul>

If Bob can only buy two of the collections, the program should print:

(5) Bob can only buy two of the collections.

If Bob can only buy one of the collections, the program should print:

(5) Bob can only buy one collection.

If Bob can’t buy any collection, the program should print:

(5) Bob cannot buy any collection.




The program should function as follows (items underlined are to be entered by the user):

Enter volumes and price per volume for collection 1: <u>2 20</u>

Enter volumes and price per volume for collection 2: <u>3 30</u>

Enter volumes and price per volume for collection 3: <u>4 50</u>

Enter Bob’s budget: <u>100</u>

<ul>

 <li>Bob has some money to buy collections</li>

 <li>At least two collections are cheaper than or equal to Bob’s budget.</li>

 <li>No collections have the same price.</li>

 <li>More than one collection is cheaper than or equal to Bob’s budget or they are all more expensive (5) Bob can only buy one collection.</li>

</ul>




Save your program as collections.c







<strong>Challenge for problem 1 </strong>(10 extra credit points):

Your program should also check the following conditions (you can add them at the end of the previous 5 in the original program):




(6) <em>Bob has enough money to buy any one of the three collections.</em>

If the condition is true the program should print:

<ul>

 <li>Bob has enough money to buy any one of the three collections.</li>

</ul>

If the condition is false, the program should print:

<ul>

 <li>Bob does not have enough money to buy any one of the three collections.</li>

</ul>




<ul>

 <li><em>Bob does not have enough money to buy any collection</em>.</li>

</ul>

If the condition is true, the program should print:

<ul>

 <li>Bob does not have enough money to buy any collection.</li>

</ul>

If the condition is false, the program should print:

(7) Bob can buy at least one collection.







The program should function as follows (items underlined are to be entered by the user):

Enter volumes and price per volume for collection 1: <u>2 20</u>

Enter volumes and price per volume for collection 2: <u>3 30</u>

Enter volumes and price per volume for collection 3: <u>4 50</u>

Enter Bob’s budget: <u>100</u>

<ul>

 <li>Bob has some money to buy collections</li>

 <li>At least two collections are cheaper than or equal to Bob’s budget.</li>

 <li>No collections have the same price.</li>

 <li>More than one collection is cheaper than or equal to Bob’s budget or they are all more expensive</li>

 <li>Bob can only buy one collection.</li>

 <li>Bob does not have enough money to buy any one of the three collections. (7) Bob can buy at least one collection.</li>

</ul>




Save your challenge separately as collections_c.c


