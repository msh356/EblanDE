# Maintainer: msh356 <msh356@yandex.by>
pkgname=eblande
pkgver=0.1
pkgrel=1
pkgdesc="Next-generation domestic desktop"
arch=('x86_64')
url="https://t.me/Eblan_DE"
license=('GPL')
depends=('openbox' 'pcmanfm' 'tint2' 'dunst' 'flameshot' 'xdialog' 'bash' 'lxappearance-obconf-gtk3' 'obconf-qt' 'arandr' 'pavucontrol-qt' 'lxinput')
source=(
    "eblan-autostart"
    "eblande-session"
    "eblande.desktop"
    "eblan-config"
    "eblan-config.desktop"
)
sha256sums=('e2c5cd6840551dee0d4f95d88e6219aa16ba8750f3ba40b60bdb76c6bf3f4029'
            'ebcece890d61eb30c7ee43058b57baa0b70fa31c68e3ec3b258ec5c6e614f8ee'
            '727c75f7b8ab80b9b2406f839dfb4ff2a896a9307b794715484a30cc962b4828'
            '9055968c5cba879aeee93a44b071b6e71d1748689e21b9ca01cf60c7499eb0b1'
            'd728726119d6e1f91a4e12e8e7787fc1dc095d2614adf627396f76db4541b705')
package() {
    install -Dm755 "eblan-autostart" "$pkgdir/usr/bin/eblan-autostart"
    install -Dm755 "eblande-session" "$pkgdir/usr/bin/eblande-session"
    install -Dm755 "eblan-config" "$pkgdir/usr/bin/eblan-config"
    install -Dm755 "eblan-config.desktop" "$pkgdir/usr/share/applications/eblan-config.desktop"
    install -Dm644 "eblande.desktop" "$pkgdir/usr/share/xsessions/eblande.desktop"
}
