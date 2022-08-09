# MERN Stack project

In this project I will build a full-stack MERN application - specifically an employee database with _MongoDB_, _Express.JS_, _React.JS_ and _Node.JS_
I have used the Bootstrap library for styling in this project to better focus on the MERN elements.

![ScreenShot](/readme-image.PNG)

In my project I have set up four react components to allow for front-end interaction: create.js, edit.js, navbar.js and recordlist.js.

Recordlist is the default view seen in the screenshot above.

When clicking on the "Create Record" button we are redirected to the _edit.js_ component seen below:

![ScreenShot](/edit-image.PNG)

We can create records using MongoDB which is connected via the file within the server folder

## Running the Application

To run the app the following needs to be executed in the command line.

Within the server directory: `node server.js`

And then back in the client directory: `npm start`
