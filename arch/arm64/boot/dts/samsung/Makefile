# SPDX-License-Identifier: GPL-2.0

ifeq ($(filter y,$(CONFIG_SEC_A52SXQ_PROJECT)),y)
dts-dirs += a52/a52sxq
else ifeq ($(filter y,$(CONFIG_SEC_M52XQ_PROJECT)),y)
dts-dirs += m52/m52xq
else ifeq ($(filter y,$(CONFIG_SEC_A73XQ_PROJECT)),y)
dts-dirs += a73/a73xq
else ifeq ($(filter y,$(CONFIG_SEC_GTS7FEWIFI_PROJECT)),y)
dts-dirs += gts7/gts7fewifi
endif

always          := $(dtb-y)
subdir-y        := $(dts-dirs)

clean-files := *.dtb *.reverse.dts *.dtbo


