Name - Swasti Jain
Roll No. - BT23ECE016

Here's a structured list of commands and steps for pushing, merging, and pulling a branch in Git-

1st Commit - Initializing and First Push

1. Initialize the Repository -
git init

2. Add a New Remote
git remote add origin https://github.com/username/repo-name.git

3. Add files to staging
git add .

4. Commit Changes
git commit -m "Initial commit"

5. Push to github
git push -u origin main
_________________________________________________________________________________________________

2nd Commit - Working on a New Branch

1. Create and Switch to a New Branch
git checkout -b new-branch

2. Make Changes and Add to Staging
git add .

3. Commit the Changes
git commit -m "Add new feature in new-branch"

4. Push the branch to github
git push -u origin new-branch

