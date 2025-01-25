# Core java program of these notes

You can download it from the [Vipul's notes](https://drive.google.com/drive/folders/1IDEteTioonkOygc_-D0F69WsJmW2P-xy?usp=sharing).


## Steps to Run the Project

Follow the steps below to set up and run the project.

### Step 1: Install Java JDK 17

Ensure that Java JDK 21 is installed on your machine. You can download it from the [official Oracle website](https://www.oracle.com/java/technologies/javase/jdk17-archive-downloads.html).

### Step 2: Build the Project

Navigate to the root directory of the project (where the `pom.xml` file is located) and run the following command to build the project:

```bash
mvn clean install -DskipTests
```

### Step 3: Run the project

Once the build is successful, you can run the project by executing the following command in the same root directory:


```bash
java -jar target/project-management-0.0.1-SNAPSHOT.jar
```

### Port:
The application will run on port 9092.


## Swagger
[swagger link](http://localhost:9092/pms/swagger-ui/index.html#/)

## Health Check of Service
[health check link](http://localhost:9092/pms/actuator/health)

