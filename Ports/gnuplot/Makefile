BuildRequires += $(BinDir)/lua # lua

include ../../Library/GNU.mk

Title=		Gnuplot
Name=		gnuplot
Version=	5.0.5
Site=		http://www.gnuplot.info/
Source=		http://sourceforge.net/projects/gnuplot/files/gnuplot/$(Version)//$(Name)-$(Version).tar.gz
License=	GPL

LicenseFile=	$(SourceDir)/Copyright

GnuConfigureExtra += --with-readline=builtin
