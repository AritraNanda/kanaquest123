# KanaQuest

A comprehensive Japanese learning platform for mastering Hiragana, Katakana, and Kanji characters through interactive lessons and quizzes.

## 🚀 Features

- **Interactive Learning**: Master Japanese characters with engaging lessons
- **Progress Tracking**: Monitor your learning journey with experience points
- **Leaderboards**: Compete with other learners
- **Dark/Light Mode**: Customizable UI experience
- **Responsive Design**: Works on desktop and mobile devices

## 🛠️ Tech Stack

- **Frontend**: React, Vite, Tailwind CSS, Redux Toolkit
- **Backend**: Node.js, Express, Apollo GraphQL Server
- **Database**: MongoDB with Mongoose
- **Authentication**: JWT tokens

## 📦 Installation

### Prerequisites
- Node.js (v16 or higher)
- MongoDB (local or cloud instance)

### Setup

1. **Clone the repository**
   ```bash
   git clone <your-repo-url>
   cd KanaQuest
   ```

2. **Install dependencies**
   ```bash
   npm run install
   ```

3. **Environment Setup**
   ```bash
   cd server
   cp env.example .env
   ```
   
   Edit `.env` file with your configuration:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   JWT_SECRET=your_jwt_secret
   PORT=3001
   NODE_ENV=development
   ```

4. **Start Development Server**
   ```bash
   npm run dev
   ```

## 🚀 Production Deployment

### Build for Production
```bash
npm run build
```

### Start Production Server
```bash
npm run start:prod
```

## 📁 Project Structure

```
KanaQuest/
├── client/                 # React frontend
│   ├── src/
│   │   ├── components/     # React components
│   │   ├── pages/         # Page components
│   │   ├── data/          # Character and lesson data
│   │   └── utils/         # Utility functions
│   └── public/            # Static assets
├── server/                # Node.js backend
│   ├── config/           # Database configuration
│   ├── models/           # MongoDB models
│   ├── schemas/          # GraphQL schemas
│   └── utils/            # Utility functions
└── package.json          # Root package configuration
```

## 👥 Contributors

- Aritra
- Paulami  
- Kritika
- Simran

## 📄 License

ISC License