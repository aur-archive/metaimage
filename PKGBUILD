# Maintainer: Rasmus Thystrup Karstensen <rathka at gmail dot com>
# git-revision: d245afbf82992866680a9833d8439ab676cbc1a2
pkgname='metaimage'
pkgver='1.3.3'
pkgrel='1'
pkgdesc='Tool for batch-proccessing metadata in image files'
arch=(any)
url='https://code.google.com/p/metaimage'
license=(GPL3)
source=(https://metaimage.googlecode.com/archive/d245afbf82992866680a9833d8439ab676cbc1a2.tar.gz)
depends=(python python-pytz python-gobject libgexiv2)
md5sums=(SKIP) # zip/tar.gz from google code differs for each download

package() {
  cd ${srcdir}/metaimage-d245afbf8299
  sh install.sh ${pkgdir}/usr
}
