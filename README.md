RIDE-install
============

A step-by-step guide on how to install Robot Framework IDE (RIDE) on a mac.

<br/>


i. Check Python version. (You should have 2.6+).
		python -V
		
ii. Download pip
		https://bootstrap.pypa.io/get-pip.py
		
iii. Install pip
		`python get-pip.py`
		
iv. Upgrade setuptools
		`pip install -U setuptools`
		
v. Upgrade pip
		`pip install -U pip`
		
vi. Turn off Gatekeeper
		System Preferences > Security & Privacy > General > 
		Allow apps downloaded from > Check on "Anywhere".
		
vii. Install wxPython
		[http://sourceforge.net/projects/wxpython/files/wxPython/2.8.12.1/]
		
viii. Install Robot Framework
		`pip install robotframework`
		
ix. Install Robot Framework RIDE
		pip install robotframework-ride
		
x. Install Selenium2 Library
		pip install robotframework-selenium2library
		
xi. MacOS 10.7+ (Mavericks)
		export VERSIONER_PYTHON_PREFER_32_BIT=yes
		
xii. Install Paver
		pip install -U Paver
		Usage: paver test
		Integration tests can be run by 'paver integrate'
		
xiii. Install VirtualEnv (Virtual Python Environment builder)
		pip install virtualenv	

xiv. Start RIDE
		ride.py		
