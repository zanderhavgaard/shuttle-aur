# Maintainer: Zander Havgaard <zander@havgaard.dk>

binname=shuttle
pkgname=shuttle-bin
pkgver=0.16.0
pkgrel=1
pkgdesc="CLI for handling shared build and deploy tools between projects no matter what technologies the projects are using"
arch=("x86_64")
url='https://github.com/lunarway/shuttle'
license=('Apache')
source=("${pkgname}-${pkgver}"::"https://github.com/lunarway/shuttle/releases/download/v${pkgver}/shuttle-linux-amd64")
sha256sums=('630983a1ad79ca82237cce1f08111d33bca5a20761f135b720a2f74ed1cbbcf4')
noextract=("${pkgname}-${pkgver}")
options=("!strip")

package() {
  install -Dm 775 "${pkgname}-${pkgver}" "${pkgdir}/usr/bin/${binname}"
}
