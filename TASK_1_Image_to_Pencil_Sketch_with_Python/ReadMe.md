I have done this project as task 1 for the data analysis internship from letsgrowmore
Task 4:Image to Pencil Sketch with Python
Level: Beginner
Domain: Data Science Intern
Programming Language: Python 
IDE: Google Colab
We need to read the image in RBG format and then convert it to a grayscale image.
This will turn an image into a classic black and white photo. 
Then the next thing to do is invert the grayscale image also called negative image, this will be our inverted grayscale image.
Inversion can be used to enhance details. Then we can finally create the pencil sketch by mixing the grayscale image with the inverted blurry image.
This can be done by dividing the grayscale image by the inverted blurry image. 
Since images are just arrays, we can easily do this programmatically using the divide function from the cv2 library in Python.
"Muskman.jpg" is a sample image used for educational purpose. Credit of the image goes to respective owner.
