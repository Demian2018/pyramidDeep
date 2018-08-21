# pyramidDeep
#Demian Escobar

#Create virtual environment
$ easy_install install virtualenvwrappe
$ export WORKON_HOME=~/Envs
$ mkdir -p $WORKON_HOME
$ export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3.5
$ source /home/freeb/.local/bin/virtualenvwrapper.sh
$ mkvirtualenv env1




$ pcreate --list
$ pcreate --scaffold pyramid_jinja2_starter hello_world   
$ python ./setup.py develop
$ cd hello_world
$ easy_install pyramid_chameleon
$ easy_install pymongo

