The Django app is divided into four modules:
1.  *moviereviews* : This is the root module. It contains the *settings.py* and *_init.py_* file. Also, contains the base template for all other templates. The base.html shows whether a user is currently logged in or not.
2.  *movie* : Defines the Models for storing movies and reviews with the admin; views for processing search request for a specific movie, sigining up user, routing to the movie details page, creating, editing and updating reviews made by that user once they are logged in. Contains the templates for displaying the movies at home page, showing movie details, and review form.
3.  *accounts* : Handles POST request to create new users, checks if a username has already been taken and implements log-in/log-out functionality.
4.  *news* : Defines the news Model for storing news articles; the view for retrieving news objects from the database and then passing them to the news.html template for display.

__Pillow__ (Python Imaging Library) has been used for image processing.

# Functionality:
__Search bar:__ 
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/921372aa-1dde-4337-8ede-6993f5985c11)


__Log-in/sing-up page:__ 

![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/f7567836-842e-4fb2-8c91-7a494be0cbef)
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/1b59c0c4-1b3e-4c5e-81c5-2014ae36279a)



__Home page:__ 

![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/c55de0ff-47c6-4f98-bd90-b27014484b41)
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/d472363a-e5ea-4ef3-a9be-e6cd06b4196d)



__Movie-details page:__

![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/c3afdb6c-66cd-4e7f-b101-618c0961c25d)


__News page:__

![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/ea983cf5-1a19-41a4-b348-75bb2210dc8e)
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/acfaa273-b8b7-42e8-beff-506b2a1cd78f)












