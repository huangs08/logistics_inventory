# Logistics Inventory

### Project description
The goal of this project is to serve as an inventory web tracking application for a logistics company.

### Technology overview
|                          | Technology/Tool                                                                                                                                                                                                                                                                                                                       
| ------------------------ | ------------------------ 
| Frontend                 | React + Typescript + Material UI
| Backend                  | Typescript + NodeJs + Express + Tsyringe + Jest + MySQL + Sequelize

## Project Setup

Prerequisites:

- NodeJS (version 12 or above)
- Typescript
- MySQL

Setup:
1. Clone the git repository.
2. Run `npm install` in the frontend folder to install all the dependencies.
3. Run `npm install` in the backend folder to install all the dependencies.
4. Create a schema called "inventory" in your local SQL database (eg.: using MySQL Workbench).
5. Open backend/src/main/**config.js**. Notice the comments to enter your credentials for your local SQL database. Enter your credentials in the **sequelize.ts** file as well.
6. Change directory into backend/src/main and run the command `npx sequelize-cli db:migrate`. This will create the necessary tables in your schema to run the project.
7. Run `npm run dev`. This will start the backend server on port 8080.
8. Change directory into the frontend folder and run `npm start`. It will start the frontend on port 3000. If it does not open a browser, you can access it at `http://localhost:3000/`.
9. The application is good to go!
10. (Optional) If desired, change directory into the backend folder and run "npm test" to run a few tests I wrote.

**_Note_**: The item collection page will not show if you do not have any items/collections created.
