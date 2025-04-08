# React App with Docker and GitHub Pages

[![Deploy to GitHub Pages](https://github.com/yourusername/my-app/actions/workflows/deploy.yml/badge.svg)](https://github.com/yourusername/my-app/actions/workflows/deploy.yml)

A React application built with Vite, featuring Docker development environment and automated deployment to GitHub Pages.

## Technology Stack
- React
- Vite
- Docker
- GitHub Actions

## Development Setup

### Prerequisites
- Docker and Docker Compose
- Node.js 18+ (for local development without Docker)

### Running with Docker
1. Start the development server:
```bash
docker-compose up
```
2. Visit http://localhost:5173 in your browser

### Running Locally
1. Install dependencies:
```bash
npm install
```
2. Start the development server:
```bash
npm run dev
```
3. Visit http://localhost:5173 in your browser

## Deployment
The application is automatically deployed to GitHub Pages when changes are pushed to the main branch. You can also trigger a manual deployment from the GitHub Actions tab.

## Project Structure
```
my-app/
├── src/           # Source files
├── public/        # Static files
├── Dockerfile.dev # Development Docker configuration
└── docker-compose.yml # Docker Compose configuration
```

## Available Scripts
- `npm run dev`: Start development server
- `npm run build`: Build for production
- `npm run preview`: Preview production build locally
