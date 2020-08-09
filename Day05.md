1. Change the provided string to a string with single quotes at the beginning and end and no escape characters. 
Right now, the <a> tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters.
~~~
OUTPUT:
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
console.log(myStr)
~~~
2. You will need to use escape sequences to insert special characters correctly. You will also need to follow the spacing as it looks above, with no spaces between escape sequences or words.
Here is the text with the escape sequences written out.
"FirstLinenewlinetabbackslashSecondLinenewlineThirdLine"
~~~
OUTPUT:
var myStr = "FirstLine\n\t\\SecondLine\nThirdLine"; // Change this line
~~~
3. Build myStr from the strings "This is the start. " and "This is the end." using the + operator.
~~~
OUTPUT:
var myStr = "This is the start. " + "This is the end."; // Only change this line
console.log(myStr)
~~~
4. Build myStr over several lines by concatenating these two strings: "This is the first sentence. " and "This is the second sentence." using the += operator. Use the += operator similar to how it is shown in the editor. Start by assigning the first string to myStr, then add on the second string.
~~~
OUTPUT:
var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
~~~
5. Set myName to a string equal to your name and build myStr with myName between the strings "My name is " and " and I am well!"
~~~
OUTPUT:
var myName = "Rahini";
var myStr = "My name is " + myName + " and I am well!";
console.log(myStr)
~~~
6. Set someAdjective and append it to myStr using the += operator.
~~~
OUTPUT:
var someAdjective = "Awesome!!!";
var myStr = "Learning to code is ";
myStr += someAdjective;
console.log(myStr)
~~~
7. Use the .length property to count the number of characters in the lastName variable and assign it to lastNameLength.
~~~
OUTPUT:
// Setup
var lastNameLength = 0;
var lastName = "Lovelace";
// Only change code below this line
lastName.length
lastNameLength = lastName.length;
~~~
8. Use bracket notation to find the first character in the lastName variable and assign it to firstLetterOfLastName.
~~~
OUTPUT:
// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";
// Only change code below this line
firstLetterOfLastName = lastName[0]; // Change this line
console.log(firstLetterOfLastName)
~~~
