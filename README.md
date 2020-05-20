# [Data Science Modules page](https://labanyamukhopadhyay.github.io/modules-dsep/)


## How to Update Site

To edit the text/simple issues and update the site, follow these steps:

### Editting the Text
* Click on the green "Clone or download" button
* Click on "Download ZIP"
* Unzip the file and open the index.html in a code editor of choice (such as Visual Studio/TextEdit etc.)
* Make the necessary changes in the index.html file and save it

### Uploading Changes to Github
* Open Terminal if on Mac or Command Prompt if on Windows
* Open the folder in Terminal. Ex if folder is in Downloads, type `cd Downloads/modules-dsep`
#### If Git repo has not been set up yet:
* Initialize the local directory as a Git repository: `git init`
* Add the files in your new local repository: `git add .`
* Commit the files in your local repository: `git commit -m "First commit" `
* At the top of your GitHub repository's Quick Setup page, click the arrow button to copy the remote repository URL
[![Freelancer Preview](https://help.github.com/assets/images/help/repository/copy-remote-repository-url-quick-setup.png)

* Add the link in place of "URL" below for the remote repository where your local repository will be pushed: 
`git remote add origin URL`
`git remote -v`
* Push the changes in your local repository to GitHub: `git push -u origin master`

For official instructions for the above visit https://help.github.com/en/github/importing-your-projects-to-github/adding-an-existing-project-to-github-using-the-command-line

#### If Git repo has been set up:
* Open the folder in Terminal. Ex if folder is in Downloads, type `cd Downloads/modules-dsep`
* Add the changes in your new local repository: `git add .`
* Commit the files in your local repository with a message: `git commit -m "Some message" `
* Push the changes in your local repository to GitHub: `git push -u origin master`


### Now the site should be updated with the changes in some time. 
For further questions/assistance email labanya.mukho@berkeley.edu





