# Awesome PocketCHIP / C.H.I.P. Resources

A curated link index for the **Next Thing Co. PocketC.H.I.P.** and **C.H.I.P.** single-board computer.

This repository prefers linking to primary sources, mirrors, archives, community projects, and external guides rather than duplicating their content. Repo-local notes are kept separately in [`docs/notes.md`](docs/notes.md).

> **Note:** Please consider subscribing to updates using GitHub's **Watch → Custom → Releases** feature rather than just starring the repository. We publish monthly releases containing the latest updates!

## Contents

* [Start Here](#start-here)
* [Firmware and Flash Images](#firmware-and-flash-images)
* [Flashing Tools](#flashing-tools)
* [Post-Flash Fixes](#post-flash-fixes)
* [Debian / Linux Repair](#debian--linux-repair)
* [Launchers and Interfaces](#launchers-and-interfaces)
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
  Community-maintained APT rescue proxy for the Next Thing Co. PocketC.H.I.P. and C.H.I.P.
* [CHIP Stuff - Max Glenister](https://blog.omgmog.net/post/chip-stuff/)
* [billys_chips.md](https://gist.github.com/billyargh/945616a654aee25d657beb1278a604d9)
* [How to get (re)started with a (Pocket)C.H.I.P.](https://gist.github.com/joshgiesbrecht/9f2857f64213d7c6f9480209b8953a14)
* [CHIP Flashing Guide - July 2020](https://www.reddit.com/r/ChipCommunity/comments/htkasm/chip_flashing_guide_july_2020/)

---

## Launchers and Interfaces

* [PocketCHIP Launcher (Marshmallow Edition)](https://github.com/o-marshmallow/PocketCHIP-pocket-home)
  Community-maintained fork of the PocketCHIP home screen with an APT repository and easier compilation.
* [pocketchip-menu](https://github.com/omgmog/pocketchip-menu)
  Experimental community-maintained Pygame replacement for the PocketCHIP home launcher, designed for Debian 11.

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

### Next Thing Co. Official Repositories

<details>
<summary>Expand to see all official Next Thing Co. repositories</summary>

* [ahoy](https://github.com/nextthingco/ahoy)
  No description provided. *(Official, Archived)*
* [armhf-debootstrap](https://github.com/nextthingco/armhf-debootstrap)
  No description provided. *(Official, Archived)*
* [B.O.B.](https://github.com/nextthingco/B.O.B.)
  No description provided. *(Official, Archived)*
* [bgfx](https://github.com/nextthingco/bgfx)
  No description provided. *(Official, Archived)*
* [blink](https://github.com/nextthingco/blink)
  No description provided. *(Official, Archived)*
* [buildroot](https://github.com/nextthingco/buildroot)
  No description provided. *(Official, Archived)*
* [bx](https://github.com/nextthingco/bx)
  No description provided. *(Official, Archived)*
* [cdb](https://github.com/nextthingco/cdb)
  No description provided. *(Official, Archived)*
* [chip-backup](https://github.com/nextthingco/chip-backup)
  No description provided. *(Official, Archived)*
* [CHIP-boot-repair](https://github.com/nextthingco/CHIP-boot-repair)
  No description provided. *(Official, Archived)*
* [chip-configs](https://github.com/nextthingco/chip-configs)
  No description provided. *(Official, Archived)*
* [chip-desktop-configs](https://github.com/nextthingco/chip-desktop-configs)
  No description provided. *(Official, Archived)*
* [CHIP-dt-overlays](https://github.com/nextthingco/CHIP-dt-overlays)
  No description provided. *(Official, Archived)*
* [chip-exit](https://github.com/nextthingco/chip-exit)
  No description provided. *(Official, Archived)*
* [chip-flasher](https://github.com/nextthingco/chip-flasher)
  No description provided. *(Official, Archived)*
* [CHIP-Hardware](https://github.com/nextthingco/CHIP-Hardware)
  No description provided. *(Official, Archived)*
* [CHIP-hwtest](https://github.com/nextthingco/CHIP-hwtest)
  No description provided. *(Official, Archived)*
* [chip-input-reset](https://github.com/nextthingco/chip-input-reset)
  No description provided. *(Official, Archived)*
* [chip-libsdl2](https://github.com/nextthingco/chip-libsdl2)
  No description provided. *(Official, Archived)*
* [CHIP-linux](https://github.com/nextthingco/CHIP-linux)
  No description provided. *(Official, Archived)*
* [chip-mali](https://github.com/nextthingco/chip-mali)
  No description provided. *(Official, Archived)*
* [chip-mali-userspace](https://github.com/nextthingco/chip-mali-userspace)
  No description provided. *(Official, Archived)*
* [chip-metapackage](https://github.com/nextthingco/chip-metapackage)
  No description provided. *(Official, Archived)*
* [chip-nand-scripts](https://github.com/nextthingco/chip-nand-scripts)
  No description provided. *(Official, Archived)*
* [chip-os-9-headless](https://github.com/nextthingco/chip-os-9-headless)
  No description provided. *(Official, Archived)*
* [chip-os-pro](https://github.com/nextthingco/chip-os-pro)
  No description provided. *(Official, Archived)*
* [CHIP-postchroot](https://github.com/nextthingco/CHIP-postchroot)
  No description provided. *(Official, Archived)*
* [chip-power](https://github.com/nextthingco/chip-power)
  No description provided. *(Official, Archived)*
* [chip-server](https://github.com/nextthingco/chip-server)
  No description provided. *(Official, Archived)*
* [chip-theme](https://github.com/nextthingco/chip-theme)
  No description provided. *(Official, Archived)*
* [CHIP-u-boot](https://github.com/nextthingco/CHIP-u-boot)
  No description provided. *(Official, Archived)*
* [chip_cloner](https://github.com/nextthingco/chip_cloner)
  No description provided. *(Official, Archived)*
* [CHIP_IO](https://github.com/nextthingco/CHIP_IO)
  No description provided. *(Official, Archived)*
* [CHIP_Pro-Hardware](https://github.com/nextthingco/CHIP_Pro-Hardware)
  No description provided. *(Official, Archived)*
* [chipcraft](https://github.com/nextthingco/chipcraft)
  No description provided. *(Official, Archived)*
* [chippro-vu-meter](https://github.com/nextthingco/chippro-vu-meter)
  No description provided. *(Official, Archived)*
* [ChippyRuxpin](https://github.com/nextthingco/ChippyRuxpin)
  No description provided. *(Official, Archived)*
* [chiptainer-rovercode](https://github.com/nextthingco/chiptainer-rovercode)
  No description provided. *(Official, Archived)*
* [chiptainer_alexa](https://github.com/nextthingco/chiptainer_alexa)
  No description provided. *(Official, Archived)*
* [chiptainer_alpine](https://github.com/nextthingco/chiptainer_alpine)
  No description provided. *(Official, Archived)*
* [chiptainer_debian](https://github.com/nextthingco/chiptainer_debian)
  No description provided. *(Official, Archived)*
* [chiptainer_example](https://github.com/nextthingco/chiptainer_example)
  No description provided. *(Official, Archived)*
* [chiptainer_octoprint](https://github.com/nextthingco/chiptainer_octoprint)
  No description provided. *(Official, Archived)*
* [chiptainer_python_io](https://github.com/nextthingco/chiptainer_python_io)
  No description provided. *(Official, Archived)*
* [chiptainer_spi_accelerometer](https://github.com/nextthingco/chiptainer_spi_accelerometer)
  No description provided. *(Official, Archived)*
* [chiptainer_vu_meter](https://github.com/nextthingco/chiptainer_vu_meter)
  No description provided. *(Official, Archived)*
* [chiptainer_wifi_access_point](https://github.com/nextthingco/chiptainer_wifi_access_point)
  No description provided. *(Official, Archived)*
* [chiptainers](https://github.com/nextthingco/chiptainers)
  No description provided. *(Official, Archived)*
* [deborah](https://github.com/nextthingco/deborah)
  No description provided. *(Official, Archived)*
* [debroofy](https://github.com/nextthingco/debroofy)
  No description provided. *(Official, Archived)*
* [Dev_Kit-Hardware](https://github.com/nextthingco/Dev_Kit-Hardware)
  No description provided. *(Official, Archived)*
* [DIP-HDMI-PCB](https://github.com/nextthingco/DIP-HDMI-PCB)
  No description provided. *(Official, Archived)*
* [DIP-VGA-PCB](https://github.com/nextthingco/DIP-VGA-PCB)
  No description provided. *(Official, Archived)*
* [DIPvendor](https://github.com/nextthingco/DIPvendor)
  No description provided. *(Official, Archived)*
* [docs](https://github.com/nextthingco/docs)
  No description provided. *(Official, Archived)*
* [drone](https://github.com/nextthingco/drone)
  No description provided. *(Official, Archived)*
* [dtc](https://github.com/nextthingco/dtc)
  No description provided. *(Official, Archived)*
* [factory-debian](https://github.com/nextthingco/factory-debian)
  No description provided. *(Official, Archived)*
* [factory-fixtures](https://github.com/nextthingco/factory-fixtures)
  No description provided. *(Official, Archived)*
* [fbtft](https://github.com/nextthingco/fbtft)
  No description provided. *(Official, Archived)*
* [fcctui](https://github.com/nextthingco/fcctui)
  No description provided. *(Official, Archived)*
* [fipit](https://github.com/nextthingco/fipit)
  No description provided. *(Official, Archived)*
* [freshmeshdemo](https://github.com/nextthingco/freshmeshdemo)
  No description provided. *(Official, Archived)*
* [gadget-bash](https://github.com/nextthingco/gadget-bash)
  No description provided. *(Official, Archived)*
* [gadget-buildroot](https://github.com/nextthingco/gadget-buildroot)
  No description provided. *(Official, Archived)*
* [Gadget-Docker-Examples](https://github.com/nextthingco/Gadget-Docker-Examples)
  No description provided. *(Official, Archived)*
* [gadget-examples](https://github.com/nextthingco/gadget-examples)
  No description provided. *(Official, Archived)*
* [gadget-inject-project](https://github.com/nextthingco/gadget-inject-project)
  No description provided. *(Official, Archived)*
* [Gadget-OS](https://github.com/nextthingco/Gadget-OS)
  No description provided. *(Official, Archived)*
* [gadget-shell](https://github.com/nextthingco/gadget-shell)
  No description provided. *(Official, Archived)*
* [gadget-tutorial](https://github.com/nextthingco/gadget-tutorial)
  No description provided. *(Official, Archived)*
* [gadget-update-server](https://github.com/nextthingco/gadget-update-server)
  No description provided. *(Official, Archived)*
* [gadgetcli](https://github.com/nextthingco/gadgetcli)
  No description provided. *(Official, Archived)*
* [gadgetosd](https://github.com/nextthingco/gadgetosd)
  No description provided. *(Official, Archived)*
* [golang-cmake-example](https://github.com/nextthingco/golang-cmake-example)
  No description provided. *(Official, Archived)*
* [gonnman](https://github.com/nextthingco/gonnman)
  No description provided. *(Official, Archived)*
* [google-assistant-demo](https://github.com/nextthingco/google-assistant-demo)
  No description provided. *(Official, Archived)*
* [ioquake3-gles](https://github.com/nextthingco/ioquake3-gles)
  No description provided. *(Official, Archived)*
* [kbuild](https://github.com/nextthingco/kbuild)
  No description provided. *(Official, Archived)*
* [libOttoHardware](https://github.com/nextthingco/libOttoHardware)
  No description provided. *(Official, Archived)*
* [libsoc](https://github.com/nextthingco/libsoc)
  No description provided. *(Official, Archived)*
* [libusb](https://github.com/nextthingco/libusb)
  No description provided. *(Official, Archived)*
* [linux](https://github.com/nextthingco/linux)
  No description provided. *(Official, Archived)*
* [logrus-gadget-formatter](https://github.com/nextthingco/logrus-gadget-formatter)
  No description provided. *(Official, Archived)*
* [Mega-PocketCHIP](https://github.com/nextthingco/Mega-PocketCHIP)
  No description provided. *(Official, Archived)*
* [MegaCHIP-Hardware](https://github.com/nextthingco/MegaCHIP-Hardware)
  No description provided. *(Official, Archived)*
* [meta-raspberrypi](https://github.com/nextthingco/meta-raspberrypi)
  No description provided. *(Official, Archived)*
* [MMA8451_Library](https://github.com/nextthingco/MMA8451_Library)
  No description provided. *(Official, Archived)*
* [Network-Interfaces-Script](https://github.com/nextthingco/Network-Interfaces-Script)
  No description provided. *(Official, Archived)*
* [nextthingco.github.io](https://github.com/nextthingco/nextthingco.github.io)
  No description provided. *(Official, Archived)*
* [ntc-chip-buildroot](https://github.com/nextthingco/ntc-chip-buildroot)
  No description provided. *(Official, Archived)*
* [ntc-CHIP-mtd-utils](https://github.com/nextthingco/ntc-CHIP-mtd-utils)
  No description provided. *(Official, Archived)*
* [ntc-CHIP-SDK](https://github.com/nextthingco/ntc-CHIP-SDK)
  No description provided. *(Official, Archived)*
* [OttDate](https://github.com/nextthingco/OttDate)
  No description provided. *(Official, Archived)*
* [otto-creator](https://github.com/nextthingco/otto-creator)
  No description provided. *(Official, Archived)*
* [otto-gfx](https://github.com/nextthingco/otto-gfx)
  No description provided. *(Official, Archived)*
* [otto-gif-mode](https://github.com/nextthingco/otto-gif-mode)
  No description provided. *(Official, Archived)*
* [otto-menu](https://github.com/nextthingco/otto-menu)
  No description provided. *(Official, Archived)*
* [otto-network-setup](https://github.com/nextthingco/otto-network-setup)
  No description provided. *(Official, Archived)*
* [otto-runner](https://github.com/nextthingco/otto-runner)
  No description provided. *(Official, Archived)*
* [otto-utils](https://github.com/nextthingco/otto-utils)
  No description provided. *(Official, Archived)*
* [otto-wifi-setup](https://github.com/nextthingco/otto-wifi-setup)
  No description provided. *(Official, Archived)*
* [pocketchip-batt](https://github.com/nextthingco/pocketchip-batt)
  No description provided. *(Official, Archived)*
* [pocketchip-configs](https://github.com/nextthingco/pocketchip-configs)
  No description provided. *(Official, Archived)*
* [PocketCHIP-Education](https://github.com/nextthingco/PocketCHIP-Education)
  No description provided. *(Official, Archived)*
* [pocketChip-keyboardPatch](https://github.com/nextthingco/pocketChip-keyboardPatch)
  No description provided. *(Official, Archived)*
* [pocketchip-keypad-patch](https://github.com/nextthingco/pocketchip-keypad-patch)
  No description provided. *(Official, Archived)*
* [pocketchip-leafpad](https://github.com/nextthingco/pocketchip-leafpad)
  No description provided. *(Official, Archived)*
* [pocketchip-load](https://github.com/nextthingco/pocketchip-load)
  No description provided. *(Official, Archived)*
* [pocketchip-localdoc](https://github.com/nextthingco/pocketchip-localdoc)
  No description provided. *(Official, Archived)*
* [PocketCHIP-Mechanical](https://github.com/nextthingco/PocketCHIP-Mechanical)
  No description provided. *(Official, Archived)*
* [pocketchip-onboard](https://github.com/nextthingco/pocketchip-onboard)
  No description provided. *(Official, Archived)*
* [PocketCHIP-PCB](https://github.com/nextthingco/PocketCHIP-PCB)
  No description provided. *(Official, Archived)*
* [pocketchip-pcmanfm](https://github.com/nextthingco/pocketchip-pcmanfm)
  No description provided. *(Official, Archived)*
* [PocketCHIP-pocket-home](https://github.com/nextthingco/PocketCHIP-pocket-home)
  No description provided. *(Official, Archived)*
* [PockulusCHIP](https://github.com/nextthingco/PockulusCHIP)
  No description provided. *(Official, Archived)*
* [rocketchip](https://github.com/nextthingco/rocketchip)
  No description provided. *(Official, Archived)*
* [rpi-buildroot](https://github.com/nextthingco/rpi-buildroot)
  No description provided. *(Official, Archived)*
* [rtl81xxc](https://github.com/nextthingco/rtl81xxc)
  No description provided. *(Official, Archived)*
* [RTL8723BS](https://github.com/nextthingco/RTL8723BS)
  No description provided. *(Official, Archived)*
* [rtl8723bs_bt](https://github.com/nextthingco/rtl8723bs_bt)
  No description provided. *(Official, Archived)*
* [RTL8723DS](https://github.com/nextthingco/RTL8723DS)
  No description provided. *(Official, Archived)*
* [rtl8723ds_bt](https://github.com/nextthingco/rtl8723ds_bt)
  No description provided. *(Official, Archived)*
* [sunxi-tools](https://github.com/nextthingco/sunxi-tools)
  No description provided. *(Official, Archived)*
* [ubonchi](https://github.com/nextthingco/ubonchi)
  No description provided. *(Official, Archived)*
* [wifi-connect](https://github.com/nextthingco/wifi-connect)
  No description provided. *(Official, Archived)*
* [wifi-onboarding](https://github.com/nextthingco/wifi-onboarding)
  No description provided. *(Official, Archived)*
* [x-chip-deb-repo](https://github.com/nextthingco/x-chip-deb-repo)
  A repository which builds the final output deb repo for chip/pocketchip *(Official, Archived)*
* [x-chip-debootstrap](https://github.com/nextthingco/x-chip-debootstrap)
  No description provided. *(Official, Archived)*
* [x-chip-linux-deb](https://github.com/nextthingco/x-chip-linux-deb)
  A repository for building linux for chip TheDebianWay *(Official, Archived)*
* [x-chip-os](https://github.com/nextthingco/x-chip-os)
  No description provided. *(Official, Archived)*
* [x-chip-tools](https://github.com/nextthingco/x-chip-tools)
  No description provided. *(Official, Archived)*
* [x-chip-uboot](https://github.com/nextthingco/x-chip-uboot)
  No description provided. *(Official, Archived)*
* [xf86-video-armsoc](https://github.com/nextthingco/xf86-video-armsoc)
  No description provided. *(Official, Archived)*

</details>

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
