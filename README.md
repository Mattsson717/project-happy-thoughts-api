# Project Happy Thoughts API

We should have both GET request RESTful endpoints to return data, and POST request endpoints to create data.

Tech Stack: MongoDB, node.js, Express, Mongoose, Heroku

## The problem

To test the endpoints I've used Postman and MongoDB Compass to make sure is working locally before deploying it to Heroku and connecting to MongoDB Atlas.

To make my Happy Thoughts project to work, I needed to add a couple of RESTful GET and POST routes.

To push it even further I added a DELETE and PATCH requests to make it possible to delete and edit Happy Thoughts-posts.

I replaced the previously API URL with this one. If I had more time I would like to add the delete function to the frontend.
I also want to add some sort of an Edit button to the frontend to test the PATCH request.

We can:

- GET: endpoints,
- GET: list of posts, maximum 20 posts and sorted by date (recent first),
- POST: create a post,
- POST: like a post by increasing the hearts by 1,
- DELETE: delete a post,
- PATCH: edit a post

## View it live

Frontend: https://mattssons-happythoughts.netlify.app/
Backend: https://happy-thoughts-patrik.herokuapp.com/
