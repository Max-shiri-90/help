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

* #### Configure the Path
    * zsh
    ```
    cat << EOF >> ~/.zprofile
    # Add Visual Studio Code (code)
    export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
    EOF
    ```
    * bash
    ```
    cat << EOF >> ~/.bash_profile
    # Add Visual Studio Code (code)
    export PATH="\$PATH:/Applications/Visual Studio Code.app/Contents/Resources/app/bin"
    EOF
    ```
    * You can now type ```code .``` in any folder to start editing files in that folder

* ##### Add these Extentions on your vscode
    + Code Runner
    + Python (Microsoft)
    + Jupyter (Microsoft)
    + Git & GitHub Extension Pack
