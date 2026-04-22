# Institute Dashboard

A comprehensive dashboard for managing institute operations, built with Next.js, TypeScript, and Tailwind CSS.

## Features

### Institute Profile
- Manage institute information (name, type, address)
- View verification status

### Student Management
- Add and invite new students
- View complete student list
- Approve or reject activity submissions

### Activity & Event Creation
- Create activities with title, description, skill category, and points
- Create events with date, location, and max participants
- View all activities and events

### Analytics Dashboard
- Total student count
- Active vs inactive student breakdown
- Skill-wise performance charts
- Participation rate trends

### Leaderboards
- Top students by total points
- Skill-based rankings

### Reports
- Monthly performance reports
- Export reports as PDF or CSV

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Tech Stack

- **Framework:** Next.js 14 with App Router
- **Language:** TypeScript
- **Styling:** Tailwind CSS
- **Charts:** Recharts
- **Icons:** Lucide React

## Project Structure

```
src/
├── app/
│   ├── analytics/
│   ├── activities/
│   ├── leaderboards/
│   ├── profile/
│   ├── reports/
│   ├── students/
│   ├── globals.css
│   ├── layout.tsx
│   └── page.tsx
└── components/
    └── Sidebar.tsx
```

## Build

To build the project for production:

```bash
npm run build
```

To start the production server:

```bash
npm start
```

## Linting

```bash
npm run lint
```