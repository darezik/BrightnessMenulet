Brightness Menulet
==================

Allows you to control monitor brigthness via menu in status bar.

This is specifically for a configuration with two external monitors. It simulataneously
changes the settings for both the monitors.

Download app build: `BrightnessMenulet.zip`_.

.. _BrightnessMenulet.zip:
    https://raw.github.com/darezik/BrightnessMenulet/master/BrightnessMenulet.zip

.. image:: https://raw.github.com/darezik/BrightnessMenulet/master/screenshot.png

Change list:
............
- Caused multiple monitors to be affected.

Original:
- Fixed brightness control ( at least it works for my Dell monitor )
- Removed brightness value polling (too slow)
- Added OSD lock toggle
- Monitor based Color Presets for Standard and sRBG
- Preferences window for RGB, Contrast and Brightness controls
- More specific changes can be found in the commit history

Roadmap:
........

- Support for other monitor makes (Currently only tested on Dell and certian HP displays)
- Time based settings
- Custom presets
- Add keyboard bindings
- Add contrast control

Credits:
........

- 'Kalvin126' - Changes under Original
- `Alec Jacobson`_ - `original Brightness Menulet app`_ creator
- Jon Taylor - `DDC/CI bindings`_
- Victor Miroshnikov - copy&paste&debug job

.. _DDC/CI bindings:
    https://github.com/jontaylor/DDC-CI-Tools-for-OS-X

.. _Alec Jacobson:
    http://www.alecjacobson.com/weblog/

.. _original Brightness Menulet app:
    http://www.alecjacobson.com/weblog/?p=1127

.. _Kalvin126:
    https://github.com/Kalvin126/BrightnessMenulet
