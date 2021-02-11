COMMON_FLAGS="-march=native -O2 -pipe"
CFLAGS="${COMMON_FLAGS}"
CXXFLAGS="${COMMON_FLAGS}"
FCFLAGS="${COMMON_FLAGS}"
FFLAGS="${COMMON_FLAGS}"
MAKE_OPTS="j12 l12"
PORTDIR="/var/db/repos/gentoo"
DISTDIR="/var/cache/distfiles"
PKGDIR="/var/cache/binpkgs"
LC_MESSAGES=C
GRUB_PLATFORMS="efi-64"
VIDEO_CARDS="amdgpu radeonsi"
CONFIG_PROTECT="-*"
EMERGE_DEFAULT_OPTS="--jobs 12 --load-average=12"
ACCEPT_LICENSE="*"
PORTAGE_NICENESS=19
GENTOO_MIRRORS="http://gentoo.osuosl.org/ https://gentoo.osuosl.org/ http://mirrors.rit.edu/gentoo/"
ACCEPT_KEYWORDS="~amd64"
USE="alsa elogind flac hardened ipv6 libcaca savedconfig X xinerama
-a52 -acpi -altivec -apache2 -appindicator -aqua -audit -ayatana -berkdb -bidi -big-endian -bluetooth -bzip2 -calendar -canna -caps -cdb -cdda -cddb
-cdinstall -cdr -cjk -clamav -coreaudio -cracklib -css -cups -cxx -doc -dv -dvb -dvd -dvdr -emacs -emboss -fontconfig -freewnn -geoip -geolocation
-gnome -gnome-keyring -gnuplot -gps -gsl -gsm -gtk-doc -handbook -ibm -ieee1394 -inotify -ios -ipod -joystick -kde -libnotify -mms -mysql -mysqli -nas
-neon -oci8 -oci8-instant-client -oracle -oss -plasma -policykit -pulseaudio -quicktime -radius -samba -semantic-desktop -smartcard -speex -spell
-startup-notification -suid -systemd -telemetry -uclibc -vim-syntax -wayland -wifi -wmf -Xaw3d -xemacs -xscreensaver -zsh-completion"
CPU_FLAGS_X86="aes avx avx2 f16c fma3 mmx mmxext pclmul popcnt rdrand sha sse sse2 sse3 sse4_1 sse4_2 sse4a ssse3"
ACCEPT_KEYWORDS="~amd64"
