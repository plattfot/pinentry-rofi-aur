# Maintainer: Fredrik Salomonsson <plattfot@gmail.com>
pkgname=guile-pinentry-rofi
pkgver=2.0.0
pkgrel=2
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
conflicts=('pinentry-rofi-guile')
replaces=()
backup=()
options=()
install=
changelog=
source=("$pkgname-$pkgver::git+https://github.com/plattfot/pinentry-rofi.git#tag=$pkgver")
noextract=()
md5sums=('SKIP')
package() {
	cd "$srcdir/$pkgname-$pkgver"
        autoreconf -vif && ./configure --prefix=/usr && make && DESTDIR="$pkgdir" make install
}
