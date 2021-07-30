# Capstone-Project__age-and-gender-prediction

THIS PROJECT IS TO PREDICT AGE AND GENDER.

I have use the wiki dataset to predict age and gender. You can download the dataset from the link below.

https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/

TRAINING.ipynb file contain the training code.

TESTING.ipynb file test the model.

inference_live_feed.py  is file which  take live image of a person to test the gender.

# To run the inference file.

I have run this on Windows. I have not tried this on linux and OS.


Download js.model file from below link.(This file is saved in my drive file. you can download it from here.)


https://drive.google.com/file/d/1HbpZsfUPncZXooqoAppn9VqyVmXLI7zJ/view?usp=sharing


Open Anaconda Prompt

Write python inference_live_feed.py

Thats it.

# To run the code.

git clone https://github.com/sakshamgupta1802/Capstone-Project__age-and-gender-prediction.git

Run Training.ipynb file  on Jupyter Notebook.


Run Testing.ipynb file on Jupyter Notebook.


Run inference_live_feed.py 


Thats it.


# limiting case


# 1.)    images in which face is not proper visibile will may fail in the model.
for example : 


![505102_1964-12-19_2007](https://user-images.githubusercontent.com/60683274/127667883-fa539e82-c5cf-431d-8720-44c1994538a6.jpg)


# 2.)     images in which male person can do makeup will may fail in the model.

for example in below image he is a male but due to makeup model will predict him a female.

![dream girl 2](https://user-images.githubusercontent.com/60683274/127668812-4b7ef823-2b3f-415b-97c5-6ac395bc2a9d.jpg)

