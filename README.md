# Namma Platform — Station Guide

**Namma Platform** is a modern, bilingual (English & Kannada) web application designed to help commuters in Karnataka find their railway stations, check platform information, and view upcoming train schedules.

Built with **TanStack Start**, it offers a fast, type-safe, and highly interactive user experience with server-side rendering capabilities.

## ✨ Features

- **Bilingual Support**: Full support for English and Kannada (ಕನ್ನಡ) languages.
- **Station Search**: Quickly find stations by name (English/Kannada) or station code.
- **Recent Stations**: Remembers your recently visited stations for quick access.
- **Real-time Feel**: Displays next trains and platform details (using demo data for v1).
- **High Contrast Mode**: Accessible design with a dedicated high-contrast toggle.
- **Responsive Design**: Optimized for mobile and desktop viewing.

## 🛠️ Tech Stack

- **Framework**: [TanStack Start](https://tanstack.com/router/v1/docs/guide/start/overview) (React + TanStack Router)
- **Language**: TypeScript
- **Styling**: [Tailwind CSS v4](https://tailwindcss.com/)
- **UI Components**: [Radix UI](https://www.radix-ui.com/) & Lucide Icons
- **Runtime/Package Manager**: [Bun](https://bun.sh/) (Compatible with npm/pnpm/yarn)
- **Deployment**: Cloudflare Pages/Workers

## 🚀 Getting Started

### Prerequisites

- [Bun](https://bun.sh/) installed on your machine (recommended).
- Alternatively, Node.js (v18+) and npm/pnpm.

### Installation

1.  **Clone the repository**:
    ```bash
    git clone <repository-url>
    cd namma-station-guide
    ```

2.  **Install dependencies**:
    ```bash
    bun install
    ```
    *(Or `npm install` / `pnpm install`)*

### Development

Run the development server with Hot Module Replacement (HMR):

```bash
bun dev
```

The application will be available at `http://localhost:3000`.

### Production Build

To build the application for production:

```bash
bun build
```

This will generate a production-ready build in the `.output` (or `dist`) directory, optimized for your deployment target.

## 🌐 Deployment

The project is configured for **Cloudflare** using `wrangler`.

To deploy to Cloudflare:

```bash
bun wrangler deploy
```

## 📁 Project Structure

- `src/routes/`: Contains the application pages and routing logic (TanStack Router).
- `src/components/`: Reusable UI components.
- `src/lib/`: Data fetching logic, types, and utility functions.
- `src/styles.css`: Global styles and Tailwind imports.
- `wrangler.jsonc`: Configuration for Cloudflare deployment.

---

Built with ❤️ for commuters in Karnataka.
