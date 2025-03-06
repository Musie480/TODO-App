# To-Do App

A full-stack To-Do application built using **React, Vite, Express, and MySQL**. The app allows users to create, update, delete, and filter tasks efficiently. It also includes **light and dark modes**, along with **search and filter functionality** for better task management.

## Features
- ✅ **Add, Edit, and Delete Tasks**
- 🌗 **Light & Dark Mode Support**
- 🔍 **Search & Filter Tasks**
- 🗃 **Persistent Data Storage with MySQL**
- ⚡ **Fast Performance with Vite & React**
- 📡 **Backend API with Express.js**
- 🔐 **Secure and Scalable Architecture**

## Technologies Used
### Frontend:
- [React](https://react.dev/) - UI Library
- [Vite](https://vitejs.dev/) - Fast Build Tool
- [Tailwind CSS](https://tailwindcss.com/) - Styling

### Backend:
- [Express.js](https://expressjs.com/) - Node.js Web Framework
- [MySQL](https://www.mysql.com/) - Database

### Additional Tools:
- [Nodemon](https://www.npmjs.com/package/nodemon) - Auto-restart for backend
- [Axios](https://axios-http.com/) - HTTP Requests

## Installation & Setup
### Prerequisites
Ensure you have the following installed:
- [Node.js](https://nodejs.org/)
- [MySQL](https://www.mysql.com/)
- [Git](https://git-scm.com/)

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/todo-app.git
cd todo-app
```

### 2. Set Up the Backend
```bash
cd backend
npm install
```

#### Configure `.env` File
Create a `.env` file in the `backend` folder and add your database credentials:
```env
DB_HOST=localhost
DB_USER=root
DB_PASSWORD=yourpassword
DB_NAME=todo_db
PORT=5000
```

#### Run the Backend Server
```bash
npm run dev
```

### 3. Set Up the Frontend
```bash
cd ../frontend
npm install
npm run dev
```

### 4. Access the Application
Visit `http://localhost:5173` in your browser.

## API Endpoints
| Method | Endpoint        | Description              |
|--------|---------------|--------------------------|
| GET    | /api/tasks     | Fetch all tasks          |
| POST   | /api/tasks     | Create a new task        |
| PUT    | /api/tasks/:id | Update a task           |
| DELETE | /api/tasks/:id | Delete a task           |

## Folder Structure
```
todo-app/
│── backend/
│   ├── server.js
│   ├── routes/
│   ├── models/
│   ├── controllers/
│   └── config/
│── frontend/
│   ├── src/
│   │   ├── components/
│   │   ├── pages/
│   │   ├── styles/
│── README.md
```

## Future Enhancements
- ✅ User authentication (Sign in / Sign up)
- 📅 Due date and priority system
- 📊 Task completion statistics
- 📱 Mobile-responsive UI

## Contributing
Pull requests are welcome! For major changes, please open an issue first to discuss what you would like to change.

## License
This project is licensed under the [MIT License](LICENSE).

