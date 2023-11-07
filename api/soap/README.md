**Task: Create CRUD SOAP API Endpoints for Managing a Post Table**

**Scenario:** In this task, you will design and implement a set of CRUD (Create, Read, Update, Delete) SOAP API endpoints to manage a "Post" table in a database. This task assesses your ability to create SOAP web services for basic data manipulation.

**Requirements:**

1. **Database Setup:**
   - Set up a database table named "Post" with the necessary columns, such as `post_id`, `title`, `content`, and `created_at`. You can use your preferred database system.

2. **SOAP Web Service Creation:**
   - Implement a SOAP web service that exposes the following CRUD operations for the "Post" table:

   a. **Create a New Post:**
      - Create a SOAP operation for creating a new post. The operation should accept input parameters for the post's title and content.

   b. **Update an Existing Post:**
      - Create a SOAP operation for updating an existing post. Users should be able to provide the `post_id`, `title`, and `content` for the update.

   c. **Get Post by ID:**
      - Implement an operation to retrieve a post by its `post_id`.

   d. **Get All Posts:**
      - Develop an operation to retrieve a list of all posts in the "Post" table.

   e. **Delete a Post:**
      - Create an operation for deleting a post by its `post_id`.

3. **Error Handling:**
   - Implement proper error handling to manage situations like invalid input, post not found, or database errors.

4. **Data Validation:**
   - Validate input data to ensure that required fields are provided and data types are correct.

5. **Documentation:**
   - Provide clear documentation for the SOAP API, including details on the input parameters, expected responses, and examples of how to use each operation.

**Evaluation Criteria:**

1. Successful implementation of SOAP operations for CRUD functionality on the "Post" table.

2. Effective handling of input validation and error scenarios.

3. Proper documentation of the SOAP API, including input parameters and responses.

This task assesses your ability to create SOAP web services for basic CRUD operations on a database table. It evaluates your skills in designing and implementing SOAP endpoints and ensuring proper error handling and data validation.