# Maintainer: Zander Havgaard <zander@havgaard.dk>

binname=shuttle
pkgname=shuttle-bin
pkgver=0.16.1
pkgrel=1
pkgdesc="CLI for handling shared build and deploy tools between projects no matter what technologies the projects are using"
arch=("x86_64")
url='https://github.com/lunarway/shuttle'
license=('Apache')
source=("${pkgname}-${pkgver}"::"https://github.com/lunarway/shuttle/releases/download/v${pkgver}/shuttle-linux-amd64")
sha256sums=('ba75657b15393f2906ef1781d542588f29db01e1cfcbb843be5452dc5cf86fe9')
noextract=("${pkgname}-${pkgver}")
options=("!strip")

package() {
  install -Dm 775 "${pkgname}-${pkgver}" "${pkgdir}/usr/bin/${binname}"
}
