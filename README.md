# [aurpackages](https://sr.ht/~smlavine/aurpackages)

These are packages that I maintain for the
[Arch User Repository (AUR)](https://aur.archlinux.org).

- [autojump-rs][autojump-rs-git] ([AUR][autojump-rs-aur], [upstream][autojump-rs-upstream])
- [catgirl][catgirl-git] ([AUR][catgirl-aur], [upstream][catgirl-upstream])
- [gmnitohtml][gmnitohtml-git] ([AUR][gmnitohtml-aur], [upstream][gmnitohtml-upstream])
- [kiln][kiln-git] ([AUR][kiln-aur], [upstream][kiln-upstream])
- [mdtohtml][mdtohtml-git] ([AUR][mdtohtml-aur], [upstream][mdtohtml-upstream])

[autojump-rs-git]: https://git.sr.ht/~smlavine/autojump-rs-aur
[autojump-rs-aur]: https://aur.archlinux.org/packages/autojump-rs
[autojump-rs-upstream]: https://github.com/xen0n/autojump-rs

[catgirl-git]: https://git.sr.ht/~smlavine/catgirl-aur
[catgirl-aur]: https://aur.archlinux.org/packages/catgirl
[catgirl-upstream]: https://git.causal.agency/catgirl/

[gmnitohtml-git]: https://git.sr.ht/~smlavine/gmnitohtml-aur
[gmnitohtml-aur]: https://aur.archlinux.org/packages/gmnitohtml
[gmnitohtml-upstream]: https://git.sr.ht/~adnano/gmnitohtml

[kiln-git]: https://git.sr.ht/~smlavine/kiln-aur
[kiln-aur]: https://aur.archlinux.org/packages/kiln
[kiln-upstream]: https://git.sr.ht/~adnano/kiln

[mdtohtml-git]: https://git.sr.ht/~smlavine/mdtohtml-aur
[mdtohtml-aur]: https://aur.archlinux.org/packages/mdtohtml
[mdtohtml-upstream]: https://git.sr.ht/~adnano/mdtohtml

## Notes (mainly for myself)

.SRCINFO is never updated manually.
It is generated using the following command:

	makepkg --printsrcinfo > .SRCINFO


Snapshots of AUR packages can be obtained with the following command:

	curl -O "https://aur.archlinux.org/cgit/aur.git/snapshot/${pkgname}.tar.gz"


AUR git repositories can be cloned from:

	ssh://aur@aur.archlinux.org/${pkgname}.git


The `updpkgsums` (pacman-contrib) script can be used to update the
checksums in a PKGBUILD.

### References

<https://wiki.archlinux.org/title/.SRCINFO#Generation>
