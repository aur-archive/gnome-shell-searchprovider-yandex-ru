# Maintainer: Mikhail Mikhaylenko <sniff303@gmail.com>
pkgname=gnome-shell-searchprovider-yandex-ru
pkgver=3.4
pkgrel=1
pkgdesc="Adds a Yandex (Russian version) search engine to GNOME."
url="http://snoo.ru/"
arch=('any')
license=('GPL')
depends=('gnome-shell')
makedepends=('wget')

build() {
  wget "http://yandex.ru/opensearch.xml" -O yandex-ru.xml
  mkdir -p $pkgdir/usr/share/gnome-shell/open-search-providers
  cp yandex-ru.xml $pkgdir/usr/share/gnome-shell/open-search-providers
}

# vim:set ts=2 sw=2 et:
