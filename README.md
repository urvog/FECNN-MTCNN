# FECNN-MTCNN
## Facial expression recognition with MTCNN face detection

Human beings interact with each other no only though speech, but also body gestures, these gestures are important part of our communication, they transmit non-verbal signlas and play a relevant role in interpersonal relation ships.

## Objective
This project propose a CNN to detect human facial expressions like: anger, happiness, fear, sadness, disgust, surprise and neutral.


## Dataset

8638 image collection, size 80x80. Faces from childs, adults and elder people.

https://www.kaggle.com/datasets/kmirfan/micro-expressions

## EDA

## Model Architecture

 
CustomModel(
(conv1): Conv2d(3, 64, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
(conv2): Conv2d(64, 128, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
(conv3): Conv2d(128, 256, kernel_size=(3, 3), stride=(1, 1), padding=(1, 1))
(fc1): Linear(in_features=65536, out_features=1024, bias=True)
(fc2): Linear(in_features=1024, out_features=7, bias=True)
(pool): MaxPool2d(kernel_size=2, stride=2, padding=0, dilation=1, ceil_mode=False)
(dropout): Dropout(p=0.2, inplace=False)
)

## Results

## Conclusions

