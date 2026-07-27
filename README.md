# Educational & Digital Skills Development Website

An interactive educational website designed to help students and young people explore digital skills, technology courses, freelancing opportunities and career pathways through a user-friendly learning platform.

## Live Application

[Open the Live Educational and Digital Skills Website](https://digital-learning-zone.netlify.app/)

## Problem Statement

Many students and young people have limited access to clear, organized and beginner-friendly information about digital skills, technology courses and online career opportunities. They may also face difficulty selecting an appropriate course or understanding how to begin their digital learning journey.

This project provides a centralized platform where users can explore digital courses, register for learning opportunities, contact the training team and receive immediate guidance through an interactive chatbot.

## Target Users

- Students
- Young graduates
- Beginners interested in digital skills
- Freelancing learners
- People seeking technology training
- Users who need guidance in selecting a digital course

## Main Features

- Responsive home page
- Digital skills course catalogue
- Course descriptions and enrolment options
- Login interface
- Signup and registration interface
- About section
- Contact information
- Functional contact form
- Interactive educational chatbot
- Mobile-responsive design
- Navigation between major sections
- Visual course cards
- Career and enrolment guidance

## AI-Powered Feature

The application includes an educational chatbot called the **E-Rozgaar Assistant**.

The assistant helps users with:

- Course information
- Enrolment guidance
- Course duration and schedules
- Career opportunities
- Contact information
- Website navigation

### Assistant Instructions

The chatbot is instructed to act as a helpful digital-learning assistant for students and beginners. It should provide clear, short and supportive responses about available courses, enrolment, digital skills, career opportunities and contact information.

It should:

- Use simple English.
- Provide beginner-friendly answers.
- Guide users to relevant sections of the website.
- Avoid unrelated responses.
- Encourage users to explore suitable digital courses.
- Provide contact information when further support is required.
-
Project Overview 
This project is a fully dynamic Educational & Digital Skills Platform developed to provide users with an interactive and engaging learning experience. The website enables users to browse available courses, register for training programs, communicate through a built-in AI chat-bot, and access essential digital learning resources.
The platform consists of multiple well-structured and responsive pages, including:
•	Home Page – Introduces the platform, highlights key features, and provides quick navigation.
•	Courses Page – Displays a categorized list of training programs with descriptions to help users choose the right course.
•	About Page – Explains the purpose, mission, and background of the platform.
•	Contact Page – Allows users to submit inquiries through a functional contact form integrated with the backend.
•	Signup & Login Pages – Provide user authentication functionality using PHP and MySQL, enabling secure access to the website's features.
Overall, the project integrates front-end and back-end technologies to create a modern, user-friendly system tailored for digital learning and skill development.
 
System Features
•	Responsive Home Page with Hero Banner 
•	The homepage is designed with a fully responsive layout that adapts seamlessly to different screen sizes, including desktops, tablets, and mobile devices. It includes a visually appealing hero banner that highlights the platform’s purpose and guides users to explore key sections of the website.
•	Courses Page with Interactive Course Cards
The Courses page showcases multiple course offerings using structured and visually attractive course cards. Each card contains course titles, descriptions, and visual elements, making it easier for users to browse and select relevant training programs.
•	Comprehensive About Us Section
This section provides a detailed overview of the e-Rozgaar initiative, its mission, objectives, and the impact it aims to create. It includes descriptive text and images to help users understand the purpose of the program and the value it delivers.
•	Secure Login & Signup System (PHP + MySQL)
A user authentication module has been implemented using PHP and MySQL. The system allows new users to create an account and existing users to log in securely. Passwords are managed safely, and form validations ensure accurate data entry.
•	AI Chat-bot Integration for Real-Time Assistance
An AI-powered chat-bot is integrated into the website to assist users by answering queries, guiding them through course selection, and enhancing the overall user experience through instant support.
•	Functional Contact Form with Backend Validation
The Contact page includes a working contact form that collects user messages and sends them to the server using PHP. Backend validation ensures that only correct and complete information is stored or processed, improving reliability and preventing errors.
•	UI/UX Enhanced Pages with Visual Elements & Images
The user interface is improved through the use of high-quality images, consistent colour themes, custom CSS styling, and a clean layout. These enhancements make the website more engaging, modern, and easy to navigate.
 
Technology Stack 
Component	Technology
Frontend	HTML, CSS, JavaScript
Backend	PHP (XAMPP Server)
Database	MySQL
AI Integration	JavaScript-based Chat-bot
Tools	VS Code, Git, GitHub

Frontend Development
The frontend of the Educational & Digital Skills Website is designed with a focus on user experience (UX), visual appeal, and responsiveness. Modern web technologies—including HTML5, CSS3, and JavaScript—have been used to create interactive and visually engaging pages that ensure smooth navigation and usability.
The interface features clean layouts, structured content sections, smooth transitions, and subtle animations to enhance user engagement. High-quality images and icons are used throughout the site to create an image-based UI that aligns with contemporary design standards.
All pages—including Home, About, Courses, Contact, Signup, and Login—are fully responsive, ensuring they automatically adjust to different screen sizes such as desktops, tablets, and mobile devices. The CSS design includes flexible grids, media queries, and responsive components to provide a consistent viewing experience across all devices.
The frontend also incorporates interactive elements such as hover effects, animated buttons, dropdown menus, and dynamic content rendering, giving the website a professional and polished feel. Overall, the frontend development ensures a smooth, modern, and user-friendly interface optimized for performance and accessibility.
 
Backend Development
The backend of the Educational & Digital Skills Website was developed using PHP as the server-side scripting language and XAMPP as the local development environment. XAMPP provides an integrated setup of Apache Server, MySQL Database, and PHP, enabling smooth execution of backend operations throughout the project.
The backend is responsible for managing the core functionalities of the website, including:
•	User Authentication System
A secure login and signup module was implemented using PHP and MySQL. The system validates user credentials, stores registration details in the database, and ensures protected access to restricted pages. Input filtering and validation are applied to prevent invalid or malicious data submission.
•	Database Operations
MySQL is used to store and manage user data, contact form submissions, and other relevant records. CRUD operations (Create, Read, Update, Delete) are handled through PHP scripts, allowing efficient interaction between the website interface and the database.
•	Form Handling & Server-Side Validation
All forms—such as Signup, Login, and Contact Forms—are processed through backend PHP scripts. The backend verifies data accuracy, sanitizes inputs, provides error messages for incomplete fields, and ensures that only valid and properly formatted information reaches the database.
•	Secure Communication with MySQL
Database connectivity is established using prepared statements (where applicable) to enhance data security and reduce risks like SQL Injection. PHP functions are used to securely transmit and retrieve information from the MySQL database.
•	Backend File Structure Organization
Backend files are organized systematically into folders such as includes, config, and database to maintain clean project architecture. This structure supports easy maintenance, scalability, and clear separation of frontend and backend logic.
Overall, the backend development ensures reliable data processing, secure authentication, and smooth interaction between the user interface and the database, making the website functional, secure, and efficient.
 
Database Design 
Field	Type	Description
id	INT (Primary Key)	Unique identifier
email	VARCHAR(100)	User email
password	VARCHAR(255)	Hashed password
AI Chat-bot Integration
The Educational & Digital Skills Website integrates a JavaScript-based AI Chat-bot designed to enhance user interaction and provide instant support. This chat-bot serves as a virtual assistant, helping users navigate the platform, understand available courses, and receive quick responses to their queries.
The chat-bot is embedded directly into the website interface and remains accessible across pages, ensuring a seamless user experience. It is programmed to simulate natural conversation through predefined responses, conditional logic, and AI-driven interaction patterns. The interface is built with a clean, modern UI that includes a chat window, message bubbles, and automated response triggers.
Key functionalities of the chat-bot include:
•	Real-Time User Assistance
The chat-bot responds immediately to user questions, offering guidance related to course details, account creation, platform navigation, and general support.
•	Interactive Conversation Flow
The chat-bot uses scripted conversation paths and keyword detection to provide relevant answers. This allows users to receive accurate information without needing to browse multiple pages.
•	Enhanced User Engagement
By providing conversational support, the chatbot increases user involvement and reduces confusion, especially for beginners exploring the website.
•	Lightweight Design & Smooth Performance
Developed using JavaScript, HTML, and CSS, the chatbot is optimized for fast loading and smooth operation without affecting website performance. It is compatible with both desktop and mobile views.
•	Expandable Framework
The chat-bot’s code structure allows future upgrades, such as integrating APIs, adding machine learning responses, or connecting it with more advanced AI systems.
Overall, the AI Chat-bot serves as an intelligent, user-friendly tool that enriches the digital learning experience by offering real-time guidance, improving communication, and making the platform more interactive and accessible.
Screenshots
Home Page
 
The homepage introduces the e-Rozgaar Training Program, showcasing its core offering of digital and freelancing skills for youth. The layout includes key sections such as 'Home,' 'Courses,' 'About,' 'Register,' and 'Contact Us,' with a central focus on the program's empowering vision and a clear invitation for users to "Join Us.
 
Courses page 
 
This image shows the course catalog section of the e-Rozgaar website. Under the heading "Explore our Courses," two sample courses are featured: a "Basic IT Course" for fundamentals and a "C++" programming course. The page is designed to guide potential students toward contacting the program via the "Email Now" button.
Contact Us page 
 
A screenshot of the e-Rozgaar "Contact Us" page. The page provides the program's contact details, including an address, phone number, and email, alongside a functional contact form for users to send a message directly.
AI Integration
 
A screenshot showcasing the e-Rozgaar AI assistant interface. The chat-based tool, named "E-Rozgar assistant," introduces itself and lists the services it can provide, such as course information, enrollment guidance, and career opportunities, to support users interactively.

### Example Assistant Instruction

```text
You are the E-Rozgaar educational assistant. Help students and beginners
understand available digital-skills courses, enrolment procedures, course
duration, career opportunities and contact information. Use simple,
supportive and concise language. Give only information related to the
educational platform and guide users to the appropriate course or section.
