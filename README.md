# mkvirtualenv-on-mac

Step 0: Open a terminal on your machine

Step 1: Install `brew` if you havent already into your machine by executing:  /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"

Step 2: Install python, in case you haven't it already into your machine (execute `brew install python3` for installing python3)

Step 3: Open your .bash_profile file (its located usually at your user path `/Users/your user's name`) and export the path variable by adding the following line.
`export PATH=/usr/local/share/python:$PATH`

Save and exit.

Step 4: Install `virtualenv` & `virtualenvwrapper` by executing: `pip3 install virtualenv virtualenvwrapper`

Step 5: Open your .bash_profile and set up and export virtualenv variables:
`export WORKON_HOME=$HOME/.virtualenvs`
`export VIRTUALENVWRAPPER_PYTHON=/usr/local/bin/python3`
`export VIRTUALENVWRAPPER_VIRTUALENV=/usr/local/bin/virtualenv`
`source /usr/local/bin/virtualenvwrapper.sh`

Save and exit.

Step 6: Execute the following command in order your machine to pick up the new changes

Step 7: Create a virtual env by executing the command  `mkvirtualenv --python=`which python3` <yourDesiredVirtualEnvName>` 
