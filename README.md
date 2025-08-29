# TalkVerse# TalkVerse

TalkVerse is a full-stack web application for secure video meetings, user authentication, and meeting history. Built with React for the frontend and Node.js/Express with MongoDB for the backend, it enables real-time video calls, user registration/login, and meeting management.

## Features

- **Real-time Video Calls:** Host and join video meetings with multiple participants.
- **User Authentication:** Register and login securely.
- **Meeting History:** View and manage your past meetings.
- **Chat:** In-call messaging for participants.
- **Responsive UI:** Modern design using Material-UI.

## Tech Stack

- **Frontend:** React, Material-UI, Socket.io-client
- **Backend:** Node.js, Express, MongoDB, Socket.io
- **Authentication:** Token-based (custom implementation)
- **Deployment:** Easily deployable to cloud platforms

## Getting Started

### Prerequisites

- Node.js (v16+)
- npm or yarn
- MongoDB instance (local or cloud)

### Installation

1. **Clone the repository:**
   ```sh
   git clone https://github.com/yourusername/talkverse.git
   cd talkverse
   ```

2. **Install dependencies:**
   - Frontend:
     ```sh
     cd frontend
     npm install
     ```
   - Backend:
     ```sh
     cd ../backend
     npm install
     ```

3. **Configure environment:**
   - Update MongoDB connection string in [`backend/src/app.js`](backend/src/app.js) if needed.

4. **Run the application:**
   - Start backend server:
     ```sh
     npm run dev
     ```
   - Start frontend:
     ```sh
     cd ../frontend
     npm start
     ```

5. **Access the app:**
   - Open [http://localhost:3000](http://localhost:3000) in your browser.

## Folder Structure

```
├── backend
│   ├── src
│   │   ├── controllers
│   │   ├── models
│   │   ├── routes
│   │   └── app.js
│   └── package.json
├── frontend
│   ├── public
│   ├── src
│   │   ├── pages
│   │   ├── contexts
│   │   ├── styles
│   │   └── utils
│   └── package.json
└── README.md
```

## Contributing

Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License

This project is licensed under the MIT License.

---
