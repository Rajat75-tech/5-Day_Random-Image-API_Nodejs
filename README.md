### 🖼️ Random Image API
A simple API built with Node.js and Express that serves up a random image URL using the awesome Picsum service. It's perfect for testing, placeholders, or just for fun!

### ✨ Features
Random Image Delivery: Get a new image URL with every request.
Simple Endpoints: Easy-to-understand and use API paths.
Lightweight & Fast: Built with minimal dependencies for quick responses.
### 🚀 How to Run
Follow these simple steps to get the API up and running on your local machine:

### Clone the repository:

`` Bash

git clone https://github.com/Rajat75-tech/5-Day_Random-Image-API_Nodejs.git
cd 5-Day_Random-Image-API_Nodejs

## Install dependencies:

* Bash *

npm install
## Start the server:

Bash

node index.js
The server will be happily running at: http://localhost:3000

## 📡 API Endpoints
GET /
Returns a friendly welcome message, confirming the server is active.

GET /api/image/random
Returns a JSON object containing a fresh, random image URL.

Example Response:

## JSON

{
  "message": "Here is your random image!",
  "image": "https://picsum.photos/500"
}
🧪 Test It Out!
You can quickly test the random image endpoint directly in your web browser or using a tool like Postman:

http://localhost:3000/api/image/random

## 📦 Dependencies
*Express: A minimal and flexible Node.js web application framework.*
*Install with: npm install express*
## 📁 Project Structure
*index.js – The main server application file.*
*package.json – Defines project metadata, scripts, and dependencies.*
## 📝 License
This project is open-source and free to use for learning, experimentation, and fun!
