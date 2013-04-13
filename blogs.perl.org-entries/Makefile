SRC = blogs.perl.org-journal.xhtml
OUT = _TEMP/t.xhtml

all: $(OUT)

$(OUT): $(SRC)
	cp -f $< $@

upload: $(OUT) $(SRC)
	rsync -a -v --progress --inplace $(OUT) $(SRC) "$${__HOMEPAGE_REMOTE_PATH}/blogs.perl-journal/"
