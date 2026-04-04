# A Spice2x game patcher

This is based on the original, now-defunct patcher maintained by the two-torial team & contributors. I will try to keep updated patches available as I find them.

Do not share arcade data publicly. Support arcades when possible.

### URL: `https://patcher.573.moe`

## Usage

In the `Patches` menu in `spicecfg.exe`, click on `Import from URL`. Then paste `https://patcher.573.moe/` into the address bar. You can select which patches you'd like to use from the checklist. By default, patches will automatically apply when the game starts.

When patching on an arcade cabinet, you may have to `Overwrite game files` (easier) or [disable/reconfigure UWF](https://learn.microsoft.com/windows/configuration/unified-write-filter/uwfmgrexe) for your patches to save. Before overwriting any game files, *be sure to back up your original data*.

> [!CAUTION]
> Do not use the `Overwrite game files` option without having a good reason to do so.

### Manually adding patches

If you cannot import patches from URL, you may also directly download the patches from this repository.
Use [SUPPORTED.md](/SUPPORTED.md) to help find patches for your game version. Click on the identifier link, then click the download button (Download raw file) in the top right of the file that opens. Add the downloaded file to the `patches/` directory next to Spice *(If this folder doesn't exist, create it yourself)*. Your patches will be available in `spicecfg.exe` under `Patches`.


More information on game patching can be found at [this mirror](https://two-torial.maimaidxprism.plus/extras/patchsp2x/) of two-torial.