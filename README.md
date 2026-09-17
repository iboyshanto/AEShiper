# AEShiper

Transfer selected Figma designs into Adobe After Effects as editable layers, organized precomps, raster assets, or a reference PNG.

## Install and activate

Download the signed **AEShiper 1.0.9 ZXP** and checksum from [GitHub Releases](https://github.com/iboyshanto/AEShiper/releases). Install with a compatible CEP ZXP installer, restart After Effects, and open **Window > Extensions > AEShiper** to activate your license. AEShiper checks your license online at each AE launch.

Version 1.0.9 preserves outside gradient strokes on clipped frames, reduces text-creation overhead in AE, and reduces repeated Figma API reads during export. One tested scene improved from 53.7 to 45.5 seconds; timings vary by scene and AE session. Install both updates for the complete fix.

Licensing uses the CEP runtime and system networking tools, with no bundled native networking executable. Older licensed companions keep supported transfers at 1× Design scale; the Figma plugin automatically resets unsupported saved scale settings. Design scale 1×–8× remains available on capable companions.

Install the companion from [Figma Community](https://www.figma.com/community/plugin/1678017504586586252/aeshiper). The Figma plugin download is free; shipping to AE requires an activated AEShiper license.

## Purchase

Visit [AEShiper](https://aeshiper.com) to sign in and request a one-time license. Current price: **799 BDT**. Send money to bKash **01646782474**, upload your payment screenshot, and wait for owner approval. Your approved license appears in your account dashboard. One active device per license.

## Updates

New stable releases show an AE update card and a dismissible Figma notification. Download the ZXP, save and close AE, install it with your ZXP installer, then reopen AE. Apple Developer enrollment is not required. Figma distributes published plugin updates through Community.

## Privacy

Artwork, layer data and asset paths stay on your computer through the local 127.0.0.1 bridge. License/device authorization metadata goes to the AEShiper backend. Update checks read this repository's release.json. No artwork uploads or analytics. Account and payment-proof submission happens on the website.

## Compatibility

Locally verified on macOS with After Effects Beta: online renewal, unlicensed transfer rejection, activated panel status and a real Figma shipment. No bundled native executable needs Gatekeeper approval. Windows, clean-machine installation and operation under a configured Adobe firewall block remain unverified. Older companion bugs require installing the fixed companion; compatibility does not repair already-installed code.
