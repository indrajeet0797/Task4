# Task4
Simple Notes Manager – Java File I/O Project

Overview:
This is a simple command-line based Notes App using Java’s File I/O capabilities to store and retrieve notes in a local file (notes.txt).

Features:
- Add a new note
- View all saved notes
- Exit the application
- Stores notes in a text file using FileWriter and reads them using BufferedReader

How to Compile and Run:
1. Save the code in a file named: NotesManager.java
2. Open a terminal or command prompt
3. Navigate to the directory containing the file
4. Compile the Java file:
   javac NotesManager.java
5. Run the application:
   java NotesManager

Code Explanation:
- FILE_NAME is a constant holding the file name "notes.txt".
- Scanner is used to take input from the user.
- A do-while loop shows the menu until the user chooses to exit.
- addNote() reads a note from the user and writes it to the file using FileWriter in append mode.
- viewNotes() reads and displays all the notes using BufferedReader.

Sample Output:
1. Add Note
2. View Notes
3. Exit
Enter your choice: 1
Enter your note: Buy groceries
Note added successfully.

1. Add Note
2. View Notes
3. Exit
Enter your choice: 2

=== Your Notes ===
1. Buy groceries


