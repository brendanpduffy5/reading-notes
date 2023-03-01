# Class 8 Notes - Readings: CSS Layout

## Learn CSS - Flexbox

*Flexbox is designed for one-dimensional content. Explain what this means.*

Flexbox can process a bunch of items that are different sizes and return the best possible combination of how to display them. It can help a sidebar so that it evenly condenses the sidebar while keeping it readable and in a presentable format.  

*Explain the difference between the main axis and cross axis.*

In Flexbox, the main axis is set by the flex-direction property and you choose for that to either go along a row or a column.  The cross axis runs perpendicular to the main axis.

*How can using certain properties of flexbox negatively impact accessibility?*

The row-reverse and column-reverse values change the visual order, but do not change how they are logically written in the code.  As a result, they can switch the order in which a screen reader would navigate the options, so we should always test and trouble shoot for accessibility options before finalizing the code with Flexbox.

## CSS Layout - Flexbox

*What are some advantages of using flexbox over float?*

>+ You can vertically center a block of content inside its parent
>+ You can make all of the children of a container take up an equal amount of the available width and/or height, regardless of how much is available
>+ You can make all columns in a multiple-column layout have the same height whether they have the same amount of content or not.

*How does this topic connect with your long term goals?*

I think overall flex allows for a much cleaner and more professional look.  So therefore, anyone who can use it tastefully will look like an inherently better developer from the end user perspective.  Also, it seems like it might be a little easier and I like easy.


[Back to home](../README.md)
