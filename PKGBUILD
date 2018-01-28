pkgname=node-test
pkgdesc="Test with node pkgbuild"
pkgver=1
pkgrel=1
arch=('i686' 'x86_64')
provides=A test node
source=('git://github.com/renanpallin/pkgbuild-node-test.git')
md5sums=('SKIP')

package() {
	# cd "$pkgname-$pkgver"
	# ls -lha
	install node-test-exec "$pkgdir/ust/bin/node-test-exec"
}