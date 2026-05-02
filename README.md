# Streamlined Case Flow Management

## Problem Statement

Courts worldwide face significant delays and inefficiencies due to manual case management processes, overwhelming paperwork, and lack of real-time tracking systems. This results in case backlogs, increased costs, delayed justice for litigants, and overburdened judicial staff. The need for a digitized, streamlined judiciary management system is critical to modernize legal workflows, reduce delays, and ensure transparent, efficient case handling.

## Features

- **Case Registration**: Register new cases with detailed information including case type, parties involved, and initial documentation.
- **Case Scheduling**: Schedule hearings, trials, and deadlines using an integrated calendar system.
- **User Management**: Role-based access for judges, lawyers, and administrative staff with secure authentication.
- **Case Tracking**: Real-time monitoring of case progress, status updates, and document management.
- **Dashboard**: Comprehensive dashboards for viewing case statistics, upcoming hearings, and workload management.
- **Notifications**: Automated reminders for upcoming deadlines and hearings.
- **Reporting**: Generate reports on case outcomes, court performance, and backlog analysis.

## Tech Stack

- **Frontend**: React with Vite, Tailwind CSS, ShadCN UI components
- **Backend**: Node.js with Express.js
- **Database**: MongoDB with Mongoose ODM
- **Authentication**: bcryptjs for password hashing
- **Calendar Integration**: FullCalendar for scheduling features
- **State Management**: TanStack Query for data fetching
- **UI Components**: Radix UI primitives

## How to Run This Project

### Prerequisites

- Node.js (version 16 or higher)
- MongoDB (local installation or cloud instance like MongoDB Atlas)
- npm or yarn package manager

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/06krish/streamlined-caseflow.git
   cd streamlined-caseflow
   ```

2. **Install frontend dependencies**:
   ```bash
   npm install
   ```

3. **Install backend dependencies**:
   ```bash
   cd Backend
   npm install
   cd ..
   ```

4. **Set up MongoDB**:
   - Ensure MongoDB is running locally on default port (27017)
   - Or update the connection string in `Backend/server.js` for your MongoDB instance

5. **Start the backend server**:
   ```bash
   npm run server
   ```
   The backend will run on `http://localhost:3000` (or configured port)

6. **Start the frontend development server**:
   ```bash
   npm run dev
   ```
   The frontend will run on `http://localhost:5173` (or configured port)

### Building for Production

```bash
npm run build
```

## Making Changes to GitHub Repo

### For Contributors

1. **Fork the repository** on GitHub
2. **Clone your fork**:
   ```bash
   git clone https://github.com/06krish/streamlined-caseflow.git
   ```
3. **Create a feature branch**:
   ```bash
   git checkout -b feature/your-feature-name
   ```
4. **Make your changes** and test thoroughly
5. **Commit your changes**:
   ```bash
   git add .
   git commit -m "Add your descriptive commit message"
   ```
6. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```
7. **Create a Pull Request** on the original repository

### For Repository Owner

1. **Make changes locally**
2. **Stage and commit**:
   ```bash
   git add .
   git commit -m "Your commit message"
   ```
3. **Push to main branch**:
   ```bash
   git push origin main
   ```

### Development Guidelines

- Follow the existing code style and structure
- Test your changes before committing
- Update documentation for any new features
- Ensure all dependencies are properly installed
- Run `npm run build` to verify production build works
