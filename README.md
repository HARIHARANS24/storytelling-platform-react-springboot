# Storytelling Platform React Springboot

## Project Overview
This project is a full-stack storytelling platform built using React for the frontend and Spring Boot for the backend. It provides a platform for users to create, share, and explore stories across various genres.
 
## Features 
- User authentication and registration  
- Story creation and management  
- Genre-based story categorization       
- Feedback and rating system        
- User dashboard for story management         
- Admin panel for user and story management          
- Responsive design for mobile and desktop          
       
## Technologies Used         
- **Frontend:**          
  - React.js        
  - Redux for state management   
  - CSS for styling 
- **Backend:** 
  - Spring Boot 
  - Spring Security for authentication
  - JPA for database interaction
  - Maven for dependency management
- **Database:**
  - MySQL (or any compatible database)
- **Other:**
  - JWT for secure authentication
  - RESTful API design

  ## Git Repository
- **Repository URL**: [https://github.com/HARIHARANS24/storytelling-platform-react-springboot](https://github.com/HARIHARANS24/storytelling-platform-react-springboot)
- **Clone the repository**:
  ```bash
  git clone https://github.com/HARIHARANS24/storytelling-platform-react-springboot.git
  ```

## Project Structure
```
Directory structure:
└── hariharans24-storytelling-platform-react-springboot/
    ├── README.md
    ├── gitattributes
    ├── LICENSE.txt
    ├── Backend/
    │   ├── API-GATEWAY/
    │   │   ├── mvnw
    │   │   ├── mvnw.cmd
    │   │   ├── pom.xml
    │   │   ├── .gitignore
    │   │   ├── src/
    │   │   │   ├── main/
    │   │   │   │   ├── java/
    │   │   │   │   │   └── com/
    │   │   │   │   │       └── example/
    │   │   │   │   │           └── demo/
    │   │   │   │   │               └── GatewayApplication.java
    │   │   │   │   └── resources/
    │   │   │   │       └── application.properties
    │   │   │   └── test/
    │   │   │       └── java/
    │   │   │           └── com/
    │   │   │               └── example/
    │   │   │                   └── demo/
    │   │   │                       └── GatewayApplicationTests.java
    │   │   └── .mvn/
    │   │       └── wrapper/
    │   │           └── maven-wrapper.properties
    │   ├── BACKEND/
    │   │   ├── mvnw
    │   │   ├── mvnw.cmd
    │   │   ├── pom.xml
    │   │   ├── .gitignore
    │   │   ├── logs/
    │   │   └── src/
    │   │       ├── main/
    │   │       │   ├── java/
    │   │       │   │   └── com/
    │   │       │   │       └── example/
    │   │       │   │           └── demo/
    │   │       │   │               ├── ProjectApplication.java
    │   │       │   │               ├── config/
    │   │       │   │               │   ├── ApplicationConfig.java
    │   │       │   │               │   ├── JwtAuthenticationFilter.java
    │   │       │   │               │   └── SecurityConfig.java
    │   │       │   │               ├── constant/
    │   │       │   │               │   └── Api.java
    │   │       │   │               ├── controller/
    │   │       │   │               │   ├── AuthenticationController.java
    │   │       │   │               │   ├── FavouriteController.java
    │   │       │   │               │   ├── FeedbackController.java
    │   │       │   │               │   ├── GenreController.java
    │   │       │   │               │   ├── ShortStoryController.java
    │   │       │   │               │   ├── StoryController.java
    │   │       │   │               │   └── UserController.java
    │   │       │   │               ├── dto/
    │   │       │   │               │   ├── Favouriterequest.java
    │   │       │   │               │   ├── request/
    │   │       │   │               │   │   ├── AuthenticationRequest.java
    │   │       │   │               │   │   └── RegisterRequest.java
    │   │       │   │               │   └── response/
    │   │       │   │               │       └── AuthenticationResponse.java
    │   │       │   │               ├── model/
    │   │       │   │               │   ├── Favourite.java
    │   │       │   │               │   ├── Feedback.java
    │   │       │   │               │   ├── Genre.java
    │   │       │   │               │   ├── ShortStory.java
    │   │       │   │               │   ├── StoryModel.java
    │   │       │   │               │   ├── User.java
    │   │       │   │               │   └── enumerate/
    │   │       │   │               │       └── Role.java
    │   │       │   │               ├── repository/
    │   │       │   │               │   ├── FavouriteRepository.java
    │   │       │   │               │   ├── FeedbackRepository.java
    │   │       │   │               │   ├── GenreRepository.java
    │   │       │   │               │   ├── ShortStoryRepository.java
    │   │       │   │               │   ├── StoryRepository.java
    │   │       │   │               │   └── UserRepository.java
    │   │       │   │               ├── service/
    │   │       │   │               │   ├── AuthService.java
    │   │       │   │               │   ├── FavouriteService.java
    │   │       │   │               │   ├── FeedbackService.java
    │   │       │   │               │   ├── GenreService.java
    │   │       │   │               │   ├── ShortStoryService.java
    │   │       │   │               │   ├── StoryService.java
    │   │       │   │               │   └── UserService.java
    │   │       │   │               └── util/
    │   │       │   │                   └── JwtUtil.java
    │   │       │   └── resources/
    │   │       │       └── application.properties
    │   │       └── test/
    │   │           └── java/
    │   │               └── com/
    │   │                   └── demo/
    │   │                       └── ProjectApplicationTests.java
    │   ├── MICROSERVICE/
    │   │   ├── mvnw
    │   │   ├── mvnw.cmd
    │   │   ├── pom.xml
    │   │   ├── .gitignore
    │   │   ├── src/
    │   │   │   ├── main/
    │   │   │   │   ├── java/
    │   │   │   │   │   └── com/
    │   │   │   │   │       └── demo/
    │   │   │   │   │           ├── MicroServiceApplication.java
    │   │   │   │   │           ├── Controller/
    │   │   │   │   │           │   └── FeedbackController.java
    │   │   │   │   │           ├── Model/
    │   │   │   │   │           │   └── Feedback.java
    │   │   │   │   │           ├── Repository/
    │   │   │   │   │           │   └── FeedbackRepository.java
    │   │   │   │   │           └── Service/
    │   │   │   │   │               └── FeedbackService.java
    │   │   │   │   └── resources/
    │   │   │   │       └── application.properties
    │   │   │   └── test/
    │   │   │       └── java/
    │   │   │           └── com/
    │   │   │               └── demo/
    │   │   │                   └── MicroServiceApplicationTests.java
    │   │   └── .mvn/
    │   │       └── wrapper/
    │   │           └── maven-wrapper.properties
    │   └── NAMING/
    │       ├── mvnw
    │       ├── mvnw.cmd
    │       ├── pom.xml
    │       ├── .gitignore
    │       ├── src/
    │       │   ├── main/
    │       │   │   ├── java/
    │       │   │   │   └── com/
    │       │   │   │       └── example/
    │       │   │   │           └── demo/
    │       │   │   │               └── NamingApplication.java
    │       │   │   └── resources/
    │       │   │       └── application.properties
    │       │   └── test/
    │       │       └── java/
    │       │           └── com/
    │       │               └── example/
    │       │                   └── demo/
    │       │                       └── NamingApplicationTests.java
    │       └── .mvn/
    │           └── wrapper/
    │               └── maven-wrapper.properties
    └── Frontend/
        ├── README.md
        ├── package-lock.json
        ├── package.json
        ├── .gitignore
        ├── public/
        │   ├── ad sin
        │   ├── admin sin.webp
        │   ├── analytics.webp
        │   ├── index.html
        │   ├── manifest.json
        │   ├── robots.txt
        │   ├── sign1.avif
        │   └── sign2.avif
        ├── src/
        │   ├── App.css
        │   ├── App.js
        │   ├── App.test.js
        │   ├── index.css
        │   ├── index.js
        │   ├── reportWebVitals.js
        │   ├── setupTests.js
        │   ├── pages/
        │   │   ├── AdminLogin/
        │   │   │   ├── adminlogin.css
        │   │   │   └── adminlogin.js
        │   │   ├── Contact/
        │   │   │   ├── Contact.css
        │   │   │   └── Contact.js
        │   │   ├── Creators Corner/
        │   │   │   ├── Creators.css
        │   │   │   └── Creators.js
        │   │   ├── Dashboardf/
        │   │   │   ├── dashboard.css
        │   │   │   ├── dashboard.js
        │   │   │   ├── dbadmins.js
        │   │   │   ├── dboverview.css
        │   │   │   ├── dboverview.js
        │   │   │   └── dbuserdetails.js
        │   │   ├── Faq/
        │   │   │   ├── F.js
        │   │   │   ├── Fa.css
        │   │   │   └── Fa.js
        │   │   ├── Genre/
        │   │   │   ├── Genre.css
        │   │   │   ├── Genre.js
        │   │   │   └── Stories/
        │   │   │       ├── StarRating.js
        │   │   │       ├── Stories.css
        │   │   │       └── Story.js
        │   │   ├── Home/
        │   │   │   ├── Home.css
        │   │   │   └── Home.js
        │   │   ├── Policies/
        │   │   │   └── PrivacyPolicy.js
        │   │   ├── Queries/
        │   │   │   ├── Queries.css
        │   │   │   └── Queries.js
        │   │   ├── ShortStory/
        │   │   │   ├── ShortStory.css
        │   │   │   ├── ShortStory.js
        │   │   │   └── Stories.css
        │   │   ├── SignIn/
        │   │   │   ├── Login.css
        │   │   │   └── Login.js
        │   │   ├── SignUp/
        │   │   │   ├── Create.css
        │   │   │   └── Create.js
        │   │   ├── Table/
        │   │   │   ├── feedbacktable.js
        │   │   │   ├── shortsorytable.js
        │   │   │   ├── storyPage.css
        │   │   │   ├── storytable.js
        │   │   │   └── usertable.js
        │   │   ├── Terms/
        │   │   │   └── Terms.js
        │   │   └── TextEditor/
        │   │       ├── TextEditor.css
        │   │       └── TextEditor.js
        │   └── redux/
        │       ├── reducer.js
        │       └── store.js
        └── .vscode/
            └── launch.json
```

## Prerequisites
- Node.js and npm for frontend development
- Java Development Kit (JDK) for backend development
- Maven for dependency management
- MySQL or any compatible database

## Frontend Setup
1. Navigate to the `Frontend` directory.
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm start
   ```

## Backend Setup
1. Navigate to the `Backend` directory.
2. Install dependencies:
   ```bash
   mvn install
   ```3. Run the application:
   ```bash
   mvn spring-boot:run
   ```

🤝 Contributing
We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

📝 License
This project is licensed under the MIT License - see the LICENSE file for details.

👥 Authors
Hariharan S - Initial work - HARIHARANS24

🙏 Acknowledgments
- Spring Boot Team
- React Team
- Material-UI Team
- All contributors and supporters
