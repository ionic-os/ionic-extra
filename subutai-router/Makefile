#
# Subutai Router
#

include $(TOPDIR)/rules.mk

PKG_NAME:=subutai-router
PKG_VERSION:=0.0.1
PKG_RELEASE:=1

PKG_BUILD_DIR:=$(BUILD_DIR)/subutai-router-$(PKG_VERSION)

include $(INCLUDE_DIR)/package.mk

define Package/subutai-router/Default
	SECTION:=Subutai
	CATEGORY:=Subutai
endef

define Package/subutai-router/Default/description
  Meta package for Subutai Router installation.
endef

define Package/subutai-router
$(call Package/subutai-router/Default)
	TITLE:=Subutai Router
endef

define Package/subutai-router/description
$(call Package/subutai-router/Default/description)
endef

define Package/subutai-router/install
	$(INSTALL_DIR) $(1)/usr/sbin
endef

$(eval $(call BuildPackage,subutai-router))

# vim: ts=2 et nowrap autoindent
