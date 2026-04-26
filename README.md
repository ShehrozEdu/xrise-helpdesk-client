# XRise Helpdesk - Client

A modern, responsive React-based helpdesk client for the XRise Mini Helpdesk system. Built with Vite, React, TypeScript, and Tailwind-inspired custom CSS.

## 🚀 Features

- **Public Ticket Submission**: Users can submit tickets without an account.
- **Ticket Status Tracking**: Real-time status updates via Socket.io.
- **Agent Dashboard**: Manage, assign, and reply to tickets.
- **AI-Powered Drafts**: Integration with Groq Llama 3 for intelligent reply suggestions.
- **Real-time Notifications**: Instant updates when tickets are updated or assigned.
- **Responsive Design**: Fully optimized for mobile, tablet, and desktop.

## 🛠️ Tech Stack

- **Framework**: React 18 with Vite
- **Language**: TypeScript
- **State Management**: Zustand
- **Data Fetching**: TanStack Query (React Query)
- **Real-time**: Socket.io Client
- **Icons**: Lucide React
- **Animations**: Custom CSS Keyframes

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- The Backend server running (see the [Backend Repo](https://github.com/ShehrozEdu/xrise-helpdesk-monorepo))

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/ShehrozEdu/xrise-helpdesk-client.git
   cd xrise-helpdesk-client
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure Environment Variables:
   Create a `.env` file in the root:
   ```env
   VITE_API_URL=http://localhost:5000/api
   ```

4. Start the development server:
   ```bash
   npm run dev
   ```

## 🏗️ Project Structure

- `src/components`: Reusable UI components (Layout, Badge, etc.)
- `src/hooks`: Custom React hooks for logic and state.
- `src/pages`: Main application views (Dashboard, Login, etc.)
- `src/services`: API client definitions using Axios.
- `src/store`: Global state management with Zustand.
- `src/shared`: Localized shared types and validation schemas.

## 🌐 Deployment

This project is ready for deployment on **Vercel**.

1. Connect this repo to Vercel.
2. Set the Environment Variable `VITE_API_URL` to your production backend URL.
3. Deploy!

---
Built by [Shehroz](https://github.com/ShehrozEdu)
