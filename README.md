# Edge-YOLO-Algorithm
The edge computing neural network based on Darknet is easy to be deployed at the edge and has high accuracy.We can easily use edgeyolo for mask detection
## Get Started
Training
We used AlexeyAB's Darknet train our model.
Install Darknet here.
```
https://github.com/AlexeyAB/darknet.git
```
## Dataset
Download our mask dataset or Coco dataset for training
```
https://github.com/Adam123wu/Edge-YOLO-Algorithm
```
## Change type
Use scripts to convert data sets into data that can be recognized by Darknet(Don't forget to modify the address information!)
```
python3 voc_label_mask.py
```
## Training

Now you need to install step by step according to the installation method of Darknet, and use our cfg file as they do.

