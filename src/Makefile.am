#
# client/Makefile.am
#
# Part of Gabriel project
# Copyright (C) 2007, Zeeshan Ali <zeenix@gstreamer.net>
#
# Gabriel is free software; you can redistribute it and/or modify
# it under the terms of the GNU General Public License as published by
# the Free Software Foundation; either version 2 of the License, or
# (at your option) any later version.
#
# Gabriel is distributed in the hope that it will be useful,
# but WITHOUT ANY WARRANTY; without even the implied warranty of
# MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
# GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with Gabriel; if not, write to the Free Software
# Foundation, Inc., 59 Temple Place, Suite 330, Boston, MA  02111-1307  USA
#

bin_PROGRAMS = gabriel

INCLUDES = $(GLIB2_CFLAGS) $(DBUS_CFLAGS) -DDBUS_API_SUBJECT_TO_CHANGE

gabriel_SOURCES = gabriel-main.c gabriel.c gabriel-client.c
gabriel_LDFLAGS = $(GLIB2_LIBS) $(DBUS_LIBS) -lssh

noinst_HEADERS = gabriel.h gabriel-client.h

