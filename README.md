# car_detection

To run project car detection. 

1. Install all dependency

2. Follow YAD2K GitHub to generate Yolo.h5
https://github.com/allanzelener/YAD2K

wget http://pjreddie.com/media/files/yolo.weights
wget https://raw.githubusercontent.com/pjreddie/darknet/master/cfg/yolo.cfg
./yad2k.py yolo.cfg yolo.weights model_data/yolo.h5

3. Make sure the yolo.h5 in folder model_data (should be done on step 2)

4. Run file cardetection.py via terminal, e.g. Python cardetection.py or Python3 cardetection.py
