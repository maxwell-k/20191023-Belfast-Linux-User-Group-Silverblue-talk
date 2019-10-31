# Fedora Silverblue

An informal presentation that I gave at the
[Belfast Linux User Group on 23 October 2019](https://www.meetup.com/belfast-lug/events/264951460/).
The talk was to probably 15 people. The speaker notes below were used with
separate tabs for the main links or images.

## Before Fedora Silverblue

![Me sailing on Stardust on Strangford Lough](2018-03-21-Stardust.jpg?raw=true "Stardust sailing on Strangford Lough")

1. Windows
2. Gentoo
3. Chrome OS, which is built on Gentoo
4. Alpine Linux including becoming a package maintainer
5. Some Debian or Ubuntu; going way back some Slackware

- Long term Chrome book user, first introduction to immutable desktop/laptop OS
- `chroots` at first Gentoo
- my current `chroot` [wrapper](https://gitlab.com/maxwell-k/cattle),
- Never any RedHat or derivatives
- I like RedHat, know a few people who work there
- Haven't seen a big impact from the IBM acquisition, "wait and see"
- Dan talked about Haskell, well I'm talk about shell scripts
- I like shell scripts

## The idea

![Slide share clip](https://image.slidesharecdn.com/thehistoryofpetsvscattle-no-ice-breaker-160930155423/95/the-history-of-pets-vs-cattle-and-using-it-properly-22-638.jpg "Getting value from 'Pets vs Cattle'")

I still have a
[small project called cattle](https://gitlab.com/maxwell-k/cattle)

Exciting because - my computer is the same as your computer

## Silverblue

<https://silverblue.fedoraproject.org>

- `libostree` and `rpm-ostree`
- Fedora underneath; `dnf`, `rpm`
- developer focused OS
- Toolbox
- Flatpak e.g. VLC, Slack, Firefox Nightly
- https://flathub.org/home
- contrast with layering, detail later

## `libostree` and `rpm-ostree`

<https://ostree.readthedocs.io/en/latest/>

- content addressed object store
- committing and downloading bootable file system trees
- atomic updates
- two steps forward, one step back: restart on every update

## Developer focussed

<https://podman.io>

- an end user that isn't a system administrator
- git, `podman`, `buildah`

## Toolbox

<https://github.com/containers/toolbox>

- pet containers
- recently adopted by http://github.com/containers/ ; so same place as `podman`,
  `buildah`
- shell script, plans to reimplement in go
- merging in <https://github.com/coreos/toolbox>
- running WINE

## "Flatpak"

<https://flathub.org/home>

## Layering

- Docker
- Chrome for a terminal emulator
