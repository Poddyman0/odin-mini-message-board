<strong>Project Title: Interactive Message Board</strong>

<strong>Description:</strong>

In this project, I built a simple message board using Express and EJS. The application allows users to view a list of messages, submit new messages via a form, and see detailed information about each message on a separate page.

<strong>Technologies Used:</strong>

<ul>
  <li><strong>Express:</strong> For setting up the server and handling routes.</li>
  <li><strong>EJS:</strong> For templating and rendering HTML views.</li>
  <li><strong>HTML/CSS:</strong> For basic styling and structure.</li>
</ul>
<strong>Features:</strong>

<ul>
  <li><strong>Home Page ("/"):</strong>
    <ul>
      <li>Displays a list of messages.</li>
      <li>Each message includes the user’s name, message text, and the date it was added.</li>
      <li>Messages are dynamically rendered from an array and displayed using EJS templates.</li>
    </ul>
  </li>
  <li><strong>New Message Form ("/new"):</strong>
    <ul>
      <li>Allows users to submit a new message.</li>
      <li>Form includes fields for the author’s name and the message text.</li>
      <li>Submissions are processed and added to the messages array.</li>
    </ul>
  </li>
  <li><strong>Message Details:</strong>
    <ul>
      <li>An "open" button next to each message redirects to a page showing detailed information about the message.</li>
    </ul>
  </li>
  <li><strong>Routing and Form Handling:</strong>
    <ul>
      <li>POST request handling for form submissions.</li>
      <li>GET request handling for rendering pages.</li>
      <li>Data is parsed from form submissions using express.urlencoded().</li>
    </ul>
  </li>

  To run this Express app locally, follow these steps:

Ensure you have Node.js and npm installed: You can check this by running the following commands in your terminal:

bash
Copy code
node -v
npm -v
If you don’t have them installed, download and install Node.js from https://nodejs.org/, which includes npm.

Navigate to your project directory: Open your terminal or command prompt and navigate to the root of your project:

bash
Copy code
cd odin-mini-message-board
Install dependencies: Run the following command to install all the necessary dependencies specified in your package.json:

bash
Copy code
npm install
Set up environment variables (optional): If the project requires environment variables, you should create a .env file in the root of your project and define those variables. For example:


For production mode:
bash
Copy code
npm start
For development mode with live reloading (using nodemon):
bash
Copy code
npm run serverstart
The serverstart script sets up the environment variable DEBUG for detailed logging and runs the app using nodemon, which watches for file changes and automatically restarts the server.

Open the app in your browser: By default, the app will run on port 3000. Open your browser and navigate to:

arduino
Copy code
http://localhost:3000
If you set a custom port in your environment variables, use that port instead.

Your Express app should now be running locally! You can view the logs in your terminal and test the endpoints in your browser or using tools like Postman.
  <li><strong>Dynamic Content Rendering:</strong>
    <ul>
      <li>The messages array is updated with new messages and displayed on the index page.</li>
    </ul>
  </li>
  <li><strong>Deployment:</strong> The project is pushed to GitHub. Deployment instructions are to be covered in a subsequent lesson.</li>
</ul>
