# $Id: PKGBUILD 7017 2009-12-29 20:22:18Z jlichtblau $
# Maintainer: Jaroslav Lichtblau <dragonlord@aur.archlinux.org>
# Contributor: Ronald van Haren <ronald.archlinux.org>
# Contributor: Andreas Wagner <A.Wagner@stud.uni-frankfurt.de>

pkgname=flux-utils
pkgver=2.3
pkgrel=1
pkgdesc="Scripts and utilities included in flux capacity"
arch=('i686' 'x86_64')
url=(http://fluxcapacity.99k.org)
license=('GPL2')
depends=('samba' 'cups' 'yad' 'util-linux-ng')
optdepends=()
source=()
md5sums=()

package() {
#  cd ${srcdir}/${pkgver}
mkdir -p ${pkgdir}/usr/bin
cp -p ${srcdir}/addflash ${pkgdir}/usr/bin
cp -p ${srcdir}/afpgui ${pkgdir}/usr/bin
cp -p ${srcdir}/cupsadm ${pkgdir}/usr/bin
cp -p ${srcdir}/fchelp ${pkgdir}/usr/bin
cp -p ${srcdir}/flux2hd ${pkgdir}/usr/bin
cp -p ${srcdir}/hotkeys ${pkgdir}/usr/bin
cp -p ${srcdir}/orphan ${pkgdir}/usr/bin
cp -p ${srcdir}/daemon ${pkgdir}/usr/bin
cp -p ${srcdir}/daemondialog ${pkgdir}/usr/bin
cp -p ${srcdir}/smbadm ${pkgdir}/usr/bin
}
