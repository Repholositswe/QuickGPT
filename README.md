#  QuickGPT — AI ChatGPT Clone

QuickGPT is a full-stack AI chat application that I built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js).  
It’s inspired by OpenAI’s ChatGPT and allows users to chat with an AI assistant, generate images, and manage credits through Stripe payments.  

I followed a tutorial from **GreatStack on YouTube**, and then added my own features and improvements — including **dark mode**, **Stripe integration**, and **Vercel deployment**.

---

## Features

-  **AI Chat Assistant** powered by OpenAI API  
-  **Context-based Conversations** (each chat remembers history)  
-  **AI Image Generation** using ImageKit  
-  **Stripe Payments** for purchasing chat credits
-  **User Authentication** (JWT-based login & registration)  
-  **Dark Mode UI** with persistent theme memory  
-  **Vercel Deployment** for both frontend and backend  
-  **MongoDB Atlas** for secure data storage  

---

## Tech Stack

**Frontend:**
- React.js  
- React Router DOM  
- Axios  
- Tailwind CSS (with Dark Mode)  
- Stripe.js / React Stripe Elements  

**Backend:**
- Node.js + Express.js  
- MongoDB + Mongoose  
- OpenAI API  
- ImageKit API  
- Stripe API  
- JWT + bcrypt.js for authentication  
- Hosted on Vercel

---

## Environment Variables

I used a `.env` file in the **server** directory to store my secrets:

