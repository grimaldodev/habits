This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Requirements

**Objective:** Develop a habit tracker app where users can create, manage, and track their daily habits. The app should provide a simple interface for adding habits, marking them as complete, and viewing progress over time.

### Requirements:

Home Screen:

Display a list of all active habits with the current streak (number of consecutive days the habit has been completed).
Include a button to add a new habit.
Add Habit Screen:

Allow users to create a new habit by entering a habit name, selecting a frequency (daily, weekly, etc.), and choosing a start date.
Include validation to ensure that the habit name is not empty.
Habit Detail Screen:

Show detailed information about the habit, including its creation date, frequency, and current streak.
Allow users to mark the habit as completed for the current day.
Progress Visualization:

Include a simple chart or calendar view that shows the user’s progress for each habit over the past 30 days.
Highlight the days when the habit was completed.
Notifications:

Implement a simple notification system that reminds users to complete their habits at a set time each day.
State Management:

Use React’s context API or a state management library (like Redux) to manage the application's state, especially for storing habits and tracking completion.
Constraints:

Emphasize clean, maintainable code with comments explaining key parts.
Candidates should use in-app data storage (e.g., AsyncStorage or local storage) to persist habit data between sessions.
Submission:

Include instructions on how to run the app locally.

