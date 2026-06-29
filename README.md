# Awesome PocketCHIP / C.H.I.P. Resources

A curated link index for the **Next Thing Co. PocketC.H.I.P.** and **C.H.I.P.** single-board computer.

This repository prefers linking to primary sources, mirrors, archives, community projects, and external guides rather than duplicating their content. Repo-local notes are kept separately in [`docs/notes.md`](docs/notes.md).

## Contents

* [Start Here](#start-here)
* [Firmware and Flash Images](#firmware-and-flash-images)
* [Flashing Tools](#flashing-tools)
* [Post-Flash Fixes](#post-flash-fixes)
* [Debian / Linux Repair](#debian--linux-repair)
* [Alternative Operating Systems](#alternative-operating-systems)
* [Hardware Documentation](#hardware-documentation)
* [Official and Historical Archives](#official-and-historical-archives)
* [Community Hubs](#community-hubs)
* [Guides and Walkthroughs](#guides-and-walkthroughs)
* [PICO-8 and Game Dev](#pico-8-and-game-dev)
* [Repo-Local Notes](#repo-local-notes)
* [Contributing](#contributing)

---

## Start Here

* [C.H.I.P. Flash Collection - Internet Archive](https://archive.org/details/C.h.i.p.FlashCollection)
  Firmware images, flashing tools, source archives, SDK files, and mirrored Next Thing Co. materials.

* [r/ChipCommunity](https://www.reddit.com/r/ChipCommunity/)
  Current community troubleshooting and discussion.

* [Thore-Krug/Flash-CHIP](https://github.com/Thore-Krug/Flash-CHIP)
  Flashing environment for CHIP and PocketC.H.I.P.

* [SaltyCybernaut/PocketCHIP-flash-utils](https://github.com/SaltyCybernaut/PocketCHIP-flash-utils)
  Helper scripts for flashing PocketC.H.I.P. / C.H.I.P. firmware locally.

* [daisyUniverse/fixchip](https://github.com/daisyUniverse/fixchip)
  Post-flash repair script for stock PocketC.H.I.P. images.

---

## Firmware and Flash Images

* [C.H.I.P. Flash Collection - Internet Archive](https://archive.org/details/C.h.i.p.FlashCollection)
* [JF Possibilities CHIP Mirror](https://chip.jfpossibilities.com/)
* [JF Possibilities CHIP Images / Tools Mirror](https://chip.jfpossibilities.com/chip/)
* [Project-chip-crumbs GitHub organisation](https://github.com/Project-chip-crumbs)

Useful image families to look for:

* `stable-pocketchip-*`
* `testing-pocketchip-*`
* `stable-gui-*`
* `testing-gui-*`
* `stable-server-*`
* `testing-server-*`
* `buildroot-*`

See [`docs/notes.md`](docs/notes.md#firmware-image-types) for a short explanation of image types.

---

## Flashing Tools

* [CHIP-tools - Project-chip-crumbs](https://github.com/Project-chip-crumbs/CHIP-tools)
* [CHIP-SDK - ntc-chip-revived](https://github.com/ntc-chip-revived/CHIP-SDK)
* [CHIP-SDK - Project-chip-crumbs](https://github.com/Project-chip-crumbs/CHIP-SDK)
* [Thore-Krug/Flash-CHIP](https://github.com/Thore-Krug/Flash-CHIP)
* [SaltyCybernaut/PocketCHIP-flash-utils](https://github.com/SaltyCybernaut/PocketCHIP-flash-utils)
* [C.H.I.P. Flash Collection - Internet Archive](https://archive.org/details/C.h.i.p.FlashCollection)

Related upstream tooling:

* [sunxi-tools](https://github.com/linux-sunxi/sunxi-tools)
* [U-Boot](https://source.denx.de/u-boot/u-boot)
* [Android platform-tools / fastboot](https://developer.android.com/tools/releases/platform-tools)

See [`docs/notes.md`](docs/notes.md#fel-mode) for short local notes on FEL mode and common detection problems.

---

## Post-Flash Fixes

* [daisyUniverse/fixchip](https://github.com/daisyUniverse/fixchip)
* [Reddit: fixchip discussion](https://www.reddit.com/r/ChipCommunity/comments/16jkmpb/im_working_on_a_script_to_combine_a_bunch_of/)
* [CHIP Stuff - Max Glenister](https://blog.omgmog.net/post/chip-stuff/)
* [billys_chips.md](https://gist.github.com/billyargh/945616a654aee25d657beb1278a604d9)

---

## Debian / Linux Repair

* [JF Possibilities Debian Package Mirror](https://chip.jfpossibilities.com/chip/debian/)
* [arran4/pocketchip-apt-rescue](https://github.com/arran4/pocketchip-apt-rescue)
  APT rescue proxy for the Next Thing Co. PocketC.H.I.P. and C.H.I.P.
* [CHIP Stuff - Max Glenister](https://blog.omgmog.net/post/chip-stuff/)
* [billys_chips.md](https://gist.github.com/billyargh/945616a654aee25d657beb1278a604d9)
* [How to get (re)started with a (Pocket)C.H.I.P.](https://gist.github.com/joshgiesbrecht/9f2857f64213d7c6f9480209b8953a14)
* [CHIP Flashing Guide - July 2020](https://www.reddit.com/r/ChipCommunity/comments/htkasm/chip_flashing_guide_july_2020/)

---

## Alternative Operating Systems

* [postmarketOS wiki: Next Thing Co. CHIP](https://wiki.postmarketos.org/wiki/Next_Thing_Co._CHIP_%28ntc-chip%29)
* [FreeBSD forum: installation attempt on Pocket C.H.I.P.](https://forums.freebsd.org/threads/lets-try-to-perform-the-installation-of-freebsd-on-the-pocket-c-h-i-p.91766/)
* [linux-sunxi: NextThingCo CHIP](https://linux-sunxi.org/NextThingCo_CHIP)

---

## Hardware Documentation

* [PocketC.H.I.P. Documentation - JF Possibilities mirror](https://chip.jfpossibilities.com/docs/pocketchip.html)
* [C.H.I.P. Documentation - JF Possibilities mirror](https://chip.jfpossibilities.com/docs/chip.html)
* [PocketC.H.I.P. Documentation - docs.getchip.cc mirror](https://docs.getchip.cc/pocketchip)
* [NextThingCo GitHub archive](https://github.com/NextThingCo)
* [Project-chip-crumbs GitHub organisation](https://github.com/Project-chip-crumbs)
* [chip-hardware mirror](https://github.com/joelguittet/chip-hardware)
* [linux-sunxi: NextThingCo CHIP](https://linux-sunxi.org/NextThingCo_CHIP)

---

## Official and Historical Archives

* [NextThingCo GitHub archive](https://github.com/NextThingCo)
* [Project-chip-crumbs GitHub organisation](https://github.com/Project-chip-crumbs)
* [C.H.I.P. Flash Collection - Internet Archive](https://archive.org/details/C.h.i.p.FlashCollection)
* [Archived getchip.com](https://web.archive.org/web/*/https://getchip.com/)
* [Archived bbs.nextthing.co](https://web.archive.org/web/*/bbs.nextthing.co/)
* [Archived CHIP Community Wiki](https://web.archive.org/web/*/http://www.chip-community.org/)
* [JF Possibilities CHIP Mirror](https://chip.jfpossibilities.com/)
* [The C.H.I.P. is dead... or is it?](https://www.jfpossibilities.com/imo/chip-dead/)

---

## Community Hubs

* [r/ChipCommunity](https://www.reddit.com/r/ChipCommunity/)
* [Best up-to-date CHIP and PocketCHIP resources list?](https://www.reddit.com/r/ChipCommunity/comments/1o0k9db/best_uptodate_chip_and_pocketchip_resources_list/)
* [Current state of CHIP flashing: mostly broken](https://www.reddit.com/r/ChipCommunity/comments/9nm66i/current_state_of_chip_flashing_mostly_broken_we/)
* [Up-to-date way of flashing](https://www.reddit.com/r/ChipCommunity/comments/ywy6yy/up_to_date_way_of_flashing/)
* [CHIP Flashing Guide - July 2020](https://www.reddit.com/r/ChipCommunity/comments/htkasm/chip_flashing_guide_july_2020/)

---

## Guides and Walkthroughs

* [Reflashing the Pocket CHIP in 2023](https://cordelya.net/posts/2023/07/03/reflashing-the-pocket-chip-in-2023/)
* [NextThingCo Pocket C.H.I.P. Flashing Guide](https://medium.com/@0x1231/nextthingco-pocket-c-h-i-p-flashing-guide-3445492639e)
* [NextThingCo C.H.I.P. Flashing guide as of November 2018](https://gist.github.com/verticalgrain/deae2821213a891747e08e2d6492808a)
* [Flash C.H.I.P. and PocketCHIP from MacOS via Chrome in 2019](https://manuke.hateblo.jp/entry/2019/05/15/173715)
* [How to get (re)started with a (Pocket)C.H.I.P.](https://gist.github.com/joshgiesbrecht/9f2857f64213d7c6f9480209b8953a14)
* [billys_chips.md](https://gist.github.com/billyargh/945616a654aee25d657beb1278a604d9)
* [PocketChip notes gist](https://gist.github.com/BjoernSchilberg/0a2cebe41e2d0934693b3712b2200b2a)

---

## PICO-8 and Game Dev

* [PocketCHIP - PICO-8 Wiki](https://pico-8.fandom.com/wiki/PocketChip)
* [Lexaloffle BBS: PocketChip](https://www.lexaloffle.com/bbs/?tid=32943)

PICO-8 is proprietary/commercial software. Link only to legitimate PICO-8 resources.

---

## Contributing

Contributions are welcome.

Preferred contributions:

* working third-party links
* verified mirrors
* archived copies of dead official pages
* tested flashing guides
* hardware documentation
* repair notes
* post-flash fix scripts
* modern OS experiments
* dead-link reports

Please avoid copying large amounts of content from third-party sources. Prefer linking to original pages, mirrors, or archived snapshots.

When adding a resource, include:

* title
* URL
* short description
* whether it is official, mirrored, archived, community-maintained, or experimental
* date tested, if known (in commit message & pr)

---

## Disclaimer

C.H.I.P. and PocketC.H.I.P. are discontinued devices. Many original services, repositories, and flashing tools are dead, mirrored, or outdated. This repository is a community-maintained index, not an official source.
