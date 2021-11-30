# ArtGala

#### 29/11/2021  

#### By **Simon Kairu**  

## Description  
 ArtGala is a photo gallery web application that display photos. 
 Users are able to see all the images uploaded by admin. 
 They can also copy the link to a photo to paste at their destination.
 They can also search for photos based on the categories.  

 ## Behaviour Driven Development(BDD) 
| Behavior            | Input                         | Output                        |
| ------------------- | ----------------------------- | ----------------------------- |
| View photos of interest | Scroll to see a gallery and click on picture | Displays a picture with name description and copy link for sharing |
| Search a picture by category | Enter the category in the search input| Displays photographs in the searched category |
| View pictures by location | Click on location of interest in menu bar | Displays photographs of chosen location |
| Copy Link to clipboard | Click on copy link button in the modal class | Copies link to clipboard |
| View Single picture | Click on photo of interest then click on image | Displays a single page with details of the picture and related images |

## Features   
 As a user of ArtGala web application, you will be able to:  
  * View different photos that interest me  
  * Search for different categories of photos  
  * Copy a link to the photo to share with my friends  
  * View photos based on the location they were taken 

  ## Setup/Installation Requirements  
 ### To interact with the ArtGala web application:   
* Have the latest version of browser installed  
* Click on this <a href = "https://artgala.herokuapp.com/">link</a> to view the gallery. 
 
 ### To contribute to ArtGala web application:  
 #### Clone the Repo  
 * Create an account on Github
* Fork the repository from Github with this <a href = "https://github.com/simonkairu/GalaArt.git" >link </a>
* Clone the repository
* Open the project cloned project

####  Activate virtual environment
Activate virtual environment using python3.6 as default handler
    `virtualenv -p /usr/bin/python3.6 venv && source venv/bin/activate`

####  Install dependancies
Install dependancies that will create an environment for the app to run `pip3 install -r requirements.txt`   

####  Create the Database
    - psql
    - CREATE DATABASE gallery;

####  .env file
Create .env file and paste paste the following filling where appropriate:

    SECRET_KEY = '<Secret_key>'
    DBNAME = 'gallery'
    USER = '<Username>'
    PASSWORD = '<password>'
    DEBUG = True  

#### Run initial Migration
    python3.8 manage.py makemigrations gallery
    python3.8 manage.py migrate     

#### Run the app
    python3.8 manage.py runserver
    Open terminal on localhost:8000    

## Known Bugs
There are no known bugs so far  

## Technologies Used  
* Python v3.8  
* HTML
* Bootstrap
* Django  
* Postgres  

## Support and contact details
In case of any problem while interacting with the web application, reach out to me at simon.mureithi@student.moringaschool.com