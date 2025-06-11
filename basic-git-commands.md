### Basic Git Commands


* ##### Initializes a New Git Repository
    Type this in your Terminal to create a git repositotry on your local
    ```
    git init
    ```

* ##### Displays the State of the Working Directory
    ```
    git status 
    ```

* ##### Moves Changes from the Working Directory to the Staging Area
    for specific file:
    ```
    git add -FileName
    ```
    for all files:
    ```
    git add .
    ```

* ##### Takes the Staged Snapshot and Commits It to the Project History
    ```
    git commit -m 'brief coment about commit'
    ```

* ##### Pulling a Branch from a Remote Repository (GitHub)
    ```
    git pull
    ```

* ##### Pushing the Local Branch to the GitHub Repository Master Branch
    ```
    git push origin master
    ```

* ##### Clone a GitHub Repository on Your Local
    This is done when you make a repository on GitHub first, then you clone it in your local.
    * Copy the GitHub repository ssh-url:
    > your-repository -> code -> copy ssh-url
    * paste it on your local:
    ```
    git clone "The_repository_ssh_code"
    ```

* ##### Add a Local Repository on Your GitHub
    This is done when you make a repository on Local first, then you push it to GitHub.
    * Create a git repositotry on your local
    ```
    git init
    ```
    * Create a new repository on GitHub
    * Copy the ssh-url:
    > your-repository -> code -> copy ssh-url
    * paste it on your local:
    ```
    git remote add origin "The_repository_ssh_code"
    ```
