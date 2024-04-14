# Blog-API-Project

This project implements a straightforward API designed for handling blog post management. It offers functionalities to create, read, update, and delete blog posts. The backend is developed using Node.js and Express.js, while Axios facilitates communication between the frontend and the API. Additionally, EJS is utilized for templating, and CSS is employed for styling purposes.

## Features

- **Create Post:** Allows users to create new blog posts by sending a POST request with the post data.
- **Read Post:** Provides endpoints to fetch all posts or a specific post by its ID.
- **Update Post:** Allows users to update an existing post by sending a PATCH request with the updated post data.
- **Delete Post:** Enables users to delete a post by sending a DELETE request with the post ID.

## Technologies Used

- **Node.js:** A JavaScript runtime environment used for building server-side applications.
- **Express.js:** A web application framework for Node.js used for building APIs and web applications.
- **Axios:** A promise-based HTTP client for making HTTP requests from the frontend to the backend API.
- **CSS:** Used for styling the frontend of the application.
- **EJS:** Employed for server-side templating, facilitating dynamic content rendering.

## Project Structure

The project consists of the following main files:

Here's the revised project structure with the additional files:

1. **index.js:** 
   - Backend server file responsible for setting up the Express.js server and defining routes for CRUD operations on blog posts.

2. **server.js:** 
   - Frontend server file serving static files and defining routes for rendering frontend pages and managing user interactions.

3. **modify.ejs:** 
   - EJS template rendering the form used to edit or create a blog post.

4. **index.ejs:** 
   - EJS template rendering the main blog page, displaying a list of posts.

5. **main.css:** 
   - Cascading Style Sheets (CSS) file containing styling rules for HTML elements in the frontend, enhancing the application's presentation and user experience.

6. **package.json:** 
   - Metadata file for the Node.js project, including configurations, dependencies, scripts, and version information.

7. **package-lock.json:** 
   - Automatically generated file providing information about the exact version of each dependency installed in the project, ensuring consistency across development environments.

## Usage

1. Clone the repository to your local machine.
2. Install dependencies using npm: `npm install`.
3. Start the backend server: `node index.js`.
4. Start the frontend server: `node server.js`.
5. Open your web browser and navigate to `http://localhost:3000` to view the blog.

## API Endpoints

- **GET /posts:** Fetch all blog posts.
- **GET /posts/:id:** Fetch a specific blog post by its ID.
- **POST /posts:** Create a new blog post.
- **PATCH /posts/:id:** Update an existing blog post by its ID.
- **DELETE /posts/:id:** Delete a blog post by its ID.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or new features to propose, feel free to open an issue or submit a pull request.

