# 📞 Simple Phonebook Program in Python

This is a simple Python program that allows users to store names and phone numbers, and then search for a contact by name.

## 🧠 Features

- Add multiple contacts (name and phone number)
- View all saved contacts in a formatted way
- Search for a contact by name
- Displays the contact information if found, else notifies if not found

## 🚀 How to Run

1. Make sure Python is installed on your system.
2. Save the script as `phonebook.py`.
3. Open your terminal and run:

```bash
python phonebook.py
```

## 💡 How It Works

- The user is prompted to enter how many contacts they want to add.
- Then the user enters each name and corresponding phone number.
- The data is stored in two lists: `names` and `phone_numbers`.
- After data entry, all contacts are printed in tabular format.
- Finally, the user can enter a name to search for, and the program will display the phone number if found.

## 📝 Sample Output

```
Enter number : 2
Name: Alice
Phone Number: 1234567890
Name: Bob
Phone Number: 9876543210

Name             Phone Number

Alice            1234567890
Bob              9876543210

Enter search term: Bob
Search result:
Name: Bob, Phone Number: 9876543210
```

## 📌 Requirements

- Python 3.x

## 📂 File Structure

```
📦Phonebook-Project
 ┣ 📄 phonebook.py
 ┗ 📄 README.md
```

## 📬 Feedback

Feel free to fork this repo, improve it, and raise pull requests. If you find it useful, give it a ⭐!

---

Made with ❤️ in Python.