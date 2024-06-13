# GitHub Steps

Describe in your own words how to establish a connection between a local repository and a remote repository on GitHub.

You can connect a local and a remote repository through GitHub.
1. Create a local directory, `git init` in it, add to the staging area, and commit it with a commemnt.
2. Create a remote repository on GitHub with `SSH`.
3. Connect the two.
    - `git remote add origin git@github.com:USERNAME/REPO_NAME.git`
4. Set the git branch to main.
    - `git branch -M main`
5. Push your current project to the remote repository.
    - `git push -u origin main`
6. Refresh your GitHub to see your repository!
