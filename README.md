###PASSWORDLESS SUDO SETUP 
##Step1.LOGIN TO REMOTE MACHINE USING SSH (ssh nikhil@89.89.89.89)


##Step2.Open sudoers file
``` sudo visudo -f /etc/sudoers.d/username```


##Step3.Add the rule that will enable pwd less sudo
 ```"username ALL=(ALL) NOPASSWD: ALL"```


##Step4.Save the ssh file and exit 


##Step5. Give permissions for owners and group to read only
```sudo chmod 440/etc/sudoers/username```


##Step6. Test using (ssh nikhil@89.89.89.89)it should not ask for pwd .
