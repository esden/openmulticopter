
#EAGLE3D_HOME=/home/poine/work/eagle3d/eagle3d/
EAGLE3D_HOME=/Applications/eagle3d/

POVLIB=+L$(EAGLE3D_HOME)/povray  +L/usr/share/fonts/truetype/msttcorefonts +L/Applications/eagle3d/msttfonts

omc-complete_small:
	povray -Iomc-complete.pov $(POVLIB) +W800 +H600

omc-complete_big:
	povray -Iomc-complete.pov $(POVLIB)  +W1600 +H1200 +Q9 +A0.3 +R5

clean:
	rm *~
