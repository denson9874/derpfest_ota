# derpfest_ota

Over-the-air update information for denson9874's unofficial DerpFest builds:
husky (Pixel 8 Pro).

These builds ship a runtime overlay that points DerpFest's Updater here instead of
[DerpFest-AOSP/Updater-Stuff](https://github.com/DerpFest-AOSP/Updater-Stuff), which lists the
official builds. Those are signed with other keys, so this Updater must never offer them. The
overlay is removed if a device's build becomes official.

DerpFest is its own ROM: these builds are signed with DerpFest-only keys, and this repo is separate
from the Evolution X one. Moving between DerpFest and another ROM always needs a clean install.

- `builds/<device>.json`: the latest build, in the Updater's format. The download is the signed A/B
  OTA package on [SourceForge](https://sourceforge.net/projects/denson9874-s-user-builds/files/derpfest/).
- `changelogs/<device>.txt`: what changed in that build.
