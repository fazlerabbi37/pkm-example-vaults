# 202608201045 OpenWrt package size is bounded by overlay flash
Packages install to the overlay partition. On 8MB-flash routers the
usable overlay after base system is ~2MB, which rules out kiwix-serve
unless built into the image or run from extroot.

Links: [[202608201030-kiwix-serve-streams-from-disk]] [[202608211200-extroot-moves-overlay-to-usb]]
Tags: #openwrt #flash
