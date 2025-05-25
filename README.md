# Chat-Application


A Java-based discussion forum application that allows users to create and participate in threaded discussions.

## Prerequisites

1. Java Development Kit (JDK) 23
2. MySQL 8.0 or higher
3. Maven
4. MySQL Workbench (recommended for database management)

## Database Setup

1. Open MySQL Workbench
2. Connect to your local MySQL server
3. Create a new database:
```sql
CREATE DATABASE thread_talk;
```

## Project Setup

1. Clone or download this repository
2. Open the project in your preferred IDE
3. Update database credentials in `src/main/java/com/threadtalk/dao/DatabaseConfig.java` if needed
4. Build the project using Maven:
```bash
mvn clean install
```

## Running the Application

After building the project, you can run it using:
```bash
java -jar target/thread-talk-1.0-SNAPSHOT-jar-with-dependencies.jar
```

## Project Structure

```
ThreadTalk/
├── src/
│   └── main/
│       └── java/
│           └── com/
│               └── threadtalk/
│                   ├── dao/         # Data Access Objects
│                   ├── model/       # Data Models
│                   ├── controller/  # Business Logic
│                   └── view/        # User Interface
├── pom.xml         # Maven configuration
└── README.md       # This file
``` 
