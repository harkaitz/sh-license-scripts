PROJECT=sh-license-scripts
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
	cp LICENSE  $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT)
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/find-h-print-licenses $(DESTDIR)$(PREFIX)/bin
	cp bin/license--mit     $(DESTDIR)$(PREFIX)/bin
	cp bin/license          $(DESTDIR)$(PREFIX)/bin
	cp bin/find-h-readme    $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
