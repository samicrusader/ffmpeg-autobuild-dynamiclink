# FFmpeg Latest Autobuilds for Windows

Full credit for this project goes to [AnimMouse](https://github.com/AnimMouse/ffmpeg-autobuild).

![Build FFmpeg on push](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/workflows/Build%20FFmpeg%20on%20push/badge.svg)
![Build FFmpeg on pull request](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/workflows/Build%20FFmpeg%20on%20pull%20request/badge.svg)

[FFmpeg](https://ffmpeg.org/) latest nonfree git builds with additional libraries/dependencies.

[Downloads](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/releases)

## Why is this not a fork?

GitHub prevents forks of projects from having certain features, one of them being pushing releases to a fork using GitHub Actions. Why? Some comment on some issue I forgot about said it was something about security or something. I don't fucking know at all! yayayayayayaya

## What is included?

![image](https://github.com/samicrusader/ffmpeg-autobuild-dynamiclink/assets/89530830/3fed911d-42f2-4784-a305-0728d1a357ce)

FFmpeg binaries (`ff{mpeg,play,probe}.exe`) and libav .dll's (`{av{codec,device,filter,format,util},sw{scale,resample}}.dll`, !!Audacity users!!: avformat-\*.dll)

These builds are nonfree with Fraunhofer FDK AAC ([libfdk_aac](https://github.com/mstorsjo/fdk-aac)) & [Blackmagic's](https://www.blackmagicdesign.com/) [DeckLink](https://www.blackmagicdesign.com/products/decklink) included.

## Schedule

Release builds: Weekly or Every time [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) updates or someone updates the repository.\
Pre-release builds: Every 9:00 AM GMT-5 daily except weekends.

## Release Retention Policy

(TODO: fix this)

Release builds are kept for two years. Last 1 pre-release build are kept every time a release build are released.

## Credits

* Original repo is from [AnimMouse](https://github.com/AnimMouse/)
* Powered by [ffmpeg-windows-build-helpers](https://github.com/rdp/ffmpeg-windows-build-helpers) script to cross compile for Windows on Linux
* Uses [GitHub Actions](https://github.com/features/actions) to automatically compile FFmpeg
* Uses [Dependabot](https://dependabot.com/) to automatically update FFmpeg and the build helper

For other builds of FFmpeg built by others, goto [AnimMouse's list of FFmpeg Binaries](https://www.animmouse.com/p/ffmpeg-binaries/).
