# Fencing Score

Fencing Score is a counting score app to count score for Fencing game. it has been built for Udacity Google Android Basics 
Scholarship during the period of Nov. 2017 – Feb. 2018. The project was the second of three required projects to finish the scholarship.

## Quick Overview 

* The goal is to create a Score Keeper app which gives a user the ability to keep track of the score of two different 
Fencing players. 
* App is divided into two columns, one for each player. 
* The user can count Touch Points, R.o.W points, and any type of cards (yellow, black and red) to each player.
* The App provides help page to give introduction about discipline types and how to count scores.
* The App provides a statistics page to enable user to maintain specific data for each player

## App structure 

At this stage of the scholarship , a multi screen app wasn’t included. All the required projects were a single screen app.
A solution to display multi screen pages is to use ScrollView.

I have built this App as a multi screen app using “Visibility” Attribute to enable the user to move easily between pages and reset
the game when needed.

The app consists of 3 pages distributed as follows :
*	Main page (home page) divided into two column with a score counter for each player. 
*	Statistics page to provide scoring data for each player.
*	Help page to provide a brief introduction about the game and how the score is being counted.  

## How it works

I have used nested views to reduce complexity of the layout with the RelativeLayout as root view and nested RelativeLayout,
LineraLayout and ScrollView if needed. a comment has been made to separate each page started the xml order from page 1 to end up
with page 3.  
By using Xml Visibility attribute, when clicking any button the current layout will be gone and reveal the other. for example,
while the user on Home page, by clicking the statistic button the Home page will disappear and the statistics page will appear.  

## The App Users 

This App is indented to count the score of Fencing game in individual competition for only two types of fencing discipline
‘Foil and Sabre’. The Third discipline which called ‘Epee’ is to be added in next version along with the team competition score.
