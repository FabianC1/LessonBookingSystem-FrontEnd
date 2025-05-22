# LessonBookingSystem - Frontend (Vue.js-App-FrontEnd)

## Overview
Frontend for the LessonBookingSystem full-stack app. Built with Vue.js, it provides a responsive UI for students and instructors to manage lesson bookings.

## Features
- User authentication (login/register)
- Role-based views (student/instructor)
- Lesson scheduling and booking
- Booking management (confirm/cancel)
- Responsive design

## Technologies
- Vue.js, Vue Router, Vuex
- Axios for API requests
- HTML5, CSS3

## Setup
1. Clone the repo:
   ```bash
   git clone https://github.com/your-username/LessonBookingSystem-FullStack-Vue-Frontend.git
   cd LessonBookingSystem-FullStack-Vue-Frontend
   ```
2. Install dependencies:
    ```bash
    npm install
   ```
3. Create a .env file with your backend URL:
    ```bash
    VUE_APP_API_BASE_URL=http://localhost:5000/api
   ```
4. Run the app:
    ```bash
    npm run
   ```
5. Open http://localhost:8080 in your browser.

## Notes

- Connects to the backend API of LessonBookingSystem via Axios.
- Uses Vuex for state management, including user authentication and booking data.
- Role-based routing guards ensure appropriate access for students and instructors.
- Responsive design supports both desktop and mobile devices.
- Environment variables manage backend API URLs securely.
- Handles API errors with user-friendly messages.
- Built with Vue CLI for streamlined development and production builds.
