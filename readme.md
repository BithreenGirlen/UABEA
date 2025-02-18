<p align="center"><img src="UABEAvalonia/Assets/logo.png" /></p>

## UABEAvalonia
Fork from [UABEA](https://github.com/nesrak1/UABEA/tree/master), with ad-hoc command line interface to export multiple dumps.

### Background

As far as I know, UABEA seems to be only tool that can dump `Naninovel` script, but lacks method to dump multiple files at one time.

### Command-line to export dumps

```
UABEAvalonia batchexportdump <import directory> <export directory> -json
```
It is assumed that `<import directory>` is composed of decompressed `CAB` files. 

## Libraries

- [Avalonia](https://github.com/AvaloniaUI/Avalonia) (MIT license)
  - [Dock.Avalonia](https://github.com/wieslawsoltes/Dock) (MIT license)
  - [AvaloniaEdit](https://github.com/AvaloniaUI/AvaloniaEdit) (MIT license)
- [AssetsTools.NET](https://github.com/nesrak1/AssetsTools.NET/tree/upd21-with-inst) (MIT license)
  - [Cpp2IL](https://github.com/SamboyCoding/Cpp2IL) (MIT license)
  - [Mono.Cecil](https://github.com/jbevain/cecil) (MIT license)
  - [AssetRipper.TextureDecoder](https://github.com/AssetRipper/TextureDecoder) (MIT license)
- [ISPC Texture Compressor](https://github.com/GameTechDev/ISPCTextureCompressor) (MIT license)
- [Unity crnlib](https://github.com/Unity-Technologies/crunch/tree/unity) (zlib license)
- [PVRTexLib](https://developer.imaginationtech.com/pvrtextool) (PVRTexTool license)
- [ImageSharp](https://github.com/SixLabors/ImageSharp) (Apache License 2.0)
- [Fsb5Sharp](https://github.com/SamboyCoding/Fmod5Sharp) (MIT license)
- [Font Awesome](https://fontawesome.com) (CC BY 4.0 license)
