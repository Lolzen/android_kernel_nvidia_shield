GCOV_PROFILE := y
ccflags-y += -Idrivers/video/tegra/host
ccflags-y += -Iarch/arm/mach-tegra

ifeq ($(CONFIG_ARCH_TEGRA_18x_SOC),y)
ccflags-y += -I../kernel-t18x/drivers/video/tegra/host/
endif

nvhost-nvdec-objs  = \
	nvdec.o

obj-$(CONFIG_TEGRA_GRHOST) += nvhost-nvdec.o
