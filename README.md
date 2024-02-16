Questions
1. Do you see anything strange in the final result?
   - This image clearly illustrates that we have obtained information in two-dimensional form, and it is possible that the vehicle needs to move towards the "intersection point" of these lines.
     
3. Do you think the Hough transform resolution is important for obtaining a good result? Why?
   - Higher resolutions can potentially detect lines with more precision, but they also increase computational complexity. Lower resolutions may miss fine details in the image, resulting in
   - lower accuracy. Therefore, choosing an appropriate resolution is crucial for balancing accuracy and computational efficiency.
     
5. Do you think the Hough transform accumulator threshold is important for obtaining a good result? Why?
   - A higher threshold can lead to fewer detected lines but with higher confidence, while a lower threshold may detect more lines, including noisy ones. Setting the threshold too high
   - may cause missed detections, while setting it too low may result in false positives. Therefore, selecting an optimal threshold is essential for achieving a good balance between sensitivity and specificity in line detection.
