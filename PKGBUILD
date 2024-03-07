# Maintainer: Leonid Pilyugin  <l.pilyugin04@gmail.com>

pkgname=kawaii-look-and-feel
pkgver=2.0
pkgrel=1
pkgdesc='Kawaii KDE look-and-feel'
groups=('kawaii')
url='https://github.com/LeonidPilyugin/kawaii-look-and-feel'
arch=(x86_64)
license=('GPL3')
source=("$pkgname-$pkgver.tar.gz::https://github.com/LeonidPilyugin/$pkgname/releases/download/v$pkgver/files.tar.gz")
sha256sums=('6975ac4ac80f7cca6453172ff57613d452c5f78fa02db10d28f3b865fe7cfe20')

package() {
    srcdir=$srcdir/files
    dir=$pkgdir/usr/share/plasma/look-and-feel
    install -dm755 $dir
    cp -r $srcdir/* $dir
}

