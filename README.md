flac2alac
=========

Simple shell script to convert flac to alac (Apple Lossless .m4a), with cover
image if available.

Install
-------

Install [flac](https://xiph.org/flac/), [FFmpeg](https://ffmpeg.org/) and
[AtomicParsley](https://github.com/wez/atomicparsley) first.

You can install them from homebrew on macOS:
```
brew install flac ffmpeg atomicparsley
```

Usage
-----

```
Convert flac file to alac.
Usage: flac2alac [-h] <file|dir>...

OPTIONS:
    -h: print help
    -v: log verbosely. this displays ffmpeg logs
    -y: always overwrite existing files
```

To use the script globally, clone the script to `/usr/local/bin` and
`chmod +x /usr/local/bin/flac2alac`.

