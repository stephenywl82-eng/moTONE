# moTONE

**中文** · [English](#english)

> 把一台闲置的旧手机，变成一台纯粹听歌的机器。

moTONE 是一款专注音乐播放的 Android 应用，无广告、无追踪、不推送。开机即播放界面，插上耳机或蓝牙音箱就能安安静静听歌。界面中英文双语，从 Android 4.0（API 14）到最新版都能用。

**作者：史蒂文（Steven Yu）**

---

## 应用特点

- **开机就是播放机**：无广告、无推送、不联网打扰，可设为默认主屏幕，让旧手机变身专用音乐播放器
- **格式支持全**：MP3、AAC、FLAC、ALAC、WAV、Opus 等常见与无损格式；支持 bit-perfect 原生采样率直出
- **音质看得见**：实时显示当前格式、采样率、位深、输出设备与输出采样率，播放信号路径逐段可查
- **自研高质量重采样**：曲目采样率与设备不一致时自己转换一次，避免多次转换劣化音质；也可交给 Android 处理
- **USB DAC 直通**：接上外置解码器时按歌曲原始采样率输出
- **曲库自动整理**：按专辑、艺术家、曲目、播放列表浏览，几千首也不乱，右侧 A–Z 快速定位
- **歌词与控制**：内嵌歌词自动显示，通知栏/锁屏可切歌，随机、循环、拖动进度顺手
- **静音 DAP 模式**：一键静音铃声、通知、闹钟，只留音乐，适合当纯音乐播放器
- **蓝牙遥控**：两台手机都装 moTONE，一台控制另一台播放
- **锁屏与桌面**：可用 moTONE 自己的封面锁屏替代系统锁屏，也可设为默认主屏幕
- **可高度定制**：全屏模式、选曲后行为、音量键、ReplayGain、音量锁定、中英文界面都能按习惯调
- **轻巧省资源**：安装包仅约 400 KB，老手机也跑得顺

---

## 功能一览

- **曲库**：专辑 / 艺术家 / 曲目 / 播放列表浏览，网格与列表切换，搜索，A–Z 快速滑轨，本地文件夹扫描
- **播放**：封面、歌名、进度，随机 / 上下曲 / 播放暂停 / 循环，逐行同步歌词高亮，实时音质信息
- **音效与输出**：细粒度音量、功放音量锁定与衰减、厂商音效面板、直通输出、USB DAC 直通、重采样切换、ReplayGain、静音 DAP
- **流媒体**：添加 NAS 网络曲库、第三方音频应用入口、更新检查
- **远程**：本机被控的远程控制开关，控制另一台 moTONE 的蓝牙遥控面板（播放暂停 / 上下曲 / 音量 / 随机）
- **设置**：语言、专用播放器模式、锁屏模式、显示、网络、设备与音频、关于

---

## 下载安装包

三个版本功能完全一致，仅支持的 CPU 架构不同：

| 安装包 | 适用设备 | 大小 |
| --- | --- | --- |
| [moTONE-v3.1.0.apk](releases/moTONE-v3.1.0.apk) | 通用版，32 位 / 64 位都能装，不确定就选这个（含文字搜索等全部功能） | 409 KB |
| [moTONE-v3.1.0-64bit.apk](releases/moTONE-v3.1.0-64bit.apk) | 仅 64 位手机，体积更小 | 265 KB |
| [moTONE-v3.1.0-32bit.apk](releases/moTONE-v3.1.0-32bit.apk) | 仅 32 位手机 / 老旧设备，修复启动闪退、桌面锁定、FLAC 闪退、歌词重叠，新增文字搜索、艺术家tab滑动优化（真机验证通过） | 265 KB |

所有安装包均已签名。安装时如提示"未知来源"，请在系统设置里允许安装未知应用。
Android 4.0/4.4（API 14-20）等老旧设备请用 v3.1.0 32 位版：该版改用兼容主题、隔离高版本 API 调用、修复运行时权限检查崩溃，修复了作为默认桌面时启动崩溃导致"桌面锁定不住"的问题、桌面模式返回键退出问题、播放 FLAC 时 NEON 指令导致 native 崩溃的问题（不支持 NEON 的老 CPU 自动回退系统解码），以及歌词页歌词与歌名重叠的问题（行高自适应屏幕高度），并新增真正的文字搜索（输入歌名/歌手/专辑实时过滤）——已在 Android 4.4 真机验证可正常启动、HOME 稳定进入、返回键留在桌面、FLAC 正常播放。

---

## 许可

© 史蒂文（Steven Yu）。保留所有权利。

---
---

<a name="english"></a>

# English

[中文](#readme) · **English**

> Turn an idle old phone into a dedicated music player.

moTONE is a focused Android music player with no ads, no tracking, and no push notifications. It boots straight into the playback screen — just plug in headphones or a Bluetooth speaker and enjoy your music in peace. The interface supports both English and Chinese, and runs on everything from Android 4.0 (API 14) to the latest versions.

**Author: Steven Yu (史蒂文)**

---

## Highlights

- **Instant music player**: No ads, no push, no network distractions. Set it as your default home screen and turn an old phone into a dedicated music machine.
- **Wide format support**: MP3, AAC, FLAC, ALAC, WAV, Opus and more, including lossless formats with bit-perfect native sample-rate output.
- **See the sound**: Real-time display of format, sample rate, bit depth, output device and output rate, with a step-by-step playback signal path.
- **High-quality resampling**: When a track's sample rate differs from the device, moTONE converts it once with a high-quality algorithm instead of letting Android convert repeatedly — or you can let Android handle it.
- **USB DAC passthrough**: Output at the track's original sample rate when an external DAC is connected.
- **Auto-organized library**: Browse by album, artist, track and playlist. Thousands of songs stay tidy, with an A–Z quick scroller on the side.
- **Lyrics and controls**: Embedded lyrics show automatically; skip tracks from the notification or lock screen; shuffle, repeat and seek are all smooth.
- **Silent DAP mode**: Mute ringtones, notifications and alarms with one tap, leaving only music — perfect for a pure music player.
- **Bluetooth remote**: Install moTONE on two phones and use one to control playback on the other.
- **Lock screen and home**: Replace the system lock screen with moTONE's own cover lock screen, or set it as the default home app.
- **Highly customizable**: Fullscreen mode, post-selection behavior, volume keys, ReplayGain, volume lock and the Chinese/English interface can all be tuned to your taste.
- **Light on resources**: The install package is only about 400 KB, so it runs smoothly even on old phones.

---

## Features at a glance

- **Library**: Browse albums / artists / tracks / playlists, grid and list views, search, A–Z quick scroller, local folder scanning.
- **Playback**: Cover art, title, progress, shuffle / previous / play-pause / next / repeat, synced lyric highlighting, live audio info.
- **Sound & output**: Fine-grained volume, amplifier volume lock and attenuation, vendor sound panels, direct output, USB DAC passthrough, resampling toggle, ReplayGain, Silent DAP.
- **Streaming**: Add a NAS network library, third-party audio app shortcuts, update check.
- **Remote**: A "remote control" switch for this device being controlled, plus a Bluetooth remote panel to control another moTONE (play/pause, previous/next, volume, shuffle).
- **Settings**: Language, dedicated player mode, lock screen mode, display, network, device & audio, about.

---

## Download

All three builds have identical features — they only differ in supported CPU architecture:

| Package | For | Size |
| --- | --- | --- |
| [moTONE-v3.1.0.apk](releases/moTONE-v3.1.0.apk) | Universal — works on both 32-bit and 64-bit; pick this if unsure (all features incl. text search) | 409 KB |
| [moTONE-v3.1.0-64bit.apk](releases/moTONE-v3.1.0-64bit.apk) | 64-bit phones only, smaller size | 265 KB |
| [moTONE-v3.1.0-32bit.apk](releases/moTONE-v3.1.0-32bit.apk) | 32-bit phones / older devices, with startup-crash, home-lock, FLAC-playback, lyrics-layout fixes, with text search & artist-tab scroll fix (verified on device) | 265 KB |

All packages are signed. If installation warns about "unknown sources", enable installation of unknown apps in your system settings.
For old devices running Android 4.0/4.4 (API 14-20), use the v3.1.0 32-bit build: it uses a compatible theme, isolates higher-API calls, fixes the runtime-permission crash, fixes the startup crash that made the home-screen lock unreliable, stops the Back key from exiting the home screen, fixes FLAC playback crashes on CPUs without NEON (falls back to system decoding), fixes lyrics overlapping the track title (line height adapts to screen height), and adds real text search (type a title/artist/album to filter instantly) — verified on an Android 4.4 device: HOME opens moTONE, Back stays in the launcher, and FLAC plays normally.

---

## License

© Steven Yu (史蒂文). All rights reserved.
