# Password Manager

A simple password manager built with Python and Tkinter. This application generates secure passwords, allows you to store them with associated websites and emails, and saves the data to a text file for future reference.

## Features

- Generates a random, secure password
- Saves website, email, and password details to `data.txt`
- Copies the generated password to the clipboard
- Prompts if any fields are left empty before saving

## Installation

1. Clone this repository.
2. Install the required packages:
   ```bash
   pip install pyperclip
   ```
3. Run the `password_manager.py` file:
   ```bash
   python password_manager.py
   ```

## Usage

1. **Enter the Website**: Type in the name of the website.
2. **Enter the Email/Username**: Type in the email or username associated with the website.
3. **Generate Password**: Click the "Generate Password" button to create a strong password, which will be automatically copied to your clipboard.
4. **Save Entry**: Click "Add" to save the information to `data.txt`.

### Example

![image](https://github.com/user-attachments/assets/40a54089-ac66-4101-b640-c9a7f1353db4)

After clicking "Add," your entry will be saved as:
```
GitHub | example@gmail.com | password123!
```
Let me know if you’d like any more details added!
