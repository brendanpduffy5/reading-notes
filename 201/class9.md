# Class 9 Notes: Forms and JS Events

## HTML Forms - Your first Web Form. How To Structure A Web Form.

*Why are forms so important in web development?*

They allow the users to submit information and interact with the website.

*When designing a form, what are some key things to keep in mind when it comes to user experience?*

>+ Don’t make the form to long or frustrating or you increase the risk of losing users. 
>+ Keep the information clear and easy to understand.
>+ Check for Accessibility so that anyone using a screen reader can have a good experience
>+ Make sure to group together fields that make sense to belong together to make it easier to read.

*List 5 form elements and explain their importance.*

\<form> is the container element that defines the space of the form. <br>
\<label> is user facing name we are giving to the input we are requesting. <br>
\<input> is the name of the field that the user will put information into. <br>
\<textarea> is an open box area where the user can add text to display a message. <br>
\<button> allows users to interact and control an aspect of the website.  Whether it is submitting a form or just prompting to go to the next page, it provides feed back so that the user can affect the page.<br>

## Learn JS - Introduction To Events.

*How would you describe events to a non-technical friend?*

Events are any actions that happen while the user is experiencing the program we write.

*When using the addEventListener() method, what 2 arguments will you need to provide?*

>+ the string “click” or something to show acknowledge the user’s action
>+ a function that will be called when the event happens

*Describe the event object. Why is the target within the event object useful?*

The event object is automatically passed to event handlers to help deliver more features.  The event object’s target property is always a reference to the element the event occurred upon.  This allows for consistency and makes it easier to work with.

*What is the difference between event bubbling and event capturing?*

Event bubbling refers to how a browser handles events that are targeted at nested elements.  It starts on the innermost element and the on to less nested elements.

Event capturing starts with the least nested element and then moves on to more nested elements until the target is reached.


[Back to home](../README.md)
