# Cross-Site Request Forgery (CSRF)

## Objective
Force a user to perform unwanted actions without consent.

## Steps
1. Captured password change request  
2. Created malicious HTML request  
3. Tricked victim into executing it  
4. Password successfully changed  

## Impact
- Unauthorized account actions  
- Credential compromise  

## Mitigation
- CSRF tokens  
- SameSite cookies  
- Re-authentication for sensitive actions
