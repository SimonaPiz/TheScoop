# <img src="https://github.com/SimonaPiz/TheScoop/blob/main/favicon.png" width="25px" alt="icon The Scoop" title="icon The Scoop"/>  The Scoop
> An article submission web app - I created all of the routing and database logic

<img src="https://github.com/SimonaPiz/TheScoop/blob/main/anteprima03.png" width="800px" alt="preview" title="preview"/>

## Table of Contents
* [General Info](#general-information)
    * [Features](#features)
    * [Implementation Details](#implementation-details)
    * [Test](#test)
* [Technologies Used](#technologies-used)
* [Setup](#setup)
* [Acknowledgements](#acknowledgements)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information

### Features

The Scoop allows users to:
- Create and log in to custom username handles
- Submit, edit, and delete articles containing a link and description
- Upvote and downvote articles
- Create, edit, and delete comments on articles
- Upvote and downvote comments
- View all of a user's articles and comments

You can view all of this functionality in action in the video below: [▶](https://content.codecademy.com/programs/build-apis/solution-videos/TheScoopFinal480.mov)


### Implementation Details

To complete this project, I needed to add for Comments:
  - [x] the database information
    - ✔ [issue 3](https://github.com/SimonaPiz/TheScoop/issues/3)
  - [x] and server routes
    - ✔ [issue 4](https://github.com/SimonaPiz/TheScoop/issues/4)

Bonus: YAML Saving and Loading

  - [x] I used YAML for saving the database object to ensure it is able to be restored. Functions:
    - **loadDatabase**
    - **saveDatabase**
    - ✔ [issue 6](https://github.com/SimonaPiz/TheScoop/issues/6)


### Test

A testing suite has been provided.
- ✔ All test passed
  
  ![test results](https://user-images.githubusercontent.com/91121660/274607082-1d3a9940-6dca-4c51-a3a5-358651c1e8d7.png)

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
