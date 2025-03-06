# Project Overview

This project is a Java application that manages Aikido training sessions, instructors, and students. It uses Jakarta Persistence (JPA) for ORM and is built with Maven.

## Project Structure## Setup Instructions

1. **Clone the repository:**
    ```sh
    git clone https://github.com/yourusername/your-repo-name.git
    cd your-repo-name
    ```

2. **Build the project using Maven:**
    ```sh
    mvn clean install
    ```

3. **Run the application:**
    ```sh
    mvn exec:java -Dexec.mainClass="Main"
    ```

4. **Ensure you have a database configured and update the `persistence.xml` file with your database connection details.**

5. **To run tests:**
    ```sh
    mvn test
    ```

## Dependencies

- Java 11+
- Maven 3.6+
- Jakarta Persistence (JPA)
- Your preferred database (e.g., MySQL, PostgreSQL)

## Contributing

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -am 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a new Pull Request.


