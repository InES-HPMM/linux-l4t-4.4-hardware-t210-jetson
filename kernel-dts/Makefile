old-dtb := $(dtb-y)
dtb-y :=
makefile-path := platform/t210/jetson/kernel-dts

dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-cv-base-p2597-2180-a00.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-cv-p2597-2180-a00.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-tx1-p2597-2180-a01-android-devkit.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-tx1-p2597-2180-a01-devkit.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-tx1-p2597-2180-a01-devkit-hdmi2csi.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-e-base-p2595-0000-a00.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-e-p2595-0000-a00-00.dtb
dtb-$(CONFIG_ARCH_TEGRA_210_SOC) += tegra210-jetson-tx1-p2597-2180-a02-devkit-24x7.dtb

ifneq ($(dtb-y),)
dtb-y := $(addprefix $(makefile-path)/,$(dtb-y))
endif

dtb-y += $(old-dtb)
