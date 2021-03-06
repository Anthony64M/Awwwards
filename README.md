# Awwwards

>[Anthony64M](https://github.com/Anthony64M)  
  
# Description  
This project allows users to post their projects for other users to rate according to design, usability and content 
##  Live Link  
 Click [View Site]()  to visit the site
  
## Screenshots 
###### Home page
 
<!-- <img src="https://ucarecdn.com/a4305bbb-8ef8-4570-8bf2-48ea79029197/"> -->
 
 ###### Rating of a post
 <!-- <img src="https://ucarecdn.com/fa9f5724-d815-4c55-b5a0-414dbc727d02/">  -->


 
## User Story  
  
* A user can view posted projects and their details.  
* A user can post a project to be rated/reviewed. 
* A user can rate/ review other users' projects.  
* Search for projects.  
* View projects overall score.
* A user can view their profile page.  
  

  
## Setup and Installation  
To get the project .......  
  
##### Cloning the repository:  
 ```bash 
 https://github.com/Anthony64M/Awwwards.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Awwwards pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv env - source env/bin/activate  
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations awwwards
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`.  
  
 ### Api Endpoints
 <!-- * https://chawwards.herokuapp.com/api/users/
 * https://chawwards.herokuapp.com/api/profile/
 * https://chawwards.herokuapp.com/api/posts/ -->
 
 
## Technology used  
  
* [Python3.6](https://www.python.org/)  
* [Django 1.11](https://docs.djangoproject.com/en/2.2/)  
* [Heroku](https://heroku.com)  
  
  
## Known Bugs  
* There are no known bugs currently but pull requests are allowed incase you spot a bug  
  
## Contact Information   
If you have any question or contributions, please email me at [jymal6anthony4@gmail.com]  
  
## License 

* [![License](https://img.shields.io/packagist/l/loopline-systems/closeio-api-wrapper.svg)](https://github.com/Anthony64M/Picture-Globe/blob/master/LICENSE)  
* Copyright (c) 2021 **Anthony64M **