# The Scoop

## Project Overview

In this project, you will build all of the routing and database logic for an article submission web app called The Scoop.

The Scoop allows users to:
- Create and log in to custom username handles
- Submit, edit, and delete articles containing a link and description
- Upvote and downvote articles
- Create, edit, and delete comments on articles
- Upvote and downvote comments
- View all of a user's articles and comments

You can view all of this functionality in action in the video below:+


## Implementation Details

To complete this project, I needed to add for Comments:
- [ ] the database information 
- [ ] and server routes

### Bonus: YAML Saving and Loading

Currently every time you start and stop your server, your database object will get erased as it isn't being saved anywhere. There are many potential formats for saving the database object to ensure it is able to be restored. For this project, as a bonus, we encourage you to use YAML. You will write two functions, one that saves your database object to YAML after each server call, and another that loads the database object when the server starts. We have implemented the logic for calling these functions, it is your task to find appropriate JavaScript modules for this functionality and writing the following functions:

**loadDatabase**

- Reads a YAML file containing the database and returns a JavaScript object representing the database

**saveDatabase**

- Writes the current value of `database` to a YAML file

Implementing this Bonus will be a tough challenge, as you'll probably have to use a new external library, and you may need to add to or edit the rather complicated `requestHandler` function that we have provided. We use [Figg](https://www.npmjs.com/package/figg) in our solution code, but you can implement saving and loading in many ways, so don't feel like you have to take the same approach that we did.

## Testing

A testing suite has been provided for you, checking for all essential functionality and
edge cases.

To run these tests, first, open the root project directory in your terminal. Then run `npm install` to install
all necessary testing dependencies (if you haven't already).
Finally, run `npm test`. You will see a list of tests that ran with information
about whether or not each test passed. After this list, you will see more specific output
about why each failing test failed.

As you implement functionality, run the tests to
ensure you are creating correctly named variables and functions that return the proper values.
The tests will additionally help you identify edge cases that you may not have anticipated
when first writing the functions.

## Setup
To start the server, run 
```
  $ npm install
``` 
and then 
```
  $ node server.js
``` 
from the root directory of this project.

To view your local version of the site, open **index.html** in a web browser.