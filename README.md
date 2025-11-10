# Description of project

This project is about learning to hack stuff and tings.

# Patched vulnerabilites

- SQL Injection (by sanitizing)
    - Login page
    - Register page
    - Notes page (notes and import)
- Brute force password per session (introduced vulnerability)
    - No more than five tries per session to prevent brute forcing
    - can workaround by deleting cookie
- Weird matching of passwords
    - "Password is already taken"
- Passwords in plaintext
    - Passwaords are now hashed via a buildin Python function (aka no salting)
