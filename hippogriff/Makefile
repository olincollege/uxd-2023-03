start:
	bundle exec jekyll serve --livereload --drafts --future --host

ghp:
	bundle exec github-pages

docker:
	docker run --rm -it -v $(PWD):/srv/jekyll -p 4000:4000 jekyll/jekyll jekyll serve --livereload --drafts --future --host