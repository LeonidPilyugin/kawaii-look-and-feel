# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-look-and-feel
pkgver=1.0
pkgrel=1
pkgdesc='Kawaii look-and-feel.'
arch=('x86_64')
license=('GPL3')
groups=('kawaii')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('b869d0997debff33d92d658cfa914ba0733fa07c056ec5c14682b82d7032a468')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
    cp -r $srcdir/* $dir
}

