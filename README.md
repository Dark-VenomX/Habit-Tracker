### Habit Tracker Project Overview

#### Description
The Habit Tracker Project is developed using Node.js, EJS, CSS, JavaScript, and Bootstrap. It provides users with the ability to track their habits on a weekly basis, allowing them to add habits, mark them as done or undone, toggle them to a default setting, and delete habits as needed.

#### Features
- **Add Habit:** Users can add new habits to track.
- **Weekly Habit Tracking:**
  - **Mark as Done:** Users can mark a habit as done for the week.
  - **Mark as Undone:** Users can revert a habit back to undone status.
  - **Toggle to Default:** Users can set a habit to a default state with no action required.
  - **Delete Habit:** Users can delete habits they no longer wish to track.

#### Folder Structure
- **Index.js:** The main JavaScript file that connects to all modules, imports necessary packages, and is the entry point of the application.
- **App/db.js:** Handles the connection to MongoDB using Mongoose.
- **Assets:** Contains static files such as CSS stylesheets and images used in the application.
- **Models/HabitModel.js:** Defines the schema for the habit tracking database structure.
- **Routes/routes.js:** Defines the routes of the application and the corresponding functions triggered upon navigation.
- **Views/Habit.ejs:** The main page of the application where users interact with the user interface.

#### Installed Packages
- **body-parser:** Middleware for parsing incoming request bodies.
- **dotenv:** Loads environment variables from a `.env` file into `process.env`.
- **ejs:** Templating engine for generating HTML markup with JavaScript.
- **express:** Web framework for Node.js used for routing and middleware.
- **mongoose:** MongoDB object modeling tool designed to work in an asynchronous environment.
- **nodemon:** Utility that monitors for changes in your Node.js application and automatically restarts the server.
