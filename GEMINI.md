# Gemini Project Configuration (`GEMINI.md`)

This file provides project-specific context and instructions for the Gemini CLI agent. By maintaining this file, you can ensure the agent adheres to your project's standards, conventions, and requirements.

## 1. Project Overview

- **Project Name:** ERD Flow
- **Description:** A web-based tool for creating and visualizing Entity-Relationship Diagrams (ERDs) from SQL schema
- **Repository:** https://github.com/AprilYoungs/ERD_Flow

## 2. Key Technologies & Frameworks

- **Frontend:** React, TypeScript, Vite
- **Styling:** Tailwind CSS, shadcn/ui
- **State Management:** Zustand
- **Backend:** Node.js, Express.js
- **Database:** PostgreSQL
- **ORM:** Prisma
- **Authentication:** JWT

## 3. Commands

Use these commands to build, run, test, and lint the project.

- **Install Dependencies:**
  ```bash
  npm install
  ```
- **Run Development Server:**
  ```bash
  npm run dev
  ```
- **Build for Production:**
  ```bash
  npm run build
  ```
- **Run Tests:**
  ```bash
  npm test
  ```
- **Lint and Format:**
  ```bash
  npm run lint
  ```
- **Run Type-Checking:**
  ```bash
  npm run typecheck
  ```

## 4. Coding Conventions & Style

- **Language:** TypeScript
- **Style Guide:** [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript)
- **Formatting:** Prettier (config in `.prettierrc`)
- **Naming:**
  - Components: `PascalCase` (e.g., `UserProfile.tsx`)
  - Functions/Variables: `camelCase` (e.g., `getUserProfile`)
  - Types/Interfaces: `PascalCase` with `T` prefix or `Type`/`Props` suffix (e.g., `TUser`, `UserProfileProps`)
- **Comments:** Add JSDoc comments for all exported functions and complex logic.

## 5. Project Structure

- `src/`: Main application source code.
  - `components/`: Reusable React components.
  - `pages/`: Top-level page components.
  - `lib/`: Utility functions and helpers.
  - `hooks/`: Custom React hooks.
  - `services/`: API interaction logic.
- `public/`: Static assets.
- `tests/`: Test files.
- `prisma/`: Database schema and migrations.

## 6. Important URLs

- **Staging Environment:** [https://staging.erd-flow.example.com](https://staging.erd-flow.example.com)
- **Production Environment:** [https://erd-flow.example.com](https://erd-flow.example.com)
- **API Documentation:** [https://api-docs.erd-flow.example.com](https://api-docs.erd-flow.example.com)
