# Spring-Boot-based-Anonymous-Feedback-System
A web application designed to foster better communication in classrooms. It enables students to anonymously send notifications or ask questions when they need clarification on a topic. Teachers receive these inputs in real-time, allowing them to address doubts promptly, promotes active learning by reducing hesitation in seeking help.

# Spring Boot-based Anonymous Feedback System  

## Project Overview  
The **Spring Boot-based Anonymous Feedback System** is a web application that bridges the communication gap between students and teachers in a classroom setting. It empowers students to send anonymous notifications or ask questions when they need additional clarification on a topic. This ensures real-time feedback, enabling teachers to adapt their teaching methods and address doubts effectively.  

---

## Features  
- **Anonymous Notifications**: Students can send feedback discreetly without fear of judgment.  
- **Real-time Updates**: Teachers receive notifications immediately to address students' concerns.  
- **Question Submission**: Students can ask questions anonymously, which appear on the teacher's dashboard.  
- **Dynamic UI**: A simple, user-friendly interface with a modern look and feel.  
- **Secure and Efficient**: Built using Spring Boot, ensuring robust back-end functionality.  

---

## Technology Stack  
- **Backend**: Spring Boot  
- **Frontend**: Thymeleaf, HTML, CSS  
- **Database**: H2 (or replaceable with any relational database)  
- **Tools**: IntelliJ IDEA/VS Code, Maven  

---

## Installation  

### Prerequisites  
1. Install [Java 8 or later](https://www.oracle.com/java/technologies/javase-downloads.html).  
2. Install [Maven](https://maven.apache.org/install.html).  
3. Install a Spring Boot-supported IDE like IntelliJ IDEA or VS Code.  

### Steps  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-repo/anonymous-feedback-system.git  
   ```  
2. Navigate to the project directory:  
   ```bash  
   cd anonymous-feedback-system  
   ```  
3. Build the project using Maven:  
   ```bash  
   mvn clean install  
   ```  
4. Run the application:  
   ```bash  
   mvn spring-boot:run  
   ```  
5. Access the application in your browser:  
   ```
   http://localhost:8080  
   ```  

---

## Usage  
1. Navigate to the home page: `/`  
2. Use the **Send Notification** tab to anonymously send a feedback notification or ask a question.  
3. Access the **View Notifications** tab to see all notifications and questions sent anonymously.  

---

## Folder Structure  
```
src  
├── main  
│   ├── java/com/notifyapp/anonynotify  
│   │   ├── AnonynotifyApplication.java  # Main Spring Boot application  
│   │   ├── NotificationController.java  # Controller to handle requests  
│   ├── resources  
│   │   ├── templates  
│   │   │   ├── sendNotification.html  # Frontend for sending notifications  
│   │   │   ├── viewNotifications.html  # Frontend for viewing notifications  
│   │   ├── static/css/styles.css       # Custom styles  
│   ├── application.properties          # Configuration  
```  

---

## Future Enhancements  
- **Email/SMS Notifications**: Notify teachers via email or SMS.  
- **Multi-Class Support**: Expand functionality to support multiple classrooms.  
- **User Authentication**: Add login features for enhanced security.  
- **Mobile App Integration**: Develop a mobile-friendly version for better accessibility.  

---

## License  
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.  

---

## Acknowledgments  
We thank our project supervisor for their guidance and all contributors for their valuable feedback during the development phase.  

---  

Feel free to customize further as needed!
