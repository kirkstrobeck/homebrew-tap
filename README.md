# homebrew-tap

Homebrew tap for kirkstrobeck's tools.

## gainmap

Convert images to Ultra HDR JPEG gain maps (ISO/TS 21496-1 / Android Ultra HDR / Apple Adaptive HDR).

### Install

```sh
brew tap kirkstrobeck/tap
brew install gainmap
```

Or in one command:

```sh
brew install kirkstrobeck/tap/gainmap
```

After install:

```sh
gainmap photo.jpg
gainmap -R ./shots -o ./out
gainmap --help
```

### Source

[github.com/kirkstrobeck/gainmaps.com](https://github.com/kirkstrobeck/gainmaps.com)
