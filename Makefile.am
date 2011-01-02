# Copyright (C) 2006 International Business Machines and others.
# All Rights Reserved.
# This file is distributed under the Common Public License.

## $Id$

# Author:  Andreas Waechter           IBM    2006-04-13

AUTOMAKE_OPTIONS = foreign

########################################################################
#                List files that should be distributed                 #
########################################################################

EXTRA_DIST = $(EXAMPLE_FILES) README AUTHORS LICENSE

DISTCLEANFILES = $(EXAMPLE_CLEAN_FILES)

datacoindir = $(prefix)/share/coin/Data/Stochastic
datacoin_DATA = $(EXAMPLE_FILES)

coindocdir = $(prefix)/share/doc/coin/Data/Stochastic
coindoc_DATA = README AUTHORS LICENSE

include BuildTools/Makemain.inc
