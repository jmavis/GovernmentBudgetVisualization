# CityBudgetVisualization
A site/tool to visualize city budgets. Will start off initially with San Jose for the Code for San Jose group with the expectation that the code will generically apply to other cities that will be added on over time.


Setup instructions for mac (WIP):

# Install tool for installing Python packages
sudo easy_install pip 

# Install python 3.5
https://www.python.org/downloads/
	# verify installation with 
	>>> python3

# Install django for python 3.x
sudo pip3 install django
	# if you get an "InsecurePlatformWarning" then you need to install security pachage (see http://stackoverflow.com/questions/29134512/insecureplatformwarning-a-true-sslcontext-object-is-not-available-this-prevent)
	>>> sudo pip install requests[security]

	# verify django installation
	>>> python3
	>>> import django
	>>> print django.get_version()