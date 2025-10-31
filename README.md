# EatEase

A feature-rich recipe management desktop application built with JavaFX, designed to help users discover, organize, and manage their favorite recipes with an intuitive graphical interface.

## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies](#technologies)
- [Getting Started](#getting-started)
- [Project Structure](#project-structure)
- [Usage](#usage)
- [Contributors](#contributors)

## 🎯 Overview

EatEase is a comprehensive recipe management system developed as the final project for CSYE6200 (Concepts of Object-Oriented Design) at Northeastern University. The application provides a seamless experience for users to browse through a curated collection of recipes, create their own culinary creations, and manage their favorites in a user-friendly desktop environment.

## ✨ Features

### User Authentication
- **Secure Login System**: Role-based authentication with User and Admin accounts
- **User Registration**: New users can create accounts with username and password
- **Account Management**: Users can manage their profile information

### Recipe Management
- **Recipe Browser**: Browse through 22+ pre-loaded recipes across multiple categories
- **Recipe Categories**: 
  - Main Dishes (e.g., Hawaiian Pizza, Paella, Broccoli Alfredo Pasta)
  - Desserts (e.g., Tiramisu, Chocolate Lava Cake, Churros, Cheesecake)
  - Soups (e.g., Polish Potato Soup)
  - Appetizers (e.g., Holiday Potatoes, Eggplant Appetizer)
  - Drinks (e.g., Sweet Lime Iced Tea, South Carolina Sweet Tea)
- **Detailed Recipe View**: Each recipe includes:
  - Name and category
  - Complete ingredients list
  - Step-by-step cooking directions
  - Recipe images
- **Create New Recipes**: Users can add their own recipes to the collection
- **Favorites System**: Mark and track your favorite recipes

### Admin Features
- **Recipe Administration**: Admins can manage the entire recipe database
- **User Account Management**: Administrative controls for user accounts

## 🛠 Technologies

- **Java**: Core programming language
- **JavaFX**: GUI framework for desktop application
- **FXML**: UI markup for scene design
- **CSS**: Styling for application interface
- **Object-Oriented Design**: Following OOP principles and design patterns

## 🚀 Getting Started

### Prerequisites
- Java Development Kit (JDK) 8 or higher
- JavaFX SDK
- IDE (Eclipse, IntelliJ IDEA, or similar)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/jiaye2001/EatEase.git
```

2. Open the project in your preferred IDE

3. Configure JavaFX in your IDE:
   - Add JavaFX SDK to your project libraries
   - Set up VM arguments if necessary

4. Build and run the project:
   - Main class: `application.Main`
   - Run configuration should point to the Main.java file

### Default Login Credentials

**User Account:**
- Username: `Mark`
- Password: `123`

**Admin Account:**
- Username: `Admin`
- Password: `123`

## 📁 Project Structure

```
EatEase/
├── src/
│   ├── application/
│   │   ├── Main.java                    # Application entry point
│   │   ├── Configure.java               # Data initialization and management
│   │   ├── Recipe.java                  # Recipe model class
│   │   ├── User.java                    # User model class
│   │   ├── Admin.java                   # Admin model class
│   │   ├── Person.java                  # Base person class
│   │   ├── MainController.java          # Main controller logic
│   │   ├── LoginPage.fxml               # Login page UI
│   │   ├── SignUpPage.fxml              # Registration page UI
│   │   ├── User_home.fxml               # User home interface
│   │   ├── Admin_home.fxml              # Admin home interface
│   │   ├── CreateRecipe.fxml            # Recipe creation form
│   │   ├── CreateRecipeController.java  # Recipe creation logic
│   │   ├── RecipeShow.fxml              # Recipe detail view
│   │   ├── RecipeShowController.java    # Recipe display logic
│   │   ├── ManageRecipe.fxml            # Recipe management UI
│   │   ├── ManageRecipeController.java  # Recipe management logic
│   │   ├── ManageAccount.fxml           # Account management UI
│   │   ├── ManageAccountController.java # Account management logic
│   │   └── application.css              # Application styling
│   └── image/                            # Recipe images directory
└── bin/                                  # Compiled classes
```

## 💡 Usage

### For Users

1. **Login/Registration**
   - Launch the application to access the login screen
   - Sign in with existing credentials or create a new account
   - New users will have standard user privileges

2. **Browse Recipes**
   - Navigate through the recipe collection from the home screen
   - Filter recipes by category
   - Click on any recipe to view full details

3. **View Recipe Details**
   - Access complete ingredient lists
   - Read step-by-step cooking directions
   - View recipe images for reference

4. **Create Recipes**
   - Click "Create Recipe" to add your own recipes
   - Fill in recipe name, type, ingredients, and directions
   - Upload images for your recipes

5. **Manage Favorites**
   - Mark recipes as favorites for quick access
   - Build your personal collection of preferred recipes

### For Administrators

1. **Recipe Management**
   - Access admin panel for full recipe database control
   - Edit existing recipes
   - Remove recipes from the collection

2. **User Management**
   - View registered users
   - Manage user accounts and permissions

## 👥 Contributors

This project was developed as a collaborative effort for CSYE6200 at Northeastern University, Fall 2024.

**Team Members:**
- **Irene Chiang** - chiang.i@northeastern.edu
- **Jiaye Lee** - lee.jiay@northeastern.edu
- **Weichun Liu** - liu.weichu@northeastern.edu
- **Yushan Zou** - zou.yush@northeastern.edu

## 📝 Course Information

**Course:** CSYE6200 - Concepts of Object-Oriented Design  
**Institution:** Northeastern University  
**Semester:** Fall 2024  
**Project Type:** Final Project

## 🙏 Acknowledgments

- Northeastern University CSYE6200 teaching staff for project guidance
- JavaFX community for documentation and resources
- All team members for their contributions and collaboration

---

**Note:** This is an educational project developed for academic purposes.