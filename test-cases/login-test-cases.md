# Login Page Test Cases

## Test Scenario
Verify that users can log in securely and receive appropriate validation messages.

| Test ID | Test Scenario | Test Data | Expected Result |
|---|---|---|---|
| TC_LOGIN_001 | Login with valid credentials | Valid username and password | User logs in successfully |
| TC_LOGIN_002 | Login with an invalid password | Valid username, invalid password | Error message is displayed |
| TC_LOGIN_003 | Submit empty fields | Username and password empty | Required-field validation appears |
| TC_LOGIN_004 | Submit only username | Valid username, empty password | Password validation appears |
| TC_LOGIN_005 | Submit only password | Empty username, valid password | Username validation appears |
| TC_LOGIN_006 | Verify password masking | Enter a password | Password is masked by default |

## Testing Notes

- Confirm expected results against the application's requirements.
- Record actual results during execution.
- Report any deviations as defects.
- Test account lockout and rate limiting if those requirements apply.
