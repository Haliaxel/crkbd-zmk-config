# crkbd-zmk-config

ZMK config for a wireless Corne (CRKBD) — **Comfort Edition v2** (Hebrew + English, lawyer layout).

- 4 layers: EN / SYM / NAV / FUN (tri-layer)
- No home-row mods · dedicated Shift & Ctrl · numbers on SYM home row
- Israeli legal characters (₪, ״, §, ©) via IBus/WinCompose Unicode macros

Firmware is built by GitHub Actions on every push. Download the `firmware` artifact
from the latest **Actions** run; flash `corne_left` then `corne_right` to each half
(double-tap reset, copy the `.uf2` to the `NICENANO` drive).
