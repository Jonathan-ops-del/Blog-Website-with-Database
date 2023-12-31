# Blog-Website-with-Database
Blog Website with Database

This challenge project was presented by Angela Yu's Online Web Development Bootcamp course. The purpose of this project is to demonstrate on how to add the MongoDB Database to our intial Blog Website Application built from Nodejs & EJS Templating. I have also provided a link below to this application which will be running off of Heroku & MongoDB Atlas. The project has two branches - the master branch, and the deploy branch. We will work off the master branch to have our application running locally, while the deploy branch is presented to display our code-base for the live application. 

Once you have cloned this project into your preferred code editor, you can go ahead and open up your HyperTerminal. 

Run this project using npm.

1)  In your HyperTerminal you will enter in "mongod" to have your local database running. In the second tab, you may enter in "mongo" to open up your mongo shell.
2)  In the master branch, you may go into your code editor terminal and install your dependencies by entering in "npm install".
3)  Once installed you may now enter in "nodemon app.js" to have the terminal running. You may now open up your web browser and enter in - http://localhost:3000/.
4)  In this web application you will have a home page, about us page, contact us page, compose page, and a posts page directed from your home page blogs.
5)  In the compose page - http://localhost:3000/compose - you can make a post request consisting of a blog Title & Post. Once you have published this post , you will be redirected to your home page where you will see all your blog posts. Note that these blog posts are limited in character, you will need to click on "Read me" to see the full content of the posts and will be directed to its individual page - ie. http://localhost:3000/posts/:postID.
6)  Once you are done entering the posts you have wanted to enter, you can go to your shell as well to see it in your database. You will need to go to your HyperTerminal. Once in your mongo shell, you can enter in "show dbs" , then you     will need to enter "use blogDB." Once in your blogDB database, you can now enter in "show collections", and you should see your "posts" collections. Now to see your documents in this collection you will now need to enter "db.posts.find()" , where you will find all your documents.
7)  To see the deployment code of the Blog Project, which is running live on the Heroku server , and using MongoDB Atlas to host its database, you will need to go to the code editor terminal and enter "git checkout deploy."

***NOTE - The link to this live project can be found here - https://my-blog-database-app-f4ad477feaf7.herokuapp.com/
