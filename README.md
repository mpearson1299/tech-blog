# tech-blog

Welcome to Tech-Blog! This is a web application built with JavaScript, Handlebars, and Schema. It serves as a platform for tech enthusiasts to share their knowledge, experiences, and insights with the community.

## Features

- User Authentication: Users can sign up, log in, and log out securely to access the full functionality of the blog.
- Create and Edit Posts: Registered users can create new blog posts, edit their existing posts, and delete them if needed.
- Commenting System: Users can engage in discussions by commenting on blog posts, fostering a sense of community.
- User Profiles: Each user has a personal profile page where their posts and comments are displayed.
- Search Functionality: Users can search for specific blog posts or topics of interest.
- User-Friendly Interface: The application is designed to be intuitive and visually appealing to enhance the user experience.

## Installation

To run Tech-Blog locally on your machine, follow these steps:

1. Clone the repository from GitHub:

   ```bash
   git clone https://github.com/mpearson1299/tech-blog.git
   ```

2. Install the required dependencies by running the following command in the project's root directory:

   ```bash
   npm install
   ```

3. Set up the database:
   - Create a `.env` file in the root directory of the project.
   - Inside the `.env` file, specify your database credentials using the following format:

     ```plaintext
     DB_NAME=your_database_name
     DB_USER=your_username
     DB_PASSWORD=your_password
     ```

4. Run the application by executing the following command:

   ```bash
   npm start
   ```

5. Once the server is running, you can access the Tech-Blog application in your browser at `http://localhost:3000`.

## Technologies Used

- JavaScript
- Handlebars
- Schema
- Node.js
- Express.js
- Sequelize
- MySQL

## Contributing

Contributions to Tech-Blog are always welcome! If you'd like to contribute, please follow these guidelines:

1. Fork the repository.
2. Create your feature branch: `git checkout -b my-new-feature`.
3. Commit your changes: `git commit -am 'Add some feature'`.
4. Push the branch to your forked repository: `git push origin my-new-feature`.
5. Submit a pull request.

## License

This project is licensed under the [MIT License](https://opensource.org/licenses/MIT).