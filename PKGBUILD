pkgname=node-test
pkgdesc="Test with node pkgbuild"
pkgver=1
pkgrel=1
arch=('i686' 'x86_64')
provides=A test node

package() {
	cd "$pkgname-$pkgver"
	install node-test-exec "$pkgdir/ust/bin/node-test-exec"
}