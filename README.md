# ascii_donut

This code generates an ASCII art animation of a rotating donut. It utilizes HTML, JavaScript and CSS to create the art and animate it within a web page (hosted with Github Pages). Below an overview of the code. It is available on the website : https://thartet.github.io/ascii_donut/

## Code Overview 
The JavaScript code does the following:
* Initialises variables to controle the donut's shape and animation parameters
* Defines a function **renderAsciiFrame** that generates a single frame of the ASCII art donut and updates the HTML element with the result.
* Calls **renderAsciiFrame** to display the initial frame of the donut
* Sets up event listeners to start the animation when the page loads and to update the frame when the window is resized

## Animation parameters
You can customize the appearance and animation of the donut by adjusting the following variables:

* A and B: Angles that control the rotation of the donut.
* R1 and R2: Radii that determine the donut's size.
* K1 and K2: Constants that affect the animation.

Feel free to experiment with different values to create your own unique donut animations.

## Notes
The code uses trigonometric calculations to create the donut's shape and achieve the rotation effect.

The ASCII characters used to represent different shades of the donut are stored in the string **".,-~:;=!*#$@"**. The choice of characters contributes to the visual effect of the donut.

