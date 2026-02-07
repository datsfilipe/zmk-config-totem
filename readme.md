<picture>
  <source media="(prefers-color-scheme: dark)" srcset="/docs/images/TOTEM_logo_dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="/docs/images/TOTEM_logo_bright.svg">
  <img alt="TOTEM logo font" src="/docs/images/TOTEM_logo_bright.svg">
</picture>

# Totem ZMK Config

Personal ZMK configuration for my Totem keyboard. Forked from [tupinikeebs/zmk-config-totem](https://github.com/tupinikeebs/zmk-config-totem).

TOTEM is a 38 key column-staggered split keyboard running [ZMK](https://zmk.dev/). It's meant to be used with a SEEED XIAO BLE or RP2040.

![TOTEM layout](/docs/images/TOTEM_layout.svg)

## Layout

Based on [Miryoku](https://github.com/manna-harbour/miryoku) with the following modifications:

![Keymap](https://github.com/datsfilipe/zmk-config-corne/raw/main/keymap-drawer/corne.svg)

- **QWERTY** base layer instead of Colemak-DH
- **Vim-style navigation** (hjkl = left/down/up/right) on NAV layer
- **Programmer-friendly symbols** on right side of SYM layer
- **Thumb rows**: Esc/MEDIA, Space/SYM, Tab/FUN | Del/NUM, Enter/NAV, Bksp
- **LALT on both sides** (no AltGr on base layer to avoid accented characters)
