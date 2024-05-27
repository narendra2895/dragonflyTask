Overview
Dragonfly Task is a web application that allows users to upload images, compress them, and track their processing status through an API. The application is built using React for the frontend and Express for the backend.

Folder Structure
The project is organized into the following structure:

dragonfly_task/
├── api/
│   ├── node_modules/
│   ├── package-lock.json
│   ├── package.json
│   └── server.js
├── node_modules/
├── public/
├── src/
│   ├── components/
│   ├── App.css
│   ├── App.js
│   ├── App.test.js
│   ├── index.css
│   ├── index.js
│   ├── logo-white.png
│   ├── logo.svg
│   ├── reportWebVitals.js
│   └── setupTests.js
├── .env
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
└── webpack.config.js



Installation
Prerequisites
<!-- --------- -->
Node.js
npm


Setup
<!-- --------- -->
Clone the repository:
<!-- --------- -->
git clone https://github.com/your-username/dragonfly_task.git
cd dragonfly_task
Install dependencies for the frontend:
npm install

Navigate to the api directory and install backend dependencies:
<!-- --------- -->
cd api
npm install
cd ..


Environment Variables
Create a .env file in the root directory and add the following environment variables:
<!-- --------- -->
API_KEY=your_api_key
BASE_URL=your_base_url



Running the Application
<!-- --------- -->
npm start
This will concurrently run both the frontend and the backend.

Available Scripts
In the project directory, you can run:

Frontend Scripts
<!-- --------- -->

npm start: Runs the app in the development mode.
npm run build-client: Builds the app for production to the build folder.
npm run test: Launches the test runner in the interactive watch mode.
npm run eject: Removes the single build dependency from your project.


Backend Scripts
<!-- --------- -->

cd api && node server.js: Starts the backend server.


Dependencies:

Frontend
<!-- --------- -->
axios
compressorjs
concurrently
dotenv
react
react-confirm-alert
react-dom
react-scripts
react-toastify
web-vitals


Backend
<!-- --------- -->
aws-sdk
axios
cors
dotenv
express
sharp



Usage
<!-- --------- -->

Upload Images: Users can upload images either by clicking "Choose Files" or by dragging and dropping files into the designated area.
Compression and Validation: The images are compressed and validated based on size and resolution constraints.
API Integration: The images are uploaded to the server, and their processing status can be tracked through API calls.


