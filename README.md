# MeetMedico: Doctor Appointment Booking Application

## Project Description
MeetMedico is an innovative doctor appointment booking application designed to streamline the process of scheduling medical appointments. Built with modern technologies, it provides a seamless user experience for both patients and healthcare providers.

## Features
- User authentication via Clerk
- Appointment scheduling and management
- Integration with Vonage Video SDK for virtual consultations
- User-friendly interface built with Next.js
- Responsive design for mobile and desktop usage

## Tech Stack
- **Frontend:** Next.js 15.3.2
- **UI Components:** React 19.0.0, Radix UI, Tailwind CSS
- **Authentication:** Clerk
- **Database:** Prisma ORM
- **Video Conferencing:** Vonage Video SDK
- **Form Handling:** React Hook Form with Zod validation

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/its-dhanya/meetmedico.git
   cd meetmedico
   ```
2. Install the dependencies:
   ```bash
   npm install
   ```
3. Set up environment variables:
   Create a `.env.local` file in the root directory and add the required environment variables for Clerk and Vonage.
4. Generate Prisma client:
   ```bash
   npx prisma generate
   ```

## Usage
- Start the development server:
  ```bash
  npm run dev
  ```
- Navigate to `http://localhost:3000` in your web browser.
- Follow the on-screen instructions to create an account and book appointments.

## Available Scripts
- `npm run dev` - Start development server with Turbopack
- `npm run build` - Build the application for production
- `npm start` - Start the production server
- `npm run lint` - Run ESLint to check code quality

## Project Structure
- `/app` - Next.js app directory with pages and routes
- `/components` - Reusable React components
- `/hooks` - Custom React hooks
- `/lib` - Utility functions and helpers
- `/prisma` - Database schema and migrations
- `/public` - Static assets

## Acknowledgments
- Thanks to all contributors and libraries that made this project possible!