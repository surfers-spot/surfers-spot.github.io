# Surfers' Spot



# Table of contents

* [GitHub](#github)
* [Overview](#overview)
* [User Guide](#user-guide)
* [Community Review](#community-review)
* [Deployment](#deployment)
* [Developer Guide](#developer-guide)
* [Development History](#development-history)
* [Team](#team)

# GitHub
[GitHub](https://github.com/surfers-spot/surfers-spot)

# Build Status
![ci-badge](https://github.com/surfers-spot/surfers-spot/workflows/ci-surfers-spot/badge.svg)

# Overview


Problem: There are students that come to UH Manoa from all over the world and want to experience Hawaii as a whole, in order to do that they want to try surfing. Students that are coming come from various skill levels and would like to know where the most suitable location for surfing on Oahu would be for them. 

Solution: With the Surfers' Spot app it will help UH students identify the surf breaks that are most suitable for their skill level based on the direction of the swell, season and their location.  

The idea behind this app is to list and categorize various beaches and surf breaks around Oahu. The breaks could be listed based off of their distance from the campus, skill level, wave direction (left or right), ideal swell direction, and ideal swell size. This app could be helpful for the students who have come to UH Manoa from other place and would like to know which beaches would be ideal to surf for their skill level. We could include potential hazards as well as a basic description of the locations. Other information that could be added to the different locations is other activities that can be done. Such as, swimming, fishing, snorkeling, volleyball, etc. We plan on having two roles, an administrative role and a basic user role. Basic users can view the places while administrators would be able to make changes. Different tabs can be used to reflect the different skill levels or other categories. A user can also specify their skill level and get various suggestions based on their skill level. When users log in and set up their profiles they can browse and receive suggestions. We could also implement a rating system where users would be able to rate the different breaks. 



# User Guide
This section will provide a walk through of the Surfers' Spot interface and its capabilities. 

### Landing Page
This is the landing page users will see when they visit the site. From here the user has the option of navigating to a directory of pages, a random break page, the most popular page, a page for surf lessons and a general about us page from the Navbar. A user can also login in at this point from the landing page. The user, furthermore, has the option to search for a break page where a dropdown feature will appear once they start typing the desired break. 

<p align="center">
  <img src="images/Landing-Page-1.png">
</p>

The user also has the option to click on one of 3 randomly populated break pages on the landing page where an image, name, location and difficulty are described at first glance. Our footer also contains links similar to our Navbar and also houses our Stay Connected functionality for new users. 

<p align ="center">
  <img src="images/Landing-Page-2.png">
</p>

### Search Bar
Here, as demonstrated in the image, the user can search for breaks in our currently populated directory of breaks. The search bar will filter breaks as the user inputs characters into the search bar in order to help the user find the specific break they are searching for. If the break exists, the user can click the break's name to be linked to that break's page. If no such break is found, then the dropdown tells the user "no results found" as depicted in the second image. 
<p align ="center">
  <img src="images/Search-Bar.png">
</p>
<br>
<p align ="center">
  <img src="images/Wrong-Search-Bar.png">
</p>

### Sign Up Page
If you are new to the website, you can create an account with us. You will be prompted with this page asking for your email and a password. 

<p align="center">
  <img src="images/resiger-your-page.png">
</p>

After creating an account with us, you will be prompted with this page everytime you log in. 
<p align="center">
  <img src="images/log-in-page.png">
</p>

### Adding Your Information
After creating your account, you will then be prompted with information to allow for the site to narrow down your searches for the different breaks. 

<p align="center">
  <img src="images/Add-Stuff.png">
</p>

### About Us
In our footer we have a tab that gives users an overview of us, and it gives a little overview of our purpose of our site, and you are able to read some of our recent reviews and find surf lessons that are happening near you. 

<p align="center">
  <img src="images/Info.png">
</p>

<p align="center">
  <img src="images/Info-1.png">
</p>

### Adding a Break
Admins can add a surf break to the website by filling out a form and giving a name, location, image, type, difficulty, and description of the surf break. 

<p align="center">
  <img src="images/Add-Break.png">
</p>

### Random Break
When accessing our random break link, a random break will appear with its level of difficulty, location, and type of break. 

<p align="center">
  <img src="images/Random-updated.png">
</p>

### Popular Break
As users continue to use the site, each break page gains site views. Each break page has a hidden property for page views, viewable only to the Admin in the break directory page, so that when the popular page link is clicked by a user, the user will be sent to the most popular page. Shown below is the current popular page and the admin view of the break directory page, which shows that the page views correspond to the popular page. 

<p align="center">
  <img src="images/Popular-updated.png">
  <img src="images/Admin-Directory-Page-Views.png">
</p>

### Directory Page
Users that do not know the name of any breaks or wish to look at all of the current existing breaks can do so on the Directory Page. Here all of the currently added break pages are listed in alphabetical order with their name, location, difficulty, photo, and an option to view the page. 

<p align="center">
  <img src="images/Directory-Page.png">
</p>

### Surf Breaks Pages 
Depicted below are example pages for the Kewalos, Canoes, and Bowls break pages. Each page provides the difficulty, type, location, a short description, a photo, a "Get Directions" link to the Google Maps search of the break location, and the option to leave a review at the bottom of the page. 

<p align="center">
  <img src="images/Kewalos-updated.png">
</p>

<p align="center">
  <img src="images/Canoes-updated.png">
</p>

<p align="center">
  <img src="images/Bowls-Updated.png">
</p>


### Lessons Page
Not all of our users may be experienced surfers. Here, beginner surfers and even those looking to improve their current skills can look for our top picks in Surf Schools. All of these schools are based out of Honolulu and have great recommendations. Users can get the name, phone number, location, and short testimonial from the school. 
<p align="center">
  <img src="images/Lessons-Page.png">
</p>

### Leave a Review
While visiting a break page, users can leave a review for that break. Once the user has finished entering their review in the textfield and submit the review. 
<p align="center">
  <img src="images/Leave_Review.png">
</p>
Once submitted the review will appear above the leave a review submission area and will permanently be affixed there since the review gets updated into the review collection kept in the repository.  
<p align="center">
  <img src="images/Review-Left.png">
</p> 

### Stay Connected
The stay connected feature in the footer will allow a user to input their email and submit it to the admin. This email is added to the email collection in the GitHub repository that the admin can look up.

<p align="center">
  <img src="images/Stay-Connected.png">
</p>

# Community Review

## Gracie Howley:
- I love how many spots are featured on this website with details such as level of difficulty and whether it's a sand or reef break. 
- It would be beyond amazing if live surf conditions could be included in each description. 
- The ???random??? feature is totally unique to any other surf site I have seen and keeps things interesting. 
- I appreciate that local lessons are incorporated into the site. 
- I???m going to show this website to my family when they visit me next!

## Tyler Stynes:
- The website was very easy to navigate and the aesthetic was clean and pleasant. 
- The ???random??? button was a fun touch as well for finding new breaks. 
- Really seems like a one stop shop with lessons tab included(good for beginners or people new to the area). 
- Overall easy to use and informational. 
- Some potential improvements would be to add live wave conditions for each site and maybe add a bit more detail in the surf spot descriptions(such as seasonal changes for each, average wave size, etc). 
- Overall, useful and user friendly.

## Ani K.:
- Make link the address for the lessons to google maps so that viewers can quickly get access
- If it is possible, add a filter on the directory page, so viewers can quickly choose what type of break they want, or a specific part of the island
- If that is not possible maybe like put the beaches in order from easiest to hardest
-  Make the get directions link easier to see
- Otherwise, it looks good.

## Dylan K.:
- Likes the intuitive design, knew what the website was about instantly
- Wants better visibility on things like buttons
- Wants the phone and addresses in the Lessons page to be clickable

## Jennah L.:
- Would like more color
- Thinks information about famous surfers would be interesting to add
- Having videos on things like surfing or the locations would be nice

# Deployment
[Surfers' Spot](https://surfersspot.xyz/#/)

# Developer Guide
### Installation 
- First, [install Meteor](https://www.meteor.com/developers/install)

- Second, download a copy of [Surfers' Spot](https://github.com/surfers-spot/surfers-spot) and clone it to your laptop 

- Third, cd into the app/directory and install the libraries with 

`$ meteor npm install`

- Fourth, run the system with 

`$ meteor npm run start`

- If all goes well it will appear at [http://localhost:3000/](http://localhost:3000/) 

# Development History

### Final Project: Milestone 1
[Milestone 1](https://github.com/surfers-spot/surfers-spot/projects/1)

***

### Final Project: Milestone 2
[Milestone 2](https://github.com/surfers-spot/surfers-spot/projects/2)

***

### Final Project: Milestone 3
[Milestone 3](https://github.com/surfers-spot/surfers-spot/projects/3)


# Team

Surfers Spot is designed, implemented, and maintained by: 
* [Kristi Chinen](https://kristihchinen.github.io/)
* [Victor Ho](https://hovictor2000.github.io/) 
* [Micheal Lavers](https://sync925.github.io/)
* [Brennan Lincoln](https://blincoln15.github.io/) 
* [Aaron Thomas](https://aaron-toomas.github.io/)









