# Face_Recognition

Program to train a machine learning model to know your face and identify it using the Raspberry Pi camera module.

Before running any code make sure you have a directory adjacent to the code named "dataset", in that directory you will make a folder with your name. Also go into the headshots_picam.py code and replace my name ("Jessie") with the name you used for the folder.

Now you can run headshots_picam.py to take some pictures of your face by pressing c in the pygame window, try using a variation of lighting and angles for better results. Once you are done quit by pressing q in the pygame window.

Next run train_model.py to train the machine learning model to learn your face, the bigger the sample size the longer it will take to train but the more accurate it will be.

Finally run facial_req.py to run the facial recognition code, You should see a yellow box around your face and it should have the name you used earlier and it will also say unknow if it detects a face it has not learned.

