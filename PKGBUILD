# Contributor: Jon Bergli Heier <snakebite@jvnv.net>
pkgname=python-async
pkgver=0.6.1
pkgrel=1
pkgdesc="Async aims to make writing asyncronous processing easier."
arch=('i686' 'x86_64')
url="http://pypi.python.org/pypi/async"
license=('BSD')
depends=('python2')
source=("http://pypi.python.org/packages/source/a/async/async-${pkgver}.tar.gz")

md5sums=('6f0e2ced1fe85f8410b9bde11be08587')

build() {
  cd "$srcdir/async-$pkgver"
  python2 setup.py install --root="$pkgdir/" || return 1
}
# vim:set ts=2 sw=2 et:
