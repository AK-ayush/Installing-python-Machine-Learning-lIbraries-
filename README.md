Installing python Machine Learning libraries
============================================

1. Set the proxy envoirment variables while installing behind a proxy network

	export $http_proxy=http://username:password@hostname:port/;
	export $ALL_PROXY=$http_proxy

2. Download the requirement.txt file


3. Create and activate new virtual environment
	
	virtualenv venv;
	source venv/bin/activate

4. Install pip using follwoing commands

	sudo apt-get update && sudo apt-get -y upgrade;
	sudo apt-get install python-pip


5. Install requirements

	pip install -r requirements.txt
