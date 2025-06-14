# Chat App

A fullstack real-time chat application built with React, Node.js, Express, MongoDB, and Socket.IO.

See the web app - https://chat-app-w44-c3sh6zdyp-sathtik-boses-projects.vercel.app/

## Features

- Real-time messaging with Socket.IO
- User authentication (sign up, login, JWT)
- Profile management (update name, bio, profile picture)
- Online users indicator
- Image sharing in chat
- Responsive design with Tailwind CSS

## Tech Stack

- **Frontend:** React, Vite, Tailwind CSS
- **Backend:** Node.js, Express, MongoDB (Mongoose), Socket.IO
- **Authentication:** JWT
- **Image Uploads:** Cloudinary

## Folder Structure

```
chat-app/
├── client/      # React frontend
│   ├── src/
│   ├── public/
│   └── ...
├── server/      # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── ...
└── ...
```

## Getting Started

### Prerequisites

- Node.js (v18+)
- MongoDB database
- Cloudinary account (for image uploads)

### Environment Variables

#### Server (`server/.env`)

```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
PORT=5000
```

#### Client (`client/.env`)

```
VITE_BACKEND_URL=http://localhost:5000
```

### Installation

1. **Clone the repository**

   ```sh
   git clone https://github.com/yourusername/chat-app.git
   cd chat-app
   ```

2. **Install dependencies**

   ```sh
   cd server
   npm install

   cd ../client
   npm install
   ```

3. **Run the development servers**

   - **Backend:**
     ```sh
     cd server
     npm run server
     ```
   - **Frontend:**
     ```sh
     cd client
     npm run dev
     ```

Frontend runs at `http://localhost:5173`, backend at `http://localhost:5000`.

## Deployment

You can deploy the frontend and backend separately (e.g., Vercel for frontend, Render or Railway for backend).

## License

MIT

---

**Developed by [Sathtik]**
