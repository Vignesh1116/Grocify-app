# Grocify Application

A robust mobile application for managing grocery lists and meal planning, built using the latest Expo SDK 56. 

## Features
- **Cross-Platform**: Runs on Android and iOS using React Native.
- **Authentication**: Secure login and sign-up using Clerk.
- **Database**: Serverless PostgreSQL via Neon DB and Drizzle ORM.
- **State Management**: Zustand for rapid global state access.
- **Styling**: Tailwind CSS & NativeWind.

## Setup Instructions

1. **Environment Variables**:
   Copy the `.env.example` file to `.env` and fill in your API keys:
   ```bash
   cp .env.example .env
   ```
   *You will need both a Neon Database URL and a Clerk Publishable Key.*

2. **Install Dependencies**:
   If not already installed, run:
   ```bash
   npm install
   ```

3. **Database Schema Push**:
   Push the Drizzle ORM schema to your Neon DB:
   ```bash
   npm run db:push
   ```

4. **Start the Application**:
   Start the Expo development server:
   ```bash
   npx expo start
   ```

## Requirements
- Expo SDK 56
- Node.js 18+

*This application was recreated based on the `burakorkmez/grocify-expo` reference repository.*
