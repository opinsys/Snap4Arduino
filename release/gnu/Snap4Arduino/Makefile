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

clean:
