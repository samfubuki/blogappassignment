# blogappassignment
Created a blog application where one can see the blogs created and only authenticated users can create the blogs.
The application is created with the help of NodeJs Express and Mongo DB.

Initially I created routes and middlewares with the help of NodeJS and Express. Then I used Mongoose for adding blogs to database. Then I performed User authentication
with passport.js.

Ways of installing:
1. Express- npm i express
2. Mongoose - npm i mongoose
3. Passport - npm i passport

Various Routes of the application
1./posts - To view all the posts
2. /user/:username - To view a specific post created by authenticated user
3. /posts/publish - To create a post (Post can only be created by authenticated user)
4. GET/posts/:id - Get a post with id
5. POST/posts/:id - To edit a specific post
6. DELETE /posts/:id - To delete a specific post

Various references for the assignment were taken from
1. WEB DEV SIMPLIFIED youtube channel
2. NodeJS blogs on medium
3. DevTo blogs on Passport
