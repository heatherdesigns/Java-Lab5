# Java-Lab5
<p>Homework assignment: Flooring Calculator</p>
<p>**Code to be added after assignment has been graded and instructor is no longer accepting homework submissions from other students.</p>

<p>The Dayton Floor Company has asked you to write a program to calculate the total cost of flooring for rectangular rooms or hallways. You will get user input for the room dimensions and the price per square foot of the flooring. To calculate total cost, multiply length &amp; width of the room to get the area, and then multiply the area by the price per square foot of flooring to get total price. For example, a 12’ x 10’ room has an area of 120 square feet. Flooring with a price of $8 per square foot, would be a total cost of $960 (12 x 10 x 8 = 960). The minimum purchase at the company is for a 10’ x 10’ room, charging $1.50 square foot. One customer, Ace Rehab Corp, has a standing monthly order to install $15.99 flooring for a 9.75’ x 12.5’ room.</p>
<p>Create the following in your program:</p>
<p>A class named RoomDimension that has the following data fields with appropriate modifiers &amp; data types:</p>
  <ul>
    <li>length of the room</li>
    <li>width of the room</li>
    <li>price of the flooring per square foot</li>
  </ul>
<p>The RoomDimension class should also contain:</p>
  <ul>
    <li>no-arg constructor (set default values: length 10.0, width 10.0, price $1.50 minimum as noted above)</li>
    <li>overloaded constructor that accepts length, width, &amp; price as arguments</li>
    <li>all setters &amp; getters</li>
    <li>value-returning method that calculates the area of the room (length x width)</li>
    <li>value-returning method that calculates the cost of the flooring (area x price)</li>
    <li>toString method to display results</li>
  </ul>
<p>The main method should:</p>
  <ul>
    <li>get user input for length &amp; width of the room and price per square foot of the flooring</li>
    <li>create an object using the no-arg constructor &amp; display output as noted above for minimum purchase</li>
    <li>create an object using the overloaded constructor &amp; display output of the user input</li>
    <li>create an object using the overloaded constructor &amp; display output as noted above for Ace Rehab</li>
  </ul>
<p>Required validation &amp; additional formatting: all user input must be validated (length &amp; width no less than 10, price no less than $1.50). Length, width, and area should be formatted to three decimal places. Price and total cost of the flooring must be formatted to currency.</p>
