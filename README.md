# Square Spiral
squareSpiral B&W - This code will generate a square spiral in black and white color.
Number of possible colors in B&W is 0 to 255. The total number of combinations is 256
and it is equal to the square of 16. It is the image size.

Color filling starts in the following way
1- from left top to right top
2- from right top to right bottom
3- from right bottom to left bottom
4- from left bottom to left top but one pixel below

The above process repeats till it reaches the center. So the top left corner is black
and the center is white.
