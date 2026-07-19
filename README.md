# Lo-fi Tape Piano

Lo-fi Tape Piano from Dehli Musikk includes the sound of a Louis Zwicki Pianette recorded with cassette tape recorder through 3 different microphones. The preamps of the tape recorder are slightly overdriven and the tape adds compression and harmonics as well as wow and flutter (pitch variation).

If you want the sound of a perfectly voiced and regulated grand piano, this may not be the samples for you. This is more like a Mellotron / Chamberlin version of the Pianette.

## Release notes

### Version 3.0.0 (2026-07-19)

- Added a plugin version. See the section "The plugin version".
- Added missing sample bindings.

### Version 2.0.0 (2025-04-17)

- Decent Sampler version released

### Version 1.0.0 (2020-05-17)

- EXS version released

## Included formats

- VST3 (macOS)
- AU (macOS)
- Standalone application (macOS)
- Decent Sampler (macOS, Windows and Linux)

The plugin version is currently released for macOS only.
Windows and Linux versions are planned.
Until then, the Decent Sampler version covers those platforms.

## The plugin version

The plugin is a self-contained instrument, available as VST3, AU and Standalone.
Samples, graphics and impulse responses are all embedded in the plugin itself, losslessly compressed, so there are no external files to install or locate.

The plugin has all the controls and features from the Decent Sampler version, including MIDI learn, the master volume fader with output meter, value readouts for the knobs and full DAW automation.
On top of that, the plugin version adds:

- Drift wheels next to the pitch and modulation wheels, adding a subtle random pitch and volume drift to each voice.
- A velocity curve setting in the settings menu.

## The Decent Sampler version

This version of Lo-fi Tape Piano is an instrument preset / sample library for Decent Sampler. If you're new to Decent Sampler, I recommend checking out [this guide][Decent Sampler guide] first.

## Technical specification

|                           | Sample rate | Bit depth | Channels   | Number of files | File size |
| ------------------------: | ----------: | --------: | ---------- | --------------: | --------: |
| **Telephone mic samples** |      48 kHz |    24 bit | 1 (mono)   |              82 | 159.70 MB |
| **Gooseneck mic samples** |      48 kHz |    24 bit | 1 (mono)   |              82 | 159.70 MB |
| **Condenser mic samples** |      48 kHz |    24 bit | 2 (stereo) |              82 | 318.20 MB |
|     **Impulse responses** |      48 kHz |    24 bit | 2 (stereo) |               2 |   1.70 MB |

## User Interface

|![Overview](/Screenshots/lo-fi-tape-piano.png)|
|:--:|
|Overview|

## About this repository

This repository contains the source for both the Decent Sampler library (the DecentSampler folder) and the plugin version.
The plugin is a thin wrapper around the shared Dehli Musikk sampler engine, and a converter translates the Decent Sampler library into the engine's native preset format at build time.
The audio files are not part of this repository, since the samples are a paid product.
The full version is available from [store.dehlimusikk.no][Gumroad profile].

[Gumroad profile]: https://store.dehlimusikk.no/
[Decent Sampler guide]: https://www.decentsamples.com/how-to-use-decent-sampler/
