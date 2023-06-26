<div align="center">
   <h1>Node-Express-MVC-API</h1>
   <h3>Hands-On Learning Repository</h3>
   <p><em>A hands-on learning repository for Node.js and Express.  Covering foundational concepts to advanced features like JWT authentication and MongoDB integration.  Creating powerful APIs, which include building a web server and implementing user authentication and authorization.</em><p>
   <img src="https://skillicons.dev/icons?i=nodejs,express,mongo,js" />
</div>
<br/>

<!-- ---------------------------------------------------------------- -->
---

# **INTRODUCTION**

This is a Node.js and Express Hands-On Learning Repository. Covering foundational concepts to advanced features like JWT authentication and MongoDB integration.
Learning to create APIs, including building a web server and implementing user authentication and authorization.

### **Table of Contents**

- [Main Objectives & Features](🎯)
- [Branches](🎯)
- [Running Locally](🎯)
- [Contributing](🎯)
- [License](🎯)
- <em>[Node best practices](https://github.com/goldbergyoni/nodebestpractices) </em>

<br/>

<!-- ---------------------------------------------------------------- -->
---

# **MAIN OBJECTIVES & FEATURES**

1. <strong>Basic Web Server Setup:</strong><br/>
This feature involves setting up a foundational web server using Node.js and Express. It includes creating routes, handling requests, and sending responses.

2. <strong>Middleware (Built-in and 3rd Party):</strong><br/>
Middleware functions are integral to Express. This feature covers both built-in mid
dleware provided by Express and the utilization of third-party middleware for tasks like request parsing, authentication, and error handling.

3. <strong>Handling CORS (Cross-Origin Resource Sharing):</strong><br/>
CORS is a security feature implemented by web browsers that restricts web applications running at one origin from making requests to a 
different origin. This feature shows how to handle CORS headers to allow or deny requests from different origins.

4. <strong>Best Practices with Error Handling:</strong><br/>
Proper error handling is crucial in any application. This feature focuses on implementing best practices for error handling, including 
how to capture and respond to different types of errors effectively.

5. <strong>Routing (Different Endpoints and Dynamic Routing with Express):</strong><br/>
Routing is fundamental to building APIs. This feature delves into setting up various endpoints or routes to handle different types of 
requests (GET, POST, PUT, DELETE). It also covers dynamic routing, where routes are defined with variables.

6. <strong>Async CRUD (Create, Read, Update, Delete) Operations:</strong><br/>
CRUD operations are core functionalities of any API. This feature demonstrates how to perform these operations asynchronously, ensuring 
efficiency and responsiveness, especially when dealing with databases.

7. <strong>Organizing Codebase Using MVC (Model-View-Controller) Method:</strong><br/>
The MVC pattern is widely used for structuring applications. This feature guides on how to organize code into Models (for data 
management), Views (for rendering), and Controllers (for managing requests and responses) to enhance maintainability and scalability.

8. <strong>Integrating and Interacting with a MongoDB Database, Using Mongoose (ODM):</strong><br/>
MongoDB is a popular NoSQL database, and Mongoose is an ODM (Object Document Mapper) that simplifies interactions with it. This feature 
covers how to connect, query, and manipulate data in a MongoDB database using Mongoose.

9. <strong>Implementing Authentication Mechanisms for User Management:</strong><br/>
This feature is crucial for securing APIs. It includes implementing various authentication mechanisms, such as JSON Web Tokens (JWT), 
which provide secure authentication tokens, as well as managing user roles and authorizations to control access.

   - <strong>JWT Authentication:</strong><br/>
Implementing JWT authentication involves generating, validating, and managing tokens for secure communication between the client and server.

   - <strong>User Roles:</strong><br/>
User roles are used to categorize users based on their privileges. This feature includes setting up roles like admin, user, etc., and assigning appropriate permissions.

   - <strong>Authorization:</strong><br/>
Authorization ensures that only authenticated users with specific roles or permissions can access certain routes or perform certain actions within the application.












<br/>

<!-- ---------------------------------------------------------------- -->
---

# **BRANCHES:**

[1. Basic Web Server Setup](🎯)

[2. Incorporate ExpressJs](🎯)

[3. Setting up Middleware](🎯)

[4. Setup Routing](🎯)

[5. MVC REST API](🎯)

[6. Setting up Authentication](🎯)

[7. Create JWT Auth](🎯)

[8. User Roles | Authorization](🎯)

[9. Intro to MongoDB & Mongoose](🎯)

[10. Mongoose Data Models](🎯)

[11. Async CRUD Operations](🎯)


<br/>

<!-- ---------------------------------------------------------------- -->


<!-- ---------------------------------------------------------------- -->
---
# **RUNNING LOCALLY**

#### Prerequisites :

<em>Node version 18.15.x</em>

##### 1. Cloning the repository

```shell
git clone
```

##### 2. Install packages

```shell
npm i
```

##### 3. Setup MongoDB URL

```js
server.ts;

const MONGO_URL = ""; // INSERT YOUR DB URI
```

<br/>

#### Finally, run app w/ available commands

Running commands with npm `npm run [command]`

| command | description                              |
| :------ | :--------------------------------------- |
| `start` | Starts a development instance of the app |

<br/>

---

# **CONTRIBUTING**

If you'd like to contribute to this repository by adding more exercises, fixing bugs, or improving documentation, please feel free to submit a pull request. Your contributions are greatly appreciated!

<br/>


---

# **LICENSE**

This project is licensed under the [MIT License](🎯).

<br/>

---

# **FUTURE TOPICS**



<!-- Small container -->
<details>
<summary> Click here to see future topics: </summary>
<br/>

- [x]  <strong>Testing: </strong><br/> Learn about testing frameworks like Mocha, Chai, and Jest to write automated tests for your APIs. This will help ensure your code is robust and reliable.

- [x]  <strong>Validation: </strong><br/> Explore libraries like Joi or express-validator to validate incoming data before processing it. This helps in maintaining data integrity.

- [x]  <strong>Error Handling: </strong><br/> Consider diving deeper into different strategies for handling errors, such as custom error classes, error middleware, or even implementing global error handling.

- [x]  <strong>Logging and Debugging: </strong><br/> Familiarize yourself with logging techniques and tools (e.g., Winston, Bunyan) to track application behavior. Also, learn how to debug Node.js applications effectively.

- [ ]  <strong>Deployment and Hosting: </strong><br/> Understand how to deploy your Node.js application on platforms like Heroku, AWS, or other cloud providers. This involves setting up environments, managing databases, and configuring web servers.

- [ ]  <strong>Containerization and Orchestration: </strong><br/> Learn about Docker for containerization and Kubernetes for orchestration. This allows you to package your application and its dependencies into a standardized unit for easier deployment and scaling.

- [x]  <strong>GraphQL: </strong><br/> Consider learning GraphQL as an alternative to REST APIs. It offers more flexibility for clients to request exactly the data they need.

- [x]  <strong>Real-time Web Applications: </strong><br/> Explore technologies like WebSockets or libraries like Socket.io for building real-time features in your applications.

- [ ]  <strong>Security Best Practices: </strong><br/> Study common security vulnerabilities like Cross-Site Scripting (XSS), SQL Injection, and CSRF attacks. Learn how to prevent them in your applications.

- [ ]  <strong>Performance Optimization: </strong><br/> Explore techniques like caching, load balancing, and optimizing database queries to improve the performance of your API.

- [ ]  <strong>Documentation: </strong><br/> Consider generating API documentation using tools like Swagger or Postman. This helps other developers understand how to use your API.

- [ ]  <strong>Continuous Integration and Deployment (CI/CD): </strong><br/> Learn how to set up automated pipelines for testing, building, and deploying your application.

<!-- CLOSING DIV -->
</details>
<br/>
