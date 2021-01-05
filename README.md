# mkvirtualenv-on-mac

<ins>Step 0</ins>: Open a terminal on your machine

<ins>Step 1</ins>: Install `brew` if you havent already into your machine by executing:  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

<ins>Step 2</ins>: Install python, in case you haven't it already into your machine (execute `brew install python3` for installing python3)

<ins>Step 3</ins>: Open your .bash_profile file (its located usually at your user path `/Users/your user's name`) and export the path variable by adding the following line.
`export PATH=/usr/local/share/python:$PATH`

Save and exit.

<ins>Step 4</ins>: Install `virtualenv` & `virtualenvwrapper` by executing: `pip3 install virtualenv virtualenvwrapper`

<ins>Step 5</ins>: Open your .bash_profile and set up and export virtualenv variables:
`export WORKON_HOME=$HOME/.virtualenvs` 

`export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3` 

`export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv` 

`source /usr/local/bin/virtualenvwrapper.sh` 

Save and exit.

<ins>Step 6</ins>: Execute the following command in order your machine to pick up the new changes

<ins>Step 7</ins>: Create a virtual env by executing the command  `mkvirtualenv --python=`which python3` <yourDesiredVirtualEnvName>` 
