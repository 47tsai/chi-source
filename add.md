# AltStore App 候選清單

更新日期：2026-10-15

本文件保留尚未定案的候選項目與版本比較。已加入自有來源的 App 會從候選清單移除；尚未決定是否加入的項目仍保留，供後續比較。

## 共同 App 比較與最佳解

以下將不同來源中「底層 App 相同或高度重疊」的項目集中比較。優先考量 App 本體版本、更新日期，再看修改版功能；若功能差異明顯，推薦代表的是「版本較新、較適合優先保留」，不代表所有人的功能需求都相同。

| App 類別 | 候選版本與來源 | 比較結果 | 建議保留 |
|---|---|---|---|
| **YouTube** | Moe YTK 21.41.5（10/13）；IPA Vault YouMod、YTKACE、YTPlus 21.41.5（10/11）；自有 YTKACE 21.41.5（10/11） | 本體版本相同，主要差在注入的 tweak 與修改套件 | **你選定：自有 YTKACE 21.41.5** |
| **YouTube Music** | Moe YouTube Music 9.41.2（10/13）；IPA Vault YTMUltimate+ 9.41.2（10/11）；自有 MaxMusic 9.34.4（8/30） | Moe 與 IPA Vault 本體版本相同且較新；MaxMusic 舊一版 | **你選定：IPA Vault YTMUltimate+ 9.41.2** |
| **Instagram** | Moe 多個修改版 451.0.0（10/13）；IPA Vault Regram、RyukGram、Sparkle 451.0.0（10/13）；自有 Instagram 433.0.0（6/10） | 外部版本明顯較新，但修改套件各不相同 | **你選定：IPA Vault Instagram (RyukGram) 451.0.0** |
| **Spotify** | IPA Vault Vitrine 9.1.90（10/13）；EeveeSpotify 9.1.90（10/08）；自有 EeveeSpotify Reincarnated 9.1.88（10/05） | Vitrine 本體較新版本與更新日期領先；Eevee 分支則更接近你現有版本 | **Spotify (Vitrine) 9.1.90**，依版本與更新時間優先；若重視 EeveeSpotify 相容性，則留 IPA Vault EeveeSpotify 9.1.90 |
| **Facebook** | IPA Vault iQFace 582.0.0（10/09）；自有 Facebook 582.0.0（10/09）；另有 Facebook Plus 同版 | iQFace 版本、日期一致，屬重複項；Facebook Plus 是另一套修改 | **你選定：自有 Facebook（iQFace）582.0.0** |
| **Threads** | IPA Vault ThreadSaver 451.0（10/13）；自有 Threads 451.0（10/13） | 版本與修改功能相同 | **你選定：自有 Threads（ThreadSaver）451.0** |
| **Reddit** | MoeReddit 2026.41.0（10/13）；IPA Vault RedditFilter 2026.41.0（10/13） | Reddit 本體版本與日期相同，修改功能相近但不完全相同 | **先保留 MoeReddit** 作為單一代表；若你偏好 RedditFilter 的過濾功能再換 |
| **Twitch** | Moe TwitchControl／Tweach 31.5（10/08）；IPA Vault Twitch 31.4（9/29） | Moe 版本較新，更新日期也較晚 | **Moe Twitch 31.5** |
| **Infuse** | IPA Vault Infuse Plus 8.5.7（10/13）；Moe Infuse Plus 8.5.6（9/30） | IPA Vault 本體版本較新，更新日期較晚 | **IPA Vault Infuse Plus 8.5.7** |
| **Google Photos** | IPA Vault Gunshot 7.20.2、7.44.0、7.96.0（均標示 10/09） | 同一修改功能的不同本體版本，7.96.0 最新 | **Google Photos Gunshot 7.96.0**，除非需要舊版 iOS 相容性 |
| **PiliPlus** | 自有 Chi Source 2.1.6.2（10/10）；AltGallery 2.1.6（build 5472，10/10） | 更新日期相同，版本標記不同，可能是不同打包方式 | **你選定：自有 Chi Source PiliPlus 2.1.6.2** |
| **Animeko** | 自有 Chi Source Personal 6.3.0（10/13）；AltGallery 6.3.0（10/13） | 版本與更新日期相同 | **你選定：自有 Chi Source Personal Animeko 6.3.0** |
| **Kazumi** | 自有 Chi Source Personal 2.3.8（10/07）；AltGallery 2.3.8（10/07） | 版本與更新日期相同 | **你選定：自有 Chi Source Personal Kazumi 2.3.8** |
| **Aidoku** | 自有 Chi Source Personal 0.9（9/03）；AltGallery 0.9（9/03） | 版本與更新日期相同 | **你選定：自有 Chi Source Personal Aidoku 0.9** |
| **AirCard-iOS** | 自有 Chi Source Personal 1.3.2（10/04）；AltGallery 1.3.2（10/04） | 版本與日期相同，但 AltGallery 標示 iOS 27 起、自有來源標示 iOS 18，最低版本資訊互相矛盾 | **你選定：自有 Chi Source Personal AirCard-iOS 1.3.2**；AltGallery 的最低系統需求待核實 |
| **Husk** | AltGallery 2.0（10/11）；IPA Vault 1.1.0（10/09） | AltGallery 版本較新，日期也較晚 | **你選擇略過，暫不決定** |

### 共同項處理原則

- 已有自有來源且版本、日期、修改功能相同：優先保留自有項目，不重複收錄。
- 本體版本與更新日期都較新：優先推薦較新的項目。
- 本體版本相同但修改套件不同：不宣稱功能完全等價，先選一個代表，避免清單膨脹。
- 相容性資訊互相矛盾或功能差異未能確認：標記待核實，不直接當成確定最佳解。

> 本文件只整理候選清單，不修改任何 `apps.json`。已加入的 App 不再重複列在來源候選表中；尚未定案的項目繼續保留。

## Moe AltStore

| App | 版本 | 最後更新時間 | 功能簡介 |
|---|---|---|---|
| Carrot | 6.5 | 2026-03-26 | Carrot 6.5 Pro Moe with Working Widgets for iOS, listed on Moe's App Hub with version, file size, and install details. L... |
| Webssh | 33.0 | 2026-09-30 | Webssh 33.0 Pro for iOS. |
| MoeReddit | 2026.41.0 (4.6.1) | 2026-10-13 | Hold down with 3 fingers to open moemod menu |
| Infuse (Moe Plus) | 8.5.6 (2.6) | 2026-09-30 | Infuse 8.5.6 2.6 Moe Plus for iOS. |
| Infuse (Plus 2.5) | 8.4.2 (2.5) | 2026-04-10 | Infuse 8.4.2 Plus 2.5 for iOS, listed on Moe's App Hub with version, file size, and install details. Linked App Store identity: Infuse in Entertainment. |
| Twitch | 24.2.4 | 2025-09-20 | Twitch is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details. |
| Twitch (Adfree, Moe Control) | 29.0 (0.0.2) | 2026-04-17 | hold down with 3 fingers for 4 seconds to open the mod menu |
| Twitch (Tweach) | 29.0 (2.3.1) | 2026-04-17 | Twitch 29.0 Tweach 2.3.1 is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details. |
| Twitch (Moe TwitchControl) | 31.5 (0.0.6) | 2026-10-08 | for adblock to work, open mod menu, and import the file you download from https://tinyurl.com/3n9sz6mv into the mods set... |
| Twitch (Twitchv, Moe Tweach) | 31.5 (2.4.1) | 2026-10-08 | Twitch 31.5 Tweach 2.4.1 for iOS. |

## IPA Vault

| App | 版本 | 最後更新時間 | 功能簡介 |
|---|---|---|---|
| Discord (RainTweak) | 349.0 | 2026-10-13 | Discord 349.0 with RainTweak 0.10.0 |
| Google Photos (Gunshot) (iOS 16.1+) | 7.20.2 | 2026-10-09 | Google Photos 7.20.2 with Gunshot 0.3.0 (iOS 16.1+) |
| Google Photos (Gunshot) (iOS 17+) | 7.44.0 | 2026-10-09 | Google Photos 7.44.0 with Gunshot 0.3.0 (iOS 17+) |
| Google Photos (Gunshot) | 7.96.0 | 2026-10-09 | Google Photos 7.96.0 with Gunshot 0.3.0 |
| iMe (MxGram) | 12.8.1 | 2026-09-01 | iMe 12.8.1 with MxGram 1.0.0 |
| iMe (iQTele) | 12.8.1 | 2026-09-05 | iMe 12.8.1 with iQTele 1.2 |
| Infuse Plus (7.8.4) | 7.8.4 | 2026-09-01 | Infuse 7.8.4 with Infuse Plus 2.6 |
| Infuse Plus (8.2.4) | 8.2.4 | 2026-09-01 | Infuse 8.2.4 with Infuse Plus 2.6 |
| Infuse Plus (8.5.7) | 8.5.7 | 2026-10-13 | Infuse 8.5.7 with Infuse Plus 2.6 |
| Husk | 1.1.0 | 2026-10-09 | Husk 1.1.0 |
| Messenger (Flow) | 582.0.0 | 2026-10-07 | Messenger 582.0.0 with Flow 1.0 |
| Messenger (Login) | 523.0.0 | 2026-09-01 | Messenger 523.0.0 login build |
| Messenger (MSGPlusX) | 582.0.0 | 2026-10-07 | Messenger 582.0.0 with MSGPlusX 1.1 |
| Nagram (MxGram) | 13.0.1 | 2026-10-13 | Nagram 13.0.1 with MxGram 1.0.0 |
| Nagram (iQTele) | 13.0.1 | 2026-10-13 | Nagram 13.0.1 with iQTele 1.4 |
| Nagram (TGExtra) | 13.0.1 | 2026-10-13 | Nagram 13.0.1 with TGExtra 1.7.7 |
| Reddit (Login) | 2024.12.0 | 2026-09-01 | Reddit 2024.12.0 login build |
| Reddit (RedditFilter) | 2026.41.0 | 2026-10-13 | Reddit 2026.41.0 with RedditFilter 4.6.1 |
| SoundCloud (NexaSC) (iOS 16.0-16.3) | 7.68.1 | 2026-09-01 | SoundCloud 7.68.1 with NexaSC beta 4 |
| SoundCloud (NexaSC) | 8.82.0 | 2026-10-11 | SoundCloud 8.82.0 with NexaSC beta 4 |
| Swiftgram (MxGram) | 13.0 | 2026-10-13 | Swiftgram 13.0 with MxGram 1.0.0 |
| Swiftgram (iQTele) | 12.9.4 | 2026-10-03 | Swiftgram 12.9.4 with iQTele 1.4 |
| Swiftgram (TGExtra) | 13.0 | 2026-10-13 | Swiftgram 13.0 with TGExtra 1.7.7 |
| Telegram (MxGram) | 13.0 | 2026-10-09 | Telegram 13.0 with MxGram 1.0.0 |
| Telegram (iQTele) | 13.0 | 2026-10-09 | Telegram 13.0 with iQTele 1.4 |
| Telegram (TGExtra) | 13.0 | 2026-10-09 | Telegram 13.0 with TGExtra 1.7.8 |
| Spotify (EeveeSpotify) | 9.1.90 | 2026-10-08 | Spotify 9.1.90 with EeveeSpotify 7.0.0 |
| Spotify (EeveeSpotify) (No Plugins) | 9.1.90 | 2026-10-08 | Spotify 9.1.90 with EeveeSpotify 7.0.0 (No Plugins) |
| Spotify (Vitrine) | 9.1.90 | 2026-10-13 | Spotify 9.1.90 with Vitrine 1.0.0-b13 |
| Spotify (Vitrine) (No Plugins) | 9.1.90 | 2026-10-13 | Spotify 9.1.90 with Vitrine 1.0.0-b13 (No Plugins) |
| Spotify (Eevee + Chroma) (9.1.78) | 9.1.78 | 2026-10-05 | Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0 |
| Spotify (Eevee + Chroma) (9.1.78) (No Plugins) | 9.1.78 | 2026-10-05 | Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0 (No Plugins) |
| TikTok (Infinitok) | 47.1.0 | 2026-10-07 | TikTok 47.1.0 with Infinitok 0.0.2 |
| Turrit (MxGram) | 1.5.5 | 2026-10-09 | Turrit 1.5.5 with MxGram 1.0.0 |
| Turrit (iQTele) | 1.5.5 | 2026-10-09 | Turrit 1.5.5 with iQTele 1.4 |
| Turrit (TGExtra) | 1.5.5 | 2026-10-09 | Turrit 1.5.5 with TGExtra 1.7.7 |
| TwitchUnblock | 1.3.0 | 2026-10-11 | TwitchUnblock 1.3.0 |
| Twitch | 31.4 | 2026-09-29 | Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6 |
| Twitch (Glass) | 31.4 | 2026-09-29 | Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6 (Glass) |
| Twitter NFB | 12.33 | 2026-10-11 | Twitter 12.33 with NFB 7.1.1 |
| Twitter NFB + TWI | 12.33 | 2026-10-11 | Twitter 12.33 with NFB 7.1.1 + TWIGalaxy 1.14 |
| X NFB | 12.33 | 2026-10-11 | X 12.33 with NFB 7.1.1 |
| X NFB + TWI | 12.33 | 2026-10-11 | X 12.33 with NFB 7.1.1 + TWIGalaxy 1.14 |
| YTMUltimate+ | 9.41.2 | 2026-10-11 | YouTube Music 9.41.2 with YTMUltimate+ 2.4.1  Added Tweaks: YTMABConfig, YouMusicPIP, VolumeBoostYT, ReturnYouTubeMusicDislike |
| YTMUltimate+ (No PiP) | 9.41.2 | 2026-10-11 | YouTube Music 9.41.2 with YTMUltimate+ 2.4.1 (No PiP)  Added Tweaks: YTMABConfig, VolumeBoostYT, ReturnYouTubeMusicDislike |
| Spotify (Taurus) | 9.1.78 | 2026-10-09 | Spotify 9.1.78 with Taurus 0.50.1 |
| Spotify (Taurus) (No Plugins) | 9.1.78 | 2026-10-09 | Spotify 9.1.78 with Taurus 0.50.1 (No Plugins) |

## AltGallery

| App | 版本 | 最後更新時間 | 功能簡介 |
|---|---|---|---|
| AniBaka | 5.2.1（build 1007） | 2026-10-07 | AniBaka 是一个基于 Flutter 的跨平台番剧聚合与媒体播放客户端，支持多番剧源、弹幕、字幕、离线缓存与本地媒体库，并提供动漫实时超分辨率画质增强。 |
| AnimeFlow | 2.6.3 | 2026-10-12 | AnimeFlow 是一个跨平台动漫视频播放应用，支持 Android、iOS、Windows、macOS 与 Linux。内置多数据源与自定义 XPath 爬虫配置，支持基于 Anime4K 的实时视频 4K 超分辨率，对接 Bangumi 同步收藏与追番数据，并支持多平台弹幕源与丰富的弹幕设置。 |
| Apollo for Reddit - GLASS | 3.9.0 | 2026-10-09 | Apollo-Reborn is the community-maintained Apollo sideload build powered by the Apollo-Reborn tweak.  It restores custom API support, media fixes, upload... |
| ARMSX2 | nightly-20261011 | 2026-10-11 | A free and open-source PlayStation 2 (PS2) emulator based on PCSX2, with native ARM64 JIT recompilers. Play PS2 games on your phone, PC, or gaming handh... |
| Doer | 1.8.6 | 2026-10-10 | A native iOS client for Linux.do — UIKit + Swift, no SwiftUI in the main app. |
| DolphiniOS | 5.0.0b6 | 2026-06-20 | Dolphin for iOS, reborn. A GameCube and Wii emulator for iPhone and iPad. |
| DukeX | 1.0.2 | 2026-06-30 | DukeX is an experimental iOS-focused frontend for xemu. It embeds the xemu core in a native Swift shell and presents the Vulkan renderer through MoltenV... |
| EhPanda | 2.8.1 | 2026-07-20 | EhPanda is an unofficial E-Hentai app for iOS & iPadOS built with SwiftUI & TCA. It supports almost all E-Hentai gallery categories, gallery browsing wi... |
| Fathom | 1.0.0 | 2026-09-14 | An x86-64 PC emulator for iOS. Fathom runs x86-64 Linux programs on an iPhone or iPad by translating them to ARM64 as they execute, using FEXCore - the ... |
| Husk | 2.0 | 2026-10-11 | Run Android apps on iOS: drop in an APK, tap it, and the Android app opens full-screen on a QEMU guest with hardware-accelerated display and audio. Need... |
| Iridium | 0.2.0 | 2026-10-04 | An experimental iPhone and iPad Windows-game runtime, with a native game library and touch, keyboard, mouse, and controller integration. Requires iOS 18... |
| iTorrent | 2.2.0-1 | 2026-07-19 | iTorrent is an ordinary torrent client for iOS with Files app support and much more.  What can this app do:  • Download in the background • Live Activit... |
| KMusic | 2.3.0 | 2026-03-12 | 基于 SwiftUI 开发的多源音乐聚合播放器，支持 iOS/macOS。内置酷我、酷狗、QQ 音乐、网易云、咪咕等多平台音源，支持 LRC 歌词同步、全局搜索、后台播放与深色主题，并可通过 JS 脚本导入自定义音源。 |
| Kumone | 0.3.20 | 2026-10-03 | Kumone（雲の音）— native NetEase Cloud Music client for iOS. Talks directly to NetEase's real API with no third-party server: QR-code login, gray-track unblo... |
| LiveContainer+SideStore | nightly | 2026-09-18 | An app launcher that runs iOS apps without actually installing them. This build of LiveContainer comes with a built-in SideStore for refreshing your apps. |
| Madeira | 0.1.3 | 2026-10-03 | Madeira runs unmodified x86-64 Windows PC games inside a single jailed iOS app: FEX-Emu translates the game's x86 code to ARM64 as it runs, Wine 11.4 bu... |
| Mangayomi | 0.9.9 | 2026-10-12 | Mangayomi is an open-source Flutter app for reading manga, novels, and watching anime across multiple platforms. |
| ManicEMU | 2.0.1 | 2026-09-18 | All-in-one retro game emulator for iOS, bringing console, arcade, computer, and mobile Java systems into one clean app with saves, cheats, custom skins,... |
| MiniWatts | 1.5.1 | 2026-10-13 | An iPhone battery and charging monitor built on Apple's private APIs: the charger's real watts, how much of that reaches the cell, where the rest goes a... |
| MoviePilotLite | 1.2.5 | 2026-10-09 | 基于 MoviePilot 的 Flutter 跨端客户端，对接 MoviePilot v2 API，在手机上完成订阅、搜索、下载、整理与系统运维等常用操作。 |
| Musly | 2.0.2 | 2026-08-26 | Musly is a free Navidrome client and Subsonic music player with an Apple Music-inspired interface. Stream your self-hosted library from Navidrome, Subso... |
| NeoStation iOS | 0.0.7 | 2026-10-13 | An independently maintained iOS/iPadOS fork of NeoStation, with embedded Dolphin, ARMSX2, RPCS3, Dusklight and KartPad runtimes alongside RetroArch and ... |
| Novella | 2.5.0 | 2026-09-23 | 使用 React Native 构建的轻书架第三方客户端，面向 iOS、iPadOS。 |
| Opaline | 1.12.0 | 2026-09-10 | A lightweight YouTube client with SponsorBlock, Return YouTube Dislike, and up to 1080p playback. No ads, no tracking, no dependencies. |
| Orchard | 0.2 | 2026-09-25 | Boots a real arm64 macOS Ventura guest on iPhone through Apple's own chain (AVPBooter, iBoot and XNU) on QEMU's apple-vm machine, with the GPU drawn thr... |
| Pixiv-SwiftUI | 0.16.2 | 2026-10-11 | 基于 SwiftUI 开发的 Pixiv 第三方客户端，支持 iOS/iPadOS/macOS。提供插画、漫画与小说的推荐、排行榜、搜索与收藏，内置评论系统、批量下载、数据导入导出、深色模式与主题自定义。 |
| Playport | 0.4.0 | 2026-10-08 | Playport runs Windows games, 64-bit and 32-bit, on a stock, non-jailbroken iPhone: install a game from your library onto the phone, pick up a controller... |
| PSX3IOS | 0.2.7-beta | 2026-09-01 | A PlayStation 3 emulator for iPhone and iPad, built on RPCS3. Real games boot and play — the whole emulator core is exposed, with community game patches... |
| PureLive | 3.1.19 | 2026-10-10 | 纯粹直播（Pure Live）是一款基于 Flutter 的开源第三方多平台直播聚合播放器，支持 Bilibili、虎牙、斗鱼、快手、抖音、网易 CC、Twitch 等平台，以及自定义 M3U/M3U8 直播源。 |
| Roam Control | 0.9.7 | 2026-10-08 | Set a fixed reported location, preview and simulate Apple Maps walking routes, and save favourites and history — all from one map. Requires iOS 27 or ne... |
| SceneBox | 1.0.4 | 2026-09-23 | Torrent streaming client for iOS, iPadOS, tvOS and Mac (Catalyst), written in SwiftUI. Streams come from Stremio-compatible addons and play through a ve... |
| SpotiFLAC | 5.1.1 | 2026-10-11 | SpotiFLAC is a Flutter music app built around installable extensions: an extension supplies the metadata and the audio downloads for one provider, so so... |
| TiebaPure | 1.4.15 | 2026-10-10 | 原生 SwiftUI 构建的非官方贴吧 iOS 客户端。未登录访客即可浏览首页推荐、进吧与吧内列表、帖子详情与楼中楼、搜索、图片缩放与视频播放；登录后支持消息、关注与粉丝、收藏帖子（与官方客户端同步）、每日签到、点赞与发帖回复。另有关键词/用户/贴吧屏蔽、浏览历史与阅读位置恢复、iPad 双栏布局，以及... |
| Tsumiru | 1.4.0 | 2026-10-13 | Tsumiru is a native client for reading manga & manhwa from a Suwayomi-Server instance, built for long webtoon binges. Offline downloads with an on-devic... |
| UTM | 4.7.5 | 2026-01-03 | UTM is a full featured virtual machine host for iOS. In short, it allows you to run Windows, Android, and more on your iPhone and iPad.  This version re... |
| VeneraNext | 1.18.0（build 234） | 2026-10-14 | 基于 Flutter 的跨平台漫画阅读器，支持本地漫画、WebDAV 漫画源与第三方网络漫画源，支持 Android、iOS、Windows、Linux、macOS 平台。 |
| YouProEXTRA | 21.41.5（build 21.41.5） | 2026-10-11 | YouPro mod of YouTube for iOS. Includes no ads, background playback, downloads, iSponsorBlock, PiP, and a host of customizable tweaks. |
| ZhihuMinusMinus | 0.9.0 | 2026-10-13 | 基于 React Native (Expo) 构建的轻量级第三方知乎客户端，无广告，支持多账号切换、游客模式、全局主题色自定义与深色模式，可查看热榜、推荐、回答、文章、想法与评论区，并支持从 GitHub Releases 自动更新。 |

## Chi Source（自己的來源）

| App | 版本 | 最後更新時間 | 功能簡介 |
|---|---|---|---|
| YTKACE | 21.41.5 | 2026-10-11 | An open-source YouTube enhancement for iOS. |
| MaxMusic | 9.34.4 | 2026-08-30 | MaxMusic is a fork of YTMusicUltimate with additional tweaks for YouTube Music on iOS. |
| Facebook | 582.0.0 | 2026-10-09 | Facebook 582.0.0 with iQFace 1.2 |
| Threads | 451.0 | 2026-10-13 | Threads 451.0 with ThreadSaver |
| Instagram | 433.0.0 | 2026-06-10 | Injected with Premium |

## Chi Source Personal（自己的來源）

| App | 版本 | 最後更新時間 | 功能簡介 |
|---|---|---|---|
| SpooferPro Pokemon GO | 0.431.1（build 0.736） | 2026-10-12 | SPOOF INTO THE World of PoGO SpooferPro for PoGO is an enhanced edition of the PoGO app, adding a joystick and ability to teleport! It also includes a l... |
| Photos Backup | 0.3.7 | 2026-09-20 | ## New  - **The Google Photos app now counts what this app backs up.** ([#24](https://github.com/g8row/PhotosBackup/pull/24), thanks @saileshbro) Upload... |
| EnsWilde | 3.1.3（build EnsWilde3.1.3） | 2026-02-25 | An experimental on-device iOS customization app. Features and compatibility depend on the iOS version; back up your device before use. |
| StikDebug | 3.1.14 | 2026-10-12 | An on-device debugger and developer toolbox for iOS versions 17.4+ powered by idevice.  Note: Requires LocalDevVPN, cannot be natively used inside LiveC... |

## 原始來源

- [Moe AltStore](https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/apps.json)
- [IPA Vault](https://raw.githubusercontent.com/927tx/IPA-Vault/main/ipavaultsource.json)
- [AltGallery](https://raw.githubusercontent.com/bebound/AltGallery/master/all-apps.json)
- [Chi Source](https://raw.githubusercontent.com/tsai97216/chi-source/main/apps.json)
- [Chi Source Personal](https://raw.githubusercontent.com/tsai97216/chi-source-personal/main/apps.json)
