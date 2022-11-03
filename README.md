# Ferris Sweep Layout for QMK and ZMK

This is a layout for [ferris sweep](https://github.com/davidphilipbarr/Sweep), supporting both QMK and ZMK.

I'm using macOS, with [Amethyst WM](https://github.com/ianyh/Amethyst), so I added Amethyst shortcuts.

Inspired by [duckyb's keymap](https://github.com/duckyb/zmk-sweep).

![keymap](./weevil.drawio.png)

## Quick start

### ZMK

If you have built your Sweep using nice!nano, that means your keyboard support bluetooth and you should use ZMK firmware.

For more ZMK information please refer to [ZMK document](https://zmk.dev/docs).

[Video tutorial](https://www.youtube.com/watch?v=G8cqcFQdHGk) about How to get start with ZMK by juyr.

### QMK

If you are using micro controllers which doesn't support bluetooth, you should use QMK then.

1. Move the <code>qmk</code> folder to <code>~/qmk_firmware/keyboards/ferris/keymaps/</code>.

2. Rename the folder to whatever you want, for me it's <code>weevil</code>.

3. Then compile:

```
qmk compile -kb ferris/sweep -km weevil
```

4. Flash the firmware using [QMK toolbox](https://github.com/qmk/qmk_toolbox) would be easy and handy. [Video tutorial](https://www.youtube.com/watch?v=fuBJbdCFF0Q).



## Modify

Keymaps are pretty personal, due to the language you use and preference. So you can change it to suit yourself.

Some references that may help you custom your own layout: 

* [QMK: Macro buttons](https://getreuer.info/posts/keyboards/macros/index.html)
* [QMK: Layer Lock key](https://getreuer.info/posts/keyboards/layer-lock/index.html)
* [QMK doc: combo](https://github.com/qmk/qmk_firmware/blob/master/docs/feature_combo.md)
* [ZMK docs](https://zmk.dev/docs)
* [Wireless Split Keyboard Primer](https://www.youtube.com/watch?v=G8cqcFQdHGk)

You can edit the [diagram file](./weevil.diawio) on [diagrams.net](https://www.diagrams.net/).

