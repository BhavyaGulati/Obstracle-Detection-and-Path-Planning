# Obstracle-Detection-and-Path-Planning
Worked on images to find obstacles and plan a path from start point to end point using a* algorithm.  Image processing was done with OpenCV to detect obstacles and start-end points.  Start-end points detection is done using skimage.

Run `main.py` to check the results.
You can edit the test image from main.py to see different results.

The `process_image.py` contains the major code.
Check that script to see the main functionality.
Follow the comments to undertand the code better.

`astarsearch.py` contains the implemenatation of A* search algo. 
`traversal.py` contains the script to traverse through the image to find objects/min path.
