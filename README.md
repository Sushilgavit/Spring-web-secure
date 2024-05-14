Running the Application
The Spring Initializr creates an application class for you, which you don't need to modify. The main application class is located at src/main/java/com/example/securingweb/SecuringWebApplication.java.

Start the Application
Build and Run:
Use the command to build and run your Spring Boot application:
sh
Copy code
./mvnw spring-boot:run
Access the Home Page:
Open your browser and go to http://localhost:8080.
You should see the home page.
Secured Page and Login
Navigate to Greeting Page:

Click on the link to go to the greeting page at /hello.
Since this page is secured, you'll be redirected to the login page.
Login:

At the login page, enter user as the username and password as the password.
After logging in, you'll be taken to the greeting page.
Logout:

Click the "Sign Out" button to log out.
You'll be redirected back to the login page with a message indicating that you are logged out.
