Steps to host a website with GitHub Pages for free

step 1
create a working directory in your local machine. In this tutorial, repos is created as parent and sample_website as daughter. However, do what makes sense with you especially if you already have the project and only want to deploy it then you can jump over to step2.

        mkdir -p repos/sample_website
	cd repos/sample_website
	touch index.html

step 2
Initialize your directory with git then add and commit all your changes.
    
	git init
	git add -A
	git commit -m "Initialize repository"

step 3
Follow this final step and have your static website hosted for free.

create a repository on GitHub

GitHub pages use the special gh-pages branch in place for master

	git checkout -b gh-pages
	git push -u origin gh-pages
