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

- Bonus: YAML Saving and Loading

  - [ ] I used YAML for saving the database object to ensure it is able to be restored. Functions:
    - **loadDatabase**
    - **saveDatabase**


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