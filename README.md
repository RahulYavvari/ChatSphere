
# ChatSphere 

**ChatSphere** is a full-stack real-time chat application built using **Node.js**, **Express**, **MongoDB**, and **React.js**. It allows users to connect and chat instantly with anyone online, share images, customize themes, and manage their profiles—all in a smooth, responsive interface.

[ChatSphere Preview](https://chatsphere-q9mv.onrender.com/)

## Features

* **User Authentication** – Sign up and log in securely.
* **Real-time Messaging** – Chat with any user who's online.
* **Image Sharing** – Send images in chat using Cloudinary.
* **Profile Management** – Upload a profile picture and manage personal settings.
* **Theme Customization** – Switch between multiple themes using the settings page.
* **Modern UI** – Built with **Tailwind CSS** and **DaisyUI** for a sleek, responsive design.

## Tech Stack

### Frontend

* **React.js**
* **Tailwind CSS**
* **DaisyUI**
* **Socket.io-client**

### Backend

* **Node.js**
* **Express.js**
* **MongoDB (Mongoose)**
* **Socket.io**
* **Cloudinary (for image storage)**

##  Installation

### Prerequisites

* Node.js (v16+)
* MongoDB instance or MongoDB Atlas URI
* Cloudinary account (for image storage)

### Clone the repository

```bash
git clone https://github.com/RahulYavvari/ChatSphere.git
cd ChatSphere
```

Create a `.env` file in the `server` directory with the following:

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the project

```bash
npm run build
```

### Start the backend

```bash
npm start
```

The frontend will run on `http://localhost:5173` and connect to the backend running on port `5001`.


## 📄 License

This project is licensed under the MIT License.
