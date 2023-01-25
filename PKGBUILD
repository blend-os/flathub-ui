pkgname=flathub-ui
pkgver=1.0
pkgrel=1
pkgdesc='User interface for flathub.org'
depends=('souk-next-git')
url='https://github.com/blend-os/flathub-ui'
arch=('any')
license=('Public domain')
source=('flathub-ui'
        'flathub-ui.desktop'
        'flathub-ui.svg')
sha256sums=('d9359bf10bd3ff8635cb20b63d9c29e8c5dd37b4339a5db696457c1f24e6460b'
            '2146a6a51dc15a12f48e4f3ba13086f38ad162bec3816c7ce5b9fba5c634858e'
            '8fe641d75825b0c099b5f5ecb8ee1b28ed95d28278c876f6d63a2ee61d7a6ef2')

package() {
	mkdir -p "$pkgdir"/usr/bin/; cp "$srcdir"/flathub-ui "$pkgdir"/usr/bin
        mkdir -p "$pkgdir"/usr/share/applications; cp "$srcdir"/flathub-ui.desktop "$pkgdir"/usr/share/applications
        mkdir -p "$pkgdir"/usr/share/icons/hicolor/scalable/apps; cp flathub-ui.svg "$pkgdir"/usr/share/icons/hicolor/scalable/apps
}
