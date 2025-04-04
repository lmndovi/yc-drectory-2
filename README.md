🚀 YC Directory

Welcome to YC Directory! This is a platform where entrepreneurs can share their startup ideas, browse other projects, and gain visibility. Think of it as a virtual pitch competition space, designed with a clean and minimal user experience.

Check it out live: YC Directory on Vercel

🔎 Source Code: GitHub Repository

📌 Table of Contents

Introduction

Tech Stack

Features

Getting Started

Environment Variables

Additional Notes

🤖 Introduction

YC Directory is a sleek, simple platform built with Next.js 15 and powered by Sanity. Entrepreneurs can submit their startup pitches, discover new ideas, and gain inspiration from fellow founders. Admins also have the ability to highlight standout projects using the "Editor Picks" feature.

This project was a great opportunity to explore modern front-end development with React 19 and TailwindCSS, while also leveraging Sanity's real-time content management.

⚙️ Tech Stack

Here's what I used to build YC Directory:

React 19 - The latest and greatest for UI development.

Next.js 15 - Full-stack capabilities with server-side rendering and API routes.

Sanity - For managing and displaying dynamic content.

TailwindCSS - Rapid, modern styling.

ShadCN - Component library for clean UI.

TypeScript - For type safety and improved developer experience.

🔋 Features

Pitch Submission: Users can submit startup ideas with titles, descriptions, categories, and media links (images or videos).

Browse and Filter: Easily explore other pitches and filter by category.

Pitch Details: Click on a pitch to view more information, including multimedia.

Profile Management: View your submitted pitches on your profile page.

Editor Picks: Admins can feature top startup ideas using Sanity Studio.

Views Counter: Tracks views for each pitch.

Search Functionality: Find pitches quickly using the search bar.

GitHub Authentication: Sign in using your GitHub account for convenience.

🤸 Getting Started

Follow these steps to get the project running locally:

Prerequisites

Make sure you have the following installed:

Git

Node.js

npm or yarn

Clone the Repository

git clone https://github.com/lmndovi/yc-drectory-2.git
cd yc-drectory-2

Install Dependencies

npm install
# or
yarn install

Set Up Environment Variables

Create a .env.local file in the root of your project and add the following variables:

NEXT_PUBLIC_SANITY_PROJECT_ID=your_project_id
NEXT_PUBLIC_SANITY_DATASET=your_dataset
NEXT_PUBLIC_SANITY_API_VERSION='vX'
SANITY_TOKEN=your_token

AUTH_SECRET=your_auth_secret
AUTH_GITHUB_ID=your_github_client_id
AUTH_GITHUB_SECRET=your_github_client_secret

Get these credentials from your Sanity and GitHub OAuth settings.

Run the Project

npm run dev

Navigate to http://localhost:3000 to see it in action!

🚀 Additional Notes

The views counter is implemented without a traditional upvote system to keep things simple.

Sanity Studio is integrated for easy content management and admin controls.

The minimalist UI ensures an intuitive user experience.

If you'd like to contribute, have any feedback, or just want to connect, feel free to reach out!

Happy coding and pitching! 🛠️
