# Facebook Sign Up – Manual Test Cases

## Invalid Scenarios (Negative Testing)
These test cases verify system behavior with incorrect or missing input.

## Invalid test scenatios
- Validate leaving the first name field empty
- Validate leaving surname empty
- Validate leaving email or phone number field empty
- Validate leaving the password empty
- Validate leaving the gender empty
- Verify providing numbers or special characters in the first name
- Verify providing numbers and special characters in the surname
- Verify providing a very short first name (one letter)
- Verify providing very short surname (one letter)
- Verify providing very long first name more than 50 characters
- Verify providing very long surname name more than 50 characters
- Verify providing a short phone number 1234
- Verify providing a phone number more than 15 digits
- Verify providing a space in mobile number
- Verify cope/paste from another website or appllication
- Verify adding email with wrong format
- Verify adding email with a mistake in a  format (@gamal.com)
- Validate the password with less than 6 digits example aid2#
- Validate the password without numbers Anya&&
- Validate the password without special characters Anya123
- Validate providing date of birth less that 13
- Validate providing date of birth more than 120

### TC-01: Sign up with empty first name field

**Test Steps:**
1. Leave the first name field empty
2. Click "Sign Up"

**Expected Result:**
- Validation error messages are displayed
- Account is not created

**Status:** Pass


### TC-02: Sign up with invalid email format

**Test Steps:**
1. Enter invalid email (e.g., `test@`)
2. Fill other fields with valid data
3. Click "Sign Up"

**Expected Result:**
- Email validation error is displayed
- Account is not created

**Status:** Pass
