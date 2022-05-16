# 4wd_car Raspberry pi 4wd_car

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





