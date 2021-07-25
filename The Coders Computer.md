### Understanding the terminal and using basic commands

1. mkdir - Allows you to create your local directory. For example, if you wanted to create a local directory for reading-notes, it would be mkdir reading-notes.
2. pwd - This command shows your local current working directory.
    * For example:
            * input: **Daniel$ pwd** output: **/mnt/c/Users/Daniel**
3. cd - Allows you to open up a certain directory, we will use reading-notes as an example. You can type **cd reading-notes** in and you can start working out of that directory.               Afterwards, you can use **pwd** to verify that you are in the correct directory.

### Cloning your repo from github

1. It's a good idea to verify your information before you start the process, you can do that by using these commands in the terminal.
      * git config --global user.name
      * git config --global user.email
      * **These will return your user name and email verifing your information**
2. Next step is to use the git clone command to clone your repository to your local directory.
      * That can be done by doing **git clone** *insert https link here*
3. You'll then want to initialize the clone by using the **git init** command, and then follow that with a **git status** to confirm it's been linked to the local directory.
4. Lastly you can use the **code .** command to open VS code, and you can verify your directory has been cloned on the left hand side.
5. Additionally, it's worth noting you can use the **touch** command to add new files to your repository. Some examples include:
      * *touch index.html*
      * *touch main.css*

6. Once you have made changes within VS code, you can push those changes to github website repository by using the command **git push origin master**
