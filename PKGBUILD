# Maintainer: happyjuniorman <347551432+happyjuniorman@users.noreply.github.com>

pkgname=checkra1n-cli
pkgver=0.12.4
pkgrel=3
pkgdesc="A semi-tethered jailbreak, developed primarily by Luca Todesco (qwertyoruiop). It's based on the checkm8 bootrom exploit released by axi0mx. Supports iOS 12.0 and newer."
license=('unknown')
url="https://checkra.in"
depends=('usbmuxd')
conflicts=('checkra1n-gui')
options=('!strip')
arch=('x86_64')

sha256sums_x86_64=('SKIP')
source_x86_64=("${pkgname}-${pkgver}-${pkgrel}-x86_64::https://assets.checkra.in/downloads/linux/cli/x86_64/${sha256sums_x86_64[0]}/checkra1n")

package() {
  install -Dm 755 \
    ${srcdir}/${pkgname}-${pkgver}-${pkgrel}-* \
    ${pkgdir}/usr/bin/checkra1n
}
