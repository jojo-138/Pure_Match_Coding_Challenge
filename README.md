# Pure Match Coding Challenge

## Technologies to use for this coding question(Required):
* Node.js
* Express.js
* JWT
* Sequelize
* AWS EB
* AWS S3

## What all things you will be evaluated on?
* Naming conventions 
* Readability of the code
* Your file structure
* Error handling

## How to submit?
Reply back to the email with an open github repository.

## How you should work on it?
You work in an agile environment where your manager keeps on coming up with new requirements. The requirements are listed below, you have to change your code or your model and create migration files requirement by requirement. Create a branch and README.md(explaining your approach to solve it) for each requirement listed below. Screenshots of the api call results are appreciated in README.md but not required.

## Requirements:
### Req1:
1. Create an Express.js app and use PostgreSQL for the database.
2. Make routes where user can register. Required fields of user are name, email, and password.
3. User can login with email and password and gets a JWT token.
4. Logged in users can create a post. Post has 2 attributes: description and a photo.

## Req 2:
Your manager next week talks to the client and gives you necessary changes to be made this week.
1. A post will have an attribute when it was created.
2. Post returning api will calculate the time difference like 2s ago, 10d ago, 4w ago, 8m ago and 1yr ago.
3. A post can have multiple photos but at most 5.
4. A post can be edited.

## Req 3:
1. A post can have multiple comments. Comments will show the user who commented and the comment.
2. Need to add pagination in the post and in the comments of the post.
3. User can add friends.
4. Friends list endpoint returns friends' info and number of mutual friends.

## Best of luck! Happy Coding!