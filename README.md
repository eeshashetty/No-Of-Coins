# Counting the number of coins using OpenCV

Reference Tutorial:

https://www.pyimagesearch.com/wp-content/uploads/2018/05/opencv_tutorial_ar_resize.jpg

(they have a tutorial on counting the number of tetris blocks, almost the same logic)


_Faced an error in some images where even a tiny edge was detected as a coin, so used approxPolyDP to determine whether the contour was a circle or not._

(based on my data, length of the function was more than 10 for a circle, and less than that was an edge.)
