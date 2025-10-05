# Maintainer: msh356 <msh356@yandex.by>
pkgname=eblande
pkgver=0.1
pkgrel=1
pkgdesc="Next-generation domestic desktop"
arch=('x86_64')
url="https://t.me/Eblan_DE"
license=('GPL')
depends=('openbox' 'pcmanfm' 'tint2' 'dunst' 'flameshot' 'xdialog' 'bash' 'lxappearance-obconf-gtk3' 'obconf-qt' 'arandr' 'pavucontrol-qt' 'lxinput' 'picom')
source=(
    "eblan-autostart"
    "eblande-session"
    "eblande.desktop"
    "eblan-config"
    "eblan-config.desktop"
)
sha256sums=('dd4ec07729c326bf5bdfe7ee87b4a805b6000829332e4e74f0a7290d2c9db304'
            'd7dc3312f1ed426c7f44ca251f21281aedf567a5b1b10a0f4b20b85299070d3a'
            '727c75f7b8ab80b9b2406f839dfb4ff2a896a9307b794715484a30cc962b4828'
            '68281f649605d6aa20a74c0a1221fb1b27d4cac068f494d0f374363628f2fc45'
            'd728726119d6e1f91a4e12e8e7787fc1dc095d2614adf627396f76db4541b705')
package() {
    install -Dm755 "eblan-autostart" "$pkgdir/usr/bin/eblan-autostart"
    install -Dm755 "eblande-session" "$pkgdir/usr/bin/eblande-session"
    install -Dm755 "eblan-config" "$pkgdir/usr/bin/eblan-config"
    install -Dm755 "eblan-config.desktop" "$pkgdir/usr/share/applications/eblan-config.desktop"
    install -Dm644 "eblande.desktop" "$pkgdir/usr/share/xsessions/eblande.desktop"
}
