# Linux User Creation Bash Script
This project is based on writing a bash script called `create_users.sh` that reads a **text file** containing the **usernames** and **group names** of the new employees where each is written in the following format: `user;groups`.

## Features
1. Create users and groups as specified in the text file.
2. Sets up home directories with appropriate permissions and ownership.
3. Generates random passwords for the users.
4. Logs all actions to `/var/log/user_management.log`.
5. Stores the generated passwords securely in `/var/secure/user_passwords.txt`.
6. Ensures error handling for scenarios like existing users providing clear documentation and comments.

Checkout the [create_users.sh](./create_users.sh) script here.

_Powered by [HNG Internship](https://hng.tech/internship) and [HNG Premium](https://hng.tech/premium)._
