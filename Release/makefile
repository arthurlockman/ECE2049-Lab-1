################################################################################
# Automatically-generated file. Do not edit!
################################################################################

SHELL = cmd.exe

CG_TOOL_ROOT := C:/ti/ccsv5/tools/compiler/msp430_4.1.5

ORDERED_OBJS += \
$(GEN_CMDS__FLAG) \
"./LcdDriver/Dogs102x64_UC1701.obj" \
"./capTouchLibrary/CTS_Layer.obj" \
"./capTouchLibrary/CTS_HAL.obj" \
"./fonts/fontfixed6x8.obj" \
"./grlib/string.obj" \
"./grlib/rectangle.obj" \
"./grlib/line.obj" \
"./grlib/image.obj" \
"./grlib/context.obj" \
"./grlib/circle.obj" \
"./structure.obj" \
"./space_invaders.obj" \
"./peripherals.obj" \
-l"libc.a" \
"../lnk_msp430f5529.cmd" \
"../lib/driverlib.lib" \
"../lib/grlib.lib" \

-include ../makefile.init

RM := DEL /F
RMDIR := RMDIR /S/Q

# All of the sources participating in the build are defined here
-include sources.mk
-include subdir_vars.mk
-include lib/subdir_vars.mk
-include grlib/subdir_vars.mk
-include fonts/subdir_vars.mk
-include capTouchLibrary/subdir_vars.mk
-include LcdDriver/subdir_vars.mk
-include subdir_rules.mk
-include lib/subdir_rules.mk
-include grlib/subdir_rules.mk
-include fonts/subdir_rules.mk
-include capTouchLibrary/subdir_rules.mk
-include LcdDriver/subdir_rules.mk
-include objects.mk

ifneq ($(MAKECMDGOALS),clean)
ifneq ($(strip $(S_DEPS)),)
-include $(S_DEPS)
endif
ifneq ($(strip $(S_UPPER_DEPS)),)
-include $(S_UPPER_DEPS)
endif
ifneq ($(strip $(S62_DEPS)),)
-include $(S62_DEPS)
endif
ifneq ($(strip $(C64_DEPS)),)
-include $(C64_DEPS)
endif
ifneq ($(strip $(ASM_DEPS)),)
-include $(ASM_DEPS)
endif
ifneq ($(strip $(CC_DEPS)),)
-include $(CC_DEPS)
endif
ifneq ($(strip $(S55_DEPS)),)
-include $(S55_DEPS)
endif
ifneq ($(strip $(C67_DEPS)),)
-include $(C67_DEPS)
endif
ifneq ($(strip $(C??_DEPS)),)
-include $(C??_DEPS)
endif
ifneq ($(strip $(CLA_DEPS)),)
-include $(CLA_DEPS)
endif
ifneq ($(strip $(CPP_DEPS)),)
-include $(CPP_DEPS)
endif
ifneq ($(strip $(S??_DEPS)),)
-include $(S??_DEPS)
endif
ifneq ($(strip $(C_DEPS)),)
-include $(C_DEPS)
endif
ifneq ($(strip $(C62_DEPS)),)
-include $(C62_DEPS)
endif
ifneq ($(strip $(CXX_DEPS)),)
-include $(CXX_DEPS)
endif
ifneq ($(strip $(C++_DEPS)),)
-include $(C++_DEPS)
endif
ifneq ($(strip $(ASM_UPPER_DEPS)),)
-include $(ASM_UPPER_DEPS)
endif
ifneq ($(strip $(K_DEPS)),)
-include $(K_DEPS)
endif
ifneq ($(strip $(C43_DEPS)),)
-include $(C43_DEPS)
endif
ifneq ($(strip $(S67_DEPS)),)
-include $(S67_DEPS)
endif
ifneq ($(strip $(SA_DEPS)),)
-include $(SA_DEPS)
endif
ifneq ($(strip $(S43_DEPS)),)
-include $(S43_DEPS)
endif
ifneq ($(strip $(OPT_DEPS)),)
-include $(OPT_DEPS)
endif
ifneq ($(strip $(S64_DEPS)),)
-include $(S64_DEPS)
endif
ifneq ($(strip $(C_UPPER_DEPS)),)
-include $(C_UPPER_DEPS)
endif
ifneq ($(strip $(C55_DEPS)),)
-include $(C55_DEPS)
endif
endif

-include ../makefile.defs

# Add inputs and outputs from these tool invocations to the build variables 

# All Target
all: ece2049c15_lab1_ajockman_clstlaurent.out

# Tool invocations
ece2049c15_lab1_ajockman_clstlaurent.out: $(OBJS) $(CMD_SRCS) $(LIB_SRCS) $(GEN_CMDS)
	@echo 'Building target: $@'
	@echo 'Invoking: MSP430 Linker'
	"C:/ti/ccsv5/tools/compiler/msp430_4.1.5/bin/cl430" -vmspx --abi=coffabi -O0 --define=__MSP430F5529__ --diag_warning=225 --display_error_number --silicon_errata=CPU21 --silicon_errata=CPU22 --silicon_errata=CPU23 --silicon_errata=CPU40 --printf_support=minimal -z -m"ece2049c15_lab1_ajockman_clstlaurent.map" --stack_size=160 --heap_size=160 --use_hw_mpy=F5 -i"C:/ti/ccsv5/ccs_base/msp430/include" -i"C:/ti/ccsv5/tools/compiler/msp430_4.1.5/lib" -i"C:/ti/ccsv5/tools/compiler/msp430_4.1.5/include" --reread_libs --warn_sections --xml_link_info="ece2049c15_lab1_ajockman_clstlaurent_linkInfo.xml" --rom_model -o "ece2049c15_lab1_ajockman_clstlaurent.out" $(ORDERED_OBJS)
	@echo 'Finished building target: $@'
	@echo ' '

# Other Targets
clean:
	-$(RM) $(MSP430_EXECUTABLE_OUTPUTS__QUOTED) "ece2049c15_lab1_ajockman_clstlaurent.out"
	-$(RM) "peripherals.pp" "space_invaders.pp" "structure.pp" "grlib\circle.pp" "grlib\context.pp" "grlib\image.pp" "grlib\line.pp" "grlib\rectangle.pp" "grlib\string.pp" "fonts\fontfixed6x8.pp" "capTouchLibrary\CTS_HAL.pp" "capTouchLibrary\CTS_Layer.pp" "LcdDriver\Dogs102x64_UC1701.pp" 
	-$(RM) "peripherals.obj" "space_invaders.obj" "structure.obj" "grlib\circle.obj" "grlib\context.obj" "grlib\image.obj" "grlib\line.obj" "grlib\rectangle.obj" "grlib\string.obj" "fonts\fontfixed6x8.obj" "capTouchLibrary\CTS_HAL.obj" "capTouchLibrary\CTS_Layer.obj" "LcdDriver\Dogs102x64_UC1701.obj" 
	-@echo 'Finished clean'
	-@echo ' '

.PHONY: all clean dependents
.SECONDARY:

-include ../makefile.targets
