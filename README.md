# **CS-465 Full-Stack Development I**

![image](https://github.com/RBuono86/CS-465/assets/107370210/0eeebea1-ad02-4fb5-afe8-a169b2997154)

## README
Welcome to the README for the Travlr full-stack web application. Travlr is a comprehensive web platform that caters to customers and administrators, providing a seamless and secure travel experience. In the final iteration, we have incorporated robust security features for admin login authentication. This README reflects on the architecture, functionality, testing, and personal growth during the development of the Travlr project.


## Architecture

### Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).
During the the full stack project development, there were a few different types of front end code that were used in different parts of the application. The customer facing site was developed originally in Express HTML and then converted over to a .hbs view to help with rendering speeds by not having to fully load every component of the site at each refresh. HTML is static and client facing, which means it can't interact with backend databases to dynamically update information. Javascript is a frontend and backend coding language that is used to add dynamic elements to the webpage. This was used to pull trip information from the MongoDB database so that the page can change dynamically based on user interaction. A single-page application is a website that doesn't fully refresh the page based on user interactions like an HTML page would. This is particularly useful in giving the website a local/native application feel when interacting with the application itself.

Frontend Customer-Facing website:

![image](https://github.com/RBuono86/CS-465/assets/107370210/f9f85abe-a884-4ec8-bcd6-fa7c9e0f9bdb)

### Why did the backend use a NoSQL MongoDB database?
The backend used a NoSQL MongoDB database because of its ease of modifying schema based on scaling and functionality changes, as well as the ability to rapidly scale horizontally because of its non-relational nature of the database.

Backend SPA (using Angular, Express, Node.js, and MongoDB):

![image](https://github.com/RBuono86/CS-465/assets/107370210/dfb1b783-a5c5-4cb6-89de-fb8ad3456400)
![image](https://github.com/RBuono86/CS-465/assets/107370210/8e2961eb-fbfd-4379-bff0-3e1b0b2d65c3)

## Functionality

### How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?
JSON is a standardized way to format object data that can be easily read by Javascript to form it into a literal Javascript object. This makes it easy for Javascript to take the data and form it into a object in the Javascript language. This ties frontend and backend development together by creating a way for data/ Javascript objects to be stored on the backend and used in different situations based on what the frontend is requesting the data for. This also means that the data just has to be stored once but can be pulled and used in a variety of ways.

### Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.
Throughout the development process, we consistently refactored our code to improve functionality and efficiency. By doing so, we achieved the following benefits from reusable UI components:

• Consistency: Maintaining a consistent look and behavior across the application.

• Efficiency: Saving time by reusing components for similar UI elements.

• Maintenance: Simplifying updates and bug fixes, with changes made in a single location.

## Testing

### Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.
There are a few ways of testing endpoints prior to adding security. The first is by just going to the localhost web address for the API endpoint to see if the page successfully loads the data or what type of error it throws if an error occurs. An application that tests HTTP requests like Postman is ideal however, because it can also take security measures and inputs into place to test endpoints that might be protected from unauthenitcated users.

### Explain your understanding of methods, endpoints, and security in a full stack application.
In a full stack application, the methods of the website is what drives the functionality and dynamics of a webpage. Methods like GET, POST, PUT, and DELETE are http requests that can be used to retrieve or modify the database so that the functionality can be implemented. These are driven on the backend by using the functions of the database (.create, .findOne, .find, .findOneAndUpdate) to modify the database depending on the clients needs. Endpoints are the results of the methods as seen by the admin or the client side of the application. Endpoints should be tested so that they function how they should and display data properly or throw errors if an actual error occurs. Security is another layer of code that is added to prevent unauthorized or unauthenticated users from accessing or modifying te database. An example of this would be to add or edit a trip in the database. These API endpoints need to be protected so that unauthorized users cant tamper with the database.

## Reflection
Completing this course and the Travlr project has had a significant impact on reaching our professional goals. We have honed the following skills:

• Full-stack Development: Proficiency in both frontend and backend technologies.

• Database Management: In-depth understanding of NoSQL databases like MongoDB.

• API Development: Creating endpoints, implementing security measures, and testing thoroughly.

• Problem-Solving and Debugging: Improved skills in identifying and resolving issues efficiently.

This course has made us more marketable candidates in our field, enabling us to take on roles that require a diverse skill set. Travlr showcases our ability to develop a secure and feature-rich full-stack application, furthering our professional journey in the world of web development.

Thank you for exploring the Travlr web application. We hope you enjoy using it as much as we enjoyed creating it.

