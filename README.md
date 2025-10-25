# 🕵️‍♂️ Criminal Record Database System

A simple Tkinter-based desktop application for managing criminal records. This project provides a graphical user interface (GUI) to view, search, add, update, and delete criminal data stored in a backend database.

This project is built using Python and Tkinter. It helps maintain criminal data efficiently through a user-friendly interface.

### Features
- View all criminal records  
- Search records by any field (Name, ID, Crime, etc.)  
- Add new entries  
- Update existing entries  
- Delete records  
- Displays a logo image and clean layout  
- Connects to a backend (back.py) for data operations  

### Project Structure
📂 CriminalRecordDatabase/
├── back.py # Handles database logic (CRUD operations)
├── main.py (or ui.py) # Tkinter GUI code
├── logo.gif # Logo displayed on the UI
└── README.md # Project documentation

### Requirements
- Python 3.x  
- Tkinter (usually comes pre-installed)  
- sqlite3 (optional, built-in with Python)

### How to Run
1. Clone or download this repository.  
2. Place all files (back.py, logo.gif, and main.py) in the same folder.  
3. Open the folder in your terminal or command prompt.  
4. Run the program:
   ```bash
   python main.py
