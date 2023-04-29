# Class 05 Notes

## React Docs - Thinking in React
*What is the single responsibility principle and how does it apply to components?*<br>
The single responsibility principle is the idea that each piece of code should only serve one purpose or do one thing.  It applies to components, in that each component should only do one thing, otherwise it should be broken down into smaller components.  <br>
*What does it mean to build a ‘static’ version of your application?*<br>
It means that it is a best practice to first build a version of your application including its structures, but to not add interactivity until the structure is fully worked out. <br>
*Once you have a static application, what do you need to add?*<br>
Then you can add interactivity so that the user can accomplish the functional purpose of the app. <br>
*What are the three questions you can ask to determine if something is state?*<br>
>+ Does it remain unchanged over time? If so, it isn’t state.
>+ Is it passed in from a parent via props? If so, it isn’t state.
>+ Can you compute it based on existing state or props in your component? If so, it definitely isn’t state! <br>
*How can you identify where state needs to live?*<br>
Find the closet parent component and test to see if that works.  You could also put state in a common component above the parent component.  And if you can’t find one that works that way, you can create a new component simply for the purpose of holding the state. <br>
## Higher-Order Functions
*What is a “higher-order function”?*<br>
Higher-order functions are functions that operate on other functions, either by taking them as arguments or by returning them. <br>
*Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?*<br>
It is saying to return m when m has a value that is greater than n. <br>
*Explain how either map or reduce operates, with regards to higher-order functions.*<br>
When an array is transformed by the map method, the array is “mapped” into a new form of an array with the same length by the function. <br>
