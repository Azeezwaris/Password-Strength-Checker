# Password Strength Checker
A Python tool with Tkinter GUI for checking password strength, calculating entropy, and hashing with bcrypt. Built for a cybersecurity portfolio.

## Setup
1. Install Python 3.13 (includes Tkinter).
2. Install bcrypt: `pip install bcrypt`.
3. Download `common_passwords.txt` from [SecLists](https://github.com/danielmiessler/SecLists/blob/master/Passwords/Common-Credentials/10k-most-common.txt).
4. Run: `python password_strength_checker.py`.

## Features
- Checks against 10k common passwords.
- Scores passwords (0-100) with color-coded feedback (red/orange/green).
- Calculates entropy.
- Hashes passwords with bcrypt.
- Saves results to `password_results.txt`.
- Polished GUI with real-time feedback.

## Screenshots
![Weak Password](screenshots/weak.png)
![Strong Password](screenshots/strong.png)

## Relevance
Demonstrates secure password practices and hashing, key for SOC analyst roles.
[Watch Demo](screenshots/demo.mp4)
