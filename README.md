This code takes Leonardo Da Vinci pieces cut into vertical strips as an input (the strips can be out of order and/or rotated 180 degrees) and outputs the correct image.
It was the final project for my Image Processing class. I used a very simplistic method for the image processing side of things by simply comparing the edges of the strips
until I found a pair of edges with a small total difference in their values. Then with some fun logic I recursively put the images together.
I call it The Da Vinci Code.
