
# Student Management System

A full-stack student administration platform designed to manage academic records and streamline educational institution workflows. The system provides dedicated modules for students, teachers, attendance, examinations, fees, academic records, and teacher assignments.

## Overview

The Student Management System centralizes academic and administrative operations through a web-based platform. It includes management interfaces and backend APIs for handling student information, teacher records, attendance, examinations, fees, and academic data.

## Features

### Student Management
- Manage student records
- View and organize student information
- Student dashboard and portal

### Teacher Management
- Teacher records management
- Teacher dashboard
- Teacher assignments

### Academic Management
- Academic records management
- Examination management
- Examination results
- Attendance tracking

### Administration
- Administration dashboard
- Fee management
- User authentication
- Password reset functionality

## Tech Stack

| Technology | Purpose |
|---|---|
| Next.js | Full-stack web framework |
| React | Frontend UI |
| TypeScript | Type-safe development |
| Prisma ORM | Database ORM |
| PostgreSQL | Database |
| Node.js | Runtime environment |
| Git & GitHub | Version control |

## Getting Started

### Prerequisites

- Node.js
- npm
- PostgreSQL
- Git

### Installation

Clone the repository:

```bash
git clone https://github.com/AnanyaSRV/Student-Management-System.git
```

Navigate into the project:

```bash
cd Student-Management-System
```

Install dependencies:

```bash
npm install
```

## Environment Configuration

Create the environment configuration file required by the project.

Configure the necessary variables, including:

- Database connection URL
- Authentication-related configuration
- Other application-specific settings

Do not commit sensitive credentials, private keys, or database passwords.

## Database Setup

Ensure PostgreSQL is installed and running, and configure your database connection.

Generate the Prisma client:

```bash
npx prisma generate
```

Apply migrations:

```bash
npx prisma migrate dev
```

## Run the Development Server

Start the application:

```bash
npm run dev
```

Open your browser:

```text
http://localhost:3000
```

## Project Structure

```text
Student-Management-System/
├── app/
│   ├── academic-records/
│   ├── administration/
│   ├── api/
│   ├── attendance/
│   ├── dashboard/
│   ├── examinations/
│   ├── fees/
│   ├── student-portal/
│   ├── students/
│   ├── teacher-assignments/
│   ├── teacher-dashboard/
│   └── teachers/
├── lib/
├── prisma/
│   ├── migrations/
│   └── schema.prisma
├── public/
├── scripts/
├── package.json
├── package-lock.json
├── next.config.ts
├── prisma.config.ts
├── tsconfig.json
└── README.md
```

## Future Improvements

- Advanced academic analytics and reporting
- Enhanced student performance insights
- Expanded administrative workflows
- Additional dashboard visualizations
- Further UI/UX enhancements

## Author

**Ananya SRV**

- GitHub: [@AnanyaSRV](https://github.com/AnanyaSRV)
- Repository: [Student Management System](https://github.com/AnanyaSRV/Student-Management-System)

---

Developed as a full-stack project exploring student administration, academic management, database integration, and modern web application development.
