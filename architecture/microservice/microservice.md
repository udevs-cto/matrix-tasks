**Task: Build a News Post System with Microservices Architecture**

**Scenario:** In this task, you will design and implement a News Post System with microservices architecture.
The system allows users to post news, view, search, comment on posts, and rate posts while commenting. 
The application consists of four microservices: user_service, post_service, comment_service, and api-gateway. 
Communication between services will be achieved using gRPC, and user authentication will be implemented using 
JWT token-based bearer authentication.

**ERD of the project must be exist!!!**

**Requirements for User Service:**

1. **User Registration and Authentication:**
   - Implement user registration functionality to allow users to sign up.
   - Implement JWT token-based authentication for user login and secure endpoints.

2. **User Profile:**
   - Allow users to view and edit their profiles, including personal information and profile picture.

**Requirements for Post Service:**

3. **News Posting:**
   - Implement an endpoint to allow users to post news articles. News articles should include a title, content, and 
   optional image attachments.

4. **News Viewing:**
   - Provide an endpoint to view a list of news articles.

5. **News Searching:**
   - Create a search endpoint to allow users to search for news articles based on keywords.

6. **News Rating:**
   - Allow users to rate news articles while commenting. Ratings should be stored and visible to other users.

**Requirements for Comment Service:**

7. **Commenting on Posts:**
   - Implement an endpoint for users to comment on news articles. Comments should include text and ratings for a post that comment is written for.

8. **Comment Replies:**
   - Allow users to reply to comments, creating threads of discussions.

**Requirements for API Gateway:**

10. **Authorization:**
    - Implement JWT token-based bearer authentication to secure API endpoints.
    - Ensure that only authenticated users can access authorized endpoints.

11. **Service Integration:**
    - Implement a gRPC-based communication mechanism to facilitate communication between the user, post, and comment services.

**Evaluation Criteria:**

1. Successful implementation of the four microservices: user_service, post_service, comment_service, and api-gateway.

2. Proper user registration, authentication, and JWT token-based security.

3. Functioning user profiles and the ability to edit user information.

4. Effective posting, viewing, and searching for news articles.

5. Proper news rating and secure authentication.

6. Commenting on posts and rating comments, including comment replies.

7. Secure JWT token-based authentication in the API gateway.

8. Accurate and efficient communication between services using gRPC.

9. Documentation that outlines each service's functionality and how they interact within the system.

This task assesses your ability to design and build a microservices-based News Post System, 
considering user registration, authentication, news posting, commenting, rating, and secure communication between services. 
It also evaluates your documentation and architectural skills.