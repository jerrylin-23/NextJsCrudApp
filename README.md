# NextJsCrudApp
Basic Crud Application for taking notes with a working database.

In your terminal enter:
npx create-next-app@latest --ts

Download Pocketbase from pocketbase.io (The database we will be using) for the respective operating system you will be using
unzip the .exe into the root folder of the project.

in the terminal cd to the project folder

Start up the database with the command; ./pocketbase serve

Open the Admin UI, create collection, and update security rules to allow read/write access.

Navigate to next.config.js (should be auto created)

Add experimental: { appDir: true } 
