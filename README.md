# AEShiper

Bring Figma and supported Illustrator designs into Adobe After Effects as editable layers, organized precomps, raster assets, or a visual reference.

## Install AEShiper 1.7.0

Get the [AEShiper Figma plugin](https://www.figma.com/community/plugin/1678017504586586252/aeshiper) from Community. Download the matching **After Effects installer for your computer** from [the latest release](https://github.com/iboyshanto/AEShiper/releases/latest):

- **macOS:** save your project, fully quit After Effects, Illustrator and Blender, then open the DMG and run the included PKG. If the installer reports that AE is running, quit AE and reopen the PKG. This installer is not Apple Developer ID signed or notarized, so macOS may require per-item approval in Privacy & Security.
- **Windows x64:** run the Windows x64 EXE. It is currently unsigned, so Windows SmartScreen may show an unrecognized-app warning. A Windows ARM64 installer is still being tested and is not part of this stable release.

Save your AE project and quit After Effects, Illustrator and Blender before installing. The installer places the AEShiper companion, Illustrator panel, AEShiper Glass, AEShiper Paste and the Blender extension together. Restart AE and open **Window > Extensions > AEShiper** to activate or manage your license. Users updating from a ZXP installation should use the platform installer; they do not need a separate ZXP step.

## What's new in 1.7.0

- A cleaner Figma workspace with quick settings and focused shipping feedback.
- Refined Blender geometry, edge rounding and scoped post-import controls.
- Beta 3D workflows for Blender and native After Effects extrusion.
- Improved Illustrator clipping, fill and stroke matching.

## Ship to Blender

Install Blender 4.2 or later, then run the matching AEShiper platform installer. It installs and enables the Blender extension automatically. If you install Blender later, rerun the same AEShiper installer. Open Blender after installation; AEShiper starts its receiver automatically. Keep the licensed AEShiper After Effects background service running. In Figma's AEShiper Settings → General, enable **Blender 3D** at the bottom; the main button becomes **Ship to Blender**. Disable the toggle to return to AE.

Supported vectors and text become editable geometry; image textures use planes. Masks and clipping boundaries import as guides. The bundled Blender extension includes its GPL source and license. AE 3D extrusion uses the Cinema 4D renderer.

## Illustrator to After Effects

Open **Window > Extensions > AEShiper** in Illustrator. Select artwork, choose Current Comp or New Comp, then Ship to AE.

- Editable paths, fills, strokes, supported point/area text, linear/circular radial gradients and recognized parametric shapes.
- Push selection, Split layers or Single layer; optional hierarchy and outer precomp controls.
- Supported clipping paths, group opacity and blend modes.
- Mark selected groups as images while leaving siblings editable, or ship each selected root as PNG at 1x–4x. Original Illustrator artwork stays editable.

Requires Illustrator 2025+ and AE 2024+ (mixed text styling requires AE 24.3+). Save the AE project before image transfers. Transparency-panel opacity masks, arbitrary live Appearance effects and unsupported typography require explicit PNG export. This is not a promise of full Illustrator feature parity.

## New Figma text and shape capabilities

- Wrapped lists with editable body lines and marker outlines.
- Mixed text colors/opacity, linear/radial gradient ranges and richer decorations.
- Editable angular/diamond gradients, improved radial/affine gradients, smoothed corners and complex-stroke outlines.
- Nonblocking font notices and unsupported-paint warnings.

Complex paint/effect combinations and media paints retain documented limitations; no full feature-parity claim.

## Other capabilities

- Improved glass edges, inner shadows and clipping in editable shipments.
- More stable Texture approximation: contained surfaces and no frame-to-frame procedural Noise flicker in the tested scene.
- AEShiper Paste imports copied images, self-contained SVG, supported media files and GIF/SVG links into AE. Media and codec support depends on the installed AE version; SVG-to-shapes is available where supported.
- Native installers include the companion and its Glass/Paste components in one download.

See the [visual update overview](https://aeshiper.com/#new) and [copy-and-paste examples](https://aeshiper.com/#paste). These are illustrated workflows, not a pixel-exact promise for every Figma effect.

## License and privacy

Visit [AEShiper](https://aeshiper.com) to purchase or manage a license. The Figma plugin installs free; shipping to AE requires an activated license. AEShiper checks its license online at AE launch.

Artwork, layer data and asset paths stay on your computer through the local `127.0.0.1` bridge. License and device authorization metadata goes to AEShiper's backend. Update checks read this repository's `release.json`. No artwork uploads or analytics.

## Updates

Stable releases appear in the AE update card and Figma update notice. Save and quit AE, download the platform installer, then reopen AE. Figma plugin updates are distributed through Community.
