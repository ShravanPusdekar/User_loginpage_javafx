# JavaFX User Dashboard App

A simple JavaFX desktop application featuring user authentication, role-based access, and profile management.

## 🔑 Features
- Login system with role support (Admin/User)
- Dashboard with personalized welcome and status
- Profile editing with email and password update
- Clean, modular JavaFX UI using scenes and layout managers

## 🧰 Tech Stack
- Java 11+
- JavaFX SDK
- IntelliJ IDEA (or any Java IDE)

## 🧱 Setup Instructions
1. **Install Java 11+** and [JavaFX SDK](https://gluonhq.com/products/javafx/)
2. **Configure JavaFX in IntelliJ:**
   - Go to: `Run > Edit Configurations`
   - Add VM options:
     ```
     --module-path /path/to/javafx-sdk/lib --add-modules javafx.controls,javafx.fxml
     ```
3. **Run `temp.java`** as JavaFX application

## 👥 Default Users
| Username | Password | Role          |
|----------|----------|---------------|
| admin    | 1234     | Administrator |
| user     | pass     | Standard User |

## 🧠 Project Structure
- `temp.java` – Main application file (contains logic for login, dashboard, and profile scenes)

## 📄 License
MIT License. Free to use and modify.
