# happiness-detector
An OpenCV application to detect faces that exhibit happiness using pre-Trained Haar Cascades.

## Methodology:
Here, Python 3.6 is used and OpenCV package had been used for training and detection.

Basically the steps followed are as follows:

- Initially the video frame from our webcam is read using OpenCV package.
- Then using the pre-trained classifiers, we detect the face and smile through OpenCV functions and user defined functions.
- Then the images with red rectangles around detected face are returned and displayed continuously in video format.
- If smile is detected, the rectangle turns green and will be labelled 'happy'.

### Detection process:

- The image is initially converted to greyscale for easy computations.
- Then the haar-like features are checked using classifiers on this grey-scale image matrix.
- Those frames, which pass the threshold value are detected as faces and smiles.
- Then, these rectangles are drawn over the coloured image in the same location and displayed.
- We perform this process using user defined function and OpenCV package.

