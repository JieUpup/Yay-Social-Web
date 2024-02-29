# Yay
## Project
######  Yay Socical Web Application

Social media web application clone along the lines of Signal, Facebook, and Twitter. This will include functionality of posting, commenting, and sharing other user’s posts, user authentication, notifications, and private messaging.
Using React we will able to develope our website, as well as using Node.js to handle package management.
## Technical Goals
###### Posts, Comments, Sharing:
Users will be able to custom tailor a ”post” to be accessible from other devices. A post will be described as a text or image upload.
The author of the post as well as other users of the web application will be able to “comment” on existing posts. Comment defined as text or image response. 
Users will be able to “share” an existing post. Share is defined as posting a link or iframe instance of the other post.
###### User Authentication:
Users will be able to login with their specific data to access posting, commenting, and sharing functionality.
We aim to utilize JWT for authentication rather than using external libraries such as Passport.js
Users' data will be stored in a database(MongoDB tentatively) to allow for recalling of existing post and profile pages.
###### Notifications:
Users will be notified through email and or browser for comments or shares on an existing post.
Users can turn on or off notifications on publication of posts.
## Languages/Frameworks
HTML
CSS
JavaScript

React
Node.js

## Database
MongoDB

# How to Start:

1. Start a mongoDB through docker.
2. Start the config nginx through docker.

3. Open a terminal, change to the server directory.
https://nodejs.org/en/download/

Download and run node js.
```
npm i
npm start
```

4. Open another terminal, change to the client directory
```
npm i
npm start
```

Website should launch locally in browser.

