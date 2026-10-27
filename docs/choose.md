# Find a next job for your device

[Illustrated collection](../README.md) · [All setup notes](catalog.md)

Start with the model and software version you actually have. Then choose a role that fits the extra equipment you can supply. These routes summarize the catalog's reviewed sources; they have not been tried by this repository's maintainer.

| You already have | Start with | First condition to check |
| --- | --- | --- |
| Spare phone and a computer | [DroidCam](catalog.md#droidcam) | Phone OS and compatible desktop client |
| Android phone and a USB 3D printer | [Octo4a](catalog.md#octo4a) | OTG support and simultaneous charging |
| Old tablet and a Windows computer | [spacedesk](catalog.md#spacedesk) | Viewer OS and Windows driver support |
| Android tablet and a photo library | [OpenPhotoFrame](catalog.md#openphotoframe) | Android 7+ and a matching release APK |
| Paperwhite 2 and a Mac | [Desk Buddy](catalog.md#desk-buddy) | Exact firmware, jailbreak prerequisites and awake Mac |
| Spare PC and a controller | [Batocera](catalog.md#batocera) | Architecture, boot media and your game files |
| Spare PC and storage drives | [openmediavault](catalog.md#openmediavault) | Debian hardware support and storage plan |
| Spare PC for a classroom | [Kolibri](catalog.md#kolibri) | Content import and server/client resources |
| Supported router and an Ethernet cable | [OpenWrt access point](catalog.md#openwrt-access-point) | Exact hardware revision and current support |
| A Squeezebox and a local music library | [Lyrion](catalog.md#lyrion-squeezebox) | A separate server that remains available |
| Retired Portal with ADB-enabled firmware | [unmetaportal](catalog.md#unmetaportal) | Model/profile and authorized ADB access |

## Decide what “reuse” means for you

**A new peripheral:** A camera, second screen or controller generally still needs a host computer. Check both ends of the connection before selecting a project.

**A dedicated appliance:** A media player, local server or printer host takes over a job. Decide where its power, storage and network connection will come from. “Old” does not automatically mean inexpensive to run.

**Keeping a useful product alive:** A replacement companion app, local server or launcher may preserve a device whose original service is gone. The result can remain close to its old role; we include this explicitly rather than presenting every case as a transformation.

## Three choices worth making before installation

1. **Screen sharing or a separate desktop?** A video stream, mirror and extended monitor are different outcomes. Follow the chosen project's display mode and host requirements.
2. **Local files or an online service?** Decide whether accounts, subscriptions or a separate server fit your intended use. The catalog calls out known dependencies; missing details should be checked upstream.
3. **An app or a system change?** A launcher or viewer can be a small commitment. Writing an OS image replaces the selected drive; firmware-specific routes need model confirmation. Use the upstream process and back up anything needed before a destructive step.

For the quickest evaluation, pick one outcome, read its entire setup note, then inspect the upstream guide before buying accessories. A source-build or legacy label is a deliberate signal to investigate the route first.

## Still deciding?

Search the catalog by what you own:

```sh
python3 scripts/catalog.py search "Android"
python3 scripts/catalog.py search "PC" --status released
python3 scripts/catalog.py search --category "E-readers"
```

For a model not represented here, consult [OpenDeviceDB](https://opendevicedb.org/) and the [related specialist lists](landscape.md). Absence from this collection does not mean a device has no useful future.
