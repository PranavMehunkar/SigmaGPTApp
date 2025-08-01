<h1>SigmaGPT</h1>
<h2>Overview</h2>
This is a full-stack conversational AI chatbot inspired by ChatGPT, designed to provide users with a seamless and efficient experience. This project leverages modern technologies and is scalable, flexible, and designed for real-world use cases.

<h2>Table of Contents</h2>
<li>Overview</li>
<li>Tech Stack</li>
<li>Features</li>
<li>Installation</li>
<li>Usage</li>
<li>Testing</li>
<li>Deployment</li>
<li>License</li>

<h2>Tech Stack</h2>
<h3>Frontend</h3>
<li>HTML</li>
<li>CSS</li>
<li>JavaScript</li>
<li>React</li>
<li>Bootstrap</li>
<li>Material UI</li>

<h3>Backend</h3>
<li>Node.js</li>
<li>Express.js</li>

<h3>Database</h3>
<li>MongoDB</li>

<h3>Deployment</h3>
<li>Render</li>

<h3>Development Tools</h3>
<li>Visual Studio Code</li>
<li>Node.js</li>
<li>Git</li>
<li>GitHub</li>

<h3>Features</h3>
<li>User-friendly interface</li>
<li>Integration with APIs.</li>
<li>Responsive design for mobile and desktop users.</li>
<li>Robust backend.</li>
<li>Data storage with MongoDB for user portfolios, history, and more.</li>
<li>Continuous deployment on Render.</li>

<h2>Installation</h2>
To run ChatGPT Clone locally, follow these steps:

<h3>1. Clone the repository:</h3>

git clone https://github.com/yourusername/SigmaGPTApp.git
<h3>2. Navigate to the project directory:</h3>

cd SigmaGPTApp
<h3>3. Install the dependencies for both the frontend and backend:</h3>

npm install
<h3>4. Set up environment variables:</h3>

Create a .env file in the root directory and configure the following variables:

MONGO_URI=<your_mongodb_uri><br>
OPENAI_API_KEY=<your_openai_api_key><br>

<h3>5. Run the development server:</h3>

For the backend:

nodemon server.js<br>
For the frontend:

npm run dev
<h3>6. Open your browser and navigate to:</h3>

http://localhost:5173
<h2>Usage</h2>
Once the application is running, you can:

<li>Create new chat.</li>
<li>See previous chats.</li>
<li>Delete a chat.</li>

<h2>Deployment</h2>
ChatGPT Clone is deployed on Render. For deployment, ensure you have the Render CLI configured and use the following commands to deploy the application:

npm run deploy<br>
Ensure your Render credentials and services are properly set up for deployment.

<h2>License</h2>
All rights reserved.
