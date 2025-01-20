Overview

Unsolved HQ is an interactive platform for true crime enthusiasts. It allows users to explore unsolved mysteries, leave their own theories, and engage with a community of like-minded individuals. The site features a guestbook-style message system, an Interactive Case Solver, and a Mystery Wall to provide a dynamic and engaging experience.

-----------------------------------------------------------------------------------------------------

Core Features:

Interactive Case Solver

Users can analyze and theorize about unsolved crimes.

Includes case details, evidence, and user-submitted theories.

Mystery Wall

A visually engaging wall displaying unsolved cases.

Dynamic updates based on community interaction.

Guestbook-Style Message System

Allows users to leave comments, theories, and feedback.

Supports a seamless and responsive user experience.

Stretch Features:

Filter and sort cases by category (e.g., cold cases, missing persons).

Like and comment functionality for individual theories.

Admin tools for moderating content.

---------------------------------------------------------------------------------------------------------------------------------

Technologies Used

Frontend: React (with Vite for fast builds)

Backend: Express.js and PostgreSQL

Database: Supabase for data storage and API integration

Styling: Chakra UI for consistent and responsive design

Deployment: Render (or any other preferred platform)

--------------------------------------------------------------------------------------------------------------------

Installation

Prerequisites:

Node.js and npm installed

PostgreSQL database set up locally or via Supabase

Steps:

Clone the repository:

git clone https://github.com/bmljlee1/Crime-solver-website.git

Navigate to the project directory:

cd Crime-solver-website

Install dependencies:

npm install

Set up environment variables:

Create a .env file in the root directory.

Add the following variables:

DATABASE_URL=your_database_url
SUPABASE_URL=your_supabase_url
SUPABASE_KEY=your_supabase_key

Start the development server:

npm run dev

Access the site at http://localhost:3000.

--------------------------------------------------------------------------------------------------------------------

Usage

Navigate to the homepage to explore cases and theories.

Use the search bar to find specific cases.

Submit your theories via the guestbook form.

Interact with other users by liking or commenting on theories.

-------------------------------------------------------------------------------------------------------------------------

Development

Database Schema:

The project uses the following main tables:

Users: Stores user information (e.g., username, email).

Theories: Contains user-submitted theories and case IDs.

Cases: Details of unsolved crimes, including evidence and timelines.

Scripts:

Start server: npm run server

Run frontend: npm run dev

Seed database: node seed.js

-------------------------------------------------------------------------------------------------------------------------------

Contribution

Contributions are welcome! Follow these steps:

Fork the repository.

Create a new branch for your feature:

git checkout -b feature-name

Commit your changes:

git commit -m "Add your feature description"

Push to your fork:

git push origin feature-name

Open a pull request.

------------------------------------------------------------------------------------------------------------

Contact

For questions or feedback, contact:

Name: Jonathan Lee

GitHub: bmljlee1




