# Login Test Cases

| Test ID | Scenario | Steps | Expected Result | Actual Result | Status |
|---------|---------|-------|----------------|---------------|--------|
| TC-01   | Valid login | Enter username "standard_user" and password "secret_sauce", click login | User is redirected to products page | | |
| TC-02   | Invalid password | Enter username "standard_user" and wrong password, click login | Error message "Username and password do not match" appears | | |
| TC-03   | Locked account | Enter username "locked_out_user" and password "secret_sauce", click login | Error message "Sorry, this user has been locked out." appears | | |
| TC-04   | Empty username | Leave username empty, enter password "secret_sauce", click login | Error message "Username is required" appears | | |
