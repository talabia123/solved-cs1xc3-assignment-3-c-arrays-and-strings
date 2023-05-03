Download Link: https://assignmentchef.com/product/solved-cs1xc3-assignment-3-c-arrays-and-strings
<br>



<strong>Primary Learning Objectives</strong>

<ul>

 <li>Write C programs using arrays and strings.</li>

</ul>

<h1>Requirements</h1>

Create a program that will count the occurrences of letters in a user-input string and create a report.

Your program should begin by asking the user to enter text for analysis.  The user should be able to type up to 1023 characters and hit enter, and your program should be able to store these characters as a C string.  Your program should have a buffer (i.e. char array) for storing this string that can handle up to the maximum length needed to hold the this amount of characters (but not more than the amount of space required either).

Your program should then analyze the string to count the number of characters of each letter from ‘A’ to ‘Z’ in the string.  Your program should count both uppercase and lowercase instances of the characters as an occurrence of the character.  In other words, the string “AaaAbB” would have a count of 4 ‘A’ characters and 2 ‘B’ characters.  Your program should keep track of the count of each A to Z character using an array, not with individual variables.

Your program should output the total occurrences of each character in a table, along with the percentage of the string that is made up of each character from A-Z.  The table should have three columns:

<ul>

 <li>Letter – 10 characters, left-aligned</li>

 <li>Occurrences – 15 characters, left-aligned</li>

 <li>Percentage – 15 characters, left-aligned, output two decimal digits of precision</li>

</ul>

Beneath the table, your program should also output the most frequently occurring character from A-Z, and the least frequently occurring character from A-Z.  If two or more characters are “tied” for either most frequently occurring character or least frequently occurring character, then you can output any of those characters as being the most frequently or least frequently occurring character.

<strong>Hint: </strong>Remember that characters in C are really just an int number.  It’s possible to write a very simple and short version of this program if you keep this in mind: <a href="http://www.asciitable.com/">http://www.asciitable.com/</a><a href="http://www.asciitable.com/">.</a>

Your program should run either identically or near identically to this example, in particular the occurrences and percentages should be identical:







Here is another example of the program running:










Note that it is OK that the percentages of the A-Z characters in the string do not add up to

100%, we would not expect this because it’s a percentage of the string that is made up of each character (and the string may includes characters that are not letters from A-Z, so things like space characters, periods, etc.).

Add some comments to your code that explain what each section of code is responsible for doing, and if needed because it may not be obvious to the read, explain how the code itself is carrying out the work it is responsible for doing.




<h1>Help</h1>

Keep in mind that we’ve written a lot of code in-class and in-lab that is similar to what you need to implement!  We went over an example of user input of a string with spaces in-class, and finding a minimum number in an array.  In-lab during week 4 you will go over examples of analyzing individual characters in a string (postal code), and finding a maximum number in an array.  We have gone over examples of printing a formatted table too. So much of what you need to do in this assignment is very similar to these examples, and you should use them to help you out!