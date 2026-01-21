# Facebook Sign Up - Manual Test Cases

## Application Under Test
- Application: Facebook
- Module: Sign Up
- Platform: Web

### TC-01: Sign up with valid data - Positive testing

### Description
Password Rules: Enter a combination that is at least six numbers, letters and punctuation marks (such as ! and &).
- six digits
- include numbers
- include letters
- include special characher

### Valid Scenarios
- Validate sign up with valid phone number
- Validate sign up with valid email address
- Validate Sign up with Russian First and Last Name
- Validate providing a short valid First Name: "Mo or Yu"
- Validate providing phone number with  and without country code
- Validate sign up with the valid age in the range 13 to 18 years old
- Validate sign up with valid age in the range 18 to 120 years old
- Validate providing gender: female, male, non binary 

**Preconditions:**
- User is on the Facebook sign up page

**Test Steps**
1. Enter valid first name
2. Enter valid last name
3. Enter valid email
4. Enter valid password
5. Select valid date of birth
6. Select gender
7. Click "Sign Up"

**Expected Result:**
- Account is created successfully
- User is redirected to confirmation or home page

**Status:** Pass

**Evidence:**

![Sign up page](../05_evidence/screenshots/signup_pass.png)
