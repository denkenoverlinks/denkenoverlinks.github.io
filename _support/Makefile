favicon.ico: DL16.png DL32.png DL64.png DL128.png DL256.png
	convert $^ $@

DL%.png: DL.png
	convert -scale $*x$* $< $@

clean:
	rm -f DL16.png DL32.png DL64.png DL128.png DL256.png

.PHONY: clean

# vim:noexpandtab
