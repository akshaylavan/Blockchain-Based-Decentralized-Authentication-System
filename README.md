Blockchain-Based Decentralized Authentication System

Overview

This project is a decentralized authentication system built using blockchain technology to enhance security and prevent unauthorized access. The system leverages MetaMask for authentication, Next.js for the frontend, React for UI components, MongoDB for storing API keys, and a token-based login system to manage session expiration.

Features

Decentralized Authentication: Users authenticate securely using MetaMask.

API Key Generation: The system generates API keys upon user registration and stores them in MongoDB.

Token-Based Login: Sessions expire after a defined period, requiring re-login for security.

Secure and Private: No central authority manages authentication, reducing risks of data breaches.

User-Friendly Interface: Built with Next.js and React for a seamless experience.

Tech Stack

Frontend: Next.js, React, Tailwind CSS

Backend: Node.js, Express.js

Database: MongoDB

Blockchain & Authentication: MetaMask, Web3.js

Installation

Prerequisites

Ensure you have the following installed:

Node.js (v16 or later)

MongoDB

MetaMask extension in your browser

Setup Instructions

Clone the repository

git clone https://github.com/akshaylavan/Blockchain-Based-Decentralized-Authentication-System.git
cd Blockchain-Based-Decentralized-Authentication-System

Install dependencies

npm install

Set up environment variables
Create a .env file in the root directory and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_secret_key
NEXT_PUBLIC_RPC_URL=your_blockchain_rpc_url

Run the development server

npm run dev

The application will be available at http://localhost:3000

Usage

Connect MetaMask: Users must connect their MetaMask wallet.

Register/Login: Upon authentication, an API key is generated and stored securely.

Session Management: Users must re-login after session expiration.

Contributing

Contributions are welcome! Please follow these steps:

Fork the repository.

Create a new branch: git checkout -b feature-branch.

Commit your changes: git commit -m "Add new feature".

Push to your branch: git push origin feature-branch.

Open a pull request.

License

This project is licensed under the MIT License.

Contact

For any questions or feedback, feel free to reach out:

GitHub: @akshaylavan

Email: akshaylavan783@gmail.com

