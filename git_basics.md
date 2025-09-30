1. git init

Purpose: Creates a new Git repository in your project folder.

What it does: It sets up all the hidden Git files (.git folder) needed to start tracking your code.

Example:
git init
→ Now your folder is a Git repository.

2. git add

Purpose: Stages changes (files you modified/created) to be included in the next commit.

What it does: Prepares the files for saving in Git’s history.

Example:
git add file1.txt
git add .
→ Adds file1.txt or all files (.) to the staging area.

3. git commit

Purpose: Saves the staged changes into the Git repository with a message.

What it does: Records a snapshot of your project at that moment.
Example:
git commit -m "Added login feature"
→ Creates a commit with the message describing what you changed.

4. git push

Purpose: Uploads your local commits to a remote repository (like GitHub or GitLab).

What it does: Syncs your local work with the remote repo so others (or you from another computer) can access it.

Example:
git push origin main
→ Pushes commits to the main branch on the remote named origin.