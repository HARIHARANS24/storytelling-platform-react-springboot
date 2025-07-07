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

### Frontend
- 📁 **src/**
  - 📁 **redux/**
    - 📄 store.js
    - 📄 reducer.js
  - 📁 **pages/**
    - 📁 **Home/**
      - 📄 Home.js
      - 📄 Home.css
    - 📁 **SignIn/**
      - 📄 Login.js
      - 📄 Login.css
    - 📁 **SignUp/**
      - 📄 Create.js
      - 📄 Create.css
    - 📁 **ShortStory/**
      - 📄 ShortStory.js
      - 📄 ShortStory.css
      - 📄 Stories.css
    - 📁 **Genre/**
      - 📄 Genre.js
      - 📄 Genre.css
      - 📁 **Stories/**
        - 📄 Story.js
        - 📄 Stories.css
        - 📄 StarRating.js
    - 📁 **Dashboardf/**
      - 📄 dbuserdetails.js
      - 📄 dboverview.js
      - 📄 dboverview.css
      - 📄 dbadmins.js
      - 📄 dashboard.js
      - 📄 dashboard.css
    - 📁 **TextEditor/**
      - 📄 TextEditor.js
      - 📄 TextEditor.css
    - 📁 **Table/**
      - 📄 usertable.js
      - 📄 storytable.js
      - 📄 storyPage.css
      - 📄 shortsorytable.js
      - 📄 feedbacktable.js
    - 📁 **Queries/**
      - 📄 Queries.js
      - 📄 Queries.css
    - 📁 **Policies/**
      - 📄 PrivacyPolicy.js
    - 📁 **Faq/**
      - 📄 Fa.js
      - 📄 Fa.css
      - 📄 F.js
    - 📁 **Contact/**
      - 📄 Contact.js
      - 📄 Contact.css
    - 📁 **AdminLogin/**
      - 📄 adminlogin.js
      - 📄 adminlogin.css
    - 📁 **Creators Corner/**
      - 📄 Creators.js
      - 📄 Creators.css
    - 📁 **Terms/**
      - 📄 Terms.js
  - 📄 setupTests.js
  - 📄 reportWebVitals.js
  - 📄 logo.svg
  - 📄 index.js
  - 📄 index.css
  - 📄 App.test.js
  - 📄 App.js
  - 📄 App.css
- 📁 **public/**
  - 📄 youtube.png
  - 📄 users12.png
  - 📄 usericons.png
  - 📄 twitter.png
  - 📄 sign2.avif
  - 📄 sign1.avif
  - 📄 sats.png
  - 📄 robots.txt
  - 📄 potry.jpg
  - 📄 phonenumber.png
  - 📄 notinterested.png
  - 📄 nature.jpg
  - 📄 mostviewed.png
  - 📄 mostliked.jpeg
  - 📄 manifest.json
  - 📄 lovi.jpg
  - 📄 logo512.png
  - 📄 logo192.png
  - 📄 lifestyle.jpg
  - 📄 instagram.png
  - 📄 index.html
  - 📄 ic2.png
  - 📄 ic.png
  - 📄 hory.jpg
  - 📄 history.jpg
  - 📄 highestrating.jpeg
  - 📄 gamy.jpg
  - 📄 fax.png
  - 📄 favicon.ico
  - 📄 facebook.png
  - 📄 email.png
  - 📄 dog.jpg
  - 📄 db 1.jpg
  - 📄 crimy.jpg
  - 📄 comdy.jpg
  - 📄 background.jpeg
  - 📄 analytics.webp
  - 📄 adminusericon.jpg
  - 📄 adminlogo.png
  - 📄 admin user corner.jpg
  - 📄 admin sin.webp
  - 📄 address.png
  - 📄 ad sin
  - 📄 MYTHY.jpg
  - 📄 KIDY.jpg
  - 📄 1.png
- 📁 **.vscode/**
  - 📄 launch.json
- 📄 package.json
- 📄 package-lock.json
- 📄 README.md
- 📄 .gitignore

### Backend
- 📁 **NAMING/**
  - 📁 **src/**
  - 📁 **.mvn/**
  - 📄 pom.xml
  - 📄 mvnw.cmd
  - 📄 mvnw
  - 📄 .gitignore
- 📁 **MICROSERVICE/**
  - 📁 **src/**
  - 📁 **.mvn/**
  - 📄 pom.xml
  - 📄 mvnw.cmd
  - 📄 mvnw
  - 📄 .gitignore
- 📁 **BACKEND/**
  - 📁 **src/**
    - 📁 **test/**
    - 📁 **main/**
      - 📁 **resources/**
        - 📄 application.properties
      - 📁 **java/**
        - 📁 **com/**
          - 📁 **example/**
            - 📁 **demo/**
              - 📁 **util/**
              - 📁 **service/**
              - 📁 **repository/**
              - 📁 **model/**
              - 📁 **dto/**
              - 📁 **controller/**
              - 📁 **constant/**
              - 📁 **config/**
              - 📄 ProjectApplication.java
  - 📁 **logs/**
  - 📄 pom.xml
  - 📄 mvnw.cmd
  - 📄 mvnw
  - 📄 .gitignore
- 📁 **API-GATEWAY/**
  - 📁 **src/**
  - 📁 **.mvn/**
  - 📄 pom.xml
  - 📄 mvnw.cmd
  - 📄 mvnw
  - 📄 .gitignore

## Backend Source Files

### Backend/BACKEND/src
- 📁 **test/**
- 📁 **main/**
  - 📁 **resources/**
    - 📄 application.properties
  - 📁 **java/**
    - 📁 **com/**
      - 📁 **example/**
        - 📁 **demo/**
          - 📁 **util/**
            - 📄 JwtUtil.java
          - 📁 **service/**
            - 📄 UserService.java
            - 📄 StoryService.java
            - 📄 ShortStoryService.java
            - 📄 GenreService.java
            - 📄 FeedbackService.java
            - 📄 FavouriteService.java
            - 📄 AuthService.java
          - 📁 **repository/**
            - 📄 UserRepository.java
            - 📄 StoryRepository.java
            - 📄 ShortStoryRepository.java
            - 📄 GenreRepository.java
            - 📄 FeedbackRepository.java
            - 📄 FavouriteRepository.java
          - 📁 **model/**
            - 📁 **enumerate/**
              - 📄 Role.java
            - 📄 User.java
            - 📄 StoryModel.java
            - 📄 ShortStory.java
            - 📄 Genre.java
            - 📄 Feedback.java
            - 📄 Favourite.java
          - 📁 **dto/**
            - 📁 **response/**
              - 📄 AuthenticationResponse.java
            - 📁 **request/**
              - 📄 RegisterRequest.java
              - 📄 AuthenticationRequest.java
            - 📄 Favouriterequest.java
          - 📁 **controller/**
            - 📄 UserController.java
            - 📄 StoryController.java
            - 📄 ShortStoryController.java
            - 📄 GenreController.java
            - 📄 FeedbackController.java
            - 📄 FavouriteController.java
            - 📄 AuthenticationController.java
          - 📁 **constant/**
            - 📄 Api.java
          - 📁 **config/**
            - 📄 SecurityConfig.java
            - 📄 JwtAuthenticationFilter.java
            - 📄 ApplicationConfig.java
          - 📄 ProjectApplication.java

## API-GATEWAY Source Files

### Backend/API-GATEWAY
- 📁 **src/**
  - 📁 **test/**
  - 📁 **main/**
    - 📁 **resources/**
    - 📁 **java/**
      - 📁 **com/**
        - 📁 **example/**
          - 📁 **demo/**
            - 📄 GatewayApplication.java
- 📁 **.mvn/**
  - 📁 **wrapper/**
    - 📄 maven-wrapper.properties
    - 📄 maven-wrapper.jar
- 📄 pom.xml
- 📄 mvnw.cmd
- 📄 mvnw
- 📄 .gitignore

## MICROSERVICE Source Files

### Backend/MICROSERVICE/src
- 📁 **test/**
- 📁 **main/**
  - 📁 **resources/**
  - 📁 **java/**
    - 📁 **com/**
      - 📁 **demo/**
        - 📁 **Service/**
          - 📄 FeedbackService.java
        - 📁 **Repository/**
          - 📄 FeedbackRepository.java
        - 📁 **Model/**
          - 📄 Feedback.java
        - 📁 **Controller/**
          - 📄 FeedbackController.java
        - 📄 MicroServiceApplication.java

## NAMING Source Files

### Backend/NAMING
- 📁 **src/**
  - 📁 **test/**
  - 📁 **main/**
    - 📁 **resources/**
    - 📁 **java/**
      - 📁 **com/**
        - 📁 **example/**
          - 📁 **demo/**
            - 📄 NamingApplication.java
- 📁 **.mvn/**
  - 📁 **wrapper/**
    - 📄 maven-wrapper.properties
    - 📄 maven-wrapper.jar
- 📄 pom.xml
- 📄 mvnw.cmd
- 📄 mvnw
- 📄 .gitignore

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
