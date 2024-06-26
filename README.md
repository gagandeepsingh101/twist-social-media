# Twist-Social-Media

## Project Overview

Twist-Social-Media is a social media platform built with Next.js, NextAuth, Prisma, MongoDB, Shadcn UI, Socket.io, and Cypress for testing. This project is structured to be completed over 8 weeks

## Project Setup and Initial Structure (Week 1)

### Day 1: Project Setup
- Create a new repository.
- Set up the project structure using Next.js for both frontend and backend.
- Initialize version control with Git and make the initial commit.
- Create an initial `README.md` file.
- Configure CI/CD pipeline.
- Set up Prisma with MongoDB.
- Push initial setup to the repository.

### Day 2: Basic Client Setup
- Set up the initial Next.js pages.
- Implement the initial landing page with Shadcn UI.
- Ensure that the frontend communicates with the backend (basic API call).
- Push initial frontend code to the repository.

## User Authentication (Week 2)

### Day 3: User Authentication - Backend
- Set up NextAuth.js with Prisma and MongoDB.
- Implement user registration and login endpoints.
- Configure JWT authentication.
- Create user model/schema with Prisma.
- Hash passwords before saving.

### Day 4: User Authentication - Frontend
- Create registration and login forms using Shadcn UI.
- Connect forms to backend API using NextAuth.js.
- Implement error handling for forms.

## User Profile (Week 3)

### Day 5: User Profile - Backend
- Implement user profile endpoint with Next.js API routes.
- Add endpoints to get and update user profile.

### Day 6: User Profile - Frontend
- Create profile view page using Shadcn UI.
- Create edit profile form using Shadcn UI.
- Connect forms to backend API.
- Implement error handling for forms.

## Basic Social Media Features (Week 4)

### Day 7: Posting Content - Backend
- Implement create post endpoint with Next.js API routes.
- Add post model/schema with Prisma.
- Implement endpoint to retrieve posts.

### Day 8: Posting Content - Frontend
- Create post creation form using Shadcn UI.
- Display posts in a feed using Shadcn UI.
- Connect forms to backend API.

## User Feed and Interactions (Week 5)

### Day 9: User Feed - Backend
- Implement follow/unfollow functionality with Next.js API routes.
- Implement endpoint to retrieve feed posts.

### Day 10: User Feed - Frontend
- Display feed on frontend using Shadcn UI.
- Implement follow/unfollow buttons using Shadcn UI.
- Connect feed to backend API.

## Liking and Commenting (Week 6)

### Day 11: Liking and Commenting - Backend
- Implement like/unlike endpoints with Next.js API routes.
- Implement comment creation endpoint with Next.js API routes.
- Add models/schemas for likes and comments with Prisma.

### Day 12: Liking and Commenting - Frontend
- Add like/unlike buttons on posts using Shadcn UI.
- Add comment section on posts using Shadcn UI.
- Connect like and comment functionality to backend API.

## Chat Functionality (Week 7)

### Day 13: Chat Setup - Backend
- Set up Socket.io for real-time messaging.
- Create chat model/schema with Prisma.
- Implement endpoints for sending/receiving messages.

### Day 14: Chat Setup - Frontend
- Set up Socket.io client for real-time messaging.
- Create chat UI using Shadcn UI.
- Implement message sending/receiving in UI.

## Final Touches and Deployment (Week 8)

### Day 15: Final UI/UX Enhancements and Bug Fixes
- Implement final UI/UX improvements using Shadcn UI.
- Conduct end-to-end testing with Cypress.
- Fix identified bugs.
- Perform load testing and optimize performance.

### Day 16: Deployment Preparation and Post-Deployment Testing
- Set up production environment.
- Configure databases and cloud storage for production.
- Ensure security best practices are in place.
- Deploy the application to production.
- Perform post-deployment testing.
- Monitor application performance and address any issues.

## Unit Test Cases

### User Authentication - Backend
- Test user registration (valid/invalid data) with Cypress.
- Test user login (valid/invalid credentials) with Cypress.

### User Authentication - Frontend
- Test form validation (empty fields, incorrect formats) with Cypress.
- Test API integration (successful/failed requests) with Cypress.

### User Profile - Backend
- Test getting user profile with Cypress.
- Test updating user profile (valid/invalid data) with Cypress.

### User Profile - Frontend
- Test form validation (empty fields, incorrect formats) with Cypress.
- Test API integration (successful/failed requests) with Cypress.

### Posting Content - Backend
- Test creating posts (valid/invalid data) with Cypress.
- Test retrieving posts with Cypress.

### Posting Content - Frontend
- Test form validation (empty fields, incorrect formats) with Cypress.
- Test API integration (successful/failed requests) with Cypress.

### User Feed - Backend
- Test follow/unfollow functionality with Cypress.
- Test retrieving feed posts with Cypress.

### User Feed - Frontend
- Test API integration (successful/failed requests) with Cypress.
- Test follow/unfollow buttons with Cypress.

### Liking and Commenting - Backend
- Test liking/unliking posts with Cypress.
- Test creating comments with Cypress.

### Liking and Commenting - Frontend
- Test like/unlike buttons with Cypress.
- Test comment submission and display with Cypress.

### Chat Functionality - Backend
- Test sending messages with Cypress.
- Test receiving messages with Cypress.

### Chat Functionality - Frontend
- Test UI message sending with Cypress.
- Test real-time message receiving with Cypress.

### Final Touches
- Comprehensive tests covering all major functionalities with Cypress.
- Stress tests for performance bottlenecks with Cypress.
- Test live environment functionalities with Cypress.
- Monitor logs and error reports.

## Getting Started

### Prerequisites
- Node.js
- npm
- MongoDB (local or Atlas)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com//twist-social-media.git
   cd twist-social-media
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Set up environment variables:
   - Create a `.env.local` file in the root directory.
   - Add your MongoDB connection string and other necessary environment variables:
     ```env
     DATABASE_URL="mongodb+srv://<username>:<password>@cluster0.mongodb.net/<database>?retryWrites=true&w=majority"
     ```

4. Initialize Prisma:
   ```sh
   npx prisma generate
   ```

### Running the Project

1. Start the development server:
   ```sh
   npm run dev
   ```

2. Open your browser and navigate to `http://localhost:3000`.

### Running Tests

1. Run Cypress tests:
   ```sh
   npm run test
   ```

## Contributing

Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request.

## License

This project is licensed under the MIT License.

---

## Contact

For any inquiries or feedback, please contact [gagandeepsingh128548@gmail.com](mailto:gagandeepsingh128548@gmail.com).