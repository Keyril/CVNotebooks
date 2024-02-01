# CVNotebooks
A collection of Computer Vision related Jupyter Notebooks for the purpose of learning  and applying CV concepts.

CSC420: Introduction to Image Understanding - originally taught by Sanja Fidler:

    Assignment 2:
    - Implementing Seam Carving using the connected path of pixels that sum to the smallest local gradient.

    Assignment 3: 
    - Harris corner detection
    - SIFT detecting keypoints/descriptors
    - KNN for finding matches
    - Computing Homography matrix between a reference image and example from a real-world environment
    - Using computed homography matrix to find the border of the reference image in the environment
    
    Assignment 4:
    - Implemented a function that stitching two images into a panorama (img1: left, img2: right):
        - SIFT for detecting keypoints/descriptors
        - FLANN for finding matches
        - RANSAC algorithm for finding best homography matrix (written from scratch)
            - computing homography matrix (written from scratch)
            - checking Least Square Distance error for each iteration of the homography matrix to count inliers
        - warp 2nd image to match alignment to 1st (cv2.warpPerspective)
        - stitch 1st image and warped 2nd image to create an accurate panorama
    NeRF Project:
    - Implemented NeRF on a captured dataset
    - Full paper explaining the process can be found in the project folder