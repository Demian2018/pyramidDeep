# pyramidDeep <br>
#Demian Escobar<br><br>

Linux - Debian streetch in here with python3 or greater and mongodb. <br>
Framework Pyramid with template engine called Jinja2 and pymongo for mongodb <br>
Mongodb in this case has no password<br>

<br>
# apt-get install python3<br>
# apt-get install mongodb<br>
$ easy_install install virtualenvwrapper<br>
$ export WORKON_HOME=~/Envs<br>
$ mkdir -p $WORKON_HOME<br>
$ export VIRTUALENVWRAPPER_PYTHON=/usr/bin/python3.5 (or the version you wish)<br>
$ source /home/freeb/.local/bin/virtualenvwrapper.sh (if can't find the file, try:  "find /home -name virtualenvwrapper.sh" )<br>
$ mkvirtualenv env3<br>
$ cd ~/Env/env3/<br>
$ workon env3<br>
$ cp ~/Downloads/unzip new_deep_package_demian.zip .<br>
$ unzip new_deep_package_demian.zip<br>
$ easy_install pyramid<br>
$ easy_install pyramid_jinja2<br>
$ easy_install pymongo<br>
$ mongod & ( if not possible to run as a normal user, try root )<br>
$ python3 app.py <br>

After that open a browser and try:<br><br>

http://localhost:1234/<br><br>


Thank you, any problems mail me.<br><br>

demianescobar@gmail.com<br>
