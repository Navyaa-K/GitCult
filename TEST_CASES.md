# Login Module - Test Cases

| TC ID | Requirement ID | Priority | Preconditions | Test Data | Steps | Expected Result | Actual Result | Status | Comments |
|-------|---------------|----------|--------------|-----------|-------|-----------------|--------------|--------|----------|
| TC-LOGIN-01 | REQ-LOGIN-01 | High | User is registered | Valid email & password | 1. Enter valid email <br> 2. Enter valid password <br> 3. Click Login | User should be redirected to dashboard |  | Not Run |  |
| TC-LOGIN-02 | REQ-LOGIN-02 | High | User is registered | Valid email & wrong password | 1. Enter valid email <br> 2. Enter wrong password <br> 3. Click Login | Proper error message displayed |  | Not Run |  |
| TC-LOGIN-03 | REQ-LOGIN-03 | High | NA | Empty fields | 1. Leave email empty <br> 2. Leave password empty <br> 3. Click Login | Validation message should be shown |  | Not Run |  |
| TC-LOGIN-04 | REQ-LOGIN-04 | Medium | User not registered | Unregistered email | 1. Enter unregistered email <br> 2. Enter password <br> 3. Click Login | User not found message displayed |  | Not Run |  |
| TC-LOGIN-05 | REQ-LOGIN-05 | Medium | NA | Invalid email format | 1. Enter invalid email format <br> 2. Enter password <br> 3. Click Login | Email format validation message displayed |  | Not Run |  |
| TC-LOGIN-06 | REQ-LOGIN-06 | High | User account locked | Locked account credentials | 1. Enter locked account email <br> 2. Enter password <br> 3. Click Login | Account locked message displayed |  | Not Run |  |
| TC-LOGIN-07 | REQ-LOGIN-07 | Medium | NA | Password less than required length | 1. Enter valid email <br> 2. Enter short password <br> 3. Click Login | Password validation message displayed |  | Not Run |  |
