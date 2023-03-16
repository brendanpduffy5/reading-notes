# Class 11 Notes: Audio, Video, Images

## Video and Audio Content

*Explain how the ability to use video and audio on the web has evolved since the early 2000s.*<br>
Online Video Providers (OVPs) are now readily available and offer an easy way to host videos online and provide links for developers to put seamlessly integrate them into their webpages.<br>
*Describe the use of the src and controls attributes in the \<video> element.* <br>
The src attribute provides a path for the browser to read where the video is located.  The controls attribute can be your own or the browser’s own allows the user to play the video.  The controls attribute must at least have a way to start, stop, and adjust the volume.<br>
*Why is it important to have fallback content inside the \<video> element?* <br>
The fallback content is important to have so that if the browser is older or for some reason doesn’t support the video content, there is a link or a way for the user to view the content somewhere else.<br>
*Write a very short story where \<audio> and \<video> are characters.* <br>
\<video>: OMG THE COMPUTER IS BUFFERING AGAIN!! WHY IS IT ONLY 300MPS?!?!<br>
\<audio>: I don’t know why you’re so upset.  Back in my day we just got excited when we could see an image icon dance.  And then the mp3 revolution came!!<br>
\<video>: UGH!!!  You don’t understand!!  This is REALLY IMPORTANT!!<br>
\<audio>: I remember being your age once and everything…<br>
\<video>: [interrupts] NOOOOO!!!  I don’t want to hear about how hard you had it with dial-up at grandma’s house and whatever UHF was!  [leaves and slams door]<br>
*End scene.*<br>

## A Complete Guide To Grid

*How does Grid layout differ from Flex?* <br>
Flex was mostly designed for a layout in one dimension such as either a row or a column.  Grid was made for a two-dimensional layout with rows and columns at the same time.<br>
*Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.* <br>
>+ grid container – the item where display : grid is applied and the parent of all the grid items.
>+ grid item – the children and direct descendants of the grid container.
>+ grid line – the horizontal or vertical dividing lines that make up the structure of the grid.

## Responsive Images
*Besides making a site visually appealing across different screen sizes, why should developers make images responsive?* <br>
Developers should make images responsive so that the quality of the information that they are trying to convey to the user is not lost in the screen size transition.<br>
*Define the following \<img> attributes srcset and sizes. Write an example of how they are used.* <br>
The srcset attribute gives the browser a set of images to choose between and what size each image is.  The sizes attribute defines conditions (screen widths) and indicates which image size would be the best fit in which condition.<br>
*How is srcset more helpful for responsive images than CSS or JavaScript?* <br>
When a browser loads a page, it first goes through and downloads any images before it gets to the point where it is interpreting the CSS and/or JavaScript information.  By using srcset, developers avoid having images loaded twice or conflicting with the instructions in the JavaScript.<br>


[Back to home](../README.md)
