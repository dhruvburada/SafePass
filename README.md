# SafePass - Password Manager

## Overview

This Password Manager is a desktop application built using C# .NET and Windows Forms. It allows users to securely store and manage their passwords. The application is protected by a master password and encrypts all sensitive data using strong encryption algorithms like Rijndael/AES, ensuring the privacy and security of your stored passwords.

## Features

1. **Master Password Protection:**
   - The application is secured by a master password. Users need to authenticate using this master password to access their stored passwords.

2. **Encryption:**
   - All passwords are encrypted using Rijndael (AES) encryption algorithm, ensuring that the sensitive data is stored securely.

3. **Password Generation:**
   - The application can generate strong, random passwords based on user preferences (including length, special characters, numbers, etc.).

4. **CRUD Operations:**
   - Users can Create, Read, Update, and Delete (CRUD) their stored passwords. The interface is designed to be user-friendly, allowing easy management of credentials.

5. **Password Search:**
   - Users can search for passwords based on different criteria, such as by name, email, username, or website.

6. **Export and Import:**
   - Passwords can be exported and imported securely, allowing users to back up their data or transfer it between devices.

7. **Data Persistence:**
   - All data is persisted securely, either locally in encrypted form or via import/export mechanisms.

## Getting Started

### Prerequisites

- **.NET Framework**: Ensure that you have .NET Framework 4.6 or higher installed on your system.
- **Windows OS**: The application is designed to run on Windows operating systems.

### Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-repo/password-manager.git
   ```

2. **Build the Application:**
   - Open the solution file (`PasswordManager.sln`) in Visual Studio.
   - Build the project using `Build > Build Solution` or by pressing `Ctrl + Shift + B`.

3. **Run the Application:**
   - After building, run the application by selecting `Debug > Start Debugging` or pressing `F5`.

### Usage

1. **Login with Master Password:**
   - Upon launching the application, you will be prompted to enter a master password. If it's your first time using the application, you will need to set a new master password.

2. **Manage Passwords:**
   - After logging in, you can start adding, viewing, editing, or deleting your stored passwords. The user interface includes a grid view that displays your stored credentials.

3. **Generate Passwords:**
   - Use the password generator feature to create secure and strong passwords based on your selected criteria.

4. **Export/Import Passwords:**
   - You can export your encrypted passwords to a file for backup purposes or import them later when needed.

### Security Details

- **Encryption Algorithm**: Rijndael (AES) encryption is used to secure all stored passwords.
- **Master Password**: The master password is required to access the application and decrypt the stored passwords.
- **Password Encryption**: All passwords are encrypted before being saved in the database or a file and decrypted only during display or export.

### Customization

The application can be customized for different encryption methods, UI themes, or storage options (e.g., cloud-based storage).


## Contributing

Feel free to contribute to this project by submitting pull requests, reporting bugs, or suggesting new features.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
