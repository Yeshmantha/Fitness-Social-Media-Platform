# Fitness Social Media Platform

The project was designed to create a social media platform tailored to fitness lovers. The platform allows users to share their fitness journeys, and workouts through a Java-based Spring Boot REST API and a React-based client web application. The application highlights React-based user-friendliness and simplicity, catering to individuals with varying levels of technical expertise.

### Key Features:
- **Media Sharing:** Users can upload photos showcasing their fitness activities.
- **Workout Status Updates:** Users can share updates on their current workout status with predefined templates.
- **Workout Plan Sharing:** Users can share and customise their workout plans.
- **Interaction:** Users can like and comment on posts.
- **Profiles:** Users can view and follow other profiles, displaying all fitness-related posts and activities.

### Technologies Used:
- **Backend:** Spring Boot, Spring Security, OAuth 2.0
- **Frontend:** React
- **Database:** MongoDB
- **Version Control:** Git, GitHub

## How to Install and Run the Project

### Prerequisites:
- **Java Development Kit (JDK) 11 or later**
- **Node.js and npm**
- **MySQL or other relational database**

### Backend (Spring Boot):
1. Clone the repository:
    ```sh
    git clone https://github.com/Yeshmantha/Fitness-Social-Media-Platform.git
    ```
2. Navigate to the backend directory:
    ```sh
    cd Fitness-Social-Media-Platform/paf-backend
    ```
3. Update the `application.properties` file with your database credentials.
    ```sh
    spring.data.mongodb.uri=your_mongodb_uri
    spring.data.mongodb.database=your_database_name
    ```

5. Build and run the Spring Boot application:
    ```sh
    ./mvnw spring-boot:run
    ```

### Frontend (React):
1. Navigate to the frontend directory:
    ```sh
    cd Fitness-Social-Media-Platform/paf-frontend
    ```
2. Install the dependencies:
    ```sh
    npm install
    ```
3. Start the React application:
    ```sh
    npm start
    ```

## Tests

To run tests for the application:

### Backend:
1. Navigate to the backend directory:
    ```sh
    cd Fitness-Social-Media-Platform/paf-backend
    ```
2. Run the tests:
    ```sh
    ./mvnw test
    ```

### Frontend:
1. Navigate to the frontend directory:
    ```sh
    cd Fitness-Social-Media-Platform/paf-frontend
    ```
2. Run the tests:
    ```sh
    npm test
    ```

## How to Contribute to the Project

1. Fork the repository.
2. Create your feature branch:
    ```sh
    git checkout -b feature/YourFeature
    ```
3. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
4. Push to the branch:
    ```sh
    git push origin feature/YourFeature
    ```
5. Open a pull request.
