# Maintainer: msh356 <msh356@yandex.by>
pkgname=eblande
pkgver=0.1
pkgrel=1
pkgdesc="Next-generation domestic desktop"
arch=('x86_64')
url="https://t.me/Eblan_DE"
license=('GPL')
depends=('openbox' 'pcmanfm' 'tint2' 'dunst' 'flameshot' 'xdialog' 'bash' 'mousepad' 'lxappearance-obconf-gtk3' 'obconf-qt')
source=(
    "eblan-autostart"
    "eblande-session"
    "eblande.desktop"
)
#sha256sums=('727c75f7b8ab80b9b2406f839dfb4ff2a896a9307b794715484a30cc962b4828  eblande.desktop' 'ba285f70faabd53da90633dcb89b65cf48054fbf19dccbbc96c20679d7d41f8f  eblan-autostart' 'ebcece890d61eb30c7ee43058b57baa0b70fa31c68e3ec3b258ec5c6e614f8ee  eblande-session')
sha256sums=('ba285f70faabd53da90633dcb89b65cf48054fbf19dccbbc96c20679d7d41f8f' 'ebcece890d61eb30c7ee43058b57baa0b70fa31c68e3ec3b258ec5c6e614f8ee' '727c75f7b8ab80b9b2406f839dfb4ff2a896a9307b794715484a30cc962b4828')
package() {
    install -Dm755 "eblan-autostart" "$pkgdir/usr/bin/eblan-autostart"
    install -Dm755 "eblande-session" "$pkgdir/usr/bin/eblande-session"
    install -Dm644 "eblande.desktop" "$pkgdir/usr/share/xsessions/eblande.desktop"
}
