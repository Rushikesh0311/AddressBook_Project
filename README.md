# AddressBook_Project
<!-- Stylish Header -->
<h1 align="center">📒 Address Book in C</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Language-C-blue.svg" alt="Language"/>
  <img src="https://img.shields.io/badge/Concept-File Handling-yellow.svg" alt="File Handling"/>
  <img src="https://img.shields.io/badge/Topic-Data Structures-orange.svg" alt="Data Structures"/>
  <img src="https://img.shields.io/badge/IDE-VS Code-lightgrey.svg" alt="IDE"/>
</p>

<p align="center">
  <b>Developed by <a href="https://github.com/Rushikesh0311">Rushikesh Gore</a></b>  
</p>

---

## 🧩 Overview
A **simple Address Book application in C** that allows users to **store, search, edit, and delete contacts** using file handling.  
All records are stored permanently in a `.csv` or `.txt` file, making it a great example of persistent storage without using databases.

---

## 📘 Project Overview
- Manage a list of contacts (Name, Phone, Email).  
- File handling for permanent data storage.  
- Menu-driven interface for user-friendly navigation.  
- Modular structure using separate functions for each operation.  

---

## 🌟 Features
✅ Add new contacts  
✅ Display all contacts  
✅ Search contact by name  
✅ Edit or delete contact  
✅ Store data permanently using files  
✅ Clear and beginner-friendly structure  

---

## 📂 File Structure
```
AddressBook/
│
├── addressbook.c         # Main source file
├── AddressBook.csv       # File for storing contact records
├── README.md             # Project documentation

```

---

## 🗂️ Data Format (contacts.dat)
Each record is stored in the file in this structure:

| Field | Type | Description |
|-------|------|-------------|
| Name  | String | Contact’s Name |
| Phone | String | Contact’s Phone Number |
| Email | String | Contact’s Email ID |

---

## ⚙️ Build and Run
### ▶️ Compile the Program
```bash
gcc addressbook.c -o addressbook
```

### ▶️ Run the Executable
```bash
./addressbook
```

---

## 🖥️ Output
```bash
========= ADDRESS BOOK =========
1. Add Contact
2. Display Contacts
3. Search Contact
4. Edit Contact
5. Delete Contact
6. Exit
===============================
Enter your choice:
```

Example Output:
![App Screenshot](assets/output.png)

---

## 💡 Ideal For
- Students learning **File Handling in C**  
- Mini Projects in **C Programming**  
- Understanding **Record Management using Files**  
- Practicing **modular design and struct usage**

---

## 🧠 Key Concepts Used
- File Handling (`fopen`, `fread`, `fwrite`, `fclose`)  
- Structures (`struct Contact`)  
- Loops and Conditional Statements  
- Functions and Modular Programming  

---

## 🧰 Tools & Environment
- **Language:** C  
- **Compiler:** GCC  
- **IDE Used:** VS Code / Code::Blocks  
- **OS Tested On:** Windows / Linux  

---

## 👨‍💻 Author
**Rushikesh Gore**  
📧 rushikeshgore0309@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/rushikeshgore11) | [GitHub](https://github.com/Rushikesh0311)

---



