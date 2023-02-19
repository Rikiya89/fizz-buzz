# fizz-buzz
 
This code uses the p5.js library to create a canvas and display a series of messages that change based on the value of the frameCount variable, which increases by 1 for each frame that is drawn.

The canvas is set up in the setup() function, which specifies the size of the canvas (400 pixels by 400 pixels), sets the text alignment to be centered horizontally and vertically, sets the font size to 72 pixels, and disables the stroke for drawing shapes. The frameRate() function is also called to set the frame rate of the animation to 5 frames per second.

The draw() function is called repeatedly in a loop and is where the main logic of the program is implemented.

The first variable declared is message which is used to store the message that will be displayed on the canvas.

The program then checks whether the frameCount variable is divisible by 3 and/or 5 using the modulo operator (%). If it is divisible by both 3 and 5, the canvas is set to a red background and the text color is black. The message variable is set to "Fizz Buzz". If it is only divisible by 3, the background is set to green and the message is set to "Fizz". If it is only divisible by 5, the background is set to blue and the message is set to "Buzz". If it is not divisible by either 3 or 5, the background is set to a dark gray and the message is set to the value of frameCount.

Finally, the text() function is called to display the message on the canvas in the center of the screen.

Overall, this program implements the FizzBuzz problem, which is a classic programming challenge that involves printing a series of numbers from 1 to a given limit, but printing "Fizz" for multiples of 3, "Buzz" for multiples of 5, and "FizzBuzz" for multiples of both 3 and 5. In this particular implementation, the program uses an animation to display the messages and the limit of the sequence is not specified.
