Recreate the following

![Challenge Outcome](/challange-assets/challenge-outcome.png)

---

**Details**

Backend:
* Inside the /backend directory is a mock server that returns a list of appointments.
* To run the server, run the following commands: ```npm ci``` and `npm start`
* It will expose the following endpoint: http://localhost:3000/appointments which will return an array of cat appointment objects
* To see the contents of the mocked database navigate to `/backend` and open the `database.json` file.


Frontend:
* Inside the /frontend directory is an angular project
* To run it, run the following commands: `npm ci` and `npm start`.
---

**Challenges:**

Backend (Optional, only if you know NodeJS, otherwise use the provided mock server in the backend folder)
* Create a REST NodeJs typescript application to be able to get, add, delete, and update cat appointments, using the database.json as a database.
  * Use TypeScript
  * Use Express
  * Create GET, POST, PUT, and DELETE routes
  * Make it developer friendly, compiling the TypeScript in JavaScript when detecting changes on save.

Frontend
* Create a service and the functionality necessary to retrieve the existing appointments and save a new appointment.
* Create the necessary components to:
  * Display the data of an appointment
  * Display the list of appointments
  * Take the user input and create a new appointment.

---
**Rules:**
* You can search for solutions online. (Angular documentation, StackOverflow, etc)
* Implement the solution as you would implement a feature in a real project.

**Optional:**
* Use rxjs
* Use ngrx

**During the interview:**
* You have to explain your thought process.
