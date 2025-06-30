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
