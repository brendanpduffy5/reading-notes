# Class 3 Notes


## Learn HTML

### Ordered and Unordered lists

*1. When should you use an unordered list in your HTML document?*
when the order of the items is not meaningful

*2. How do you change the bullet style of unordered list items?*
by nesting the list with indentations

*3. When should you use an ordered list vs an unorder list in your HTML document?*
ues an ordered list when the order is important and the meaning of the list would change if you changed the order of the items.

*4. Describe two ways you can change the numbers on list items provided by an ordered list?*
by adjusting the type attribute to i for lowercase Roman numerals or to I for uppercase Roman numerals.

## Learn CSS

### The Box Model

*1. Describe the CSS properties of margin and padding as characters in a story. What is their role in a story titled: “The Box Model”?*
Margin is a magic forcefield that pushes the border out to a specific distance from the content in accordance with the spell.  The padding is a very thin and flexible armor that allows the border to come right up to the content area but not cross it.

*2. List and describe the four parts of an HTML elements box as referred to by the box model.*
    >+ margins- clear the area outside of the border
    >+ borders- a boundary that goes around the padding and the content
    >+ padding- is transparent and clears the area around the content
    >+ content- the text or images displayed in the box

## Learn JS

### Arrays. Operators and Expressions. Conditionals. Loops

*1. What data types can you store inside of an Array?*
elements of the same data type

*2. Is the people array a valid JavaScript array? If so, how can I access the values stored? If not, why?*

No because there are strings mixed with numbers.  You could add quotes around the numbers making them strings and then it would work.

*3. List five shorthand operators for assignment in javascript and describe what they do.*

Addition assignment 	x += f()	x = x + f()
Subtraction assignment	x -= f()	x = x - f()
Multiplication assignment	x *= f()	x = x * f()
Division assignment	x /= f()	x = x / f()
Remainder assignment	x %= f()	x = x % f()

*4. Read the code below and evaluate the last expression and explain what the result would be and why.*

 let a = 10;
 let b = 'dog';
 let c = false;

 // evaluate this
 (a + c) + b;

(10 + false) + dog = (false) + dog = false

*5. Describe a real world example of when a conditional statement should be used in a JavaScript program.*
A wake up alarm app could play music on weekedays at 7:00 AM, but be instructed to not go off until 9:00 AM on the weekends.

*6. Give an example of when a Loop is useful in JavaScript.*
If you wanted to have an app count down to a special day, you would have it run the loop and display a message each day until the special day.

[Back to home](../README.md)
