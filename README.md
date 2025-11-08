# 💬 Real-Time Chat Application — **Chattrix**

---

## 📘 Overview

**Chattrix** is a full-stack real-time chat application built using **Socket.io**, **React**, **Express**, and **MongoDB**.  
It enables instant communication between users with features such as authentication, presence indicators, image uploads, and real-time notifications.

---

## 🚀 Features Implemented

### Core Features
1. **Real-time Messaging** – Bidirectional communication via Socket.io  
2. **User Authentication** – Secure JWT-based login & signup  
3. **Chat Rooms / Private Messaging** – One-on-one and group conversations  
4. **Notifications** – Typing and message alerts  
5. **Presence Indicators** – Online/offline status updates  

### Advanced Features
- ✅ Typing Indicators with sound notifications  
- ✅ Image Uploads via Cloudinary  
- ✅ Welcome Emails using Resend API  
- ✅ API Rate-Limiting using Arcjet  
- ✅ Toggleable Sound & Dark Mode in UI  

---

## 🧱 Tech Stack

| Layer | Technologies |
|-------|---------------|
| **Frontend** | React, Tailwind CSS, DaisyUI, Zustand |
| **Backend** | Node.js, Express.js, Socket.io |
| **Database** | MongoDB |
| **Integrations** | Cloudinary, Resend, Arcjet |
| **Auth** | Custom JWT |


---

## ⚙️ Setup Instructions


## 🧪 .env Setup

### Backend (`/backend`)

```bash
PORT=3000
MONGO_URI=your_mongo_uri_here

NODE_ENV=development

JWT_SECRET=your_jwt_secret

RESEND_API_KEY=your_resend_api_key
EMAIL_FROM=your_email_from_address
EMAIL_FROM_NAME=your_email_from_name

CLIENT_URL=http://localhost:5173

CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret

ARCJET_KEY=your_arcjet_key
ARCJET_ENV=development
```

---

## 🔧 Run the Backend

```bash
cd backend
npm install
npm run dev
```

## 💻 Run the Frontend

```bash
cd frontend
npm install
npm run dev
```
---
---
## 💬 Core Functionality Summary

| Feature        | Description                     |
|----------------|---------------------------------|
| Messaging      | Real-time text chat             |
| Auth           | JWT-based authentication        |
| Presence       | Online/offline indicators       |
| Notifications  | Typing & message alerts         |
| Media          | Image uploads via Cloudinary    |
| Email          | Automatic welcome emails        |

## 🧠 Architecture

1. Zustand handles global app state

2. Socket.io synchronizes client ↔ server events

3. MongoDB persists user and chat data

4. Express powers REST endpoints

5. Arcjet limits API abuse

6. Cloudinary manages uploaded media


---
---

## Screenshots

## login page
![Login Screen](frontend/public/1%20(1).png)
---
## register page
![Register Screen](frontend/public/1%20(2).png)
---
## chat page for user - bravin
![Login Screen](frontend/public/1%20(3).png)
---
## chat page for user - cate
![Login Screen](frontend/public/1%20(4).png)
---
## cate sending an image and text to bravin in realtime
![Login Screen](frontend/public/1%20(5).png)
---
## bravin recieved the image sent by cate  in realtime
![Login Screen](frontend/public/1%20(7).png)
---
 ## an offline user
 ![Login Screen](frontend/public/1%20(10).png)

 ---
 ---
 ---
 ## 📚 Resources
---
[Socket.io Docs](https://socket.io/docs/v4/)

[React Docs](https://react.dev/)

[Express Docs](https://expressjs.com/)

[MongoDB Docs](https://www.mongodb.com/docs/)