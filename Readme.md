# Reference  
https://github.com/chenyr0021/camera_calibration_tool

# Usage  
This code can be used to calculate calibration matrix and distortion coefficients of your camera now.   

## Calibration   
1. Prepare more than 10 images of chessboard photoed by your camera in different position and direction.  
2. Be sure they are in the format of 'JPG' or 'jpg' or 'png'. (They are better to be in the same format, because I do not know if it will work or not.)    
3. Put them in a folder named chess which should be in the same directory as calibration.py.   
4. Run Terminal in current directory:   
```python3 calibration.py --image_size 1920x1080 --mode calibrate --corner 8x6 --square 20```  

**Replace the value according to your camera and chessboard.**  

Your camera parameters will saved in a xml file named `camera_params.xml`.
