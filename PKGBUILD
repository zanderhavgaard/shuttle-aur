# Maintainer: Zander Havgaard <zander@havgaard.dk>

binname=shuttle
pkgname=shuttle-bin
pkgver=0.17.0
pkgrel=1
pkgdesc="CLI for handling shared build and deploy tools between projects no matter what technologies the projects are using"
arch=("x86_64")
url='https://github.com/lunarway/shuttle'
license=('Apache')
source=("${pkgname}-${pkgver}"::"https://github.com/lunarway/shuttle/releases/download/v${pkgver}/shuttle-linux-amd64")
sha256sums=('ec10ad9c705ad4eb804c1efd1b8f9d3ae3b67c7d875c25449a12996b297086d7')
noextract=("${pkgname}-${pkgver}")
options=("!strip")

package() {
	install -Dm 775 "${pkgname}-${pkgver}" "${pkgdir}/usr/bin/${binname}"
}
