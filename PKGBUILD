# Maintainer: Martynas Mickevičius <self at 2m dot lt>
pkgbase=ucm
pkgname=ucm-bin
pkgver=M1g
pkgrel=1
pkgdesc='Unison language code manager'
arch=('x86_64')
url='https://www.unisonweb.org'
license=('custom')
depends=('base')

source=("ucm::https://github.com/unisonweb/unison/releases/download/release/$pkgver/unison-linux64.tar.gz"
        "https://raw.githubusercontent.com/unisonweb/unison/release/$pkgver/LICENSE")
sha256sums=('4b05432d735fa12a17aac8a6233002617f6bb2c565c942edd5ea5216b26229ce'
            '6dd1702f5e06317fef9577559ff85dae2aba622b0bc66f18db88c66ffeb693a2')

package() {
  install -D -m755 ucm "$pkgdir/usr/bin/ucm"
  install -Dm644 LICENSE "$pkgdir/usr/share/licenses/$pkgname/LICENSE"
}
