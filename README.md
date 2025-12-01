 Notes App

A simple and beginner-friendly Notes App built using HTML, Tailwind CSS, and JavaScript.
This project helps you create, edit, delete, and store notes in the browser using localStorage, so your notes remain saved even after refreshing the page.

 Features
 Add Notes

User can type a note and save it instantly.

Delete Notes

Each note has a delete button to remove it permanently.

 LocalStorage Support

All notes remain saved in the browser even after closing the tab or refreshing the page.

 Responsive UI

Tailwind CSS ensures the interface looks clean and works on all device sizes.

 Auto Updating Notes List

Whenever a note is added or deleted, the note list updates instantly.

Technologies Used:
1. HTML : Structure of the app
2. Tailwind CSS : attractive UI
3. Javascript : Logic for adding, showing, and deleting notes
4. LocalStorage : Used for saving notes in the browser

Project Structure : 

index.html
Since this is beginner friendly project so everything is inside one file
Inside this file:

<style> contains Tailwind CDN + custom styling

<script> contains all JavaScript logic

HTML has the app layout

 How It Works (Detailed Breakdown)
1️.Adding a Note

The user types a note inside the input field.

When the user clicks "Add Note":

JS reads the input value

pushes the text into a notes array

saves the array in localStorage

refreshes the notes UI on the page

2️. Storing Notes

JavaScript converts the array into a JSON string:

localStorage.setItem("notes", JSON.stringify(notesArray));

3️. Loading Notes Automatically

Whenever you open the page, JS checks:

If notes exist in localStorage

If yes → loads them and shows on the screen

4️. Deleting a Note

Each note has a delete button:

Clicking delete removes the note from the array

Updates localStorage

Refreshes the list

  Future Improvements:

 Search notes

 Edit notes

 Dark mode

 Cloud sync (Firebase)

 Categories / tags

Download notes as a file
  
 Contributing

Since this is a beginner project, contributions are welcome!
You can improve UI, add new features, or optimize code.

Made By :
   Rishika Sinha
