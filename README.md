gitUpdate
=========

<b>USAGE:</b>

1) Change to your Downloads dir<br />
* "cd /home/myUser/Downloads/"<br />
      
2) Git the project from my repo<br />
* "git clone https://github.com/kthxbai2u/gitUpdate.git gitUpdate/"<br />
      
3) Copy the gitUpdate script to your Project's Directory<br />
* "cp gitUpdate/gitUpdate /home/myUser/Projects/XYZapp/"

4) Make it executable<br />
* "chmod +x /home/myUser/Projects/XYZapp/gitUpdate"
      
5) Create a repo on GitHub and copy the .git address

6) Edit the gitUpdate script<br />
* "nano gitUpdate"<br />
* Customize the 3 variables for your project<br />
* Swap out "kthxbai2u" for your GitHub username in the GIT_ADDRESS<br />
      
7) If you haven't done 'git init' in your project dir do it now<br />
* "cd /home/myUser/Projects/XYZapp/"<br />
* "git init"<br />
* "git pull https://github.com/my_user/my_project.git"<br />

8) Run gitUpdate every time you need to update the repository!<br />
* "./gitUpdate"<br />
* It should only ask for GitHub user/pass once, and never again.<br />
