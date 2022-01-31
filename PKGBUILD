# Maintainer: Matt C <mdc028[at]bucknell[dot]edu>
# Arch Contributor: Arch Linux Team
# Arch Contributor: Levente Polyak <anthraxx[at]archlinux[dot]org>
# Arch Contributor: Eli Schwartz <eschwartz@archlinux.org>

pkgname=base
pkgver=9
pkgrel=1
pkgdesc='Minimal package set to define a basic Crystal Linux installation'
url='https://getcryst.al'
arch=('any')
license=('GPL')
depends=(
  # very very base
  'gcc-libs' 'glibc' 'bash'

  # POSIX tools
  'coreutils' 'file' 'findutils' 'gawk' 'grep' 'procps-ng' 'sed' 'tar'

  # standard linux toolset
  'gettext' 'pciutils' 'psmisc' 'shadow' 'util-linux' 'bzip2' 'gzip' 'xz'

  # distro (Arch) defined requirements
  'licenses' 'pacman' 'systemd' 'systemd-sysvcompat'

  # Crystal specific modifications
  'amethyst' 'filesystem' 'crystal-keyring' 'sl' 'crystal-wallpapers'

  # networking, ping, etc
  'iputils' 'iproute2'
)
optdepends=(
  'linux: bare metal support'
)

# vim: ts=2 sw=2 et:








