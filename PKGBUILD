# Maintainer: Dario Götz <dario dot goetz at googlemail dot com>

pkgname=xkb-noted-layout
pkgver="1.0.0"
pkgrel=1
pkgdesc="Keyboard layout 'noted' optimized for German and English as a custom xkb layout"
arch=('any')
url="https://github.com/dariogoetz/noted-layout"
license=('GPL')
depends=('xkeyboard-config')
source=("https://raw.githubusercontent.com/dariogoetz/noted-layout/main/noted")
md5sums=("ac832dfb181ed366ed7873ae335f24e4")

package() {
  cd "$srcdir"

  install -Dm644 noted "$pkgdir/usr/share/X11/xkb/symbols/noted"
}
