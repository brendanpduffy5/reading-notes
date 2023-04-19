# Class 02 Notes
## Reading

*Based off the diagram, what happens first, the ‘render’ or the ‘componentDidMount’?* <br>
The ‘render’ phase happens before the ‘componentDidMount’. <br>

*What is the very first thing to happen in the lifecycle of React?* <br>
The constructor in the Mounting phase is the first thing in the lifecycle of React.<br>

*Put the following things in the order that they happen: componentDidMount, render, constructor, componentWillUnmount, React Updates* <br>
 constructor, render, React Updates, componentDidMount, componentWillUnmount <br>

*What does componentDidMount do?* <br>
componentDidMount helps the dev load anything using a network request or initialize the DOM.<br>


## Videos

*What types of things can you pass in the props?* <br>
You can pass things in the props things that you want to render and/or pass into a function in the component like an initial count or a name or title that might change. <br>

*What is the big difference between props and state?* <br>
The main difference is that props are pass into a component and state is handled inside of the component.  So elements in state are updated in the component and props must be updated outside the component.<br>

*When do we re-render our application?* <br>
When the state is changed inside of the application, the component of the application will be re-rendered.<br>

*What are some examples of things that we could store in state?*
We could store things that need to be updated based on things that the user does, like a counter or personal information in a form that the user updates.<br>
