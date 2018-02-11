# Maintainer: Nissar Chababy <funilrys at outlook dot com>
# Ex-Maintainer: 	Jeroen Bollen <jbinero at gmail dot comau>

pkgname=ckbcomp
pkgver=1.177
pkgrel=1
pkgdesc="Compile a XKB keyboard description to a keymap suitable for loadkeys or kbdcontrol"
arch=(any)
url="http://anonscm.debian.org/cgit/d-i/console-setup.git/"
license=('GPL2')
depends=('perl')
source=("http://ftp.de.debian.org/debian/pool/main/c/console-setup/console-setup_${pkgver}.tar.xz")
sha512sums=('3d9c9290ac4e7f230be33bc67bba5624b4570514a05abe08425e9b443820829cd2da0e83d137bea4c412642e02f38a8e40911d1f6b7fdcdd4f5697dcc20226d5')

package() {
  cd console-setup
  install -d ${pkgdir}/usr/bin/
  install -m755 Keyboard/ckbcomp ${pkgdir}/usr/bin/
}
