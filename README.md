# AutoRoomEQ Desktop — public beta

[![Version](https://img.shields.io/github/v/release/Rexxus69/AutoRoomEQ-Desktop-Beta?include_prereleases&label=version&color=orange)](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)
[![Downloads latest](https://img.shields.io/github/downloads/Rexxus69/AutoRoomEQ-Desktop-Beta/latest/total?label=latest%20downloads)](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)
[![Total downloads](https://img.shields.io/github/downloads/Rexxus69/AutoRoomEQ-Desktop-Beta/total?label=total%20downloads)](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases)

**[⬇ Download the latest beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest/download/AutoRoomEQ_Desktop_beta_win64.zip)** ([release notes](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)) · Windows 10/11 x64 · single `.exe`, no installer

AutoRoomEQ Desktop is a room-correction workstation and a bit-perfect music player in one exe.
It is built around **AutoRoomEQ 2.1** by DSPxLab.

## Beta testers: 3 steps

1. **Before downloading**, open the [Beta feedback form](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/issues/new?template=beta-feedback.yml) and fill in **Section 1: your PC and audio setup**.
2. [Download the latest beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest/download/AutoRoomEQ_Desktop_beta_win64.zip), unzip it and run `AutoRoomEQ Desktop.exe`.
3. Use the app, then complete the same form: what worked, **the problems you found** (a list of typical problems is provided) and **your suggestions**.

## What's new

See the [release notes of the latest beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest). From 0.2.3 the app **updates itself**: when a new beta is out it shows *Update now*.

## What it does

- **Measure and correct your room.** Native sweep measurement works through ASIO or WASAPI. The app designs a FIR correction, which you can export as WAV/YAML/Equalizer APO or apply directly in the player.
- **Music player with a convolution engine.**
  - Partitioned FIR convolution in real time: it can replace a player + convolver setup for local files.
  - **Level-matched A/B**: Bypass and RoomEQ play at the same loudness.
  - Bit-perfect in Bypass at 0 dB; automatic DAC sample rate per track.
  - Library with search, browsing by artist, album, genre, composer and year, playlists, favourites, and lyrics and artwork fetched online.
  - Web radio with live metadata.
  - Streaming services (Qobuz, Tidal, Spotify…) are not built in. The app is a UPnP/DLNA renderer, so apps that can send a streaming service to a UPnP renderer should play through the correction (not tested with every app yet: feedback welcome); or use the Equalizer APO export to correct every app on the PC.
- **Phone remote.** Pair your phone by QR code or 6-digit code. The remote works on Wi-Fi and, through an encrypted relay, on mobile data.
- **UPnP/DLNA.** Your PC library is shared on the LAN as a MediaServer. The app also acts as a MediaRenderer, so other apps can play on it.
- **AutoRoomEQ Player for Android.** It pairs with the desktop app: it works as a remote, and you can exchange presets, playlists, favourites and mic calibration.
- **No sleep during playback.** Windows does not go to standby while music is playing or a measurement is running.

## Beta

- All PRO engine features are unlocked during the beta (a Gumroad licence still works as usual).
- Each beta build has a limited lifetime; when a new beta is out the app offers to update itself.
- Please report problems with the **[Beta feedback form](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/issues/new?template=beta-feedback.yml)**. If the app crashed or froze, attach the files in `%APPDATA%\AutoRoomEQ Desktop\logs` (log, `crash.txt`, `.dmp`).
- **Windows SmartScreen** may warn on first launch because the exe is not code-signed yet. Click *More info → Run anyway*.
- The **Microsoft WebView2 Runtime** is installed automatically if it is missing.

## Validation

The SHA-256 of each zip is in its release notes; the in-app update checks it before installing.

## Italiano

**[⬇ Scarica l'ultima beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest/download/AutoRoomEQ_Desktop_beta_win64.zip)** ([note di rilascio](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)). Funziona su Windows 10/11 a 64 bit ed è un singolo `.exe`, senza installazione.

Cosa trovi nell'app:

- misura e correzione acustica della stanza (AutoRoomEQ 2.1) con FIR;
- player con motore di convoluzione, bit-perfect in Bypass, A/B a livello allineato e frequenza del DAC automatica;
- libreria, radio, testi e copertine;
- telecomando dal telefono, sia in Wi-Fi sia con i dati mobili;
- server e renderer UPnP/DLNA;
- integrazione con AutoRoomEQ Player per Android.

Note sulla beta:

- Prima di scaricare compila la sezione 1 del **[modulo di feedback](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/issues/new?template=beta-feedback.yml)**, poi completalo dopo aver usato l'app.
- In caso di crash o blocchi allega i file in `%APPDATA%\AutoRoomEQ Desktop\logs`.
- Al primo avvio SmartScreen può mostrare un avviso: clicca *Ulteriori informazioni → Esegui comunque*.

---
© DSPxLab — AutoRoomEQ. Freeware beta for testing: all rights reserved. Redistribution and reverse engineering are not allowed. Source code is not public.
