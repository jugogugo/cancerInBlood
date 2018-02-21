all:
	rm -rf docs
	R -e 'rmarkdown::render_site()'
	mv _site docs

publish:
	git add docs
	git commit -am "Automatic generation of website"
	git push
