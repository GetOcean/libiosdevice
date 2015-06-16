AM_CXXFLAGS = $(CFLAGS) $(CXXFLAGS) -DIDEVICERESTORE_NOMAIN=1 -D_WEBSOCKETPP_CPP11_STL_ -DHAVE_STRCPY -I$(top_srcdir)/include -I$(top_srcdir) -I$(top_srcdir)/src/irecv -I$(top_srcdir)/src/idevicerestore -I$(top_srcdir)/lib/jsoncpp -std=c++11 

AM_CFLAGS = $(CFLAGS) -DIDEVICERESTORE_NOMAIN=1 -D_WEBSOCKETPP_CPP11_STL_ -DHAVE_STRCPY -I$(top_srcdir)/include -I$(top_srcdir) -I$(top_srcdir)/src/irecv -I$(top_srcdir)/src/idevicerestore -I$(top_srcdir)/lib/jsoncpp -I$(top_srcdir)/lib/jsoncpp 

AM_LDFLAGS = $(libusbmuxd_CFLAGS) $(libxml2_CFLAGS) $(libplist_CFLAGS) $(libzip_CFLAGS) $(libz_CFLAGS) $(openssl_CFLAGS) $(libusb_CFLAGS) $(libpthread_CFLAGS) $(libcrypto_CFLAGS) $(libcurl_CFLAGS) $(libimobiledevice_CFLAGS)

lib_LTLIBRARIES = libiosdevice.la
libiosdevice_la_LDFLAGS = $(AM_LDFLAGS) -lusbmuxd -lboost_system -limobiledevice -lusb-1.0 -lcurl -lstdc++ -static -static-libstdc++
libiosdevice_la_SOURCES = \
		idevicerestore/asr.c \
		idevicerestore/asr.h \
		idevicerestore/common.c \
		idevicerestore/common.h \
		idevicerestore/dfu.c \
		idevicerestore/dfu.h \
		idevicerestore/download.c \
		idevicerestore/download.h \
		idevicerestore/fls.c \
		idevicerestore/fls.h \
		idevicerestore/idevicerestore.c \
		idevicerestore/idevicerestore.h \
		idevicerestore/img3.c \
		idevicerestore/img3.h \
		idevicerestore/img4.c \
		idevicerestore/img4.h \
		idevicerestore/ipsw.c \
		idevicerestore/ipsw.h \
		idevicerestore/limera1n.c \
		idevicerestore/limera1n.h \
		idevicerestore/limera1n_payload.h \
		idevicerestore/locking.c \
		idevicerestore/locking.h \
		idevicerestore/mbn.c \
		idevicerestore/mbn.h \
		idevicerestore/normal.c \
		idevicerestore/normal.h \
		idevicerestore/recovery.c \
		idevicerestore/recovery.h \
		idevicerestore/restore.c \
		idevicerestore/restore.h \
		idevicerestore/tss.c \
		idevicerestore/tss.h \
		irecv/libirecovery.c \
		irecv/libirecovery.h

idevicerestoredir = $(includedir)/idevicerestore
irecvdir = $(includedir)/irecv
idevicerestore_HEADERS = \
		idevicerestore/asr.h \
		idevicerestore/common.h \
		idevicerestore/dfu.h \
		idevicerestore/download.h \
		idevicerestore/fls.h \
		idevicerestore/idevicerestore.h \
		idevicerestore/img3.h \
		idevicerestore/img4.h \
		idevicerestore/ipsw.h \
		idevicerestore/limera1n.h \
		idevicerestore/limera1n_payload.h \
		idevicerestore/locking.h \
		idevicerestore/mbn.h \
		idevicerestore/normal.h \
		idevicerestore/recovery.h \
		idevicerestore/restore.h \
		idevicerestore/tss.h

irecv_HEADERS = \
		irecv/libirecovery.h
