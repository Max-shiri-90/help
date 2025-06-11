### An Instruction to Connect Your PC to Your Github Account


* ##### Install git on Your Computer
    Find git in this [link] (https://git-scm.com/downloads) 

* ##### Config git on Your PC
    Use your github email
    ```
    git config --global user.name "Your_Username_for_GitHub"
    ```
    ```
    git config --global user.email "Your_email@something.com"
    ```

* ##### Create a ssh-key
    SSH key is a pair of cryptographic keys (public and private) that provides a secure, password-less way to authenticate your computer with the platform (GitHub)
    ```
    ssh-keygen -t ed25519 -C "Your_email@something.com"
    ```

* ##### Add ssk-key into Your PC
    Once you have made the key, you must save it in your PC
    ```
    eval "$(ssh-agent -s)"
    ```
    ```
    ssh-add ~/.ssh/id_ed25519
    ```

* ##### Add the Code to Your GitHub Account
    To copy the code use this command:
    ```
    cat ~/.ssh/id_ed25519.pub | clip
    ```
    Paste it in this path of github:
    > yourgithub -> settings -> ssh -> new-ssh-key

* ##### Make Sure the ssh is Connected
    ```
    ssh -T git@github.com
    ```
    You must see such a result:
    > Hi User_Name! You've successfully authenticated, but GitHub does not provide shell access.
