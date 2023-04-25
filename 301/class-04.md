# Class 04 Notes

## React Docs - Forms
*What is a ‘Controlled Component’?*<br>
A Controlled Component is an input form element whose value is controlled by React state. <br>
*Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.* <br>
If we use the value attribute in our form element, the value we see will be this.state.value, which will automatically update the state as the user moves along and enters information.<br>
*How do we target what the user is entering if we have an event handler on an input field?* <br>
We can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name. <br>
## The Conditional (Ternary) Operator Explained
*Why would we use a ternary operator?* <br>
A ternary operator is a more efficient way to make a conditional statement in one line of code. <br>
*Rewrite the following statement using a ternary statement:* <br>
let value = x === y ? console.log(true); : console.log(false); <br>
