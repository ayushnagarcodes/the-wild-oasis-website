# The Wild Oasis Website

Customer-side website for [The Wild Oasis](https://github.com/ayushnagarcodes/the-wild-oasis). It allows users to browse cabins and book reservations effortlessly. Built with Next.js to utilize SSR and other benefits. Watch live <a href="https://ayush-wild-oasis-website.vercel.app/" target="_blank">here</a> ➡️

<br />

## Key Features

- Users can view and reserve cabins.
- Users need to log in with their Google account to make a reservation.
- Image and font optimizations.
- Implemented optimistic UI updates using the `useOptimistic` hook for deleting reservations.
- Used Suspense API to display loading indicators effectively.
- Implemented mutations using Server Actions.

<br />

## Tools and Packages

- **Build Tool:** `create-next-app`.
- Supabase for backend (data storage & CRUD operations).
- Context API for UI state management.
- Tailwind CSS for styling.
- Auth.js for authentication.
- `react-day-picker` for date selection.
- `date-fns` for date calculations.

<br />

## Project Setup

Make sure `node` and `npm` are installed. Run the following command in the terminal:

1. `npm i` or `npm install`
2. `npm run dev`
