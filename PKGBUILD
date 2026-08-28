pkgname=helwan-wallpaper
pkgver=1.0
pkgrel=1
pkgdesc="Helwan Linux default wallpaper"
arch=('any')
license=('custom')

source=("bg.png")
install=helwan-wallpaper.install

package() {
    install -Dm644 "$srcdir/bg.png" \
        "$pkgdir/usr/share/backgrounds/bg.png"
}
