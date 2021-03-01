RIDE-install
============

A step-by-step guide on how to install Robot Framework IDE (RIDE) on a mac.

<br/>


Check Python version. (You should have 2.6+).

		python -V
		
Download pip

		https://bootstrap.pypa.io/get-pip.py
		
Install pip

		python get-pip.py
		
Upgrade setuptools

		pip install -U setuptools
		
Upgrade pip

		pip install -U pip
		
Turn off Gatekeeper

		System Preferences > Security & Privacy > General > 
		Allow apps downloaded from > Check on "Anywhere".
		
Install wxPython

		http://sourceforge.net/projects/wxpython/files/wxPython/2.8.12.1/
		
Install Robot Framework

		pip install robotframework
		
Install Robot Framework RIDE

		pip install robotframework-ride
		
Install Selenium2 Library

		pip install robotframework-selenium2library
		
MacOS 10.7+ (Mavericks)

		export VERSIONER_PYTHON_PREFER_32_BIT=yes
		
Install Paver

		pip install -U Paver
		
		Usage: paver test
		
		Integration tests can be run by 'paver integrate'
		
Install VirtualEnv (Virtual Python Environment builder)

		pip install virtualenv

Start RIDE

		ride.py		
