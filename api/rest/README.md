**Task: Develop a Monolithic Library Management System with REST API, Bearer Authentication, and Admin User Type**

**Scenario:** In this task, you will create a monolithic Library Management System (LMS) project with a RESTful API, Bearer token-based authentication, and an "Admin" user type. The Admin user will have specific capabilities, including CRUD operations for books and issuing books to students.

**Requirements:**

1. **Admin User Type:**
   - Define an "Admin" user type with specific privileges within the system.

2. **RESTful API Endpoints for Admin:**

    a. **Create a New Book**
       - **HTTP Method:** POST
       - **Endpoint:** /api/books
       - **Request Payload:** JSON object containing book details (e.g., title, author, ISBN, etc.).
       - **Authentication:** Bearer token required.
       - **Response:** JSON response confirming the book creation or an error message.

    b. **Retrieve Book Details**
       - **HTTP Method:** GET
       - **Endpoint:** /api/books/{book_id}
       - **Parameters:** `book_id` is the unique identifier of the book.
       - **Authentication:** Bearer token required.
       - **Response:** JSON response containing book details or an error message.

    c. **Update Book Information**
       - **HTTP Method:** PUT
       - **Endpoint:** /api/books/{book_id}
       - **Parameters:** `book_id` is the unique identifier of the book.
       - **Request Payload:** JSON object with updated book details.
       - **Authentication:** Bearer token required.
       - **Response:** JSON response confirming the book update or an error message.

    d. **Delete a Book**
       - **HTTP Method:** DELETE
       - **Endpoint:** /api/books/{book_id}
       - **Parameters:** `book_id` is the unique identifier of the book to delete.
       - **Authentication:** Bearer token required.
       - **Response:** JSON response confirming the book deletion or an error message.

    e. **Issue a Book to a Student**
       - **HTTP Method:** POST
       - **Endpoint:** /api/issue/{book_id}
       - **Parameters:** `book_id` is the unique identifier of the book to issue.
       - **Request Payload:** JSON object containing the student's ID.
       - **Authentication:** Bearer token required.
       - **Response:** JSON response confirming the book issuance or an error message.

    There should also be api endpionts to get list of issues, update issue status.

**Evaluation Criteria:**

1. Successful development of the Admin user type with specific privileges.

2. Proper implementation of RESTful API endpoints for the Admin user.

3. Secure and functioning Bearer token-based authentication.

4. Effective handling of CRUD operations for books and book issuance.

5. Clarity and completeness of the API documentation, including endpoint details and authentication requirements.

This task assesses your ability to design and implement a monolithic Library Management System, focusing on the capabilities of the Admin user type. It evaluates your skills in defining user roles and developing specific functionalities within the system.