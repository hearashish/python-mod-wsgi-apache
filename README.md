# python-mod-wsgi-apache
This is a help repo for running django in production
It uses django, apache2 and its modile mod_wsgi
Below are the steps to follow

1. Install apache2
2. Install apache2 module mod_wsgi
It can be installed in two ways
> apt install libapache2-mod-wsgi (for python2 )
> apt install libapache2-mod-wsgi-py3 (for python3)
3. Install python3 virtual environment
> apt install python3.8-venv
4. Create virtual environment
> python3 -m venv env
5. Activate virtual environment
> source env/bin/activate
> Can be deactivated using `deactivate` command
> Can be deleted using rm -rf <virtual-env-dir>
6. Install dependencies will be used in project like django
> pip3/pip install django
> sudo apt-get install libapache2-mod-wsgi-py3
7. Create virtual host and activate it in apache
8. Virtual host is given for help

Now everything is setup
Thanks!!
