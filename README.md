# A2PASS INTRODUCTION

This script generates secure, random passwords with a specified length and optionally saves them to a file.

## Features

- Ensures the password includes at least one of each:
  - Lowercase letter
  - Uppercase letter
  - Digit
  - Special character
- Customizable password length (minimum 4 characters).
- Optionally saves the generated password to a file.

## How to Use

### Prerequisites
- Python 3 installed on your system.

### Steps

1. Save the script to a file (e.g., `A2Pass.py`).
2. Open a terminal or command prompt.
3. Run the script:
   ```bash
   python A2Pass.py
   ```

### Example Usage
- **Set Password Length**: Modify the `password_length` variable in the script to set the desired length of the generated password.
- **Save the Password**: When prompted, you can save the generated password to a file by entering `yes` and providing a file path.

#### Sample Execution
```bash
Generated Password: aB3!xR7&dY9#
Would you like to save the password to a file? (yes/no): yes
Enter the file path to save the password (default: password.txt): secure_password.txt
Password saved to /path/to/secure_password.txt
```

## Output

- The generated password will be printed in the terminal.
- If saved, the password will be written to the specified file (default: `password.txt`).

## Notes

- The default password length is 15 characters. Modify the `password_length` variable to change it.
- The script ensures strong password creation by including all character types and randomizing their order.
- If you encounter any issues saving the password, ensure you have the necessary permissions for the specified file path.

