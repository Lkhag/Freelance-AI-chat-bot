# Freelance-AI-chat-bot
1. Introduction

  1.1 Project Overview 
  The Real-Time Freelance Job Finder AI Chatbot is a web-based application that helps         freelancers discover job opportunities using artificial intelligence. The system aggregates job   listings from several platforms. and provides personalized recommendations through an   interactive chatbot interface.

  1.2 Objectives
  * Provide real-time job search functionality

  * Use AI (OpenAI) to understand user queries

  * Offer a conversational job search experience

  * Filter jobs by skills, location, salary, and job type

2. Key Features
   AI-Powered chatbot - Understand natural language queries.

   Job Aggregation - Fetches jobs from APIs.

   Real-time Updates - Uses WebSockets to notify users of new job postings.

   Filters - Filters jobs by skills, salary, location, and job type.

   Saved jobs - Users can bookmark jobs for later review.

3. Technology Stack

   3.1 Frontend
   
     Technology used:                 Purpose:

     HTML/CSS/JavaScript        Core web development

     React.js                   Interactive UI components

     Socket.IO                  Real-time chat updates

     Axios                      API request to backend

   3.2 Backend

     Technology used:                 Purpose:

     Node.js                      Server runtime

     Express.js                   REST API endpoints

     Socket.IO                    WebSocket communication

     OpenAI API                   NPL for chatbot responses

   3.3 Database

     Technology used:                  Purpose:

     MongoDB                      Stores user data and saved jobs

     Redis                        Caching for faster responses

4. System Requirements

   4.1 Software Requirements

     Node.js (v18 or later)

     npm (Node Package Manager)

     MongoDB (for database)

     OpenAI API Key (for AI chatbot)

   4.2 Hardware Requirements

     RAM: 4GB or higher

     Storage: 500MB free space

     Internet Connection (for API calls)

5. Installation Guide

   5.1 Setting up repository

     1. Clone the repository:

        git clone https://github.com/your_user_name/freelance-job-finder.git

     2. Install depemdencies:

        cd freelance-job-finder
        
        npm install

        cd client && npm install

     3. Configure environment variables (create .env file):
  
        PORT=3001

        OPENAI_API_KEY=your_key

        MONGODB_URI=your_mongodb_connection_string

   5.2 Running the app

     Start the backend:

       npm run server

     Start the frontend:

       cd client && npm start

     Access the app:

       Open http://localhost:3000 in a web browser

6. How it works

   6.1 User Flow

      User opens the web app.

      Types a job query (e.g., "Find remote Python jobs").

      AI chatbot processes the request and fetches matching jobs.

      Jobs are displayed in real-time with filters.

      User can save jobs or refine the search.
     
