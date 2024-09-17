# Palindrome-Checker
Palindrome Checker A simple web-based application that checks whether a given word or phrase is a palindrome (reads the same forwards and backwards).

Features
Input a word or phrase to check if it's a palindrome.
Ignores case, spaces, and punctuation to perform the check.
Displays the result with a smooth animation.
Clean and responsive design.

Demo
Provide a live link to your GitHub Pages if you've deployed the project there, or add screenshots of the interface.

How to Use
Enter any word or phrase into the text input field.
Click the "Check" button.
The result will be displayed below the input field, indicating whether the entered text is a palindrome or not.

Technologies Used
HTML: Provides the structure of the page with input fields and buttons​(index).
CSS: Adds styling, animations, and a responsive layout for a clean user interface​(style).
JavaScript: Handles the logic for checking if the entered text is a palindrome, including removing spaces, special characters, and making the comparison case-insensitive​(script).

Code Explanation
JavaScript Functionality:
isPalindrome(str): Cleans the input string, removes special characters, and compares the original and reversed string.
palindromeChecker(): Handles the user input and displays the result.
