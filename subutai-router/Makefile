#
# Subutai Router
#

include $(TOPDIR)/rules.mk

PKG_NAME:=subutai-router
PKG_VERSION:=0.0.1
PKG_RELEASE:=1

PKG_BUILD_DIR:=$(BUILD_DIR)/subutai-router-$(PKG_VERSION)

include $(INCLUDE_DIR)/package.mk

define Package/subutai-router
	SECTION:=Subutai
	CATEGORY:=Base
	TITLE:=Subutai Router

define Package/subutai-router/install
	$(INSTALL_DIR) $(1)/usr/sbin

$(eval $(call BuildPackage subutai-router))

# vim: ts=2 et nowrap autoindent
