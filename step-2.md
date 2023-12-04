Capstone 2
Step 2
12/8/2023

Well, I prefer python but my question is I want to make a mobile app that will compare a sport player salary with there currents stats to see if they are overpaid or underpaid. Now being that I want to do a mobile app I believe that would not include python right? So in that case I would just want to build the app for a web app. Also if you think it would be better for me to create a project with react and node.js to diversify my portfolio I am ok with that as well.

I would like the focus of my app to be balanced with the ui and backend.

Prefer a mobile app but ok with a website.

The goal of my app is to challenge myself to create an app that will compare data as that is what I enjoy.

I am assuming sports fans will lokk at my app and maybe more importantly frustrated sports fans lol.

There are many free sports api’s available out there I would just pick the best one regardless of sport. I will need my data in the API to contain sports stats.BalldontlieAPI, NBA-API from RapidAPI

Database schema(example for say nba player)
Tables Needed:
Login
Register
User
Player(includes their general info and stats) 
Salary(dont know if i need a seperate model for this or include salary in Player model or create one and make a relationship to player)
Average Position stats and salary(again dont know if i need another Model to represent the average stats, salary for each of the 5 positions)

Also I was unable to find an api that will have a nba players salary in it. May need to scrape or any thoughts on that?

I will need to create a login and registration for a users security.

The functionality will be simple thats my aim, input a players name and output is overpaid or underpaid

User Flow:
Homepage 
Login first to search player
If you dont have login credentials then you need to register
Login after proper credentials are issued
redirect back to homepage where you can search for a player in an input
redirect to the results if your player is over or underpaid
maybe include the players stats vs average player at position stats.

