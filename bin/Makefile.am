EXTRA_DIST = \
    audio-convert-mod.in

install-data-local:
	$(mkinstalldirs) $(DESTDIR)$(bindir)
	$(INSTALL) -m 755 audio-convert-mod $(DESTDIR)$(bindir)/audio-convert-mod

uninstall-local:
	rm -f $(DESTDIR)$(bindir)/audio-convert-mod
