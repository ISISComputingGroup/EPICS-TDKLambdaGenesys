TOP=../..

include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE
#=============================

#==================================================
# build a support library

LIBRARY_IOC += TDK_Lambda_Genesys

# xxxRecord.h will be created from xxxRecord.dbd
#DBDINC += xxxRecord
# install TDK_Lambda_Genesys.dbd into <top>/dbd
DBD += TDK_Lambda_Genesys.dbd

# specify all source files to be compiled and added to the library
#TDK_Lambda_Genesys_SRCS += xxx

TDK_Lambda_Genesys_LIBS += $(EPICS_BASE_IOC_LIBS)

#===========================

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

