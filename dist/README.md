# Cosmic Noir Portfolio

A high-impact, cinematic portfolio website built with React and Vite. It features a dark "Cosmic Noir" editorial design system, leveraging modern web technologies to deliver an immersive and performant user experience.

## Tech Stack

- **Framework**: [React 19](https://react.dev/) with [Vite](https://vitejs.dev/)
- **Styling**: [Tailwind CSS](https://tailwindcss.com/)
- **3D Graphics & Animations**: 
  - [Three.js](https://threejs.org/)
  - [@react-three/fiber](https://docs.pmnd.rs/react-three-fiber/getting-started/introduction)
  - [@react-three/drei](https://github.com/pmndrs/drei)
  - [@shadergradient/react](https://www.shadergradient.co/)
  - [Framer Motion](https://www.framer.com/motion/)
- **Scrolling**: [Lenis](https://lenis.studiofreight.com/) (Smooth scroll)
- **Icons**: [Lucide React](https://lucide.dev/)

## Prerequisites

- Node.js (version 18+ recommended)
- npm or yarn

## Getting Started

1. **Clone the repository** (if you haven't already):
   ```bash
   git clone <your-repo-url>
   cd port
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Start the development server**:
   ```bash
   npm run dev
   ```
   The application will be available at `http://localhost:5173`.

## Scripts

- `npm run dev`: Starts the local development server.
- `npm run build`: Builds the app for production in the `dist` folder.
- `npm run preview`: Locally previews the production build.
- `npm run deploy`: Builds the project and runs the custom deployment script (`deploy.js`).
- `npm run lint`: Analyzes the code for potential errors using ESLint.

## Deployment

This project includes a custom deployment script using FTP/SFTP. You will need a `.env` file with your deployment credentials:

```env
FTP_HOST=your_ftp_host
FTP_USER=your_ftp_username
FTP_PASSWORD=your_ftp_password
```

Run `npm run deploy` to build and upload the contents of the `dist` folder to your server.
