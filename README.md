# Full-Stack-Web-Dev-CS-456
## Full Stack Web Dev MEAN Stack App

https://www.youtube.com/watch?v=yV-yrNIlwiY&t=1s<VIDEO ID>


### Architecture
- Compare and contrast the types of frontend development you used in your full stack project, including Express HTML, JavaScript, and the single-page application (SPA).

To get to the Single Page Application (SPA), we passed through several types of architectures. Originally, a ll pages on the first static website had all the information they needed hard-coded into the html files. The first step was to remove the data about the different travel options from the HTML and place it in a JSON file. As a result, we were able to make the HTML pages smaller while still leveraging Handlebars and JavaScript to automatically populate the HTML files with data as they were accessed. The next step was to take the information then transfer it from the static JSON file into MongoDB. From which we used Node Express to obtain the information whenever the client accessed the page. All of this took place on the server-side, where the pages are still served fully loaded with data. The last step was building the SPA using Angular. Angular allows us to have the logic of the SPA processed on the client side as opposed to it being sent from the server. The only information passed between the client and the server is data.

- Why did the backend use a NoSQL MongoDB database?

Because of its adaptable data format, MongoDB is a fantastic option for the back-end database. NoSQL databases like MongoDB, structures the data in a "document" which are objects that may include parts that are different from those found in other documents in the database. This makes it possible to store many data structures with greater flexibility in a single database collection, which simplifies the architecture of the application by eliminating the need to maintain track of numerous tables or collections and use join statements to combine various data for display.

### Functionality
- How is JSON different from Javascript and how does JSON tie together the frontend and backend development pieces?

JavaScript is more of a language that manipulates data, whereas JSON is a data model or format descriptive specification, utilizing k ey/value pairs to show data's content. This data structure is written and read by JavaScript then outputs it as required.

- Provide instances in the full stack process when you refactored code to improve functionality and efficiencies, and name the benefits that come from reusable user interface (UI) components.

The ability to develop components during the full stack process allows for them to be utilized anywhere inside the application is the fundamental benefit of this process. For example, converting the static HTML of the trip cards into a component allowed me to delete duplicate code structures and by iterating through data structures to populating the data.

### Testing
- Methods for request and retrieval necessitate various types of API testing of endpoints, in addition to the difficulties of testing with added layers of security. Explain your understanding of methods, endpoints, and security in a full stack application.

Requests are directed to endpoints where they are carried out. These appear to be URL addresses. The actions that create the request, lead it to the endpoint, or, if on a server, receive and process the request are known as methods. Data protection and full stack development both depend on security. Authentication and authorization are the two key areas of attention. The security procedure of authenticating the identity of the access and ensuring that access is secure is known as authentication. The process of ensuring that a named user has permission to use the resource is known as authorization.

### Reflection
- How has this course helped you in reaching your professional goals? What skills have you learned, developed, or mastered in this course to help you become a more marketable candidate in your career field?


The introduction of the MongoDB, Express, Angular, and Node (MEAN) stack into my professional toolkit will allow for me to utilize this framework and others like it in future projects.


## Steps taken for the different branches of the project
### Intro, Setup, and Static HTML Site
- Create Website
- Install Static Web Files

### MVC Routing
- Create Web Application Folders
- Create Controllers and Routes
- Create Handlebars Views

### Static HTML to Templates With JSON

### NoSQL Databases, Models, and Schemas
- Install and Configure Mongoose
- Seed the Database

### RESTful API
- Create Mongoose Schema and DB Access Code
- Test the Data Access Code
- Modify Public Website to Use API Endpoints

### SPA
- Create Angular Admin Site
- Create Trip Listing Component
- Refactor Trip Rendering Logic into an Angular Component
- Create Trip Data Service
- Add/Edit Trips

### Security
- Add Authentication to Express backend
- Add Authentication to Angular SPA frontend
