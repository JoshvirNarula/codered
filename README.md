GREETINGS

There are two ways of running the model

method1: running the python script locally and seeing the whole pipline of processing:

  step1: install all files in the github repo to your system in a folder
  step2: open anpr_final.py and at the bottom change path variable to the image to test
  step3: install all the required python packages that are in the import statements of this python file
  step4:run the program 
  step5: multiple matplotlib plots will open, keep closing them to see the process of prediction
  step6: the final license plate, if detected, will be displayed in terminal


method2: local deployment of app:

  step1: install all files in the github repo to your system in a folder
  step2: open app.py and install all required packages
  step4:run app.py
  step5: open the local host url in the terminal(http://127.0.0.1:3000)
  step6:click upload and upload image
  step7:click predict


NOTE: model works best on a specific type of images that i designed the image processing techniques on.
such example images are in the repository
  
