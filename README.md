This repository showcases a demo website built using Vite, React, CSS, PHP, SQLite, HTML, and Firebase. The website is designed to display and search data from the CHI 2023 Conference, providing a dynamic and interactive experience for users.

**Features**

Search Functionality: 
Users can search publications by author, title, country, or topic.

Publication Summaries: 
Each result includes a summary, a link to the video, and access to the full paper.

Random Video Display: 
The homepage highlights a random video from the conference.

User Accounts: 
Firebase-powered JWTs enable secure login and account functionality.

Notes and Favorites: 
Users can take notes on publications and favorite them for later reference.

**Web API**
The Web API acts as the backbone of the application, enabling smooth navigation and error handling. Key features include:

Endpoint Framework: 
Routes user requests to appropriate endpoints.

Exception Handling: 
Handles unknown pages and bad responses.

Data Requests: 
Facilitates secure communication between the client and server.

**App**
The App folder contains the Vite-based front end, which serves as the user interface. It is responsible for:

Fetching and displaying data from the Web API.
Rendering content dynamically using React and Tailwind CSS.
Handling authentication via JWT tokens for secure user interactions.

**Setup and Usage With NPM and Vite**

Ensure you have NPM and Vite installed. If not, please view their documentation for instructions on how to do so.

Install dependencies:
```
npm install  
```
Start the development server:
```
npm run dev  
```


**Important Notes**

Dummy Logins: 
Two dummy accounts are provided for testing, but the login functionality requires integration with your own Firebase private key and server setup.

Favourites and Notes: 
To enable full functionality, uncomment the code related to these features in the Notes page and update the server links.

**Disclaimer**

This example is intended for educational purposes. Directly copying and deploying this code without modification will result in limited functionality, particularly for user authentication and account-specific features.
