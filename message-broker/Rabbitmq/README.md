**Task: Develop a Notification Microservice Using RabbitMQ and Firebase Cloud Messaging (FCM)**

**Scenario:** In this task, you will be assessed on your ability to design and implement a microservice that receives notification data from RabbitMQ and sends notifications to mobile devices using Firebase Cloud Messaging (FCM). This task evaluates your proficiency in building a microservice that processes messages from a message broker and sends them to mobile devices.

**Requirements:**

1. **Microservice Design:**
   - Design a microservice responsible for receiving messages from RabbitMQ and sending notifications to mobile devices using FCM.
   - Define the architecture, including message handling, error handling, and notification sending components.

2. **Message Format:**
   - Specify the format of the messages received from RabbitMQ. In this case, the message format should include fields for user_id, FCM token, title, body, and an optional image.

3. **RabbitMQ Integration:**
   - Implement message consumption from RabbitMQ. Design your microservice to listen to a specific RabbitMQ queue for incoming notification data.
   - Ensure reliable and efficient message processing.

4. **FCM Integration:**
   - Integrate with the FCM service to send notifications to mobile devices. Use the provided FCM tokens to target specific devices.
   - Implement proper error handling and retry mechanisms for failed FCM deliveries.

5. **Notification Handling:**
   - Create a module that takes the incoming notification data, as received from RabbitMQ, and formats it into FCM notification messages.
   - Ensure that notifications include title, body, and optionally an image attachment.

6. **Authentication:** Secure the microservice by implementing authentication and authorization mechanisms, ensuring that only authorized clients can use the service.

7. **Documentation:**
   - Create clear and comprehensive documentation for your microservice, including API specifications, message formats, and integration instructions.

**Evaluation Criteria:**

1. Successful implementation of the notification microservice with proper RabbitMQ and FCM integration.

2. Proper handling of incoming notification data and conversion into FCM messages.

3. Effective error handling and retry mechanisms for FCM message delivery.

4. Secure authentication mechanisms for the microservice.

5. Clear and well-documented microservice architecture and usage instructions.

This task assesses your ability to design and build a notification microservice that receives messages from RabbitMQ and delivers notifications to mobile devices using FCM. It evaluates your skills in microservice architecture, message handling, and secure service implementation.