# TrustFix — Cooperative Gig Services Platform

**Connecting communities with trusted local service providers.**

TrustFix is a prototype platform designed to make it easier for people to discover, accept, and coordinate household and community service jobs. It focuses on building a more organized local service ecosystem through role-based access, location-aware workflows, and synchronized job interactions.

## Live Demo

- **Application:** https://trustfix.ai.studio
- **Source Code:** https://github.com/nkstars/TrustFix

## The Problem

Finding reliable help for household and community tasks can be fragmented and difficult to coordinate. Service seekers need a convenient way to connect with available providers, while providers need a clear workflow for accessing and accepting suitable jobs.

TrustFix explores a digital approach to organizing these interactions within a single platform.

## Our Solution

TrustFix provides a role-based interface for coordinating local service requests and job interactions. Its prototype incorporates location-aware functionality and job-acceptance synchronization to demonstrate how service coordination could work in a community-oriented platform.

## Key Features

- **Role-Based Access:** Interfaces and workflows organized around different user roles.
- **Location-Aware Workflows:** GPS and live-location functionality to support location-based service coordination.
- **Job Acceptance Synchronization:** Designed to keep job-acceptance interactions coordinated across the platform.
- **Community Service Coordination:** A centralized prototype for connecting service requests with local service providers.
- **AI Integration:** Built using Google AI Studio and the Gemini API as part of the application's development.

## Technology Stack

- **Frontend:** React, TypeScript
- **Build Tool:** Vite
- **Styling:** Tailwind CSS
- **AI Integration:** Google GenAI SDK / Gemini API
- **Deployment:** AI Studio-hosted demo

## Getting Started

### Prerequisites

- Node.js and npm
- A Google Gemini API key

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/nkstars/TrustFix.git
   cd TrustFix
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Create a `.env.local` file in the project root and add your API key:

   ```env
   GEMINI_API_KEY=your_gemini_api_key
   ```

   Replace `your_gemini_api_key` with your own key. Do not commit API keys or other secrets to GitHub.

4. Start the development server:

   ```bash
   npm run dev
   ```

5. Open the local URL printed in the terminal.

### Available Scripts

| Command | Purpose |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the application for deployment |
| `npm run preview` | Preview the production build |
| `npm run lint` | Run the TypeScript check configured in the project |

## Project Status

TrustFix is a hackathon prototype. Features and integrations should be evaluated against the current implementation; production deployment would require further validation of authentication, location permissions, job-state consistency, data storage, privacy, and security.

## Future Improvements

- Persistent backend and database integration
- Stronger authentication and role-based authorization
- More robust job assignment and status tracking
- Provider verification and trust indicators
- Improved location-based matching
- Notifications and job-history management
- Accessibility, privacy, and security testing
