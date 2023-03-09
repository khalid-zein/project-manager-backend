# project-manager-backend

## Learning Goals
<ul>
  <li>Build a web basic API with Sinatra and Active Record to support a React frontend</li>
</ul>

  
## Introduction


Congrats on getting through all the material for Phase 3! Now's the time to put it all together and build something from scratch to reinforce what you know and expand your horizons.


The focus of this project is building a Sinatra API backend that uses Active Record to access and persist data in a database, which will be used by a separate React frontend that interacts with the database via the API.



## Requirements
For this project, you must:

<ul>
  <li>Use Active Record to interact with a database.</li>
  <li>Have at least two models with a one-to-many relationship.</li>
  <li>At a minimum, set up the following API routes in Sinatra:
   <ul>
     <li>create and read actions for both models</li>
     <li>full CRUD capability for one of the models: The update action should be implemented using a form  that is pre-filled with existing values for the object. On submission of the form, the object should update. Note: Using a like button or similar will not meet the update requirement.</li>
    </ul>
  </li>
  <li>Build a separate React frontend application that interacts with the API to perform CRUD actions.</li>
  <li>Implement proper front end state management. You should be updating state using a setState function after receiving your response from a POST, PATCH, or DELETE request. You should NOT be relying on a GET request to update state.</li>
  <li>Use good OO design patterns. You should have separate classes for each of your models, and create instance and class methods as necessary.</li>
  <li>Routes in your application (both client side and back end) should follow RESTful conventions.</li>
  <li>Use your back end optimally. Pass JSON for related associations to the front end from the back end. You should use active record methods in your controller to grab the needed data from your database and provide as JSON to the front end. You should NOT be relying on filtering front end state or a separate fetch request to retrieve related data.</li>
</ul>

For example, build a todo list application with a React frontend interface and a Sinatra backend API, where a user can:


- **Create** a new todo
- **Read** a list of all todos
- **Update** an individual todo
- **Delete** a todo


A `Todo` can be tagged with a `Category`, so that each todo _belongs to_ a
category and each category _has many_ todos.


