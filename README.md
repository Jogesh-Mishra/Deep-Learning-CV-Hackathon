# Deep-Learning-CV-Hackathon

This repositoy contains two folders : Problem Statement Part 1 (For Hackathon Model) and Problem Statement Part 2 (For report on FCN in Autonomous Vehicle)

The model for Hackathon is trained using the idea that each folder in Trainset is a department for the comapny with image of each employee (both passport and selfie). This was necessary for now as training the model using each employee's picture was not possible due to availability of less documents.

The above code for task 1 of Deep Learning CV Hackathon is trained on the data set in the link https://drive.google.com/file/d/12_WTFi9ppvD-loaWUWpUar25Z3nT5k9P/view 

Hackathon.ipynb is the trained model that was trained in GOOGLE COLAB, so I would recommend you to run the hackathon.ipynb on Google Colab, in case you don't want to use !mkdir or !unzip in your code, you can run the file in jupyter even, after commenting these statements.

hackathon.py is the required python file that takes in two arguments : the selfies image and passport image along with the extension and directory ( if not present in the same folder as the hackathon.py model). The file should be run on python IDE , not on Command Prompt as this has been programmed accordingly.

haarcasccade_frontalface_default.xml file has been used for Face Region of Interest detection. This needs to be in the same folder as Hackathon.ipynb and hackathon.py

The model is saved by the name of saved_model .

