pkgname=2gis-sochi
pkgver=49
pkgrel=1
pkgdesc="Map of Sochi for 2GIS, August 2014"
arch=('i686' 'x86_64')
url="http://info.2gis.ru/sochi/products/download#linux"
license=('custom')
depends=('2gis>=3.14.7.0')
source=("http://download.2gis.com/arhives/2GISData_Sochi-49.orig.zip")
md5sums=('8b0d3dcbe5b50a5b39ce78f6bd6ce5ea')

package() {
  install -D -m 644 "${srcdir}/2gis/3.0/Data_Sochi.dgdat" "${pkgdir}/opt/2gis/2gis-sochi.dgdat" || return 1
  
}
