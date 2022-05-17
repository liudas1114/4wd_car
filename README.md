# 4wd_car Raspberry pi 4wd_car

Watch how TF model working and basic car moves [Raspberry pi Car].
[Raspberry pi Car]: https://youtu.be/1NgvWW8Pqis


* Create new folder

```
cd ~/Desktop/(folder name)/
```

```python
git clone https://github.com/liudas1114/4wd_car.git
```

### Go to folder
```
cd 4wd_car
```

### Install all libraries
```python
pip3 install opencv-python
sudo apt-get install libhdf5-dev
sudo apt-get install libhdf5-serial-dev
sudo apt-get install libatlas-base-dev
sudo apt-get install libjasper-dev
echo "deb https://packages.cloud.google.com/apt coral-edgetpu-stable main" | sudo tee /etc/apt/sources.list.d/coral-edgetpu.list
curl https://packages.cloud.google.com/apt/doc/apt-key.gpg | sudo apt-key add -
sudo apt-get update
sudo apt-get install python3-tflite-runtime
```

### Run detect.py
```
python3 detect.py
```
If you want quit press ```q```


### Changes
In line 68 can change tolerance, at what minimum percentage show object detection. Right now 0.2 = 20%

#### res = detect_objects(interpreter, img, ```0.2```)

### Always can test just showing this pictures
![alt text](https://github.com/liudas1114/4wd_car/blob/main/Test%20photos/brick.png "Brick")


![alt text](https://github.com/liudas1114/4wd_car/blob/main/Test%20photos/stop.jpg "Stop")
