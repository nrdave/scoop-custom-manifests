# Scoop Bucket/App List


[![Tests](https://github.com/nrdave/scoop-custom-manifests/actions/workflows/ci.yml/badge.svg)](https://github.com/nrdave/scoop-custom-manifests/actions/workflows/ci.yml)
[![Excavator](https://github.com/nrdave/scoop-custom-manifests/actions/workflows/excavator.yml/badge.svg)](https://github.com/nrdave/scoop-custom-manifests/actions/workflows/excavator.yml)

Template bucket for [Scoop](https://scoop.sh), the Windows command-line installer.

How do I install these manifests?
---------------------------------

To add this bucket, run `scoop bucket add scoop-custom-manifests https://github.com/nrdave/scoop-custom-manifests`. To install, do `scoop install <manifest>`.

How do I contribute new manifests?
----------------------------------

To make a new manifest contribution, please read the [Contributing Guide](https://github.com/ScoopInstaller/.github/blob/main/.github/CONTRIBUTING.md).

----

To install all apps I use
```
scoop bucket add main
scoop bucket add extras
scoop bucket add scoop-custom-manifests https://github.com/nrdave/scoop-custom-manifests
scoop install draw.io ffmpeg-shared firefox gimp hwinfo kdenlive libreoffice miktex mingw obs-studio pdfsam powertoys python texstudio ungoogled-chromium vlc vscodium winaero-tweaker windirstat youtube-dl spotx-np-custom
```
