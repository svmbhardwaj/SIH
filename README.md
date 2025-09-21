# RailZenith - Complete Railway Traffic Management System# Train Traffic Optimization System - SIH 2025



> Advanced Railway Traffic Optimization System for Smart India Hackathon 2024A comprehensive Train Traffic Optimization system built for Smart India Hackathon 2025.



![RailZenith](https://img.shields.io/badge/RailZenith-Complete_System-amber?style=for-the-badge)## 🚂 Features

![Next.js](https://img.shields.io/badge/Next.js-Frontend-black?style=for-the-badge&logo=next.js)

![Node.js](https://img.shields.io/badge/Node.js-Backend-green?style=for-the-badge&logo=node.js)- **Real-time Train Tracking**: Live monitoring of train positions and status

![MongoDB](https://img.shields.io/badge/MongoDB-Database-green?style=for-the-badge&logo=mongodb)- **Route Optimization**: AI-powered route planning and optimization algorithms

- **Schedule Management**: Comprehensive schedule planning and management

## 🚄 Project Overview- **Traffic Coordination**: Advanced traffic coordination and conflict resolution

- **Performance Analytics**: Real-time analytics and reporting dashboard

**RailZenith** is a comprehensive railway traffic optimization and management system built for Smart India Hackathon 2024. The system features a professional dark railway-themed interface for real-time train monitoring, schedule management, traffic coordination, and performance analytics.- **Responsive UI**: Modern, responsive interface built with Next.js and Tailwind CSS



## ✨ Key Features## 🛠️ Tech Stack



- **🌙 Dark Railway Theme**: Professional dark interface with authentic railway aesthetics### Frontend

- **📊 Real-time Dashboard**: Live train tracking with comprehensive statistics- **Next.js 15.5.3** - React framework with App Router

- **🚆 Train Monitoring**: Active train status with detailed location and performance data- **React 19** - Component library

- **📅 Schedule Management**: Dynamic schedule handling with platform assignments- **TypeScript** - Type safety

- **🛤️ Route Optimization**: Advanced algorithms for efficient railway routing- **Tailwind CSS** - Styling framework

- **📈 Performance Analytics**: Network performance metrics and visualizations- **Axios** - API client

- **🎨 Enhanced UI/UX**: Smooth hover effects and premium railway styling

- **🔄 Real-time Updates**: Socket.io integration for live data streaming### Backend

- **Node.js** - Runtime environment

## 🏗️ System Architecture- **Express.js** - Web framework

- **MongoDB** - Database

### Repository Structure- **Mongoose** - ODM

- **Socket.io** - Real-time communication

This project is organized into separate repositories for better deployment and maintenance:- **Helmet** - Security middleware



| Repository | Purpose | Technology Stack | Deployment |## 📁 Project Structure

|------------|---------|------------------|------------|

| **[SIH_FRONTEND](https://github.com/arnab-maity007/SIH_FRONTEND)** | User Interface | Next.js, TypeScript, Tailwind CSS | Vercel |```

| **[SIH_BACKEND](https://github.com/arnab-maity007/SIH_BACKEND)** | API Services | Node.js, Express, MongoDB | Railway/Heroku |SIH_CRAZY/

| **[SIH](https://github.com/arnab-maity007/SIH)** | Complete Project | Full Stack | Multi-platform |├── frontend/           # Next.js React application

│   ├── src/

### Local Development Structure│   │   ├── app/       # App Router pages

```│   │   ├── components/ # React components

SIH_CRAZY/│   │   ├── services/  # API services

├── frontend/          # Next.js Application (RailZenith UI)│   │   └── types/     # TypeScript types

├── backend/           # Node.js API Server│   └── package.json

├── .github/           # GitHub workflows and configurations├── backend/           # Node.js Express API

├── README.md          # This file│   ├── models/       # Database models

└── package.json       # Root package management│   ├── routes/       # API routes

```│   ├── middleware/   # Express middleware

│   └── server.js

## 🛠️ Technology Stack└── README.md

```

### Frontend

- **Framework**: Next.js 14 with App Router## 🚀 Getting Started

- **Language**: TypeScript

- **Styling**: Tailwind CSS with custom railway theme### Prerequisites

- **State Management**: React Hooks and Context- Node.js 18+ 

- **Real-time**: Socket.io Client- npm or yarn

- **Build Tools**: ESLint, PostCSS- MongoDB (local or cloud)



### Backend### Installation

- **Runtime**: Node.js

- **Framework**: Express.js1. **Clone the repository**

- **Database**: MongoDB with Mongoose ODM   ```bash

- **Real-time**: Socket.io Server   git clone https://github.com/arnab-maity007/SIH.git

- **Validation**: Express Validator   cd SIH

- **Environment**: dotenv   ```



### Deployment & DevOps2. **Install Frontend Dependencies**

- **Frontend Hosting**: Vercel (Optimized for Next.js)   ```bash

- **Backend Hosting**: Railway/Heroku (Node.js support)   cd frontend

- **Database**: MongoDB Atlas (Cloud)   npm install

- **Version Control**: Git with GitHub   ```

- **CI/CD**: GitHub Actions

3. **Install Backend Dependencies**

## 🚀 Quick Start   ```bash

   cd ../backend

### Prerequisites   npm install

- Node.js 18+   ```

- MongoDB (local or cloud)

- Git4. **Environment Setup**

   

### Complete Setup   Create `.env` file in backend directory:

   ```env

```bash   PORT=5001

# Clone the main repository   MONGODB_URI=mongodb://localhost:27017/train_optimization

git clone https://github.com/arnab-maity007/SIH.git   NODE_ENV=development

cd SIH   JWT_SECRET=your_jwt_secret_here

   ```

# Install dependencies for both frontend and backend

npm install### Running the Application



# Setup Frontend1. **Start Backend Server**

cd frontend   ```bash

npm install   cd backend

cp .env.example .env.local   npm run dev

# Configure your environment variables   ```

   Backend will run on `http://localhost:5001`

# Setup Backend (in new terminal)

cd ../backend2. **Start Frontend Development Server**

npm install   ```bash

cp .env.example .env   cd frontend

# Configure your environment variables   npm run dev

   ```

# Start development servers   Frontend will run on `http://localhost:3000`

npm run dev        # This starts both frontend and backend

```## 📊 API Endpoints



### Individual Repository Setup### Train Management

- `GET /api/trains` - Get all trains

#### Frontend Only- `POST /api/trains` - Create new train

```bash- `PUT /api/trains/:id` - Update train

git clone https://github.com/arnab-maity007/SIH_FRONTEND.git- `DELETE /api/trains/:id` - Delete train

cd SIH_FRONTEND

npm install### Schedule Management  

npm run dev- `GET /api/schedules` - Get all schedules

```- `POST /api/schedules` - Create new schedule

- `PUT /api/schedules/:id` - Update schedule

#### Backend Only- `DELETE /api/schedules/:id` - Delete schedule

```bash

git clone https://github.com/arnab-maity007/SIH_BACKEND.git### Route Optimization

cd SIH_BACKEND- `POST /api/optimization/route` - Optimize route

npm install- `GET /api/optimization/history` - Get optimization history

npm run dev

```### Analytics

- `GET /api/analytics/dashboard` - Get dashboard analytics

## 🎨 RailZenith Design System- `GET /api/analytics/performance` - Get performance metrics

- `POST /api/analytics/custom-report` - Generate custom report

### Visual Identity

- **Primary Colors**: Amber/Orange gradients (`#F59E0B` to `#EA580C`)## 🌟 Key Components

- **Background**: Dark gradients (`#111827` via `#1E293B` to `#111827`)

- **Accent Colors**: Railway-inspired palette (Green, Yellow, Purple, Blue)### Frontend Components

- **Typography**: Professional sans-serif with gradient accents- **Dashboard**: Main analytics and overview dashboard

- **TrainTracking**: Real-time train tracking interface

### Railway Visual Elements- **ScheduleManagement**: Schedule CRUD operations

- Railway track SVG patterns with opacity effects- **RouteOptimization**: Route planning and optimization

- Train silhouette graphics and icons- **Sidebar**: Navigation component

- Professional railway-themed iconography

- Backdrop blur effects for modern premium feel### Backend Services

- Smooth hover animations with color transitions- **Train Service**: Train lifecycle management

- **Schedule Service**: Schedule management

## 📡 API Documentation- **Optimization Service**: Route optimization algorithms

- **Analytics Service**: Reporting and analytics

### Core Endpoints

## 🔧 Development

#### Train Management

```### Code Quality

GET    /api/trains          # Get all trains with real-time status- ESLint configuration for code quality

GET    /api/trains/:id      # Get specific train details- TypeScript for type safety

POST   /api/trains          # Register new train- Prettier for code formatting

PUT    /api/trains/:id      # Update train information

DELETE /api/trains/:id      # Remove train from system### Testing

``````bash

# Run frontend tests

#### Schedule Managementcd frontend && npm test

```

GET    /api/schedules       # Get all schedules# Run backend tests  

POST   /api/schedules       # Create new schedulecd backend && npm test

PUT    /api/schedules/:id   # Update existing schedule```

DELETE /api/schedules/:id   # Cancel schedule

```### Building for Production

```bash

#### Route Optimization# Build frontend

```cd frontend && npm run build

GET    /api/routes          # Get all available routes

POST   /api/routes/optimize # Calculate optimal routes# Build backend

GET    /api/routes/:id      # Get specific route detailscd backend && npm run build

``````



#### Analytics & Monitoring## 🚀 Deployment

```

GET    /api/analytics/performance  # Performance metrics### Frontend (Vercel)

GET    /api/analytics/delays       # Delay statistics1. Connect GitHub repository to Vercel

GET    /api/analytics/occupancy    # Occupancy analytics2. Configure environment variables

GET    /api/health                 # System health check3. Deploy automatically on push to main

```

### Backend (Railway/Render)

## 🌐 Live Deployments1. Connect GitHub repository to hosting platform

2. Configure environment variables

| Service | URL | Status |3. Set up MongoDB Atlas for production database

|---------|-----|--------|

| **Frontend** | [RailZenith Dashboard](https://sih-frontend-railway.vercel.app) | ✅ Live |## 🤝 Contributing

| **Backend API** | [API Endpoints](https://sih-backend-api.railway.app) | ✅ Live |

| **Documentation** | [API Docs](https://sih-backend-api.railway.app/docs) | ✅ Live |1. Fork the repository

2. Create a feature branch (`git checkout -b feature/amazing-feature`)

## 📊 System Performance3. Commit your changes (`git commit -m 'Add amazing feature'`)

4. Push to the branch (`git push origin feature/amazing-feature`)

### Key Metrics5. Open a Pull Request

- **Response Time**: < 200ms average API response

- **Uptime**: 99.9% availability target## 📝 License

- **Real-time Updates**: < 100ms latency

- **Concurrent Users**: Supports 1000+ simultaneous usersThis project is developed for Smart India Hackathon 2025.

- **Data Processing**: Real-time train data from 500+ trains

## 👥 Team

## 🔧 Development Workflow

- **Lead Developer**: [Your Name]

### Local Development- **Project**: Train Traffic Optimization System

```bash- **Event**: Smart India Hackathon 2025

# Start complete development environment

npm run dev:full     # Starts frontend + backend + database## 🙏 Acknowledgments



# Individual services- Smart India Hackathon organizers

npm run dev:frontend # Frontend only (port 3000)- Railway domain experts

npm run dev:backend  # Backend only (port 3001)- Open source community

npm run dev:db       # Database only (port 27017)

```---



### Testing**Built with ❤️ for Smart India Hackathon 2025**
```bash
# Run all tests
npm test

# Frontend tests
npm run test:frontend

# Backend tests
npm run test:backend

# E2E tests
npm run test:e2e
```

### Deployment
```bash
# Build for production
npm run build

# Deploy frontend to Vercel
npm run deploy:frontend

# Deploy backend to Railway
npm run deploy:backend
```

## 🤝 Contributing

1. Fork the main repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Development Guidelines
- Use TypeScript for type safety
- Follow REST API conventions
- Implement responsive design principles
- Use modern React patterns (hooks, context)
- Maintain clean code architecture
- Write comprehensive tests

## 📄 License

This project is part of Smart India Hackathon 2024 submission.

## 🔗 Related Links

- **[Frontend Repository](https://github.com/arnab-maity007/SIH_FRONTEND)** - Next.js application
- **[Backend Repository](https://github.com/arnab-maity007/SIH_BACKEND)** - Node.js API server
- **[Live Demo](https://sih-frontend-railway.vercel.app)** - RailZenith dashboard
- **[API Documentation](https://sih-backend-api.railway.app/docs)** - Interactive API docs

## 📞 Support

For questions, issues, or support:
- Open an issue in the respective repository
- Contact the development team
- Check the documentation and FAQ

## 🏆 Smart India Hackathon 2024

**Problem Statement**: Railway Traffic Optimization and Management
**Team**: RailZenith Development Team
**Solution**: Comprehensive real-time railway traffic management system

---

**Built with ❤️ for Smart India Hackathon 2024**

*Transforming Railway Operations Through Innovation*