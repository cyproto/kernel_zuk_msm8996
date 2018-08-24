ccflags-y += -Idrivers/media/platform/msm/camera_v2z
ccflags-y += -Idrivers/media/platform/msm/camera_v2z/common
ccflags-y += -Idrivers/media/platform/msm/camera_v2z/sensor/io
obj-$(CONFIG_MSM_CCI) += msm_cci.o

CFLAGS_msm_cci.o += $(call cc-disable-warning, array-bounds) 
