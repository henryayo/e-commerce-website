# e-commerce-website
---- AUTHOR ----

Henry Johnson

---- PROJECT ----

E-commerce Website 

---- DESCRIPTION ----

This is a fully responsive FullStack E-commerce website built with NodeJS, Express and MongoDB with the implementation of the Stripe API for a checkout system. It has an authentication system, shop and allows order tracking. It also has special admin-only features like adding, managing or deleting the products and updating order status.

![Screenshot (19)](https://user-images.githubusercontent.com/40214178/159981755-ba1784bb-67cf-44fb-bf2b-160b21322aa6.png)

![Screenshot (20)](https://user-images.githubusercontent.com/40214178/159981832-68ea36e5-c261-49ff-8bc0-874a6556a171.png)

![Screenshot (21)](https://user-images.githubusercontent.com/40214178/159981865-d924b642-ed88-4647-a818-af5acf1054ee.png)



---- FILES/FOLDERS ----

config folder:
  - Contains the session.js file which maintains all user sessions.

data folder:
  - Contains the database.js file which stores the database information.

public folder:
  - Contains styles and scripts folders
    - styles folder contains all the styling for my webpages
    - scripts folder has all my front end javascript which uses DOM and AJAX to send requests to the server.

views folder:
  - Contains all front end ejs files that are displayed on the website 

app.js
  - This is my web server implementation using express which serves my webpages and functionality of my project.

package.json
  - The JSON file used to install all my node packages/dependencies. In the main directory run the comman "npm install" to install the required dependencies.

---- SYSTEM EXTENSIONS ----

The NPM modules and dependencies I have in my system are:
 - express
 - express-session
 - ejs
 - mongodb
 - stripe
 - csurf
 - bcryptjs
 - connect-mongodb-session
 - multer
 - uuid

To test it out, clone it and then install all dependencies using npm i or npm install, run npm start and run localhost:3000 or 127.0.0.1:3000 on your browser.
