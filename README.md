# Handwritten-Text-Recognition-by-kartik
TO run this model on your system some steps are as follow:
1.	Install python 3.10 or higher version
2.	After that install some libraries using pip commands
i.	OpenCV
ii.	Editdistance
iii.	Numpy
iv.	Tensorflow
v.	Flask
vi.	Sklearn
3.	If you want to train the model from scratch
i.	First download the IAM dataset from https://fki.tic.heia-fr.ch/databases/iam-handwriting-database   
ii.	Download only the lines handwritten dataset and put this files in data folder under lines folder.
This site will require you to sign up so sign up with your email which is very easy.
iii.	Just open the terminal in source folder of the repository and run the following commands
iv.	To train the model
python main.py --train 
v.	To validate the model 
      python main.py –validate
4.	The process of training and validating model is very time consuming you can skip this 3rd step by using pre trained model which I have uploaded as zip in gdrive just extract the zip file in model folder.
The link of model is https://drive.google.com/file/d/1qRE3w_NrfKljyIOmoEruU9lr5m-VNzZC/view?usp=sharing

5.	Now you are ready to get the prediction from the model.
vi.	To open the model in browser and get prediction on your data
python upload.py
vii.	This will give you a IP address just open this IP in your browser upload the image and get the text extract from it.

