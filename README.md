# cs465-fullstack
CS-465 Full Stack Development with MEAN

## Architecture

**o	Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).**

For this full stack project, I used Express HTML, JavaScript, and the single-page application (SPA).  Initially, I developed the frontend using Express HTML.  The problem with this is HTML cannot dynamically update information due to it being static and client-facing.  JavaScript allowed me to add dynamic elements to the webpage.  JavaScript, unlike HTML, can interact with the backend databases.  Finally.  The single-page application (SPA) was able to interact with a user by dynamically rewriting the current web page with new data from the web server.  This allowed for faster apps than using other development tools.

**o	Why did the backend use a NoSQL MongoDB database?**

The NoSQL MongoDB database allowed easy updates to schemas and fields.  It can also allow for greater scalability than an SQL database.

## Functionality

**o	How is JSON different from JavaScript and how does JSON tie together the frontend and backend development pieces?**

There are a few differences between JSON and JavaScript.  JSON cannot contain functions, whereas JavaScript can contain functions.  JSON can be created and used by other programming languages, whereas JavaScript objects can only be used in JavaScript.  JSON can format the data in the application in a form that can be read by JavaScript.  This allows the JavaScript objects to be stored in the backend and used in different situations that the frontend requires.

**o	Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.**

Within the application I swapped out hard coded HTML with functions that called the requested information.  Also, I created an array to hold all the trip information in a separate object.

## Testing

**o	Methods for request and retrieval necessitate several types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.  Explain your understanding of methods, endpoints, and security in a full stack application.**

There are many different ways to assess the API endpoints.  Going to the localhost website and inputting data and seeing if it accepts it and outputs it correctly is one way.  Also, using an application that evaluates the HTTP requests helps greatly.  During this project I utilized Postman which allowed me to input the localhost address and test different endpoints.  The common methods used in HTTP requests are GET, POST, PUT, and DELETE.  These methods can be used to add data, update data, retrieve data, and delete data from the database.  These endpoints must be tested to ensure that they perform correctly and do not throw errors.  If they are incorrectly figured it can pose a security risk to the application.  Only authorized users should be allowed to access these API endpoints and mess with the data.

## Reflection
**o	How has this course helped you in reaching your professional goals?  What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?**

This course has helped me become a more marketable candidate in my career field by teaching me a skill I have never used before.  I learned the basics of full stack development, how to combine different languages, and how to use JavaScript.  I have never used JavaScript before, and this was a great crash course.  Also, I learned how to test different API endpoints using the application postman.  Finally, I ran into many errors and issues during the development of this application.  Therefore, I had to become very proficient at reading the error codes, looking up my errors, and figuring out what I did wrong.
