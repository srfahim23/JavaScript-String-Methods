# JavaScript-String-Methods
In JavaScript, strings are used to represent and work with a 
sequence of charecters. A string can represent an object as well as the primitive data type. JavaScript automatically converts priitive strings to String so that it's possible to use String methods and access properties even for primite strings.

In this reference page, yo will find all String methods and properties available in JavaScript. For example, the toUpperCase() method returns the string converted to uppercase.


# JavaScript String length
In this tutorial, you will learn abbout the JavaScript String length property with the help of examples.

The length property returns the number of charecters in a string.

Example

    // defining a string
    let sentence = "I love Programming.";

    // returns number of charecters in the sentence string
    let len = sentence.length;

    console.log(len);

    //output:
    // 17


# length Syntax
The syntax of the length property is:

    str.length

Here, str is a string


# length Parameters
The length property does not take any parameters.

# Length Return Value
Returns the number charecters in a string.

Note: The string.length property returns the code 
units in the UTF-16 string format. Some rare string
charecters require two code units to be represented. Due to this, the length property might not always return the number of charecters.

# Example 1: Using length Property

    // defing string
    let string1 = "JavaScript";

    // returns the number of charecters in 'JavaScript'
    let len = string.length;

    console.log(len);


Output:

    10

In the above example, we have defined a string named string1. We have then used the length property to find out the number of charecters in string1.

Since 'Javascript' contains 10 charecters, string1.length returns 10