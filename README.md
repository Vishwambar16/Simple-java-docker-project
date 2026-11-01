# ☕ Simple Java Application Using Docker

## 📌 Project Overview

This project demonstrates how to containerize and run a simple Java application using Docker.

The application is developed in Java and uses the built-in `java.util.Date` class to retrieve and display the current system date and time.

Docker is used to package the Java application into a container using OpenJDK 17 Alpine.

## 💻 Application Code

The application uses the following Java functionality:

```java
import java.util.Date;

public class Main {
    public static void main(String[] args) {
        Date currentDate = new Date();
        System.out.println("Hello, Docker! Current date: " + currentDate);
    }
}
```

### Expected Output

```text
Hello, Docker! Current date: [current system date and time]
```

The displayed date and time depend on the container's system clock.

## 🎯 Project Objective

- Understand Java application containerization.
- Learn how to write and use a Dockerfile.
- Build a Docker image using OpenJDK 17.
- Compile and execute Java code inside a Docker container.
- Understand the basic Docker image and container lifecycle.

## 🛠️ Technologies

- Java
- OpenJDK 17
- Docker
- Alpine Linux
- Git and GitHub

## 🚀 Run the Project

```bash
docker build -t simple-java-app .
docker run --rm simple-java-app
```

## 👨‍💻 Author

**Vishwambar Waghamode**

Aspiring Cloud & DevOps Engineer

- LinkedIn: https://www.linkedin.com/in/vishwambar-waghamode/
- Email: vishwambar16@gmail.com

---

⭐ Building practical projects while learning Cloud and DevOps.

**Build • Automate • Deploy** 🚀
