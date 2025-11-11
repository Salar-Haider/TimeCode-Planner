# TimeCode Desktop App

*A software to help people make their weekly timetables and manage their activities on PC or laptop.*

---


## 🧐 Overview

TimeCode Desktop App is a Java-based desktop application built using Apache NetBeans IDE and the ANT build system. You can use it to create weekly timetables, track your activities, and manage your time more effectively while working on your PC or laptop. The application uses a backend database via Supabase to store your timetable data and activity logs.

Whether you are a student, professional, or simply someone who wants to organize their week, TimeCode helps you stay on top of your schedule.

---

## ✅ Features

* Create, view, and update weekly timetables.
* Add, edit, or delete activities/tasks for any time slot.
* Persist data to Supabase (online backend) so your timetable is saved.
* Simple and intuitive desktop UI built in Java.
* Works on PC or laptop (cross-platform as long as Java is installed).
* Modular code structure allows you to extend/adapt features easily.

---

## 🛠 Tech Stack

* **Language:** Java
* **IDE & Build System:** Apache NetBeans with ANT
* **Database / Backend:** Supabase (Postgres under the hood)
* **Platform:** Desktop (Windows / macOS / Linux with Java)

---

## 🧩 Installation & Setup

Follow these steps to get the project up and running:

1. **Clone the repository**

   ```bash
   git clone https://github.com/Salar-Haider/TimeCode-Project-DesktopApp.git  
   cd TimeCode-Project-DesktopApp  
   ```

2. **Set up Supabase backend**

   * Create a free account at Supabase and create a new project.
   * Set up the required database tables (e.g., users, timetables, activities) according to the schema in the `src` folder (if provided) or your design.
   * Obtain the Supabase URL and API key/credentials and set them in the application config.
     (You may need to edit a `config.properties` or similar file – search for “SUPABASE_URL” or “SUPABASE_KEY”.)

3. **Open the project in NetBeans**

   * Launch NetBeans, choose *Open Project*, and select the folder.
   * Make sure ANT build file (`build.xml`) is recognized.
   * Build the project (`Clean & Build`).

4. **Run the application**

   * Either run via NetBeans or locate the JAR file in the `dist` or `build` folder (e.g., `TimeCodeDesktopApp.jar`).
   * Execute:

     ```bash
     java -jar TimeCodeDesktopApp.jar  
     ```
   * The main UI should launch; connect to your Supabase backend.

5. **Using the app**

   * If first time, you might need to register/create a user (depending on implementation).
   * Add a weekly timetable, assign activities, save, and you’re good to go!

---

## 📁 Project Structure

Below is a high-level view of how the repository is organized:

```
TimeCode-Project-DesktopApp/
├─ JAR/                # Pre-built executable JARs (if present)  
├─ build/              # Build artifacts  
├─ images/             # Screenshots / UI images  
├─ nbproject/          # NetBeans project metadata  
├─ src/                # Java source code  
├─ test/               # Unit tests (if implemented)  
├─ LICENSE             # License file  
├─ README.md           # This file  
├─ build.xml           # ANT build script  
├─ manifest.mf         # Manifest (if packaged)  
```

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve the app (add features, fix bugs, improve UI), here’s how:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature/YourFeatureName`
3. Make your changes, commit with descriptive message.
4. Ensure code builds and runs correctly on your environment.
5. Submit a Pull Request with details of what you changed and why.
6. I will review and merge consistent changes.

Please ensure your code follows standard Java conventions and includes comments/documentation where necessary.

---

## 📜 License

This project is licensed under the [MIT License](./LICENSE).
You are free to use, modify, and distribute the software — see the license file for details.

---

## 📬 Contact

If you encounter any issues or have suggestions, feel free to open an issue in this repository or reach out to me via my GitHub profile: [@Salar-Haider](https://github.com/Salar-Haider).

Thanks for using TimeCode Desktop App — happy scheduling!

---

***Last updated:** November 12, 2025*
