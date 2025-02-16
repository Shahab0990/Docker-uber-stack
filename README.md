🚖 Uber Clone - Dockerized Full Stack Application

This is a full-stack Uber Clone application that includes both the backend (Node.js + Express + MongoDB) and the frontend (React.js + Vite + Google Maps API). This project has been Dockerized to allow easy deployment using Docker Compose.

📌 What's Included?

Backend: Node.js, Express.js, MongoDB, JWT Authentication, Socket.io for real-time ride updates.

Frontend: React.js, Vite, Google Maps API, Socket.io client.

Deployment: Docker & Docker Compose for containerized development.

MongoDB: Runs inside a Docker container (No need for manual installation!)

🆕 What's New?

✅ Added Docker support with Dockerfile for both backend & frontend.
✅ Added docker-compose.yml to run the full-stack app easily.
✅ Environment Variables (.env file) NOT included – users need to create their own.
✅ Credit given to the original repository & author.

🔗 Original Repository

This project is based on  https://github.com/Ankur77720/uber-video/tree/main
You can find the original YouTube tutorial by Sheryians Coding School here:👉 https://www.youtube.com/watch?v=4qyBjxPlEZo&t=2474s&ab_channel=SheryiansCodingSchool
🔥 How to Download & Run This Project

1️⃣ Clone the Repository

Open your terminal and run:

 git clone https://github.com/Shahab0990/Docker-uber-stack.git
 cd Docker-uber-stack

2️⃣ Create Your .env Files

Since .env files are not included, you need to create them manually.

Backend .env File (backend/.env)

PORT=5000
MONGO_URI=mongodb://mongo:27017/uber_clone
JWT_SECRET=your_secret_key
VITE_BASE_URL=http://localhost:5000
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key

Frontend .env File (frontend/.env)

VITE_BASE_URL=http://localhost:5000
VITE_GOOGLE_MAPS_API_KEY=your_google_maps_api_key

🚨 Replace your_secret_key and your_google_maps_api_key with actual values.

🐳 Running the Project with Docker Compose

Once the .env files are created, simply run:

docker-compose up --build

✅ This will start MongoDB, Backend, and Frontend together.

🛑 To Stop the Containers

docker-compose down

🔥 Running Without Docker (Manual Setup)

1️⃣ Backend Setup

cd backend
npm install
npm start

✅ Runs on http://localhost:5000

2️⃣ Frontend Setup

cd frontend
npm install
npm run dev

✅ Runs on http://localhost:5173

Feel free to contribute & improve this project! 🚀
