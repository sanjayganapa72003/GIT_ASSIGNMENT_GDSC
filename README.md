# GIT_ASSIGNMENT_GDSC
## Assignment
- Make a folder with name of the folder in the format - `<Name>_<Rollno>` (Shashank_201CS257)
- In that folder you can add any piece of code.
- Make a pull request
    
    
## Contributing Guidelines
### Setting Up
- Fork the repo.
- Clone the forked repo using `git clone <repo-url>` to desired directory.
### Pull Requests
- For each new `submission`, `fix` or `feature` create a new branch named `<github-handle>-<explanatory-name>`.
    ```cmd
    git branch <branch-name>
    ```
- Switch to the new branch.
    ```cmd
    git checkout <branch-name>
    ```
- Make the changes in the new branch.
- Stage the changes for the next commit.<br>
    To stage changes from specific files:
    ```cmd
    git add <filename>
    ```
    To stage all the changes at once:
    ```cmd
    git add .
    ```
    Use `git status` to track the changes made.
- Commit the changes.
    ```cmd
    git commit -m "<commit-message>"
    ```
- Push the changes to your forked repo. <br>
    If you're working on a new branch:
    ```cmd
    git push -u origin <branch-name>
    ```
    If the branch already exists:
    ```
    git push
    ```
- Create a `pull request`.
### Keep in Mind
- Use `meaningful small commits`. Refer to this [link](https://cbea.ms/git-commit/).
- `Remember to fetch` changes from the upstream repo before working on something.

