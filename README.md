# Module 10 Assignment 10A: User Authentication with a Laravel Starter Kit



## Short-Answer Questions

**1. In your own words, what is the difference between authentication and authorization?**
Authentication verifies who a user is. Authorization determines what the verified user is allowed to do or access.

**2. Why are passwords hashed instead of stored as plain text?**
Passwords are hashed using a one-way scrambling algorithm so that the original password is not actually saved in a database. A hacker would only see gibberish, not a real password. 

**3. Which package registers the /login and /register routes, and which artisan command lets you see them?**
Laravel automatically registers /login and /register routes in the background. You can see active routes by using  php artisan route:list command in the terminal.

**4. What does the auth middleware do, and what happens when a logged-out user hits a page protected by it?**
The auth middleware is a security checkpoint in front of a route. 

---

## Project Setup 


1. Clone the repository.
2. Run composer install to install PHP dependencies.
3. Run npm install and npm run build to compile assets.
4. Copy .env.example to .env and run php artisan key:generate.
5. Create an empty file at database/database.sqlite.
6. Run php artisan migrate to set up the database tables.
7. Run php artisan serve to start the local development server.