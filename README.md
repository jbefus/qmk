# Keyboard Config Repo for OLKB Drop Preonic

## Tooling

- [QMK Toolbox](https://qmk.fm/toolbox)
- [QMK Configurator](https://config.qmk.fm/)


Make sure to use following revision in qmk configurator when trying to compile new layouts

 - preonic/rev3_drop

## Via

[Via](https://usevia.app/) enables us to modify our layout on-the-fly.

To be able to use via the `rules.mk` file needs to contain

```C
VIA_ENABLE = yes
```
