# File Inclusion Attacks

## Objective
Access or execute unauthorized files on the server.

## Types
- Local File Inclusion (LFI)
- Remote File Inclusion (RFI)

## Steps
1. Identified vulnerable file parameter  
2. Used payloads:
   - LFI: `../../etc/passwd`  
   - RFI: remote script URL  
3. Accessed sensitive files / executed code  

## Impact
- Data leakage  
- Remote code execution  

## Mitigation
- Validate file paths  
- Disable remote inclusion  
- Use whitelisting
