# AEShiper

Bring Figma designs into Adobe After Effects as editable layers, organized precomps, raster assets, or a visual reference.

## Install AEShiper 1.1.1

Get the [AEShiper Figma plugin](https://www.figma.com/community/plugin/1678017504586586252/aeshiper) from Community. Download the matching **After Effects installer for your computer** from [the latest release](https://github.com/iboyshanto/AEShiper/releases/latest):

- **macOS:** save your project, fully quit every After Effects version, then open the DMG and run the included PKG. If the installer reports that AE is running, quit AE and reopen the PKG. This installer is not Apple Developer ID signed or notarized, so macOS may require per-item approval in Privacy & Security.
- **Windows x64:** run the Windows x64 EXE. It is currently unsigned, so Windows SmartScreen may show an unrecognized-app warning. A Windows ARM64 installer is still being tested and is not part of this stable release.

Save your AE project and quit After Effects before installing. The installer places the AEShiper companion, AEShiper Glass and AEShiper Paste together. Restart AE and open **Window > Extensions > AEShiper** to activate or manage your license. Users updating from a ZXP installation should use the platform installer; they do not need a separate ZXP step.

## What's new

- Create Matching Comp now accepts a selected visible frame, group, or image-fill shape in one click.
- After Ship, Figma shows names of fonts reported missing by Figma or AE while the transfer continues.
- One-drawing SVG groups preserve their Color Dodge or Soft Light blend for editable shapes.
- The AE update card can download and check a platform installer for future updates that publish installer metadata.

### Earlier 1.1.0 improvements

- Improved glass edges, inner shadows and clipping in editable shipments.
- More stable Texture approximation: contained surfaces and no frame-to-frame procedural Noise flicker in the tested scene.
- AEShiper Paste imports copied images, self-contained SVG, supported media files and GIF/SVG links into AE. Media and codec support depends on the installed AE version; SVG-to-shapes is available where supported.
- Native installers include the companion and its Glass/Paste components in one download.

See the [visual update overview](https://aeshiper.com/#new) and [copy-and-paste examples](https://aeshiper.com/#paste). These are illustrated workflows, not a pixel-exact promise for every Figma effect.

## License and privacy

Visit [AEShiper](https://aeshiper.com) to purchase or manage a license. The Figma plugin installs free; shipping to AE requires an activated license. AEShiper checks its license online at AE launch.

Artwork, layer data and asset paths stay on your computer through the local `127.0.0.1` bridge. License and device authorization metadata goes to AEShiper's backend. Update checks read this repository's `release.json`. No artwork uploads or analytics.

## Updates

Stable releases appear in the AE update card and Figma update notice. Existing 1.1.0 companions open the release page to download the 1.1.1 platform installer. From 1.1.1 onward, the AE card can download and verify a platform installer before opening it after AE quits. Complete the installer and reopen AE. Figma plugin updates are distributed through Community.
