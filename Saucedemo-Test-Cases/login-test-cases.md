# Login Page Test Cases - Saucedemo (Practice Site)

Website tested: https://www.saucedemo.com/

These are sample manual test cases I created for the login functionality.

| Test Case ID | Description                  | Steps                                      | Expected Result                     |
|--------------|------------------------------|--------------------------------------------|-------------------------------------|
| TC-001       | Valid login                  | 1. Open site<br>2. Enter username: standard_user<br>3. Enter password: secret_sauce<br>4. Click Login | User logs in successfully and sees products page |
| TC-002       | Invalid password             | 1. Open site<br>2. Enter username: standard_user<br>3. Enter wrong password<br>4. Click Login | Error message: "Username and password do not match" |
| TC-003       | Locked out user              | 1. Open site<br>2. Enter username: locked_out_user<br>3. Enter password: secret_sauce<br>4. Click Login | Error message: "Sorry, this user has been locked out." |
| TC-004       | Empty fields                 | 1. Open site<br>2. Leave username and password blank<br>3. Click Login | Error message: "Username is required" |
