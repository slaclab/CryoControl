#==============================================================
#
#  Abs:  Makefile to build EPICS Database components
#
#  Name: Makefile
#
#  Facility: LCLS-II CryoControls Db/test
#
#  Auth: 01-Sep-2016, Diane Fairley  (dfairley)
#  Rev:  dd-mmm-yyyy, First Lastname  (USERNAME)
#--------------------------------------------------------------
#  Mod:
#        01-Sept-2016, D. Fairley (dfairley):
#           Add all db files
#
#==============================================================
#
TOP=../../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#
#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES
USR_DBFLAGS += -I../O.Common
#
#----------------------------------------------------
# Create and install (or just install)
# databases, templates, substitutions like this for test directory

DB += sioc-cp12-cr14.db

# =======================================================================
#
include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE
#
# End of file
