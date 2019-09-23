### Git/GitHub Basics
**Requirements**
* Git -> https://git-scm.com/

Download and install Git. After that, when right-clicking inside some directory you should see some new options: such as "Git Bash here". There are different ways to download a repository. 
Click on the green "Clone or download" button and copy the link.
Pick a folder where you will store the repository (ex: My Documents/Repositories).
The navigate inside this folder, right-click inside it and click "Git Bash here".
A command prompt should appear.
There are several simple Git command you need to use to get started.
To download the selected repository, you need to use the following command:

`git clone <repo link>`

*Note: to paste inside Git console, use `Shift + Insert`*

After doing some changes to the files, you need to upload them.
This action requires three steps:
* **Select the files:** the most often thing you'll do (or at least for now) will be selecting all files.
To do that you need to navigate inside the root directory of the repository, right click and select "Git Bash here" (or just navigate through the git command prompt in case you didn't close it),
and use the following command: `git add .` Selecting '.' means everything. 
You can select a single folder or file, it depends on you. 
Like I mentioned, most often you will probably use '.' for now.

* **Commit the changes:** or "I made some changes and I am about to upload them". 
Use the command `git commit -m "<message, that describes the changes>"` Don't forget to add the `-m` option, otherwise *vim* will be opened.
* **Push (upload) the changes:** `commit` won't upload the files, you need to do it by using one last command: `git push`

*Additional:*
If someone has committed and pushed any changes to the repository, 
your local files will not be up-to-date. In that case, you need to 'download' the changes. 
You can do that by using the following command: `git pull` Or: "give me the last changes" 

