pkgname=hel-dbg
pkgver=1.0
pkgrel=1
pkgdesc="Helwan Linux default wallpaper"
arch=('any')
license=('custom')

source=("https://github.com/helwan-linux/dbg/raw/refs/heads/main/bg.png")
sha256sums=('SKIP')

install=hel-dbg.install

package() {
    install -Dm644 "$srcdir/bg.png" \
        "$pkgdir/usr/share/backgrounds/helwan-bg.png"
}
