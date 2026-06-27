# DevConnect Frontend

## Purpose

This is the frontend application for DevConnect, a platform for developers to showcase projects, skills, and connect with other developers.

## Tech Stack

- React 18
- TypeScript
- Vite
- React Router DOM

## How to Run

### Prerequisites

- Node.js (v18 or higher)
- npm or yarn

### Installation

```bash
npm install
```

### Development

```bash
npm run dev
```

The application will be available at `http://localhost:5173`

### Build

```bash
npm run build
```

### Preview Build

```bash
npm run preview
```

## Commands

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run linter

## Folder Structure

```
src/
├── assets/          # Static assets (images, fonts, etc.)
├── components/      # React components
│   ├── common/      # Shared/common components
│   ├── layout/      # Layout components
│   └── ui/          # UI components (Reserved for Abhiram)
├── pages/           # Page components (Reserved for Abhiram)
│   ├── Home/
│   ├── Login/
│   ├── Register/
│   ├── Profile/
│   └── Dashboard/
├── layouts/         # Page layout wrappers
├── hooks/           # Custom React hooks
├── services/        # API and data services
│   ├── api/         # Backend API integration (Reserved for Backend)
│   └── mock/        # Mock data services
├── types/           # TypeScript type definitions
├── utils/           # Utility functions
├── routes/          # Route configuration
├── styles/          # Global styles
├── context/         # React context providers
├── constants/       # Application constants
├── config/          # Configuration files
└── tests/           # Test files
```

## Contribution Guide

### Branch Workflow

1. Create a new branch from `main` or `feature/frontend-setup`
2. Make your changes
3. Test thoroughly
4. Commit changes with clear messages
5. **Open Pull Request before merging**

### Code Style

- Follow TypeScript best practices
- Use functional components with hooks
- Write meaningful component names
- Add comments for complex logic

### Team Responsibilities

**Jonatan (Frontend Lead)**
- Frontend architecture
- Repository organization
- React initialization
- Project coordination
- Integration later

**Abhiram (UI/UX)**
- UI Components
- Screens
- Design System
- Visual Design

**Aristóteles (Backend)**
- Backend
- API
- Database
- Authentication
- Data layer

## Notes

- This is Phase 1: Frontend foundation only
- Backend integration will be added later
- UI components and screens are placeholders
- Coordinate with team before making architectural changes
