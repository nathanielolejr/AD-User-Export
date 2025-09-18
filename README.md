# AD User Export

## Overview
A PowerShell script that extracts Active Directory user account details and exports them into a CSV file for auditing and reporting.  
The export includes account status, logon timestamps, password expiration, and other key properties.

## Features
- Retrieves user account details from Active Directory  
- Exports results to a date-based CSV file  
- Includes account status, password expiration, and logon info  
- Useful for audits, reporting, and monitoring AD accounts  

## Usage
1. Open **PowerShell** as Administrator.  
2. Ensure the **Active Directory module** is installed.  
3. Update the script variables:
   - `$domain` → Your AD domain (e.g., `DC=example,DC=local`)  
   - `$outputFile` → Desired export location  
4. Run the script:  
   ```powershell
   .\Export-ADUsers.ps1
