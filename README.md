## National Hockey League Advertisement Detection

This project was created by me, Peyton Burns, in an effort to learn new technologies in the space of computer vision while reinforcing my prior machine learning and AI knowledge.

The goal of this project was to create a computer vision model that is able to detect and recognize advertisements that are displayed during broadcasts of National Hockey League games. 
This includes advertisements that are on the rink ice, rink boardings, and even advertisments displayed in the upper portion of the arena where fans are sitting. 
In order to create this model I gathered and annotated my own custom data set of 200+ images from NHL broadcasts. I then used the Yolov5 model in transfer learning on my own custom dataset
to create the final model. By doing this I was able to create a model which is able to achieve a recall of over 0.90 and a precision over 0.85 on the validation set.

Running the model on the test set produced strong results, being able to detect almost all advertisements with confidence over 0.80. The model was able to achieve these results
while being tested on images from rinks the model had never seen before with advertisements that were also never seen to the model.

![alt text](https://github.com/Pburns18/NHLAdDetection/blob/main/AdDetections.png)

### Built With

* [Python](https://www.python.org/)
* [Yolov5](https://github.com/ultralytics/yolov5)
* [PyTorch](https://pytorch.org/)
* [OpenCV](https://opencv.org/)
* [Roboflow](https://roboflow.com/)

### Getting Started & Usage
For ease of use I have created a [Jupyter Notebook](https://github.com/Pburns18/NHLAdDetection/blob/main/NHLAdDetectionInterface.ipynb) to easily interfacte with the created model. The easiest way to run this notebook would be to use Google Colab, and simply run all of the code within the notebook. The notebook will set up the environment, download 
the trained model, display some examples and training results, and run an example test detection session.

### Contact
Peyton Burns - peyton.burns.j@gmail.com
NHL Ad Detection - [https://github.com/Pburns18/NHLAdDetection](https://github.com/Pburns18/NHLAdDetection)

#### Disclaimer
I do not own any of the images of National Hockey League used in training and detection of the model. These images are being used purely for educational purposes 
to train a model that will not be used for profit or to circumvent National Hockey League copyrights. Authors Guild V. Google provides precedent for this scenario. 
