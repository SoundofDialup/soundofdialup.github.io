---
title: Fixes for common streaming problems
author: Sound of Dialup
pubDatetime: 2023-08-12T12:10:34.188Z
postSlug: fixes-for-common-streaming-problems
featured: false
draft: false
tags:
  - livestream
  - OBS
  - stream deck
description: How to fix some common hardware and software issues encountered while livestreaming.
---

This is a running record of some issues I've managed to solve that stemmed from using software and hardware for livestreaming. Please note that I only update solutions if I continue to encounter the same problem. Oftentimes issues reoccur a few times - to be irritating enough that I feel it necessary to document the fix -, and then I never have to deal with them again.

## Table of contents

## Software issues

### Can't hear audio for sources played in OBS

> Solution working as of **January, 2021**

👉 **In OBS**

1. Go to `Settings > Audio`
2. Scroll down to `Advanced`
3. Choose the Monitoring Device (e.g. Sample (TC-Helicon GoXLR Mini))

👉 **In Windows Volume Mixer**

1. Select the same monitoring audio channel from _Step 3_ above.
2. Check the volume of OBS (it's probably muted!)
3. If that doesn't work, restart OBS and repeat the above.

## Hardware issues

### Can't connect Stream Deck to OBS

> Solution working as of **January, 2021**

1. Delete `StreamDeckPlugin.dll` and `StreamDeckPlugin.pdb`

   ```bash
   C:\Program Files\OBS\obs-plugins\64bit
   ```

2. Download the [OBS Studio plugin installer](https://edge.elgato.com/egc/windows/sd/Stream_Deck_OBS_Plugin_5.3.2.35.msi) from Elgato.

3. Run the installer file.

4. Download the [OBS Studio plugin v2.0.3](https://edge.elgato.com/egc/sd_content/com.elgato.obsstudio.streamDeckPlugin) for Stream Deck.

5. Install the plugin with **com.elgato.obsstudio.streamDeckPlugin**

## What's all this then?

**[Stream Deck](https://www.elgato.com/us/en/p/stream-deck-mk2-black)** is a customizable control interface with programmable buttons, used by content creators for simplifying and enhancing tasks related to live streaming, video production, and multimedia activities.

**[OBS (Open Broadcaster Software)](https://obsproject.com/)** is a free and open-source tool used for live streaming and recording video content from a computer's screen and webcam, popular among various content creators and streamers.
