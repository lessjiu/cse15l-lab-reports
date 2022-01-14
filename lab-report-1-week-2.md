## Lab Report 1
### Remote Access

**Step 1. Install Visual Studio Code**
* Install VScode: [https://code.visualstudio.com](https://code.visualstudio.com)
* Open a window as shown below

![](vscode.png)

**Step 2. Remotely Connecting**
* Install OpenSSH: [InstallOpenSSH](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse)
* Look up your course specific account for CSE 15L on ieng6: [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)
* Open a terminal in VS code and *ssh* into your account
* If prompted, enter your password- it will not show up in your terminal.

![](ssh.png)

**Step 3. Trying Some Commands**
* *ls* lists all files in the current directory
* *ls -a* lists all files in the current directory, including hidden files
* *exit* logs you out of the remote server in your terminal
* *cd* changes directories

![](commands.png)

**Step 4. Moving Files with *scp***
* Create a new file on your computer and compile and run the program
* Use *scp* to copy the file to your ieng6 account
* Now run the program from ieng6

![](scpMoveFile.png)
![](scp2.png)

**Step 5. Setting an SSH Key**
* Use *ssh-keygen* to create a public key file and a private key file
* Copy the public key somewhere on the server and the private key somewhere on the client
* Copy the public key to the *.ssh* directory on the server
* Use *ssh*- if the passphrase you entered was empty, you should no longer need to use your password

![](keygen1.png)
![](keygen2.png)
![](keygen3.png)

**Step 6. Optimizing Remote Running**
* To copy a local edit to a file, run multiple commands on the same line using a semicolon

![](optimize.png)
