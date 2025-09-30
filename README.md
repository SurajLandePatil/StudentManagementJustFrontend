

```
# 📚 Student Management System

A modern, responsive Angular-based student management application designed for educational institutions to efficiently manage student records with a clean and intuitive interface.

![Angular](https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

## ✨ Features

- ➕ **Add Students** - Complete registration form with validation
- 📋 **View Students** - Display all students in an organized table
- ✏️ **Edit Students** - Update student information seamlessly  
- 🗑️ **Delete Students** - Remove student records with confirmation
- 📱 **Responsive Design** - Works perfectly on all devices
- ✅ **Form Validation** - Real-time validation with error messages
- 🎨 **Modern UI** - Clean, professional interface with animations

## 🚀 Quick Start

### Prerequisites

- [Node.js](https://nodejs.org/) (v16 or higher)
- [Angular CLI](https://angular.io/cli) - `npm install -g @angular/cli`

### Installation

1. **Clone the repository**
   ```
   git clone https://github.com/yourusername/student-management-system.git
   cd student-management-system
   ```

2. **Install dependencies**
   ```
   npm install
   ```

3. **Run the application**
   ```
   ng serve
   ```

4. **Open your browser**
   Navigate to `http://localhost:4200`

## 📋 Student Form Fields

The application manages the following student information:

- **First Name** *(required)*
- **Last Name** *(required)*
- **Middle Name** *(optional)*
- **Roll Number** *(required)*
- **Class Name** *(required)*
- **Age** *(required, 15-100)*
- **Date of Birth** *(required)*
- **Gender** *(required - Male/Female/Other)*

## 🏗️ Project Structure

```
src/app/
├── components/
│   ├── student-form/     # Add/Edit student form
│   └── student-list/     # Student data table
├── models/
│   └── student.model.ts  # Student interface
├── services/
│   └── student.service.ts # CRUD operations
└── app.component.*       # Main application component
```

## 💻 Usage

### Adding a New Student
1. Click **"➕ Add Student"** in the navigation
2. Fill out the required fields
3. Click **"Add Student"** to save

### Viewing Students
- Click **"📋 View Students"** to see all records
- Students are displayed in a responsive table format

### Editing a Student
1. Click the **"✏️ Edit"** button next to any student
2. Modify the information in the pre-filled form
3. Click **"Update Student"** to save changes

### Deleting a Student
1. Click the **"🗑️ Delete"** button next to any student
2. Confirm deletion in the popup dialog

## 🛠️ Built With

- **Angular 16+** - Frontend framework
- **TypeScript** - Type-safe programming
- **HTML5 & CSS3** - Modern web standards
- **Template-driven Forms** - Angular forms with validation
- **Responsive Design** - Mobile-first approach

## 📱 Responsive Design

Optimized for all screen sizes:
- 📱 **Mobile** (320px+)
- 📱 **Tablet** (768px+)
- 💻 **Desktop** (1024px+)

## 🎨 UI Features

- Modern gradient backgrounds
- Smooth hover animations
- Glass morphism effects
- Professional color scheme
- Intuitive navigation
- Form validation feedback

## 🧪 Development

### Running Tests
```
ng test
```

### Building for Production
```
ng build --prod
```

### Code Scaffolding
```
ng generate component component-name
ng generate service service-name
```

## 📊 Sample Data

The application includes sample student data:
- **Rahul Kumar Sharma** - Computer Science, Roll: CSE001
- **Priya Devi Patel** - Computer Science, Roll: CSE002

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License


## 🙏 Acknowledgments

- Angular team for the amazing framework
- Open source community for inspiration
- Contributors and testers


⭐ **If this project helped you, please give it a star!** ⭐

## 📸 Screenshots


---<img width="1917" height="965" alt="Screenshot 2025-09-30 205031" src="https://github.com/user-attachments/assets/845599f0-1d4a-4453-9881-544c0a47668e" />


Made with ❤️ using Angular
```
