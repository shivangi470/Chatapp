
# Realtime Chat Application 💬

A **Realtime Chat Application** built with the **MERN Stack** (MongoDB, Express.js, React.js, Node.js) and enhanced with **Socket.io** for real-time communication. The application features **authentication and authorization** with **JWT**, a responsive UI with **TailwindCSS** and **Daisy UI**, and modern state management with **Zustand**.

---

## Features 🌟

- **Tech Stack:** MERN + Socket.io + TailwindCSS + Daisy UI
- 🔐 **Authentication & Authorization:** Secure login and signup using JWT.
- 📡 **Real-Time Messaging:** Powered by Socket.io for seamless communication.
- 👥 **Online User Status:** Keep track of who is online.
- 🌐 **Global State Management:** Managed with Zustand for better scalability.
- 🐛 **Error Handling:** Robust error handling on both server and client sides.
- 📤 **Cloudinary Integration:** Upload and store media files securely in Cloudinary.
- 🚀 **Deployment Ready:** Easily deploy the app for free!
- 📱 **Responsive Design:** User-friendly interface optimized for all devices.

---

## Installation & Setup 🛠️

### Prerequisites

Ensure you have the following installed:

- [Node.js](https://nodejs.org/) (v16 or higher)
- [MongoDB](https://www.mongodb.com/) (local or cloud instance)

---

### Backend Setup

1. Navigate to the backend directory:
   ```bash
   cd backend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Create a `.env` file and add the following:
   ```env
   MONGODB_URI=your_mongodb_connection_string
   PORT=5001
   JWT_SECRET=your_jwt_secret_key
   CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
   CLOUDINARY_API_KEY=your_cloudinary_api_key
   CLOUDINARY_API_SECRET=your_cloudinary_api_secret
   ```

4. Start the backend server:
   ```bash
   npm run dev
   ```

---

### Frontend Setup

1. Navigate to the frontend directory:
   ```bash
   cd frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the development server:
   ```bash
   npm run dev
   ```

--- 

---

### Configuration

Set up a `.env` file in the root of the server directory with the following variables:

```env
# MongoDB Configuration
MONGODB_URI=your_mongodb_connection_string

# Server Configuration
PORT=5001
NODE_ENV=development

# JWT Secret
JWT_SECRET=your_jwt_secret_key

# Cloudinary Configuration
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

---

### Running the Application 🚀

1. **Start the server**:
   ```bash
   cd backend
   npm run dev
   ```

2. **Start the client**:
   ```bash
   cd frontend
   npm run dev
   ```

3. Open your browser and navigate to:
   ```
   http://localhost:3000
   ```

---

---

## Highlights 🏆

- **Socket.io Integration**: For real-time bi-directional communication.
- **JWT Authentication**: Ensures secure and private communication.
- **Zustand**: Lightweight and powerful state management.
- **Cloudinary**: Simplifies media uploads and hosting.

---

## Screenshots 📸

_Add screenshots of your application here._
![image](https://github.com/user-attachments/assets/f0b458e1-e304-4d5c-8ab3-28a3d5e49d3f)
![image](https://github.com/user-attachments/assets/aca0aa7c-1ef6-4b67-8381-38ff468dad80)
![image](https://github.com/user-attachments/assets/f4d71d43-4891-402e-a0a5-f9ca0c43d5b7)
![image](https://github.com/user-attachments/assets/7bdad7f3-6917-4b6a-8688-214fb9d47da1)
![image](https://github.com/user-attachments/assets/868e1acb-f32c-4d2b-a715-7cd2c67073a3)


---

## Contributing 🤝

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add your message"
   ```
4. Push to the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a Pull Request.

---

## License 📄

This project is licensed under the MIT License. See the `LICENSE` file for details.

---

## Acknowledgments 🙏

- [TailwindCSS](https://tailwindcss.com/)
- [Socket.io](https://socket.io/)
- [MongoDB](https://www.mongodb.com/)
- [React.js](https://reactjs.org/)
- [Express.js](https://expressjs.com/)

---

