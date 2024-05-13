# Examination-System-Using-JavaScript
An automated online examination system with database support, facilitating exam generation, management, and result processing.
# Description
The Online Examination System is a web-based platform designed to facilitate online exams. It includes user registration, sign-in, and exam-taking functionalities, with timed exams, random question display, and answer submission features.

# Features
Registration: Users can register with their first name, last name, email address, and password. Password validation ensures a minimum length of 8 characters and matching passwords.
Sign-in: Registered users can sign in using their email and password.
Exam Page: The exam page displays questions randomly. Each question includes options for answers, navigation buttons to move between questions, a timer indicator, and a submit button to finalize the exam.
Timeout Handling: If the exam time expires before submission, a timeout page is displayed with a message for the user.
Grading: If the exam is submitted before the time ends, a grades page is displayed with a message for the user.
Marking Questions: Users can mark questions for review, which are then listed separately for easy reference.
Question and Answer Objects: Utilizes function constructors for question and answer objects to manage exam content efficiently.
Technology Stack
Programming Language: JavaScript (Frontend), Java (Backend)
Framework: Spring Boot (Backend)
Database: MySQL
Frontend: HTML, CSS, JavaScript
Version Control: Git
IDE: IntelliJ IDEA
# Usage
Registration: Users register with their personal details on the registration page.
Sign-in: Registered users sign in using their email and password on the sign-in page.
Exam Page: Users are directed to the exam page upon successful sign-in. They can navigate through questions, mark them for review, and submit answers within the allotted time.
Grading/Timeout Page: Depending on submission timing, users are redirected to either the grades page or the timeout page.