#
# SCTP Conformance Test Suite Implementation
# (C) Copyright Fujitsu Ltd. 2008, 2009, 2010
#
# This file is part of the SCTP Conformance Test Suite implementation.
#
# The SCTP Conformance Test Suite implementation is free software;
# you can redistribute it and/or modify it under the terms of
# the GNU General Public License version 2 as published by
# the Free Software Foundation.
#
# The SCTP Conformance Test Suite implementation is distributed in the
# hope that it will be useful, but WITHOUT ANY WARRANTY; without even
# the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR
# PURPOSE. See the GNU General Public License for more details.
#
# You should have received a copy of the GNU General Public License
# along with GNU CC; see the file COPYING.  If not, write to
# the Free Software Foundation, 59 Temple Place - Suite 330,
# Boston, MA 02111-1307, USA.
#
# Please send any bug reports or fixes you make to the
# email address(es):
#    networktest sctp <networktest-sctp@lists.sourceforge.net>
#
# Or submit a bug report through the following website:
#    http://networktest.sourceforge.net/
#
# Written or modified by:
#    Hiroaki Kago <linuxsctp-kg@ml.css.fujitsu.com>
#    Wei Yongjun <yjwei@cn.fujitsu.com>
#
# Any bugs reported given to us we will try to fix... any fixes shared will
# be incorporated into the next SCTP release.
#
##############################################################################

INSTALL_DIR=$(TESTDIR)/bund
XFILES = *.seq
FILES = *.def INDEX* *.html .footer

all:

install:
	install -d -o bin -g bin -m 755 $(INSTALL_DIR)
	install -c -o bin -g bin -m 555 $(XFILES) $(INSTALL_DIR)
	install -c -o bin -g bin -m 444 $(FILES) $(INSTALL_DIR)
	install -c -o bin -g bin -m 444 Makefile.test $(INSTALL_DIR)/Makefile

include Makefile.test
