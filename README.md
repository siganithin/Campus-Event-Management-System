# Campus-Event-Management-System


🔍 OBSERVATION – Git & GitHub Task 
For pushing the files from git to github
1. Verify Git installation

Command:

git --version


Observation / Output:

Displays the installed Git version (e.g., git version 2.52.0.windows.1).

Confirms Git is properly installed and ready to use.

2. Initialize Git repository

Command:

git init


Observation / Output:

Creates a hidden .git directory.

Output indicates that an empty Git repository is initialized.

3. Check repository status

Command:

git status


Observation / Output:

Shows the current branch (main).

Displays untracked files before staging.

Indicates the working tree status.

4. Add files to staging area

Command:

git add .


Observation / Output:

Adds all project files to the staging area.

No output is shown, indicating successful staging.

5. Commit the files

Command:

git commit -m "Initial commit"


Observation / Output:

Saves staged files as a commit.

Output shows commit ID, number of files changed, and files created.

6. Connect local repository to GitHub

Command:

git remote add origin https://github.com/username/repository-name


Observation / Output:

Links local repository to the remote GitHub repository.

No output indicates successful connection.

7. Verify remote repository

Command:

git remote -v


Observation / Output:

Displays fetch and push URLs of the GitHub repository.

Confirms remote connection.

8. Push code to GitHub

Command:

git push -u origin main


Observation / Output:

Uploads local commits to GitHub.

Shows object enumeration and successful push message.

Sets upstream tracking between local and remote branches.

9. View commit history

Command:

git log --oneline


Observation / Output:

Displays commit history in one-line format.

Shows commit hash and commit message.

10. Final repository status

Command:

git status


Observation / Output:

Shows message: nothing to commit, working tree clean.

Confirms all changes are committed and pushed.

✅ Final Observation Summary

Git was successfully initialized in the project directory.

Project files were staged, committed, and pushed to GitHub.

Local repository was properly linked to a remote repository.

Version control was successfully implemented using Git and GitHub.
