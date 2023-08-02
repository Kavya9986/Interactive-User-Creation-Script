# Interactive User Creation Script

The "Interactive User Creation Script" is a bash script designed to facilitate the creation of new users in a Linux-based system. This script prompts the user to enter a desired username and password, ensuring the username doesn't contain spaces. The password is then entered twice for confirmation, and if the entries match, the script proceeds to create the user using the useradd command. It offers three attempts to enter a matching password before aborting the process. After successful user creation, it displays the user's details from ```/etc/passwd``` and allows the option to delete the newly created user if desired.

### Usage
To use this script, follow these steps:

1. Clone the repository to your local machine.
2. Navigate to the script's directory.
3. Execute the script with sudo privileges:

```sh
$ sudo chmod +x add_user
```

```sh
$ sudo ./add_user
```

### Author
This script is authored by Kavya.

### Features
- Securely prompts for a username and password.
- Validates the username to ensure no spaces are used.
- Allows three attempts to enter a matching password.
- Utilizes the useradd command to create the user account.
- Verifies the user creation by displaying the user's details from /etc/passwd.
- Provides the option to delete the newly created user if desired.
- Please note that this script should be executed with sudo privileges to ensure it has the necessary permissions for user management on the system. Use it responsibly and be cautious while handling user accounts on your system.

Please note that this script should be executed with sudo privileges to ensure it has the necessary permissions for user management on the system. Use it responsibly and be cautious while handling user accounts on your system.
