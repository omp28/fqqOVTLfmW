## setup

cd backend
npm install

## env

PORT=5000
MONGODB_URI=mongodb://localhost:27017/auth-app
JWT_SECRET=your_jwt_secret_key

## start

npm start

## frontend

cd ../frontend
npm install

## env.local

NEXT_PUBLIC_API_URL=http://localhost:5000/api

## start

npm run dev
