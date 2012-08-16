Hello Project.


[Github for colaborator]

1. git bash 
2. $ ssh-keygen -t rsa -C "your_email@youremail.com"
   # Creates a new ssh key using the provided email
   # Generating public/private rsa key pair.
   # Enter file in which to save the key (/c/Users/you/.ssh/id_rsa): [Press enter]

3. copy content in id_rsa
   # Your identification has been saved in /c/Users/you/.ssh/id_rsa.
   # Your public key has been saved in /c/Users/you/.ssh/id_rsa.pub.
   # The key fingerprint is:
   # 01:0f:f4:3b:ca:85:d6:17:a1:7d:f0:68:9d:f0:a2:db your_email@youremail.com
   
   $ clip < ~/.ssh/id_rsa.pub
   # Copies the contents of the id_rsa.pub file to your clipboard

4. sent to starmomo by facebook message
5. starmomo add SSH keys to member's ssh-key
6. Testing(After confirm to adding SSH keys)
   $ ssh -T git@github.com
   # Attempts to ssh to github
   
   # (Success! message)
   # Hi username! You've successfully authenticated, but GitHub does not
   # provide shell access

   # (Don't worry, This message. you do type "yes")
   # The authenticity of host 'github.com (207.97.227.239)' can't be established.
   # RSA key fingerprint is 16:27:ac:a5:76:28:2d:36:63:1b:56:4d:eb:df:a6:48.
   # Are you sure you want to continue connecting (yes/no)?

7. Use github 'pull' and 'push' without username, password.





Then you may do ssh-keygen by git bash in Help(Hello Project folder).

When you upload to Github
First, github 'pull' and then you may use 'push' to Github.




Thanks Helper~!  



	         2012.08.16..20:27
	         by starmomo.