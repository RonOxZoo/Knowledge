* SMB --> server message block
* Port --> 445

Command:
smbclient -L //server_name -U (<user>)
smbclient -L //server_name -I (<IP>)

flags:
------
* -L --> list SMB files.(directories)
* -U --> connect to SMB server with a given user
* -I --> connect to SMB server with IP
    * smbget --> download files
Syntax : smbget --recursive smb://<ip>/<file>
