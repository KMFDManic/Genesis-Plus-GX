Genesis Xtreme GX is a fork of Genesis Plus GX, which is an open-source Sega 8/16 bit emulator focused on performance and speed over the former's accuracy and portability. Initially ported and developped on Gamecube / Wii consoles through [libogc / devkitPPC](http://sourceforge.net/projects/devkitpro/), this emulator's more stable implementations are now available on many other platforms through various frontends such as:

**P4PRIUM MP3 Support**

This build integrates custom MP3 decoding support for **P4PRIUM** via the [minimp3](https://github.com/lieff/minimp3) decoder by **lieff**.  
`minimp3` is a minimal, high-performance, public domain MP3 library well-suited for embedded use.

Only a single MP3 track is loaded into memory at a time, helping reduce memory overhead on low-spec hardware (e.g. SNESC, A30, PSC, etc).

This support is possible thanks to the reverse engineering efforts of the **Project Little Man (PLM)** community, who cracked the audio and data structures used in Paprium and enabled emulated support for one of the most advanced homebrew games on the Genesis platform.

**Initial P4PR1UM Support**

Meant for preservation of the incredibly expensive and rare cartridges that can cost hundreds of USD to obtain. No actual assets from said game are included in this code base. It is ultimately up to the end user to legally dump their own cartridges. More fix-ups to come related to this addition.

Official developers of the game — thank you so very much for the incredible experience. Now, I can let it rest on my shelf like those action figures never meant to be outside their boxes! 🕷🏁

Thanks to **ALL** who have had a part in reverse engineering the protection.


---

## 🎮 A Brief History of P4PR1UM

**P4PR1UM** (originally released as "Paprium") is an ambitious homebrew beat-'em-up developed and published by **WaterMelon Games**, the creators of *Pier Solar*. It was announced in 2012 under the codename **Project Y**, and after several years of development, delays, and community speculation, the game finally shipped in **December 2020** for the Sega Mega Drive/Genesis.

Designed to push the hardware to its limits, P4PR1UM utilized a custom cartridge with an embedded chip called the **DATENMEISTER (DT128M16VA1LT)** — containing an MCU, sound decoder, and additional RAM. This enabled hardware-level effects, digitized MP3-quality audio, and visual tricks never before seen on Sega's 16-bit platform.

Despite its technical brilliance, the game's launch was marred by years-long delays, missed updates, preorder confusion, and lack of transparency. These circumstances made the game incredibly rare and expensive — many units are still sealed or resold at exorbitant prices.

---

## 🧠 About Project Little Man (PLM)

**Project Little Man** is a grassroots initiative started by preservationists and reverse engineers determined to unlock the secrets of P4PR1UM.

Through careful memory tracing, reverse engineering of the cartridge logic, and code decompilation, PLM:
- Decoded the MP3 loading logic
- Mapped out the custom initialization routines and memory layout
- Identified crash points on real and emulated hardware
- Made it possible to run P4PR1UM on emulators like Genesis Plus GX

Their efforts helped democratize access to a game otherwise locked behind proprietary DRM and limited physical supply.

> Project Little Man operates with a preservation-first mindset, and does not distribute game assets. Their work empowers legal backup and personal use for cartridge owners.

---

## 🙏 Thanks to WaterMelon

While much of the game’s history is polarizing, credit is due to **WaterMelon Games** for creating a visually stunning and technically groundbreaking experience. P4PR1UM stands as a testament to what is possible on retro hardware with modern creativity.

We honor the artistic and technical efforts of the developers — even as we seek to ensure the game is preserved and playable for future generations of enthusiasts.

---
---

### ⚖️ Legal Precedents for Reverse Engineering:

**Sega v. Accolade**  
Established that reverse engineering for interoperability may constitute *fair use*, even when intermediate copies of code are made.

**Atari Games Corp. v. Nintendo of America**  
Affirmed that reverse engineering can be permissible when it’s the only way to access functional or unprotectable elements of software.

> This project exists primarily to **preserve and celebrate** a beloved gem of gaming history — one that many of us may never be able to obtain again due to limited supply and high demand.

If and when a digital version becomes available for modern platforms — I’ll be the first in line to purchase!

* [Retroarch (libretro)](http://www.libretro.com)
* [Bizhawk](http://tasvideos.org/Bizhawk.html)
* [OpenEmu](http://openemu.org/)

----

The source code, initially based on Genesis Plus 1.2a by [Charles MacDonald](http://www.techno-junk.org/) has been heavily modified & enhanced, with respect to original goals and design, in order to improve emulation accuracy as well as adding support for new peripherals, cartridge or console hardware and many other exciting [features](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/wiki/Features.md).

For more accurate emulation and higher compatibility, use (https://github.com/ekeeke/Genesis-Plus-GX/blob/master/wiki/Compatibility.md) the more stable fork/s with near 100% Genesis / Mega Drive, Sega/Mega CD, Master System, Game Gear & SG-1000 released software supported (including all unlicensed or pirate known dumps), also emulating backwards compatibility modes when available. All the people who contributed (directly or indirectly) to this project are listed on the [Credits](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/wiki/Credits.md) page.

----

Multi-platform sourcecode (core), which is made available for use under a specific non-commercial [license](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/LICENSE.txt), is maintained on [Bitbucket](https://bitbucket.org/eke/genesis-plus-gx/src/) / [Github](https://github.com/ekeeke/Genesis-Plus-GX) so that other Genesis Plus ports can benefit of it, as I really wish this emulator becomes a reference for _portable_ and _accurate_ Sega 8/16-bit emulation. If you ported this emulator to other platforms or need help porting it, feel free to contact me.

----

Latest official Gamecube / Wii standalone port (screenshots below) is available [here](https://github.com/ekeeke/Genesis-Plus-GX/tree/master/builds). Be sure to check the included [user manual](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/gx/docs/README.pdf) first. A [startup guide](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/wiki/Getting%20Started.md) and a [FAQ](https://github.com/ekeeke/Genesis-Plus-GX/blob/master/wiki/Frequently%20Asked%20Questions.md) are also available.

![MainMenu.png](https://bitbucket.org/repo/7AjE6M/images/3565283297-MainMenu.png)
![menu_load.png](https://bitbucket.org/repo/7AjE6M/images/164055790-menu_load.png)

![RomBrowser.png](https://bitbucket.org/repo/7AjE6M/images/1972035547-RomBrowser.png)
![CtrlMenu.png](https://bitbucket.org/repo/7AjE6M/images/2283464354-CtrlMenu.png)

----

You can also test latest compiled builds for Gamecube / Wii and Retroarch (Windows 32-bit version only) by downloading them from [here](https://github.com/ekeeke/Genesis-Plus-GX/tree/master/builds).

----

[![btn_donate_LG.gif](https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif)](https://www.paypal.com/cgi-bin/webscr?cmd=_s-xclick&hosted_button_id=2966212) If you like this project and want to show your appreciation, Paypal donations are always welcomed.