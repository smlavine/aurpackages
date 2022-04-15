# [aurpackages](https://sr.ht/~smlavine/aurpackages)

These are packages that I maintain for the
[Arch User Repository (AUR)](https://aur.archlinux.org).

- [catgirl][catgirl-git] ([AUR][catgirl-aur], [upstream][catgirl-upstream])
- [jo][jo-git] (<s>[AUR][jo-aur]</s>, [upstream][jo-upstream])
	- No longer in AUR, [yoinked][jo-community] by a TU

[catgirl-git]: https://git.sr.ht/~smlavine/catgirl-aur
[catgirl-aur]: https://aur.archlinux.org/packages/catgirl
[catgirl-upstream]: https://git.causal.agency/catgirl/

[jo-git]: https://git.sr.ht/~smlavine/jo-aur
[jo-aur]: https://aur.archlinux.org/packages/jo
[jo-community]: https://archlinux.org/packages/jo
[jo-upstream]: https://github.com/jpmens/jo

## Notes (mainly for myself)

.SRCINFO is never updated manually.
It is generated using the following command:

	makepkg --printsrcinfo > .SRCINFO


Snapshots of AUR packages can be obtained with the following command:

	curl -O "https://aur.archlinux.org/cgit/aur.git/snapshot/${pkgname}.tar.gz"


AUR git repositories can be cloned from:

	ssh://aur@aur.archlinux.org/${pkgname}.git


The ```updpkgsums``` (pacman-contrib) script can be used to update the
checksums in a PKGBUILD.

### References

<https://wiki.archlinux.org/title/.SRCINFO#Generation>
