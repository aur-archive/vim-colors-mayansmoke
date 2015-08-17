# Maintainer: Andy Weidenbaum <archbaum@gmail.com>

pkgname=vim-colors-mayansmoke
pkgver=2.0
_srcid=14049
pkgrel=3
pkgdesc="Pleasant and ergonomic light-background Vim color scheme, designed for long hours of coding and working"
arch=('any')
depends=('vim')
groups=('vim-plugins')
url="http://www.vim.org/scripts/script.php?script_id=3065"
license=('MIT')
source=(${pkgname}::http://www.vim.org/scripts/download_script.php?src_id=$_srcid)
sha256sums=('27cf7e304a8eae4de39b51f71101cef3388326eafc0cc64430f0a35e2ab771fc')
provides=('vim-colors-mayansmoke')
install=mayansmoke.install

package() {
  msg 'Installing...'
  install -Dm 644 "$srcdir/$pkgname" "$pkgdir/usr/share/vim/vimfiles/colors/mayansmoke.vim"
}
