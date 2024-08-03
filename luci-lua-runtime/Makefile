<<<<<<< HEAD
#
# Copyright (C) 2022 Jo-Philipp Wich <jo@mein.io>
#
# This is free software, licensed under the Apache License, Version 2.0 .
#

include $(TOPDIR)/rules.mk

PKG_NAME:=luci-lua-runtime

LUCI_TYPE:=mod
LUCI_BASENAME:=lua-runtime

LUCI_TITLE:=LuCI Lua runtime libraries
LUCI_DEPENDS:= \
	+luci-base \
	+lua \
	+luci-lib-base \
	+luci-lib-nixio \
	+luci-lib-ip \
	+luci-lib-jsonc \
	+libubus-lua \
	+liblucihttp-lua \
	+ucode-mod-lua

include ../../luci.mk

# call BuildPackage - OpenWrt buildroot signature
=======
include $(TOPDIR)/rules.mk

PKG_NAME:=luci-lua-runtime
PKG_RELEASE:=1

include $(INCLUDE_DIR)/package.mk

define Package/luci-lua-runtime
	SECTION:=luci
	CATEGORY:=LuCI
	TITLE:=Empty LuCI Lua Runtime Package
endef

define Package/luci-lua-runtime/description
	This is an empty package for LuCI Lua Runtime.
endef

define Build/Compile
	# Nothing to compile
endef

define Package/luci-lua-runtime/install
	# Nothing to install
endef

$(eval $(call BuildPackage,luci-lua-runtime))
>>>>>>> d0ddee68d1aea3809760ae1108dab1ad732152f2