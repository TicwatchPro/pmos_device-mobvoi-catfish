# Reference: <https://postmarketos.org/devicepkg>
# Maintainer: Tipz Team <rcheung844@gmail.com>
pkgname=device-mobvoi-catfish
pkgdesc="Mobvoi Ticwatch Pro"
pkgver=0.1
pkgrel=0
url="https://postmarketos.org"
license="MIT"
arch="armv7"
options="!check !archcheck"
depends="postmarketos-base linux-mobvoi-catfish mkbootimg mesa-dri-gallium"
makedepends="devicepkg-dev"
source="deviceinfo"

build() {
	devicepkg_build $startdir $pkgname
}

package() {
	devicepkg_package $startdir $pkgname
}

sha512sums="378c03baf66344f69b7d31270f382c4919528ed52280afdf13a2e840d39fba36669195414b585cf32359918fd35c8706c4c3963feaad6a4eb6c1a39ddb5f30c7  deviceinfo"
