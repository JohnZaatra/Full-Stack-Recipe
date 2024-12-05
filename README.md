# Full-Stack Recipe Search Engine Project

This project is a **full-stack application** developed using **Vue.js** for the frontend and **Node.js** with **MySQL** for the backend. It is a comprehensive, professional-grade solution designed to manage and search a vast array of recipes. It leverages several important open-source libraries and frameworks, offering a rich and interactive user experience. The project showcases the ability to design, develop, and deploy a complete web application.

---

## Key Features

- **User Authentication & Authorization:** Implemented with custom login and registration mechanisms, allowing users to securely access their personalized content (like saved recipes and favorite dishes).
- **Recipe Search Engine:** A powerful search system enabling users to find recipes by various criteria.
- **Personalized User Experience:** Users can save their favorite recipes, create custom recipes, and manage a list of family recipes.
- **Dynamic Navigation:** Navbar adapts based on the user’s login status, offering personalized options such as 'Favorites', 'My Recipes', and 'Family Recipes'.
- **Responsive & Modern UI:** Built using **Vue.js**, **Bootstrap**, and **BootstrapVue**, ensuring the application is mobile-friendly and aesthetically pleasing.

---

## Technologies Used

### Frontend:
- **Vue.js:** A progressive JavaScript framework used for building the user interface.
- **Vue Router:** Manages routing and navigation between pages in the app.
- **Axios:** For handling HTTP requests to the backend API, with automatic cookie handling for user authentication.
- **Bootstrap 4 & BootstrapVue:** Used for responsive, mobile-first design components like navigation, buttons, modals, and forms.
- **Vuelidate:** For real-time client-side validation of form inputs.
- **Vue Cookies:** To handle cookie management for the application.

### Backend:
- **Node.js:** Used for creating a backend API that interacts with the MySQL database.
- **MySQL:** Database used for storing recipes, user data, and other related information. The database is hosted locally on the developer's computer server.
- **Express.js:** Web application framework for Node.js that simplifies routing and handling HTTP requests.
- **Axios (Frontend-to-Backend Communication):** Used to make asynchronous requests from the Vue.js frontend to the Node.js backend.

---

## Project Architecture

### Frontend:
- The frontend is built using **Vue.js**, with a clean separation between components, views, and routes.
- **Vue Router** manages different routes, like Home, Search, Login, and Profile pages, enabling seamless navigation.
- **State Management**: The application’s shared data (like user session information) is stored globally and accessed across different components.

### Backend:
- The backend is developed in **Node.js** using **Express** for routing and **Axios** for making requests to the database.
- **MySQL** is used as the relational database for storing recipe data, user information, and search history.

---

## How It Works

1. **Local Setup**:  
   This project is hosted and run locally. The backend API communicates with a MySQL database installed on your computer, allowing users to interact with the system via a web browser. There is no live demo, but you can easily set up the project on your local machine to test its functionality.

2. **User Registration and Login**:  
   Users can create an account by registering with their credentials. Upon logging in, they gain access to personalized features such as saving recipes, managing favorites, and adding custom recipes.

3. **Recipe Search & View**:  
   Users can search through the recipe database with multiple filters and view detailed recipe pages. They can also rate recipes and save them to their profile.

4. **Recipe Management**:  
   Users have the ability to create their own recipes and save them for later use. Additionally, they can organize recipes into their 'Favorites' or 'Family Recipes' sections for quick access.

---

## Installation

### Prerequisites

- **Node.js** (v16.x or higher)
- **MySQL** (v8.x or higher)

### Steps to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/recipe-search-engine.git
   cd recipe-search-engine
2. **Backend Setup:**
**Navigate to the backend directory and install dependencies:**
   ```bash
   cd backend
   npm install
*Set up your MySQL database:
*Create a new database (e.g., recipe_search_db).
*Import the schema provided in backend/db/schema.sql into your database.
*Update the database connection settings in backend/config/db.js with your MySQL credentials.
*Start the backend server:*
   ```bash
   npm start
```
3. **Frontend Setup:**
*Navigate to the frontend directory and install dependencies:
   ```bash
   cd frontend
   npm install
*Run the frontend development server:
   ```bash
npm run serve
   ```
4. **Access the Application:**
* Open your browser and go to http://localhost:8080 to see the application in action.

# Future Enhancements

* Deploy to Production: While the project currently runs locally, future work will involve deploying it to cloud platforms like AWS, Heroku, or DigitalOcean for production use.
* Advanced Search Filters: Implement more sophisticated filtering and sorting options, such as searching by ingredients, cooking time, or difficulty level.
* Improved User Interface: Continue enhancing the UI for a more seamless and intuitive user experience.

# Contribution

Feel free to fork this repository and submit pull requests. Any contributions, suggestions, or improvements are welcome!
License

This project is licensed under the MIT License.
Conclusion

This full-stack recipe search engine is a showcase of modern web development practices and open-source technologies. By using Vue.js, Node.js, MySQL, and other essential tools, it demonstrates a high level of development expertise and is a perfect project for anyone looking to break into web development or show off their skills to potential employers. The project is a great example of clean, maintainable code and a user-centered design.
