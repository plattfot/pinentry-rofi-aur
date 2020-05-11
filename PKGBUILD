# Maintainer: Fredrik Salomonsson <plattfot@gmail.com>
pkgname=pinentry-rofi-guile
pkgver=1.0.0
pkgrel=1
epoch=
pkgdesc="rofi frontend for pinentry"
arch=('any')
url=""
license=('Expat')
groups=()
depends=('rofi' 'guile' )
makedepends=()
checkdepends=()
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
changelog=ChangeLog
source=("$pkgname-$pkgver::git+https://github.com/plattfot/pinentry-rofi.git#tag=$pkgver")
noextract=()
md5sums=('SKIP')
package() {
	cd "$srcdir/$pkgname-$pkgver"
	make install PREFIX="$pkgdir"
}
