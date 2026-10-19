#---------------------------------------------------------------------------------
# CLEAR THE LIST OF MODULES
#---------------------------------------------------------------------------------
ifeq ($(strip $(DEVKITPPC)),)
$(error "Please set DEVKITPPC in your environment. export DEVKITPPC=<path to>devkitPPC")
endif

include $(DEVKITPPC)/wiiu_rules

TARGET      :=  ProjectAfterLight
BUILD       :=  build
SOURCES     :=  source
DATA        :=  data
INCLUDES    :=  include

include $(DEVKITPPC)/wups_rules