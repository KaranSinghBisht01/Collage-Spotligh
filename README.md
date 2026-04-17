# EduEvents - College Event Management System 🎓

A comprehensive college event management platform built with React, TypeScript, and Tailwind CSS. This system provides role-based dashboards for administrators, organizers, and students to efficiently manage educational events.

## 🌟 Features

### For Students
- **Event Discovery**: Browse and register for approved events
- **Registration Management**: Easy registration and unregistration
- **Attendance Tracking**: View attended events
- **Feedback System**: Submit ratings and comments after events
- **Digital Certificates**: Download certificates for completed events

### For Organizers
- **Event Creation**: Create detailed event proposals
- **Event Management**: Track event status and registrations
- **Attendance Marking**: Mark student attendance during events
- **Registration Overview**: View all registered participants

### For Administrators
- **Event Approval**: Review and approve/reject event proposals
- **User Management**: Overview of all platform users
- **System Analytics**: Track platform usage and statistics
- **Role Management**: Manage user roles and permissions

## 🎨 Design System

The application features a modern, education-focused design with:
- **Beautiful gradients** and smooth animations
- **Role-based color coding** (Admin: Red, Organizer: Orange, Student: Green)
- **Responsive design** that works on all devices
- **Accessible components** built with Radix UI primitives
- **Semantic design tokens** for consistent theming

## 🚀 Getting Started

### Prerequisites
- Node.js 18+ 
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <your-git-url>
cd <your-project-name>
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and navigate to `http://localhost:8080`

## 🔐 Demo Credentials

You can test the application with these demo accounts:

### Admin Account
- **Email**: admin@college.edu
- **Password**: demo123
- **Role**: Admin

### Organizer Account
- **Email**: organizer@college.edu  
- **Password**: demo123
- **Role**: Organizer

### Student Account
- **Email**: student1@college.edu
- **Password**: demo123
- **Role**: Student

## 📱 User Interface

### Landing Page
- Hero section with platform overview
- Feature highlights
- Call-to-action buttons

### Authentication
- Role-based login system
- Demo credential buttons for easy testing
- Responsive design with beautiful gradients

### Dashboard Views
Each role has a customized dashboard:

#### Admin Dashboard
- Event approval/rejection interface
- User management panel
- System statistics overview
- Real-time event status tracking

#### Organizer Dashboard  
- Event creation form
- Event management interface
- Attendance marking system
- Registration analytics

#### Student Dashboard
- Available events catalog
- Registration management
- Feedback submission forms
- Certificate download center

## 🛠️ Technology Stack

- **Frontend Framework**: React 18 with TypeScript
- **Styling**: Tailwind CSS with custom design system
- **UI Components**: Shadcn/ui (Radix UI primitives)
- **Icons**: Lucide React
- **Routing**: React Router DOM
- **State Management**: React Context API
- **Build Tool**: Vite
- **Form Handling**: React Hook Form with Zod validation

## 📁 Project Structure

```
src/
├── components/          # Reusable UI components
│   ├── ui/             # Shadcn/ui components
│   ├── Auth/           # Authentication components
│   ├── Dashboard/      # Role-specific dashboards
│   └── Layout/         # Layout components
├── context/            # React Context providers
├── data/              # Mock data and API utilities
├── hooks/             # Custom React hooks
├── pages/             # Page components
├── types/             # TypeScript type definitions
└── lib/               # Utility functions
```

## 🎯 Current Status

This is the **frontend-only** version of the application. All data is currently mocked for demonstration purposes.

### ✅ Completed Features
- Role-based authentication system
- Three distinct dashboard interfaces
- Event creation and management
- Registration and attendance systems
- Feedback and rating system
- Responsive design with modern UI
- Mock data integration

### 🔄 Planned Features (Backend Integration)
- Flask backend with Python
- MySQL database integration
- Real-time notifications
- PDF certificate generation
- Email notifications
- File upload capabilities
- Advanced analytics and reporting
- CSV/PDF export functionality

## 🎨 Design Philosophy

The application follows a **semantic design system** approach:
- All colors are defined as HSL values in CSS custom properties
- Components use semantic tokens rather than hardcoded colors
- Consistent spacing and typography throughout
- Smooth transitions and elegant animations
- Role-based visual indicators for better UX

## 🔧 Customization

The design system can be easily customized by modifying:
- `src/index.css` - CSS custom properties and design tokens
- `tailwind.config.ts` - Tailwind theme configuration
- Component variants in `src/components/ui/`

## 📖 Usage Guide

1. **Start at the Landing Page**: Overview of platform features
2. **Login with Demo Credentials**: Test different user roles
3. **Explore Role-Specific Features**: Each role has unique capabilities
4. **Create and Manage Events**: Test the full event lifecycle
5. **Experience the User Journey**: From event creation to certificate generation

## 🤝 Contributing

This project is designed to be extended with backend functionality. The current frontend provides a solid foundation for:
- API integration points
- Component structure for dynamic data
- User interface patterns for all major features

## 📄 License

This project is created for educational purposes and portfolio demonstration.

---

**EduEvents** - Transforming college event management, one event at a time! 🎓✨
