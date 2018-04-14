# Maintainer: Nissar Chababy <funilrys at outlook dot com>
# Ex-Maintainer: 	Jeroen Bollen <jbinero at gmail dot comau>

pkgname=ckbcomp
pkgver=1.182
pkgrel=1
pkgdesc="Compile a XKB keyboard description to a keymap suitable for loadkeys or kbdcontrol"
arch=(any)
url="http://anonscm.debian.org/cgit/d-i/console-setup.git/"
license=('GPL2')
depends=('perl')
source=("http://ftp.de.debian.org/debian/pool/main/c/console-setup/console-setup_${pkgver}.tar.xz")
sha512sums=('e534a5efe01dacab6bff9d8298f61e0a423aec25ef6b334709605f5a46df194b1713b52e17befe89d5c77f3ad22ad47b2b12c7f5998498a86e553b5f1189fc2f')

package() {
  cd console-setup
  install -d ${pkgdir}/usr/bin/
  install -m755 Keyboard/ckbcomp ${pkgdir}/usr/bin/
}
