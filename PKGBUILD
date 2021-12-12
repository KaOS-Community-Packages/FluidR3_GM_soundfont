pkgname=FluidR3_GM_soundfont
pkgver=3.1
pkgrel=1
pkgdesc="Release 3 of Frank Wen's pro-quality GM/GS soundfont"
arch=('x86_64')
url='http://www.hammersound.net'
license=('custom:MIT')
source=("http://cdn-fastly.deb.debian.org/debian/pool/main/f/fluid-soundfont/fluid-soundfont_${pkgver}.orig.tar.gz")
md5sums=('189bbdf70221018cbda536984b105dfa')

package() {
	local src="${srcdir}/fluid-soundfont-${pkgver}"
	local dest="${pkgdir}/usr/share/soundfonts"
	install -Dm0644 "${src}/FluidR3_GM.sf2" "${dest}/FluidR3_GM.sf2"
	install -Dm0644 "${src}/FluidR3_GS.sf2" "${dest}/FluidR3_GS.sf2"
	install -Dm0644 "${src}/README" "${pkgdir}/usr/share/doc/soundfont-fluid/README"
	install -Dm0644 "${src}/COPYING" "${pkgdir}/usr/share/licenses/soundfont-fluid/COPYING"
}
