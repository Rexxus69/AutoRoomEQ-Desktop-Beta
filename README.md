# AutoRoomEQ Desktop — public beta

**[⬇ Download the latest beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)** · Windows 10/11 x64 · single `.exe`, no installer

AutoRoomEQ Desktop is a room-correction workstation and a bit-perfect music player in one exe.
It is built around **AutoRoomEQ 2.1** by DSPxLab.

## What it does

- **Measure and correct your room.** Native sweep measurement works through ASIO or WASAPI. The app designs a FIR correction, which you can export as WAV/YAML or apply directly in the player.
- **Music player.**
  - Partitioned FIR convolution.
  - **Level-matched A/B**: Bypass and RoomEQ play at the same loudness.
  - Automatic DAC sample rate per track.
  - Library with search, browsing by genre, composer and year, playlists, favourites, and lyrics and artwork fetched online.
  - Web radio with live metadata.
- **Phone remote.** Pair your phone by QR code or 6-digit code. The remote works on Wi-Fi and, through an encrypted relay, on mobile data.
- **UPnP/DLNA.** Your PC library is shared on the LAN as a MediaServer. The app also acts as a MediaRenderer, so other apps can play on it.
- **AutoRoomEQ Player for Android.** It talks to the desktop app: you can exchange presets, playlists, favourites and mic calibration, and stream the PC library.
- **No sleep during playback.** Windows does not go to standby while music is playing or a measurement is running.

## Beta

- Each beta build **expires 90 days** after its build date. The title bar shows how many days are left. When it expires, the app opens this page so you can download the new build.
- The beta is free. Please report problems in **[Issues](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/issues)**. If the app crashed, attach `crash.txt` and `autoroomeq-desktop.log` from `%APPDATA%\AutoRoomEQ Desktop\logs`.
- **Windows SmartScreen** may warn on first launch because the exe is not code-signed yet. Click *More info → Run anyway*.
- The **Microsoft WebView2 Runtime** is installed automatically if it is missing.

## Italiano

**[⬇ Scarica l'ultima beta](https://github.com/Rexxus69/AutoRoomEQ-Desktop-Beta/releases/latest)**. Funziona su Windows 10/11 a 64 bit ed è un singolo `.exe`, senza installazione.

Cosa trovi nell'app:

- misura e correzione acustica della stanza (AutoRoomEQ 2.1) con FIR;
- player bit-perfect con A/B a livello allineato e frequenza del DAC automatica;
- libreria, radio, testi e copertine;
- telecomando dal telefono, sia in Wi-Fi sia con i dati mobili;
- server e renderer UPnP/DLNA;
- integrazione con AutoRoomEQ Player per Android.

Note sulla beta:

- Ogni build beta **scade dopo 90 giorni**.
- I problemi si segnalano negli **Issues**, allegando `crash.txt` e il log che trovi in `%APPDATA%\AutoRoomEQ Desktop\logs`.
- Al primo avvio SmartScreen può mostrare un avviso: clicca *Ulteriori informazioni → Esegui comunque*.

---
© DSPxLab — AutoRoomEQ. Freeware beta for testing: all rights reserved. Redistribution and reverse engineering are not allowed. Source code is not public.
