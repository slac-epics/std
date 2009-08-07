T_A=$(EPICS_HOST_ARCH)
TOP=../..

include $(TOP)/configure/CONFIG

COPY_SUBDIR = display

COPY_FILES += $(wildcard *.edl) $(wildcard *.gif)

# COPY_ONLY_IF_NON_LOCAL=1

include $(TOP)/configure/RULES
include $(TOP)/configure/RULES.copy