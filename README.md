A Readme that fully explains to a user how to do the following:
How to install this app on their local machine
What global installations they need and what files do they need to create that didn't come in the github repo
How to start the app in dev mode
How to make an api request in Postman (i.e what port, what url etc)
How to run tests



##**USER STORY**

+ As a user, I can land on a page when I can clicks at the login or sign up buttons and be navigated to a page where I can log in or sign up.
+ As a user, I should be able to land on a page and see a Nav Bar with a navigation link to 'wordsets','words' and 'labels'
+ As a user, I can click a navagation link to see all the words and be navigated to a page where I see a list of words
+ As a user, I should be able to click a link to create/update/delete words and be navigated to a page where I create/update/delete words.
+ As a user, I should be able to click on an individual word and be navigated to a page where I see all the details for that particular word
+ as a user, I can click on a navigation link to see all the wordsets and be navigated to a page where I see a list of wordsets.
+ As a user, I should be able to click a link to create/update/delete wordsets and be navigated to a page where I create/update/delete wordsets.
+ As a user, I should be able to click on an individual wordset and be navigated to a page where I see all the details for that particular wordset"
+ As a user, I should be able to click on a workset and add all the words to the workset.
+ As a user, I should be able to click on a workset and add all the labels to the workset.
+ As a user, I should be able to click a link to create/update/delete labels and be navigated to a page where I create/update/delete labels.
+ As a user, I should be able to click on an individual movie and be navigated to a page where I see all the details for that particular movie"

_______
##**HOW TO INSTALL THIS APP ON YOUR LOCAL MACHINE**  
*step1: On the top right corner, click the green button <> Code and choose SSH and copy the url: git@github.com:EmmaQjf/Chinese-learning-4models.git.
*step2: Open Terminal and change the current working directory to the location where you want the cloned directory.
*step3: Type git clone, and then paste the URL you copied earlier.
*step4: cd into the directionary and run npm i to install all the packages
*step5: run code . to open the code in VS.

_______
##**GLOBAL INSTALLATIONS AND FILES YOU NEED**    
1. run *git i* in terminal to install all the packages: express, mongoose, dotenv, nodemon, bcrypt, jsonwebtoken, mongodb-memory-server,morgan, jest, supertest
2. create a file .env and put in your MONGO_URI and SECRET

_______
##**HOW TO START THE APP IN DEV MODE**   
Make sure *nodemon* is installed, then run *npm run dev* in the terminal.

_______
##**how to make an api request in Postman**

user router
| method | url | |
| :---- | :----: | ----: |
| post| /users | R1C3 |
| get | /users | R2C3 |
| post| /users/login | R1C3 |
| get | /users/:id | R2C3 |
| put| /users/:id | R1C3 |
| delete | /users/:id | R2C3 |



_______
##**how to run test**
1. Check jest and supertest is installed, if not run the code npm -i D jest supertest.
2. Check jest and supertest is set up on the package.json.
 `"scripts": {
    "test": "jest --watchAll --detectOpenHandles",
    "start": "node server.js",
    "dev": "nodemon"
  },
  "jest": {
    "testEnvironment": "node"
  },`
3. Run *npm run test* in the terminal.

_______
##**How to start the app without dev mode.**
run the code: *npm run start*














