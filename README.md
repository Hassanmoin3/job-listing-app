# Job Listing Application

## Goal
Create an API for a simple job posting application and link it with a React Native app.

## Part 1: Backend (Choose Go or Laravel)
Choose either Go or Laravel for the backend. Set up a Job Posting API capable of basic CRUD operations for 'Job' resources. Endpoints should include listing all jobs, creating a new job, retrieving specific job details, updating a job posting, and deleting a job. Write tests for your endpoints.

### Backend Setup (Laravel)
1. Navigate to the `backend` folder.
2. Run `composer install` to install required libraries.
3. Run `php artisan serve` to start the server.

## Part 2: React Native
Create a mobile app using React Native as the frontend for the job posting application. Interface with the previously created Job Posting API. Display the list of all jobs, individual job details, and allow users to create and edit job postings.

### Frontend Setup
1. Navigate to the `job-listing-app` folder.
2. Run `npm install` to install required libraries.
3. Run `npx expo start` to run the application.

### Additional Requirements
Implement Redux for state management and error handling.

## How to Run
Follow the steps mentioned above for backend and frontend setups. Ensure both the backend server and React Native app are running simultaneously for full functionality.

