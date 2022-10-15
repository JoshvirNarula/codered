GREETINGS<br/>

There are two ways of running the model<br/>

method1: running the python script locally and seeing the whole pipline of processing:<br/>

  step1: install all files in the github repo to your system in a folder<br/>
  step2: open anpr_final.py and at the bottom change path variable to the image to test<br/>
  step3: install all the required python packages that are in the import statements of this python file<br/>
  step4:run the program <br/>
  step5: multiple matplotlib plots will open, keep closing them to see the process of prediction<br/>
  step6: the final license plate, if detected, will be displayed in terminal<br/>


method2: local deployment of app:<br/>

  step1: install all files in the github repo to your system in a folder<br/>
  step2: open app.py and install all required packages<br/>
  step4:run app.py<br/>
  step5: open the local host url in the terminal(eg http://127.0.0.1:3000)<br/>
  step6:click upload and upload image<br/>
  step7:click predict<br/>


NOTE: model works best on a specific type of images that i designed the image processing techniques on.<br/>
such example images are in the repository<br/>
  
