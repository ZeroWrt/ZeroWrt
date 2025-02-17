#
# Copyright (C) 2006-2020 OpenWrt.org
#
# This is free software, licensed under the GNU General Public License v2.
# See /LICENSE for more information.
#
include $(TOPDIR)/rules.mk

PKG_NAME:=firmware-utils
PKG_RELEASE:=1

PKG_SOURCE_PROTO:=git
PKG_SOURCE_URL=$(PROJECT_GIT)/project/firmware-utils.git
PKG_SOURCE_DATE:=2025-01-20
PKG_SOURCE_VERSION:=2051fe5bc2a10306f0cdd8930a1cb893e433b9f4
PKG_MIRROR_HASH:=44fd4615f2266c19be5b24651b4b6ce8913cb8c427351f5ec5ceadd959a40732

include $(INCLUDE_DIR)/host-build.mk
include $(INCLUDE_DIR)/cmake.mk

$(eval $(call HostBuild))
