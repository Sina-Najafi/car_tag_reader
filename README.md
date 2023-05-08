## Intoduction
As the name of the repo suggests in this project me and my friend Erfan Norouzi have created a **license plate** reader. it recieves an image of the car and 
extracts the plate characters. the project consists of three different parts that altogether do the job for us:
- plate_localizer: this model recieves as input an image of a car and specifies where in the image is the plate.
- character_seperator: it recieves an image of a plate and localizes all the 8 characters of the plate.
- character_reader: it recieves an image of a character and returns whatever character it finds in the image. we pass 8 characters of a plate to this model and 
this way we finally read the plate.

***Attention: I used this online free annotation tool for this project to create the labels: https://imglab.in/***

