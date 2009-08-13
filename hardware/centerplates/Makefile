##
## openmulticopter - 100% Free Software and Open Hardware multicopter project
## Copyright (C) 2009 Uwe Hermann <uwe@hermann-uwe.de>
##
## This program is free software; you can redistribute it and/or modify
## it under the terms of the GNU General Public License as published by
## the Free Software Foundation; either version 3 of the License, or
## (at your option) any later version.
##
## This program is distributed in the hope that it will be useful,
## but WITHOUT ANY WARRANTY; without even the implied warranty of
## MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
## GNU General Public License for more details.
##
## You should have received a copy of the GNU General Public License
## along with this program.  If not, see <http://www.gnu.org/licenses/>.
##

BOARD = centerplates

all: pcb-gerber pcb-ps pcb-png

pcb-gerber:
	pcb -x gerber --gerberfile $(BOARD) $(BOARD).pcb

pcb-ps:
	pcb -x ps --psfile $(BOARD).ps $(BOARD).pcb

pcb-png:
	pcb -x png --dpi 300 --only-visible --outfile $(BOARD).png $(BOARD).pcb

clean:
	@rm -f $(BOARD).pcb- $(BOARD).*.gbr $(BOARD).*.cnc $(BOARD).ps $(BOARD).png

