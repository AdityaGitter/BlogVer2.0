# BlogVer2.0 - Your Personal Blogging Platform
BlogVer2.0 is a full-stack web application designed for individuals who want to share their thoughts, experiences, and creativity through blogging. The platform allows users to create, edit, and delete posts, manage comments, and interact with other users. It provides a user-friendly interface for readers and writers alike.

## Table of Contents
1. [Features](#features)
2. [Technology Stack](#technology-stack)
3. [Setup and Installation](#setup-and-installation)
4. [Usage](#usage)
5. [Project Structure](#project-structure)
6. [Contributing](#contributing)

## Features
User Authentication: Users can register, log in, and manage their profiles.
Post Management: Create, edit, and delete blog posts easily.
Comment System: Readers can leave comments on posts, fostering interaction.
Responsive Design: The platform is designed to work seamlessly on both desktop and mobile devices.
User Profiles: Each user has a profile page showcasing their posts and activities.

## Technology Stack
Frontend: React.js
Backend: Node.js, Express.js
Database: MongoDB
Styling: Tailwind CSS
APIs: RESTful APIs for post and comment management

## Setup and Installation
Clone the repository:

bash
```
git clone https://github.com/your-username/BlogVer2.0.git
cd BlogVer2.0
```
Install dependencies for both frontend and backend:
bash
```
## Backend setup
cd backend
npm install

## Frontend setup
cd ../frontend
npm install
```
Environment Variables:

Create a .env file in the root of the backend folder and add:
plaintext
```
PORT=4001
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key

FRONTEND_URL=http://localhost:5173

CLOUD_NAME=your_cloudinary_cloud_name
CLOUD_API_KEY=your_cloudinary_api_key
CLOUD_SECRET_KEY=your_cloudinary_api_secret

```

bash
```
# Backend
cd backend
npm start

# Frontend
cd ../frontend
npm run dev
```
Access the application at `http://localhost:5173/`.

## Usage
Sign Up/Login: Register or log in to start blogging.
Create Posts: Write and publish your blogs with ease.
Comment on Posts: Engage with other users by leaving comments.
Manage Your Profile: View and edit your profile information and posts.

## Project Structure
```
BLOGVER2.0/
├── backend/
│ ├── controller/
│ ├── jwt/
│ ├── middleware/
│ ├── models/
│ ├── routes/
│ ├── .env
│ ├── .env_example
│ ├── .gitignore
│ ├── index.js
│ ├── package.json
│ └── package-lock.json
│
├── frontend/
│ ├── public/
│ ├── src/
│ │ ├── components/
│ │ ├── pages/
│ │ ├── context/
│ │ └── main.jsx
│ ├── .gitignore
│ ├── eslint.config.js
│ ├── index.html
│ ├── postcss.config.js
│ ├── tailwind.config.js
│ ├── vite.config.js
│ ├── package.json
│ └── package-lock.json
│
└── README.md
```
## Contributing
I welcome contributions from the community! Please feel free to submit issues and pull requests. For major changes, please discuss them in an issue first to ensure alignment with the project goals.

