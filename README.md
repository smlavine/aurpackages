# AUR packages

These are packages that I maintain for the
[Arch User Repository (AUR)](https://aur.archlinux.org).


## Notes (mainly for myself)

.SRCINFO is never updated manually.
It is generated using the following command:

	makepkg --printsrcinfo > .SRCINFO

Snapshots of AUR packages can be obtained with the following command:

	curl -O "https://aur.archlinux.org/cgit/aur.git/snapshot/${pkgname}.tar.gz"

The ```updpkgsums``` (pacman-contrib) script can be used to update the
checksums in a PKGBUILD.

# Packages

- [catgirl](https://aur.archlinux.org/packages/catgirl)

### References

https://wiki.archlinux.org/title/.SRCINFO#Generation
