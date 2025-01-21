# Plant Care Reminder App 🌱

A full-stack web application to help plant enthusiasts track and manage their plant care routines.

## Features

- 🪴 Track multiple plants and their care requirements
- 💧 Automated watering schedule reminders
- ☀️ Light requirement tracking
- 🐛 Pest management reminders
- 📱 Responsive design for desktop and mobile

## Tech Stack

- Frontend: React.js with Tailwind CSS and shadcn/ui
- Backend: Node.js/Express
- Database: MongoDB
- Authentication: JWT

## Getting Started

### Prerequisites

- Node.js (v14 or higher)
- MongoDB Atlas account
- npm or yarn

### Installation

1. Clone the repository
```bash
git clone https://github.com/yourusername/plant-care-app.git
cd plant-care-app
```

2. Install dependencies
```bash
# Install backend dependencies
cd backend
npm install

# Install frontend dependencies
cd ../frontend
npm install
```

3. Set up environment variables

Create a `.env` file in the backend directory:
```
MONGODB_URI=your_mongodb_connection_string
PORT=5000
```

Create a `.env` file in the frontend directory:
```
REACT_APP_API_URL=http://localhost:5000
```

4. Start the application
```bash
# Start backend (from backend directory)
npm start

# Start frontend (from frontend directory)
npm start
```

The app will be available at `http://localhost:3000`

## Deployment

This app can be deployed for free using:
- Backend: Render.com
- Frontend: Vercel
- Database: MongoDB Atlas

Detailed deployment instructions can be found in the [Deployment Guide](./DEPLOYMENT.md)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details

## Acknowledgments

- Plant care timing recommendations based on general horticultural guidelines
- UI components from shadcn/ui
- Icons from Lucide React
