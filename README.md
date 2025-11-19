# Student Life Toolking Backend API

### Overview
Student Life Toolking is a **RESTful backend API** built with Node.js, Express.js, and MongoDB to help students **organize their daily academic life**.  
This API allows users to manage classes, track budgets, plan study goals, and generate exam questions efficiently.  

It powers a **full-stack MERN application** where students can:
- Add, update, delete, and view classes.
- Track income and expenses with validation.
- Create study goals, add tasks, and monitor completion.
- Generate questions based on subject, topic, type, and difficulty.

---

### Tech Stack & Tools
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB, Mongoose  
- **Others:** CORS, dotenv  
- **Development Tools:** VSCode, Postman  

---

### Features

####  Class Schedule
- Add, update, delete, and fetch all classes.
- Get today's classes based on the current weekday.
- Store class details like subject, professor, time, location, day, and type.
- 
#### Budget Tracker
- Add income and expense transactions with validation.
- Calculate total income, expenses, balance, and used percentage.
- Prevent overspending by validating expenses against available income.
- Fetch all transactions and totals.

#### Study Planner
- Add and manage study goals with priority, category, and deadlines.
- Add tasks to each goal and toggle their completion status.
- Delete goals and keep track of completed tasks per goal.

####  Generated Questions
- Generate exam questions dynamically.
- Filter questions by subject, topic, type, difficulty, and number of questions.
- Return random questions matching the criteria.


