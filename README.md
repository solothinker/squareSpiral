# Square Spiral

##squareSpiral B&W

This code will generate a square spiral in black and white color.
Number of possible colors in B&W is 0 to 255. The total number of combinations is 256
and it is equal to the square of 16. It is the image size.

Color filling starts in the following way  
1- from left top to right top  
2- from right top to right bottom  
3- from right bottom to left bottom  
4- from left bottom to left top but one pixel below

The above process repeats till it reaches the center. So the top left corner is black
and the center is white.

##squareSpiral coloured  

The color filling method is same as mentioned above. Here R,G,B color combination is used
to generate the spiral square. The possible combinations in R,G,B  
1- R,G,B  
2- R,B,G  
3- B,R,G  
4- B,G,R  
5- G,B,R  
6- G,R,B  

 

