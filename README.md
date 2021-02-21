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

USE="X alsa branding djvu flac gpm hardened libressl savedconfig xinerama

-Xaw3d -a52 -aac -aalib -accessibility -acl -acpi -adns -afs -altivec -ao -apache2

-aqua -atm -appindicator -audiofile -audit -ayatana -bash-completion -berkdb -bidi

-big-endian -blas -bluetooth -bzip2 -cairo -calendar -canna -caps -cdb -cdda -cddb

-cdinstall -cdr -cgi -cjk -clamav -colord -connman -coreaudio	-cracklib -css -cups

-cvs -cxx	-dbi -dbm -dga -doc -dts -dv -dvb -dvd -dvdr -eds -elogind -emacs -examples 

-exif -expat -fam -fastcgi -fftw -filecaps -firebird -fltk -fortran -freetds 

-freewnn -ftp -gd -gdbm -geoip -geolocation -ggi -gif -gimp -gles2-only	-glut -gmp

-gnome -gnome-keyring	-gnuplot -gnutls -gphoto2 -gps -graphicsmagick -graphviz -gsl

-gsm -gstreamer -gtk -gtk-doc -guile -gzip -handbook -hddtemp -hdf5 -headers-only	

-hscolour -ibm -iconv -icu -ieee1394 -imagemagick -imlib -infiniband -inotify 

-introspection -iodbc -ios -ipod -java -javascript -jbig -jit -joystick -jpeg -jpeg2k

-kde -ladspa -lame -lapack -lapack -lash -latex -ldap -libass -libcaca -libedit

-libnotify -libsamplerate -libwww -lirc -lua -luajit -m17n-lib -mad -magic -maildir

-mbox -mhash -mikmod -milter -mmap -mms -mng -modplug -motif -mpeg -mpi -mssql -mtp

-multilib -musepack -musicbrainz -musicbrainz -mysqli -nas -neXt -neon -netcdf -nis 

-nls -nntp -nocd -nsplugin -ocaml -ocamlopt -oci8 -oci8 -instant-client -odbc -ofx

-openal -openexr -openmp -opus -oracle -osc -oss -pam -pch -pcmcia -pcre -pda -pdf 

-perl -php -pie -plasma -plotutils -png -policykit -portaudio -posix -postgres 

-postscript -ppds -prefix -pulseaudio -python -qdbm -qmail-spp -qt5 -quicktime -radius

-raw -rdp -rss -ruby -samba -sasl -scanner -sctp -sdl -semantic-desktop	-skey -slang -slp 

-smartcard -snappy -sndfile -snmp -soap -sockets -socks5 -source -sox -speex -spell

-sqlite -startup-notification	-subversion	-suid -svg -svga -symlink -systemd -szip

-taglib -tcl -tcmalloc -tcpd -telemetry -test -theora -tidy -tiff -truetype -uclibc

-v4l -vaapi -vcd -vdpau -verify-sig	-vhosts -vim-syntax	-vorbis -wayland -wifi

-wxwidgets -xemacs -xface -xft -xml -xmlrpc -xmp -xmpp -xscreensaver -zsh-completion"

CPU_FLAGS_X86="aes avx avx2 f16c fma3 mmx mmxext pclmul popcnt rdrand sha sse sse2 sse3 sse4_1 sse4_2 sse4a ssse3"

ACCEPT_KEYWORDS="~amd64"
