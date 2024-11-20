# Bookstore Program 📚

A lightweight and efficient program to manage book records. This tool allows users to store and manage book information such as the title, author, publication year, and ISBN.

## Features 🚀

- **View All Records**: Display a complete list of stored books.
- **Search Entries**: Search for a book by title, author, year, or ISBN.
- **Add New Entry**: Add details for a new book to the database.
- **Update Existing Entry**: Modify information about an existing book.
- **Delete Entry**: Remove a book from the database.
- **Close Program**: Exit gracefully.

## Getting Started 🛠️

Follow these steps to set up and run the program on your machine.

### Prerequisites

- Python 3.x installed on your machine
- Libraries used:
    - `tkinter`: For the graphical user interface (GUI).
    - `sqlite3`: For database handling.
        
        Both tkinter and sqlite3 are included by default with Python—no additional installation is required.

### Installation

1. Clone the repository:
   ```
   git clone https://github.com/kingamal/tkinter.git
   cd [folder_name]
   ```

2. Install dependencies if you want to have an executive file:
   ```
   pip install -r requirements.txt
   ```

3. Generate executable:
   ```
   pyinstaller --onefile --windowed bookstore.py
   ```

- **--onefile**: Packages the entire program into a single executable file.
- **--windowed**: Ensures no console window appears when running the program (useful for GUI apps).
   
4. Run the program:
   ```
   python bookstore.py
   ```
   or simply open executive file and enjoy!


