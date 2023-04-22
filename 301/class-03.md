# Class 03 Notes

## Reading

### React Docs - lists and keys
1.	*What does .map() return?* <br>
An new array that is the same length as the array put into it. <br>
2.	*If I want to loop through an array and display each value in JSX, how do I do that in React?* <br>
Loop through the array with .map( ) and using the curly brackets for JSX. <br>
3.	*Each list item needs a unique ____.*<br>
key<br>
4.	*What is the purpose of a key?* <br>
Keys help React identify which items have changed, are added, or are removed. <br>
### The Spread Operator
1.	*What is the spread operator?* <br>
A quick syntax for adding items to arrays. <br>
2.	*List 4 things that the spread operator can do.* <br>
It can spread the array into different functions, copy an array, use an array as an argument or combine objects. <br>
3.	*Give an example of using the spread operator to combine two arrays.* <br>
If you had separate rosters of students and needed to combine them into one class. <br>
4.	*Give an example of using the spread operator to add a new item to an array.* <br>
If you needed to update an order and add an another item to the end. <br>
5.	*Give an example of using the spread operator to combine two objects into one.* <br>
If you had one object that contained address and contact information for a customer and the other object contained their purchase habits, you could combine them for market research. <br>
## Videos
### How to Pass Functions Between Components
1.	*In the video, what is the first step that the developer does to pass functions between components?* <br>
He uses the increment function. <br>
2.	*In your own words, what does the increment function do?* <br>
It passes thru the parent object creating a new array with an updated count. <br>
3.	*How can you pass a method from a parent component into a child component?* <br>
By using props to update the information in the state. <br>
4.	*How does the child component invoke a method that was passed to it from a parent component?* <br>
It updates the state of count in the iteration when the button is clicked. <br>
