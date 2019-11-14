# GitWorkshop
This workshop will take you through adding a commit to a git project.

## Steps
### Fork it
Start by forking this repository into your own account (click "fork" on the top right of this screen). 

### Installation
Make sure you have git installed: https://git-scm.com/book/en/v1/Getting-Started-Installing-Git
Then open a terminal, and run:
```
git clone https://github.com/{your_profile_name}/GitWorkshop.git
cd GitWorkshop
```

### Change the code
Open the file "mainn.html" via any code editor, and change the paragraph that has your assigned number.

### Commit your code
For the next step, you may need to create an access token: https://help.github.com/en/github/authenticating-to-github/creating-a-personal-access-token-for-the-command-line
```
git add .
git commit -m "this is my first commit"
git pull
git push origin master
```
Detailed tutorial: https://rubygarage.org/blog/most-basic-git-commands-with-examples

### Create a pull request
Click "New oull request" to merge your code into the original repository.

### Get latest code
To get the latest code from the original repository:
```
git remote add upstream https://github.com/hanle11/GitWorkshop.git
git fetch upstream
git checkout master
git merge upstream/master
```

Detailed tutorial: https://digitaldrummerj.me/git-syncing-fork-with-original-repo/

