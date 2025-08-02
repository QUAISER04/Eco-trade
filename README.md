# 🌱 EcoTrade - Sustainable E-Commerce Platform

A modern, eco-conscious e-commerce platform that promotes sustainable shopping by tracking carbon footprints and rewarding environmentally friendly choices.

## 🚀 Live Demo

[View Live Demo](https://github.com/QUAISER04/Eco-trade.git)

## 📋 Table of Contents

- [About](#about)
- [Features](#features)
- [Tech Stack](#tech-stack)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## 🌍 About

EcoTrade is a sustainable e-commerce platform that revolutionizes online shopping by integrating environmental consciousness into every purchase. Our platform helps users make informed decisions by providing detailed carbon footprint information for each product and rewarding sustainable choices through a points-based system.

### Key Benefits

- **Carbon Footprint Tracking**: Every product displays its environmental impact
- **Sustainability Scoring**: Products are rated based on materials and manufacturing processes
- **Rewards System**: Earn points for making eco-friendly purchases
- **Leaderboard**: Compete with other users to reduce your carbon footprint
- **Educational Content**: Learn about sustainability through tips and insights

## ✨ Features

### 🛍️ Shopping Experience
- **Product Catalog**: Browse sustainable products across multiple categories
- **Detailed Product Pages**: View comprehensive product information including carbon footprint
- **Smart Filtering**: Filter products by sustainability score, category, and price
- **Shopping Cart**: Add items and manage quantities with real-time carbon impact updates

### 👤 User Management
- **Authentication**: Secure login and signup with Firebase
- **User Profiles**: Track your sustainability journey and achievements
- **Order History**: View past purchases and their environmental impact
- **Points System**: Earn and track sustainability points

### 🌱 Sustainability Features
- **Carbon Footprint Calculator**: Real-time calculation of purchase environmental impact
- **Sustainability Badges**: Visual indicators for eco-friendly products
- **Impact Statistics**: Track your overall environmental contribution
- **Leaderboard**: Compare your sustainability efforts with other users

### 📊 Analytics & Insights
- **Personal Dashboard**: View your sustainability metrics and progress
- **Carbon Over Time**: Visualize your carbon footprint trends
- **Achievement Tracking**: Monitor your sustainability milestones
- **Community Impact**: See collective environmental contributions

## 🛠️ Tech Stack

### Frontend
- **React 18** - Modern UI library with hooks
- **TypeScript** - Type-safe development
- **Vite** - Fast build tool and development server
- **Tailwind CSS** - Utility-first CSS framework
- **React Router** - Client-side routing

### State Management
- **Zustand** - Lightweight state management
- **Firebase** - Authentication and real-time database

### UI Components
- **Lucide React** - Beautiful icon library
- **Recharts** - Data visualization components

### Development Tools
- **ESLint** - Code linting and formatting
- **PostCSS** - CSS processing
- **Autoprefixer** - CSS vendor prefixing

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn package manager
- Firebase project setup

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/QUAISER04/Eco-trade.git
   cd EcoTrade
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Environment Configuration**
   Create a `.env` file in the root directory and add your Firebase configuration:
   ```env
   VITE_FIREBASE_API_KEY=your_api_key
   VITE_FIREBASE_AUTH_DOMAIN=your_auth_domain
   VITE_FIREBASE_PROJECT_ID=your_project_id
   VITE_FIREBASE_STORAGE_BUCKET=your_storage_bucket
   VITE_FIREBASE_MESSAGING_SENDER_ID=your_sender_id
   VITE_FIREBASE_APP_ID=your_app_id
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open your browser**
   Navigate to `http://localhost:5173`

## 🚀 Usage

### Development Commands

```bash
# Start development server
npm run dev

# Build for production
npm run build

# Preview production build
npm run preview

# Run linting
npm run lint
```

### Key Features Usage

1. **Browse Products**: Navigate to the products page to explore sustainable items
2. **Track Carbon Impact**: Each product displays its carbon footprint
3. **Earn Points**: Make eco-friendly purchases to accumulate sustainability points
4. **View Leaderboard**: Check your ranking among other environmentally conscious users
5. **Manage Profile**: Update your information and view your sustainability stats

## 📁 Project Structure

```
EcoTrade/
├── src/
│   ├── components/
│   │   ├── common/           # Reusable components
│   │   ├── home/            # Home page components
│   │   ├── layout/          # Layout components
│   │   └── product/         # Product-related components
│   ├── pages/               # Page components
│   ├── services/            # API and external services
│   ├── store/               # State management
│   ├── types/               # TypeScript type definitions
│   └── uploads/             # Static assets
├── public/                  # Public assets
├── package.json
├── vite.config.ts
├── tailwind.config.js
└── README.md
```

## 🔧 API Reference

### Authentication
- `auth.checkAuth()` - Check current authentication status
- `auth.signIn(email, password)` - User login
- `auth.signUp(email, password, displayName)` - User registration
- `auth.signOut()` - User logout

### Products
- `getProducts()` - Fetch all products
- `getProductById(id)` - Get specific product details
- `getFeaturedProducts()` - Get featured products

### User Management
- `getUserProfile(userId)` - Get user profile data
- `updateUserProfile(userId, data)` - Update user information
- `getUserStats(userId)` - Get user sustainability statistics

## 🤝 Contributing

We welcome contributions to make EcoTrade even better! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/amazing-feature`)
3. **Commit your changes** (`git commit -m 'Add amazing feature'`)
4. **Push to the branch** (`git push origin feature/amazing-feature`)
5. **Open a Pull Request**

### Development Guidelines

- Follow TypeScript best practices
- Use meaningful commit messages
- Ensure all tests pass before submitting
- Update documentation for new features
- Follow the existing code style

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- **Firebase** for authentication and database services
- **Tailwind CSS** for the beautiful UI framework
- **React Community** for the amazing ecosystem
- **Sustainability Advocates** for inspiration and guidance

## 📞 Contact

- **GitHub**: [@QUAISER04](https://github.com/QUAISER04)
- **Project Link**: [https://github.com/QUAISER04/Eco-trade](https://github.com/QUAISER04/Eco-trade)

---

**Made with ❤️ for a sustainable future**
