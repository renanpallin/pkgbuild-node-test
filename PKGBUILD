pkgname=node-test
pkgdesc="Test with node pkgbuild"
pkgver=1
pkgrel=1
arch=('i686' 'x86_64')
provides=A test node
source=('git://github.com/renanpallin/pkgbuild-node-test.git')
md5sums=('SKIP')

_gitname=pkgbuild-node-test

package() {
	cd $_gitname
	# ls -lha
	install -D node-test-exec "$pkgdir/usr/bin/node-test-exec"
}