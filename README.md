# Lane-Detection-Using-OpenCV
Lane detection using OpenCV is a computer vision technique that allows you to identify and track the lanes of a road in a video stream or an image.

Steps:

1. Load the video stream or image: Use the OpenCV library to load the video stream or image into your program.

2. Convert to grayscale: Convert the video stream or image to grayscale. This reduces the number of colors and simplifies the image, making it easier to process.

3. Apply Gaussian blur: Apply a Gaussian blur to the grayscale image to smooth out any noise and reduce the number of edges.

4. Apply Canny edge detection: Use the Canny edge detection algorithm to detect edges in the image. This algorithm identifies the significant changes in intensity between adjacent pixels, which correspond to the edges of the lane markings.

5. Create a region of interest (ROI): Define a region of interest that includes only the portion of the image where the lanes are located. This helps to reduce false positives and improve the accuracy of the lane detection.

6. Apply Hough transform: Use the Hough transform algorithm to identify the lines that represent the lanes in the ROI. This algorithm converts the edge points into lines in parameter space and then looks for intersections of these lines, which correspond to the lanes.

7. Draw the detected lanes: Use the parameters of the detected lines to draw the lane markings on the original image or video stream.
