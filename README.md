# MERN-book-search-app

## Description

This is a book search engine web application that allows avid readers to search for new books and keep a list of books to purchase. Users can search for books, create an account, save books to their account, view their saved books, and remove books from their account. The aim of this project was to refactor the starter code provided to meet the acceptance criteria below.


### User Story
As an avid reader, I want to search for new books to read so that I can keep a list of books to purchase.

### Acceptance Criteria
When I load the search engine, I am presented with a menu that includes the options "Search for Books" and "Login/Signup," an input field to search for books, and a submit button.
When I click on the "Search for Books" menu option, I am presented with an input field to search for books and a submit button.
When I am not logged in and enter a search term in the input field and click the submit button, I am presented with several search results, each featuring a book's title, author, description, image, and a link to that book on the Google Books site.
When I click on the "Login/Signup" menu option, a modal appears on the screen with a toggle between the options to log in or sign up.
When the toggle is set to "Signup," I am presented with three inputs for a username, an email address, and a password, and a signup button.
When the toggle is set to "Login," I am presented with two inputs for an email address and a password, and a login button.
When I enter a valid email address and create a password and click on the signup button, my user account is created, and I am logged into the site.
When I enter my account's email address and password and click on the login button, the modal closes, and I am logged into the site.
When I am logged into the site, the menu options change to "Search for Books," an option to see my saved books, and "Logout."
When I am logged in and enter a search term in the input field and click the submit button, I am presented with several search results, each featuring a book's title, author, description, image, and a link to that book on the Google Books site, and a button to save a book to my account.
When I click on the "Save" button on a book, that book's information is saved to my account.
When I click on the option to see my saved books, I am presented with all of the books I have saved to my account, each featuring the book's title, author, description, image, and a link to that book on the Google Books site, and a button to remove a book from my account.
When I click on the "Remove" button on a book, that book is deleted from my saved books list.
When I click on the "Logout" button, I am logged out of the site and presented with a menu that includes the options "Search for Books" and "Login/Signup," an input field to search for books, and a submit button.


## Technologies Used

* Frontend: React.js
* Backend: Node.js, Express.js
* Database: MongoDB
* Authentication: JSON Web Tokens (JWT)
* GraphQL API: Apollo Server
* External API: Google Books API


## Installation and usage

To run the Book Search Engine application locally, follow these steps:


* Clone the repository:

git clone https://github.com/Adinahidan/MERN-book-search-app

* Install the dependencies:

cd book-search-engine
npm install

* Start the application:

npm start

Access the application in your browser at http://localhost:3000.

Note: Make sure you have Node.js and npm (Node Package Manager) installed on your machine before running the above commands.


## Link to deployed application

https://afternoon-beyond-47432-6023dd3f9484.herokuapp.com/



## Acknowledgments

This project was developed as part of a coding challenge .
Special thanks to the  Instructional Team and Learning Assistants who have assisted me with this project.


