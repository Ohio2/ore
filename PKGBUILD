# Maintainer: Ohio2 <ohio2.mail@zohomail.eu>
pkgname=ore
pkgver=1
pkgrel=0
pkgdesc="(O)hio2's AU(R) helper & pacman wrapp(e)r"
arch=(x86_64)
url="https://github.com/Ohio2/ore"
license=('GPLv3')
install=
md5sums=()
validpgpkeys=()
prepare(){
 git clone $url
 cd ore
}
package() {
<<<<<<< HEAD
	install -Dm775 "$srcdir"/ore/ore "$pkgdir"/usr/bin/ore
  install -Dm644 "$srcdir"/ore/doc "$pkgdir"/usr/local/man/man1/ore.1
  gzip" $pkgdir"/usr/local/man/man1/ore.1 
=======
	install -Dm 775 $srcdir/ore/ore $pkgdir/usr/bin/ore
       #install -Dm 644 $srcdir/ore/doc $pkgdir/usr/local/man/man1/ore
>>>>>>> b20ddbd30202fa9b3ab5f2e6ffcff172a6f4ce30
}
