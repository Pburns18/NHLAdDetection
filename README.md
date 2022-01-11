## National Hockey League Advertisement Detection

This project was created by me, Peyton Burns, in an effort to learn new technologies in the space of computer vision while reinforcing my prior machine learning and AI knowledge.

The goal of this project was to create a computer vision model that is able to detect and recognize advertisments that are displayed during broadcasts of National Hockey League games. 
This includes advertisements that are on the rink ice, rink boardings, and even advertisments displayed in the upper portion of the arena where fans are sitting. 
In order to create this model I gathered and annotated my own custom data set of 200+ images from NHL broadcasts. I then used the Yolov5 model in transfer learning on my own custom dataset
to create the final model. By doing this I was able to create a model which is able to achieve a recall of over 0.90 and a precision over 0.85 on the validation set.

Running the model on the test set porudced strong results, being able to detect almost all advertisements with confidence over 0.80. The model was able to acheive these results
while being tested on images from rinks the model had never seen before with advertisements that were also never seen to the model.

![alt text](https://github.com/Pburns18/NHLAdDetection/edit/main/AdDetections.png)
