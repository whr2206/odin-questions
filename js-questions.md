**JAVASCRIPT CONCEPT REVIEW**  
  
    
1. What are the 8 data types in JavaScript?
  
  > **number** - For numbers of any kind.  
  **bigint** - For integers of arbitrary length.  
  **string** - For strings.  
  **boolean** - For true/false statements.  
  **null** - For unknown values.  
  **undefined** - For un assigned values.  
  **object** - For complex data structures.  
  **symbol** - for unique identifiers.  
    
2. Which data type is NOT primitive?  
  
>Objects are not primitive.  

3. What's the relationship between null and undefined?  

>Null is an object with a valid, non-existant value. An object type of undefined is in itself, undefined.  

4. What's the difference between single, double, and backtick quotes for strings?  

>There is no difference between single and double quotes. Backtick quotes are useful because then you can use single and double quotes inside the string without using "\" as an escape.

5. What's the term for embedding variables/expressions in a string?  

>Template literals?

6. Which quotes let you embed variables/expressions in strings?

>Backtick quotes

7. How do you embed variables/expressions in a string?  

>Use ?{variablename} wrapped in `  `. For example  
```
console.log(`Last weekend, ?{firstName}` was in charge.); 
```
8. How do you escape characters in a string?  

>By using \ to procede it.
```
console.log('I\'m a bit hungry today!);
```
9. What are methods?

>Methods are actions that can be performed on objects. A JavaScript method is a property containing a function definition.  

*Note: Don't understand*  
  
10. What is the difference between slice/substring/substr?

>These functions pick out parts of an existing string.  

> **substring** - Any number less than 0 is treated as 0. If indexEnd < indexStart, the two are swapped.    

>**substr** - Is considered a lega function. With substr, a negative value will result in the count starting at the end of the string. Substring uses start & end while substr uses start AND LENGTH.  
  
>**slice** - Incorporates the strengths of both substr and substring. It can take both the start and end indices as parameters.  

11. What are the three logical operators and what do they stand for?  

>**&&** - Means and  
**||** - Means or  
**!** - Means not  

12. What are the comparison operators?  

> **<** - less than  
 **<=** - less than or equal to  
 **>** - greater than  
 **>=** - greater than or equal to  
 **==** - equal to  
 **===** - strict quality (value and data type)  
   
13. What are truthy and falsy values?  

>Truthy values are considered true when encountered in a boolean context. All values are truthy unless defined as falsy.  
  
*Note: Don't understand*  
  
14. What are conditionals?  

>Statements such as "if else" "if else if else". These control the order in which statements are executed in a script.  
  
15. What is the syntax for an if/else conditional?
```
const isWorkDone = false;

if (isWorkDone) {
    console.log ('The work is done!);
}
else {
    console.log ('You're not done yet!);
}
```  

16. What is the syntax for a switch statement?
```
const food = "pizza";

switch (food) {
    case 'burger':
        console.log("Yummy. Cow.");
        break;
    case 'tacos':
        console.log("Love me some tacos.");
        break;
    default:
        console.log("Pizza is the answer.");
}
```
17. What is the syntax for a ternary operator?
```
let price = 20000;
let day = "Friday";

day === "Friday" ? price -=1.5 : price +=1.5;
```  
18. What is nesting?  

>When you write a function inside a function. Or in HTML, when you give an element tags inside an existing pair of tags.