# 22-ConflicctGameB
This is a repository for pull request and conflict practice

## Play the game using these TWO RULES
- You will ONLY edit the file when on your feature branch!
- You will NEVER commit changes when on the main branch!Play the game using these TWO RULE

**Setup in Git Bash or use VS Code integrated Terminal**

2. Open Git Bash
3. Clone the repo into a new directory
4. Create a new branch, call it **sign-in\*-yourName\*** (this will be your ***feature branch***) and check out this new branch using "**git checkout -b \*your feature branch name\***"
5. Modify the *sign-in.txt* code to add your name and the BC email address below my name
6. Commit the changes
7. Push your feature branch to Github using "**git push origin \*your feature branch name\***"

**Using GitHUB**

8. Make a Pull Request from your branch to main to push changes
9. resolve the merge conflicts, if there is any.(Check pull-Merge-Commit-Push details below)
   * Be mindful not to delete other people's response.
   * You may have to deal with merge conflicts more than once through this process.

### Pull-Merge-Commit-Push (repeat this part)

*(NOTE: you will need to do this several times since the main branch will be changing using other NT's  pull requests )*

 #### From VS Code Integrated Terminal

1. Be sure you are in the directory for this project
2. Type "**git status**" to make sure you are on your  **feature** branch and it is clean
3. Type "**git pull --rebase origin main**" or **git pull origin main** to pull the current copy of the main branch from the server and merge it into your feature branch
4. Make whatever changes you need to the file so that all of the existing names are included in the list and your name is below all other names
5. Finish the changes and Commit your changes
6. Type "**git status**" to be sure you are on your feature branch and it is clean
7. Type "**git push -u origin \*your feature branch name\***" to push the updated copy of your feature branch to the server

#### From Github

1. Navigate to your Pull request
2. Review your pull request to see that it shows that it is able to be merged.
3. If yes, complete the merge, otherwise see below

#### Repeat until complete the merge

1. Review your pull request details to see if your branch has conflicts with the current main branch. (Somebody branch has been merged ahead of you or other changes were made to main, sorry!!)
2. Resolve the conflicts using the "Pull-Merge-Commit-Push-Request" steps above (redo the entire process from pulling the main branch to pushing your feature branch and requesting a new review) - notice that the code continue to incorporate new names into main.
3. Repeat until you are able to merge your branch and close your pull request.
