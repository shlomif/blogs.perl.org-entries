all:

upload:
	rsync -a -v --progress --inplace *.xhtml "$${__HOMEPAGE_REMOTE_PATH}/blogs.perl-journal/"
	rsync -a -v --progress --inplace blogs.perl.org-journal.xhtml "$${__HOMEPAGE_REMOTE_PATH}/blogs.perl-journal/t.xhtml"
