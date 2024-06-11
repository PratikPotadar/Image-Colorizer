# Image-Colorizer
Black and white image colorization with OpenCV.

**Steps**
1. Load the model and the convolution/kernel points
2. Read and preprocess the image
3. Generate model predictions using the L channel from our input image
4. Use the output -> ab channel to create a resulting image

**Lab Colour**\n
Like RGB, lab colour has 3 channels L, a, and b. But here instead of pixel values, these have different significances i.e :

**L-channel:** light intensity
**a channel:** green-red encoding
**b channel:** blue-red encoding
