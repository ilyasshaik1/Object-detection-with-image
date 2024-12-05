# Object-detection-with-image
# Object Detection with MobileNet-SSD

This project demonstrates object detection using the MobileNet-SSD model. It leverages OpenCV's DNN module to process images and detect objects. The model is trained on the COCO dataset and can detect 20 common objects, including people, cars, animals, and more.

## Features
- Object detection using the MobileNet-SSD model.
- Detects 20 classes of objects (e.g., person, car, dog, cat).
- Works on static images (images provided in the code).
- Efficient and lightweight for image-based applications.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- OpenCV (with DNN module support)

You can install the required Python libraries using pip:

pip install opencv-python
pip install opencv-python-headless


├── MobileNetSSD_deploy.caffemodel      # Pre-trained MobileNet-SSD model weights
├── MobileNetSSD_deploy.prototxt        # Model architecture
├── main.py                            # Python script to run object detection on image
├── README.md                          # Project documentation


![image](https://github.com/user-attachments/assets/3bd6f340-4605-4f50-9aa6-0a17854517cb)

![image](https://github.com/user-attachments/assets/cc24de5a-6178-449b-b089-d90f3126085f)


Licensing
MobileNet-SSD model: Licensed under the Apache 2.0 License.
COCO dataset: Licensed under CC BY 4.0 License.
This project: Licensed under the MIT License.
