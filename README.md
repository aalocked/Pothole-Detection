
# Pothole Detection using Yolov5

This project uses YOLOv5, a popular object detection algorithm, to detect potholes in real-time using a camera module attached to a Raspberry Pi 4. The GPS sensor on the Raspberry Pi 4 logs the coordinates of the potholes as they are detected and sends them to the central department for repair.



## Installation




- Clone the repository to Raspberry Pi 4

```bash
  git clone https://github.com/aalocked/Pothole-Detection.git

```
- Install the required packages
```bash
cd Pothole-Detection
pip install -r requirements.txt

```

## Usage
- Connect the camera module and GPS sensor to your Raspberry Pi 4
- Run the following command to start the script. 
```bash
python detect.py
```

## License
This project is licensed under GNU General Public License v3.0 

