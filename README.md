# The Cook Book

This project represents a website with differet recipes for the cooking lovers and uses modern tech to represent the information in the best way possible. 

This Website provides you with the a broad options of recipes that you would like to try out
and also makes it possible to add your favorite recipes yourself. 

![Cookbook cover](https://www.thebalancecareers.com/thmb/_X1aDEUbxj0achcbvM2rOOVJ5Mk=/2022x1483/filters:fill(auto,1)/communityrecipebook-e6417b8aefb2436fbc03861206263c9f.jpg)

## User experience

This website focuses on the users that have a special passion for cooking and surely the coocking fanatics and lovers. Once the website is loaded you will be directed
to the main page that it's called **All Recipes**

#### User Goals:

As a User I would like to have a simple UX that is self explantory and at the same time efficient enough to do what I'm expecting from it,
Like fetching and manipulating date easily. Like clicking the **Add recipe** button and you know what comes next and it's easy to fill out. That is my goal as a user. 

## Wireframes

Here come the **Mockups** that I planned my project with.

[CLICK HERE](https://www.scribd.com/document/449610829/Project-Mockups)

## Features

In this section we will be talking about the features that I implemented in this project and features that could be implemented as well:

#### Existing Features:

* **Adding a Recipe:** At this point when the user click the button "Add Recipe" She/He will be redirected to a page with a submission form that provides several fields to add the needed data in order to get your recipe displayed. 
* **Editing a Recipe:** Once you have added a recipe and realize that you would like to change something in it, I added an "Edit" button on the bottom of each recipe to make it possible to do so. 
* **Deleting a Recipe:** In case the user would like to delete a recipe that She/He added, All is needed to press on the "Del" button next to the edit button and than they will be facing a model popup asking to confirm the deletion. 

All those feature above are presented in a easy manner to make it simple for the user to take advantage of them. 

#### Left to be implemented Features:

* Adding a upload file section to the **Add Recipe** instead of asking for a URL. This can be achieved by using **AWS S3** and connect it to **MongoDB**. 
* Making the Categories page linked to the recipe so once you choose a specific category, you will be redirected to those specific recipes of that specific category. 

## Technologies Used

In this project I have used several Technologies in order to achieve the end goal:

* **Python 3:** In order to create the fully functional app that you see!
* **Flask:** To make it easier to create the different python app.routes to connect. 
* **Materialize:** I used it for the navigation bar, the cards and the footers. 
* **jQuery:** In order to get the Navigation button running and also the delete popup model.
* **Font-Awesome:** To get the icons for the submission form "Add Recipe"
* **Google-Font:** To add new fonts. 

## Testing

I have conducted multiple tests in order to check the app on feasbility and also on durability, I also used the section of **"Add Recipe"** to
add a Recipe and see how it is displayed once added. 

I went first with the delete button without using the modal popup to ask for confirmation before deletion, but than realised after testing that's
super easy to delete recipe by mistake. Therefor implementing the button is crucial. 

I also asked Family members and collagues at work to go through the website and test it on functionality and they were impressed by its performance
and they added some recipes themselves. 

## Deployment

The project is pushed to **Github** from there it was linked to Heroku for deployment. 

Here is the link of the app:

* [The Cook Book](https://the-cook-book-by-ram.herokuapp.com/)

## Credits

* The Pictures have been taken from google.
* The description of each Cuisine was taken from Wikipedia. 
* The "MORE ABOUT THIS CUISINE" button is linked to [BBC good food](https://www.bbcgoodfood.com/recipes/category/cuisines)


## Acknowledgements

This website is inspired by the very known cooking website: 

[Allrecipes](https://www.allrecipes.com/)