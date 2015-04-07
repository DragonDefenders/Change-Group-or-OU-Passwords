# Change-Group-or-OU-Passwords

dsquery user “OU=domain_name,DC=domain_controller,DC=local” | dsmod user –pwd “password” 

DSQUERY user "OU=HAL,DC=domain,DC=com" | DSMOD user -pwd "password123"
