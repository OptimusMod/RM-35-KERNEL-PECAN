obj-$(CONFIG_PM)	+= sysfs.o
obj-$(CONFIG_PM_SLEEP)	+= main.o
obj-$(CONFIG_PM_RUNTIME)	+= runtime.o
obj-$(CONFIG_PM_OPS)	+= generic_ops.o
obj-$(CONFIG_PM_TRACE_RTC)	+= trace.o

ccflags-$(CONFIG_DEBUG_DRIVER) := -DDEBUG
ccflags-$(CONFIG_PM_VERBOSE)   += -DDEBUG

# Ignore warnings to prevent build breaks when using gcc 4.5.0
CFLAGS_REMOVE_main.o = -Werror
