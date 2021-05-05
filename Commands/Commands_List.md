
description: Comprehensive list of Tasmota commands and how to use them

### Control

## Lights

rr
Command|Parameters
:---|:---
Hue<a class="cmnd" id="Hue"></a>|Active Solid Palette Hue <BR> `0..360`
Sat<a class="cmnd" id="Sat"></a>|Active Solid Palette Saturation <BR> `0..100`
Sat_255<a class="cmnd" id="Sat"></a>|Active Solid Palette Saturation <BR> `0..255`
Brightness<a class="cmnd" id="Brightness"></a>|Brightness <BR> `0..100`
Brightness_255<a class="cmnd" id="Brightness_255"></a>|Brightness full range <BR> `0..255`
BrightnessRGB<a class="cmnd" id="BrightnessRGB"></a>|BrightnessRGB <BR> `0..100`
BrightnessRGB_255<a class="cmnd" id="BrightnessRGB_255"></a>|BrightnessRGB full range <BR> `0..255`

Backlog0<a class="cmnd" id="backlog0"></a>|List of commands to be executed without any delay in sequence separated by  `;`<BR> See [Using Backlog](#the-power-of-backlog) for examples.
BlinkCount<a class="cmnd" id="blinkcount"></a>|Number of relay toggles ([blinks](#power)) _(does not control the status LED)_<BR> `0` = blink many times before restoring power state <BR> `1..32000` = set number of blinks *(default = `10`)*
BlinkTime<a class="cmnd" id="blinktime"></a>|`2..3600` set duration, in 0.1 second increments, to [blink](#power) aka toggle Power _(does not control the status LED)_
ButtonDebounce|Change the name of the toggle buttons of the WEB UI. This command accepts spaces in the name
See also|[`SetOption1`](#setoption1) - Set button multipress mode<BR>[`SetOption11`](#setoption11) - Swap pushbutton single and double press functionality<BR>[`SetOption13`](#setoption13) - Allow immediate action on single button press<BR>[`SetOption26`](#setoption26) - Use indexes even when only one relay is present<BR>[`SetOption31`](#setoption31) - Disable Wi-Fi LED status blinking<BR>[`SetOption32`](#setoption32) - Set hold interval before sending `HOLD` action<BR>[`SetOption40`](#setoption40) - Stop detecting any input change on button GPIO<BR>[`SetOption67`](#setoption67) - Enable/Disable Buzzer<BR>[`SetOption73`](#setoption73) - Decouple buttons from controlling power outputs
