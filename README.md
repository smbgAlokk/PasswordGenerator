## Password Generator

This project is a customizable password generator built using ReactJS with Vite. It allows users to create strong and secure passwords with a variety of options for length and character types.

## Features

Dynamic Password Length:

Users can set the length of the password using a slider, ranging from 6 to 100 characters.

Character Options:

Include Numbers: Option to include numerical digits (0-9) in the password.

Include Special Characters: Option to include special characters like !@#$%^&*()_-+=[]{}~/?|` for enhanced password strength.


A "copy" button allows users to easily copy the generated password to their clipboard for convenient use.

## Real-time Password Update:

The password is updated in real-time whenever the length or character options are changed.
Installation

## @Clone the repository:

git clone https://github.com/smbgAlokk/PasswordGenerator.git
cd PasswordGenerator
## Install dependencies:

npm install

## Start the development server:

npm run dev

## Open the app in your browser:

http://localhost:5173

## Usage

Adjust the length slider to set the desired password length (6 to 100 characters).

Select options to include numbers and special characters by checking the respective checkboxes.

The generated password is displayed in the input box. Click the Copy button to copy the password to your clipboard.

## Technologies Used

ReactJS: JavaScript library for building user interfaces.

Vite: A fast build tool for modern web projects.

## Project Structure

src/

├── App.jsx          # Main component with password generation logic
├── index.css        # Styling for the app
└── main.jsx         # Entry point for the React app
