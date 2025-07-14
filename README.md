📝 Personal Diary App (Terminal Version)

Welcome to the Personal Diary App, a secure and easy-to-use diary you can run entirely in your terminal.
It lets users create, view, search, delete, and filter diary entries by category or date — all while managing user accounts with bcrypt-hashed passwords.
🚀 Features

    User Registration
    New users can register with a username and password (password is visible while typing).

    User Login
    Existing users can log in (password is hidden using asterisks or dots).

    Secure Passwords
    Passwords are hashed with bcrypt and stored securely in users.txt.

    Diary Entries

        Write, view, search, and delete entries

        Add timestamps and categories

        Filter by category or keyword

    No UI
    Everything runs in the terminal. No GUI. No web. Just clean keyboard-driven interaction.

📁 Project Structure
File/Folder	Purpose
auth.py	Handles registration, login, and password hashing
diary.py	Core diary functionality: writing, reading, filtering
users.txt	Stores usernames and bcrypt-hashed passwords
entries/	Folder containing diary entry files (one per user)

🛠 Getting Started

Install dependencies

    pip install bcrypt

Run the app

    python main.py

Register or log in, then start writing your entries.

📝 Notes

    Ensure users.txt exists in the same folder (can be empty initially).

    Entries are saved per user inside the entries/ folder.

    Each entry includes a timestamp and optional category.

    Runs entirely in the terminal — no mouse, no web.

📬 Contributing

Want to improve it? Add a feature? Build a GUI?
Fork the repo and open a pull request — contributions are welcome.
