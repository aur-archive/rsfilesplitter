# Maintainer: Red Squirrel <iam at redsquirrel87 dot com>

pkgname=rsfilesplitter
pkgver=5.0
pkgrel=2
pkgdesc="A simple GUI for LXSplit"
arch=('any')
url="http://www.redsquirrel87.com/RSFileSplitter.html"
license=('freeware')
depends=('gambas3-gb-gtk' 'gambas3-gb-form' 'gambas3-gb-image' 'lxsplit')
optdepends=('gambas3-gb-qt4: if you need the QT support (KDE)')
install='rsfilesplitter.install'
source=(https://bitbucket.org/Red_Squirrel/rs-file-splitter/downloads/${pkgname}-AUR-${pkgver}.tar.gz)
md5sums=('64df75720b6ec040e27662fb45f25d4e')

package() {
  install -Dm755 "${srcdir}/${pkgname}-${pkgver}/rsfilesplitter.gambas" "${pkgdir}/usr/bin/rsfilesplitter"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/rsfilesplitter.desktop" "${pkgdir}/usr/share/applications/rsfilesplitter.desktop"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/48x48.png" "${pkgdir}/usr/share/icons/hicolor/48x48/apps/rsfilesplitter.png"
  install -Dm644 "${srcdir}/${pkgname}-${pkgver}/32x32.png" "${pkgdir}/usr/share/icons/hicolor/32x32/apps/rsfilesplitter.png"
}

