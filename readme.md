# How to install virtualenv:

#### Install `pip` first

    $ sudo apt-get install python3-pip
    
#### Install `virtualenv` using pip3

    $ sudo pip3 install virtualenv 


#### Install `virtualenvwrapper` using pip3

    $ sudo pip3 install virtualenvwrapper
    
#### Shell Startup File
Add three lines to your shell startup file (.bashrc, .profile, etc.) to set the location where the virtual environments should live, the location of your development project directories, and the location of the script installed with this package:

    export WORKON_HOME=$HOME/.virtualenvs
    export VIRTUALENVWRAPPER_SCRIPT=/usr/local/bin/virtualenvwrapper.sh
    source /usr/local/bin/virtualenvwrapper_lazy.sh
    
After editing it, reload the startup file (e.g., run source ~/.bashrc).