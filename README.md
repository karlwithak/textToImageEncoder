textToImageEncoder
==================

Two sister scripts that can convert text to an image and back to text. <br>
It can take any characters in the 256 character extended ascii table. <br>
The size of the created image depends on the length of the text, the ratio is 3 characters to 1 pixel. <br>
For example, 300 characters (a bit over 2 tweets) would be converted into a 10x10 square of 100 pixels, <br>
&nbsp;&nbsp;&nbsp; taking up aproximately the same screen space as a single character.


textToImage
------------
Converts inputted text to an image. This image can then be used with the sister tool to convert back to the original text


imageToText
------------
To be used to convert an image back to original text.
