# Dvorak Custom layout
Custom keyboard layout to use with my macbook pro. It's a modified version of Dvorak Programmer.
- Base Layout: Dvorak Programmer (because I'm fancy like that).
- Numbers: Rearranged to match QWERTY—because muscle memory is a thing.
- Cmd: Turns—QWERTY mode for convenience. Less keyboard gymnastics for copy-pasta!
- Option + e: Accent tilde for spanish writting

Brasically, it's Dvorak, but with a few tricks.

![layout-img-0](Dvorak%20Programmer/dvorak-custom-0.jpg)

![layout-img-1](Dvorak%20Programmer/dvorak-custom-1.jpg)

![layout-img-2](Dvorak%20Programmer/dvorak-custom-2.jpg)

![layout-img-3](Dvorak%20Programmer/dvorak-custom-3.jpg)

# U.S. Custom layout
It's also nice to have the 'US Programmer' QWERTY custom bundle up your sleeve.

![us-programmer-base-layer](US%20Programmer/us-programmer-base-layer.png)
![us-programmer-shift-layer](US%20Programmer/us-programmer-shift-layer.png)

## Notes for bundle icons

1. Prepare a PNG image (ideally 1024x1024).
2. Create a folder for the icon set e.g. `mkdir icon.iconset`
3. Create PNGs for all icon sizes
```
sips -z 128 128   original.png --out icon.iconset/icon_128x128.png
sips -z 512 512   original.png --out icon.iconset/icon_512x512.png
...
```
4. use `iconutil` to convert the set to .icns
```
iconutil -c icns icon.iconset
``
In the same directory you'll get a `icon.icns` to add to the bundle.
