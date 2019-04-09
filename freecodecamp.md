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

31.
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

```JavaScript

```

```JavaScript

```
