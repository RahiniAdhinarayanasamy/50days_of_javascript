1. Use the .pop() function to remove the last item from myArray, assigning the "popped off" value to removedFromMyArray.
~~~
// Setup
var myArray = [["John", 23], ["cat", 2]];
// Only change code below this line
var removedFromMyArray = myArray.pop();
console.log(removedFromMyArray)
console.log(myArray)
~~~
2. Use the .shift() function to remove the first item from myArray, assigning the "shifted off" value to removedFromMyArray.
~~~
OUTPUT:
// Setup
var myArray = [["John", 23], ["dog", 3]];
// Only change code below this line
var removedFromMyArray= myArray.shift();
console.log(removedFromMyArray)
console.log(myArray)
~~~
3. Add ["Paul",35] to the beginning of the myArray variable using unshift().
~~~
OUTPUT:
// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();
// Only change code below this line
myArray.unshift(["Paul", 35]);
console.log(myArray)
~~~
4. ["Chocolate Bar", 15]
There should be at least 5 sub-arrays in the list.
~~~
OUTPUT:
var myList = [["Chocolate Bar", 15], ["Choco Cone", 30], ["Venila", 10], ["venila Cone", 35], ["Amul Choco Cone", 50]];
console.log(myList)
~~~
5. Create a function called reusableFunction which prints "Hi World" to the dev console.
Call the function.
~~~
OUTPUT:
function reusableFunction(){
  console.log("Hi World");
}
reusableFunction();
~~~
