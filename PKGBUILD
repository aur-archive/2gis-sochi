# Contributor: max1m <mr[dot]mxm86[at]gmail[dot]com>

pkgname=2gis-sochi
pkgver=10
pkgrel=1
pkgdesc="Map of Sochi for 2GIS"
arch=('i686' 'x86_64')
url="http://help.2gis.ru/linux/"
license=('custom')
depends=('2gis')
source=("http://download.2gis.ru/arhives/2GISData_Sochi-${pkgver}.orig.zip")
md5sums=('a9c3ad7ea10cf5c6db2192f9ed4d9485')

build() {

  cd $startdir

# Installing to /opt/2gis
  install -D -m 644 ${startdir}/src/2gis/3.0/Data_Sochi.dgdat "${startdir}/pkg/opt/2gis/sochi.dgdat" || return 1
  install -D -m 644 ${startdir}/src/2gis/3.0/Plugins/DGisLan/Sochi.dglf "${startdir}/pkg/opt/2gis/Plugins/DGisLan/Sochi.dglf" || return 1

}
