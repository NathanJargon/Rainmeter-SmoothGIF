# GifAnimation Rainmeter Skin

This is a Rainmeter skin that displays an animated GIF. The animation is achieved by cycling through individual frames of the GIF.

## Installation

1. Install [Rainmeter](https://www.rainmeter.net/).
2. Download this repository and extract it to your Rainmeter skins directory. The default location is `C:\Users\YourName\Documents\Rainmeter\Skins`.
3. Open the Rainmeter Manage window, find `GifAnimation` in the list of skins, and load it.

## Configuration

The skin is configured to display a GIF with 50 frames. The frames should be named `frame_00_delay-0.2s.gif`, `frame_01_delay-0.2s.gif`, etc., and placed in the `@Resources\Anim` folder.

You can adjust the number of frames by changing the `FrameCount` variable in the `[Variables]` section of the `gif.ini` file.

The skin updates every 50 milliseconds, and the measure updates every 100 milliseconds. You can adjust these values by changing the `Update` option in the `[Rainmeter]` section and the `UpdateDivider` option in the `[MeasureAnimation]` section of the `gif.ini` file.

## License

This project is licensed under the Creative Commons Attribution license.
