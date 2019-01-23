# Plant_Diesease_Django


Source code for training the model is available in this github repository.

https://github.com/G-Slient/Plantdiseases


## How to run the Django application 

  1. Create A virtual envirnoment 
  
 ### How to create virtualenv
  
  For Ubuntu:
  
  creating the virtual env:
      
    virtualenv (nameoftheenv)
  
  Activating the env:
  
    source (nameoftheenv)/bin/activate
      
  2. Install the required libraries from requirements.txt
 
    pip install -r requirements.txt
 
  3. Now,everything is ready. Run the app.py 
        
    python manage.py runserver



 Open 127.0.0.1:8000 url in your browser.
 
 ### For predicting the diesease of a plant, first we need to provide the image as input.
 
 
We use [Postman](https://www.getpostman.com/) for this purpose.

1. Download the Postman for the respective operating system using the [link](https://www.getpostman.com/apps).

2. Parameters for running Postman:
   
       Type of request: POST
       In body:
       Type of data: form-data
       key: plant_image
       value:(input image which is converted into base64 using onlineconvertor https://www.base64-image.de/))

 
 
