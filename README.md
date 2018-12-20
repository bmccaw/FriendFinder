# FriendFinder

A compatibility-based 'FriendFinder' application using Node and Express.

Currently deployed to Heroku at : https://bmc-friendfinder.herokuapp.com/

# Description

Friend Finder is a match-making app that takes in user-input on the front-end and compares it to what is already stored in the back-end, providing the best possible match based on the answers given. The user is given a 10 question survey and are asked to answer on a 1 (Strongly Disagree) to 5 (Strongly Agree) scale for each question. The existing record with the closest set of responses (the set with the lowest absolute difference for all combined questions) will be matched to the user when the hit submit.

This application was created using Node.js and Express.js on the back end and the Materialize CSS framework on the front end. 

# Operating Locally

Clone the repository to you machine and npm install to install dependencies. The app is currently set to run on Port 3000.
