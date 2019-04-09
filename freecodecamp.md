1.Comment Your JavaScript Code

```JavaScript
// this is one line comment
/*this is multiline comment
  no I did not copy paste from the left of the page:) */
  ```
  
2.Declare JavaScript Variables

```JavaScript
//Declare myName below this line
var myName;
```

3.Storing Values with the Assignment Operator

  Note:Assignment always goes from right to left. Everything to the right of the = operator is resolved before the value is assigned to the variable to the left of the operator.
  
  - Assign the value 7 to variable a.
  - Assign the contents of a to variable b
```JavaScript
// Setup
var a;
var b = 2;

// Only change code below this line
a = 7;
b =a;
```

4.Initializing Variables with the Assignment Operator

  Note:It is common to initialize a variable to an initial value in the same line
  
  - Define a variable a with var and initialize it to a value of 9
```JavaScript
// Example
var ourVar = 19;
// Only change code below this line
var a = 9;
```

5.Understanding Uninitialized Variables

  Note:When JavaScript variables are declared, they have an initial value of undefined. If you do a mathematical operation on an undefined variable your result will be NaN which means "Not a Number". If you concatenate a string with an undefined variable, you will get a literal string of "undefined".
  
  -Initialize the three variables a, b, and c with 5, 10, and "I am a" respectively so that they will not be undefined.
```JavaScript
// Initialize these three variables
var a = 5;
var b = 10;
var c = "I am a";
// Do not change code below this line
a = a + 1;
b = b + 5;
c = c + " String!";
```

6.Understanding Case Sensitivity in Variables

Note:Best Practice-Write variable names in JavaScript in camelCase. In camelCase, multi-word variable names have the first word in lowercase and the first letter of each subsequent word is capitalized.

  -Modify the existing declarations and assignments so their names use camelCase.
Do not create any new variables.
```JavaScript
// Declarations
var studlyCapVar;
var properCamelCase;
var titleCaseOver;

// Assignments
studlyCapVar = 10;
properCamelCase = "A String";
titleCaseOver = 9000;
```

7.Add Two Numbers with JavaScript

  -Change the 0 so that sum will equal 20.
```JavaScript
var sum = 10 + 10;

```

8.Subtract One Number from Another with JavaScript

  -Subtract One Number from Another with JavaScript
```JavaScript
var difference = 45 - 33;
```

9.Multiply Two Numbers with JavaScript

  -Change the 0 so that product will equal 80
```JavaScript
var product = 8 * 10;
```

10.Divide One Number by Another with JavaScript

  -Change the 0 so that the quotient is equal to 2
```JavaScript
var quotient = 66 / 33;
```

11.Increment a Number with JavaScript

  -Change the code to use the ++ operator on myVar.
```JavaScript
var myVar = 87;
// Only change code below this line
myVar++;
```

12.Decrement a Number with JavaScript

  -Change the code to use the -- operator on myVar
```JavaScript
var myVar = 11;
// Only change code below this line
myVar--;
```

13.Create Decimal Numbers with JavaScript

Note:Not all real numbers can accurately be represented in floating point. This can lead to rounding errors.

  -Create a variable myDecimal and give it a decimal value with a fractional part
```JavaScript
var ourDecimal = 5.7;
// Only change code below this line
var myDecimal = 3.14;
```

14.Multiply Two Decimals with JavaScript

  -Change the 0.0 so that product will equal 5.0
```JavaScript
var product = 2.0 * 2.5;
```

15.Divide One Decimal by Another with JavaScript

  -Change the 0.0 so that quotient will equal to 2.2
```JavaScript
var quotient = 4.4 / 2.0; // Fix this line
```

16.Finding a Remainder in JavaScript

Note: The remainder operator % gives the remainder of the division of two numbers.The remainder operator is sometimes incorrectly referred to as the "modulus" operator. It is very similar to modulus, but does not work properly with negative numbers.Usage In mathematics, a number can be checked to be even or odd by checking the remainder of the division of the number by 2.
    17 % 2 = 1 (17 is Odd)
    48 % 2 = 0 (48 is Even)
    Example
    5 % 2 = 1 because
    Math.floor(5 / 2) = 2 (Quotient)
    2 * 2 = 4
    5 - 4 = 1 (Remainder)

  -Set remainder equal to the remainder of 11 divided by 3 using the remainder (%) operator.
```JavaScript
// Only change code below this line
var remainder = 11 % 3;
```

17.Compound Assignment With Augmented Addition

Note:One such operator is the += operator.
    Example
    var myVar = 1;
    myVar += 5;
    console.log(myVar); // Returns 6
    
  -Convert the assignments for a, b, and c to use the += operator.
```JavaScript
var a = 3;
var b = 17;
var c = 12;
// Only modify code below this line
a += 12;
b += 9;
c += 7;
```

18.Compound Assignment With Augmented Subtraction

-Convert the assignments for a, b, and c to use the -= operator.
```JavaScript
var a = 11;
var b = 9;
var c = 3;
// Only modify code below this line
a -= 6;
b -= 15;
c -= 1;
```

19.Compound Assignment With Augmented Multiplication

-Convert the assignments for a, b, and c to use the *= operator.
```JavaScript
var a = 5;
var b = 12;
var c = 4.6;
// Only modify code below this line
a *= 5;
b *= 3;
c *= 10;
```

20.Compound Assignment With Augmented Division

  -Convert the assignments for a, b, and c to use the /= operator.
```JavaScript
var a = 48;
var b = 108;
var c = 33;
// Only modify code below this line
a /= 12;
b /= 4;
c /= 11;
```

21.Declare String Variables

  -Create two new string variables: myFirstName and myLastName and assign them the values of your first and last name, respectively.
```JavaScript
// Example
var firstName = "Alan";
var lastName = "Turing";
// Only change code below this line
var myFirstName = "Fatih";
var myLastName = "Tutar";
```

22.Escaping Literal Quotes in Strings

Note:In JavaScript, you can escape a quote from considering it as an end of string quote by placing a backslash (\) in front of the quote.Example:
          var sampleStr = "Alan said, \"Peter is learning JavaScript\".";
          Alan said, "Peter is learning JavaScript".

  -Use backslashes to assign a string to the myStr variable so that if you were to print it to the console, you would see:
   I am a "double quoted" string inside "double quotes".
```JavaScript
var myStr = "I am a \"double quoted\" string inside \"double quotes\"."; // Change this line
```

23.Quoting Strings with Single Quotes

Note:The backslash \ should not be be confused with the forward slash /. They do not do the same thing.
     Another use for it would be saving an <a> tag with various attributes in quotes, all within a string.
     String values in JavaScript may be written with single or double quotes, as long as you start and end with the same type of quote.Example:
     goodStr = 'Jake asks Finn, "Hey, let\'s go on an adventure?"';
badStr = 'Finn responds, "Let's go!"'; // Throws an error

  -Change the provided string to a string with single quotes at the beginning and end and no escape characters.Right now, the <a> tag in the string uses double quotes everywhere. You will need to change the outer quotes to single quotes so you can remove the escape characters. 
  var myStr = "<a href=\"http://www.example.com\" target=\"_blank\">Link</a>";
  
```JavaScript
var myStr = '<a href="http://www.example.com" target="_blank">Link</a>';
```

24.Escape Sequences in Strings

Note:Code	Output
      \'	single quote
      \"	double quote
      \\	backslash
      \n	newline
      \r	carriage return
      \t	tab
      \b	backspace
      \f	form feed
      Note that the backslash itself must be escaped in order to display as a backslash.

  -Assign the following three lines of text into the single variable myStr using escape sequences.
    FirstLine
        \SecondLine
    ThirdLine
```JavaScript
var myStr = 'FirstLine\n\t\\SecondLine\nThirdLine' ; // Change this line
```

25.Concatenating Strings with Plus Operator

  -Build myStr from the strings "This is the start. " and "This is the end." using the + operator.
```JavaScript
// Example
var ourStr = "I come first. " + "I come second.";
// Only change code below this line
var myStr = "This is the start. " + "This is the end." ;
```

26.Concatenating Strings with the Plus Equals Operator

Note:We can also use the += operator to concatenate a string onto the end of an existing string variable. This can be very helpful to break a long string over several lines.
  
  -Build myStr over several lines by concatenating these two strings: "This is the first sentence. " and "This is the second sentence." using the += operator. Use the += operator similar to how it is shown in the editor. Start by assigning the first string to myStr, then add on the second string.
```JavaScript
// Example
var ourStr = "I come first. ";
ourStr += "I come second.";
// Only change code below this line
var myStr = "This is the first sentence. ";
myStr += "This is the second sentence.";
```

27.Constructing Strings with Variables

  -Set myName to a string equal to your name and build myStr with myName between the strings "My name is " and " and I am well!"
```JavaScript
// Example
var ourName = "freeCodeCamp";
var ourStr = "Hello, our name is " + ourName + ", how are you?";
// Only change code below this line
var myName = "Fatih";
var myStr = "My name is " + myName  + " and I am well!"; 
```

28. Appending Variables to Strings

  -Set someAdjective and append it to myStr using the += operator.
```JavaScript
// Example
var anAdjective = "awesome!";
var ourStr = "freeCodeCamp is ";
ourStr += anAdjective;
// Only change code below this line
var someAdjective = "cool!";
var myStr = "Learning to code is ";
myStr += someAdjective;
```

29.Find the Length of a String

Note:You can find the length of a String value by writing .length after the string variable or string literal.Example:
   "Alan Peter".length; // 10
   
   -Use the .length property to count the number of characters in the lastName variable and assign it to lastNameLength.// Example
var firstNameLength = 0;
var firstName = "Ada";

firstNameLength = firstName.length;

// Setup
var lastNameLength = 0;
var lastName = "Lovelace";

// Only change code below this line.

lastNameLength = lastName.length;
```JavaScript
// Example
var firstNameLength = 0;
var firstName = "Ada";
firstNameLength = firstName.length;
// Setup
var lastNameLength = 0;
var lastName = "Lovelace";
// Only change code below this line.
lastNameLength = lastName.length;
```

30.Use Bracket Notation to Find the First Character in a String

Note:Bracket notation is a way to get a character at a specific index within a string. Most modern programming languages, like JavaScript, don't start counting at 1 like humans do. They start at 0. This is referred to as Zero-based indexing. 
For example;
The character at index 0 in the word "Charles" is "C". So if var firstName = "Charles", you can get the value of the first letter of the string by using firstName[0]

  -Use bracket notation to find the first character in the lastName variable and assign it to firstLetterOfLastName.
```JavaScript
// Example
var firstLetterOfFirstName = "";
var firstName = "Ada";
firstLetterOfFirstName = firstName[0];
// Setup
var firstLetterOfLastName = "";
var lastName = "Lovelace";
// Only change code below this line
firstLetterOfLastName = lastName[0];
```

31.Understand String Immutability

Note:In JavaScript, String values are immutable, which means that they cannot be altered once created.
For example, the following code:
    var myStr = "Bob";
    myStr[0] = "J";
cannot change the value of myStr to "Job", because the contents of myStr cannot be altered. 

  -Correct the assignment to myStr so it contains the string value of Hello World.
```JavaScript
// Setup
var myStr = "Jello World";
// Only change code below this line
myStr = "Hello World"; // Fix Me
```

32.Use Bracket Notation to Find the Nth Character in a String

  -Let's try to set thirdLetterOfLastName to equal the third letter of the lastName variable using bracket notation.
```JavaScript
// Example
var firstName = "Ada";
var secondLetterOfFirstName = firstName[1];
// Setup
var lastName = "Lovelace";
// Only change code below this line.
var thirdLetterOfLastName = lastName[2];
```

33.Use Bracket Notation to Find the Last Character in a String

Note:In order to get the last letter of a string, you can subtract one from the string's length.
For example, if var firstName = "Charles", you can get the value of the last letter of the string by using firstName[firstName.length - 1].

  -Use bracket notation to find the last character in the lastName variable.
```JavaScript
// Example
var firstName = "Ada";
var lastLetterOfFirstName = firstName[firstName.length - 1];
// Setup
var lastName = "Lovelace";
// Only change code below this line.
var lastLetterOfLastName = lastName[lastName.length-1];
```

34.Use Bracket Notation to Find the Nth-to-Last Character in a String

Note:You can use the same principle we just used to retrieve the last character in a string to retrieve the Nth-to-last character.
For example, you can get the value of the third-to-last letter of the var firstName = "Charles" string by using firstName[firstName.length - 3]

  -Use bracket notation to find the second-to-last character in the lastName string.
```JavaScript
// Example
var firstName = "Ada";
var thirdToLastLetterOfFirstName = firstName[firstName.length - 3];
// Setup
var lastName = "Lovelace";
// Only change code below this line
var secondToLastLetterOfLastName = lastName[lastName.length - 2];
```

35.Word Blanks

  -In this challenge, we provide you with a noun, a verb, an adjective and an adverb. You need to form a complete sentence using words of your choice, along with the words we provide.You will need to use the string concatenation operator + to build a new string, using the provided variables: myNoun, myAdjective, myVerb, and myAdverb. You will then assign the formed string to the result variable.You will also need to account for spaces in your string, so that the final sentence has spaces between all the words. The result should be a complete sentence.
```JavaScript
function wordBlanks(myNoun, myAdjective, myVerb, myAdverb) {
  // Your code below this line
  var result = "your " + myAdjective + " " + myNoun + " " + myVerb + " "  + myAdverb;
  // Your code above this line
  return result;
}
// Change the words here to test your function
wordBlanks("little"," cat "," hit"," slowly");
```

36.Store Multiple Values in one Variable using JavaScript Arrays

Note:With JavaScript array variables, we can store several pieces of data in one place.You start an array declaration with an opening square bracket, end it with a closing square bracket, and put a comma between each entry, like this:

var sandwich = ["peanut butter", "jelly", "bread"].

  -Modify the new array myArray so that it contains both a string and a number (in that order).
```JavaScript
// Example
var ourArray = ["John", 23];
// Only change code below this line.
var myArray = ["string",1];
```

37.Nest one Array within Another Array

Note:You can also nest arrays within other arrays, like this: [["Bulls", 23], ["White Sox", 45]]. This is also called a Multi-dimensional Array.

  -Create a nested array called myArray.
```JavaScript
// Example
var ourArray = [["the universe", 42], ["everything", 101010]];
// Only change code below this line.
var myArray = [["my age", 41], ["my height", 1.75]];
```

38.Access Array Data with Indexes

Note: We can access the data inside arrays using indexes. Array indexes are written in the same bracket notation that strings use, except that instead of specifying a character, they are specifying an entry in the array. Like strings, arrays use zero-based indexing, so the first element in an array is element 0.There shouldn't be any spaces between the array name and the square brackets, like array [0]. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.
Example

    var array = [50,60,70];
    array[0]; // equals 50
    var data = array[1]; // equals 60

  -Create a variable called myData and set it to equal the first value of myArray using bracket notation.
```JavaScript
// Example
var ourArray = [50,60,70];
var ourData = ourArray[0]; // equals 50
// Setup
var myArray = [50,60,70];
// Only change code below this line.
var myData = myArray[0];
```

39.Modify Array Data With Indexes

Note: Unlike strings, the entries of arrays are mutable and can be changed freely.

Example

    var ourArray = [50,40,30];
    ourArray[0] = 15; // equals [15,40,30]

  -Modify the data stored at index 0 of myArray to a value of 45
```JavaScript
// Example
var ourArray = [18,64,99];
ourArray[1] = 45; // ourArray now equals [18,45,99].
// Setup
var myArray = [18,64,99];
// Only change code below this line.
myArray[0] = 45;
```

40.Access Multi-Dimensional Arrays With Indexes

Note: One way to think of a multi-dimensional array, is as an array of arrays. When you use brackets to access your array, the first set of brackets refers to the entries in the outer-most (the first level) array, and each additional pair of brackets refers to the next level of entries inside.There shouldn't be any spaces between the array name and the square brackets, like array [0][0] and even this array [0] [0] is not allowed. Although JavaScript is able to process this correctly, this may confuse other programmers reading your code.

Example
    var arr = [
      [1,2,3],
      [4,5,6],
      [7,8,9],
      [[10,11,12], 13, 14]
    ];
    arr[3]; // equals [[10,11,12], 13, 14]
    arr[3][0]; // equals [10,11,12]
    arr[3][0][1]; // equals 11

  -Using bracket notation select an element from myArray such that myData is equal to 8
```JavaScript
// Setup
var myArray = [[1,2,3], [4,5,6], [7,8,9], [[10,11,12], 13, 14]];
// Only change code below this line.
var myData = myArray[2][1];
```

41.Manipulate Arrays With push()

An easy way to append data to the end of an array is via the push() function. push() takes one or more parameters and "pushes" them onto the end of the array.For example:
   var arr = [1,2,3];
   arr.push(4);
   // arr is now [1,2,3,4]

  -Push ["dog", 3] onto the end of the myArray variable.
```JavaScript
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.push(["happy", "joy"]); 
// ourArray now equals ["Stimpson", "J", "cat", ["happy", "joy"]]
// Setup
var myArray = [["John", 23], ["cat", 2]];
// Only change code below this line.
myArray.push(["dog", 3]);
```

42.Manipulate Arrays With pop()

Note: Another way to change the data in an array is with the .pop() function. .pop() is used to "pop" a value off of the end of an array. We can store this "popped off" value by assigning it to a variable. In other words, .pop() removes the last element from an array and returns that element. Any type of entry can be "popped" off of an array - numbers, strings, even nested arrays.
    Example:
    var threeArr = [1, 4, 6];
    var oneDown = threeArr.pop();
    console.log(oneDown); // Returns 6
    console.log(threeArr); // Returns [1, 4]

  -Use the .pop() function to remove the last item from myArray, assigning the "popped off" value to removedFromMyArray.
```JavaScript
// Example
var ourArray = [1,2,3];
var removedFromOurArray = ourArray.pop(); 
// removedFromOurArray now equals 3, and ourArray now equals [1,2]
// Setup
var myArray = [["John", 23], ["cat", 2]];
// Only change code below this line.
var removedFromMyArray = myArray.pop();
```

43.Manipulate Arrays With shift()

Note: .shift() works just like .pop(), except it removes the first element instead of the last.

  -Use the .shift() function to remove the first item from myArray, assigning the "shifted off" value to removedFromMyArray.
```JavaScript
// Example
var ourArray = ["Stimpson", "J", ["cat"]];
var removedFromOurArray = ourArray.shift();
// removedFromOurArray now equals "Stimpson" and ourArray now equals ["J", ["cat"]].
// Setup
var myArray = [["John", 23], ["dog", 3]];
// Only change code below this line.
var removedFromMyArray = myArray.shift();
```

44.Manipulate Arrays With unshift()

Note: .unshift() works exactly like .push(), but instead of adding the element at the end of the array, unshift() adds the element at the beginning of the array.

  -Add ["Paul",35] to the beginning of the myArray variable using unshift().
```JavaScript
// Example
var ourArray = ["Stimpson", "J", "cat"];
ourArray.shift(); // ourArray now equals ["J", "cat"]
ourArray.unshift("Happy"); 
// ourArray now equals ["Happy", "J", "cat"]
// Setup
var myArray = [["John", 23], ["dog", 3]];
myArray.shift();
// Only change code below this line.
myArray.unshift(["Paul",35]);
```

45.Shopping List

  -Create a shopping list in the variable myList. The list should be a multi-dimensional array containing several sub-arrays.
The first element in each sub-array should contain a string with the name of the item. The second element should be a number representing the quantity i.e.["Chocolate Bar", 15] There should be at least 5 sub-arrays in the list.
```JavaScript
var myList = [
    ["tomatoes", 10],
    ["potatoes", 11],
    ["onions", 12],
    ["peppers", 13],
    ["garlics", 14]
];
```

46.Write Reusable JavaScript with Functions

Note: In JavaScript, we can divide up our code into reusable parts called functions. For example;

    function functionName() {
      console.log("Hello World");
    }

You can call or invoke this function by using its name followed by parentheses, like this:

functionName();

  -Each time the function is called it will print out the message "Hello World" on the dev console. All of the code between the curly braces will be executed every time the function is called.
```JavaScript
// Example
function ourReusableFunction() {
  console.log("Heyya, World");
}
ourReusableFunction();
// Only change code below this line
function reusableFunction(){
  console.log("Hi World");
}
reusableFunction();
```

```JavaScript

```

```JavaScript

```

```JavaScript

```

```JavaScript

```

```JavaScript

```

```JavaScript

```

```JavaScript

```
