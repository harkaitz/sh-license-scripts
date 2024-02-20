PROJECT=sh-license-scripts
VERSION=1.0.0
PREFIX=/usr/local
all:
clean:
install:

## -- BLOCK:license --
install: install-license
install-license: 
	install -D -t $(DESTDIR)$(PREFIX)/share/doc/$(PROJECT) LICENSE
## -- BLOCK:license --
## -- BLOCK:sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/license--gplv2   $(DESTDIR)$(PREFIX)/bin
	cp bin/find-h-print-licenses $(DESTDIR)$(PREFIX)/bin
	cp bin/license--mit     $(DESTDIR)$(PREFIX)/bin
	cp bin/make-h-license   $(DESTDIR)$(PREFIX)/bin
	cp bin/license          $(DESTDIR)$(PREFIX)/bin
	cp bin/license--gplv2-git $(DESTDIR)$(PREFIX)/bin
	cp bin/license--isc-openbsd $(DESTDIR)$(PREFIX)/bin
	cp bin/find-h-readme    $(DESTDIR)$(PREFIX)/bin
	cp bin/license--isc     $(DESTDIR)$(PREFIX)/bin
	cp bin/make-h-man       $(DESTDIR)$(PREFIX)/bin
## -- BLOCK:sh --
