# Awesome Device Afterlife: setup notes

[Back to the illustrated collection](../README.md) · [中文入口](../README.zh-CN.md)

These are brief, source-derived routes into each project, not substitute installation manuals or executed test reports. Follow the linked upstream instructions for the exact version and device.

## Phones and tablets

<a id="alfredcamera"></a>

### AlfredCamera

**Phone → remote camera** · Available setup · Source reviewed 2026-10-26

**Device / input:** Camera: Android 5\+ or iOS 12\+

**You need:** Viewer: Android 7\+ or iOS 15\+; Network; Account

1. Install AlfredCamera on both devices\.
2. Sign in and assign Camera and Viewer roles\.
3. Pair them and verify the live feed\.

**Limits:** Cloud service; paid features and retention limits apply\.

[Project](https://alfred.camera/) · [Primary evidence](https://support.alfred.camera/hc/en-us/articles/360039719851-How-do-I-set-up-AlfredCamera)

**Evidence:** Official setup and current requirements reviewed; not tested\.

<a id="audiorelay"></a>

### AudioRelay

**Phone → wireless speaker** · Available setup · Source reviewed 2026-10-26

**Device / input:** Android 5\+ phone

**You need:** AudioRelay desktop app; Local network

1. Install AudioRelay on both devices\.
2. Start the desktop sender\.
3. Open Android Player and select the computer\.

**Limits:** Latency varies; paid Premium adds multiple receivers, custom quality and unlimited microphone use\. Sending other Android apps’ audio requires Android 10\+\.

[Project](https://audiorelay.net/downloads) · [Primary evidence](https://audiorelay.net/docs/windows/stream-audio-from-your-pc-to-your-phone)

**Evidence:** Official download requirements and instructions reviewed; not tested\.

<a id="droidcam"></a>

### DroidCam

**Phone → webcam** · Available setup · Source reviewed 2026-10-26

**Device / input:** Supported Android phone or iPhone

**You need:** Desktop client or OBS plugin; USB or local Wi\-Fi

1. Install the phone app and desktop client\.
2. Connect by the documented USB or Wi\-Fi route\.
3. Select DroidCam in the receiving application\.

**Limits:** Base features are free; paid Pro removes HD watermarks and unlocks options\. Check mobile OS requirements; older phones may need MJPEG\.

[Project](https://droidcam.app/) · [Primary evidence](https://droidcam.app/help/)

**Evidence:** Developer setup reviewed; no device test\.

<a id="gretel"></a>

### Gretel

**Android → focused appliance** · Available setup · Source reviewed 2026-10-26

**Device / input:** Android 8\+ devices; BOOX Nova Air \(developer\-tested\)

**You need:** Device must expose Android Home\-app selection

1. Install the release APK\.
2. Choose your single\-purpose app\.
3. Set Gretel as Home; double\-press Home for settings\.

**Limits:** Not a lock or parental control; Kindle/Fire unsupported\.

[Project](https://github.com/abeant/gretel) · [Primary evidence](https://github.com/abeant/gretel)

**Evidence:** Developer tests each release on Nova Air; our review only\.

<a id="mixbus-touchosc"></a>

### Mixbus TouchOSC Layout

**Tablet → studio control surface** · Available setup · Source reviewed 2026-10-26

**Device / input:** Older iPad\-sized iOS/Android tablet

**You need:** Paid TouchOSC MK1 app; Paid Mixbus 10 license; Local network

1. Import the supplied TouchOSC layout\.
2. Enable OSC in Mixbus preferences\.
3. Set matching host addresses and ports\.

**Limits:** Mixbus 8/9 OSC bugs; some compressor controls remain incomplete\.

[Project](https://github.com/nicbeu/Mixbus-TouchOSC-Layout) · [Primary evidence](https://github.com/nicbeu/Mixbus-TouchOSC-Layout)

**Evidence:** Author explicitly designed for older tablets; source review only\.

<a id="navigatorosm"></a>

### NavigatorOSM

**Old iPad → navigation display** · Available setup · Source reviewed 2026-10-26

**Device / input:** iPad mini 1 or iPad 2/3/4; iOS 9\.3\.5

**You need:** Existing jailbreak/AppSync setup; Working GPS source; Network

1. Follow the project’s certificate and compatibility prerequisites\.
2. Install its Cydia package or released IPA\.
3. Connect the documented GPS source and check positioning\.

**Limits:** Wi\-Fi models need GPS tethering; do not assume fully offline routing\.

[Project](https://github.com/vibe-maribit/NavigatorOSM) · [Primary evidence](https://vibe-maribit.github.io/NavigatorOSM/)

**Evidence:** Developer shows real iPad mini 1 screenshots; not tested here\.

<a id="octo4a"></a>

### Octo4a

**Phone → printer host** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for Octo4a](../assets/octo4a.svg)

**Device / input:** Android 5\+ phone

**You need:** USB OTG; 700 MB free storage; Compatible USB printer

1. Install the release APK\.
2. Run Install OctoPrint with internet access\.
3. Connect the printer through OTG; finish browser setup\.

**Limits:** Charging during OTG varies by phone\.

[Project](https://github.com/feelfreelinux/octo4a) · [Primary evidence](https://github.com/feelfreelinux/octo4a/wiki/FAQ)

**Evidence:** Upstream setup and compatibility review; not tested here\.

<a id="openphotoframe"></a>

### OpenPhotoFrame

**Tablet → private photo frame** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for OpenPhotoFrame](../assets/openphotoframe.svg)

**Device / input:** Android 7\+ tablet; matching CPU architecture

**You need:** Local photos or Nextcloud share

1. Install the matching release APK\.
2. Choose local photos or a Nextcloud share\.
3. Set slide duration and synchronization interval\.

**Limits:** F\-Droid availability is unconfirmed; choose the correct APK architecture\.

[Project](https://github.com/micw/OpenPhotoFrame) · [Primary evidence](https://github.com/micw/OpenPhotoFrame/releases/tag/v1.12.1) · [Source code](https://github.com/micw/OpenPhotoFrame)

**Evidence:** Release APKs verified; source minSdk 24\. README installation text lags; not tested\.

<a id="phyphox"></a>

### phyphox

**Phone → pocket laboratory** · Available setup · Source reviewed 2026-10-26

**Device / input:** Android 4\+ phone; iPhone with iOS 12\+

**You need:** Sensors required by the chosen experiment

1. Install the stable app\.
2. Choose an experiment supported by the phone\.
3. Record and export measurements or save the state\.

**Limits:** Available measurements depend on actual sensors; readings need interpretation\.

[Project](https://phyphox.org/) · [Primary evidence](https://apps.apple.com/us/app/phyphox/id1127319693)

**Evidence:** Current App Store minimum supersedes older iOS FAQ; Android FAQ reviewed\. Not tested\.

<a id="spacedesk"></a>

### spacedesk

**Tablet → second monitor** · Available setup · Source reviewed 2026-10-26

**Device / input:** Android 5\+ tablet; iOS 9\.3\+ iPad

**You need:** Windows 10/11 host; LAN or supported USB connection

1. Install the host driver\.
2. Install the tablet viewer and connect\.
3. Choose extended desktop in display settings\.

**Limits:** Free for non\-commercial use; standard business use requires a paid license\. Free driver versions expire and need updating; connection support varies by OS\.

[Project](https://www.spacedesk.net/) · [Primary evidence](https://manual.spacedesk.net/SystemRequirements1.html) · [Upstream visual / demo](https://www.youtube.com/watch?v=YkWZSwBD-XY)

**Evidence:** Current official compatibility table reviewed; not device\-tested\.

**Visual credit / context:** Developer video linked from official Google Play listing; link only, reuse license not established\.

<a id="superdisplay"></a>

### SuperDisplay

**Pen tablet → drawing display** · Available setup · Source reviewed 2026-10-26

**Device / input:** Compatible Android tablet with stylus

**You need:** Windows 10 1703\+ 64\-bit; Windows driver; USB; Paid unlock after the three\-day trial

1. Install the Android app and Windows driver\.
2. Connect the tablet by USB\.
3. Open desktop drawing software and test pen pressure\.

**Limits:** One Android display per PC; verify pen and PC compatibility during the trial\.

[Project](https://superdisplay.app/) · [Primary evidence](https://superdisplay.app/help/)

**Evidence:** Official stylus and host requirements reviewed; not tested\.

## E\-readers

<a id="desk-buddy"></a>

### Desk Buddy

**Paperwhite → desk companion** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for Desk Buddy](../assets/desk-buddy.svg)

**Device / input:** Paperwhite 2; firmware 5\.12\.x

**You need:** Jailbreak with hotfix; macOS 13\+; 2\.4 GHz WPA2 Wi\-Fi

1. Install the desktop app\.
2. Connect Kindle by USB and transfer Desk Buddy\.
3. Open it from the Kindle library\.

**Limits:** Other Kindles unconfirmed; Windows version is early testing; Mac must remain awake\.

[Project](https://github.com/deskbuddy-app/desk-buddy) · [Primary evidence](https://github.com/deskbuddy-app/desk-buddy)

**Evidence:** Author daily\-tests Paperwhite 2; our source review only\.

<a id="kindle-carousel"></a>

### Kindle Carousel

**Kindle → interactive dashboard** · Source / DIY build · Source reviewed 2026-10-26

**Device / input:** Kindle 3 Keyboard; Kindle 4 non\-touch

**You need:** Jailbreak and SSH; Screenshot server; Wi\-Fi

1. Deploy the web frontends\.
2. Configure the screenshot server\.
3. Install the Kindle client and assign dashboard rotation\.

**Limits:** Button listening reduces battery life to days\.

[Project](https://github.com/qadzek/kindle-carousel) · [Primary evidence](https://github.com/qadzek/kindle-carousel) · [Upstream visual / demo](https://www.youtube.com/shorts/efZBwJXBD3U)

**Evidence:** Author documents these two models; source review only\.

**Visual credit / context:** Author demo linked in README; video fetch throttled; no reuse license established\.

<a id="koreader"></a>

### KOReader

**E\-reader → reference library** · Available setup · Source reviewed 2026-10-26

**Device / input:** Supported Kindle, Kobo, PocketBook and other listed models

**You need:** Model\-specific installation prerequisites; DRM\-free documents

1. Check the model’s installation guide\.
2. Install its matching release package\.
3. Add documents and configure reading or dictionary options\.

**Limits:** Installation differs by model; Kindle generally requires jailbreak\.

[Project](https://github.com/koreader/koreader) · [Primary evidence](https://github.com/koreader/koreader)

**Evidence:** Upstream platform list and installation links reviewed; not tested\.

## Computers

<a id="batocera"></a>

### Batocera

**PC → retro console** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for Batocera](../assets/batocera.svg)

**Device / input:** Compatible x86\-64 PC or laptop

**You need:** 16 GB drive minimum; 32 GB recommended; Controller; Your own game files

1. Download the matching image\.
2. Write it to a spare drive and boot\.
3. Configure controls and add your game files\.

**Limits:** Emulation performance depends on hardware; flashing erases the selected drive\.

[Project](https://batocera.org/) · [Primary evidence](https://wiki.batocera.org/install_batocera) · [Upstream visual / demo](https://www.youtube.com/watch?v=KUfHAFyjby0)

**Evidence:** Official installer and old\-PC guidance reviewed; not tested\.

**Visual credit / context:** ETA PRIME demonstration linked by official Batocera installation guide; link only, reuse license not established\.

<a id="daphile"></a>

### Daphile

**PC → music appliance** · Available setup · Source reviewed 2026-10-26

**Device / input:** x86 computer; 32\-bit image available

**You need:** 512 MB RAM; 2 GB boot storage; Audio device; Browser controller

1. Write the ISO to USB\.
2. Boot and open its browser interface\.
3. Install to target storage and configure music/audio\.

**Limits:** Default installation deletes target storage; hardware audio support varies\.

[Project](https://www.daphile.com/) · [Primary evidence](https://www.daphile.com/download/DaphileInstallation.pdf) · [Upstream visual / demo](https://www.daphile.com/screenshots/audio_player.png)

**Evidence:** Official installation guide and current downloads reviewed; not tested\.

**Visual credit / context:** Daphile official screenshot; site reserves all rights\. Link for reference; no asset downloaded\.

<a id="home-assistant-os"></a>

### Home Assistant OS

**Mini PC → automation hub** · Available setup · Source reviewed 2026-10-26

**Device / input:** 64\-bit Intel/AMD computer with UEFI

**You need:** Ethernet; Internet for initial setup; Dedicated boot storage

1. Check UEFI and installation prerequisites\.
2. Write the generic x86\-64 OS image\.
3. Boot with Ethernet and finish browser onboarding\.

**Limits:** Image installation overwrites the selected drive; legacy BIOS is outside this guide\.

[Project](https://www.home-assistant.io/installation/generic-x86-64/) · [Primary evidence](https://www.home-assistant.io/installation/generic-x86-64/)

**Evidence:** Official generic\-PC installation reviewed; not tested\.

<a id="kiwix-server"></a>

### Kiwix Server

**PC → offline knowledge server** · Available setup · Source reviewed 2026-10-26

**Device / input:** Computer supported by available kiwix\-tools packages

**You need:** ZIM archives; Local network; Sufficient disk space

1. Install the appropriate kiwix\-tools package\.
2. Download chosen ZIM files while online\.
3. Start kiwix\-serve and open its LAN address\.

**Limits:** Archive size drives storage needs; archives are snapshots\.

[Project](https://get.kiwix.org/en/solutions/applications/kiwix-server/) · [Primary evidence](https://get.kiwix.org/en/solutions/applications/kiwix-server/)

**Evidence:** Official server distribution and usage reviewed; not tested\.

<a id="kolibri"></a>

### Kolibri

**Old PCs → offline classroom** · Available setup · Source reviewed 2026-10-26

**Device / input:** Linux/Windows computer; very old PCs can be clients

**You need:** Server: 1 GB Linux / 2 GB Windows RAM recommended; Content storage

1. Install the OS\-specific package\.
2. Complete facility setup and import channels\.
3. Connect classroom browsers over the local network\.

**Limits:** Download/import content first; client video playback needs compatible drivers\.

[Project](https://learningequality.org/kolibri/) · [Primary evidence](https://kolibri.readthedocs.io/en/latest/install/system_requirements.html)

**Evidence:** Official requirements and installation guide reviewed; not tested\.

<a id="libreelec"></a>

### LibreELEC

**PC → living\-room media player** · Available setup · Source reviewed 2026-10-26

**Device / input:** Compatible x86\-64 PC, nettop or laptop

**You need:** Matching Generic or Generic\-legacy image; Boot drive

1. Choose the hardware\-appropriate image\.
2. Create boot media with the official tool\.
3. Boot and configure Kodi media sources\.

**Limits:** Very old drivers may be absent; NVIDIA needs the appropriate legacy build\.

[Project](https://libreelec.tv/downloads/generic/) · [Primary evidence](https://wiki.libreelec.tv/hardware/intel-x86-64-generic)

**Evidence:** Official hardware and image documentation reviewed; not tested\.

<a id="openmediavault"></a>

### openmediavault

**PC → home NAS** · Available setup · Source reviewed 2026-10-26

**Device / input:** Debian\-supported computer

**You need:** 1 GB RAM minimum; more recommended; Storage and network

1. Install using the official guide\.
2. Create storage folders and user permissions\.
3. Enable the relevant shares and verify client access\.

**Limits:** Hardware support follows Debian; access needs both share and filesystem permissions\.

[Project](https://www.openmediavault.org/) · [Primary evidence](https://docs.openmediavault.org/en/latest/prerequisites.html)

**Evidence:** Official prerequisites and Samba documentation reviewed; not tested\.

## Routers

<a id="openwrt-access-point"></a>

### OpenWrt Bridged Access Point

**Router → additional Wi\-Fi coverage** · Available setup · Source reviewed 2026-10-26

**Device / input:** OpenWrt\-supported router; exact hardware revision matters

**You need:** Supported OpenWrt installed; Ethernet uplink; Main router

1. Check current model support\.
2. Apply the documented bridge and DHCP settings\.
3. Connect the LAN uplink and test clients\.

**Limits:** Older instructions may require DSA adaptation; unsupported/EOL models excluded\.

[Project](https://openwrt.org/docs/guide-user/network/wifi/wifiextenders/bridgedap) · [Primary evidence](https://openwrt.org/zh/docs/guide-user/network/wifi/dumbap)

**Evidence:** Official configuration indexed; direct English page presents bot challenge\. Not tested\.

## Consoles

<a id="pspdisp"></a>

### PSPdisp

**PSP → miniature PC terminal** · Archived / legacy · Source reviewed 2026-10-26

**Device / input:** PSP with custom firmware or HEN

**You need:** Compatible Windows PC; USB or Wi\-Fi

1. Install the documented Windows package\.
2. Copy PSPdisp into the PSP game folder\.
3. Launch both sides and select connection/display mode\.

**Limits:** Legacy experiment: extended\-display driver unsupported on Windows 8\+; fullscreen capture limitations\.

[Project](https://www.jjs.at/software/pspdisp.html) · [Primary evidence](https://www.jjs.at/software/pspdisp.html)

**Evidence:** Historical developer release and compatibility notes reviewed; not tested\.

<a id="wiimc"></a>

### WiiMC

**Wii → media player** · Available setup · Source reviewed 2026-10-26

**Device / input:** Nintendo Wii

**You need:** Homebrew Channel; Compatible SD/USB media

1. Install the matching WiiMC release\.
2. Copy media to compatible storage\.
3. Launch through Homebrew Channel and choose files\.

**Limits:** Current GitHub build is prerelease; NTFS was removed despite older setup docs\. Use FAT media\.

[Project](https://github.com/dborth/wiimc) · [Primary evidence](https://www.wiimc.org/documentation/setup/) · [Source code](https://github.com/dborth/wiimc)

**Evidence:** Project source and setup docs reviewed; not tested\.

## Retired connected devices

<a id="airconnect"></a>

### AirConnect

**Older speaker → AirPlay destination** · Available setup · Source reviewed 2026-10-26

**Device / input:** Supported Sonos/UPnP/Chromecast players

**You need:** Always\-running local bridge computer; Same network segment

1. Choose the platform’s prebuilt binary\.
2. Run airupnp or aircast for the speaker type\.
3. Select the discovered AirPlay destination\.

**Limits:** Audio\-only; latency is unsuitable for synchronized video\.

[Project](https://github.com/philippe44/AirConnect) · [Primary evidence](https://github.com/philippe44/AirConnect)

**Evidence:** Upstream binaries and operation guide reviewed; not tested\.

<a id="gadgetbridge-pebble"></a>

### Gadgetbridge for Pebble

**Pebble → independent smartwatch** · Available setup · Source reviewed 2026-10-26

**Device / input:** Pebble Classic, Steel, Time and listed variants

**You need:** Supported Android phone; Bluetooth

1. Install Gadgetbridge\.
2. Follow the exact Pebble\-model pairing guide\.
3. Initialize the watch and configure supported features\.

**Limits:** Pairing/firmware procedures differ by generation; some models need migration firmware\.

[Project](https://gadgetbridge.org/gadgets/wearables/pebble/) · [Primary evidence](https://gadgetbridge.org/basics/pairing/pebble/)

**Evidence:** Maintainer support matrix and pairing guide reviewed; not tested\.

<a id="lyrion-squeezebox"></a>

### Lyrion Music Server

**Squeezebox → local music endpoint** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for Lyrion Music Server](../assets/lyrion-squeezebox.svg)

**Device / input:** Logitech Squeezebox Touch and supported players

**You need:** Supported server computer; Local music; Same network

1. Install Lyrion on the server\.
2. Configure its music library through the web interface\.
3. Connect the Squeezebox to the local server\.

**Limits:** A server must remain available; streaming\-service plugins have separate dependencies\.

[Project](https://lyrion.org/getting-started/) · [Primary evidence](https://preview.lyrion.org/players-and-controllers/squeezebox-touch/)

**Evidence:** Maintainer player and server setup docs reviewed; not tested\.

<a id="mirror-repurpose"></a>

### MIRROR Repurpose

**Fitness mirror → home display** · Available setup · Source reviewed 2026-10-26

**Device / input:** Qualcomm MIRROR; Android 6\.0\.1 IFC\-6309\-2\.0\-MIR/329

**You need:** Existing documented ADB/provisioning access; Matching APK

1. Confirm the exact hardware and firmware\.
2. Follow standard MirrorHome APK installation documentation\.
3. Set the home app and configure its display\.

**Limits:** Later NXP models unsupported; optional privileged helper excluded here\.

[Project](https://github.com/TimStewartJ/lululemon-mirror-repurpose) · [Primary evidence](https://github.com/TimStewartJ/lululemon-mirror-repurpose)

**Evidence:** Author device\-validates appliance; fresh\-stock installation not established\. Our source review only\.

<a id="unmetaportal"></a>

### unmetaportal

**Portal → Android appliance** · Available setup · Source reviewed 2026-10-26

![Conceptual workflow for unmetaportal](../assets/unmetaportal.svg)

**Device / input:** Portal/Portal\+ aloha; Portal TV ripley

**You need:** ADB\-enabled firmware; Authorized USB ADB; Platform tools

1. Confirm model/firmware and authorize ADB\.
2. Review the script dry run\.
3. Run the matching conversion profile and verify Home\.

**Limits:** Android 9 app limits; TV needs its separate launcher profile\.

[Project](https://github.com/fcjr/unmetaportal) · [Primary evidence](https://github.com/fcjr/unmetaportal)

**Evidence:** Developer tested Portal\+ build 1\.44\.4; broader profiles documented, not tested here\.
