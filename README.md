<h1 align="center">- ryo-osc -</h1>
<p align="center">
  <samp>A modern and minimal OSC for mpv. ryo-osc is a fork of hayase-osc.</samp> 
</p>

<img width="2560" height="1440" alt="showcase000" src="https://github.com/user-attachments/assets/fd1b8290-2b73-470f-8d2f-14405388c5f0" />

<img width="2560" height="1440" alt="showcase001" src="https://github.com/user-attachments/assets/54c54c01-0e2f-4514-9977-e54b89de7c34" />

<img width="2560" height="1440" alt="showcase002" src="https://github.com/user-attachments/assets/b18dabf3-4e2c-4607-8534-7584a2a3f198" />

<img width="2560" height="1440" alt="showcase003" src="https://github.com/user-attachments/assets/50d1f9f3-de72-4cde-997c-751ffe9a4d16" />

<img width="2560" height="1440" alt="showcase004" src="https://github.com/user-attachments/assets/ba7deb73-ac5b-49e4-a839-32205f430ccf" />

### Requirements

- **[mpv](https://mpv.io/installation/)** (v0.39.0 or above)  
- **[thumbfast](https://github.com/po5/thumbfast)** (optional, recommended for hover thumbnails)

### Folder Structure
**You can find all these files in my [mpv-config](https://github.com/Xightify/mpv-config/)**

    mpv/
    │   ffmpeg.exe
    │   mpv.exe
    │   updater.bat
    │   yt-dlp.exe
    │
    └── portable_config/
        │   input.conf
        │   mpv.conf
        │   watch_history.jsonl
        │   profiles.conf
        │
        ├── cache/
        │   ├── shaders_cache
        │   └── watch_later
        │
        ├── fonts/
        │   └── ryo-icons.ttf ★
        │
        ├── script-opts/
        │   ├── anilist_rpc.conf
        │   ├── media_rpc.conf
        │   ├── ryo-osc.conf ★
        │   ├── deband-cycle.conf
        │   ├── subtitle.conf
        │   ├── console.conf
        │   └── stats.conf
        │
        ├── scripts/
        │   ├── anilist_rpc.lua
        │   ├── media_rpc.lua
        │   ├── ryo-osc.lua ★
        │   ├── lang-seek.lua
        │   ├── deband-cycle.lua
        │   ├── subtitle.lua
        │   ├── thumbfast.lua
        │   ├── evafast.lua
        │   ├── silentskip.lua
        │   └── webm.lua
        │
        └── shaders/
            └── .glsl files

## Paste this in mpv.conf for a better experience.
```
osc=no
osd-bar=no
border=no
window-corners=roundsmall
```

## **How's ryo-osc different from hayase-osc?**
hayase-osc is already good, but I added a few features I wanted and fixed some issues I noticed while using it. More about it [here](https://github.com/Xightify/ryo-osc/releases/v0.1.0).

## Acknowledgements
- **[hayase-osc](https://github.com/nekoxuee/hayase-osc)**
