# FISH CLASSIFICATION 
<br><br>
## Entrance

This dataset contains 9 different seafood types collected from a supermarket in Izmir, Turkey
for a university-industry collaboration project at Izmir University of Economics, and this work
was published in ASYU 2020.
The dataset includes gilt head bream, red sea bream, sea bass, red mullet, horse mackerel,
black sea sprat, striped red mullet, trout, shrimp image samples.<br>

Authors: O. Ulucan, D. Karakaya, M. Turkan
Department of Electrical and Electronics Engineering, Izmir University of Economics, Izmir, Turkey<br><br>
https://www.kaggle.com/datasets/crowww/a-large-scale-fish-dataset/data


## About The Project

First, the data was analyzed using some exploratory data analysis steps to gain more information about the data.
For example, a visualization of data from each class was made. In addition, the number of data in each class was visualized with 'pie'.<br><br>
The second step is to prepare the data for training. The data was separated as 70% training and 30% validation and the normalization process was performed.<br><br>
The third step is to establish the artificial neural network structure. An artificial neural network consisting of an input layer, three hidden layers and an output layer was designed.

![image](https://github.com/user-attachments/assets/929da093-7b6b-4deb-83b2-ff4c46d05352)

The model was trained with the Adam optimization algorithm and lasted for 20 epochs.

## Result

The training result was successful at the desired level. 92% accuracy and 22% loss value were obtained.

![image](https://github.com/user-attachments/assets/69268569-c40f-42d2-bbbf-852d0ec44cf8)

The project was developed on Kaggle.<br>
Kaggle notebook link:  https://www.kaggle.com/code/mehmetcantemir1/deep-learning-bootcamp-project/edit
