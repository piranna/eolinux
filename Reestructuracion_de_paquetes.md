Reestructuracion de los paquetes de Xebian para adaptarlos a EOLinuX

Tamaño actual: 366 megas

# Esenciales #
Paquetes que NO se deben borrar (o no se pueden porque el sistema se queja):

| A | apt |
|:--|:----|
| B | base-files base-passwd bash |
| C | coreutils |
| D | debian-archive-keyring debianutils diff dpkg |
| E | ed |
| F | findutils |
| G | gcc-4.1-base gnugp gpgv gzip |
| H | hostname |
| I | initscripts |
| L | libc6 libedit2 libgcc1 locales login lsb-base |
| M | mawk mktemp mount |
| N | ncurses-base ncurses-bin |
| P | perl-base |
| S | sed sysv-rc sysv-rc-bootsplash sysvinit sysvinit-utils |
| T | tar |
| U | util-linux |

# Instalacion #
Paquetes necesarios para EOLinuX (basicamente, personalizaciones y optimizaciones)

| D | dash |
|:--|:-----|
| I | ispanish |
| T | tzdata |
| W | wspanish |

# Elimininacion #
Paquetes a eliminar de Xebian que no son en absoluto necesarios excepto en casos muy particulares (servidor de impresion, P2P...) o que son subceptibles a eliminacion

## Sarge ##
| A | aalib1 at atlas3-base |
|:--|:----------------------|
| B | base-config bc bin86 bittornado bison bochsbios bootsplash bootsplahs-theme-xebian build-essential busybox |
| C | cdparanoia cdrecord cpp cpp-3.3 cpp-4.1 cvs |
| D | dc db4.2-util debconf-utils doc-debian dselect |
| E | ed eterm exim4 exim4-base exim4-config exim4-daemon-light |
| F | fbset fdutils finger flac flex fluxbox-theme-xebian freevo freevo-media |
| G | g++ gcc gdb gftp gftp-common gftp-gtk gftp-text gnu-efi groff-base |
| H | hexedit |
| I | iamerican ibritish info ipw2100-modules-2.6.11.8 ipw2200-modules-2.6.11.8 |
| K | klogd |
| L | laptop-detect lbxproxy libast2 libid3tag0 libimlib2 libtiff4 libungif4g libxine1 lpr lynx |
| M | m4 mailx makedev man-db manpages manpages-dev mime-support mplayer-386 mpack mplayer-fonts module-assistant module-init-tools mozilla-firefox mtools mutt |
| N | ncftp nfs-common nmap nmapfe nvi |
| O | openssl |
| P | pan ppp pppconfig pppoe pppoeconf portmap procmail proxymngr |
| Q | qemu |
| R | rar ratpoison reportbug |
| S | samba setserial sgml-base slang1 speex squashfs-tools strace sysklogd |
| T | tasksel tcl8.4 tcsh telnet texinfo transfig twm |
| U | unrar unzip |
| V | vacation vim vim-common vgabios vorbis-tools |
| W | w3m wamerican whois wpasupplicant |
| X | x-window-system xchat xchat-common xchat-text xcursor-themes xdm xfs xfonts-75dpi xfonts-scalable xfwp xine-ui xml-core xmms xmms-kjofol xmms-kjofol-skins xprint xprint-common xprt xprt-xprintorg xserver-common xtdesktop xvfb |
| Z  | zip |

## Etch ##
| A | alsa-utils apt-listchanges apt-utils aptitude aspell |
|:--|:-----------------------------------------------------|
| B | binutils bsdmainutils bzip2 |
| C | ca-certificates cdbs console-common console-data console-tools cpio cramfsprogs cron |
| D | debhelper debmake devscripts dmidecode dpatch dpkg-dev |
| E | esound-common |
| F | fakeroot fontconfig ftp |
| G | g++-3.3 g++-4.1 gcc-3.3 gcc-3.3-base gcc-3.4-base gcc-4.1 gconf2 gconf2-common genisoimage gettext gettext-base gpa |
| H | hwdata hwsetup |
| I | iceweasel ifrename imlib-base imlib11 intltool-debian |
| K | kernel-package klibc-utils |
| L | lame language-env less liba52-0.7.4 libaa1 libatk1.0-data libao2 libartsc0 libaspell15 libatk1.0-0 libaudiofile0 libavcodec0d libc6-dev libcaca0 libcairo2 libcdparanoia0 libconsole libcucul0 libcupsys2 libcupsys2-gnutls10 libcurl2 libcurl3 libcurl3-gnutls libdb1-compat libdb2 libdb3 libdb4.0 libdb4.1 libdbus-glib-1-2 libdbus-1-3 libdevmapper1.00 libdevmapper1.01 libdirectfb-0.9-20 libdirectfb-0.9-25 libdns11 libdns16 libdps1 libdv4 libdvdcss2 libdvdread3 libenchant1c2a libesd0 libevent1 libfaad2-0 libflac4 libflac6 libflac7 libgii0 libgii0-target-x libg2c0 libgc1 libgc1c2 libgconf2-4 libgcrypt1 libgcrypt7 libggi2 libgl1-mesa-dri libglib1.2 libglib2.0-0 libglu1-mesa libgmime-2.0-2 libgnet2.0-0 libgnutls10 libgnutls11 libgpgme11 libgpmg1 libgssapi2 libgsm1 libgtk1.2 libgtk1.2-common libgtk2.0-0 libgtk2.0-bin libgtk2.0-common libgtkspell0 libidl0 libident libidn11 libiw27 libiw28 libisc7 libjasper-1.701-1 libklibc liblame0 liblockfile1 libltdl3 libmad0 libmagick9 libmikmod2 libmodplug0 libmodplug0c2 libmyspell3c2 libncurses5-dev libneon24 libnewt0.51 libnewt0.52 libnfsidmap2 libnss-db libogg0 liboggflac1 liboggflac3 libopencdk4 liborbit2 libpango1.0-0 libpango1.0-common libpcap0.7 libpcap0.8 libpci2 libpcre3 libperl5.8 libpostproc0d libreadline4 librpcsecgss3 libsasl2 libsexy2 libsdl1.2debian libsdl1.2debian-oss libsdl-image1.2 libsdl-mixer1.2 libsdl-ttf2.0-0 libsigc++-1.2-5c102 libsigc++-2.0-0c2a libsmbclient libsmpeg0 libspeex1 libssl0.9.7 libssp0 libstdc++5 libstdc++5-3.3-dev libstdc++6-4.1-dev libsvga1 libsysfs1 libsysfs2 libtasn1-2 libtextwrap1 libtheora0 libvolume-id0 libvorbis0a libvorbisenc2 libvorbisfile3 libxml2 libxp6 libxtst6 libxvidcore2 libxvmc1 linux-kernel-headers lirc-modules-2.4.30-xbox logrotate lsdvd |
| M | make mkisofs modconf mtr-tyni |
| N | ncurses-term ndiswrapper-common ndiswrapper-modules-2.4.31-xbox ndiswrapper-modules-2.6.11.8 ndiswrapper-utils ndiswrapper-utils-1.1 netkit-inetd |
| O | openhackware |
| P | patch patchutils pciutils po-debconf proll python python-apt python-central python-minimal python-newt python-support python2.3 python2.3-numeric-ext python2.3-pygame python2.3-twisted python2.4 python2.4-minimal |
| R | rcconf rcs |
| S | sharutils slang1a-utf8 sysfsutils |
| T | time traceroute type-handling |
| V | vim-runtime |
| W | whiptail winbind wireless-tools wodim |
| X | x-window-system-core xfonts-100dpi xfree86-common xine xlibmesa-dri xlibmesa-gl xlibmesa-glu xlibs xlibs-data xnest xorg xprt-common xserver-xorg-video-vga xserver-xorg-video-voodoo xserver-xorg-video-via xserver-xorg-video-trident xserver-xorg-video-tga xserver-xorg-video-tdfx xserver-xorg-video-sisusb xserver-xorg-video-sis xserver-xorg-video-siliconmotion xserver-xorg-video-savage xserver-xorg-video-s3virge xserver-xorg-video-s3 xserver-xorg-video-rendition xserver-xorg-video-newport xserver-xorg-video-neomagic xserver-xorg-video-mga xserver-xorg-video-ati xserver-xorg-video-chips xserver-xorg-video-cirrus xserver-xorg-video-dummy xserver-xorg-input-all xserver-xorg-input-synaptics xserver-xorg-input-wacom xserver-xorg-video-apm xserver-xorg-video-ark xserver-xorg-video-cyrix xserver-xorg-video-glint xserver-xorg-video-imstt xserver-xorg-video-nsc xserver-xorg-video-tseng xserver-xorg-video-i128 xserver-xorg-video-i740 xserver-xorg-video-i810 xutils xutils-dev |
| Y | yada |
| Z | zlib1g-dev |

## Candidatos a eliminacion ##

| bind9-host | |
|:-----------|:|
| bootsplash |  |
| bootsplash-theme-xebian | Depende de bootsplash |
| dnsutils | Depende de bind9-host |
| debsums |  |
| devfsd |  |
| hdparm ||  ||
| menu |  |
| procps | depende de hotplug |

## Probables de ser eliminados ##

| dictionaries-common | ¿realmente es necesario? son 10 megas... |
|:--------------------|:------------------------------------------|
| gettext | deborphan depende de el |
| hotplug |  |
| iptables | ¿realmente lo necesitamos? |
| locales | ¿realmente es necesario? son 10 megas... |

# Sustituciones #

| **Actual** | **Propuesto** |
|:-----------|:--------------|
| **fluxbox** fluxbox-theme-xebian | **matchbox-window-manager** libmatchbox1 libstartup-notification0 |
| **xvkbd** xaw3dg | **matchbox-keyboard** libfakekey0 |

# Exclusivos #
## PC ##
| lilo |
|:-----|
| mbr |

## XBox ##
| N | nv-drv-xbox |
|:--|:------------|
| R | raincoat |
| X | xbox-blink xbox-installer xboxdumper xboxfbctl xboxhdtool xboxinfo xbv |

## Instalacion ##
| pc-installer |
|:-------------|
| xserver-xorg-video-vmware |