pkgname=2gis-sochi
pkgver=41
pkgrel=1
pkgdesc="Map of Sochi for 2GIS, December 2013"
arch=('i686' 'x86_64')
url="http://sochi.2gis.ru/how-get/linux/"
license=('custom')
depends=('2gis>=3.13.11.0')
source=("http://download.2gis.ru/arhives/2GISData_Sochi-41.orig.zip")
md5sums=('6e60c050a08e997dacb3813a3f598a3c')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Sochi.dgdat" "${pkgdir}/opt/2gis/sochi.dgdat" || return 1
  
}
