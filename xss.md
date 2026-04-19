# Cross-Site Scripting (XSS)

## Objective
Execute malicious scripts in the victim’s browser.

## Types Performed
- Stored XSS (persistent payload stored in database)
- Reflected XSS (payload via URL parameters)

## Steps
1. Identified input fields without validation  
2. Injected payload: `<script>alert('XSS')</script>`  
3. Executed script in browser  

## Impact
- Session hijacking  
- Cookie theft  
- Malicious redirects  

## Mitigation
- Input validation & sanitization  
- Output encoding  
- Content Security Policy (CSP)
