# Job Portal App

A modern and feature-rich job portal application that connects job seekers with employers, facilitating seamless recruitment processes.

## 🌟 Key Features

- 🔐 Secure user authentication and role-based authorization
- 📝 Comprehensive job posting and management system
- 🔍 Advanced job search with multiple filters
- 📄 Resume upload and management with cloud storage
- 💼 Employer profile and company management
- 📱 Responsive design for all devices
- 🔔 Real-time notifications for job applications
- 📊 Analytics dashboard for employers
- 🤝 Application tracking system
- 📈 Job market insights and trends

## 🛠️ Technical Stack

### Backend
- **Node.js** - Runtime environment
- **Express.js** - Web application framework
- **MongoDB** - NoSQL database
- **JWT** - Secure authentication
- **Cloudinary** - Cloud-based media management
- **Mongoose** - MongoDB object modeling
- **Bcrypt** - Password hashing
- **Multer** - File upload handling

### Frontend
- **React.js** - UI library
- **Redux Toolkit** - State management
- **Tailwind CSS** - Utility-first CSS framework
- **Vite** - Build tool and development server
- **React Router** - Client-side routing
- **Radix UI** - Accessible UI components
- **Axios** - HTTP client
- **Framer Motion** - Animation library

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- MongoDB
- npm or yarn
- Git

### Backend Setup
```bash
# Clone the repository
git clone https://github.com/yourusername/job-portal-app.git

# Navigate to backend directory
cd backend

# Install dependencies
npm install

# Create .env file and add environment variables
cp .env.example .env

# Start development server
npm run dev
```

### Frontend Setup
```bash
# Navigate to frontend directory
cd frontend

# Install dependencies
npm install

# Start development server
npm run dev
```

## ⚙️ Environment Variables

Create a `.env` file in the backend directory with the following variables:

```env
# Server Configuration
PORT=5000
NODE_ENV=development

# Database
MONGODB_URI=your_mongodb_uri

# Authentication
JWT_SECRET=your_jwt_secret
JWT_EXPIRE=24h

# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

## 📁 Project Structure

```
job-portal-app/
├── backend/
│   ├── controllers/    # Request handlers
│   ├── models/        # Database models
│   ├── routes/        # API routes
│   ├── middlewares/   # Custom middlewares
│   ├── utils/         # Helper functions
│   └── index.js       # Entry point
│
└── frontend/
    ├── src/
    │   ├── components/    # Reusable components
    │   ├── pages/        # Page components
    │   ├── redux/        # State management
    │   ├── utils/        # Helper functions
    │   └── App.js        # Root component
    └── public/           # Static assets
```

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Code Style
- Follow ESLint configuration
- Use meaningful commit messages
- Write clear documentation
- Add tests for new features

## 📝 License

This project is licensed under the ISC License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- Your Name - Initial work

## 🙏 Acknowledgments

- Thanks to all contributors
- Inspired by modern job portal platforms
- Built with best practices in mind 