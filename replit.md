# CREDSCOPE - Finance Tracking & Investment Insights Platform

## Overview
CREDSCOPE is a modern, production-ready finance tracking and investment insights platform built with React, TypeScript, and Express. The application features stunning animations, AI-powered insights using OpenAI, and comprehensive portfolio management capabilities.

## Recent Changes (Nov 10, 2025)
- **Frontend Complete**: Implemented all core pages with exceptional visual quality
  - Landing page with animated hero section and feature showcase
  - Dashboard with portfolio summary cards, interactive charts, and transaction history
  - Profile & Goals page with editable user information and animated progress tracking
  - Insights page with AI-powered recommendations and analytics charts
- **Design System**: Configured custom color palette (Teal #00BFA6, Deep Blue #002B5B)
- **Animations**: Integrated Framer Motion for smooth page transitions and micro-interactions
- **Theme Support**: Implemented dark/light mode toggle with persistent storage

## Project Architecture

### Technology Stack
- **Frontend**: React 18 + Vite, TypeScript, Wouter (routing)
- **Styling**: TailwindCSS, shadcn/ui components, custom glassmorphism effects
- **Animations**: Framer Motion for smooth transitions and interactions
- **Charts**: Recharts for data visualizations
- **Icons**: Lucide React
- **State Management**: TanStack Query (React Query)
- **Backend**: Express.js, TypeScript
- **Storage**: In-memory storage (MemStorage)
- **AI Integration**: OpenAI GPT-5 for investment insights

### Data Schema
- **UserProfile**: User information, risk tolerance, investment experience
- **PortfolioAsset**: Stock/asset holdings with purchase and current prices
- **Transaction**: Buy/sell transaction history
- **FinancialGoal**: Savings goals with progress tracking
- **PortfolioPerformance**: Historical performance data for charts

### Folder Structure
```
├── client/
│   ├── src/
│   │   ├── components/
│   │   │   ├── Navbar.tsx (animated navigation with scroll effects)
│   │   │   ├── ThemeProvider.tsx (dark/light mode management)
│   │   │   ├── ThemeToggle.tsx (theme switcher button)
│   │   │   └── ui/ (shadcn components)
│   │   ├── pages/
│   │   │   ├── Landing.tsx (hero section, features, CTA)
│   │   │   ├── Dashboard.tsx (portfolio overview, charts, transactions)
│   │   │   ├── Profile.tsx (user profile, financial goals)
│   │   │   └── Insights.tsx (AI assistant, analytics)
│   │   ├── lib/
│   │   │   └── queryClient.ts (API configuration)
│   │   └── App.tsx (routing, providers)
│   └── index.html (SEO meta tags, Poppins/Inter fonts)
├── server/
│   ├── routes.ts (API endpoints - to be implemented)
│   └── storage.ts (data persistence interface)
├── shared/
│   └── schema.ts (TypeScript types and Zod schemas)
└── design_guidelines.md (comprehensive design specification)
```

## User Preferences
- **Font**: Poppins (primary), Inter (alternative)
- **Colors**: Deep Blue (#002B5B), Teal (#00BFA6), Soft White (#F8FAFC)
- **Style**: Glassmorphism cards, rounded corners, smooth animations
- **Responsive**: Mobile-first design with breakpoints at 768px and 1024px

## API Endpoints (To Be Implemented)
- `GET /api/profile` - Get user profile
- `PATCH /api/profile` - Update user profile
- `GET /api/portfolio` - Get portfolio assets
- `GET /api/transactions` - Get transaction history
- `GET /api/performance` - Get portfolio performance data
- `GET /api/goals` - Get financial goals
- `POST /api/ai-insights` - Generate AI investment insights

## Features
1. **Landing Page**: Animated hero with gradient background, feature cards, CTA sections
2. **Dashboard**: Real-time portfolio tracking with interactive charts (Line, Area, Pie)
3. **Profile & Goals**: Editable user profile with animated progress bars for financial goals
4. **AI Insights**: OpenAI-powered investment recommendations with analytics visualizations
5. **Theme Support**: Dark/light mode toggle with smooth transitions
6. **Animations**: Page transitions, scroll effects, hover states using Framer Motion

## Design Principles
- Glassmorphism effect on cards with backdrop blur
- Consistent spacing (small: 0.5rem, medium: 1rem, large: 2rem)
- Three-level text hierarchy (default, secondary, tertiary)
- Smooth animations (fade, slide, scale) at 60fps
- Accessible color contrast (WCAG AA compliant)
- Mobile-first responsive design

## Next Steps
1. Implement backend API endpoints
2. Set up OpenAI integration for AI insights
3. Connect frontend to backend with React Query
4. Add loading and error states
5. Test complete user journeys
