# Python3 port scanner.

This python3 package is built to scan ports 1-65535 of the users requested IP
 - By calling AF_INET from the sys module, Python knows to communicate with IPv4 addresses. 
 - To indicate the user intends to check for open TCP ports, the program will use the SOCK_STREAM function from the sys module.

## PyFiglet

PyFiglet is used for generating the ascii art. In this application it is used to create a banner for the user.

