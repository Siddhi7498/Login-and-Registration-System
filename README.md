# Login-and-Registration-System
This C++ code is a simple console-based program for user registration and login, which reads and writes user data to a file.
1. User Prompt: The program starts by prompting the user to choose between signing up (1) or logging in (2).
2. Sign Up Process:The user is prompted to enter a username and password.It checks the length of the username (3 to 16 characters) and the password (4 to 32 characters).The program verifies if the username is already taken by checking the "Login_Info.txt" file.If the username is unique, it writes the username and password to the file and confirms the registration.
3. Login Process:The user is prompted to enter a username and password.It checks the length of the username and password to ensure they meet the specified requirements.The program reads the "Login_Info.txt" file to verify if the entered username and password match any existing entries.If the credentials match, the user is welcomed; otherwise, an error message is displayed.
4. Error Handling:The program includes basic error handling for invalid inputs and file access errors, displaying appropriate error messages and exiting if any issue is encountered
