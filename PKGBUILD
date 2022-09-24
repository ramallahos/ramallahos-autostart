# Maintainer: Safwan Nayeem Yousuf <safwannayeemyousuf.com>
pkgname=ramallahos-autostart
pkgver=1
pkgrel=1
pkgdesc="BSPWM config for RamallahOS"
arch=('any')
url="https://github.com/ramallahos/$pkgname"
license=('GPL3')
depends=()
makedepends=('coreutils')
source=("$pkgname::git+$url.git")
sha256sums=('SKIP')

package() {
    cd "$pkgname"
    install -Dm755 "$pkgname" "$pkgdir/usr/bin/$pkgname"
}

