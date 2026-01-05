# Real-Time Chat Application

A **real-time chat platform** enabling instant messaging between users, built for performance and modern UI.

---

## Project Structure

### Backend
- `controllers/`: Modular controllers handling chat and user operations  
- `middleware/`: Authentication middleware and security logic  
- `models/`: MongoDB schemas (User, Message, Chat)  
- `routes/`: API endpoints  
- `socket/`: Real-time messaging logic with Socket.io  
- `index.js`: Server entry point  
- `package.json`: Backend dependencies  

### Frontend
- `src/`: React components & pages  
- `public/`: Static assets  
- `package.json`: Frontend dependencies  
- `tailwind.config.js`: Tailwind CSS configuration  

---

## Key Features
- Real-time messaging using **Socket.io** for **low-latency, bi-directional communication**  
- Persistent state with **Redux Toolkit + Redux Persist** to maintain sessions and chat history  
- Modern, responsive UI with **Tailwind CSS & DaisyUI**, including:  
  - Online/offline status indicators  
  - Toast notifications  
  - Background blur effects  
- Secured API endpoints with **custom authentication middleware**  
- Optimized backend with modular controllers  

---

## Tech Stack
- Frontend: React.js, Tailwind CSS, DaisyUI, Redux Toolkit, Redux Persist  
- Backend: Node.js, Express.js, MongoDB, Mongoose  
- Real-time: Socket.io  
- Authentication: JWT, bcrypt  

---

## Setup Instructions
```bash
# Clone the repository
git clone https://github.com/ujjawalkumar19/Chat-app.git
cd Chat-app

# Backend setup
cd backend
npm install
npm start

# Frontend setup
cd ../frontend
npm install
npm start
