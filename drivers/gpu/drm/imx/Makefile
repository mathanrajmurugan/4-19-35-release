# SPDX-License-Identifier: GPL-2.0

imxdrm-objs := imx-drm-core.o

obj-$(CONFIG_DRM_IMX) += imxdrm.o

obj-$(CONFIG_DRM_IMX_PARALLEL_DISPLAY) += parallel-display.o
obj-$(CONFIG_DRM_IMX_TVE) += imx-tve.o
obj-$(CONFIG_DRM_IMX_LDB) += imx-ldb.o

imx-ipuv3-crtc-objs  := ipuv3-crtc.o ipuv3-plane.o ipuv3-kms.o
obj-$(CONFIG_DRM_IMX_IPUV3)	+= imx-ipuv3-crtc.o
obj-$(CONFIG_DRM_IMX_HDMI) += dw_hdmi-imx.o
obj-$(CONFIG_DRM_IMX_NWL_DSI) += nwl_dsi-imx.o
obj-$(CONFIG_DRM_IMX_SEC_DSIM) += sec_mipi_dsim-imx.o
obj-$(CONFIG_DRM_IMX_LCDIF) += lcdif/
obj-$(CONFIG_DRM_IMX_DCSS) += dcss/
obj-$(CONFIG_DRM_IMX_HDP) += hdp/
obj-$(CONFIG_DRM_IMX_DPU) += dpu/
