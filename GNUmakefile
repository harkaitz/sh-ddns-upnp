DESTDIR =
PREFIX  =/usr/local


all:
clean:
install:
update:
## -- install-sh --
install: install-sh
install-sh:
	mkdir -p $(DESTDIR)$(PREFIX)/bin
	cp bin/update-upnp      $(DESTDIR)$(PREFIX)/bin
	cp bin/dynu             $(DESTDIR)$(PREFIX)/bin
	cp bin/update-ddns      $(DESTDIR)$(PREFIX)/bin
## -- install-sh --
## -- license --
install: install-license
install-license: LICENSE
	mkdir -p $(DESTDIR)$(PREFIX)/share/doc/sh-ddns-upnp
	cp LICENSE $(DESTDIR)$(PREFIX)/share/doc/sh-ddns-upnp
## -- license --
