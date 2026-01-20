
HRM Employee Frontend
A React-based Human Resource Management system frontend built with Vite for fast development and optimized builds.

🚀 Quick Start
Prerequisites
Node.js (v16 or higher)
npm or yarn
Installation
# Clone the repository
git clone <repository-url>
cd frontend_hrm_employee

# Install dependencies
npm install

# Start development server
npm run dev
📁 Project Structure
frontend_hrm_employee/
├── src/
│   ├── components/     # Reusable UI components
│   ├── pages/         # Page components
│   ├── config/        # Configuration files
│   ├── utils/         # Utility functions
│   ├── hooks/         # Custom React hooks
│   └── assets/        # Static assets
├── public/            # Public assets
└── package.json
🛠️ Available Scripts
npm run dev - Start development server
npm run build - Build for production
npm run preview - Preview production build
npm run lint - Run ESLint
⚙️ Configuration
API Configuration
The application uses axios for API calls. Configuration is in src/config/axiosConfig.js:

const baseURL = "https://superladmin.seclobconnect.com";
Environment Variables
Create a .env file in the root directory:

VITE_BACKEND_URL=your_api_url_here
🔧 Tech Stack
React - UI library
Vite - Build tool and dev server
Axios - HTTP client
ESLint - Code linting
🌐 API Integration
The app connects to the HRM backend API with:

JWT token authentication
Automatic token attachment via axios interceptors
Base URL configuration for different environments
📦 Build & Deploy
# Build for production
npm run build

# The built files will be in the `dist` directory
🤝 Contributing
Fork the repository
Create a feature branch
Make your changes
Run tests and linting
Submit a pull request
📄 License
This project is licensed under the MIT License.
