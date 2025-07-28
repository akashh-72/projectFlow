# ProjectFlow - Project Management Application

A modern, responsive project management application built with HTML, CSS, JavaScript, and Firebase. ProjectFlow helps you organize tasks, capture ideas, and track project progress with a beautiful, intuitive interface.

## 🌟 Features

### 🔐 Authentication System
- **Secure Login/Signup**: Firebase Authentication with email/password
- **User Profiles**: Individual user accounts with personalized data
- **Session Management**: Automatic login state management
- **Secure Logout**: Safe session termination

### 📊 Project Management
- **Project Creation**: Create and manage multiple projects
- **Task Management**: Add, edit, and organize tasks with drag-and-drop
- **Progress Tracking**: Visual progress indicators and analytics
- **Idea Capture**: Store and promote ideas to tasks
- **Real-time Sync**: Live updates across all devices

### 🎨 User Interface
- **Modern Design**: Clean, professional interface with smooth animations
- **Dark/Light Theme**: Toggle between themes with persistent settings
- **Responsive Layout**: Works perfectly on desktop, tablet, and mobile
- **Interactive Elements**: Hover effects, transitions, and visual feedback

### 📈 Analytics
- **Task Status Charts**: Visual representation of task distribution
- **Priority Analysis**: Track tasks by priority levels
- **Progress Metrics**: Real-time project completion statistics

## 🚀 Getting Started

### Prerequisites
- A modern web browser (Chrome, Firefox, Safari, Edge)
- Firebase project with Authentication and Realtime Database enabled

### Installation
1. Clone or download the project files
2. Open `login.html` in your web browser
3. Create a new account or sign in with existing credentials
4. Start managing your projects!

### File Structure
```
projectFlow/
├── index.html          # Main application
├── login.html          # Authentication page
└── README.md           # This file
```

## 🔧 Firebase Configuration

The application uses Firebase for:
- **Authentication**: User login/signup
- **Realtime Database**: Project and task data storage

### Required Firebase Services
1. **Authentication**: Enable Email/Password sign-in method
2. **Realtime Database**: Set up database rules for user data

### Database Structure
```
users/
├── {userId}/
│   ├── uid: string
│   ├── name: string
│   ├── email: string
│   ├── createdAt: timestamp
│   └── projects/
│       ├── {projectId}/
│       │   ├── id: string
│       │   ├── name: string
│       │   ├── description: string
│       │   ├── dueDate: string
│       │   ├── tasks/
│       │   │   └── {taskId}/
│       │   │       ├── id: string
│       │   │       ├── title: string
│       │   │       ├── details: string
│       │   │       ├── priority: string
│       │   │       ├── status: string
│       │   │       └── deadline: string
│       │   └── ideas/
│       │       └── {ideaId}/
│       │           ├── id: string
│       │           ├── title: string
│       │           └── description: string
```

## 🎯 How to Use

### Authentication
1. **Sign Up**: Create a new account with email and password
2. **Sign In**: Use your credentials to access your projects
3. **Profile Management**: Access user profile and settings from the navbar
4. **Sign Out**: Safely log out from the dropdown menu

### Project Management
1. **Create Project**: Click "New Project" to add a new project
2. **Add Tasks**: Use the "Add Task" button in the To-Do column
3. **Organize Tasks**: Drag and drop tasks between columns (To-Do, In-Progress, Done)
4. **Track Progress**: View real-time progress bars and analytics
5. **Capture Ideas**: Add ideas and promote them to tasks when ready

### Features Overview
- **Dashboard**: Overview of all projects with progress indicators
- **Project Detail**: Detailed view with tasks, ideas, and analytics
- **Task Board**: Kanban-style board for task management
- **Analytics**: Charts showing task distribution and priorities
- **Search**: Find projects quickly with the search functionality

## 🎨 Customization

### Themes
- Toggle between light and dark themes using the theme switch
- Theme preference is saved in localStorage
- Consistent theming across all components

### Styling
- Built with Bootstrap 5 for responsive design
- Custom CSS variables for easy theming
- Material Icons for consistent iconography
- Smooth animations and transitions

## 🔒 Security Features

- **User Authentication**: Secure login with Firebase Auth
- **Data Isolation**: Each user's data is isolated by user ID
- **Input Validation**: Form validation and data sanitization
- **Error Handling**: Comprehensive error handling and user feedback

## 📱 Responsive Design

The application is fully responsive and works on:
- **Desktop**: Full-featured experience with all capabilities
- **Tablet**: Optimized layout for medium screens
- **Mobile**: Touch-friendly interface with simplified navigation

## 🛠️ Technical Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **UI Framework**: Bootstrap 5
- **Icons**: Material Icons
- **Charts**: Chart.js
- **Backend**: Firebase
- **Authentication**: Firebase Auth
- **Database**: Firebase Realtime Database

## 🚀 Future Enhancements

- [ ] User profile management
- [ ] Project sharing and collaboration
- [ ] File attachments for tasks
- [ ] Email notifications
- [ ] Advanced analytics and reporting
- [ ] Project templates
- [ ] Time tracking
- [ ] Mobile app version

## 🤝 Contributing

Feel free to contribute to this project by:
- Reporting bugs
- Suggesting new features
- Submitting pull requests
- Improving documentation

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

## 🆘 Support

If you encounter any issues or have questions:
1. Check the browser console for error messages
2. Ensure Firebase is properly configured
3. Verify your internet connection
4. Try refreshing the page

---

**ProjectFlow** - Streamline your project management workflow with style and efficiency! 🚀 