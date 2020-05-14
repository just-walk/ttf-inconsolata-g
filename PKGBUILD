# Maintainer: Sidney Crestani (sidneycrestani@yahoo.com)

pkgname=ttf-inconsolata-g
pkgver=20090213
pkgrel=3
conflicts=('ttf-inconsolata-g')
provides=('ttf-inconsolata-g')
pkgdesc="Monospace font for pretty code listings and for the terminal modified by Leonardo Maffi (http://www.fantascienza.net/leonardo/)"
url='https://github.com/justinwalker/'
license=('unknown')
depends=('fontconfig' 'xorg-font-utils')
source=('inconsolata_g::git+ssh://git@github.com/justinwwalker/inconsolata_g.git')
install=ttf-inconsolata-g.install
arch=('any')
md5sums=('SKIP')
         
package() {
    install -Dm644 $srcdir/inconsolata_g/Inconsolata-g.ttf $pkgdir/usr/share/fonts/TTF/ttf-inconsolata-g.ttf
}
