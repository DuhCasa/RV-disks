Disk refurbishing utilities
===========================

[Zeitgeist, the Slovenian Sustainability Society] that work in direction of [Resource-based economy] is
[refurbishing old and unused PCs][1] so they can be used again by
underprivileged children/families in Slovenia.

[Resource-based economy]: http://thevenusproject.com/about/resource-based-economy
[Zeitgeist, the Slovenian Sustainability Society]: http://www.duh-casa.si/en
[1]: http://www.duh-casa.si/en/projekti/racunalniki-za-socialno-ogrozene/

There are a couple of tools in this repository:

- `create_image`, creates a rootfs archive of a particular Debian-based
  GNU/Linux operating system,
- `refurbish_disk`, refurbishes a disk by:

    - `wipe_disk`, securely wiping data on the disk,
    - `assess_disk`, assessing the quality and efficacy of the disk,
    - `copy_image`, copying over the image created by `create_image`.

For `refurbish_disk` (and parts) you need the dependencies listed in
`install_depends` (can be run on Debian-based systems, `./install_depends`).

All tools print a short **usage info when run without arguments**.
