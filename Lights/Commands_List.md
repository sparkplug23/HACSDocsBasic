
description: Comprehensive list of Tasmota commands and how to use them

### Control

## Lights

Command|Options|Notes&ExampleJSON
:---|:---|:---
AnimationEnable<a class="cmnd" id="AnimationEnable"></a> | `Numbers, 0..1` <BR> `Solid RGBCCT` <BR> `Colour Select` <BR> `Slow Glow`, `Blend` <BR> `FirePlace01` | Example <BR> `{"AnimationEnable":1}`
Effects.Function<a class="cmnd" id="Effects.Function"></a> | `Numbers, 0..1` <BR> `Solid RGBCCT` <BR> `Colour Select` <BR> `Slow Glow`, `Blend` <BR> `FirePlace01` | Example <BR> `{"Effects":{"Function":1}}`<BR> `{"Effects":{"Function":"Slow Glow"}}`
AnimationMode<a class="cmnd" id="AnimationMode"></a>|@1 <BR> @2
Brightness<a class="cmnd" id="Brightness"></a>|Brightness <BR> `0..100`
Brightness_255<a class="cmnd" id="Brightness_255"></a>|Brightness full range <BR> `0..255`[`SetOption13`](#setoption13) 
BrightnessRGB<a class="cmnd" id="BrightnessRGB"></a>|BrightnessRGB <BR> `0..100` ['Hue'](#Hue) 
BrightnessRGB_255<a class="cmnd" id="BrightnessRGB_255"></a>|BrightnessRGB full range <BR> `0..255`
ColourPalette<a class="cmnd" id="ColourPalette"></a>|@1 <BR> @2
Colour<a class="cmnd" id="Colour"></a>|@1 <BR> @2
HardwareType<a class="cmnd" id="HardwareType"></a>|@1 <BR> @2
HSB<a class="cmnd" id="HSB"></a>|@1 <BR> @2
Hue<a class="cmnd" id="Hue"></a>|Active Solid Palette Hue <BR> `0..360`
LightPower<a class="cmnd" id="LightPower"></a>|@1 <BR> @2
PixelUpdateNum<a class="cmnd" id="PixelUpdateNum"></a>|@1 <BR> @2
PixelUpdatePerc<a class="cmnd" id="PixelUpdatePerc"></a>|@1 <BR> @2
PaletteGeneration<a class="cmnd" id="PaletteGeneration"></a>|@1 <BR> @2
ColourOrder<a class="cmnd" id="ColourOrder"></a>|@1 <BR> @2
RGBClock<a class="cmnd" id="RGBClock"></a>|@1 <BR> @2
rgbcct_linked<a class="cmnd" id="rgbcct_linked"></a>|@1 <BR> @2
RandomiseBrightnessMode<a class="cmnd" id="RandomiseBrightnessMode"></a>|@1 <BR> @2
ManualNumber<a class="cmnd" id="ManualNumber"></a>|@1 <BR> @2
PaletteEdit<a class="cmnd" id="PaletteEdit"></a>|@1 <BR> @2
CCT_TempPercentage<a class="cmnd" id="CCT_TempPercentage"></a>|@1 <BR> @2
CCT_Temp<a class="cmnd" id="CCT_Temp"></a>|@1 <BR> @2
SceneColour<a class="cmnd" id="SceneColour"></a>|@1 <BR> @2
SceneName<a class="cmnd" id="SceneName"></a>|@1 <BR> @2
Sat<a class="cmnd" id="Sat"></a>|Active Solid Palette Saturation <BR> `0..100`
Sat_255<a class="cmnd" id="Sat"></a>|Active Solid Palette Saturation <BR> `0..255`
LightSize<a class="cmnd" id="LightSize"></a>|@1 <BR> @2
Scene<a class="cmnd" id="Scene"></a>|@1 <BR> @2
Transition<a class="cmnd" id="Transition"></a>|@1 <BR> @2


Command|Parameters
:---|:---
AgedColouring<a class="cmnd" id="AgedColouring"></a>|@1 <BR> @2
Alternate<a class="cmnd" id="Alternate"></a>|@1 <BR> @2
AlternateAmount<a class="cmnd" id="AlternateAmount"></a>|@1 <BR> @2
AlternateBrightnessMax<a class="cmnd" id="AlternateBrightnessMax"></a>|@1 <BR> @2
AlternateBrightnessMin<a class="cmnd" id="AlternateBrightnessMin"></a>|@1 <BR> @2
RGBDataStream<a class="cmnd" id="RGBDataStream"></a>|@1 <BR> @2
Direction<a class="cmnd" id="Direction"></a>|@1 <BR> @2
Effects<a class="cmnd" id="Effects"></a>|@1 <BR> @2
Effects.Function<a class="cmnd" id="Effects.Function"></a>|@1 <BR> @2
Effects.ColourRefreshRate<a class="cmnd" id="Effects.ColourRefreshRate"></a>|@1 <BR> @2
Effects.Direction<a class="cmnd" id="Effects.Direction"></a>|@1 <BR> @2
Effects.AlternateBrightnessMax<a class="cmnd" id="Effects.AlternateBrightnessMax"></a>|@1 <BR> @2
Effects.AlternateBrightnessMin<a class="cmnd" id="Effects.AlternateBrightnessMin"></a>|@1 <BR> @2
Effects.AlternateAmount<a class="cmnd" id="Effects.AlternateAmount"></a>|@1 <BR> @2
Effects.AgedColouring<a class="cmnd" id="Effects.AgedColouring"></a>|@1 <BR> @2
Effects.Function<a class="cmnd" id="Effects.Function"></a>|@1 <BR> @2
`{"Effects":{"Function":#}}`<a class="cmnd" id="Effects.Function"></a>|@1 <BR> @2
Mixer<a class="cmnd" id="Mixer"></a>|@1 <BR> @2
Multiplier<a class="cmnd" id="Multiplier"></a>|@1 <BR> @2
MappedMultiplierData<a class="cmnd" id="MappedMultiplierData"></a>|@1 <BR> @2
PixelGrouping<a class="cmnd" id="PixelGrouping"></a>|@1 <BR> @2
PixelNum<a class="cmnd" id="PixelNum"></a>|@1 <BR> @2
ColourRefreshRate<a class="cmnd" id="ColourRefreshRate"></a>|@1 <BR> @2
RunningID<a class="cmnd" id="RunningID"></a>|@1 <BR> @2
ManualSetPixelToScene<a class="cmnd" id="ManualSetPixelToScene"></a>|@1 <BR> @2
TimeMultiplierAsPerc<a class="cmnd" id="TimeMultiplierAsPerc"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
TimeOn<a class="cmnd" id="TimeOn"></a>|@1 <BR> @2
Transition.Time<a class="cmnd" id="Transition.Time"></a>|@1 <BR> @2
Transition.TimeMs<a class="cmnd" id="Transition.TimeMs"></a>|@1 <BR> @2
Transition.Rate<a class="cmnd" id="Transition.Rate"></a>|@1 <BR> @2
Transition.RateMs<a class="cmnd" id="Transition.RateMs"></a>|@1 <BR> @2
Transition.Order<a class="cmnd" id="Transition.Order"></a>|@1 <BR> @2
Transition.UpdateNumber<a class="cmnd" id="Transition.UpdateNumber"></a>|@1 <BR> @2
Transition.UpdatePercentage<a class="cmnd" id="Transition.UpdatePercentage"></a>|@1 <BR> @2
PaletteEdit.ColourPalette<a class="cmnd" id="PaletteEdit.ColourPalette"></a>|@1 <BR> @2
Scene.Colour<a class="cmnd" id="Scene.Colour"></a>|@1 <BR> @2
PM_JSON_PIXELGROUPING.PM_JSON_AGED_COLOURING
PM_JSON_PIXELGROUPING.PM_JSON_MODE
PM_JSON_PIXELGROUPING.PM_JSON_MULTIPLIER
PM_JSON_PIXELGROUPING.PM_JSON_MAPPED_MULTIPLIER_DATA
PM_JSON_MIXER.PM_JSON_ENABLED
PM_JSON_MIXER.PM_JSON_TIME_SCALER_AS_PERCENTAGE
PM_JSON_MIXER.PM_JSON_RUNTIME_DURATION_SCALER_PERCENTAGE
PM_JSON_MIXER.PM_JSON_RUNNING_ID
PM_JSON_PALETTE_GENERATION.PM_JSON_RANDOMISE_BRIGHTNESS_MODE
PM_JSON_RGB_CLOCK.PM_JSON_MANUAL_NUMBER


Command|Accepts Type|Range|Example|Notes
:---|:---|:---|:---|:---
PM_JSON_NOTIFICATIONS.PM_JSON_PIXELNUM
PM_JSON_NOTIFICATIONS.PM_JSON_COLOUR
PM_JSON_NOTIFICATIONS.PM_JSON_HUE
PM_JSON_NOTIFICATIONS.PM_JSON_BRIGHTNESS
PM_JSON_NOTIFICATIONS.PM_JSON_SPEED
PM_JSON_NOTIFICATIONS.PM_JSON_MODE
PM_JSON_NOTIFICATIONS.PM_JSON_TIME_SECS
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2
#<a class="cmnd" id="#"></a>|@1 <BR> @2