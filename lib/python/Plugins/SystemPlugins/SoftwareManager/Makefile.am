installdir = $(pkglibdir)/python/Plugins/SystemPlugins/SoftwareManager

SUBDIRS = meta

install_PYTHON =	\
	__init__.py \
	plugin.py \
	BackupRestore.py \
	RestoreWizard.py \
	SoftwareTools.py \
	ImageBackup.py \
	PluginBackup.py \
	PluginRestore.py \
	Flash_online.py \
	Multibootmgr.py

dist_install_DATA = \
	restorewizard.xml \
	installable.png \
	installed.png \
	install.png \
	noprev.png \
	remove.png \
	update.png \
	upgradeable.png \
	upgrade.png \
	PluginBackup.sh \
	PluginRestore.sh

install-data-hook:
	chmod +x $(DESTDIR)$(installdir)/PluginBackup.sh; \
	chmod +x $(DESTDIR)$(installdir)/PluginRestore.sh;
