A Zerodha-inspired stock trading web application that replicates the look and core workflow of the Zerodha (Kite) platform.
The stock market data in this project was fetched once from a free API and stored locally, and is now static, as most real-time stock APIs are paid.

🚀 Features

🔐 User Authentication (Login / Signup)

📊 Trading Dashboard (Static Market Data)

📉 Stock Charts & Price Visualization

💼 Portfolio & Holdings View

📑 Buy / Sell Order Simulation

📱 Responsive UI

🛠️ Tech Stack

Frontend: React.js, HTML, CSS, JavaScript

Backend: Node.js, Express.js

Database: MongoDB

Auth: JWT

⚙️ Installation & Setup
1️⃣ Clone the Repository
git clone https://github.com/alphanumeric0905/ZERODHA-clone.git
cd ZERODHA-clone

2️⃣ Install Backend Dependencies
cd backend
npm install
nodemon index.js

3️⃣ Install Frontend Dependencies
cd frontend
npm install
npm run start

4️⃣ Install Dashboard Dependencies
cd dashboard
npm install
npm run start

🌐 Environment Variables

Create a .env file in the backend directory:

PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key

ZERODHA clone walkthrough video:
https://github.com/alphanumeric0905/ZERODHA-clone/releases/tag/v1
