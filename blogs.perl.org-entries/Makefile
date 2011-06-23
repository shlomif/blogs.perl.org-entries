all: t.xhtml

t.xhtml: blogs.perl.org-journal.xhtml
	cp -f $< $@

upload: t.xhtml
	rsync -a -v --progress --inplace *.xhtml "$${__HOMEPAGE_REMOTE_PATH}/blogs.perl-journal/"
