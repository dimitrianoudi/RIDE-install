### Installing __RIDE RobotFramework__ on a mac
<br/>


######1. Check Python version. (You should have 2.6+).
		python -V
		
######2. Download pip
		https://bootstrap.pypa.io/get-pip.py
		
######3. Install pip
		python get-pip.py
		
######4. Upgrade setuptools
		pip install -U setuptools
		
######5. Upgrade pip
		pip install -U pip		

######6. Turn off Gatekeeper
		System Preferences > Security & Privacy > General > 
		Allow apps downloaded from > Check on "Anywhere".
		
######7. Install wxPython
		http://sourceforge.net/projects/wxpython/files/wxPython/2.8.12.1/
<br/>		

######8. Download Ride Robot
		pip install robotframework-ride
		
######9. MacOS 10.7+ (Mavericks)
		export VERSIONER_PYTHON_PREFER_32_BIT=yes
		
######10. Install Paver (Python Package Manager)
		pip install -U Paver
		Usage: paver test
		Integration tests can be run by 'paver integrate'
		
######11. Install VirtualEnv (Virtual Python Environment builder)
		pip install virtualenv	

######12. Start RIDE
		ride.py		
