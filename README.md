## Other projects which I have make however can't show the source code.


# Table of Contents:
- [Allergy Menu](#Allergy-Menu)
- [Plannu](#Plannu)
- [Colour Game](#Colour-Game)
- [Connect4](#Connect4)
- [RL Investments](#RL-Investments)
- [Other Ideas](#Other-Ideas)


## Allergy Menu
This project has 2 websites:
One for restaurants to add their current menu with their food's allergies and descriptions
Other one for customers to input their allergies and can see what food they can eat in the restaurant

Finished the basic concept, there are still a few issues but they are more visual and productivity related rather can the core concept, such as adding sections to the menu, changing the colours and adding specific allergies to each restaurant.

Here is the customer website: https://allergycheckercustomer.azurewebsites.net, below is a sample photo of the customer site:

![Image 1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/Allergy_Checker_Customer_1.png?raw=true)

Here is the restaurant website: https://allergycheckerrestaurant.azurewebsites.net, below is a sample photo of the restaurant site:

![Image 1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/Allergy_Checker_Restaurant_1.png?raw=true)

Front-end is built with Angular, but backend API is built in Python with Firebase for the authentication and database. Used Azure to host the website and the API.

## Logins:

Restaurant Email: res@outlook.com (Restaurant A)\
Restaurant Password: nothing123

Customer Email: test@outlook.com\
Customer Password: nothing123


## Plannu
Plannu is an iOS app designed to help people in such as tutors or personal trainers. 

You just add the people you work with and put your sessions on the inbuilt calendar, and Plannu will automatically calculate the monthly bill for each specific person. You can also add groups and cancel sessions (with or without cancelling payment), and you can add notes next to each session, person or group.

It is on the iOS app store here: https://apps.apple.com/us/app/plannu/id1530983939

Here are some previews:
![Preview1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/PlannuPreviews1.png?raw=true)
![Preview2](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/PlannuPreviews2.png?raw=true)


## Colour Game
A game where you have to try and get all the colours in the correct order, it shows you your previous moves and you have to use trial and error to get the correct order.

Here is the URL: https://colours.azurewebsites.net

Here are some previews:

![Preview1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/colourGame1.png?raw=true)

![Preview2](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/colourGame2.png?raw=true)

Correct means the colour is in the correct position, almost means it is 1 within the correct position


## Connect4
A Connect4 multiplayer game, where you have to get 4 in a row\
This was mainly so I could more about interacting with Firebase Realtime databases.

Here is the URL: https://aryaaconnect4.z33.web.core.windows.net/

You create an account and then you can choose a custom colour, then click find match and it will place you in the queue, until someone else joins and then you will be against them. You get +25 rating when you win and -25 when you lose

Here are some previews:
![Preview1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/connect41.png?raw=true)

![Preview2](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/connect43.png?raw=true)
*Unfortunately I had to write this in AngularJS instead of the usual Angular, which means the code is messy and there are a few bugs, such as if 2 players have the same colour it will just let the host (the player who starts) win. However the bugs shouldn't hinder the playing experience too much*

### Embedded:
This is a local version of the connect4, and I have enabled you to just embed it into your own project
I have added it to my Web Operating System as an app, without having to write any game code inside that project.

Use this URL to access the embed mode: https://connect4-863d1.web.app/game.html?embed=true

The minimum width and height is: 740px X 1000px\
If this is too large or too small for you, you can also add an optional scale parameter, 0.5 will apply a 50% scale, 2 will apply a 200% scale.\
Here is an example of a URL with scale: https://connect4-863d1.web.app/game.html?embed=true&&scale=0.5

Here is an example to just add to your HTML:
```
<iframe  style="height: 1000px; width: 740px" src="https://connect4-863d1.web.app/game.html?embed=true&&scale=1"></iframe>
```

Here is a preview:

![Preview1](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/conenct4.png?raw=true)


## RL Investments
An app which helps you track your investments in the popular game Rocket League. There is an active trading scene in this game with the primary currency being credits, many people make investments and try and sell later on when the price of the item has gone up in price.

To get accurate pricing details, most people use the website: https://rl.insider.gg. I have also used this website to gather pricing information.

### Investments
The app just lets you add investments, including the item itself, the colour, the price it was bought for, and the platform it was bought on. It then will output the profit/loss if you sell the item right now.\
There is also a total button if you want to find out the complete profit/loss if you sell everything that you have added in the app.

### Cross Platform
There is also a cross-platform section, which allows you to transfer credits from one platform to another, since it is not directly possible due to differing terms and condition on each platform. For example if you were transferring credits from Xbox -> PC, you could buy an item for X amount of credits on xbox, and sell it for Y amount of credits on pc. The app tries and gives you the best conversion rate so you lose as little credits as possible.

### Prices
This is just a simple list of all the items and their respective prices.

Here are some previews: 

![RL Investment Preview](https://github.com/AryaaSk/Other-Projects/blob/main/Previews/RLInvestments.png?raw=true)


## Other Ideas
### Fetch-Decode-Execute Cycle Demo
This website is just like a visual representation of the fetch-decode-execute cycle which occurs inside CPUs. The user will be able to input some instructions, it shows which step it is currently on and overall just shows how a computer works. I could use this video to better visualise what it should do: https://www.youtube.com/watch?v=Z5JC9Ve1sfI

### LingoLearn online website:
Just like the app, I can just use the already existing API and create a website, will have the store the words in local storage similar to how it is stored in user defaults in iOS.

### SQL Database Viewer
A frontend application which can create, update, and delete data from a backend SQL database, could also make this in a simple python project, just to learn about SQL and it's commands better.
