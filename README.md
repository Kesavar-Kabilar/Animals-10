# Animals-10
Using VGG16 and MobileNet to create a combined model to detect between 10 Different Animals with high accuracy
Data used from https://www.kaggle.com/alessiocorrado99/animals10

In order to run this program you will need to download the data from the above link and move the 
folder raw-img to the same directory as the python file.

This program downloads VGG16 Model, and MobileNet model and alters them to work on the 10 animals from the data set.
The VGG16 Model works with 90.15% accuracy and MobileNet works with 89.95% accuracy. I have also implemented a new method 
that combines both models by adding their predicted values. With this strategy I was able to implement a model 
with 93.9% accuracy. Hence creating a more accurate prediction but slower in time.
