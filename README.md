# Node Web App

A simple Node.js web application using Express and EJS.

## Features
- Express.js backend
- EJS templating engine
- Static file serving
- Docker support

## Installation
### Install Node.js

If you don't have Node.js installed, install it from:
- [Node.js official site](https://nodejs.org/) (Recommended LTS version)
- Or use the following command:
  ```sh
  sudo apt install -y nodejs
  sudo apt install -y npm
  ```

### Clone the repository:
1. Clone the repository:
   ```sh
   git clone https://github.com/your-repo/sample-webapp-node.git
   cd sample-webapp-node
   ```

2. Install dependencies:
   ```sh
   npm install
   ```

3. Start the server:
   ```sh
   npm start
   ```
   The app will be running at `http://localhost:3000`.

## Running with Docker

1. Build the Docker image:
   ```sh
   docker build -t node-web-app .
   ```

2. Run the container:
   ```sh
   docker run -d -p 3000:3000 node-web-app
   ```



<!-- Security scan triggered at 2025-09-02 15:27:59 -->

<!-- Security scan triggered at 2025-09-02 17:17:47 -->