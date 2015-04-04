# Change-Group-or-OU-Passwords

dsquery user “OU=domain_name,DC=domain_controller,DC=local” | dsmod user –pwd “password” 
