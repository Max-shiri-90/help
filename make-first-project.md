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
    now you must see ```(.venv)``` in the begining of every line of your termminal. You can Deactivate Virtual Enviroment with ```deactivate```.

* #### Install ipynb kernel
    install jupyter kernel manualy in vscode

* #### Installing Libraries
    you can either install one by one:
    ```
    pip install numpy
    ```
    or you can install several libraries at a time:
    ```
    pip install pandas seaborn scikit-learn
    ```
