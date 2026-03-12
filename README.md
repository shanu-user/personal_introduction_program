# Personal Introduction Program

This is a beginner Python program that collects basic information from the user and displays a friendly welcome message.

## 📌 Project Description

The program asks the user a few simple questions such as:

- Name
- Age
- Favorite hobby

After collecting the responses, the program generates a personalized welcome message using the provided information.

## 🛠 Features

- Uses `input()` to collect user information
- Stores responses in variables
- Uses formatted strings (`f-strings`) to create a personalized message
- Provides a friendly output message

## 📋 Questions Asked

The program asks the following questions:

1. What is your name?
2. How old are you?
3. What is your favorite hobby?

## ▶️ How to Run the Program

1. Make sure Python is installed on your system.
2. Clone the repository.


## Setup Instructions

Follow these steps to run the project:

1. Install Python (version 3.x recommended).
2. Download or clone the repository.

git clone <repository_link>

3. Navigate to the project directory.

cd personal-intro-program

4. Run the program.

python personal_intro.py


## Code Structure

The repository contains the following files:

personal-intro-program/
│
├── personal_intro.py   # Main Python script that collects user input
├── README.md           # Project documentation
├── requirements.txt    # Lists dependencies (none required)
└── screenshot.png      # Screenshot of program execution

## Technical Details

The program uses basic Python concepts:

Input Handling  
The `input()` function is used to collect responses from the user.

Variables  
User responses are stored in variables such as `name`, `age`, and `hobby`.

String Formatting  
The welcome message is generated using Python f-strings to insert user data into the output message.

Example:

print(f"Welcome {name}! You are {age} years old and love {hobby}.")
