# Description of project

This project is about learning how to infiltrate a server via a webservice. It is important to note that this website is filled with security flaws (on purpose).

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
    - Passwords are now hashed via wergzeug


# Added vulnerabilities

- Unsecure endpoint ```/config```
- Direct root access to server via a terminal from admin page
- Compromised username "rosario"


