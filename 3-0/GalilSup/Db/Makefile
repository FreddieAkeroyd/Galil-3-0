TOP=../..
include $(TOP)/configure/CONFIG
#----------------------------------------
#  ADD MACRO DEFINITIONS AFTER THIS LINE

#----------------------------------------------------
#  Optimization of db files using dbst (DEFAULT: NO)
#DB_OPT = YES

#----------------------------------------------------
# Create and install (or just install) into <top>/db
# databases, templates, substitutions like this

#----------------------------------------------------
# If <anyname>.db template is not named <anyname>*.template add
# <anyname>_template = <templatename>


# Galil program code for e.g. homing, installed to $(TOP)/gmc
GMC += galil_Default_Footer.gmc  galil_Default_Header.gmc  galil_Home_Home.gmc  galil_Home_ForwLimit.gmc
GMC += galil_Home_RevLimit.gmc  galil_Piezo_Home.gmc

include $(TOP)/configure/RULES
#----------------------------------------
#  ADD RULES AFTER THIS LINE

