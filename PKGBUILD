pkgname=vibecrate-git
pkgver=1.0.0
pkgrel=1
pkgdesc="VibeCrate — загрузчик медиа SoundCloud,TikTok,YouTube"
arch=('any')
url="https://github.com/obbsidiann/vibecrate"
license=('MIT')
depends=('python' 'yt-dlp')
makedepends=('git')
source=("$pkgname::git+https://github.com/obbsidiann/vibecrate.git")
sha256sums=('SKIP')

package() {
    cd "$srcdir/$pkgname"
    install -Dm755 vibecrate "$pkgdir/usr/bin/vibecrate"
}
