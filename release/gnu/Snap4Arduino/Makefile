all:

install:
	mkdir -p $(DESTDIR)/opt/Snap4Arduino
	mkdir -p $(DESTDIR)/usr/bin/
	mkdir -p $(DESTDIR)/usr/share/applications/
	cp -a nw nw.pak app.nw $(DESTDIR)/opt/Snap4Arduino
	install -m 655 -t $(DESTDIR)/usr/bin/ \
		Snap4Arduino
	install -m 644 -t $(DESTDIR)/usr/share/applications/ \
		Snap4Arduino.desktop
	install -m 644 icons/teddybear16.png \
		$(DESTDIR)/usr/share/icons/hicolor/16x16/apps/Snap4Arduino.png
	install -m 644 icons/teddybear24.png \
		$(DESTDIR)/usr/share/icons/hicolor/24x24/apps/Snap4Arduino.png
	install -m 644 icons/teddybear32.png \
		$(DESTDIR)/usr/share/icons/hicolor/32x32/apps/Snap4Arduino.png
	install -m 644 icons/teddybear48.png \
		$(DESTDIR)/usr/share/icons/hicolor/48x48/apps/Snap4Arduino.png
	install -m 644 icons/teddybear128.png \
		$(DESTDIR)/usr/share/icons/hicolor/128x128/apps/Snap4Arduino.png
	install -m 644 icons/teddybear256.png \
		$(DESTDIR)/usr/share/icons/hicolor/256x256/apps/Snap4Arduino.png

clean:
