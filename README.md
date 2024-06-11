# Image-Colorizer
Black and white image colorization with OpenCV.

**Steps**
1. Load the model and the convolution/kernel points
2. Read and preprocess the image
3. Generate model predictions using the L channel from our input image
4. Use the output -> ab channel to create a resulting image

**Lab Colour**
Like RGB, lab colour has 3 channels L, a, and b. But here instead of pixel values, these have different significances i.e :

_**L-channel:**_ light intensity
_**a channel:**_ green-red encoding
_**b channel:**_ blue-red encoding
