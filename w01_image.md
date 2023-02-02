# dwsource_spring

1. Before looking closely into the code, describe what the program does.

The program displays the art.jpg image with some changes to the color depending on either how long the program has been running or the number of frames drawn so far. The blue value for each pixel starts at 0 and increases until it is reset to 0 again, repeating the cycle.

2. What data type is the art vairable?

art is a PImage datatype.

3. What is a PImage?

PImage is a datatype that tells the computer to intrepet the type of data it contains as an image.

4. What is art.pixels?

art.pixels is an array that contains the color values of each pixel in art.

5. What does image(art) do?

image(art) draws the image given as its input.

6. What does red(c) and green(c) do?

red(c) and green(c) return the red and green values of the color c, respectively.