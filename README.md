# Contact Book Application

Welcome ! 🎉
I'm excited to introduce you to our educational Qt/C++ desktop application, a fun way to simulate a contact management system complete with call tracking!  📞  This project was developed as part of the C++ programming course at the National Engineering School of Tunis (ENIT) and showcases key concepts in object-oriented programming, database management, and GUI development using the Qt framework.

Imagine a digital phone book  📚  where you can effortlessly manage your contacts and simulate calls (just a heads-up: this isn't a real calling app!). Our application features two user-friendly interfaces: one for Administrators 👩‍💼 and another for regular Users 👤. You'll find robust capabilities for managing contacts, tracking simulated calls, and even analyzing statistics. 📊

This project is not just practical—it's a fantastic learning opportunity for anyone interested in modern desktop application development!  🚀

## 📋 Features

### User Authentication
- Secure login system with role-based access (Administrator/User)
- Different interfaces and permissions for each role

### Administrator Features
- Manage contacts (Add, Delete, Display, Update)
- Initialize and reset contact data
- Full database management capabilities

### User Features
- Make and record calls
- Search contacts by name or phone number
- View call statistics
- Visualize call data through histograms

### Database Management
- SQLite-based data storage
- Efficient contact information management
- Call history tracking
- Secure user credentials storage

## 🔧 Technical Requirements

- Qt Creator (Latest version recommended)
- SQLite3
- C++ Compiler (Supporting C++11 or later)
- DB Browser for SQLite (Optional, for database management)

## 📥 Installation

1. Clone the repository:
```bash
git clone https://github.com/yassinomri/Contact-Book-.git
```

2. Open the project in Qt Creator:
- Launch Qt Creator
- Select "Open Project"
- Navigate to the cloned repository
- Select the `.pro` file

3. Configure the database:
- Ensure SQLite is properly installed
- The application will create the necessary database structure on first run
- Alternatively, use the provided SQL script to initialize the database

4. Build and run:
- Click the "Build" button in Qt Creator
- Run the application using the "Run" button

## 🗄️ Database Structure

The application uses three main tables:
- **Carnet**: Stores contact information (name, phone number, address, email)
- **Appel**: Records call details (caller name, start time, end time, duration)
- **Login**: Manages user authentication (username, password, role)

## 🔍 Class Structure

### Core Classes
- **dbconnexion**: Handles database connectivity
- **carnet**: Manages contact operations
- **contactDialog**: Handles contact interaction interface
- **AppelDialog**: Manages call-related operations
- **rechDialog**: Implements search functionality
- **Histogram**: Generates visual data representations
- **Stat**: Handles statistical calculations and display

## 🎯 Usage

### Administrator Access
1. Login with administrator credentials
2. Use the main interface to manage contacts
3. Access database management features

### User Access
1. Login with user credentials
2. Navigate through the four main tabs:
   - **Call**: Make and manage calls
   - **Search**: Find contacts
   - **Stats**: View call statistics
   - **Histogram**: Visualize call data

## 🛠️ Development

### Building from Source
```bash
qmake
make
```

### Contributing
1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 👥 Contributors

- Yassin OMRI
  Linkedin : linkedin.com/in/yassinomri

## 🙏 Acknowledgments

- ENIT (École Nationale d'Ingénieurs de Tunis)
- Department of Electrical Engineering

## Let’s Connect! 🤝
I'm always eager to share knowledge and connect with fellow developers! Feel free to reach out to me on LinkedIn and GitHub. I’m just beginning my journey in embedded software and would love to collaborate, learn, and grow together. Let’s build something amazing!

