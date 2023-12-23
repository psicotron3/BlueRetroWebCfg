# BlueRetroWebCfg

https://psicotron3.github.io/BlueRetroWebCfg/

*** fork to try out different presets for 8bitdo m30 controller running firmware 1.10 - current version of Blueretro only work with firmware 1.15 and the button mapping is not very good for using the gamecube version with wii emulators.

Since v1.8.2-5-gb607dd2, without any changes to the code, the 8bitdo M30 can be paired in Switch Mode (start + y) and reconnect with start.

With this, I don't need to connect in d-input anymore, since Switch mode has that same button mapping.

*** Using with compiled version of my fork of [Software files repository](https://github.com/psicotron3/BlueRetro)

Button combinations functions
Their is two forms of button combo to activate macro functions:

Base1 + Base2 + Base3 + CommonFunction
Base1 + Base2 + Base3 + Base4 + RestrictedFunction
The default mapping for the base buttons is as follow:

LM (SNES L, PS L2) -> Base1
RM (SNES R, PS R2) -> Base2
MM (Start) -> Base3
RB Up (SNES X, PS Triangle) -> Base4
The default mapping for the common function last button:

RB Left (SNES Y, PS Square) -> System Reset
RB Down (SNES B, PS X) -> System Shutdown/Controller disconnect
RB Right (SNES A, PS Circle) -> Toggle BT pairing mode on/off
MS (Select) -> Toogle wired output mode between GamePad & GamePadAlt
The default mapping for the restricted function last button

D-pad Up -> Factory Reset
D-pad Down -> Disable BlueRetro (Deep sleep)

(https://github.com/darthcloud/BlueRetro/wiki#6---button-combinations-functions)

BlueRetro Web-Bluetooth configuration pages

Those pages are base on [Google Chrome Samples](https://github.com/GoogleChrome/samples)

More detail BlueRetro:\
[Main hackaday.io page](https://hackaday.io/project/170365-blueretro)\
[Software files repository](https://github.com/darthcloud/BlueRetro)
