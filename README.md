# Comparison_with_other_method_Sort
# Conventional-Rule-based-Method
# Multi-viewpoint-Patterns-and-Occlusions-Handling-Using-Hybrid-Features-for-Vehicle-Tracking

## Source code of vehicle tracking and Re-ID

### Authors



### Get Started
1. cd the folder where you want to download this repo
2. Run git clone https://github.com/dddd247/Multi-viewpoint-Patterns-and-Occlusions-Handling-Using-Hybrid-Features-for-Vehicle-Tracking.git
3. Install dependencise:
   * python >= 3.6
   * pytorch >= 0.4
   * opencv-contrib-python >= 3.4.1.15
   * opencv-python >= 3.4.1.15
   * colorsys
   * time
   * scipy
   * math
   * numpy
   * os, sys
4. Prepare dataset, VehicleMVO,
   Download the dataset from https://drive.google.com/drive/folders/1OER0lGggqaUzWJdxCDgxYkGsofvf8voU?usp=sharing
   you can put them into the file "Souce_video_bdd100k_video"
   #### There are ten different videos in this drive, we separate them into 2 parts: Day and Night coniditions.
   * Day_normal_1 -> Day_normal_5.mp4
   * night_video_1 -> night_video_5.mp4
5. Create a file and name it weight.
   Download the object detector weight, "yolov3.weight", and then put it into the file 
   
   
#### Run ( D_1 to D_5 and N_1 to N_5)
(1) Run the code on the command line. (from D_1 to N_5)
    
python sort_add_yolov3.py --input ./video/Day_normal_1.mp4 --threshold 0.23               
    
(2) You can change the '--input' to your test video's path.

(3) You can change the '--threshold' to adjust your performance.







