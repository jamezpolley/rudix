BuildRequires += $(BinDir)/cython # cython

include ../../Library/Python.mk

Title=		Bazaar
Name=		bzr
Version=	2.7.0
Site=		http://bazaar-vcs.org/
Source=		http://launchpad.net/bzr/2.6/$(Version)/+download/$(Name)-$(Version).tar.gz
License=	GPL

LicenseFile=	$(SourceDir)/COPYING.txt

define test_hook
$(BinDir)/bzr --version | grep $(Version)
endef
