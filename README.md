# FLOWER-CLASSIFIER-WEBAPP
This is an neural network webapp visualizing the training of the network and testing accuracy of 98.6% accuracy.
The neural network uses pretrained resnet152 and then trained to classify images of flowers.
It is built using Pytorch framework using Python as primary language.
The webapp is built using flask.

## Dataset used :     
102 Category Flower Dataset  

## Complete flow :    
![model](/static/model.gif)   


## Run on windows - 
Make sure you have installed Python , Pytorch and flask.


* _First download all the folders and files_     
`git clone https://github.com/antriiksh/flowerClassificationModel`       
* _Download pretrained weights and keep it in the same Project directory_ [Download here](https://www.kaggle.com/souravs17031999/flowerclassifierudacitypretrainedweights)    
* _Then open the command prompt (or powershell) and change the directory to the path where all the files are located._       
`cd FLOWER-CLASSIFIER-WEBAPP`      
* _Now run the following commands_ -        

`set FLASK_APP=flower.py`   

`flask run`      

*If does not run then do this 


`Under Powershell, you have to set the FLASK_APP environment variable as follows:

$env:FLASK_APP = "webapp"

Then you should be able to run "python -m flask run" inside the hello_app folder. In other words, PowerShell manages environment variables differently, so the standard command-line "set FLASK_APP=webapp" won't work.`   

This will firstly download the models and then start the local web server.



# CREATOR
- [ANTRIKSH KASHYAP](https://github.com/antriiksh)

--------------------------------------------------
