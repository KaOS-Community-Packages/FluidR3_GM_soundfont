pkgname=FluidR3_GM_soundfont
pkgver=2
pkgrel=2
pkgdesc="Release 3 of Frank Wen's pro-quality GM/GS soundfont"
arch=('x86_64')
url="http://www.musescore.org/en/handbook/soundfont" "www.hammersound.com"
# Fluid R3, Copyright 2000-2002 Frank Wen.  All Rights Reserved.  Fluid.sf@gte.net
# Released to Public Domain on 12/25/01
license=('custom:Public Domain')
source=("http://www.musescore.org/download/fluid-soundfont.tar.gz")
md5sums=('bc0df95c7f3c33a82e606a5f4e601594')

package() {
  install -Dm0644 "$srcdir/FluidR3 GM2-2.SF2" "$pkgdir/usr/share/soundfonts/FluidR3_GM2-2.sf2"
  install -Dm0644 "$srcdir/Fluid R3- Readme.doc" "$pkgdir/usr/share/doc/fluid-soundfont/Fluid R3- Readme.doc"
  install -Dm0644 "$srcdir/Changelog.txt" "$pkgdir/usr/share/doc/fluid-soundfont/Changelog.txt"
}
