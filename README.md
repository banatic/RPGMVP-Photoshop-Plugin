# RPGMVP Photoshop Plugin

This Photoshop plugin adds support for opening and saving `.rpgmvp` `.png_` image files — the encrypted PNG format used in RPG Maker MV/MZ.

---

##  Features

- Open `.rpgmvp` `.png_` files directly in Photoshop
- Save `.rpgmvp` `.png_` files directly in Photoshop
- Automatic decryption, encryption of header.
---

##  Installation

1. Download the `SimpleFormat.8bi` binary from [Releases](https://github.com/banatic/RPGMVP-Photoshop-Plugin/releases).
2. Copy the `.8bi` file into your Photoshop `Plug-ins` folder:
    - e.g., `C:\Program Files\Adobe\Adobe Photoshop 2023\Plug-ins`
3. Restart Photoshop.

---

## Known Limitations
Only RGB/RGBA PNGs are supported. (palette/grayscale unsupported)

---

## ⚠️ Disclaimer

The write (export) feature is **experimental** and may cause unintended behavior, including overwriting game assets.

> Use at your own risk.  
> I am **not responsible** for any damage, corruption, or loss resulting from use of this plugin.

## Credits

- Decryption logic inspired by [Petschko/RPG-Maker-MV-Decrypter](https://github.com/Petschko/RPG-Maker-MV-Decrypter)
