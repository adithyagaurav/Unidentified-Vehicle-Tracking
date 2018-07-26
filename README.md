# Unidentified-Vehicle-Tracking
Objective of this project is to develop a Computer Vision algorithm in MATLAB to track a single
unrecognized vehicle in a video stream using its features even in the presence of other similar
targets and occlusions, and detect suspicious activity (if any) over a IP Camera Network in real
time. 

This project/ research work is a part of an M.tech. Thesis project of ECE department, Govind Ballabh Pant University of Agriculture & Technology. The development code cannot be revealed as the research work is under review for possible publication in a scientific journal. The output images elaborate the results obtained.

The algorithm was tested for tracking capabilities under six cases of increasing complxities:
Case 1: The vehicle in the case is alone in the frame and does not undergo any occlusion. (Depicted by single_no_occlusion.png)
Case 2: There are multiple vehicles in the frame, however algorithm succesfully tracks only the unidentified target vehicle which doesn't undergo any occlusion (Depicted by multiple_no_occlusion.png)
Case 3: The vehicle is alone however it undergoes a partial occlusion (Depicted by single_partial.png)
Case 4: There are multiple vehicles in the video frame, however algorithm successfully tracks only the unidentified target vehicle even after it undergoes a partial occlusion. (Depicted by multiple_partial.png)
Case 5: The vehicle is alone however it undergoes a complete occlusion (Depicted by single_complete.png)
Case 6: There are multiple vehicles in the video frame, however algorithm successfully tracks only the unidentified target vehicle even after it undergoes a complete occlusion. (Depicted by multiple_complete.png)


The algorithm was tested for suspicious activity detection capabilities for two different criteria:
Criteria 1: If the target vehicle moves through the stream with an abnormally slow speed. (Depicted by suspicious_slow_speed.jpg)
Criteria 2: If the target vehicle moves through the stream with an abnormally non uniform motion (repeated stops and starts). (Depicted by suspicious_abnormal_motion.jpg)
