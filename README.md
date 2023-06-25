CS465 Full Stack Development - MEAN

Architecture

Compare and contrast the types of front-end development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

During project there we used many different types of front-end and back-end code for different parts of the application. The customer site was originally in Express HTML then we converted it over to handelbars to help with rendering speeds, so it did not have to fully load every component of the each time the site refreshed. HTML is static, which means it is unable to interact with backend databases to update information. For this we use Javascript, which is a frontend and backend language that can add dynamic elements to the webpage. We used this pull trip information from the MongoDB database based on user interaction. For the client side we used a single-page application, which is a website that doesn't fully refresh the page based on user interactions like an HTML page would. This is very useful in giving the website a local/native application feel for the user interacting with the application itself.

Why did the backend use a NoSQL MongoDB database?

The backend used a NoSQL MongoDB database because of its ease of modifying schema, and the ability to scale both vertically as well scale horizontally because of its non-relational nature of the database.


Functionality

How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JSON is a standardized way to structure object data that can be easily read by Javascript to form it into a Javascript object. This makes it easy for Javascript to take the data and form it into a object in the Javascript language. This JSON format standard ties frontend and backend development together by creating a way for data Javascript objects to be stored on the backend and used in different situations based on what the frontend is requesting the data for. This also means that the data just must be stored once but can be pulled and used in a variety of ways.

Provide instances in the full stack process when you refactored code to improve functionality and efficiencies and name the benefits that come from reusable user interface (UI) components.

An instance where code was refactored to improve functionality and efficiency is the usage of trip card versus trip list components. Having two separate components that render the same information was inefficient, but having each trip being rendered separately but part of the whole works better for the overall functionality of the site. Reusing UI components is beneficial because it decreases the overall size of an application, makes the development process quicker, and decreases the chance of errors and vulnerabilities introduced into the system (if the component is secure).

Testing

The methods used for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security.  There are a few ways of testing endpoints prior to adding security. First, you just go to the localhost web address for the API endpoint and see if the page successfully loads the data or what type of error it throws if an error occurs on the request server. However, an application that tests HTTP requests like Postman is ideal however, because it can also take security measures and inputs into place to test endpoints that might need to be protected from unauthenticated users.  Also, the developer tools in the Chrome browser give many details on how your website is running.

Explain your understanding of methods, endpoints, and security in a full stack application.

In a full stack application, the methods of the website are what drives the functionality of the site. Methods like GET, POST, PUT, and DELETE are http requests that can retrieve or modify the database data. These are driven on the backend by database functions (.create, .findOne, .find, .findOneAndUpdate) modifying the database, meeting the client’s needs. Endpoints are the results of the methods as seen by the admin or the client side of the application. They need to be tested to ensure that they function how they should, displaying data properly and throwing errors, if one occurs. Security is another layer of code that is added to prevent unauthorized, unauthenticated users from accessing and modifying the database. Authentication is used and tokens are generated and tracked to ensure a user is authorized and has access to such functions.  Example functions that require such security are to add or edit a trip in the database. These endpoints need to be protected so that unauthorized users can't modify the database.

Reflection

How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?

This course has helped me immensely with understanding server interactions. Working with so many coding languages at once is so interesting to me, and the front and back-end development world is very intriguing. This course has helped me narrow down the direction I want to go career wise and what other skills I need to pursue to be competitive in the job market. I think that the biggest skill that I have developed in this process is that I have gained a better understanding of how different modules or components of code link together and how they can be used to build a finished product.
