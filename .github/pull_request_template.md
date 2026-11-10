# ELOV PACKAGE REQUEST

### Brief description

> <--here-->


### PKGBUILD

```
# Maintainer: v1sta <realv1sta1233@gmail.com>

pkgname=package-name-here

pkgver=1.0

pkgrel=1

pkgdesc="Short description of what the script does"

arch=('any')

license=('MIT')

source=('script-filename.sh')

sha256sums=('SKIP')

package() {
    cd "$srcdir"
    # Install and rename into the system path
    install -Dm755 script-filename.sh "$pkgdir/usr/bin/$pkgname"

}

```

### SCRIPT

```

```

# REQUIREMENTS 

[ ] I have tested my package locally
[ ] It doesn't contain any sort of mallware
