# Dehart Bruteforce (Beta)
This python script is a brute force script for iterating through passwords for a login page. It uses a given username and list of passwords from a file and iterates through each until the correct password is found. 

# Required Libraries
Running Python 3.x

<u>requests</u>
Install with the following command:
`pip install requests`

<u>termcolor</u>
Install with the following command: 
`pip install termcolor`

## Guide
1. Ensure the requirements are met by installing or updating the above libraries. 
2. This program requires you to save a list of passwords in a file.
4. Run the script using the following command:

```
python script.py
```

5. The script will prompt you to provide the following values:

`Login URL`
`Username of the account`
`Enter the path to the password file`
`Provide the string that occurs on the page when login fails`
`Provide the cookie value if prompted`

Once the script is executed, the script will iterate through and display the attempted passwords. In the event that it finds the correct password, the username and password will be printed and the script will terminate. 
