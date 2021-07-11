# Maintainer: Benjamin Herne <2001herne@gmail.com>

pkgname=herneUtils
pkgver=0.1
pkgrel=1
pkgdesc=""
arch=('any')
url="https://github.com/2001herne/herneUtils.git"
license=('APACHE')
groups=()
depends=('nano')
makedepends=('git')
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
source=("herneUtils-$pkgver.tar.gz::https://github.com/2001herne/herneUtils/archive/$pkgver.tar.gz")
noextract=()
sha256sums=('be848c918678a6ad78bb1596ad0507395dfd4df6a72a7c44578577ffa6a6230e')

package() {
    install -D -t "$pkgdir/usr/bin" "$srcdir/$pkgname-$pkgver/xnano"
}
