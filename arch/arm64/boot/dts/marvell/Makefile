# Berlin SoC Family
dtb-$(CONFIG_ARCH_BERLIN) += berlin4ct-dmp.dtb
dtb-$(CONFIG_ARCH_BERLIN) += berlin4ct-stb.dtb

# Mvebu SoC Family
dtb-$(CONFIG_ARCH_MVEBU) += armada-3720-db.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-3720-db-sgmii1.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-3720-db-sfp.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-7040-db-router.dtb
# For Armada-7040-Z1 revision
dtb-$(CONFIG_ARCH_MVEBU) += armada-7040-rz-db-router.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-7040-rz-db-nand.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-7040-rz-db-rxaui.dtb
dtb-$(CONFIG_ARCH_MVEBU) += armada-7040-rz-pd.dtb

dtb-$(CONFIG_ARCH_MVEBU) += armada-8040-db-router.dtb

always		:= $(dtb-y)
subdir-y	:= $(dts-dirs)
clean-files	:= *.dtb
