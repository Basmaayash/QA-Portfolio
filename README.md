# 🐞 Bug Report

## Bug ID:
BUG-101

## Title:
Account is not locked after 3 consecutive failed login attempts

## Module:
Authentication – Login

## Environment:
- Browser: Chrome (latest version)
- OS: Windows 10
- Build Version: 1.0.0

## Preconditions:
User account exists and is active.

## Steps to Reproduce:
1. Open the Login page.
2. Enter a valid username/email.
3. Enter an incorrect password.
4. Click on the Login button.
5. Repeat steps 2–4 three times.
6. Attempt to log in again using any password.

## Expected Result:
The account should be locked after 3 failed login attempts.
User should see a message indicating the account is temporarily locked.

## Actual Result:
The system allows the user to continue attempting login even after 3 failed attempts.
No account lock or warning message appears.

## Severity:
High  
(Security issue – allows unlimited login attempts)

## Priority:
High  
(Should be fixed immediately to prevent security risks)

## Status:
Open

## Reported By:
[basma ayash]

## Date:
2026-02-14
