# Maintainer: mitsuse <mitsuset - gmail>
pkgname=blohg
pkgver=0.13
pkgrel=1
pkgdesc="blohg is a simple and easy to use blog engine, that uses the Mercurial SCM as backend, to store the content of the posts and pages."
arch=("any")
url="http://blohg.org"
license=('GPL-2')
groups=()
depends=(
    'python2-docutils>=0.7'
    'python2-flask>=0.7'
    'python2-flask-babel>=0.6'
    'python2-flask-script>=0.3'
    'python2-frozen-flask>=0.7'
    'python2-jinja>=2.5.2'
    'python2-yaml'
    'python2-pygments'
    'mercurial')
makedepends=('python2-distribute')
optdepends=()
provides=()
conflicts=()
replaces=()
backup=()
options=()
install=
source=("https://pypi.python.org/packages/source/b/$pkgname/$pkgname-$pkgver.tar.gz")
md5sums=('de2c354619644047f6c19cd7ce2fbd34')

package() {
    cd $srcdir/$pkgname-$pkgver
    python2 setup.py install --root="$pkgdir" --optimize=1
}
