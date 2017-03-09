Created a site directory, initialize the git repository and add the LOG.md and README.md markdown files.

	git init
	touch LOG.md
	touch README.md
	git add .
	git commit -m "First commit."

Got a .gitignore file suitable for a python project

	$ curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/master/Python.gitignore

Added some entries to the .gitignore file.

Setup a virtual environment locally in the project. The gitignore file ensures that it will not be checked into the repository.

	$ virtualenv venv
	$ source venv/bin/activate
	$ pip install --upgrade pip
