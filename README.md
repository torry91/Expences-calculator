# Calculator

## Overview
This simple web application helps users calculate the amount to pay per person, including a tip, based on the total bill and the number of people. Users can also choose to add a tip percentage. The application utilizes JavaScript for the calculation logic and integrates SweetAlert2 for user-friendly alert messages.
<img width="1221" alt="Screenshot 2024-01-27 at 20 30 20" src="https://github.com/torry91/Expences-calculator/assets/149702982/506e224a-3a79-4159-b12c-6d370655ffea">


## Features
Calculate Amount: Users can input the total bill amount, the number of people, and optionally add a tip percentage. The application calculates and displays the amount to pay per person, the tip amount per person, and the total amount per person.

Input Validation: The application checks for valid inputs, ensuring that the bill amount and the number of people are provided and that the number of people is greater than zero.

Tip Option: Users can choose to add a tip percentage to the total bill, distributing it equally among the specified number of people.

## Usage
Enter the total bill amount in the "Bill" input field.
Enter the number of people sharing the bill in the "Number of People" input field.
Optionally, input the tip percentage in the "Tip Percentage" input field.
Click the "Calculate" button to see the amount to pay per person, tip per person, and the total amount per person.
Click the "Add Tip" button to display the tip input field if you want to add a tip after the initial calculation.

## Implementation
HTML: Contains the structure of the application, including input fields, buttons, and result displays.
JavaScript: Implements the calculation logic, handles user input, and displays result messages.
SweetAlert2: Utilized for visually appealing and customizable alert messages. (SweetAlert2 GitHub)

## Dependencies
SweetAlert2: A JavaScript library for creating beautiful and responsive modal dialogs.

## Notes
The application ensures that the number of people is greater than zero and that all necessary information is provided before performing calculations.
Users can choose to add a tip after the initial calculation by clicking the "Add Tip" button.
Enjoy calculating and splitting bills with ease!
