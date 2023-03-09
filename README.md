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
</ul>


