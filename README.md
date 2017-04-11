# cseS5
An App for Cse S5 of MGU

Those who Want to add Contents to this app follow the instructions

First Make a Fork of this repository
Then Do the following changes to your repository to add stuffs to the app.

#For Adding A Notification
  
  Open the Notification.json file inside the JsonFiles Directory
  
  Here is the format for a Notification
  
        {
              "title":"  Your Title Here",
              "content":" Your Content Here",
	            "date" : " Date of Upload"
        },
  
  Add this block the Notification.json and then check if it a valid json file.. if not .. correct it..  
  
#For Adding a File to a subject

  Add the file to the respective directory inside the Downloads folder
  Now Open download.json inside JsonFiles Directory
  
  and add the following code to it...   
  
      {
          "name":"Name or Title of the File",
          "description":"Description",
          "author" : " Change author name here",
          "type" : " type of file",
          "subject" : "subject code should be here" ,
          "date" : " Date of Upload",
          "download":" Link to the file.. it must be a direct download link.. from this repo"
      },
   
    In subject field.. 
    you can choose the following subjects :-
   
              maths     -  Engineering Maths
              pom     -  Principles of Management
              amp  -  Advanced Microprocessors and peripherals
              dms     -  Database Management Systems
              dsp   -  Digital Signal Processing
              os     -  Operating Systems
              databaselab     -  Databse Lab
	      mplab - Hardware and Microprocessors Lab
              qp      -  Question Papers
              misc    -  Miscellaneous Stuffs
              
  After modifying the code and adding it to download.json   make sure the json file is valid...  
  after that push changes to your repo and the give a pull request to this repo.. 
  it will be added as soon as it is Verified... 
              
        
        
      #  Thank you for your support
