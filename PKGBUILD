# Maintainer: Daniel Hillenbrand <codeworkx@bbqlinux.org>

pkgname=bbqlinux-themes-slim
pkgver=0.0.1
pkgrel=1
pkgdesc="BBQLinux Slim Themes"
arch=('any')
url="https://github.com/bbqlinux/bbqlinux-themes-slim"
license=('GPL')

package() {
    cd "$pkgdir"

    mkdir -p usr/share/slim/themes/bbqlinux-default
    install -Dm644 "$srcdir/usr/share/slim/themes/bbqlinux-default/background.png" usr/share/slim/themes/bbqlinux-default/background.png
    install -Dm644 "$srcdir/usr/share/slim/themes/bbqlinux-default/COPYING" usr/share/slim/themes/bbqlinux-default/COPYING
    install -Dm644 "$srcdir/usr/share/slim/themes/bbqlinux-default/panel.png" usr/share/slim/themes/bbqlinux-default/panel.png
    install -Dm644 "$srcdir/usr/share/slim/themes/bbqlinux-default/slim.theme" usr/share/slim/themes/bbqlinux-default/slim.theme
}
