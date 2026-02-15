# HostelFlow - Smart Hostel Management Automation

HostelFlow is a modern, responsive full-stack hostel management web application designed for college campuses. It automates mess attendance, issue reporting, and fine management.

## Tech Stack
- **Framework**: Next.js 14 (App Router)
- **Styling**: Tailwind CSS + Shadcn Design Principles
- **Icons**: Lucide React
- **State Management**: React Context (Simulated Backend Logic)

## Features
- **Smart Mess Attendance**: Mark attendance 2 hours prior. Auto-fine generation for absentees.
- **Complaint System**: Categorized issue reporting with status tracking.
- **Admin Dashboard**: Real-time analytics, fine reports, and complaint resolution.
- **Mobile Responsive**: Fully optimized for mobile and desktop.

## Project Structure
- `src/app`: App Router pages.
  - `(main)`: Authenticated routes with Sidebar layout.
  - `dashboard`: Smart dashboard switching (Student/Admin).
  - `mess`: Mess attendance interface.
  - `complaints`: Issue reporting.
- `src/components`: Reusable UI components.
- `src/context`: Global state management simulating valid backend logic.

## Getting Started

1. Install dependencies:
   ```bash
   npm install
   ```

2. Run the development server:
   ```bash
   npm run dev
   ```

3. Open [http://localhost:3000](http://localhost:3000) with your browser.

## Logic Overview (Simulation)
- **Attendance**: Toggle status. Click "Scan QR" to confirm consumption.
- **Automation**: In Admin Dashboard, click "Run EOD Automation" to generate fines for marked-but-absent students.
- **Data Persistence**: In-memory (resets on refresh).
