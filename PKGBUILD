# Maintainer: Zander Havgaard <zander@havgaard.dk>

binname=shuttle
pkgname=shuttle-bin
pkgver=0.18.0
pkgrel=1
pkgdesc="CLI for handling shared build and deploy tools between projects no matter what technologies the projects are using"
arch=("x86_64")
url='https://github.com/lunarway/shuttle'
license=('Apache')
source=("${pkgname}-${pkgver}"::"https://github.com/lunarway/shuttle/releases/download/v${pkgver}/shuttle-linux-amd64")
sha256sums=('6cde5b209160d3f2ceb726293b88d5321d8a0c457e0d0645e83f55a681c65dc1')
noextract=("${pkgname}-${pkgver}")
options=("!strip")

package() {
	install -Dm 775 "${pkgname}-${pkgver}" "${pkgdir}/usr/bin/${binname}"
}
