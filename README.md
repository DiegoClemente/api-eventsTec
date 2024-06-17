<body>
  <h1>Event Management Backend (Spring Boot) ☕</h1>

  <p>This is a Java Spring Boot backend project for event management. The application allows you to create events (remote or in-person), list events with filters, view event details, and create coupons with expiration dates for specific events.</p>

<h2>Technologies Used 🛠️</h2>
  <ul>
    <li>Java Spring Boot</li>
    <li>Lombok</li>
    <li>Flyway (for database migration)</li>
    <li>H2 Database (for development)</li>
    <li>PostgreSQL (for production)</li>
    <li>AWS Java SDK S3 (for cloud storage integration)</li>
  </ul>

<h2>Features</h2>
  <ul>
    <li><strong>Event Creation:</strong> Allows creating remote or in-person events by sending data in the request body.</li>
    <li><strong>Event Listing:</strong> Enables listing created events with filtering options.</li>
    <li><strong>Upcoming Events Search:</strong> Allows searching for upcoming events.</li>
    <li><strong>Event Details:</strong> Displays complete details of a specific event.</li>
    <li><strong>Coupon Creation:</strong> Allows creating coupons with expiration dates for a specific event.</li>
  </ul>

<h2>Testing and Usage</h2>
  <p>All tests were conducted using Insomnia. You can import the <code>Insomnia.json</code> file into Insomnia to see request examples and test the application's functionalities.</p>

<h2>Installation and Execution</h2>

<h3>Prerequisites</h3>
  <ul>
    <li>Java JDK 8 or higher installed</li>
    <li>Maven installed</li>
    <li>PostgreSQL installed (for production)</li>
    <li>AWS account and access keys to use AWS S3 (for S3 integration)</li>
  </ul>

<h3>Steps</h3>

  <ol>
      <li>Clone the repository:</li>
      <pre><code>git clone https://github.com/DiegoClemente/api-eventstec.git</code></pre>
      </br>
      <li>Navigate to the project directory:></li>
      <pre><code>cd api-eventstec</code></pre>
      </br>
      <li><strong>Database Settings:</strong>
        <ul>
          <li>For development (H2 Database already configured): No additional configuration required.</li>
          <li>For production (PostgreSQL): Configure PostgreSQL credentials in the <code>application.properties</code> file.</li>
        </ul>
      </li>
      </br>
      <li><strong>AWS S3 Settings:</strong></li>
      <p>Configure AWS S3 access keys in the <code>application.properties</code> file for AWS S3 integration.</p>
      </br>
      <li><strong>Build the Project:</strong></li>
      <pre><code>mvn clean install</code></pre>
      </br>
      <li><strong>Run the Application:</strong></li>
      <pre><code>java -jar target/api-eventstec-0.0.1-SNAPSHOT</code></pre>
      </br>
      <li><strong>Access the Application:</strong></li>
      <p>The application will be running at <a href="http://localhost:8080" target="_blank">http://localhost:8080</a>.</p>
  </ol>

<h2>Contribution</h2>
  <p>Contributions are welcome! Feel free to open issues or submit pull requests.</p>

<h2>License</h2>
  <p>This project is licensed under the <a href="https://opensource.org/licenses/MIT" target="_blank">MIT License</a>.</p>
</body>
