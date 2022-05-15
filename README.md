# Emotion-Classification-by-Segmented-Facial-Expressions

Final project for DS301- Advanced Topics in Data Science<br>
Quristoff Jiang<br>


Emotion recognitions by facial expressions are relying on the complete images of face. However, complete images of faces are not often available.<br>
This project try to finetune models pre-trained on complete images of faces to classify emotions of segmented faces.<br>
## Link to models
models<br>
https://drive.google.com/drive/folders/1HgExD9omvRpiouxGjaiT309c6uavawaO?usp=sharing
<br>demo<br>
https://colab.research.google.com/drive/14d-H2KDDsqAMbLzWeVZNl9aX1g4xwCET?usp=sharing

## Face Segmentation
![alt text]()


## Summary
The upper face model achieved an accuracy of 0.72<br>
The lower face model achieved an accuracy of 0.66<br>

## Conclution
Our models show that:<br>
-Upper and lower faces both have some capacity of predicting emotions, while both of their capacities are not strong<br>
-Upper face performs slightly better than lower face<br>
-By combining the softmax activation score of upper face and lower face, a higher score of accuracy can be achieved. But the accuracy is still lower than using the complete face<br>
-Though different parts of faces can signify some emotions, emotion detection using facial recognition relies on interaction and combination between different parts of the face<br>
<br>
The model performance can be improved by:<br>
-Using better models (VGG, ResNet)<br>
-Training for more epochs using cyclic learning rate schedules<br>
-More balanced and accurately annotated data, or applying methods coping with imbalance and bias in annotation<br>
