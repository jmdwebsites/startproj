Create a site directory, initialize the git repository and add the LOG.md and README.md markdown files.

	git init
	touch LOG.md
	touch README.md
	git add .
	git commit -m "First commit."

Get a .gitignore file suitable for a python project

	$ curl -o .gitignore https://raw.githubusercontent.com/github/gitignore/master/Python.gitignore