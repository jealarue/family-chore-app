# FamilyChores - Family Chore Management App

A web application for managing family chores with a points/rewards system. This app allows parents to assign tasks to children, verify completion, and manage rewards based on points earned.

## Features

- **User Management**: Admin (parent) and user (children) roles with different permissions
- **Task Management**: Create, assign, and track chores
- **Points System**: Earn points for completing tasks with bonuses for good behavior
- **Rewards System**: Convert points to rewards or money
- **Leaderboard**: Friendly competition among family members
- **Calendar View**: Schedule and view upcoming tasks
- **Notifications**: Reminders and updates about tasks and rewards
- **Analytics**: Track progress and performance over time

## Tech Stack

- **Frontend**: Next.js 14, React 18, Tailwind CSS, Framer Motion
- **Backend**: Next.js API Routes
- **Database**: PostgreSQL with Prisma ORM
- **Authentication**: NextAuth.js
- **UI Components**: Radix UI, Lucide Icons

## Getting Started

### Prerequisites

- Node.js 18+ and npm/yarn
- PostgreSQL database

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/yourusername/family-chores.git
   cd family-chores
   ```

2. Install dependencies:
   ```
   npm install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory with the following:
   ```
   DATABASE_URL="postgresql://username:password@localhost:5432/familychores"
   NEXTAUTH_SECRET="your-secret-key"
   NEXTAUTH_URL="http://localhost:3000"
   ```

4. Initialize the database:
   ```
   npx prisma db push
   ```

5. Run the development server:
   ```
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Initial Setup

After starting the application for the first time:

1. Create an admin account (parent)
2. Add children as users
3. Create task categories
4. Set up rewards
5. Configure point-to-money conversion rates in settings

## License

This project is licensed under the MIT License - see the LICENSE file for details.