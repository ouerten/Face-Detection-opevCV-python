# Face-Detection
Face Detection Application on Python with OpenCV, from photos or  videos

-Requires Docker and X Launch for Windows. (Or a Linux OS)<br />
-Necessary Libraries: imutils (pip install imutils)<br />

 <b>Face Detection Demo: </b><br />
 
 
 ```shell 
 python detect_faces.py --image rooster.Jpg -p deploy.prototxt.txt  -m res10_300x300_ssd_iter_140000.caffemodel
 ```

 <b>Video Face Detection Demo: </b><br /> 
 
  ```shell 
 python detect_faces_video.py -p deploy.prototxt.txt -m res10_300x300_ssd_iter_140000.caffemodel
   ```
   
 <b>Output: </b><br />
![alt text](https://github.com/ouerten/Face-Detection-opevCV-python/blob/master/vision/ExpectedOutput.png?raw=true)
