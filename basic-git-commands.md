### Basic Git Commands


* ##### Initializes a New Git Repository
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

* ##### Pushing the Local Branch to the GitHub Repository Master Branch
    ```
    git push origin master
    ```

* ##### Pulling a Branch from a Remote Repository (GitHub)
    ```
    git pull
    ```

* ##### Clone a GitHub Repository on Your Local
    This is done when you make a repository on GitHub first, then you clone it in your local.
    * Create a new repository on GitHub
    * Copy the ssh-url:
    > your-repository -> code -> copy ssh-url
    * paste it on your local:
    ```
    git clone "The_repository_ssh_code"
    ```

* ##### Add a Local Repository on Your GitHub
    This is done when you make a repository on Local first, then you push it to GitHub.
    * Create a new repository on GitHub
    * Copy the ssh-url:
    > your-repository -> code -> copy ssh-url
    * paste it on your local:
    ```
    git remote add origin "The_repository_ssh_code"
    ```