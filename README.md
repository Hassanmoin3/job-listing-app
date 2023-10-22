# Job Posting Application

This project comprises a Job Posting API built with Laravel and a React Native mobile app that interacts with the API. The backend is responsible for basic CRUD operations on job resources, while the frontend displays job listings, allows job creation, editing, and detailed viewing.

## Getting Started

### Clone the Repository

```bash
git clone <repository-url>
Run the Application
Backend (Laravel)
Navigate to the Laravel project folder:

bash
Copy code
cd job-posting-api
Run the Laravel development server:

bash
Copy code
php artisan serve
Frontend (React Native)
Navigate to the React Native project folder:

bash
Copy code
cd JobPostingApp
Install dependencies:

bash
Copy code
npm install
Run the React Native application:

bash
Copy code
npx react-native run-android  # For Android
# or
npx react-native run-ios      # For iOS
Functionality
Backend (Laravel)
API Endpoints:

GET /jobs: List all job postings.
POST /jobs: Create a new job posting.
GET /jobs/{id}: Retrieve details of a specific job posting.
PUT /jobs/{id}: Update a specific job posting.
DELETE /jobs/{id}: Delete a specific job posting.
Job Structure:

json
Copy code
{
  "title": "Job Title",
  "description": "Job Description",
  "salary": "Job Salary",
  "company": "Company Name",
  "postedAt": "Date the job was posted"
}
Testing:
Implemented PHPUnit tests for API endpoints.

Frontend (React Native)
Main Screens:

List Screen: Displays all job postings.
Detail Screen: Shows details of a specific job posting.
Add Screen: Allows adding a new job posting.
Edit Screen: Enables editing an existing job posting.
Data Interaction:

List Screen fetches data from GET /jobs.
Detail Screen fetches data from GET /jobs/{id}.
Add Screen posts data to POST /jobs.
Edit Screen puts data to PUT /jobs/{id}.
Data Synchronization:
Changes made in add or edit screens reflect in the job listings.

Error Handling:
Displays appropriate error messages for user guidance.
