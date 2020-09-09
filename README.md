# **Web Application for Sharing Public Transport Experience**

This solution was implemented for a Web Technologies project in a team of four.

The purpose of the application is to allow logged in and anonymous users to share public transport experience.

## Features and technologies

### Front-end

The front-end of this project is done using the React framework with the help of Material-UI. It presents the user with all feedbacks already registered, while also letting him add new ones.

### Back-end

The back-end of this application is quite-complex, following the Model-View-Controller architecture, where the React application is the View, which allows faster development and easier modifications. The Rest API communicates with the front end via HTTP, done in ExpressJS, having a MySQL Database managed trough Sequelize ORM.
