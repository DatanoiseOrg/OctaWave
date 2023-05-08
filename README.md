# Datanoise OctaWave

## Introduction
The OctaWave is a portable ADAT Lightpipe to 8 channel analog audio DAC / converter. It seamlessly integrates with any ADAT components and gives you 8 3.5mm mono jack outputs.

![image](https://user-images.githubusercontent.com/6614616/236771236-a3d9f3f3-1a77-4650-a1be-34c1e42ce53b.png)

## Specifications

* Optical ADAT Lightpipe Input
* USB Type-C for Power Supply (with power filtering)
* Advanced Power Supply for DACs
* 24-bit Audio at 44/48kHz
* Clock extraction (slave) from ADAT with low-jitter (< 1.3ns) PLL
* -120dB noise floor typical
* 112dB Dynamic Range typical
* Mostly Linear Frequency Response (0.1dB non-linearity typical)
* Power and Link LEDs
* 8x 3.5mm Jacks (mono, mechanically stereo for more stability) with 2V RMS output level, DC-coupled
* Compact form factor (140x60x25mm)
* Very low < 1W power consumption

## Setup instructions

* Connect your ADAT output (e.g. from your Audio Interface, such as RME Digiface, MiniDSP MCHstreamer) with an optical cable to the ADAT input of the Octawave
* Make sure your Audio Interface is running at 44/48kHz Sample Rate. Sample Rates above 48kHz are not supported. Using 96kHz will result in only 4 audio outputs being available due to S/MUX
* Power the OctaWave DAC via USB Type-C. You can use a power bank (make sure it doesn’t shut down with too low power consumption), a 500mA USB Power Supply or connect it straigt to your computer. For lowest noise and best performance, we recommend using a brickwall adapter.
* Connect your outputs to your gear (mixer, effects, ..)

## Troubleshooting

Link LED is not lit?
* Check if your ADAT output is wired correctly. The port should be glowing red.
* Check if your sample rate is correct

Power LED not lit?
* Check if the Power Supply is connected or if the plug is correctly inserted.

## Companion devices

These are devices that are tested and proven to work good in combination with the OctaWave

* RME DigiFace (gives you up to 32 outputs with 4 OctaWaves)
* MiniDSP MCHStreamer (cheap solution to get ADAT outputs via USB)
