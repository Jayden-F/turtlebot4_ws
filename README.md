# turtlebot4_ws

ssh into the turtlebot4 and uninstall all packages you would like to install from source.

Next uninstall the robot upstart service using the turtlebot4 supplied python file.
~~~
uninstall.py
~~~

In setup.sh change the environment variable:
~~~
NAMESPACE=<enter your namespace>
~~~

next recreate the turtlebot4 upstart service using the python file.
~~~
install.py lite/standard
~~~
