The Django app is divided into four modules:
1.  *moviereviews* : This is the root module. It contains the *settings.py* and *_init.py_* file. Also, contains the base template for all other templates. The base.html shows whether a user is currently logged in or not.
2.  *movie* : Defines the Models for storing movies and reviews with the admin; views for processing search request for a specific movie, sigining up user, routing to the movie details page, creating, editing and updating reviews made by that user once they are logged in. Contains the templates for displaying the movies at home page, showing movie details, and review form.
3.  *accounts* : Handles POST request to create new users, checks if a username has already been taken and implements log-in/log-out functionality.
4.  *news* : Defines the news Model for storing news articles; the view for retrieving news objects from the database and then passing them to the news.html template for display.

# Functionality:
Search bar: 
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/06638967-bd42-460a-8ed6-791ba34b3274)
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/1640d3ae-e96f-4a4e-9d16-56ccbe6304e3)


Log-in/sing-up page: 
![image](https://github.com/hotair88/moviereviewsapp/assets/105349649/5fa34d16-3847-411c-ae8f-91087f35834b)







