# NoEscape Firmware Dumps

A collection of firmware dumps for various Android devices, maintained by **NoEscape.exe**.

This repository hosts extracted firmware components from official firmware packages for research, Android ROM development, kernel development, device bring-up, and proprietary blob analysis.

> **Repository:** https://gitlab.com/NoEscape-Firmware-Dumps

---

## About

The archive contains firmware dumps from a wide range of Android devices and OEMs.

Each dump is extracted from official firmware packages while preserving the original partition layout as closely as possible.

These dumps are useful for:

* Android ROM development
* Device tree bring-up
* Kernel development
* Vendor blob extraction
* Hardware abstraction analysis
* Porting proprietary components
* Reverse engineering and research

---

## Repository Structure

Each device typically contains extracted partitions such as:

* `boot`
* `vendor_boot`
* `vendor`
* `system`
* `product`
* `system_ext`
* `odm`
* `dtbo`
* `vbmeta`
* `vendor_dlkm`
* `system_dlkm`
* and other firmware images when available.

---

## Source

Firmware is extracted from official OTA packages or factory firmware using automated extraction tools and custom scripts.

No modifications are made to the extracted contents.

---

## Disclaimer

All firmware files belong to their respective manufacturers.

This repository is intended solely for development, educational, interoperability, and research purposes.

If you are the copyright owner and believe any content should be removed, please open an issue or contact the repository maintainer.

---

## Contributing

Contributions are welcome.

If you'd like to add firmware for a new device:

1. Extract it from an official firmware package.
2. Verify that the dump is complete.
3. Preserve the original partition names.
4. Submit a Merge Request.

---

## Credits

* **NoEscape** — Repository maintenance and firmware archive
* **DumprX** — Firmware extraction workflow and tooling
* Android open-source development community
