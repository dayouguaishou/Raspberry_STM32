#
# 《树莓派玩转STM32开发》系列专题
#  求知Coder
#

include $(WORKSPACE)/scripts/variables.mk

MODULE_OBJS = $(patsubst %.c, %.o, $(wildcard $(CURDIR)/*.c))

INCLUDE_PATH += $(CURDIR) $(WORKSPACE)/STLibrary
INCLUDE_PATH += $(WORKSPACE)/CMSIS/CM3/CoreSupport $(WORKSPACE)/CMSIS/CM3/DeviceSupport/ST/STM32F10x

include $(WORKSPACE)/scripts/module.mk