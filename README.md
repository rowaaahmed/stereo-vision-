# stereo-vision-
This repository presents an implementation of stereo vision–based disparity estimation using two classical stereo matching approaches: block matching and dynamic programming.

For the block matching approach, two widely used similarity metrics are implemented to compute the disparity map: Sum of Squared Differences (SSD) and Sum of Absolute Differences (SAD). These methods compare fixed-size windows between the left and right stereo images to determine the most likely pixel correspondences, offering a balance between computational simplicity and matching accuracy.

In addition to block matching, the repository includes a dynamic programming–based stereo matching method, which enforces smoothness constraints along image scanlines to produce more consistent disparity maps, particularly in regions with low texture or occlusions.

Overall, this repository serves as a practical and educational reference for understanding and comparing classical stereo matching techniques, highlighting the trade-offs between accuracy, robustness, and computational cost in disparity estimation.
