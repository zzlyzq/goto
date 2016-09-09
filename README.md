# goto
A wrapper for system administrator, to accelarate the login server steps.

# situation 1
You are in one company, you are the system administrator, you managered 20 servers.
If the sa want to login to the server or router or switch, you should use secure crt or xshell or iterm to login the server, the xshell and securecrt have the password memory, so you just open the gui and select which one you want to login. 
But now, you have another option - The goto script. It is a wrapper.

goto > the user execute script, how to use , "./goto 1.1.1.1" or "./goto mytestserver", the parameter followed by goto will search the list file and find only one line that machtes your need, and involve the denglu2 script.

denglu2 > the script used the shell expect util, emulate the steps you login in the server.

list > records the name password and other things.
