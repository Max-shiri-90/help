### Setup MacOS for Data Science


* ##### Install [Homebrew] (https://brew.sh/) as package manager for macOS
    ```
    /bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
    ```

* ##### Install oh-my-zsh
    ```
    sh -c "$(curl -fsSL https://raw.githubusercontent.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
    ```

* ##### Zsh configuration
    ```
    source ~/.zshrc
    ```

* ##### Install vscode
    * first way:
    Download and Install [vscode] (https://code.visualstudio.com/docs/setup/mac)
    * second way:
    use brew package manager
    ```
    brew install --cask visual-studio-code
    ```

* ##### Add these Extentions on your vscode
    + Code Runner
    + Python (Microsoft)
    + Jupyter (Microsoft)
    + Git & GitHub Extension Pack


===============================================


### Make the First Project


* #### Create Virtual Enviroment
    ```
    python -m venv .venv
    ```
    somtimes when you have several pythons in your computer. you should use ```python3```
    the name ```.venv``` is optional. the ```.``` make the venv directory invisible in linux and mac

* #### Activate Virtual Enviroment
    ```
    source .venv/bin/activate
    ```
    now you must see ```(.venv)``` in the begining of every line of your termminal

* #### Deactivate Virtual Enviroment
    ```
    deactivate
    ```

* #### Installin Libraries
    you can either install one by one:
    ```
    pip install numpy
    ```
    or you can install several libraries at a time:
    ```
    pip install numpy pandas matplotlib seaborn
    ```
