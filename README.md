## Project Overview

**Project Name**: SuperCoolFileHost

**Project Description**: Have to Develop a file hosting application that allows users to upload files, generate public links, and optionally subscribe to a paid plan for extended hosting. The application should have a minimalistic design and be built using the MERN (MongoDB, Express, React, Node.js) stack.

## Key Requirements

1. **User File Upload**:
   - Allow users, both logged in and anonymous, to upload files.
   - Generate public links for the uploaded files.

2. **Object Storage**:
   - Implement secure file storage, either using a third-party object storage service (e.g., Amazon S3) or a custom storage solution.

3. **User Subscription**:
   - Offer a single paid subscription plan with features like extended file hosting.
   - Integrate Stripe for subscription management.

4. **File Expiration**:
   - Automatically remove anonymous files after 7 days.

5. **Minimalistic Design**:
   - Design the application with a clean and minimalistic user interface.

## Technology Stack

- **Frontend**:
   - React.js for the user interface.
   - CSS or a CSS framework for styling.

- **Backend**:
   - Node.js and Express for the server.
   - MongoDB for the database.

- **File Storage**:
   - Choose between external object storage services like Amazon S3 or a custom storage solution depending on the project's scalability and budget.

- **Payment Processing**:
   - Integrate Stripe for handling subscriptions and payments.
