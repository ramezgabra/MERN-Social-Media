# MERN Social Media Project

## Description

A full-stack social media application built using the MERN stack (MongoDB, Express.js, React, Node.js) for users to create accounts, post updates, and connect with others.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)

## Demo

Check out the live demo: [social media Live Demo](https://mern-social-media-ramez.netlify.app/)

## Installation

1. Clone the repository: `git clone https://github.com/ramezgabra/Mern-Social-Media.git`
2. Navigate to the project directory: `cd Mern-Social-Media`

### Server Installation

3. Navigate to the server directory: `cd server`
4. Install server dependencies: `npm install`

### Client Installation

5. Navigate to the client directory: `cd ../client`
6. Install client dependencies: `npm install`


### Configuration

- Create a `.env` file in the root directory with the following environment variables:

```env
MONGO_URL=your_mongodb_connection_uri
JWT_SECRET=your_jwt_secret
PORT=3001
```
## Usage

To run the server, navigate to the server directory:

```bash
cd server
npm run start
```

To run the client, navigate to the client directory:

```bash
cd client
nodemon index.js
```

Make sure to follow these steps to start the server and client.

Access the application in your web browser at `http://localhost:3000`.
