# The following build order must be maintained.
SUBDIRS = exceptions util log cryptolink dns asiolink cc testutils database

if HAVE_MYSQL
SUBDIRS += mysql
endif

if HAVE_PGSQL
SUBDIRS += pgsql
endif

if HAVE_CQL
SUBDIRS += cql
endif

SUBDIRS += config_backend hooks dhcp config stats

if HAVE_SYSREPO
SUBDIRS += yang
endif

SUBDIRS += asiodns dhcp_ddns eval cfgrpt process dhcpsrv http
