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
  <li><strong>Dynamic Content Rendering:</strong>
    <ul>
      <li>The messages array is updated with new messages and displayed on the index page.</li>
    </ul>
  </li>
  <li><strong>Deployment:</strong> The project is pushed to GitHub. Deployment instructions are to be covered in a subsequent lesson.</li>
</ul>
