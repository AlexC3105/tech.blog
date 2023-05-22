MVC Tech Blog
This is an MVC (Model-View-Controller) tech blog application developed as part of the UCF Bootcamp. The application allows users to create an account, publish blog posts, comment on posts, and interact with other users in a tech blogging community.

Screenshot

Table of Contents
Installation
Usage
Features
Technologies Used
Contributing
License
Questions
Installation
To install and run the MVC Tech Blog application, follow these steps:

Clone the repository to your local machine.
Navigate to the project's root directory.
Run npm install to install the required dependencies.
Set up the database:
Create a MySQL database.
Update the connection details in the .env file.
Run the database schema using npm run db:create.
Start the application by running npm start.
Usage
Once the application is installed and running, you can access it through your web browser by navigating to http://localhost:3001/. The landing page will display the latest blog posts. To access all the features of the application, you need to create an account or log in if you already have one.

The MVC Tech Blog allows users to:

Create an account and log in.
Publish new blog posts with titles, content, and optional tags.
View and edit their own blog posts.
Delete their own blog posts.
Comment on blog posts from other users.
View and edit their own comments.
Delete their own comments.
View a dashboard displaying all their posts.
Features
The MVC Tech Blog application offers the following features:

User Authentication:

Users can sign up with a unique username, email, and password.
Passwords are securely hashed and stored in the database.
User sessions are managed using cookies.
Blog Posts:

Users can create, view, edit, and delete their blog posts.
Blog posts can have titles, content, and optional tags.
Users can view and comment on other users' blog posts.
Users can view a dashboard displaying their own blog posts.
Comments:

Users can comment on blog posts.
Users can view, edit, and delete their own comments.
Comment timestamps are displayed.
User Profile:

Users have a profile page displaying their information.
Users can view all their blog posts and comments on their profile page.
Technologies Used
The MVC Tech Blog application is built using the following technologies:

Node.js
Express.js
MySQL
Sequelize ORM
Handlebars.js
JavaScript
HTML
CSS
Contributing
Contributions to the MVC Tech Blog are welcome. If you find any bugs or have suggestions for improvements, please open an issue or submit a pull request.

License
This MVC Tech Blog application is licensed under the MIT License.

Questions
If you have any questions or need further assistance, please feel free to contact me via email or GitHub.

Email: sniper3105@gmail.com
GitHub: AlexC3105