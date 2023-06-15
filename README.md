Steps to host a website with GitHub Pages for free

	cd repos/sample_\website
	touch index.html

	git init
	git add -A
	git commit -m "Initialize repository"

create a repository on GitHub

GitHub pages use the special gh-pages branch in place for master

	git checkout -b gh-pages
	git push -u origin gh-pages
