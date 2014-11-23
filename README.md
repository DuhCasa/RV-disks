Disk refurbishing utilities
===========================

Once Slovenian fraction of the [Zeitgeist Movement], [Duh časa], is
[refurbishing old and unused PCs][1] so they can be used again by
underprivileged children/families in Slovenia.

[Zeitgeist Movement]: http://www.thezeitgeistmovement.com/
[Duh časa]: http://www.duh-casa.si/
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
