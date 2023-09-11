1. git init -> Powers your folder to be managed by git, and initialises a new empty repository. It also creates a .git folder that has all the relevant logic to manage versions of your project.

2. rm -rf .git -> removes the .git folder so that your project is no longer managed by git.

3. "Working Area" -> There might be a bunch of files that are not currently handled by git. That is the changes done or to be done in those files are not managed by git yet. A file which is in working area is considered to be not in the staging area.When we do git status, and we see a bunch of untracked files, then these are said to be in the working area.

4. "Staging area" -> What all files are going to be a part of the next version that we will create. This staging area is the place where git knows what changes will be done from the last version to the next version..

5. "Repository Area" -> This area contains the details of all your previous registered versions. And the files in this area, git already manages them and knows there version history.

6. git add <file> -> moves the file from working area to the staging area.

7. git rm --cached <file> -> moves the file back from staging area to the working area.

8. git commit -> commit is a particular version of the project. It captures a snapshot of the project's staged changes and creates a version out of it.

9. git log -> lists down all the commits that have been made in the repository. Use `q` to exit the log area.

10. git restore <file> -> If we did some dirty piece of code, and we want to delete all of it. We can simply restore the last staged clean version of the file using this command.
