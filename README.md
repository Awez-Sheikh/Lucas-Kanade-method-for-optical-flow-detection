# Lucas-Kanade-method-for-optical-flow-detection
The Lucas-Kanade Optical Flow is an algorithm used to estimate the motion (optical flow)
between two consecutive images based on the apparent motion of objects in the scene. Its one of
the most widely used methods in computer vision, especially for tracking objects or estimating
motion in video sequences.

# Lucas Kanade tracks motion mainly with these features -
● Brightness constancy: The pixel intensities at a point do not change between two
consecutive frames, i.e., the brightness of the object remains constant as it moves.
● Small motion: The displacement of pixels between the two frames is small, which means
the optical flow can be approximated using a linear model.
● Spatial coherence: Neighboring pixels have similar motion.
