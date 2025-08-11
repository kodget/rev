# Rev – Mobile Device Repair Matching App
## Overview
Rev is a mobile-first platform that matches users with vetted technicians for mobile device repairs.
The MVP focuses on quick booking, technician assignment, and real-time repair status tracking.
## Features (MVP)
Request a Repair – Users submit device, issue, and location.
Technician Dashboard – View and manage assigned repair requests.
Status Tracking – Users can track repair progress in real time via a unique link.
Notifications (planned) – SMS/email updates for booking and status changes.
Analytics (planned) – User behavior tracking with Google Analytics & Firebase Analytics.
## Tech Stack
### Frontend:
Next.js 13+ (App Router)
Chakra UI – UI components & styling
React Hooks for state management
### Backend (Planned):
Firebase Firestore – Real-time database
Firebase Hosting
Twilio – SMS/WhatsApp notifications
SendGrid – Email notifications
### Analytics (Planned):
Google Analytics 4
Firebase Analytics
## Project Structure
rev-mvp/
├── public/                 # Static assets
├── src/
│   ├── app/                # App Router pages
│   ├── components/         # Reusable UI components
│   ├── assets/             # Images, icons, brand colors
│   ├── lib/                # Utility functions (Firebase, API helpers)
│   ├── styles/             # Theme & global styles
│   └── hooks/              # Custom React hooks
├── .env.local              # Environment variables
└── README.md
## Notes for Contributors
### Stick to brand colors:
Primary: #1E3A8A
Secondary: #F97316
Accent: #14B8A6
### Use Chakra UI components for consistent styling.
Pages should be mobile-first and responsive.


# To run this: 
type npm run dev on your terminal and hit enter
# or
yarn dev
# or
pnpm dev
# or
bun dev
Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.
You can start editing the page by modifying `app/page.js`. The page auto-updates as you edit the file.
This project uses [`next/font`](https://nextjs.org/docs/app/building-your-application/optimizing/fonts) to automatically optimize and load [Geist](https://vercel.com/font), a new font family for Vercel.
## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/app/building-your-application/deploying) for more details.
