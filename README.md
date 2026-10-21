# 📇 Contact Manager

A Python-based Contact Manager application with a graphical user interface (GUI) built using Tkinter. It allows users to manage contact information through a simple interface, with contact details stored persistently in a text file.

## ✨ Features

- **Add Contacts:** Save a contact's name, phone number, email, address, and other supported details.
- **View Contacts:** Display saved contacts in an organized interface.
- **Search Contacts:** Find contacts using available search options.
- **Update Contacts:** Modify existing contact information.
- **Delete Contacts:** Remove contacts that are no longer needed.
- **Persistent Storage:** Store contact records in `contacts.txt`.
- **Input Validation:** Validate required fields before saving.
- **Duplicate Detection:** Help identify duplicate or similar contacts.
- **Dashboard:** View contact statistics supported by the application.
- **User-Friendly Interface:** Interact with contacts through a graphical interface instead of a command-line menu.

## 🛠️ Technologies Used

- **Python 3**
- **Tkinter** for the graphical user interface
- **CSV module** for reading and writing text-file records
- **Pathlib** for file path management

## 📁 Project Structure

```text
ContactManager/
│
├── main.py
├── contacts.txt
├── README.md
│
├── database/
│   └── contact_db.py
│
├── core/
│   ├── contact_service.py
│   ├── duplicate_service.py
│   └── analytics_service.py
│
├── ui/
│   ├── main_window.py
│   ├── dashboard_view.py
│   ├── add_contact_view.py
│   ├── view_contacts_view.py
│   ├── search_view.py
│   ├── update_contact_view.py
│   └── delete_contact_view.py
│
├── theme/
│   └── theme_manager.py
│
└── utils/
    ├── dialogs.py
    ├── exporter.py
    └── importer.py
```

*Note: The exact files and folders may vary depending on the version of the project.*

## ⚙️ Requirements

- Python 3 installed on your system
- Tkinter available with your Python installation
- No external packages are required for the basic application if all modules use Python's standard library.

## 🚀 Installation and Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Replace `YOUR_GITHUB_REPOSITORY_URL` with your actual GitHub repository URL.

### 2. Open the project directory

```bash
cd ContactManager
```

### 3. Run the application

```bash
python main.py
```

On some systems, use:

```bash
python3 main.py
```

## 💾 Data Storage

The application stores contact details in a plain-text file named `contacts.txt`, using CSV formatting.

The file is created automatically when the application initializes the storage system. Contact records can be read when the application starts again, allowing saved contacts to persist between sessions.

Example format:

```text
id,name,phone,email,address,favorite,tags,created_at
1,Megha,9876543210,megha@example.com,Delhi,0,Friend,2026-10-22T10:00:00
```

The example above is illustrative. Actual records depend on the fields saved by the application.

## 📚 Learning Objectives

This project demonstrates practical use of:

- Python variables, functions, and modules
- File handling and persistent storage
- Reading and writing CSV-formatted text files
- Conditional statements and exception handling
- GUI development with Tkinter
- CRUD operations: Create, Read, Update, and Delete
- Basic input validation and search functionality

## 🔒 Privacy Note

Contact information is stored in a plain-text file. Do not store sensitive personal information in this project, and avoid committing real contact details to a public GitHub repository.

## 👨‍💻 Author

**Megh Jaiswal**

A Python project developed to practice file handling, GUI development, and contact management functionality.

## 📄 License

This project is available for educational and learning purposes. Add a license file if you intend to distribute it under specific reuse terms.
