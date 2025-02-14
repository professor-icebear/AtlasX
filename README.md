# AtlasX 🌍✈️

A modern AI-powered travel planning platform built with Next.js 14 and OpenAI.

## Overview

AtlasX is a full-stack application that leverages AI to create personalized travel itineraries. Simply input your travel preferences like "2 days trip to London with budget $1000," and get a detailed, AI-generated travel plan complete with scheduling, budgeting, and local recommendations.

## Features

- 🤖 AI-powered travel planning with OpenAI integration
- 🗺️ Interactive maps with Google Maps API
- 💰 Budget tracking and management
- 📅 Smart itinerary scheduling
- 🌐 Community-shared travel plans
- 🎨 Beautiful, responsive UI with Tailwind CSS
- 🔐 Secure authentication with Clerk
- 💳 Payment integration with Stripe and Razorpay

## Tech Stack

### Frontend
- **Framework**: Next.js 14 (App Router)
- **Language**: TypeScript
- **Styling**: Tailwind CSS
- **UI Components**: Radix UI
- **State Management**: React Hooks
- **Maps**: Google Maps API
- **Forms**: React Hook Form + Zod

### Backend
- **Database**: Convex
- **Authentication**: Clerk
- **AI**: OpenAI API
- **Payments**: Stripe, Razorpay
- **Email**: Resend

## Quick Start

1. Clone the repository
```bash
git clone https://github.com/professor-icebear/AtlasX.git
cd AtlasX
```

2. Install dependencies
```bash
pnpm install
```

3. Set up environment variables
```bash
cp .env.example .env
```

Required environment variables:
- `NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY`
- `CLERK_SECRET_KEY`
- `OPENAI_API_KEY`
- `NEXT_PUBLIC_CONVEX_URL`
- `GOOGLE_MAPS_API_KEY`
- `STRIPE_SECRET_KEY`
- `NEXT_PUBLIC_STRIPE_PUBLISHABLE_KEY`

4. Start the development server
```bash
pnpm dev
```

## Project Structure

```
AtlasX/
├── app/                # Next.js app router pages
├── components/         # Reusable UI components
├── contexts/          # React context providers
├── convex/            # Convex backend functions
├── hooks/             # Custom React hooks
├── lib/               # Utility functions
└── public/            # Static assets
```

## License

MIT

---
Built with Next.js 14 and OpenAI 🚀
