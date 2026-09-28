🧪 Lab 02 — Linux Users, Groups & Permissions

🎯 Objective

Learn how Linux users, groups, file ownership, and permissions control access to system resources.

🖥️ Environment

- Operating System: Kali Linux
- Purpose: Cybersecurity learning
- Environment: My own system

🔎 Commands Used

1. Current User

whoami

Displays the username of the currently logged-in user.

2. User ID and Groups

id

Displays the current user's UID, GID, and group memberships.

3. List File Permissions

ls -l

Displays file ownership and read, write, and execute permissions.

4. Current Groups

groups

Displays the groups associated with the current user.

5. Create a Lab File

touch security-test.txt

Creates an empty file for testing permissions.

6. Change File Permissions

chmod 600 security-test.txt

Restricts the file so that only its owner can read and write it.

7. Verify Permissions

ls -l security-test.txt

Used to verify the permission changes.

🧠 What I Learned

Linux uses users, groups, ownership, and permissions to control access to files and resources.

I learned how to identify my user and groups, inspect file permissions, and modify permissions using "chmod".

🔐 Security Relevance

Incorrect file permissions can expose sensitive information or allow unauthorized users to modify important files.

Understanding Linux permissions is therefore an important foundation for system hardening and cybersecurity.

📸 Lab Evidence

Screenshots will be added after completing the practical exercises.

📌 Next Step

Continue learning about Linux processes, services, logs, and system security.

