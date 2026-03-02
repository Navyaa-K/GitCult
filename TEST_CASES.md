## User Registration & Authentication

| TC ID | Module | Priority | Preconditions | Test Data | Steps | Expected Result | Actual Result | Status | Comments |
|-------|--------|----------|--------------|-----------|-------|-----------------|--------------|--------|----------|
| TC-AUTH-01 | Authentication | High | NA | Valid user details | 1. Enter valid details <br> 2. Click Register | User account created successfully |  | Not Run |  |
| TC-AUTH-02 | Authentication | High | Registered user | Valid email & password | 1. Enter credentials <br> 2. Click Login | User logged in successfully |  | Not Run |  |
| TC-AUTH-03 | Authentication | High | User logged in | Same credentials | Login from another device | Previous session should logout automatically |  | Not Run |  |
| TC-AUTH-04 | Authentication | High | NA | Invalid password | Enter wrong password | Proper error message displayed |  | Not Run |  |
| TC-AUTH-05 | Authentication | Medium | NA | Empty fields | Click login without data | Validation message shown |  | Not Run |  |
