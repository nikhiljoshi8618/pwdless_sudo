#PASSWORDLESS SUDO SETUP 
1.LOGIN TO REMOTE MACHINE USING SSH (ssh nikhil@89.89.89.89)
2.Open sudoers file
	cmd:-sudo visudo
3.Add this "username ALL=(ALL) NOPASSWD: ALL"
4.Save the ssh file and exit 
6. Test using (ssh nikhil@89.89.89.89)it should not ask for pwd .
