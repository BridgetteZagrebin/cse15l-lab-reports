## Installing VScode
* Go to [https://code.visualstudio.com/](https://code.visualstudio.com/).
* Download and install the version correspnding to your system(Mac, Windows, etc.).
* Follow the steps it gives you.
* Bellow is what it should look like once VSCode has successfully been installed.
![VScode](https://user-images.githubusercontent.com/103292060/162644188-063fea7b-c9be-4119-8868-565bbfc4a562.PNG)

## Remote Connecting
* Install OpenSSH at [https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse](https://docs.microsoft.com/en-us/windows-server/administration/openssh/openssh_install_firstuse).
* Look for your CSE 15L account at [https://sdacs.ucsd.edu/~icc/index.php](https://sdacs.ucsd.edu/~icc/index.php)
* Once OpenSSH is installed, open a terminal in VSCode and type `ssh cs15lsp22zz@ieng6.ucsd.edu` but change the `zz` to your own CSE 15L account.
* Type `yes` and enter your password.
* Below is what your terminal should look like afterwards.

![Lab1 1](https://user-images.githubusercontent.com/103292060/162556043-f108c674-9d29-4a27-94d4-3d842de0f274.PNG)

## Trying Some Commands
*  Now run some of the following commands:
* `cd ~`
*  `cd`
*  `ls -lat`
*  `ls -a`
*  `ls /home/linux/ieng6/cs15lsp22abc` but replace `abc` with your own username
*  `cp /home/linux/ieng6/cs15lsp22/public/hello.txt ~/`
*  `cat /home/linux/ieng6/cs15lsp22/public/hello.txt/`
*  use the `exit` command to log out
*  Below is an example of runnig a command.
![Command_Example](https://user-images.githubusercontent.com/103292060/162651712-bd3b9256-b2b9-4911-a727-384db8b9ea2d.PNG)

## Moving Files with scp
* `scp` is a command used to move files from your computer to a remote computer.
* Create a file named `WhereAmI.java` with the following code

```
class WhereAmI {
  public static void main(String[] args) {
    System.out.println(System.getProperty("os.name"));
    System.out.println(System.getProperty("user.name"));
    System.out.println(System.getProperty("user.home"));
    System.out.println(System.getProperty("user.dir"));
  }
}
```
* run this file with `javac` and `java`
* then run the following command: `scp WhereAmI.java cs15lsp22zz@ieng6.ucsd.edu:~/` but with your own account
* use `ls` to see if the file was coppied into the remote computer
* run `javac`   and `java`

![WhereAmIStuff__](https://user-images.githubusercontent.com/103292060/162654668-3c9b6729-73b9-4ff3-ae81-79c4b2cfed44.PNG)

## Setting an SSH Key
* This SSH key will allow you to log into a reote computer without having to type in your passowrd!
* 
![sshThing](https://user-images.githubusercontent.com/103292060/162655145-d4b4017a-7557-47e5-afc8-825e3646b26a.PNG)

## Optimizing Remote Running

