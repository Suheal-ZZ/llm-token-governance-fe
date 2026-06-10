# LLM Token Governance Frontend

React + Vite frontend application for managing LLM projects, budgets, token usage, API keys, analytics, and user access.

## Features

- Dashboard Overview
- Project Management
- Budget Configuration
- User Management
- Usage Analytics
- API Key Management
- Audit Logs
- Alerts & Notifications

## Tech Stack

- React 19
- Vite
- TypeScript
- Material UI
- React Router
- React Query
- Axios
- Recharts

## Project Structure

```text
src/
├── components/
├── pages/
├── services/
├── hooks/
├── context/
├── layouts/
├── routes/
├── types/
├── utils/
├── assets/
└── App.tsx
```

## Installation

### Install Dependencies

```bash
npm install
```

### Start Development Server

```bash
npm run dev
```

Application URL:

```text
http://localhost:5173
```

## Build

```bash
npm run build
```

## Environment Variables

Create a `.env` file:

```env
VITE_API_BASE_URL=http://localhost:8000/api/v1
```

## API Integration

```typescript
import axios from "axios";

export const api = axios.create({
  baseURL: import.meta.env.VITE_API_BASE_URL,
});
```

## Run Tests

```bash
npm run test
```

## Build for Production

```bash
npm run build
npm run preview
```

## License

Internal Use Only
