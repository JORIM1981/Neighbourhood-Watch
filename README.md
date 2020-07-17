

# Neighbourhood-Watch

#### 17/07/2020
#### By **Jorim Midumbi Okong'o Opondo**

## Description
A web application that allows you to be in the loop about everything happening in your neighborhood. From contact information of different handyman to meeting announcements or even alerts.

You can view the site at:[Heroku]()


## User Stories
As a user, I would like to:
* Sign in with the application to start using.
* Set up a profile about me and a general location and my neighborhood name.
* Find a list of different businesses in my neighborhood.
* Find Contact Information for the health department and Police authorities near my neighborhood.
* Create Posts that will be visible to everyone in my neighborhood.
* Change My neighborhood when I decide to move out.
* Only view details of a single neighborhood.
  

  
## Setup and Installation  
To get the project ....... 
  
##### Cloning the repository:  
 ```bash 
 https://github.com/JORIM1981/Neighbourhood-Watch.git 
```
##### Navigate into the folder and install requirements  
 ```bash 
cd Neighbourhood-watch pip install -r requirements.txt 
```
##### Install and activate Virtual  
 ```bash 
- python3 -m venv venv - source venv/bin/activate 
```  
##### Install Dependencies  
 ```bash 
 pip install -r requirements.txt 
```  
 ##### Setup Database  
  SetUp your database User,Password, Host then make migrate  
 ```bash 
python manage.py makemigrations pictures 
 ``` 
 Now Migrate  
 ```bash 
 python manage.py migrate 
```
##### Run the application  
 ```bash 
 python manage.py runserver 
``` 
##### Running the application  
 ```bash 
 python manage.py server 
```
##### Testing the application  
 ```bash 
 python manage.py test 
```
Open the application on your browser `127.0.0.1:8000`. 

### Api Endpoints
 * https://awwards-jorim.herokuapp.com/api/users/
 * https://awwards-jorim.herokuapp.com/api/profile/
 * https://awwards-jorim.herokuapp.com/api/posts/

  




## Technology used

* [Python3.8](https://www.python.org/)
* [Django3.0.7](https://docs.djangoproject.com/en/2.2/)
* [Heroku](https://heroku.com)


## Known Bugs
* There are no known bugs currently but pull requests are allowed incase you spot a bug

## Contact Information 

If you have any question or contributions, please email me at [okongo.midumbi.opondo@gmail.com]

## License:

- _MIT License:_[LICENSE MIT](./LICENSE)

- Copyright (c) 2020 **Jorim Midumbi Okongo Opondo**


