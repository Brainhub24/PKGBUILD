# Maintainer: Marcin Kulik <marcin@asciinema.org>

pkgname=asciinema
pkgver=1.3.0
pkgrel=1
pkgdesc="Record and share your terminal sessions, the right way"
arch=('any')
url="https://asciinema.org/"
license=('GPLv3')
source=("https://github.com/asciinema/asciinema/archive/v${pkgver}.tar.gz")
sha1sums=('cbfec02e9b0cfa47ae8f8793032e6f4b8eb76d40')

package() {
  cd "$srcdir/$pkgname-$pkgver"
  python3 setup.py install --root="$pkgdir/" --optimize=1
}
