A Spring Boot REST API for user authentication, supporting signup, login, and token validation with JWT.
________________________________________
🚀 Features: 

 User Signup
  
  User Login
  
  JWT Token generation and validation
  
  RESTful API design

________________________________________
🏟 Technology Stack: 

  Java 17,
  Spring Boot, 
  Spring Security,
  JWT (JSON Web Token),
  Maven
________________________________________
📌 API Endpoints
1. Signup
   
•	URL: http://localhost:8090/auth/signup

•	Method: POST

•	Request & Response Body:  => images/signUp.png   

Data updated on Database tables:   => images/database_table.png
 
2. Login
   
•	URL: http://localhost:8090/auth/login

•	Method: POST

•	Request & Response Body:  =>images/login.png

________________________________________

3. Validate Token
   
•	URL: http://localhost:8090/auth/validate/GIVWJQMKOEa86fnNtaexxcXj4coZIYetBpdP6TyStvZFMKWJaRSyWH2cW89zXW9VC4iw1VcOSGU2VaDPmEZrUlnGLzWfWBu4I18tJZ4cjX9gaxJT3ehF9yYsARpHU2MH

•	Method: GET

•	Headers:
Authorization: Bearer <token>

•	Response:     =>  images/validateToken.png

 
________________________________________
🔧 Setup & Installation
1.	Clone the repository:
git clone https://github.com/017-anamika/UserService.git
2.	Navigate to project folder:      cd UserService
3.	Build and run the application:    mvn spring-boot: run
4.	API is available at: http://localhost:8090
________________________________________
💼 Usage
1.	Use Postman or any API client to test the endpoints.
2.	First, create a user via /signup.
3.	Login using /login to get the JWT token.
4.	Access protected endpoints using the token in the Auth
