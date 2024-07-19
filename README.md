# Just Another Text Editor (J.A.T.E.)

Just Another Text Editor (J.A.T.E.) is a Progressive Web Application (PWA) designed to provide a modern, offline-capable text editor experience. It uses technologies like Express.js, Webpack, and IndexedDB to deliver a seamless user experience both online and offline.

## Features

- **Rich Text Editing:** Use CodeMirror for syntax highlighting and code editing.
- **Offline Capability:** The app works offline with service workers and IndexedDB.
- **PWA Support:** Install the app on your device for an enhanced user experience.
- **Client-Server Architecture:** Uses Express.js for the server-side and Webpack for building the client-side application.

## Table of Contents

1. [Installation](#installation)
2. [Usage](#usage)
3. [Testing](#testing)
4. [Deployment](#deployment)
5. [Contributing](#contributing)
6. [License](#license)

## Installation

### Prerequisites

- Node.js (v14 or later)
- npm (Node Package Manager)

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/jate.git
   cd jate
   ```
2. **Install Dependencies**

  Navigate to the client directory and install dependencies:

  ```bash
  cd client
  npm install
  ```

  Navigate to the server directory and install dependencies:

  ```bash
  cd ../server
  npm install
  ```

3. **Build the Client-Side**

  Run the build command in the client directory to generate the production-ready files:

  ```bash
  cd ../client
  npm run build
  ```

## Usage
### Start the Development Server

  Navigate to the server directory and run:

  ```bash
  cd server
  npm run server
  ```
Open your browser and go to http://localhost:3000 to access the application.

### Build and Run for Production

Build the client-side files:

```bash
cd client
npm run build
```

Start the production server:

  ```bash
  cd ../server
  npm start
  ```

## Testing
### Run Tests

For unit testing and integration testing, you may need to add test scripts in the client/package.json and server/package.json files. Run your tests using:

  ```bash
  npm test
   ```

#### Verify Functionality
Check Offline Functionality

Disable your network connection and verify that the application still functions as expected.

Inspect Browser Console
Open the browser's developer tools and inspect for any errors or warnings.

## Deployment
Deploy to Render
Create a New Web Service on Render

Go to the Render dashboard and create a new Web Service.

Connect your Git repository and select the branch you want to deploy.

Configure Build and Start Commands

Build Command: npm run build

Start Command: npm run server
