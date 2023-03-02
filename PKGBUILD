# Maintainer: Maurício de Lima <mauriciodelima.mol@gmail.com>

pkgname=uaiso-bluetooth
pkgver=$(date +%y.%m.%d)
pkgrel=$(date +%H%M)
arch=('any')
url="https://wiki.archlinux.org/index.php/Bluetooth"
license=('GPL')
pkgdesc="Metapkg containing needed packages for using Bluetooth"
depends=("bluez"
        "bluez-hid2hci"
        "bluez-libs"
        "bluez-plugins"
        "bluez-tools"
        "bluez-utils")
optdepends=('blueman: A GTK bluetooth manager'
            'bluedevil: Qt bluetooth frontend'
            'blueberry: Bluetooth configuration tool')
install=$pkgname.install
