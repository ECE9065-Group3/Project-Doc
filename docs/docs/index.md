# Project Requirements

## Excutive Summary
In response to the growing demand for a seamless and feature-rich online bookstore experience, our proposed website project aims to deliver a user-centric platform that seamlessly integrates user registration and authentication, a comprehensive book catalog powered by an external API, and a streamlined shopping cart with a simulated checkout process. Additionally, the project includes robust backend development with a RESTful API and a dedicated database for storing user and order data.

## User Stories
### Epic 1: User Registration and Authentication
**Frontend:**

- [x] As a new user, I want to be able to create an account with my email, password, and name so I can access the full functionality of the website.

**Backend:**

- [x] As a user, I want the website to implement basic security measures to protect my personal data, ensuring a safe registration and login process.
- As a registered user, I want the ability to update my password for added security.
- [x] As a user, I want the option to authenticate using an external service like Google or Facebook, providing a convenient and secure login.
- [x] As a new user, I want to receive an email verification to confirm my account and ensure the legitimacy of my registration.
- [x] As a user with a deactivated account, I want to see a message prompting me to contact the site administrator for assistance, preventing unauthorized logins.

### Epic 2: Book Catalog and Shopping Cart
**Frontend:**

- [x] As an unauthenticated user, I want to see a start page introducing the application, including a brief description and a login mechanism.
- [x] As an unauthenticated user, I want to search for books by author, field, or title, with results displaying key information like book title and author.
- [x] As an unauthenticated user, I want to expand each search result to view additional information about a book.
- [x] As an unauthenticated user, I want to soft-match search terms, ensuring a more forgiving search experience.
- [x] As an unauthenticated user, I want to see a list of public booklists ordered by the last modified date, displaying name, creator, total pages, and book count.
- [x] As an unauthenticated user, I want to expand each book list to view its description and the list of books it contains.
- [x] As an unauthenticated user, I want the ability to display additional information and view all the books in a public book list.

**Frontend & Backend:**

- [x] As an authenticated user, I want to create up to 20 named book lists with a unique name, optional description, list of books, and a visibility flag set to private by default.
- [x] As an authenticated user, I want to click on a list to view detailed information about all the books it contains.
- [x] As an authenticated user, I want to edit all aspects of an existing book list and record the last edited time.
- [x] As an authenticated user, I want to delete a book list.
- [x] As an authenticated user, I want to add a review to any public book list.

### Epic 3: Administrator Functionality
**Backend:**

- As an administrator, I want to have a special account with privileged access.
- As an administrator, I want to grant site manager privileges to one or more existing users.
- As an administrator, I want the ability to mark a review as hidden or clear the "hidden" flag if set.
- As an administrator, I want the ability to mark a user as "deactivated" or mark as "active" if deactivated.

### Epic 4: Web Service API
**Backend:**

- [x] As a developer, I want to design and implement a clear and appropriate API, defining endpoints, specifying HTTP request methods, and describing expected request and response formats.
- [x] As a developer, I want to ensure the API design is consistent with the required functionality, including interactions with the database.
- [x] As a developer, I want to build the web application by integrating and effectively utilizing the designed API for full functionality, including database operations.