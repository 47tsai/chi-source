# App 全量清單與版本追蹤（add.md）

> **資料快照日期：2026-10-14（台灣時間）**  
> 本文件收錄三個外部 AltStore sources（Moe AltStore、IPA Vault、AltGallery）中的每一個 App，並附上 Chi Source 與 Chi Source Personal 的全部現有 App，供逐項比對及後續決定是否匯入。  
> **注意：** 本文件是盤點文件，不會自動把外部 App 加進 `apps.json`；相同 App 可能在多個來源重複出現，請按來源分開核對。

## 來源總覽

| Source | App 數量 | 來源檔案 | 本次用途 |
|---|---:|---|---|
| Moe AltStore | 34 | [原始 JSON](https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/apps.json) | 外部候選 App 清單 |
| IPA Vault | 63 | [原始 JSON](https://raw.githubusercontent.com/927tx/IPA-Vault/main/ipavaultsource.json) | 外部候選 App 清單 |
| AltGallery | 43 | [原始 JSON](https://raw.githubusercontent.com/bebound/AltGallery/master/all-apps.json) | 外部候選 App 清單 |
| Chi Source（自己的來源） | 7 | [原始 JSON](https://raw.githubusercontent.com/tsai97216/chi-source/main/apps.json) | 自己目前已收錄的 App |
| Chi Source Personal（自己的來源） | 8 | [原始 JSON](https://raw.githubusercontent.com/tsai97216/chi-source-personal/main/apps.json) | 自己目前已收錄的 App |

**外部來源共 140 個來源項目**（跨來源重複項目會分別保留），自己的兩個來源共 15 個 App。版本號與日期依各來源 JSON 原樣整理；來源未提供的欄位會標示「未提供」。

## 一、Moe AltStore

- **來源 JSON：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/apps.json
- **來源首頁：** https://github.com/MountainofPenguin/moe-altstore
- **App 數量：** 34

### 1. Carrot

- **開發者：** Moe Apps
- **Bundle ID：** `com.grailr.CARROTweather`
- **副標題：** Weather app, Moe Pro patch
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/carrot.png
- **功能／描述：** Carrot 6.5 Pro Moe with Working Widgets for iOS, listed on Moe's App Hub with version, file size, and install details. L...
- **來源內版本數：** 1
- **目前列出的版本：** 6.5
- **最新列出的發布日期：** 2026-03-26
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 6.5 | 未提供 | 2026-03-26 | 15.0 | 256.88 MB (269,355,072 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/carrot-6.5/carrot.ipa) |

**版本說明：** requires the use of a custom entitlement file from your cert. so get your mobile provision, name it "entitlements.text" now start copying all of your entitlements starting with "dict" and ending with "dict". now paste that into an Ai bot and say (Please conver…（版本說明已節錄）

### 2. Webssh

- **開發者：** Moe Apps
- **Bundle ID：** `com.itimeteo.webssh`
- **副標題：** SSH client, Pro patch
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/webssh.png
- **功能／描述：** Webssh 33.0 Pro for iOS.
- **來源內版本數：** 4
- **目前列出的版本：** 33.0
- **最新列出的發布日期：** 2026-09-30
- **最低 iOS：** 26.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 33.0 | 未提供 | 2026-09-30 | 26.0 | 100.88 MB (105,780,395 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/webssh-33.0/webssh.ipa) |
| 32.7 | 未提供 | 2026-08-18 | 26.0 | 94.57 MB (99,163,453 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/webssh-32.7/webssh.ipa) |
| 32.6 | 未提供 | 2026-08-10 | 26.0 | 91.69 MB (96,147,727 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/webssh-32.6/webssh.ipa) |
| 32.1 | 未提供 | 2026-06-04 | 26.0 | 88.04 MB (92,316,394 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/webssh-32.1/webssh.ipa) |

**版本說明：** Webssh 33.0 Pro for iOS.

### 3. MoeReddit

- **開發者：** Moe Apps
- **Bundle ID：** `com.reddit.Reddit`
- **副標題：** Reddit client, MoeReddit build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/moereddit.png
- **功能／描述：** Hold down with 3 fingers to open moemod menu
- **來源內版本數：** 5
- **目前列出的版本：** 2026.41.0 (4.6.1)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2026.41.0 (4.6.1) | 未提供 | 2026-10-13 | 16.0 | 138.69 MB (145,423,943 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/moereddit-2026.41.0/moereddit.ipa) |
| 2026.40.0 (4.5.1) | 未提供 | 2026-10-08 | 16.0 | 138.45 MB (145,178,579 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/moereddit-2026.40.0/moereddit.ipa) |
| 2026.39.0 (4.5.1) | 未提供 | 2026-09-30 | 16.0 | 137.71 MB (144,401,884 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/moereddit-2026.39.0/moereddit.ipa) |
| 2026.39.0 (4.5) | 未提供 | 2026-09-28 | 16.0 | 137.56 MB (144,239,958 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/moereddit-2026.39.0/moereddit.ipa) |
| 2026.38.0 (4.5) | 未提供 | 2026-09-28 | 16.0 | 137.00 MB (143,655,051 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/moereddit-2026.38.0/moereddit.ipa) |

**版本說明：** Hold down with 3 fingers to open moemod menu

### 4. Infuse (Moe Plus)

- **開發者：** Moe Apps
- **Bundle ID：** `com.firecore.infuse`
- **副標題：** Media player, Moe Plus patch
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/infuse-moe-plus.png
- **功能／描述：** Infuse 8.5.6 2.6 Moe Plus for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 8.5.6 (2.6)
- **最新列出的發布日期：** 2026-09-30
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 8.5.6 (2.6) | 未提供 | 2026-09-30 | 18.0 | 94.59 MB (99,183,211 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-moe-plus-8.5.6/infuse-moe-plus.ipa) |
| 8.5.5 (2.6) | 未提供 | 2026-09-17 | 18.0 | 95.13 MB (99,751,126 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-moe-plus-8.5.5/infuse-moe-plus.ipa) |
| 8.5.4 (2.6) | 未提供 | 2026-09-15 | 18.0 | 95.12 MB (99,735,608 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-moe-plus-8.5.4/infuse-moe-plus.ipa) |
| 8.5.2 (2.6) | 未提供 | 2026-08-26 | 18.0 | 95.09 MB (99,710,955 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-moe-plus-8.5.2/infuse-moe-plus.ipa) |
| 8.5 (2.6) | 未提供 | 2026-08-03 | 18.0 | 94.98 MB (99,596,210 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-moe-plus-8.5/infuse-moe-plus.ipa) |

**版本說明：** Infuse 8.5.6 2.6 Moe Plus for iOS.

### 5. Infuse (Plus 2.5)

- **開發者：** Moe Apps
- **Bundle ID：** `com.firecore.infuse`
- **副標題：** Media player, Plus 2.5 patch
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/infuse-plus-2-5.png
- **功能／描述：** Infuse 8.4.2 Plus 2.5 for iOS, listed on Moe's App Hub with version, file size, and install details. Linked App Store identity: Infuse in Entertainment.
- **來源內版本數：** 1
- **目前列出的版本：** 8.4.2 (2.5)
- **最新列出的發布日期：** 2026-04-10
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 8.4.2 (2.5) | 未提供 | 2026-04-10 | 18.0 | 91.49 MB (95,930,426 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/infuse-plus-2-5-8.4.2/infuse-plus-2-5.ipa) |

**版本說明：** Infuse 8.4.2 Plus 2.5 for iOS, listed on Moe's App Hub with version, file size, and install details. Linked App Store identity: Infuse in Entertainment.

### 6. YouTube (Moe Multi)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** Multi-tweak loader: YTKillerPlus, DLTube, TubeLRD, YTLite, and more
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-moe-multi.png
- **功能／描述：** DONT SIGN WITH ESIGN AND hold down with 4 fingers to open multi menu
- **來源內版本數：** 3
- **目前列出的版本：** 21.32.4 (10.17)
- **最新列出的發布日期：** 2026-08-09
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.32.4 (10.17) | 未提供 | 2026-08-09 | 16.0 | 197.59 MB (207,188,456 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-multi-21.32.4/youtube-moe-multi.ipa) |
| 21.24.3 (10.16) | 未提供 | 2026-07-21 | 16.0 | 194.19 MB (203,622,936 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-multi-21.24.3/youtube-moe-multi.ipa) |
| 21.28.3 (10.16) | 未提供 | 2026-07-17 | 16.0 | 208.14 MB (218,251,422 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-multi-21.28.3/youtube-moe-multi.ipa) |

**版本說明：** Included tweaks: - YTKillerPlus - DLTube - TubeLRD - YTLite - YTReborn - YouTubeX - YTSy - DontEatMyContent - YouTubeDislikesReturn - and more

### 7. YouTube (Moe YTK)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** YTKillerPlus tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-moe-ytk.png
- **功能／描述：** YouTube 21.41.5 YTKillerPlus 6.7.1 Stable with Mods for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 21.41.5 (6.7.1)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 (6.7.1) | 未提供 | 2026-10-13 | 17.0 | 148.31 MB (155,517,760 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-ytk-21.41.5/youtube-moe-ytk.ipa) |
| 21.40.5 (6.6.5) | 未提供 | 2026-10-08 | 17.0 | 148.38 MB (155,591,532 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-ytk-21.40.5/youtube-moe-ytk.ipa) |
| 21.39.4 (6.6) | 未提供 | 2026-09-28 | 17.0 | 148.98 MB (156,212,414 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-ytk-21.39.4/youtube-moe-ytk.ipa) |
| 21.38.2 (6.5.8) | 未提供 | 2026-09-23 | 17.0 | 143.21 MB (150,163,602 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-ytk-21.38.2/youtube-moe-ytk.ipa) |
| 21.38.2 (6.5.6) | 未提供 | 2026-09-21 | 17.0 | 149.03 MB (156,273,342 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-ytk-21.38.2/youtube-moe-ytk.ipa) |

**版本說明：** YouTube 21.41.5 YTKillerPlus 6.7.1 Stable with Mods for iOS.

### 8. YouTube (YTPlus Cyan Edition)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** YTPlus tweak build, Cyan Edition
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-ytplus-cyan.png
- **功能／描述：** Youtube 20.10.4 YTPlus 5.2 Beta 4 Cyan Edition is an iOS release entry for YouTube on Moe's App Hub, with version, file size, icon, and install details.
- **來源內版本數：** 1
- **目前列出的版本：** 20.10.4 (5.2)
- **最新列出的發布日期：** 2025-11-29
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 20.10.4 (5.2) | 未提供 | 2025-11-29 | 15.0 | 115.59 MB (121,206,969 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-cyan-20.10.4/youtube-ytplus-cyan.ipa) |

**版本說明：** Youtube 20.10.4 YTPlus 5.2 Beta 4 Cyan Edition is an iOS release entry for YouTube on Moe's App Hub, with version, file size, icon, and install details.

### 9. YouTube (LRD)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** TubeLRD tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-lrd.png
- **功能／描述：** Youtube 21.08.3 LRD 1.13 Moe is an iOS release entry for YouTube on Moe's App Hub, with version, file size, icon, and install details.
- **來源內版本數：** 1
- **目前列出的版本：** 21.08.3 (1.13)
- **最新列出的發布日期：** 2026-02-25
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.08.3 (1.13) | 未提供 | 2026-02-25 | 16.0 | 125.08 MB (131,158,131 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-21.08.3/youtube-lrd.ipa) |

**版本說明：** Youtube 21.08.3 LRD 1.13 Moe is an iOS release entry for YouTube on Moe's App Hub, with version, file size, icon, and install details.

### 10. YouTube (DLTube, Moe Patched)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** DLTube tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-dltube-patched.png
- **功能／描述：** Youtube 21.26.4 DLTube 2.16.4 Moe Patched for iOS.
- **來源內版本數：** 1
- **目前列出的版本：** 21.26.4 (2.16.4)
- **最新列出的發布日期：** 2026-06-29
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.26.4 (2.16.4) | 未提供 | 2026-06-29 | 16.0 | 125.67 MB (131,772,506 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-dltube-patched-21.26.4/youtube-dltube-patched.ipa) |

**版本說明：** Youtube 21.26.4 DLTube 2.16.4 Moe Patched for iOS.

### 11. YouTube (Moe DLTube, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** DLTube tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-dltube-cracked.png
- **功能／描述：** Youtube 21.24.3 Moe DLTube 2.16.3 Cracked for iOS.
- **來源內版本數：** 2
- **目前列出的版本：** 21.24.3 (2.16.3)
- **最新列出的發布日期：** 2026-07-21
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.24.3 (2.16.3) | 未提供 | 2026-07-21 | 16.0 | 123.97 MB (129,987,803 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-dltube-cracked-21.24.3/youtube-dltube-cracked.ipa) |
| 21.28.3 (2.16.3) | 未提供 | 2026-07-14 | 16.0 | 140.28 MB (147,096,972 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-dltube-cracked-21.28.3/youtube-dltube-cracked.ipa) |

**版本說明：** Youtube 21.24.3 Moe DLTube 2.16.3 Cracked for iOS.

### 12. YouTube (Moe LRD, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** TubeLRD tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-lrd-cracked.png
- **功能／描述：** Youtube 21.41.5 Moe LRD 1.13 Cracked for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 21.41.5 (1.13)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 (1.13) | 未提供 | 2026-10-13 | 17.0 | 154.71 MB (162,229,592 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-cracked-21.41.5/youtube-lrd-cracked.ipa) |
| 21.40.5 (1.13) | 未提供 | 2026-10-08 | 17.0 | 154.79 MB (162,304,686 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-cracked-21.40.5/youtube-lrd-cracked.ipa) |
| 21.39.4 (1.13) | 未提供 | 2026-09-28 | 17.0 | 155.39 MB (162,939,846 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-cracked-21.39.4/youtube-lrd-cracked.ipa) |
| 21.38.2 (1.13) | 未提供 | 2026-09-21 | 17.0 | 155.46 MB (163,011,230 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-cracked-21.38.2/youtube-lrd-cracked.ipa) |
| 21.37.4 (1.13) | 未提供 | 2026-09-14 | 17.0 | 154.89 MB (162,411,668 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-lrd-cracked-21.37.4/youtube-lrd-cracked.ipa) |

**版本說明：** Youtube 21.41.5 Moe LRD 1.13 Cracked for iOS.

### 13. YouTube (Moe SY)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** SY tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-moe-sy.png
- **功能／描述：** Youtube 21.41.5 Moe SY 2.0 Moe for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 21.41.5 (2.0)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 (2.0) | 未提供 | 2026-10-13 | 17.0 | 154.15 MB (161,633,296 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-sy-21.41.5/youtube-moe-sy.ipa) |
| 21.40.5 (2.0) | 未提供 | 2026-10-08 | 17.0 | 154.22 MB (161,708,389 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-sy-21.40.5/youtube-moe-sy.ipa) |
| 21.39.4 (2.0) | 未提供 | 2026-09-28 | 17.0 | 154.82 MB (162,343,547 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-sy-21.39.4/youtube-moe-sy.ipa) |
| 21.38.2 (2.0) | 未提供 | 2026-09-21 | 17.0 | 154.89 MB (162,414,933 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-sy-21.38.2/youtube-moe-sy.ipa) |
| 21.37.4 (2.0) | 未提供 | 2026-09-14 | 17.0 | 154.32 MB (161,815,372 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-moe-sy-21.37.4/youtube-moe-sy.ipa) |

**版本說明：** Youtube 21.41.5 Moe SY 2.0 Moe for iOS.

### 14. YouTube (Moe YTPlus, Temp Free)

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** YTPlus tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-ytplus-temp-free.png
- **功能／描述：** Youtube 21.41.5 Moe YTPlus 5.2.1 Free for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 21.41.5 (5.2.1)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 (5.2.1) | 未提供 | 2026-10-13 | 17.0 | 160.35 MB (168,144,274 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-temp-free-21.41.5/youtube-ytplus-temp-free.ipa) |
| 21.40.5 (5.2.1) | 未提供 | 2026-10-08 | 17.0 | 160.43 MB (168,219,368 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-temp-free-21.40.5/youtube-ytplus-temp-free.ipa) |
| 21.39.4 (5.2.1) | 未提供 | 2026-09-28 | 17.0 | 161.03 MB (168,854,528 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-temp-free-21.39.4/youtube-ytplus-temp-free.ipa) |
| 21.38.2 (5.2.1) | 未提供 | 2026-09-21 | 17.0 | 161.10 MB (168,925,914 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-temp-free-21.38.2/youtube-ytplus-temp-free.ipa) |
| 21.37.4 (5.2.1) | 未提供 | 2026-09-14 | 17.0 | 160.53 MB (168,326,372 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-ytplus-temp-free-21.37.4/youtube-ytplus-temp-free.ipa) |

**版本說明：** Youtube 21.41.5 Moe YTPlus 5.2.1 Free for iOS.

### 15. YouTube Music

- **開發者：** Moe Apps
- **Bundle ID：** `com.google.ios.youtubemusic`
- **副標題：** Ultimate Enhanced tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/youtube-music.png
- **功能／描述：** Youtube Music 9.41.2 Ultimate Enhanced 2.4.1 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 9.41.2 (2.4.1)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.41.2 (2.4.1) | 未提供 | 2026-10-13 | 17.0 | 105.74 MB (110,880,317 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-music-9.41.2/youtube-music.ipa) |
| 9.40.2 (2.4.1) | 未提供 | 2026-10-08 | 17.0 | 105.35 MB (110,468,420 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-music-9.40.2/youtube-music.ipa) |
| 9.39.2 (2.4.1) | 未提供 | 2026-09-27 | 16.0 | 105.68 MB (110,810,055 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-music-9.39.2/youtube-music.ipa) |
| 9.38.1 (2.4.1) | 未提供 | 2026-09-22 | 16.0 | 105.90 MB (111,046,081 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-music-9.38.1/youtube-music.ipa) |
| 9.37.2 (2.4.1) | 未提供 | 2026-09-15 | 16.0 | 105.26 MB (110,368,024 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/youtube-music-9.37.2/youtube-music.ipa) |

**版本說明：** Youtube Music 9.41.2 Ultimate Enhanced 2.4.1 for iOS.

### 16. Instagram (Moe Multi)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** Multi-tweak loader
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-moe-multi.png
- **功能／描述：** Do not sign with ESign. Hold the Reels button or use a three-finger gesture to open Moe Multi. A fresh install is recomm...
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (8.5)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (8.5) | 未提供 | 2026-10-13 | 16.3 | 398.19 MB (417,529,373 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-moe-multi-451.0.0/instagram-moe-multi.ipa) |
| 450.1.0 (8.5) | 未提供 | 2026-10-08 | 16.3 | 391.07 MB (410,070,889 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-moe-multi-450.1.0/instagram-moe-multi.ipa) |
| 449.0.0 (8.5) | 未提供 | 2026-10-02 | 16.3 | 391.69 MB (410,721,101 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-moe-multi-449.0.0/instagram-moe-multi.ipa) |
| 448.0.0 (8.5) | 未提供 | 2026-09-21 | 16.3 | 385.27 MB (403,980,739 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-moe-multi-448.0.0/instagram-moe-multi.ipa) |
| 447.0.0 (8.5) | 未提供 | 2026-09-15 | 16.3 | 381.74 MB (400,278,502 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-moe-multi-447.0.0/instagram-moe-multi.ipa) |

**版本說明：** 8.4 changelog= added sparkle

### 17. Instagram (AC)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** AC tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-ac.png
- **功能／描述：** Instagram 451.0.0 AC 1.5 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (1.5)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (1.5) | 未提供 | 2026-10-13 | 16.3 | 302.69 MB (317,397,839 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ac-451.0.0/instagram-ac.ipa) |
| 450.1.0 (1.5) | 未提供 | 2026-10-08 | 16.3 | 295.04 MB (309,366,810 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ac-450.1.0/instagram-ac.ipa) |
| 449.0.0 (1.5) | 未提供 | 2026-10-02 | 16.3 | 295.72 MB (310,087,046 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ac-449.0.0/instagram-ac.ipa) |
| 448.0.0 (1.5) | 未提供 | 2026-09-21 | 16.3 | 288.89 MB (302,919,452 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ac-448.0.0/instagram-ac.ipa) |
| 447.0.0 (1.5) | 未提供 | 2026-09-15 | 16.3 | 285.34 MB (299,204,404 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ac-447.0.0/instagram-ac.ipa) |

**版本說明：** Instagram 451.0.0 AC 1.5 for iOS.

### 18. Instagram (BH)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** BH tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-bh.png
- **功能／描述：** Instagram 451.0.0 BH 1.2 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (1.2)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (1.2) | 未提供 | 2026-10-13 | 16.3 | 302.87 MB (317,577,116 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-bh-451.0.0/instagram-bh.ipa) |
| 450.1.0 (1.2) | 未提供 | 2026-10-08 | 16.3 | 295.21 MB (309,546,085 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-bh-450.1.0/instagram-bh.ipa) |
| 449.0.0 (1.2) | 未提供 | 2026-10-02 | 16.3 | 295.89 MB (310,266,322 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-bh-449.0.0/instagram-bh.ipa) |
| 448.0.0 (1.2) | 未提供 | 2026-09-21 | 16.3 | 289.06 MB (303,098,728 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-bh-448.0.0/instagram-bh.ipa) |
| 447.0.0 (1.2) | 未提供 | 2026-09-15 | 16.3 | 285.51 MB (299,383,681 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-bh-447.0.0/instagram-bh.ipa) |

**版本說明：** Instagram 451.0.0 BH 1.2 for iOS.

### 19. Instagram (DL, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** DL tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-dl-cracked.png
- **功能／描述：** Instagram 451.0.0 DL 2.5 Cracked for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (2.5)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (2.5) | 未提供 | 2026-10-13 | 16.3 | 303.08 MB (317,805,449 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-dl-cracked-451.0.0/instagram-dl-cracked.ipa) |
| 450.1.0 (2.5) | 未提供 | 2026-10-08 | 16.3 | 295.42 MB (309,774,421 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-dl-cracked-450.1.0/instagram-dl-cracked.ipa) |
| 449.0.0 (2.5) | 未提供 | 2026-10-02 | 16.3 | 296.11 MB (310,494,656 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-dl-cracked-449.0.0/instagram-dl-cracked.ipa) |
| 448.0.0 (2.5) | 未提供 | 2026-09-21 | 16.3 | 289.28 MB (303,327,063 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-dl-cracked-448.0.0/instagram-dl-cracked.ipa) |
| 447.0.0 (2.5) | 未提供 | 2026-09-15 | 16.3 | 285.73 MB (299,612,016 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-dl-cracked-447.0.0/instagram-dl-cracked.ipa) |

**版本說明：** Instagram 451.0.0 DL 2.5 Cracked for iOS.

### 20. Instagram (IGFormat)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** IGFormat tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-igformat.png
- **功能／描述：** instagram 451.0.0 IGFormat 2.6 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (2.6)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (2.6) | 未提供 | 2026-10-13 | 16.3 | 312.07 MB (327,224,212 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-igformat-451.0.0/instagram-igformat.ipa) |
| 450.1.0 (2.6) | 未提供 | 2026-10-08 | 16.3 | 304.41 MB (319,193,183 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-igformat-450.1.0/instagram-igformat.ipa) |
| 449.0.0 (2.6) | 未提供 | 2026-10-02 | 16.3 | 305.09 MB (319,913,418 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-igformat-449.0.0/instagram-igformat.ipa) |
| 448.0.0 (2.6) | 未提供 | 2026-09-21 | 16.3 | 298.26 MB (312,745,825 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-igformat-448.0.0/instagram-igformat.ipa) |
| 447.0.0 (2.6) | 未提供 | 2026-09-15 | 16.3 | 294.71 MB (309,030,778 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-igformat-447.0.0/instagram-igformat.ipa) |

**版本說明：** instagram 451.0.0 IGFormat 2.6 for iOS.

### 21. Instagram (INK Plus)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** INK Plus tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-ink-plus.png
- **功能／描述：** Instagram 451.0.0 INK Plus 5.2.10 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (5.2.10)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (5.2.10) | 未提供 | 2026-10-13 | 16.3 | 301.92 MB (316,584,521 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ink-plus-451.0.0/instagram-ink-plus.ipa) |
| 450.1.0 (5.2.10) | 未提供 | 2026-10-08 | 16.3 | 294.81 MB (309,126,931 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ink-plus-450.1.0/instagram-ink-plus.ipa) |
| 449.0.0 (5.2.10) | 未提供 | 2026-10-02 | 16.3 | 295.43 MB (309,776,322 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ink-plus-449.0.0/instagram-ink-plus.ipa) |
| 448.0.0 (5.2.10) | 未提供 | 2026-09-28 | 16.3 | 289.00 MB (303,036,050 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ink-plus-448.0.0/instagram-ink-plus.ipa) |
| 448.0.0 (5.2.9) | 未提供 | 2026-09-23 | 16.3 | 289.00 MB (303,036,984 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ink-plus-448.0.0/instagram-ink-plus.ipa) |

**版本說明：** Instagram 451.0.0 INK Plus 5.2.10 for iOS.

### 22. Instagram (LRD, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** LRD tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-lrd-cracked.png
- **功能／描述：** Instagram 451.0.0 LRD 2.19 Cracked for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (2.19)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (2.19) | 未提供 | 2026-10-13 | 16.3 | 306.82 MB (321,723,564 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-lrd-cracked-451.0.0/instagram-lrd-cracked.ipa) |
| 450.1.0 (2.19) | 未提供 | 2026-10-08 | 16.3 | 299.16 MB (313,692,534 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-lrd-cracked-450.1.0/instagram-lrd-cracked.ipa) |
| 449.0.0 (2.19) | 未提供 | 2026-10-02 | 16.3 | 299.85 MB (314,412,770 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-lrd-cracked-449.0.0/instagram-lrd-cracked.ipa) |
| 448.0.0 (2.19) | 未提供 | 2026-09-21 | 16.3 | 293.01 MB (307,245,176 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-lrd-cracked-448.0.0/instagram-lrd-cracked.ipa) |
| 447.0.0 (2.19) | 未提供 | 2026-09-15 | 16.3 | 289.47 MB (303,530,128 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-lrd-cracked-447.0.0/instagram-lrd-cracked.ipa) |

**版本說明：** Instagram 451.0.0 LRD 2.19 Cracked for iOS.

### 23. Instagram (Moe RyukGram)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** RyukGram tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-ryukgram.png
- **功能／描述：** Instagram 451.0.0 Moe RyukGram 1.4.5 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (1.4.5)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (1.4.5) | 未提供 | 2026-10-13 | 16.3 | 327.63 MB (343,548,814 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ryukgram-451.0.0/instagram-ryukgram.ipa) |
| 450.1.0 (1.4.5) | 未提供 | 2026-10-08 | 16.3 | 319.97 MB (335,517,779 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ryukgram-450.1.0/instagram-ryukgram.ipa) |
| 449.0.0 (1.4.0) | 未提供 | 2026-10-02 | 16.3 | 319.85 MB (335,387,061 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ryukgram-449.0.0/instagram-ryukgram.ipa) |
| 448.0.0 (1.4.0) | 未提供 | 2026-09-21 | 16.3 | 313.01 MB (328,219,467 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ryukgram-448.0.0/instagram-ryukgram.ipa) |
| 447.0.0 (1.4.0) | 未提供 | 2026-09-15 | 16.3 | 309.47 MB (324,504,430 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-ryukgram-447.0.0/instagram-ryukgram.ipa) |

**版本說明：** Instagram 451.0.0 Moe RyukGram 1.4.5 for iOS.

### 24. Instagram (NYX B2, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** NYX tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-nyx-b2-cracked.png
- **功能／描述：** Instagram 443.0.0 NYX 1.6.4 B2 Cracked for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 443.0.0 (1.6.4)
- **最新列出的發布日期：** 2026-08-18
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 443.0.0 (1.6.4) | 未提供 | 2026-08-18 | 16.3 | 295.29 MB (309,636,699 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b2-cracked-443.0.0/instagram-nyx-b2-cracked.ipa) |
| 442.0.0 (1.6.4) | 未提供 | 2026-08-10 | 16.3 | 315.67 MB (331,005,831 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b2-cracked-442.0.0/instagram-nyx-b2-cracked.ipa) |
| 441.0.0 (1.6.4) | 未提供 | 2026-08-03 | 16.3 | 318.76 MB (334,245,143 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b2-cracked-441.0.0/instagram-nyx-b2-cracked.ipa) |
| 439.0.0 (1.6.4) | 未提供 | 2026-07-21 | 16.3 | 316.62 MB (331,999,635 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b2-cracked-439.0.0/instagram-nyx-b2-cracked.ipa) |
| 438.0.0 (1.6.4) | 未提供 | 2026-07-14 | 16.3 | 305.94 MB (320,799,210 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b2-cracked-438.0.0/instagram-nyx-b2-cracked.ipa) |

**版本說明：** Instagram 443.0.0 NYX 1.6.4 B2 Cracked for iOS.

### 25. Instagram (NYX B4)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** NYX tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-nyx-b4.png
- **功能／描述：** instagram 451.0.0 NYX 1.7.2 Beta for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (1.7.2)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (1.7.2) | 未提供 | 2026-10-13 | 16.3 | 332.33 MB (348,468,665 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b4-451.0.0/instagram-nyx-b4.ipa) |
| 450.1.0 (1.7.2) | 未提供 | 2026-10-08 | 16.3 | 324.67 MB (340,437,632 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b4-450.1.0/instagram-nyx-b4.ipa) |
| 449.0.0 (1.7.2) | 未提供 | 2026-10-02 | 16.3 | 325.35 MB (341,157,877 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b4-449.0.0/instagram-nyx-b4.ipa) |
| 448.0.0 (1.7.2) | 未提供 | 2026-09-21 | 16.3 | 318.52 MB (333,990,282 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b4-448.0.0/instagram-nyx-b4.ipa) |
| 447.0.0 (1.7.2) | 未提供 | 2026-09-15 | 16.3 | 314.98 MB (330,275,242 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-nyx-b4-447.0.0/instagram-nyx-b4.ipa) |

**版本說明：** instagram 451.0.0 NYX 1.7.2 Beta for iOS.

### 26. Instagram (Regram)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** Regram OLED tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-regram.png
- **功能／描述：** Instagram 443.0.0 Regram 6.0 OLED 1.5 Moe for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 443.0.0 (1.5)
- **最新列出的發布日期：** 2026-08-20
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 443.0.0 (1.5) | 未提供 | 2026-08-20 | 16.3 | 303.96 MB (318,728,791 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-regram-443.0.0/instagram-regram.ipa) |
| 443.0.0 (1.5) | 未提供 | 2026-08-18 | 16.3 | 283.15 MB (296,908,805 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-regram-443.0.0/instagram-regram.ipa) |
| 439.0.0 (1.5) | 未提供 | 2026-08-11 | 16.3 | 304.89 MB (319,704,696 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-regram-439.0.0/instagram-regram.ipa) |
| 442.0.0 (1.4) | 未提供 | 2026-08-10 | 16.3 | 308.71 MB (323,711,087 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-regram-442.0.0/instagram-regram.ipa) |
| 441.0.0 (1.4) | 未提供 | 2026-08-03 | 16.3 | 311.88 MB (327,031,379 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-regram-441.0.0/instagram-regram.ipa) |

**版本說明：** Instagram 443.0.0 Regram 6.0 OLED 1.5 Moe for iOS.

### 27. Instagram (Rocket, Cracked)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** Rocket tweak build, cracked
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-rocket-cracked.png
- **功能／描述：** Instagram 451.0.0 Moe Rocket Cracked 4.3.3 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (4.3.3)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (4.3.3) | 未提供 | 2026-10-13 | 16.3 | 303.32 MB (318,052,926 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-rocket-cracked-451.0.0/instagram-rocket-cracked.ipa) |
| 450.1.0 (4.3.3) | 未提供 | 2026-10-08 | 16.3 | 295.66 MB (310,021,897 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-rocket-cracked-450.1.0/instagram-rocket-cracked.ipa) |
| 449.0.0 (4.3.3) | 未提供 | 2026-10-02 | 16.3 | 296.35 MB (310,742,133 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-rocket-cracked-449.0.0/instagram-rocket-cracked.ipa) |
| 448.0.0 (4.3.3) | 未提供 | 2026-09-21 | 16.3 | 289.51 MB (303,574,539 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-rocket-cracked-448.0.0/instagram-rocket-cracked.ipa) |
| 447.0.0 (4.3.3) | 未提供 | 2026-09-15 | 16.3 | 285.97 MB (299,859,490 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-rocket-cracked-447.0.0/instagram-rocket-cracked.ipa) |

**版本說明：** Instagram 451.0.0 Moe Rocket Cracked 4.3.3 for iOS.

### 28. Instagram (SC)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** SC tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-sc.png
- **功能／描述：** Instagram 451.0.0 SC 1.1.1 Moe for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (1.1.1)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (1.1.1) | 未提供 | 2026-10-13 | 16.3 | 302.76 MB (317,471,796 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-sc-451.0.0/instagram-sc.ipa) |
| 450.1.0 (1.1.1) | 未提供 | 2026-10-08 | 16.3 | 295.11 MB (309,440,765 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-sc-450.1.0/instagram-sc.ipa) |
| 449.0.0 (1.1.1) | 未提供 | 2026-10-02 | 16.3 | 295.79 MB (310,161,002 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-sc-449.0.0/instagram-sc.ipa) |
| 448.0.0 (1.1.1) | 未提供 | 2026-09-21 | 16.3 | 288.96 MB (302,993,408 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-sc-448.0.0/instagram-sc.ipa) |
| 447.0.0 (1.1.1) | 未提供 | 2026-09-15 | 16.3 | 285.41 MB (299,278,360 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-sc-447.0.0/instagram-sc.ipa) |

**版本說明：** Instagram 451.0.0 SC 1.1.1 Moe for iOS.

### 29. Instagram (Theta)

- **開發者：** Moe Apps
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** Theta tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/instagram-theta.png
- **功能／描述：** Instagram 451.0.0 Theta 5.0 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 451.0.0 (5.0)
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 16.3

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 (5.0) | 未提供 | 2026-10-13 | 16.3 | 321.17 MB (336,772,970 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-theta-451.0.0/instagram-theta.ipa) |
| 450.1.0 (5.0) | 未提供 | 2026-10-08 | 16.3 | 313.51 MB (328,741,936 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-theta-450.1.0/instagram-theta.ipa) |
| 449.0.0 (5.0) | 未提供 | 2026-10-02 | 16.3 | 314.20 MB (329,462,181 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-theta-449.0.0/instagram-theta.ipa) |
| 448.0.0 (5.0) | 未提供 | 2026-09-21 | 16.3 | 307.36 MB (322,294,587 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-theta-448.0.0/instagram-theta.ipa) |
| 447.0.0 (5.0) | 未提供 | 2026-09-15 | 16.3 | 303.82 MB (318,579,546 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/instagram-theta-447.0.0/instagram-theta.ipa) |

**版本說明：** Instagram 451.0.0 Theta 5.0 for iOS.

### 30. Twitch

- **開發者：** Moe Apps
- **Bundle ID：** `tv.twitch`
- **副標題：** Standard build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/twitch-bare.png
- **功能／描述：** Twitch is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details.
- **來源內版本數：** 1
- **目前列出的版本：** 24.2.4
- **最新列出的發布日期：** 2025-09-20
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 24.2.4 | 未提供 | 2025-09-20 | 16.4 | 114.61 MB (120,173,354 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-bare-24.2.4/twitch-bare.ipa) |

**版本說明：** Twitch is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details.

### 31. Twitch (Adfree, Moe Control)

- **開發者：** Moe Apps
- **Bundle ID：** `tv.twitch`
- **副標題：** Adfree tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/twitch-adfree.png
- **功能／描述：** hold down with 3 fingers for 4 seconds to open the mod menu
- **來源內版本數：** 1
- **目前列出的版本：** 29.0 (0.0.2)
- **最新列出的發布日期：** 2026-04-17
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 29.0 (0.0.2) | 未提供 | 2026-04-17 | 16.4 | 145.16 MB (152,208,247 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-adfree-29.0/twitch-adfree.ipa) |

**版本說明：** alternate adfree ipa hold down with 3 fingers for 4 seconds to open the mod menu

### 32. Twitch (Tweach)

- **開發者：** Moe Apps
- **Bundle ID：** `tv.twitch`
- **副標題：** Tweach tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/twitch-tweach.png
- **功能／描述：** Twitch 29.0 Tweach 2.3.1 is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details.
- **來源內版本數：** 1
- **目前列出的版本：** 29.0 (2.3.1)
- **最新列出的發布日期：** 2026-04-17
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 29.0 (2.3.1) | 未提供 | 2026-04-17 | 16.4 | 154.31 MB (161,808,661 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-tweach-29.0/twitch-tweach.ipa) |

**版本說明：** Twitch 29.0 Tweach 2.3.1 is an iOS release entry for Twitch: Live Streaming on Moe's App Hub, with version, file size, icon, and install details.

### 33. Twitch (Moe TwitchControl)

- **開發者：** Moe Apps
- **Bundle ID：** `tv.twitch`
- **副標題：** TwitchControl tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/twitch-twitchcontrol.png
- **功能／描述：** for adblock to work, open mod menu, and import the file you download from https://tinyurl.com/3n9sz6mv into the mods set...
- **來源內版本數：** 5
- **目前列出的版本：** 31.5 (0.0.6)
- **最新列出的發布日期：** 2026-10-08
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 31.5 (0.0.6) | 未提供 | 2026-10-08 | 16.4 | 182.30 MB (191,154,778 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-twitchcontrol-31.5/twitch-twitchcontrol.ipa) |
| 31.4.4 (0.0.6) | 未提供 | 2026-10-01 | 16.4 | 177.22 MB (185,826,808 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-twitchcontrol-31.4.4/twitch-twitchcontrol.ipa) |
| 31.4.2 (0.0.6) | 未提供 | 2026-09-30 | 16.4 | 177.20 MB (185,812,509 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-twitchcontrol-31.4.2/twitch-twitchcontrol.ipa) |
| 31.4 (0.0.6) | 未提供 | 2026-09-28 | 16.4 | 177.21 MB (185,813,460 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-twitchcontrol-31.4/twitch-twitchcontrol.ipa) |
| 31.3.2 (0.0.6) | 未提供 | 2026-09-22 | 16.4 | 175.26 MB (183,771,301 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitch-twitchcontrol-31.3.2/twitch-twitchcontrol.ipa) |

**版本說明：** for adblock to work, open mod menu, and import the file you download from https://tinyurl.com/3n9sz6mv into the mods settings

### 34. Twitch (Twitchv, Moe Tweach)

- **開發者：** Moe Apps
- **Bundle ID：** `tv.twitch`
- **副標題：** Tweach tweak build
- **圖示：** https://raw.githubusercontent.com/MountainofPenguin/moe-altstore/main/icons/twitchv-tweach.png
- **功能／描述：** Twitch 31.5 Tweach 2.4.1 for iOS.
- **來源內版本數：** 5
- **目前列出的版本：** 31.5 (2.4.1)
- **最新列出的發布日期：** 2026-10-08
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 31.5 (2.4.1) | 未提供 | 2026-10-08 | 16.4 | 192.76 MB (202,124,649 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitchv-tweach-31.5/twitchv-tweach.ipa) |
| 31.4.4 (2.4.1) | 未提供 | 2026-10-01 | 16.4 | 187.68 MB (196,796,683 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitchv-tweach-31.4.4/twitchv-tweach.ipa) |
| 31.4.2 (2.4.1) | 未提供 | 2026-09-30 | 16.4 | 187.67 MB (196,782,384 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitchv-tweach-31.4.2/twitchv-tweach.ipa) |
| 31.4 (2.4.1) | 未提供 | 2026-09-28 | 16.4 | 187.67 MB (196,783,335 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitchv-tweach-31.4/twitchv-tweach.ipa) |
| 31.3.2 (2.4.1) | 未提供 | 2026-09-22 | 16.4 | 185.72 MB (194,741,174 bytes) | [下載](https://github.com/MountainofPenguin/moe-altstore/releases/download/twitchv-tweach-31.3.2/twitchv-tweach.ipa) |

**版本說明：** Twitch 31.5 Tweach 2.4.1 for iOS.

## 二、IPA Vault

- **來源 JSON：** https://raw.githubusercontent.com/927tx/IPA-Vault/main/ipavaultsource.json
- **來源首頁：** https://github.com/927tx/IPA-Vault
- **App 數量：** 63

### 1. Discord (RainTweak)

- **開發者：** Ra1ncord & IPA Vault
- **Bundle ID：** `com.hammerandchisel.discord`
- **副標題：** Discord 349.0 with RainTweak 0.10.0
- **主題色：** `#5865F2`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Discord-Icons/Discord-AppStore-1024x1024.png
- **功能／描述：** Discord 349.0 with RainTweak 0.10.0
- **來源內版本數：** 1
- **目前列出的版本：** 349.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 349.0 | 未提供 | 2026-10-13 | 未提供 | 104.03 MB (109,083,695 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Discord-349.0-RainTweak.ipa) |

**版本說明：** Discord 349.0 with RainTweak 0.10.0

### 2. Facebook (iQFace)

- **開發者：** 7MD & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.facebook.Facebook`
- **副標題：** Facebook 582.0.0 with iQFace 1.2
- **主題色：** `#1877F2`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Facebook-Icons/Facebook-AppStore-1024x1024.png
- **功能／描述：** Facebook 582.0.0 with iQFace 1.2
- **來源內版本數：** 1
- **目前列出的版本：** 582.0.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 582.0.0 | 未提供 | 2026-10-09 | 未提供 | 223.92 MB (234,797,502 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Facebook-582.0.0-iQFace.ipa) |

**版本說明：** Facebook 582.0.0 with iQFace 1.2

### 3. Facebook (Facebook Plus)

- **開發者：** shajon404 & IPA Vault
- **Bundle ID：** `com.facebook.Facebook.facebookplus`
- **副標題：** Facebook 582.0.0 with Facebook Plus 1.0.1
- **主題色：** `#1877F2`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Facebook-Icons/Facebook-AppStore-1024x1024.png
- **功能／描述：** Facebook 582.0.0 with Facebook Plus 1.0.1
- **來源內版本數：** 1
- **目前列出的版本：** 582.0.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 582.0.0 | 未提供 | 2026-10-09 | 未提供 | 217.13 MB (227,674,605 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Facebook-582.0.0-Facebook-Plus.ipa) |

**版本說明：** Facebook 582.0.0 with Facebook Plus 1.0.1

### 4. Google Photos (Gunshot) (iOS 16.1+)

- **開發者：** tqmane & IPA Vault
- **Bundle ID：** `com.google.Photos.v7-20-2`
- **副標題：** Google Photos 7.20.2 with Gunshot 0.3.0 (iOS 16.1+)
- **主題色：** `#4285F4`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Google-Photos-Icons/Google-Photos-AppStore-1024x1024.png
- **功能／描述：** Google Photos 7.20.2 with Gunshot 0.3.0 (iOS 16.1+)
- **來源內版本數：** 1
- **目前列出的版本：** 7.20.2
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 7.20.2 | 未提供 | 2026-10-09 | 未提供 | 121.71 MB (127,620,974 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/GooglePhotos-7.20.2-Gunshot.ipa) |

**版本說明：** Google Photos 7.20.2 with Gunshot 0.3.0 (iOS 16.1+)

### 5. Google Photos (Gunshot) (iOS 17+)

- **開發者：** tqmane & IPA Vault
- **Bundle ID：** `com.google.Photos.v7-44-0`
- **副標題：** Google Photos 7.44.0 with Gunshot 0.3.0 (iOS 17+)
- **主題色：** `#4285F4`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Google-Photos-Icons/Google-Photos-AppStore-1024x1024.png
- **功能／描述：** Google Photos 7.44.0 with Gunshot 0.3.0 (iOS 17+)
- **來源內版本數：** 1
- **目前列出的版本：** 7.44.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 7.44.0 | 未提供 | 2026-10-09 | 未提供 | 137.84 MB (144,535,046 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/GooglePhotos-7.44.0-Gunshot.ipa) |

**版本說明：** Google Photos 7.44.0 with Gunshot 0.3.0 (iOS 17+)

### 6. Google Photos (Gunshot)

- **開發者：** tqmane & IPA Vault
- **Bundle ID：** `com.google.Photos`
- **副標題：** Google Photos 7.96.0 with Gunshot 0.3.0
- **主題色：** `#4285F4`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Google-Photos-Icons/Google-Photos-AppStore-1024x1024.png
- **功能／描述：** Google Photos 7.96.0 with Gunshot 0.3.0
- **來源內版本數：** 1
- **目前列出的版本：** 7.96.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 7.96.0 | 未提供 | 2026-10-09 | 未提供 | 172.91 MB (181,305,965 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/GooglePhotos-7.96.0-Gunshot.ipa) |

**版本說明：** Google Photos 7.96.0 with Gunshot 0.3.0

### 7. iMe (MxGram)

- **開發者：** m1ronx1412 & IPA Vault
- **Bundle ID：** `com.olcorporation.olai.mxgram`
- **副標題：** iMe 12.8.1 with MxGram 1.0.0
- **主題色：** `#2AABEE`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/iMe-Icons/iMe-AppStore-1024x1024.png
- **功能／描述：** iMe 12.8.1 with MxGram 1.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 12.8.1
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.8.1 | 未提供 | 2026-09-01 | 未提供 | 141.31 MB (148,174,542 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/iMe-12.8.1-MxGram.ipa) |

**版本說明：** iMe 12.8.1 with MxGram 1.0.0

### 8. iMe (iQTele)

- **開發者：** 7MD & IPA Vault
- **Bundle ID：** `com.olcorporation.olai`
- **副標題：** iMe 12.8.1 with iQTele 1.2
- **主題色：** `#2AABEE`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/iMe-Icons/iMe-AppStore-1024x1024.png
- **功能／描述：** iMe 12.8.1 with iQTele 1.2
- **來源內版本數：** 1
- **目前列出的版本：** 12.8.1
- **最新列出的發布日期：** 2026-09-05

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.8.1 | 未提供 | 2026-09-05 | 未提供 | 132.78 MB (139,224,713 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/iMe-12.8.1-iQTele.ipa) |

**版本說明：** iMe 12.8.1 with iQTele 1.2

### 9. Infuse Plus (7.8.4)

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.firecore.infuse.v7-8-4`
- **副標題：** Infuse 7.8.4 with Infuse Plus 2.6
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Infuse-icons/Infuse-AppStore-1024x1024.png
- **功能／描述：** Infuse 7.8.4 with Infuse Plus 2.6
- **來源內版本數：** 1
- **目前列出的版本：** 7.8.4
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 7.8.4 | 未提供 | 2026-09-01 | 未提供 | 65.99 MB (69,195,129 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Infuse-7.8.4-Infuse-Plus.ipa) |

**版本說明：** Infuse 7.8.4 with Infuse Plus 2.6

### 10. Infuse Plus (8.2.4)

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.firecore.infuse.v8-2-4`
- **副標題：** Infuse 8.2.4 with Infuse Plus 2.6
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Infuse-icons/Infuse-AppStore-1024x1024.png
- **功能／描述：** Infuse 8.2.4 with Infuse Plus 2.6
- **來源內版本數：** 1
- **目前列出的版本：** 8.2.4
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 8.2.4 | 未提供 | 2026-09-01 | 未提供 | 66.76 MB (70,005,530 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Infuse-8.2.4-Infuse-Plus.ipa) |

**版本說明：** Infuse 8.2.4 with Infuse Plus 2.6

### 11. Infuse Plus (8.5.7)

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.firecore.infuse`
- **副標題：** Infuse 8.5.7 with Infuse Plus 2.6
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Infuse-icons/Infuse-AppStore-1024x1024.png
- **功能／描述：** Infuse 8.5.7 with Infuse Plus 2.6
- **來源內版本數：** 1
- **目前列出的版本：** 8.5.7
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 8.5.7 | 未提供 | 2026-10-13 | 未提供 | 92.67 MB (97,173,009 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Infuse-8.5.7-Infuse-Plus.ipa) |

**版本說明：** Infuse 8.5.7 with Infuse Plus 2.6

### 12. Husk

- **開發者：** Leviidev & IPA Vault
- **Bundle ID：** `com.husk.app`
- **副標題：** Husk 1.1.0
- **主題色：** `#64748B`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Husk-Icons/Icon-Default_Normal.png
- **功能／描述：** Husk 1.1.0
- **來源內版本數：** 1
- **目前列出的版本：** 1.1.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.1.0 | 未提供 | 2026-10-09 | 未提供 | 51.87 MB (54,385,494 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Husk-1.1.0.ipa) |

**版本說明：** Husk 1.1.0

### 13. Instagram (Regram 6.4)

- **開發者：** IPA Vault
- **Bundle ID：** `com.burbn.instagram.regram`
- **副標題：** Instagram 451.0.0 with Regram 6.4 cracked
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with Regram 6.4 cracked
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 315.03 MB (330,328,160 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-Regram.ipa) |

**版本說明：** Instagram 451.0.0 with Regram 6.4 cracked

### 14. Instagram (Regram 6.4) (No Plugins)

- **開發者：** IPA Vault
- **Bundle ID：** `com.burbn.instagram.regram.noplugins`
- **副標題：** IG 451.0.0 (Regram 6.4 cracked) (No Plugins)
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with Regram 6.4 cracked (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 264.17 MB (277,000,750 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-Regram-No-Plugins.ipa) |

**版本說明：** Instagram 451.0.0 with Regram 6.4 cracked (No Plugins)

### 15. Instagram (RyukGram No Plugins)

- **開發者：** faroukbmiled & IPA Vault
- **Bundle ID：** `com.burbn.instagram.ryukgram.noplugins`
- **副標題：** Instagram 451.0.0 with RyukGram 1.4.5 (No Plugins)
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with RyukGram 1.4.5 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 264.41 MB (277,250,463 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-RyukGram-No-Plugins.ipa) |

**版本說明：** Instagram 451.0.0 with RyukGram 1.4.5 (No Plugins)

### 16. Instagram (RyukGram)

- **開發者：** faroukbmiled & IPA Vault
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** Instagram 451.0.0 with RyukGram 1.4.5
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with RyukGram 1.4.5
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 329.10 MB (345,086,224 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-RyukGram.ipa) |

**版本說明：** Instagram 451.0.0 with RyukGram 1.4.5

### 17. Instagram (Sparkle No Plugins)

- **開發者：** efibalogh & CieLogic & IPA Vault
- **Bundle ID：** `com.burbn.instagram.sparkle.noplugins`
- **副標題：** Instagram 451.0.0 with Sparkle 1.5.1 (No Plugins)
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with Sparkle 1.5.1 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 267.43 MB (280,423,332 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-Sparkle-No-Plugins.ipa) |

**版本說明：** Instagram 451.0.0 with Sparkle 1.5.1 (No Plugins)

### 18. Instagram (Sparkle)

- **開發者：** efibalogh & CieLogic & IPA Vault
- **Bundle ID：** `com.burbn.instagram.sparkle`
- **副標題：** Instagram 451.0.0 with Sparkle 1.5.1
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Instagram-Icons/Instagram-AppStore-1024x1024.png
- **功能／描述：** Instagram 451.0.0 with Sparkle 1.5.1
- **來源內版本數：** 1
- **目前列出的版本：** 451.0.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0.0 | 未提供 | 2026-10-13 | 未提供 | 322.98 MB (338,667,077 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Instagram-451.0.0-Sparkle.ipa) |

**版本說明：** Instagram 451.0.0 with Sparkle 1.5.1

### 19. Messenger (Flow)

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.facebook.Messenger.flow`
- **副標題：** Messenger 582.0.0 with Flow 1.0
- **主題色：** `#0084FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Messenger-Icons/Messenger-AppStore-1024x1024.png
- **功能／描述：** Messenger 582.0.0 with Flow 1.0
- **來源內版本數：** 1
- **目前列出的版本：** 582.0.0
- **最新列出的發布日期：** 2026-10-07

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 582.0.0 | 未提供 | 2026-10-07 | 未提供 | 111.30 MB (116,709,494 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Messenger-582.0.0-Flow.ipa) |

**版本說明：** Messenger 582.0.0 with Flow 1.0

### 20. Messenger (Login)

- **開發者：** IPA Vault
- **Bundle ID：** `com.facebook.Messenger.login`
- **副標題：** Messenger 523.0.0 login build
- **主題色：** `#0084FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Messenger-Icons/Messenger-AppStore-1024x1024.png
- **功能／描述：** Messenger 523.0.0 login build
- **來源內版本數：** 1
- **目前列出的版本：** 523.0.0
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 523.0.0 | 未提供 | 2026-09-01 | 未提供 | 71.79 MB (75,278,231 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Messenger-523.0.0-Login.ipa) |

**版本說明：** Messenger 523.0.0 login build

### 21. Messenger (MSGPlusX)

- **開發者：** Dens0r & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.facebook.Messenger`
- **副標題：** Messenger 582.0.0 with MSGPlusX 1.1
- **主題色：** `#0084FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Messenger-Icons/Messenger-AppStore-1024x1024.png
- **功能／描述：** Messenger 582.0.0 with MSGPlusX 1.1
- **來源內版本數：** 1
- **目前列出的版本：** 582.0.0
- **最新列出的發布日期：** 2026-10-07

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 582.0.0 | 未提供 | 2026-10-07 | 未提供 | 111.45 MB (116,866,041 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Messenger-582.0.0-MSGPlusX.ipa) |

**版本說明：** Messenger 582.0.0 with MSGPlusX 1.1

### 22. Nagram (MxGram)

- **開發者：** m1ronx1412 & IPA Vault
- **Bundle ID：** `xyz.nextalone.nagram.mxgram`
- **副標題：** Nagram 13.0.1 with MxGram 1.0.0
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Nagram-Icons/Nagram-AppStore-1024x1024.png
- **功能／描述：** Nagram 13.0.1 with MxGram 1.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 13.0.1
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0.1 | 未提供 | 2026-10-13 | 未提供 | 107.67 MB (112,895,169 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Nagram-13.0.1-MxGram.ipa) |

**版本說明：** Nagram 13.0.1 with MxGram 1.0.0

### 23. Nagram (iQTele)

- **開發者：** 7MD & IPA Vault
- **Bundle ID：** `xyz.nextalone.nagram`
- **副標題：** Nagram 13.0.1 with iQTele 1.4
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Nagram-Icons/Nagram-AppStore-1024x1024.png
- **功能／描述：** Nagram 13.0.1 with iQTele 1.4
- **來源內版本數：** 1
- **目前列出的版本：** 13.0.1
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0.1 | 未提供 | 2026-10-13 | 未提供 | 100.33 MB (105,208,769 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Nagram-13.0.1-iQTele.ipa) |

**版本說明：** Nagram 13.0.1 with iQTele 1.4

### 24. Nagram (TGExtra)

- **開發者：** swiftleopard & IPA Vault
- **Bundle ID：** `xyz.nextalone.nagram.tgextra`
- **副標題：** Nagram 13.0.1 with TGExtra 1.7.7
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Nagram-Icons/Nagram-AppStore-1024x1024.png
- **功能／描述：** Nagram 13.0.1 with TGExtra 1.7.7
- **來源內版本數：** 1
- **目前列出的版本：** 13.0.1
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0.1 | 未提供 | 2026-10-13 | 未提供 | 99.74 MB (104,589,096 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Nagram-13.0.1-TGExtra.ipa) |

**版本說明：** Nagram 13.0.1 with TGExtra 1.7.7

### 25. Reddit (Login)

- **開發者：** IPA Vault
- **Bundle ID：** `com.reddit.Reddit.login`
- **副標題：** Reddit 2024.12.0 login build
- **主題色：** `#FF4500`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Reddit-Icons/Reddit-AppStore-1024x1024.png
- **功能／描述：** Reddit 2024.12.0 login build
- **來源內版本數：** 1
- **目前列出的版本：** 2024.12.0
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2024.12.0 | 未提供 | 2026-09-01 | 未提供 | 109.86 MB (115,192,852 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Reddit-2024.12.0-Login.ipa) |

**版本說明：** Reddit 2024.12.0 login build

### 26. Reddit (RedditFilter)

- **開發者：** Moe & IPA Vault
- **Bundle ID：** `com.reddit.Reddit`
- **副標題：** Reddit 2026.41.0 with RedditFilter 4.6.1
- **主題色：** `#FF4500`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Reddit-Icons/Reddit-AppStore-1024x1024.png
- **功能／描述：** Reddit 2026.41.0 with RedditFilter 4.6.1
- **來源內版本數：** 1
- **目前列出的版本：** 2026.41.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2026.41.0 | 未提供 | 2026-10-13 | 未提供 | 140.58 MB (147,412,514 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Reddit-2026.41.0-RedditFilter.ipa) |

**版本說明：** Reddit 2026.41.0 with RedditFilter 4.6.1

### 27. SoundCloud (NexaSC) (iOS 16.0-16.3)

- **開發者：** cielogic & IPA Vault
- **Bundle ID：** `com.soundcloud.TouchApp.nexasc.v7-68-1`
- **副標題：** SoundCloud 7.68.1 with NexaSC beta 4
- **主題色：** `#FF5500`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/SoundCloud-7.68.1-Icons/SoundCloud-7.68.1-AppStore-1024x1024.png
- **功能／描述：** SoundCloud 7.68.1 with NexaSC beta 4
- **來源內版本數：** 1
- **目前列出的版本：** 7.68.1
- **最新列出的發布日期：** 2026-09-01

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 7.68.1 | 未提供 | 2026-09-01 | 未提供 | 93.74 MB (98,298,525 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/SoundCloud-7.68.1-NexaSC.ipa) |

**版本說明：** SoundCloud 7.68.1 with NexaSC beta 4

### 28. SoundCloud (NexaSC)

- **開發者：** cielogic & IPA Vault
- **Bundle ID：** `com.soundcloud.TouchApp`
- **副標題：** SoundCloud 8.82.0 with NexaSC beta 4
- **主題色：** `#FF5500`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/SoundCloud-8.76.0-Icons/SoundCloud-AppStore-1024x1024.png
- **功能／描述：** SoundCloud 8.82.0 with NexaSC beta 4
- **來源內版本數：** 1
- **目前列出的版本：** 8.82.0
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 8.82.0 | 未提供 | 2026-10-11 | 未提供 | 216.71 MB (227,238,033 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/SoundCloud-8.82.0-NexaSC.ipa) |

**版本說明：** SoundCloud 8.82.0 with NexaSC beta 4

### 29. Swiftgram (MxGram)

- **開發者：** m1ronx1412 & IPA Vault
- **Bundle ID：** `app.swiftgram.ios.mxgram`
- **副標題：** Swiftgram 13.0 with MxGram 1.0.0
- **主題色：** `#F85C2C`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Swiftgram-Icons/Swiftgram-AppStore-1024x1024.png
- **功能／描述：** Swiftgram 13.0 with MxGram 1.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 13.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0 | 未提供 | 2026-10-13 | 未提供 | 93.05 MB (97,568,937 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Swiftgram-13.0-MxGram.ipa) |

**版本說明：** Swiftgram 13.0 with MxGram 1.0.0

### 30. Swiftgram (iQTele)

- **開發者：** 7MD & IPA Vault
- **Bundle ID：** `app.swiftgram.ios`
- **副標題：** Swiftgram 12.9.4 with iQTele 1.4
- **主題色：** `#F85C2C`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Swiftgram-Icons/Swiftgram-AppStore-1024x1024.png
- **功能／描述：** Swiftgram 12.9.4 with iQTele 1.4
- **來源內版本數：** 1
- **目前列出的版本：** 12.9.4
- **最新列出的發布日期：** 2026-10-03

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.9.4 | 未提供 | 2026-10-03 | 未提供 | 74.36 MB (77,976,994 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Swiftgram-12.9.4-iQTele.ipa) |

**版本說明：** Swiftgram 12.9.4 with iQTele 1.4

### 31. Swiftgram (TGExtra)

- **開發者：** swiftleopard & IPA Vault
- **Bundle ID：** `app.swiftgram.ios.tgextra`
- **副標題：** Swiftgram 13.0 with TGExtra 1.7.7
- **主題色：** `#F85C2C`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Swiftgram-Icons/Swiftgram-AppStore-1024x1024.png
- **功能／描述：** Swiftgram 13.0 with TGExtra 1.7.7
- **來源內版本數：** 1
- **目前列出的版本：** 13.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0 | 未提供 | 2026-10-13 | 未提供 | 85.13 MB (89,262,870 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Swiftgram-13.0-TGExtra.ipa) |

**版本說明：** Swiftgram 13.0 with TGExtra 1.7.7

### 32. Telegram (MxGram)

- **開發者：** m1ronx1412 & IPA Vault
- **Bundle ID：** `ph.telegra.Telegraph.mxgram`
- **副標題：** Telegram 13.0 with MxGram 1.0.0
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Telegram-Icons/Telegram-AppStore-1024x1024.png
- **功能／描述：** Telegram 13.0 with MxGram 1.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 13.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0 | 未提供 | 2026-10-09 | 未提供 | 87.45 MB (91,697,454 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Telegram-13.0-MxGram.ipa) |

**版本說明：** Telegram 13.0 with MxGram 1.0.0

### 33. Telegram (iQTele)

- **開發者：** 7MD & IPA Vault
- **Bundle ID：** `ph.telegra.Telegraph`
- **副標題：** Telegram 13.0 with iQTele 1.4
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Telegram-Icons/Telegram-AppStore-1024x1024.png
- **功能／描述：** Telegram 13.0 with iQTele 1.4
- **來源內版本數：** 1
- **目前列出的版本：** 13.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0 | 未提供 | 2026-10-09 | 未提供 | 80.12 MB (84,011,090 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Telegram-13.0-iQTele.ipa) |

**版本說明：** Telegram 13.0 with iQTele 1.4

### 34. Telegram (TGExtra)

- **開發者：** swiftleopard & IPA Vault
- **Bundle ID：** `ph.telegra.Telegraph.tgextra`
- **副標題：** Telegram 13.0 with TGExtra 1.7.8
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Telegram-Icons/Telegram-AppStore-1024x1024.png
- **功能／描述：** Telegram 13.0 with TGExtra 1.7.8
- **來源內版本數：** 1
- **目前列出的版本：** 13.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 13.0 | 未提供 | 2026-10-09 | 未提供 | 79.53 MB (83,391,380 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Telegram-13.0-TGExtra.ipa) |

**版本說明：** Telegram 13.0 with TGExtra 1.7.8

### 35. Spotify (EeveeSpotify)

- **開發者：** skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client.eeveespotify`
- **副標題：** Spotify 9.1.90 with EeveeSpotify 7.0.0
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.90 with EeveeSpotify 7.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.90
- **最新列出的發布日期：** 2026-10-08

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.90 | 未提供 | 2026-10-08 | 未提供 | 133.74 MB (140,240,862 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.90-EeveeSpotify.ipa) |

**版本說明：** Spotify 9.1.90 with EeveeSpotify 7.0.0

### 36. Spotify (EeveeSpotify) (No Plugins)

- **開發者：** skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client.eeveespotify.noplugins`
- **副標題：** Spotify 9.1.90 with EeveeSpotify 7.0.0 (No Plugins)
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.90 with EeveeSpotify 7.0.0 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.90
- **最新列出的發布日期：** 2026-10-08

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.90 | 未提供 | 2026-10-08 | 未提供 | 131.10 MB (137,469,098 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.90-EeveeSpotify-No-Plugins.ipa) |

**版本說明：** Spotify 9.1.90 with EeveeSpotify 7.0.0 (No Plugins)

### 37. Spotify (Vitrine)

- **開發者：** MyNameIsJeff & skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client`
- **副標題：** Spotify 9.1.90 with Vitrine 1.0.0-b13
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.90 with Vitrine 1.0.0-b13
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.90
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.90 | 未提供 | 2026-10-13 | 未提供 | 125.24 MB (131,327,168 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.90-Vitrine.ipa) |

**版本說明：** Spotify 9.1.90 with Vitrine 1.0.0-b13

### 38. Spotify (Vitrine) (No Plugins)

- **開發者：** MyNameIsJeff & skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client.vitrine.noplugins`
- **副標題：** Spotify 9.1.90 with Vitrine 1.0.0-b13 (No Plugins)
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.90 with Vitrine 1.0.0-b13 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.90
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.90 | 未提供 | 2026-10-13 | 未提供 | 124.19 MB (130,219,610 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.90-Vitrine-No-Plugins.ipa) |

**版本說明：** Spotify 9.1.90 with Vitrine 1.0.0-b13 (No Plugins)

### 39. Spotify (Eevee + Chroma) (9.1.78)

- **開發者：** skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client.v9-1-78`
- **副標題：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.78
- **最新列出的發布日期：** 2026-10-05

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.78 | 未提供 | 2026-10-05 | 未提供 | 130.59 MB (136,933,817 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.78-Eevee-Chroma-pw.ipa) |

**版本說明：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0

### 40. Spotify (Eevee + Chroma) (9.1.78) (No Plugins)

- **開發者：** skopevoj & IPA Vault
- **Bundle ID：** `com.spotify.client.spotipw.noplugins.v9-1-78`
- **副標題：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0 (No Plugins)
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.78
- **最新列出的發布日期：** 2026-10-05

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.78 | 未提供 | 2026-10-05 | 未提供 | 129.83 MB (136,138,258 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.78-Eevee-Chroma-pw-No-Plugins.ipa) |

**版本說明：** Spotify 9.1.78 with EeveeSpotify 7.0.0 + Chroma.pw 0.50.0 (No Plugins)

### 41. Threads (ThreadSaver)

- **開發者：** swiftleopard & IPA Vault
- **Bundle ID：** `com.burbn.barcelona`
- **副標題：** Threads 451.0 with ThreadSaver
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Threads-Icons/Threads-AppStore-1024x1024.png
- **功能／描述：** Threads 451.0 with ThreadSaver
- **來源內版本數：** 1
- **目前列出的版本：** 451.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0 | 未提供 | 2026-10-13 | 未提供 | 107.76 MB (112,995,145 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Threads-451.0-ThreadSaver.ipa) |

**版本說明：** Threads 451.0 with ThreadSaver

### 42. TikTok (Infinitok)

- **開發者：** Mod4 & IPA Vault
- **Bundle ID：** `com.zhiliaoapp.musically`
- **副標題：** TikTok 47.1.0 with Infinitok 0.0.2
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/TikTok-Icons/TikTok-AppStore-1024x1024.png
- **功能／描述：** TikTok 47.1.0 with Infinitok 0.0.2
- **來源內版本數：** 1
- **目前列出的版本：** 47.1.0
- **最新列出的發布日期：** 2026-10-07

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 47.1.0 | 未提供 | 2026-10-07 | 未提供 | 468.64 MB (491,405,708 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/TikTok-47.1.0-Infinitok.ipa) |

**版本說明：** TikTok 47.1.0 with Infinitok 0.0.2

### 43. Turrit (MxGram)

- **開發者：** m1ronx1412 & IPA Vault
- **Bundle ID：** `com.seastar.turrit.mxgram`
- **副標題：** Turrit 1.5.5 with MxGram 1.0.0
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Turrit-Icons/Turrit-AppStore-1024x1024.png
- **功能／描述：** Turrit 1.5.5 with MxGram 1.0.0
- **來源內版本數：** 1
- **目前列出的版本：** 1.5.5
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.5.5 | 未提供 | 2026-10-09 | 未提供 | 102.39 MB (107,363,861 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Turrit-1.5.5-MxGram.ipa) |

**版本說明：** Turrit 1.5.5 with MxGram 1.0.0

### 44. Turrit (iQTele)

- **開發者：** 7MD & IPA Vault
- **Bundle ID：** `com.seastar.turrit`
- **副標題：** Turrit 1.5.5 with iQTele 1.4
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Turrit-Icons/Turrit-AppStore-1024x1024.png
- **功能／描述：** Turrit 1.5.5 with iQTele 1.4
- **來源內版本數：** 1
- **目前列出的版本：** 1.5.5
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.5.5 | 未提供 | 2026-10-09 | 未提供 | 95.06 MB (99,677,471 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Turrit-1.5.5-iQTele.ipa) |

**版本說明：** Turrit 1.5.5 with iQTele 1.4

### 45. Turrit (TGExtra)

- **開發者：** swiftleopard & IPA Vault
- **Bundle ID：** `com.seastar.turrit.tgextra`
- **副標題：** Turrit 1.5.5 with TGExtra 1.7.7
- **主題色：** `#0088CC`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Turrit-Icons/Turrit-AppStore-1024x1024.png
- **功能／描述：** Turrit 1.5.5 with TGExtra 1.7.7
- **來源內版本數：** 1
- **目前列出的版本：** 1.5.5
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.5.5 | 未提供 | 2026-10-09 | 未提供 | 94.43 MB (99,020,717 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Turrit-1.5.5-TGExtra.ipa) |

**版本說明：** Turrit 1.5.5 with TGExtra 1.7.7

### 46. TwitchUnblock

- **開發者：** MXFia19 & IPA Vault
- **Bundle ID：** `com.mxfia19.TwitchUnblock`
- **副標題：** TwitchUnblock 1.3.0
- **主題色：** `#9146FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Twitch-Tweach-TC-Icons/Twitch-AppStore-1024x1024.png
- **功能／描述：** TwitchUnblock 1.3.0
- **來源內版本數：** 1
- **目前列出的版本：** 1.3.0
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.3.0 | 未提供 | 2026-10-11 | 未提供 | 3.02 MB (3,166,703 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/TwitchUnblock-1.3.0.ipa) |

**版本說明：** TwitchUnblock 1.3.0

### 47. Twitch

- **開發者：** dvntms/zeroxdeadbeef/canpng/IPA Vault
- **Bundle ID：** `tv.twitch`
- **副標題：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6
- **主題色：** `#9146FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Twitch-Tweach-TC-Icons/Twitch-AppStore-1024x1024.png
- **功能／描述：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6
- **來源內版本數：** 1
- **目前列出的版本：** 31.4
- **最新列出的發布日期：** 2026-09-29

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 31.4 | 未提供 | 2026-09-29 | 未提供 | 189.46 MB (198,667,923 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Twitch-31.4-Tweach-TC.ipa) |

**版本說明：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6

### 48. Twitch (Glass)

- **開發者：** dvntms/zeroxdeadbeef/canpng/IPA Vault
- **Bundle ID：** `tv.twitch.glass`
- **副標題：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6 (Glass)
- **主題色：** `#9146FF`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Twitch-Tweach-TC-Icons/Twitch-AppStore-1024x1024.png
- **功能／描述：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6 (Glass)
- **來源內版本數：** 1
- **目前列出的版本：** 31.4
- **最新列出的發布日期：** 2026-09-29

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 31.4 | 未提供 | 2026-09-29 | 未提供 | 189.46 MB (198,667,925 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Twitch-31.4-Tweach-TC-Glass.ipa) |

**版本說明：** Twitch 31.4 with Tweach 2.4.1 + Twitch Control 0.0.6 (Glass)

### 49. Twitter NFB

- **開發者：** orionblur & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.atebits.Tweetie2.twitter`
- **副標題：** Twitter 12.33 with NFB 7.1.1
- **主題色：** `#1DA1F2`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Twitter-12.14-Icons/Twitter-AppStore-1024x1024.png
- **功能／描述：** Twitter 12.33 with NFB 7.1.1
- **來源內版本數：** 1
- **目前列出的版本：** 12.33
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.33 | 未提供 | 2026-10-11 | 未提供 | 245.02 MB (256,917,945 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Twitter-12.33-NFB.ipa) |

**版本說明：** Twitter 12.33 with NFB 7.1.1

### 50. Twitter NFB + TWI

- **開發者：** orionblur & dens0r & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.atebits.Tweetie2.twittertwi`
- **副標題：** Twitter 12.33 with NFB 7.1.1 + TWIGalaxy 1.14
- **主題色：** `#1DA1F2`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Twitter-12.14-Icons/Twitter-AppStore-1024x1024.png
- **功能／描述：** Twitter 12.33 with NFB 7.1.1 + TWIGalaxy 1.14
- **來源內版本數：** 1
- **目前列出的版本：** 12.33
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.33 | 未提供 | 2026-10-11 | 未提供 | 245.57 MB (257,500,199 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Twitter-12.33-NFB-TWI.ipa) |

**版本說明：** Twitter 12.33 with NFB 7.1.1 + TWIGalaxy 1.14

### 51. X NFB

- **開發者：** orionblur & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.atebits.Tweetie2`
- **副標題：** X 12.33 with NFB 7.1.1
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/X-Icons/X-AppStore-1024x1024.png
- **功能／描述：** X 12.33 with NFB 7.1.1
- **來源內版本數：** 1
- **目前列出的版本：** 12.33
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.33 | 未提供 | 2026-10-11 | 未提供 | 248.22 MB (260,275,746 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/X-12.33-NFB.ipa) |

**版本說明：** X 12.33 with NFB 7.1.1

### 52. X NFB + TWI

- **開發者：** orionblur & dens0r & IPA Vault & lucaspedrosa
- **Bundle ID：** `com.atebits.Tweetie2.twi`
- **副標題：** X 12.33 with NFB 7.1.1 + TWIGalaxy 1.14
- **主題色：** `#000000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/X-Icons/X-AppStore-1024x1024.png
- **功能／描述：** X 12.33 with NFB 7.1.1 + TWIGalaxy 1.14
- **來源內版本數：** 1
- **目前列出的版本：** 12.33
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 12.33 | 未提供 | 2026-10-11 | 未提供 | 248.77 MB (260,858,005 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/X-12.33-NFB-TWI.ipa) |

**版本說明：** X 12.33 with NFB 7.1.1 + TWIGalaxy 1.14

### 53. YouTube (YouMod 2.0.0) (iOS 16+)

- **開發者：** Tonwalter888 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.youmod.21-33-6`
- **副標題：** YouTube 21.33.6 with YouMod 2.0.0
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.33.6 with YouMod 2.0.0 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouTubeNativeShare, YouQuality, YouSlider, YTUHD, UncappedAVPlayer
- **來源內版本數：** 1
- **目前列出的版本：** 21.33.6
- **最新列出的發布日期：** 2026-09-29

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.33.6 | 未提供 | 2026-09-29 | 未提供 | 120.10 MB (125,938,270 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.33.6-YouMod.ipa) |

**版本說明：** YouTube 21.33.6 with YouMod 2.0.0 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouTubeNativeShare, YouQuality, YouSlider, YTUHD, UncappedAVPlayer

### 54. YouTube (YouMod 2.0.0)

- **開發者：** Tonwalter888 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.youmod`
- **副標題：** YouTube 21.41.5 with YouMod 2.0.0
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.41.5 with YouMod 2.0.0  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouTubeNativeShare, YouQuality, YouSlider, YTUHD, UncappedAVPlayer
- **來源內版本數：** 1
- **目前列出的版本：** 21.41.5
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 | 未提供 | 2026-10-11 | 未提供 | 135.04 MB (141,601,778 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.41.5-YouMod.ipa) |

**版本說明：** YouTube 21.41.5 with YouMod 2.0.0  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouTubeNativeShare, YouQuality, YouSlider, YTUHD, UncappedAVPlayer

### 55. YouTube (YTKACE 1.1.3) (iOS 16+)

- **開發者：** itzzace0 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.ytkace`
- **副標題：** YouTube 21.33.6 with YTKACE 1.1.3
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.33.6 with YTKACE 1.1.3 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YTHoldForSpeed, YouGroupSettings
- **來源內版本數：** 1
- **目前列出的版本：** 21.33.6
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.33.6 | 未提供 | 2026-10-11 | 未提供 | 128.44 MB (134,683,259 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.33.6-YTKACE.ipa) |

**版本說明：** YouTube 21.33.6 with YTKACE 1.1.3 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YTHoldForSpeed, YouGroupSettings

### 56. YouTube (YTKACE 1.1.3)

- **開發者：** itzzace0 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** YouTube 21.41.5 with YTKACE 1.1.3
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.41.5 with YTKACE 1.1.3  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YTHoldForSpeed, YouGroupSettings
- **來源內版本數：** 1
- **目前列出的版本：** 21.41.5
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 | 未提供 | 2026-10-11 | 未提供 | 136.64 MB (143,273,134 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.41.5-YTKACE.ipa) |

**版本說明：** YouTube 21.41.5 with YTKACE 1.1.3  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YTHoldForSpeed, YouGroupSettings

### 57. YouTube (YTPlus 6.0 b2) (iOS 15+)

- **開發者：** dvntms & itzzace0 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.ytplus.20-21-6`
- **副標題：** YouTube 20.21.6 with YTPlus 6.0 b2
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 20.21.6 with YTPlus 6.0 b2 (iOS 15+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD
- **來源內版本數：** 1
- **目前列出的版本：** 20.21.6
- **最新列出的發布日期：** 2026-10-04

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 20.21.6 | 未提供 | 2026-10-04 | 未提供 | 130.20 MB (136,521,979 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-20.21.6-YTPlus.ipa) |

**版本說明：** YouTube 20.21.6 with YTPlus 6.0 b2 (iOS 15+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD

### 58. YouTube (YTPlus 6.0 b2) (iOS 16+)

- **開發者：** dvntms & itzzace0 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.ytplus.21-33-6`
- **副標題：** YouTube 21.33.6 with YTPlus 6.0 b2
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.33.6 with YTPlus 6.0 b2 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD
- **來源內版本數：** 1
- **目前列出的版本：** 21.33.6
- **最新列出的發布日期：** 2026-10-04

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.33.6 | 未提供 | 2026-10-04 | 未提供 | 140.43 MB (147,251,627 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.33.6-YTPlus.ipa) |

**版本說明：** YouTube 21.33.6 with YTPlus 6.0 b2 (iOS 16+)  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD

### 59. YouTube (YTPlus 6.0 b2)

- **開發者：** dvntms & itzzace0 & IPA Vault
- **Bundle ID：** `com.google.ios.youtube.ytplus`
- **副標題：** YouTube 21.41.5 with YTPlus 6.0 b2
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Icons/YouTube-AppStore-1024x1024.png
- **功能／描述：** YouTube 21.41.5 with YTPlus 6.0 b2  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD
- **來源內版本數：** 1
- **目前列出的版本：** 21.41.5
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 | 未提供 | 2026-10-11 | 未提供 | 152.03 MB (159,411,487 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YouTube-21.41.5-YTPlus.ipa) |

**版本說明：** YouTube 21.41.5 with YTPlus 6.0 b2  Added Tweaks: YTABConfig, YTweaks, YouPIP, VolumeBoostYT, DontEatMyContent, ReturnYouTubeDislike, LowContrastMode, VideoOverlay, YouGetCaption, YouQuality, YouChooseQuality, YouSpeed, YouGroupSettings, YTUHD

### 60. YTMUltimate+

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.google.ios.youtubemusic.ytmultimateplus`
- **副標題：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Music-Icons/YouTube-Music-AppStore-1024x1024.png
- **功能／描述：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1  Added Tweaks: YTMABConfig, YouMusicPIP, VolumeBoostYT, ReturnYouTubeMusicDislike
- **來源內版本數：** 1
- **目前列出的版本：** 9.41.2
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.41.2 | 未提供 | 2026-10-11 | 未提供 | 106.04 MB (111,187,370 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YTMUltimatePlus-9.41.2.ipa) |

**版本說明：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1  Added Tweaks: YTMABConfig, YouMusicPIP, VolumeBoostYT, ReturnYouTubeMusicDislike

### 61. YTMUltimate+ (No PiP)

- **開發者：** dvntms & IPA Vault
- **Bundle ID：** `com.google.ios.youtubemusic`
- **副標題：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1 No PiP
- **主題色：** `#FF0000`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/YouTube-Music-Icons/YouTube-Music-AppStore-1024x1024.png
- **功能／描述：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1 (No PiP)  Added Tweaks: YTMABConfig, VolumeBoostYT, ReturnYouTubeMusicDislike
- **來源內版本數：** 1
- **目前列出的版本：** 9.41.2
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.41.2 | 未提供 | 2026-10-11 | 未提供 | 106.03 MB (111,177,185 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/YTMUltimatePlus-9.41.2-No-PiP.ipa) |

**版本說明：** YouTube Music 9.41.2 with YTMUltimate+ 2.4.1 (No PiP)  Added Tweaks: YTMABConfig, VolumeBoostYT, ReturnYouTubeMusicDislike

### 62. Spotify (Taurus)

- **開發者：** samj-exe & IPA Vault
- **Bundle ID：** `com.spotify.client.taurus`
- **副標題：** Spotify 9.1.78 with Taurus 0.50.1
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.78 with Taurus 0.50.1
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.78
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.78 | 未提供 | 2026-10-09 | 未提供 | 127.67 MB (133,874,753 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.78-Taurus.ipa) |

**版本說明：** Spotify 9.1.78 with Taurus 0.50.1

### 63. Spotify (Taurus) (No Plugins)

- **開發者：** samj-exe & IPA Vault
- **Bundle ID：** `com.spotify.client.taurus.noplugins`
- **副標題：** Spotify 9.1.78 with Taurus 0.50.1 (No Plugins)
- **主題色：** `#1DB954`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Spotify-Icons/Spotify-AppStore-1024x1024.png
- **功能／描述：** Spotify 9.1.78 with Taurus 0.50.1 (No Plugins)
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.78
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.78 | 未提供 | 2026-10-09 | 未提供 | 126.78 MB (132,933,434 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Spotify-9.1.78-Taurus-No-Plugins.ipa) |

**版本說明：** Spotify 9.1.78 with Taurus 0.50.1 (No Plugins)

## 三、AltGallery

- **來源 JSON：** https://raw.githubusercontent.com/bebound/AltGallery/master/all-apps.json
- **來源首頁：** https://github.com/bebound/AltGallery
- **App 數量：** 43

### 1. Aidoku

- **開發者：** Skitty
- **Bundle ID：** `app.aidoku.Aidoku`
- **副標題：** Free and open source manga reader for iOS and iPadOS
- **主題色：** `#FF375F`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Aidoku/icon.png
- **功能／描述：** A free and open source manga reading application for iOS and iPadOS.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Aidoku/images/library.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Aidoku/images/source.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Aidoku/images/reader.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.9
- **最新列出的發布日期：** 2026-09-03
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.9 | 未提供 | 2026-09-03 | 15.0 | 14.05 MB (14,731,108 bytes) | [下載](https://github.com/Aidoku/Aidoku/releases/download/v0.9/Aidoku.ipa) |

**版本說明：** - OCR dictionary support (iOS 18+): import Yomitan-compatible dictionaries in the app and look up words while reading. - Suwayomi built-in source: read and track from a Suwayomi instance, just like Komga and Kavita. - Auto scroll for webtoon reader: enable and…（版本說明已節錄）

### 2. AirCard-iOS

- **開發者：** Mak5er
- **Bundle ID：** `com.mak5er.aircard`
- **副標題：** Apple Wallet card skins, passcode themes and wallpapers
- **主題色：** `#5020E0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AirCard/icon.png
- **功能／描述：** Customize Apple Wallet card artwork, lock screen passcode dialers and PosterBoard wallpapers directly on device, without a jailbreak. Requires iOS 27 or newer, LocalDevVPN running in loopback mode, and Developer Mode pairing.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AirCard/images/wallet.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AirCard/images/pairing.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AirCard/images/wallpapers.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.3.2
- **最新列出的發布日期：** 2026-10-04
- **最低 iOS：** 27.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.3.2 | 未提供 | 2026-10-04 | 27.0 | 4.42 MB (4,638,147 bytes) | [下載](https://github.com/Mak5er/AirCard-iOS/releases/download/v1.3.2/AirCard-iOS.ipa) |

**版本說明：** ## What's Changed in v1.3.2 🚀  This update brings full feature parity with AirCard macOS v1.2.6, restores robust card discovery across all iOS versions, introduces automatic bank/network recognition with custom card nicknames, delivers an ultra-fast tunnel ca…（版本說明已節錄）

### 3. AniBaka

- **開發者：** AniBakaBaka
- **Bundle ID：** `ani.baka`
- **副標題：** 跨平台番剧聚合、媒体播放与弹幕客户端
- **主題色：** `#0077B6`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AniBaka/icon.png
- **功能／描述：** AniBaka 是一个基于 Flutter 的跨平台番剧聚合与媒体播放客户端，支持多番剧源、弹幕、字幕、离线缓存与本地媒体库，并提供动漫实时超分辨率画质增强。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AniBaka/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AniBaka/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AniBaka/images/player.png
- **來源內版本數：** 1
- **目前列出的版本：** 5.2.1（build 1007）
- **最新列出的發布日期：** 2026-10-07
- **最低 iOS：** 13.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 5.2.1 | 1007 | 2026-10-07 | 13.0 | 21.54 MB (22,588,259 bytes) | [下載](https://github.com/AniBakaBaka/AniBaka/releases/download/5.2.1%2B1007/baka-5.2.1%2B1007-ios-unsigned.ipa) |

**版本說明：** - 新增视频内片头、片尾区间选择，支持拖动起止位置、预览画面并保存到本机。 - 优化片头片尾管理面板，支持分别控制当前片源的跳过开关，并查看区间来源、调整标注及提交反馈。 - 修复标注时拖动、试看或切换后台可能覆盖观看进度、误记为已看完的问题。 - 修复部分云端历史无法正常续播的问题，完善片源重新匹配、集数与线路恢复，保留本机播放信息。 - 新增视频源更新提醒，支持启动及返回应用时检查更新，并提供批量更新、进度显示和失败重试。 - 完善规则版本管理，规则库连接失败时保留上次检查结果并显示提示。 - 新增 MuteF…（版本說明已節錄）

### 4. AnimeFlow

- **開發者：** openAnimeFlow
- **Bundle ID：** `com.ligg.anime_flow`
- **副標題：** 跨平台动漫视频播放器，支持多数据源、实时 4K 超分辨率与弹幕
- **主題色：** `#124EB3`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AnimeFlow/icon.png
- **功能／描述：** AnimeFlow 是一个跨平台动漫视频播放应用，支持 Android、iOS、Windows、macOS 与 Linux。内置多数据源与自定义 XPath 爬虫配置，支持基于 Anime4K 的实时视频 4K 超分辨率，对接 Bangumi 同步收藏与追番数据，并支持多平台弹幕源与丰富的弹幕设置。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AnimeFlow/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AnimeFlow/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/AnimeFlow/images/comment.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.6.3
- **最新列出的發布日期：** 2026-10-12
- **最低 iOS：** 13.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.6.3 | 未提供 | 2026-10-12 | 13.0 | 28.07 MB (29,429,482 bytes) | [下載](https://github.com/openAnimeFlow/AnimeFlow/releases/download/v2.6.3/AnimeFlow-ios-2.6.3.ipa) |

**版本說明：** ### 🔄 更新内容  ## 2.6.3 更新  ## 新增  - 新增播放器迷你进度条(可在设置页面关闭) #101 - 新增图片缓存清理 - 番剧角色页面补全声优信息 #105 - 安卓端支持自定义视频下载路径 - 用户收藏页面支持已最新观看记录排序 #100  ## 优化   - 优化图片加载速度(在通用设置页面手动点击一次恢复ECH默认值) - 账户设置页面ID、账号支持复制 - 优化多处ui细节 - 优化新番时间表排序功能 #108 - 优化播放资源权重排序 #98  ## 修复  - 修复更新信息页面…（版本說明已節錄）

### 5. Animeko

- **開發者：** open-ani
- **Bundle ID：** `org.animeko.animeko`
- **副標題：** 一站式弹幕追番平台
- **主題色：** `#0050A0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Animeko/icon.png
- **功能／描述：** Animeko 是一个 Kotlin/Compose Multiplatform 打造的一站式弹幕追番平台，集找番、追番、看番于一体，支持 Bangumi 云同步观看记录、多视频数据源聚合（含 BitTorrent、Jellyfin、Emby）、离线缓存与弹幕云过滤。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Animeko/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Animeko/images/subject-details.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Animeko/images/episode.png
- **來源內版本數：** 1
- **目前列出的版本：** 6.3.0
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 6.3.0 | 未提供 | 2026-10-13 | 14.0 | 44.33 MB (46,485,035 bytes) | [下載](https://github.com/open-ani/animeko/releases/download/v6.3.0/ani-6.3.0.ipa) |

**版本說明：** - 数据源选择支持手动查找模式，支持直接浏览数据源剧集并记住选择，方便后续切集，同时优化 BT 资源搜索、筛选和列表展示 - 新增热度排行页，可浏览完整的 Bangumi 动画热度榜 - 大幅提升分季拆分放送的动画的选集准确性 - Android 和 iOS 支持系统画中画播放 (#3466 by @GeneralK1ng) - 优化播放器截图体验，新增角落预览，支持查看、复制与系统分享 - 观看进度支持离线处理, 上线后自动同步 - 剧集列表按正片、特别篇等类型分组，上一集、下一集与自动连播只在同类型剧集之间切换…（版本說明已節錄）

### 6. Apollo for Reddit - GLASS

- **開發者：** Christian Selig (& Apollo-Reborn contributors)
- **Bundle ID：** `com.christianselig.Apollo`
- **副標題：** Apollo-Reborn build with Liquid Glass patch
- **主題色：** `#6050F0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Apollo-Reborn/icon.png
- **功能／描述：** Apollo-Reborn is the community-maintained Apollo sideload build powered by the Apollo-Reborn tweak.  It restores custom API support, media fixes, uploads, inline media, translation, saved categories, Home Screen and Lock Screen widgets, Liquid Glass support on iOS 26+, and the rest of the project’s ongoing fixes and enhancements.  These sources are intended for AltStore Classic, SideStore, and Feather. Apollo-Reborn …（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Apollo-Reborn/images/avatar-profile.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Apollo-Reborn/images/settings.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Apollo-Reborn/images/custom.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Apollo-Reborn/images/recents.jpg（另有 1 張）
- **來源內版本數：** 1
- **目前列出的版本：** 3.9.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 3.9.0 | 未提供 | 2026-10-09 | 未提供 | 122.60 MB (128,560,322 bytes) | [下載](https://github.com/Apollo-Reborn/Apollo-Reborn/releases/download/v1.15.11_3.9.0/Apollo-Reborn-3.9.0-GLASS.ipa) |

**版本說明：** ### Features  - Add an **in-app update prompt**: from the next release on, Apollo Reborn checks for updates once a day and, when one is out, lets you send it to AltStore, SideStore, Feather, or FlareStore or download the IPA, with the release notes a tap away …（版本說明已節錄）

### 7. ARMSX2

- **開發者：** ARMSX2
- **Bundle ID：** `com.armsx2.ios`
- **副標題：** PlayStation 2 emulator for ARM64
- **主題色：** `#3CAEFF`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ARMSX2/icon.png
- **功能／描述：** A free and open-source PlayStation 2 (PS2) emulator based on PCSX2, with native ARM64 JIT recompilers. Play PS2 games on your phone, PC, or gaming handheld.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ARMSX2/images/game.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ARMSX2/images/list.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ARMSX2/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** nightly-20261011
- **最新列出的發布日期：** 2026-10-11
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| nightly-20261011 | 未提供 | 2026-10-11 | 17.0 | 38.09 MB (39,938,405 bytes) | [下載](https://github.com/ARMSX2/ARMSX2/releases/download/nightly-20261011/ARMSX2-nightly-20261011-0076b5c389-iOS-arm64.ipa) |

**版本說明：** Automated nightly build for community testing (unsigned).  Every download is named `ARMSX2-nightly-DATE-COMMIT-PLATFORM`, so builds from different nights stay distinguishable after you have downloaded them.  - macOS arm64: macOS-arm64.tar.xz - Linux arm64: Lin…（版本說明已節錄）

### 8. Doer

- **開發者：** moliango
- **Bundle ID：** `com.naine.doer`
- **副標題：** A native iOS client for Linux.do
- **主題色：** `#4080E0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Doer/icon.png
- **功能／描述：** A native iOS client for Linux.do — UIKit + Swift, no SwiftUI in the main app.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Doer/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Doer/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Doer/images/me.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.8.6
- **最新列出的發布日期：** 2026-10-10
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.8.6 | 未提供 | 2026-10-10 | 15.0 | 26.79 MB (28,095,758 bytes) | [下載](https://github.com/moliango/doer/releases/download/v1.8.6/doer-unsigned.ipa) |

**版本說明：** **Full Changelog**: https://github.com/moliango/doer/compare/v1.8.5.3...v1.8.6

### 9. DolphiniOS

- **開發者：** OatmealDome
- **Bundle ID：** `me.oatmealdome.DolphiniOS-njb-patreon-beta`
- **副標題：** GameCube and Wii emulator for iOS/iPadOS
- **主題色：** `#E0B030`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DolphiniOS/icon.png
- **功能／描述：** Dolphin for iOS, reborn. A GameCube and Wii emulator for iPhone and iPad.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DolphiniOS/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DolphiniOS/images/game.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DolphiniOS/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 5.0.0b6
- **最新列出的發布日期：** 2026-06-20
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 5.0.0b6 | 未提供 | 2026-06-20 | 14.0 | 17.13 MB (17,963,367 bytes) | [下載](https://github.com/OatmealDome/dolphin-ios/releases/download/v5.0.0b6/Non-Jailbroken.ipa) |

**版本說明：** * Fixed JIT support on A13/A14/M1 devices running iOS 27 beta. (@CelloSerenity) * Fixed wrong app version number introduced in 5.0.0b5. (@CelloSerenity)  The next update will be sometime after the next official Dolphin release. It will include a core update.  …（版本說明已節錄）

### 10. DukeX

- **開發者：** Manic EMU Development Team
- **Bundle ID：** `com.mafty.dukex`
- **副標題：** Original Xbox emulation for iOS
- **主題色：** `#8FCA39`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DukeX/icon.png
- **功能／描述：** DukeX is an experimental iOS-focused frontend for xemu. It embeds the xemu core in a native Swift shell and presents the Vulkan renderer through MoltenVK and native Metal.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DukeX/images/library.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DukeX/images/activity.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/DukeX/images/game.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.0.2
- **最新列出的發布日期：** 2026-06-30
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.0.2 | 未提供 | 2026-06-30 | 16.0 | 19.40 MB (20,345,841 bytes) | [下載](https://github.com/MaftyManicEMU/DukeX/releases/download/v1.0.2/DukeX.v1.0.2.ipa) |

**版本說明：** # DukeX v1.0.2 - Expanding the Xbox Experience  DukeX v1.0.2 is our biggest step yet toward preserving the full original Xbox experience, not just the games. This release introduces the first native macOS build, expands XB.Live integration, and brings richer c…（版本說明已節錄）

### 11. EhPanda

- **開發者：** EhPanda-Team
- **Bundle ID：** `app.ehpanda`
- **副標題：** An unofficial E-Hentai App for iOS built with SwiftUI & TCA
- **主題色：** `#0f766e`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/EhPanda/icon.png
- **功能／描述：** EhPanda is an unofficial E-Hentai app for iOS & iPadOS built with SwiftUI & TCA. It supports almost all E-Hentai gallery categories, gallery browsing with filters, gallery details with tags & related galleries, posting / editing / replying to comments, H@H archiving, torrent listing, E-Hentai settings, and SNI-bypass (domain fronting) for restricted networks. Localization is built in and the app icon and accent color…（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/EhPanda/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/EhPanda/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/EhPanda/images/comment.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.8.1
- **最新列出的發布日期：** 2026-07-20
- **最低 iOS：** 26.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.8.1 | 未提供 | 2026-07-20 | 26.0 | 7.01 MB (7,352,364 bytes) | [下載](https://github.com/EhPanda-Team/EhPanda/releases/download/v2.8.1/EhPanda.ipa) |

**版本說明：** 1. feat: Adapt to the new Liquid Glass design. 3. fix: Gesture issue in the reading page. 4. fix: Crash issue in eh setting page. 5. fix: A minor issue in search page.

### 12. Fathom

- **開發者：** Leviidev
- **Bundle ID：** `app.fathom.emulator`
- **副標題：** x86-64 PC emulator for iOS
- **主題色：** `#68D8D8`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Fathom/icon.png
- **功能／描述：** An x86-64 PC emulator for iOS. Fathom runs x86-64 Linux programs on an iPhone or iPad by translating them to ARM64 as they execute, using FEXCore - the dynamic recompiler behind FEX-Emu - with a native SwiftUI front end.  Import a statically linked x86-64 Linux executable, open it, press Run. Fathom maps it into a guest address space, hands its instructions to FEXCore's JIT, answers its Linux syscalls, and shows you …（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Fathom/images/library.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Fathom/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.0.0
- **最新列出的發布日期：** 2026-09-14
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.0.0 | 未提供 | 2026-09-14 | 18.0 | 1.12 MB (1,175,175 bytes) | [下載](https://github.com/Leviidev/Fathom/releases/download/v1.0.0/Fathom.ipa) |

**版本說明：** An x86-64 PC emulator for iOS, running guest code on FEXCore.  2048 and tic tac toe both run. Add them from the Library tab and play with the on-screen arrow keys.  **Downloads** - `Fathom.ipa` - the app, unsigned, for sideloading. Needs StikDebug attached for…（版本說明已節錄）

### 13. Husk

- **開發者：** Leviidev
- **Bundle ID：** `com.husk.app`
- **副標題：** Android app launcher for iOS
- **主題色：** `#5949E5`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Husk/icon.png
- **功能／描述：** Run Android apps on iOS: drop in an APK, tap it, and the Android app opens full-screen on a QEMU guest with hardware-accelerated display and audio. Needs JIT plus a debugger attached at runtime, so it requires a sideloading setup that can provide get-task-allow rather than a plain re-sign.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Husk/images/main.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Husk/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.0
- **最新列出的發布日期：** 2026-10-11
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.0 | 未提供 | 2026-10-11 | 16.4 | 105.78 MB (110,921,859 bytes) | [下載](https://github.com/Leviidev/Husk/releases/download/2.0/Husk.ipa) |

**版本說明：** ## Welcome to Husk 2.0. I’ve been working hard over the past few days, and I’m glad to say, Husk 2.0 is out! You’ll enjoy it, a lot. ## What’s new? - Christmas Decoration - In-app help feature - Window manager - New UI - Removed downloads tab ## New App Suppor…（版本說明已節錄）

### 14. Iridium

- **開發者：** intraducine
- **Bundle ID：** `software.iridium`
- **副標題：** Experimental Windows-game runtime for iPhone and iPad
- **主題色：** `#1C1C1E`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Iridium/icon.png
- **功能／描述：** An experimental iPhone and iPad Windows-game runtime, with a native game library and touch, keyboard, mouse, and controller integration. Requires iOS 18+, JIT, and your own game files; compatibility varies by game and device.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Iridium/images/all-games.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Iridium/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.2.0
- **最新列出的發布日期：** 2026-10-04
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.2.0 | 未提供 | 2026-10-04 | 18.0 | 381.39 MB (399,916,792 bytes) | [下載](https://github.com/intraducine/iridium/releases/download/v0.2.0/Iridium-unsigned.ipa) |

**版本說明：** # Iridium 0.2.0  Download your Steam games directly in Iridium, manage repairs and updates, and try the updated Windows runtime. Game support remains experimental.  ## Download  **[Download Iridium (.ipa)](https://github.com/intraducine/iridium/releases/downlo…（版本說明已節錄）

### 15. iTorrent

- **開發者：** XITRIX
- **Bundle ID：** `com.xitrix.iTorrent2`
- **副標題：** Torrent client for iOS
- **主題色：** `#F19E69`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/iTorrent/icon.png
- **功能／描述：** iTorrent is an ordinary torrent client for iOS with Files app support and much more.  What can this app do:  • Download in the background • Live Activity and Dynamic Island progress bar • Downloading on external drives • Sequential download (use VLC to watch films while loading) • Add torrent files from Share menu (Safari and other apps) • Add magnet links directly from Safari • Store files in Files app • File sharin…（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/iTorrent/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/iTorrent/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/iTorrent/images/player.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.2.0-1
- **最新列出的發布日期：** 2026-07-19
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.2.0-1 | 未提供 | 2026-07-19 | 16.0 | 23.16 MB (24,288,935 bytes) | [下載](https://github.com/XITRIX/iTorrent/releases/download/v2.2.0-1/iTorrent.ipa) |

**版本說明：** ## What's new: * Meet the new built-in VLC player. Play compatible video and audio files directly in iTorrent, even while they are still downloading. * Enjoy Picture in Picture, playback speeds from 0.5x to 2x, audio and subtitle track selection, precise seeki…（版本說明已節錄）

### 16. Kazumi

- **開發者：** Predidit
- **Bundle ID：** `com.example.kazumi`
- **副標題：** 基于自定义规则的番剧采集APP，支持流媒体在线观看，支持弹幕，支持实时超分辨率。
- **主題色：** `#4CAF50`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kazumi/icon.png
- **功能／描述：** 使用 Flutter 开发的基于自定义规则的番剧采集与在线观看程序。使用最多五行基于 Xpath 语法的选择器构建自己的规则，支持规则导入与规则分享，支持基于 Anime4K 的实时超分辨率。  其他特性：番剧目录与搜索、分集播放、番剧弹幕、追番列表、历史记录、倍速播放、多视频源支持、配色方案等。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kazumi/images/home.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kazumi/images/timetable.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kazumi/images/details.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kazumi/images/selection.jpg（另有 2 張）
- **來源內版本數：** 1
- **目前列出的版本：** 2.3.8
- **最新列出的發布日期：** 2026-10-07
- **最低 iOS：** 13.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.3.8 | 未提供 | 2026-10-07 | 13.0 | 29.05 MB (30,463,104 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.8/Kazumi_ios_2.3.8_no_sign.ipa) |

**版本說明：** - 优化截图交互 (#2599) (@Predidit) - 统一应用内下拉菜单样式 (@Predidit) - 修复大字体下番剧详情页追番按钮与其他按钮重叠而无法点击的问题 (#2622) (@Predidit) - 修复宽屏设置页重复点击已选中分类时二级页面重复嵌套的问题 (#2607) (@Predidit) - 修复鼠标悬停时播放器控制栏动画反复重启的问题 (@Predidit) - 修复分集评论标题栏显示多余副标题的问题 (@Predidit) - 其他UI改进 (@Predidit)

### 17. KMusic

- **開發者：** Mac-XK
- **Bundle ID：** `com.macxk.KMusic`
- **副標題：** 基于 SwiftUI 的多源音乐聚合播放器
- **主題色：** `#F03050`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/KMusic/icon.png
- **功能／描述：** 基于 SwiftUI 开发的多源音乐聚合播放器，支持 iOS/macOS。内置酷我、酷狗、QQ 音乐、网易云、咪咕等多平台音源，支持 LRC 歌词同步、全局搜索、后台播放与深色主题，并可通过 JS 脚本导入自定义音源。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/KMusic/images/recommendation.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/KMusic/images/playlist.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/KMusic/images/play.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.3.0
- **最新列出的發布日期：** 2026-03-12
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.3.0 | 未提供 | 2026-03-12 | 14.0 | 3.66 MB (3,836,900 bytes) | [下載](https://github.com/Mac-XK/KMusic/releases/download/%E6%AD%8C%E4%B8%80%E5%88%802.3.0/_2.3.0_22.2.ipa) |

**版本說明：** - 优化增加各种问题

### 18. Kumone

- **開發者：** missuo
- **Bundle ID：** `sb.moe.kumone`
- **副標題：** 原生 NetEase Cloud Music iOS 客户端（雲の音）
- **主題色：** `#F0D060`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kumone/icon.png
- **功能／描述：** Kumone（雲の音）— native NetEase Cloud Music client for iOS. Talks directly to NetEase's real API with no third-party server: QR-code login, gray-track unblocking, synced lyrics with translation, immersive artwork-tinted now-playing, and playlist management.  Supports English and Simplified Chinese localization.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kumone/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kumone/images/search.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Kumone/images/featured.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.3.20
- **最新列出的發布日期：** 2026-10-03
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.3.20 | 未提供 | 2026-10-03 | 16.0 | 7.20 MB (7,546,632 bytes) | [下載](https://github.com/missuo/kumone/releases/download/v0.3.20/Kumone-iOS-0.3.20.ipa) |

**版本說明：** ### Added  - **macOS** (experimental): AutoMix — an Apple-Music-style continuous-playback mode with beat-matched transitions, optional stem separation, loudness compensation and an output-device picker, on a new dual-deck AVAudioEngine backend. Off by default;…（版本說明已節錄）

### 19. LiveContainer+SideStore

- **開發者：** LiveContainer Team
- **Bundle ID：** `com.kdt.livecontainer`
- **副標題：** Run iOS apps without actually installing them!
- **主題色：** `#0784FC`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/master/apps/LiveContainer+SideStore/icon.png
- **功能／描述：** An app launcher that runs iOS apps without actually installing them. This build of LiveContainer comes with a built-in SideStore for refreshing your apps.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/master/apps/LiveContainer+SideStore/images/apps.png · https://raw.githubusercontent.com/bebound/AltGallery/master/apps/LiveContainer+SideStore/images/sources.png · https://raw.githubusercontent.com/bebound/AltGallery/master/apps/LiveContainer+SideStore/images/settings.png
- **來源內版本數：** 2
- **目前列出的版本：** nightly
- **最新列出的發布日期：** 2026-09-18
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| nightly | 未提供 | 2026-09-18 | 15.0 | 34.26 MB (35,926,202 bytes) | [下載](https://github.com/LiveContainer/LiveContainer/releases/download/nightly/LiveContainer%2BSideStore.ipa) |
| 3.8.0 | 未提供 | 2026-07-17 | 15.0 | 33.76 MB (35,403,538 bytes) | [下載](https://github.com/LiveContainer/LiveContainer/releases/download/3.8.0/LiveContainer%2BSideStore.ipa) |

**版本說明：** **Commit:** [4dbe0f9a626de801184a42c0be8d2cb105058e3d](https://github.com/LiveContainer/LiveContainer/commit/4dbe0f9a626de801184a42c0be8d2cb105058e3d) **Message:** Update litehook: add arm64e_x1 dsc suffix  This is a nightly release [created automatically with…（版本說明已節錄）

### 20. Madeira

- **開發者：** Will Faust
- **Bundle ID：** `com.willfaust.madeora`
- **副標題：** Windows PC games on your iPhone
- **主題色：** `#7B68EE`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Madeira/icon.png
- **功能／描述：** Madeira runs unmodified x86-64 Windows PC games inside a single jailed iOS app: FEX-Emu translates the game's x86 code to ARM64 as it runs, Wine 11.4 built for ARM64EC provides Windows itself, and DXMT plus Madeira's own Direct3D 12 runtime draw Direct3D 9, 10, 11 and 12 through Metal. Games come with a library, Steam sign-in and installs, controller and touch controls, and keyboard, mouse and trackpad input. Require…（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Madeira/images/introduction.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Madeira/images/main.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Madeira/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.1.3
- **最新列出的發布日期：** 2026-10-03
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.1.3 | 未提供 | 2026-10-03 | 17.0 | 138.81 MB (145,554,426 bytes) | [下載](https://github.com/willfaust/Madeira/releases/download/v0.1.3/Madeira-0.1.3.ipa) |

**版本說明：** ### New - **In-app JIT: no StikDebug needed.** Madeira can enable JIT by itself through a bundled helper built on StikJIT. On iOS 27 it pairs with the iPhone it runs on: in Settings › Privacy & Security › Developer Mode, tap **Pair with Madeira** and enter the…（版本說明已節錄）

### 21. Mangayomi

- **開發者：** Moustapha Kodjo Amadou
- **Bundle ID：** `com.kodjodevf.mangayomi`
- **副標題：** Read manga, novels, and watch anime
- **主題色：** `#EF4444`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Mangayomi/icon.png
- **功能／描述：** Mangayomi is an open-source Flutter app for reading manga, novels, and watching anime across multiple platforms.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Mangayomi/images/screenshot1.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Mangayomi/images/screenshot2.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Mangayomi/images/screenshot3.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 0.9.9
- **最新列出的發布日期：** 2026-10-12

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.9.9 | 未提供 | 2026-10-12 | 未提供 | 109.29 MB (114,603,425 bytes) | [下載](https://github.com/kodjodevf/mangayomi/releases/download/v0.9.9/Mangayomi-v0.9.9-ios.ipa) |

**版本說明：** ## What's Changed * fix(extension): enable mobile code copy by @mrandhawa14 in https://github.com/kodjodevf/mangayomi/pull/1039 * fix(reader): restore double-tap zoom toggle by @mrandhawa14 in https://github.com/kodjodevf/mangayomi/pull/1037 * feat(player): ad…（版本說明已節錄）

### 22. ManicEMU

- **開發者：** Manic EMU Development Team
- **Bundle ID：** `com.aoshuang.manicemu`
- **副標題：** All-in-one retro game emulator for iOS
- **主題色：** `#F02040`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ManicEMU/icon.png
- **功能／描述：** All-in-one retro game emulator for iOS, bringing console, arcade, computer, and mobile Java systems into one clean app with saves, cheats, custom skins, RetroAchievements, and more.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ManicEMU/images/library.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ManicEMU/images/landscape.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ManicEMU/images/achievements.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 2.0.1
- **最新列出的發布日期：** 2026-09-18
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.0.1 | 未提供 | 2026-09-18 | 15.0 | 275.16 MB (288,525,117 bytes) | [下載](https://github.com/Manic-EMU/ManicEMU/releases/download/v2.0.1/ManicEMU.v2.0.1.SideloadJIT.ipa) |

**版本說明：** - Added WonderSwan support - Added NAOMI, Atomiswave, and System SP arcade support - Added Flash support   · Skin button binding   · Hardware keyboard input   · Software keyboard input   · Touch input - Built-in, self-contained JIT — no external debugger requi…（版本說明已節錄）

### 23. MiniWatts

- **開發者：** ResistanceTo
- **Bundle ID：** `org.zhaohe.MiniWatts`
- **副標題：** Battery, charging and thermal instrument
- **主題色：** `#30E0F0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MiniWatts/icon.png
- **功能／描述：** An iPhone battery and charging monitor built on Apple's private APIs: the charger's real watts, how much of that reaches the cell, where the rest goes as heat, and every temperature sensor in the phone. No network code — nothing it reads leaves your phone.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MiniWatts/images/power.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MiniWatts/images/thermal.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MiniWatts/images/adapter.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MiniWatts/images/history.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 1.5.1
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.5.1 | 未提供 | 2026-10-13 | 17.0 | 3.15 MB (3,305,290 bytes) | [下載](https://github.com/ResistanceTo/MiniWatts/releases/download/v1.5.1/MiniWatts-unsigned.ipa) |

**版本說明：** Unsigned build — sign it with your own Apple ID before installing. https://github.com/ResistanceTo/MiniWatts#install  ## 改进  - **输入读数不完整时，不再当作输入功率显示。** 在 iPad Pro 和 iPhone 18 Pro Max 上，输入传感器只测到了一部分功率（比如实际 43.5 W 只显示 21.8 W）。现在当进入电芯的功率比输入读数还大时，表盘改为显示"进入电池"的功率，不…（版本說明已節錄）

### 24. MoviePilotLite

- **開發者：** singleton-altman
- **Bundle ID：** `com.altman.moviepilot`
- **副標題：** MoviePilot 移动端，基于 Flutter 实现
- **主題色：** `#8050F0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MoviePilotLite/icon.png
- **功能／描述：** 基于 MoviePilot 的 Flutter 跨端客户端，对接 MoviePilot v2 API，在手机上完成订阅、搜索、下载、整理与系统运维等常用操作。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MoviePilotLite/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MoviePilotLite/images/recommend.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/MoviePilotLite/images/explorer.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.2.5
- **最新列出的發布日期：** 2026-10-09
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.2.5 | 未提供 | 2026-10-09 | 15.0 | 35.33 MB (37,045,206 bytes) | [下載](https://github.com/singleton-altman/MoviePilotLite/releases/download/release-v1.2.5-2026-10-09/ios-v1.2.5-2026-10-09.ipa) |

**版本說明：** MoviePilot Release  - Version: 1.2.5 - Build Date: 2026-10-09 - Android: Signed universal APK - Android: Signed arm64-v8a APK - iOS: Unsigned IPA  iOS 安装说明： - IPA 为未签名包 - 请使用自己的 Apple Developer 账号通过 AltStore、Sideloadly 或 Xcode 进行签名安装   ## What's Changed * fix(…（版本說明已節錄）

### 25. Musly

- **開發者：** dddevid
- **Bundle ID：** `com.dddevid.musly`
- **副標題：** Free Navidrome client & Subsonic music player
- **主題色：** `#FA243C`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Musly/icon.png
- **功能／描述：** Musly is a free Navidrome client and Subsonic music player with an Apple Music-inspired interface. Stream your self-hosted library from Navidrome, Subsonic, or Airsonic servers on iOS, Android, desktop, and more.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Musly/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Musly/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Musly/images/player.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.0.2
- **最新列出的發布日期：** 2026-08-26
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.0.2 | 未提供 | 2026-08-26 | 15.0 | 13.28 MB (13,928,367 bytes) | [下載](https://github.com/dddevid/Musly/releases/download/v2.0.2/musly-ios.ipa) |

**版本說明：** ## 🎉 Musly v2.0.2  ### 📦 Downloads  **Android:** - `app-release.apk` (universal APK for all devices)  **iOS:** - `musly-ios.ipa` (sideload with AltStore, Sideloadly, or similar — not signed)  **Windows:** - `musly-setup.exe` (setup installer, run to install …（版本說明已節錄）

### 26. NeoStation iOS

- **開發者：** TarbleFR
- **Bundle ID：** `com.neogamelab.neostation`
- **副標題：** Emulation frontend for iPhone and iPad
- **主題色：** `#01E989`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/NeoStation/icon.png
- **功能／描述：** An independently maintained iOS/iPadOS fork of NeoStation, with embedded Dolphin, ARMSX2, RPCS3, Dusklight and KartPad runtimes alongside RetroArch and MeloNX integration, JIT workflows and mobile-friendly game and session management.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/NeoStation/images/intro.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/NeoStation/images/library.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/NeoStation/images/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.0.7
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.0.7 | 未提供 | 2026-10-13 | 18.0 | 201.10 MB (210,867,021 bytes) | [下載](https://github.com/TarbleFR/neostation-ios/releases/download/0.0.7/NeoStation-0.0.7.ipa) |

**版本說明：** # NeoStation iOS 0.0.7 🎮 *Build 455 · What's new since v0.0.6*  - **Nintendo 3DS moves to Azahar 2127.0-alpha1**, with **Fast Interpreter** mode and improved BIOS and NAND imports. **Encrypted game ROMs remain unsupported.** - **AirPlay on Apple TV:** fixed h…（版本說明已節錄）

### 27. Novella

- **開發者：** CELIA
- **Bundle ID：** `sh.celia.novella`
- **副標題：** 轻书架第三方客户端
- **主題色：** `#2E2E2E`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Novella/icon.png
- **功能／描述：** 使用 React Native 构建的轻书架第三方客户端，面向 iOS、iPadOS。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Novella/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Novella/images/shelf.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Novella/images/detail.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.5.0
- **最新列出的發布日期：** 2026-09-23
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.5.0 | 未提供 | 2026-09-23 | 16.4 | 24.84 MB (26,047,504 bytes) | [下載](https://github.com/celia-sh/Novella/releases/download/v2.5.0/Novella-2.5.0-release.ipa) |

**版本說明：** <img width="800" alt="Banner" src="https://github.com/user-attachments/assets/4deb46d9-8b91-4b8a-a4f4-5d59f9190628" />  ## **What's Changed 🧐**  本次更新主要完善了 **书架管理**，并完成了 **组件迁移**。 **仅支持 iOS / iPadOS**。  ### **⚡️ 内容概要**  * **API**   跟进新的接口。   截止发版前 **详情页 / 书架 /…（版本說明已節錄）

### 28. Opaline

- **開發者：** verback2308
- **Bundle ID：** `com.verback.YTLite`
- **副標題：** YouTube client for iOS 12+
- **主題色：** `#FF0000`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Opaline/icon.png
- **功能／描述：** A lightweight YouTube client with SponsorBlock, Return YouTube Dislike, and up to 1080p playback. No ads, no tracking, no dependencies.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Opaline/images/home.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Opaline/images/player.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Opaline/images/channel.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 1.12.0
- **最新列出的發布日期：** 2026-09-10
- **最低 iOS：** 12.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.12.0 | 未提供 | 2026-09-10 | 12.0 | 6.38 MB (6,685,919 bytes) | [下載](https://github.com/verback2308/Opaline/releases/download/1.12.0/Opaline_1.12.0.ipa) |

**版本說明：** **New**  - Hold anywhere on the video to seek ([#116](https://github.com/verback2308/Opaline/issues/116)). Press and hold on the picture, then drag sideways. The seek bar follows your finger and the video jumps where you let go, so you no longer have to hit th…（版本說明已節錄）

### 29. Orchard

- **開發者：** MakrSas
- **Bundle ID：** `com.makr.orchard`
- **副標題：** Apple Silicon macOS Ventura running inside an iPhone app
- **主題色：** `#F0C060`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Orchard/icon.png
- **功能／描述：** Boots a real arm64 macOS Ventura guest on iPhone through Apple's own chain (AVPBooter, iBoot and XNU) on QEMU's apple-vm machine, with the GPU drawn through Metal by reims-vgpu. Requires JIT, a signing tool that adds the increased memory limit, and a macOS VM you make yourself. It is slow — light scenes reach 30–40 fps at best.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Orchard/images/main.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.2
- **最新列出的發布日期：** 2026-09-25
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.2 | 未提供 | 2026-09-25 | 16.0 | 17.62 MB (18,477,287 bytes) | [下載](https://github.com/MakrSas/orchard-ios/releases/download/v0.2/Orchard.ipa) |

**版本說明：** Orchard for iPhone 0.2: a faster emulator and a faster Metal path, plus a fix for guests that end up in Recovery.  Setup and settings: [README](https://github.com/MakrSas/orchard-ios#readme).  ## Faster  On an iPhone 15 (A16), light scenes now reach 30–40 fram…（版本說明已節錄）

### 30. PiliPlus

- **開發者：** bggRGjQaUbCoE
- **Bundle ID：** `com.example.piliplus`
- **副標題：** 使用Flutter开发的BiliBili第三方客户端
- **主題色：** `#73b480`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PiliPlus/icon.png
- **功能／描述：** 使用Flutter开发的BiliBili第三方客户端
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PiliPlus/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PiliPlus/images/bangumi.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PiliPlus/images/dynamic.png
- **來源內版本數：** 1
- **目前列出的版本：** 2.1.6（build 5472）
- **最新列出的發布日期：** 2026-10-10
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.1.6 | 5472 | 2026-10-10 | 14.0 | 23.23 MB (24,353,925 bytes) | [下載](https://github.com/bggRGjQaUbCoE/PiliPlus/releases/download/2.1.6.2/PiliPlus_ios_2.1.6%2B5472.ipa) |

**版本說明：** 专栏支持跳转至评论 #3213 其他调整 #3208 by @My-Responsitories  修复 bug 修复搜索风控验证 #3106 修复窗口大小变化时图片闪烁 #2685 修复安卓视频暂停时画面裁切问题 #3034 by @Hdy08

### 31. Pixiv-SwiftUI

- **開發者：** Eslzzyl
- **Bundle ID：** `org.eu.eslzzyl.Pixiv-SwiftUI`
- **副標題：** 基于 SwiftUI 的 Pixiv 第三方客户端
- **主題色：** `#13A1FD`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Pixiv-SwiftUI/icon.png
- **功能／描述：** 基于 SwiftUI 开发的 Pixiv 第三方客户端，支持 iOS/iPadOS/macOS。提供插画、漫画与小说的推荐、排行榜、搜索与收藏，内置评论系统、批量下载、数据导入导出、深色模式与主题自定义。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Pixiv-SwiftUI/images/recommend.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Pixiv-SwiftUI/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Pixiv-SwiftUI/images/search.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.16.2
- **最新列出的發布日期：** 2026-10-11
- **最低 iOS：** 17.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.16.2 | 未提供 | 2026-10-11 | 17.0 | 9.86 MB (10,343,925 bytes) | [下載](https://github.com/Eslzzyl/Pixiv-SwiftUI/releases/download/v0.16.2/Pixiv-SwiftUI.ipa) |

**版本說明：** ## 新功能  - App 更新弹窗新增“跳过此版本”选项，支持忽略指定版本的自动更新提醒 - （v0.16.1 的新功能）HTTP/3 直连模式，修正此前版本的 403 问题  ## 优化  - 优化了一系列图片的加载逻辑，改善了 v0.16.1 的高发热问题。  > 性能优化还有很大空间，但暂时推不动了。有想法的朋友期待你的 PR  ## 问题修复  - 修复手动提交搜索后未清空搜索栏输入内容的问题 - 修复全屏查看图片失败时的降级回退逻辑，优先展示已加载的预览图 - 修复 iOS 端在页面切换或应用切入后台后…（版本說明已節錄）

### 32. Playport

- **開發者：** playportdev
- **Bundle ID：** `dev.playport.app`
- **副標題：** PC games on your iPhone. Natively, no streaming.
- **主題色：** `#F5B544`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Playport/icon.png
- **功能／描述：** Playport runs Windows games, 64-bit and 32-bit, on a stock, non-jailbroken iPhone: install a game from your library onto the phone, pick up a controller and press Play. The game runs on the phone's own CPU and GPU — no PC, no cloud, no stream. Requires iOS 26 or later with JIT enabled through LocalDevVPN or StikDebug.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Playport/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Playport/images/library.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Playport/images/game-page.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.4.0
- **最新列出的發布日期：** 2026-10-08
- **最低 iOS：** 26.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.4.0 | 未提供 | 2026-10-08 | 26.0 | 641.30 MB (672,450,129 bytes) | [下載](https://github.com/playportdev/playport/releases/download/v0.4.0/Playport-0.4.0.ipa) |

**版本說明：** # Playport 0.4.0: GOG, Epic Games and your own games  **Playport is no longer only for Steam.** Sign in to **GOG** or **Epic Games** and install your games from there, or bring any DRM-free PC game from Files. Games now sign in to their store as they would on …（版本說明已節錄）

### 33. PSX3IOS

- **開發者：** xmiguel911x
- **Bundle ID：** `com.miguel.psx3ios`
- **副標題：** PlayStation 3 emulator for iPhone and iPad
- **主題色：** `#5080D0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PSX3IOS/icon.png
- **功能／描述：** A PlayStation 3 emulator for iPhone and iPad, built on RPCS3. Real games boot and play — the whole emulator core is exposed, with community game patches, trophies, play time, save data and 14 languages. Works with or without JIT.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PSX3IOS/images/home.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PSX3IOS/images/install.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PSX3IOS/images/settings.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 0.2.7-beta
- **最新列出的發布日期：** 2026-09-01
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.2.7-beta | 未提供 | 2026-09-01 | 15.0 | 64.51 MB (67,644,766 bytes) | [下載](https://github.com/xmiguel911x/PSX3IOS/releases/download/v0.2.7-beta/PSX3IOS-beta.0.2.7-unsigned.ipa) |

**版本說明：** Various improvements added, jit fixed A15 iOS 17.0 TrollStore Go to settings, JIT mode detected, and leave it on automatic, and bugs fixed

### 34. PureLive

- **開發者：** liuchuancong
- **Bundle ID：** `com.mystyle.purelive.liu`
- **副標題：** 基于 Flutter 的开源多平台直播聚合播放器
- **主題色：** `#50B0F0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PureLive/icon.png
- **功能／描述：** 纯粹直播（Pure Live）是一款基于 Flutter 的开源第三方多平台直播聚合播放器，支持 Bilibili、虎牙、斗鱼、快手、抖音、网易 CC、Twitch 等平台，以及自定义 M3U/M3U8 直播源。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PureLive/images/list.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PureLive/images/area.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/PureLive/images/auth.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 3.1.19
- **最新列出的發布日期：** 2026-10-10
- **最低 iOS：** 15.6

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 3.1.19 | 未提供 | 2026-10-10 | 15.6 | 63.76 MB (66,858,114 bytes) | [下載](https://github.com/liuchuancong/pure_live/releases/download/v3.1.19/PureLive-3.1.19-4108-ios-arm64-trollstore.ipa) |

**版本說明：** # 纯粹直播 v3.1.19 \|版本\|下载地址\| \|---\|---\| \|TV版\|[pure_live_TV](https://github.com/liuchuancong/pure_live_TV/releases/latest)\| \|Windows/macOS/Android/iOS版\|[pure_live](https://github.com/liuchuancong/pure_live/releases/latest)\| ### 🖥️ Windows 版 - **Portable…（版本說明已節錄）

### 35. Roam Control

- **開發者：** seanhowarthdev
- **Bundle ID：** `com.sean.roamcontrol`
- **副標題：** Choose, test and move your iPhone's reported location
- **主題色：** `#1090F0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Roam-Control/icon.png
- **功能／描述：** Set a fixed reported location, preview and simulate Apple Maps walking routes, and save favourites and history — all from one map. Requires iOS 27 or newer, and guided LocalDevVPN-compatible sessions for Wi-Fi and mobile data.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Roam-Control/images/welcome.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Roam-Control/images/fixed-location.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Roam-Control/images/walking-preview.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.9.7
- **最新列出的發布日期：** 2026-10-08
- **最低 iOS：** 27.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.9.7 | 未提供 | 2026-10-08 | 27.0 | 3.92 MB (4,111,825 bytes) | [下載](https://github.com/seanhowarthdev/Roam-Control/releases/download/v0.9.7/RoamControl-0.9.7-Build96.ipa) |

**版本說明：** ## Stability and reliability improvements  Roam Control 0.9.7 is a maintenance update focused on background location-session reliability and mobile-data connectivity.  ### What's improved  - Improved native connection handling for LocalDevVPN. - Corrected netw…（版本說明已節錄）

### 36. SceneBox

- **開發者：** donbytyqi
- **Bundle ID：** `app.scenebox.SceneBox`
- **副標題：** Torrent streaming client
- **主題色：** `#E0E000`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SceneBox/icon.png
- **功能／描述：** Torrent streaming client for iOS, iPadOS, tvOS and Mac (Catalyst), written in SwiftUI. Streams come from Stremio-compatible addons and play through a vendored libtorrent engine feeding VLC.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SceneBox/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SceneBox/images/search.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SceneBox/images/profile.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.0.4
- **最新列出的發布日期：** 2026-09-23
- **最低 iOS：** 18.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.0.4 | 未提供 | 2026-09-23 | 18.0 | 29.18 MB (30,593,765 bytes) | [下載](https://github.com/donbytyqi/scenebox/releases/download/v1.0.4/SceneBox-1.0.4.ipa) |

**版本說明：** Important: accounts now need your own Firebase project  SceneBox no longer connects to a shared Firebase project. Sign-in, profiles and sync between devices now run on a free Firebase project that you create and own. Your data stays in your own account, not mi…（版本說明已節錄）

### 37. SpotiFLAC

- **開發者：** zarzet
- **Bundle ID：** `com.zarz.spotiflac`
- **副標題：** FLAC Downloader for iOS
- **主題色：** `#1DB954`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SpotiFLAC/icon.png
- **功能／描述：** SpotiFLAC is a Flutter music app built around installable extensions: an extension supplies the metadata and the audio downloads for one provider, so sources can be added or repaired without an app update. Downloads land in a local library with lyrics, cover art, quality badges and duplicate detection.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SpotiFLAC/images/home.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SpotiFLAC/images/library.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SpotiFLAC/images/store.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/SpotiFLAC/images/settings.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 5.1.1
- **最新列出的發布日期：** 2026-10-11
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 5.1.1 | 未提供 | 2026-10-11 | 16.0 | 32.04 MB (33,596,866 bytes) | [下載](https://github.com/spotiflacapp/SpotiFLAC-Mobile/releases/download/v5.1.1/SpotiFLAC-v5.1.1-ios-unsigned.ipa) |

**版本說明：** ### New Features  - **network**: Delete SMB and WebDAV tracks from the library - **autoplay**: Add opt-in on-device recommendation learning - **network**: Enable audio and hi-res analysis for network tracks - **mornye**: Animate squircle menus from their trigg…（版本說明已節錄）

### 38. TiebaPure

- **開發者：** infinityf4p
- **Bundle ID：** `dev.infinityf4p.tiebapure`
- **副標題：** 基于 SwiftUI 的第三方百度贴吧客户端
- **主題色：** `#708070`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/TiebaPure/icon.png
- **功能／描述：** 原生 SwiftUI 构建的非官方贴吧 iOS 客户端。未登录访客即可浏览首页推荐、进吧与吧内列表、帖子详情与楼中楼、搜索、图片缩放与视频播放；登录后支持消息、关注与粉丝、收藏帖子（与官方客户端同步）、每日签到、点赞与发帖回复。另有关键词/用户/贴吧屏蔽、浏览历史与阅读位置恢复、iPad 双栏布局，以及 `tiebapure://` 深链接。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/TiebaPure/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/TiebaPure/images/thread.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/TiebaPure/images/search.png
- **來源內版本數：** 1
- **目前列出的版本：** 1.4.15
- **最新列出的發布日期：** 2026-10-10
- **最低 iOS：** 16.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.4.15 | 未提供 | 2026-10-10 | 16.4 | 8.91 MB (9,347,637 bytes) | [下載](https://github.com/infinityf4p/TiebaPure-iOS/releases/download/v1.4.15/TiebaPure-v1.4.15-unsigned.ipa) |

**版本說明：** ## What's included  - Stabilizes Home tab reselection and refresh behavior after scrolling. - Returning from a thread or search now closes that screen first; the next Home tap refreshes the feed. - A Home tap during an in-flight refresh returns to the top with…（版本說明已節錄）

### 39. Tsumiru

- **開發者：** Suwayomi
- **Bundle ID：** `com.suwayomi.tachideskSorayomi`
- **副標題：** Native manga & manhwa reader for Suwayomi-Server
- **主題色：** `#7c7bff`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Suwayomi-Tsumiru/icon.png
- **功能／描述：** Tsumiru is a native client for reading manga & manhwa from a Suwayomi-Server instance, built for long webtoon binges. Offline downloads with an on-device catalog, a rebuilt continuous-scroll webtoon reader, incognito mode, and 13 built-in themes.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Suwayomi-Tsumiru/images/list.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Suwayomi-Tsumiru/images/update.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 1.4.0
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.4.0 | 未提供 | 2026-10-13 | 14.0 | 15.47 MB (16,222,984 bytes) | [下載](https://github.com/Suwayomi/Suwayomi-Tsumiru/releases/download/v1.4.0/tsumiru-v1.4.0-ios.ipa) |

**版本說明：** A manga and webtoon reader for your [Suwayomi](https://suwayomi.org/) server.  ### ✨ New Features  - Added **SyncYomi** settings and a sync button in Library and Updates when **Sync with SyncYomi** is on (@aaronbamblett) - Added **KOReader Sync** settings (@aa…（版本說明已節錄）

### 40. UTM

- **開發者：** osy
- **Bundle ID：** `com.utmapp.UTM`
- **副標題：** Virtual machines for iOS
- **主題色：** `#1a2cc2`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/UTM/icon.png
- **功能／描述：** UTM is a full featured virtual machine host for iOS. In short, it allows you to run Windows, Android, and more on your iPhone and iPad.  This version requires using AltJIT. Install UTM SE for slower emulation without JIT.  More information at https://getutm.app/  Features:  • Emulate any Processor 30+ processors supported by qemu including x86_64, ARM64, and RISC-V • Run any Operating System Windows, Linux, and more …（原始描述較長，已節錄）
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/UTM/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/UTM/images/settings.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/UTM/images/display.png
- **來源內版本數：** 1
- **目前列出的版本：** 4.7.5
- **最新列出的發布日期：** 2026-01-03
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 4.7.5 | 未提供 | 2026-01-03 | 14.0 | 124.03 MB (130,058,389 bytes) | [下載](https://github.com/utmapp/UTM/releases/download/v4.7.5/UTM.ipa) |

**版本說明：** ## Highlights * **QEMU v10.0.2**: The backend has been updated to the latest upstream QEMU which brings with it a variety of bug fixes and performance improvements. * **Liquid Glass**: UTM adopts the Liquid Glass design on *OS 26. * **App Intents**: New suppor…（版本說明已節錄）

### 41. VeneraNext

- **開發者：** CyrilPeng
- **Bundle ID：** `com.github.cyrilpeng.veneranext`
- **副標題：** 跨平台漫画阅读器
- **主題色：** `#2090E0`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Venera-Next/icon.png
- **功能／描述：** 基于 Flutter 的跨平台漫画阅读器，支持本地漫画、WebDAV 漫画源与第三方网络漫画源，支持 Android、iOS、Windows、Linux、macOS 平台。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Venera-Next/images/home.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Venera-Next/images/explorer.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/Venera-Next/images/search.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 1.18.0（build 234）
- **最新列出的發布日期：** 2026-10-14
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.18.0 | 234 | 2026-10-14 | 14.0 | 20.15 MB (21,127,254 bytes) | [下載](https://github.com/CyrilPeng/Venera-Next/releases/download/v1.18.0/VeneraNext-ios-1.18.0%2B234.ipa) |

**版本說明：** 本次正式版在 v1.17.0 基础上完成大范围架构重构，收束阅读器、漫画源、同步与运行时的职责边界，并新增图片原始像素尺寸、章节阅读进度、自动阅读屏幕常亮与跳过不可用图片。同步修复 WebDAV 应用数据同步、日志持久化、AVIF 识别及图片去混淆性能问题，修复 Rust 依赖安全告警并更新相关依赖。经 v1.18.0-rc.1 至 rc.5 逐版验证，Windows 与 Android 的 WebDAV 手动上传、云端下载覆盖及自动同步已通过实机验收。  ### 新增  - 阅读器可选显示图片原始像素尺寸，支持单…（版本說明已節錄）

### 42. YouProEXTRA

- **開發者：** alibusut
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** YouTube mod with customizable tweaks
- **主題色：** `#FF0000`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/YouProEXTRA/icon.png
- **功能／描述：** YouPro mod of YouTube for iOS. Includes no ads, background playback, downloads, iSponsorBlock, PiP, and a host of customizable tweaks.
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/YouProEXTRA/images/list.jpg · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/YouProEXTRA/images/play.jpg
- **來源內版本數：** 1
- **目前列出的版本：** 21.41.5（build 21.41.5）
- **最新列出的發布日期：** 2026-10-11
- **最低 iOS：** 16.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 | 21.41.5 | 2026-10-11 | 16.0 | 124.67 MB (130,721,602 bytes) | [下載](https://github.com/mrdrvt99/YouProEXTRA/releases/download/youproextra-ipa2/YouProExtra_21.41.5_1.3.1.ipa) |

**版本說明：** ### Latest Release, ENJOY!! > [!NOTE] > - **YTUHD** is not included. 4K60HDR is available. > - if you're signed out you can sign in manually.  > - no iSponsorBlock. (unstable in newer builds) > - for <A15 devices press share button in the arrow down panel and …（版本說明已節錄）

### 43. ZhihuMinusMinus

- **開發者：** huamurui
- **Bundle ID：** `com.huamu013.ZhihuMinusMinus`
- **副標題：** 轻量、纯净的第三方知乎客户端
- **主題色：** `#0084ff`
- **圖示：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ZhihuMinusMinus/icon.png
- **功能／描述：** 基于 React Native (Expo) 构建的轻量级第三方知乎客户端，无广告，支持多账号切换、游客模式、全局主题色自定义与深色模式，可查看热榜、推荐、回答、文章、想法与评论区，并支持从 GitHub Releases 自动更新。
- **截圖：** https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ZhihuMinusMinus/images/home.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ZhihuMinusMinus/images/detail.png · https://raw.githubusercontent.com/bebound/AltGallery/refs/heads/master/apps/ZhihuMinusMinus/images/hot.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.9.0
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 15.1

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.9.0 | 未提供 | 2026-10-13 | 15.1 | 15.35 MB (16,096,852 bytes) | [下載](https://github.com/huamurui/zhihu-minus-minus/releases/download/v0.9.0/zhihu-minus-minus-v0.9.0-unsigned.ipa) |

**版本說明：** * 修复断网恢复等待与首次游客 Feed 初始化 by @huamurui in https://github.com/huamurui/zhihu-minus-minus/pull/127 * 恢复收藏快捷操作，统一 SVG 图标与列表收藏信息 by @huamurui in https://github.com/huamurui/zhihu-minus-minus/pull/128 * 修复关注头像栏横滑冲突，支持最近发布左右切换用户 by @huamurui in https://github.com/hua…（版本說明已節錄）

## 四、自己的 Chi Source 全部 App

- **Source URL：** https://ipa.chi.qzz.io
- **JSON：** https://raw.githubusercontent.com/tsai97216/chi-source/main/apps.json
- **App 數量：** 7

### 1. PiliPlus

- **開發者：** bggRGjQaUbCoE
- **Bundle ID：** `com.bgg.piliplus`
- **副標題：** bggRGjQaUbCoE（2026-10-10）
- **分類：** entertainment
- **主題色：** `B8D2C1`
- **圖示：** https://raw.githubusercontent.com/tsai97216/chi-source/main/piliplus.png
- **功能／描述：** 第三方 Bilibili 客戶端，提供增強播放與其他功能。
- **來源內版本數：** 1
- **目前列出的版本：** 2.1.6.2
- **最新列出的發布日期：** 2026-10-10

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.1.6.2 | 未提供 | 2026-10-10 | 未提供 | 23.23 MB (24,353,925 bytes) | [下載](https://github.com/bggRGjQaUbCoE/PiliPlus/releases/download/2.1.6.2/PiliPlus_ios_2.1.6%2B5472.ipa) |

**版本說明：** 专栏支持跳转至评论 #3213 其他调整 #3208 by @My-Responsitories  修复 bug 修复搜索风控验证 #3106 修复窗口大小变化时图片闪烁 #2685 修复安卓视频暂停时画面裁切问题 #3034 by @Hdy08

### 2. YTKACE

- **開發者：** itzzace
- **Bundle ID：** `com.google.ios.youtube`
- **副標題：** itzzace（2026-10-11）
- **分類：** entertainment
- **主題色：** `E8A8B7`
- **圖示：** https://raw.githubusercontent.com/tsai97216/chi-source/main/YT.png
- **功能／描述：** An open-source YouTube enhancement for iOS.
- **來源內版本數：** 1
- **目前列出的版本：** 21.41.5
- **最新列出的發布日期：** 2026-10-11

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 21.41.5 | 未提供 | 2026-10-11 | 未提供 | 130.80 MB (137,158,764 bytes) | [下載](https://github.com/itzzace/ytkace/releases/download/v1.1.3/YTKACE_1.1.3_YouTube_21.41.5.ipa) |

**版本說明：** by @itzzace0  What's new: • Updated to YouTube 21.41.5 • Added Hide AI Channels, which hides videos from channels on the AiSList blocklist in your feed and search, with an option for the warnlist too • Swipe the SponsorBlock popup away to dismiss it  Fixed: • …（版本說明已節錄）

### 3. MaxMusic

- **開發者：** Mark02-2012
- **Bundle ID：** `com.google.ios.youtubemusic`
- **副標題：** Mark02-2012（2026-08-30）
- **分類：** entertainment
- **主題色：** `E8A8B7`
- **圖示：** https://raw.githubusercontent.com/Mark02-2012/YTMUltimatePLUS/MYmain/Resources/IMG_5914.png
- **功能／描述：** MaxMusic is a fork of YTMusicUltimate with additional tweaks for YouTube Music on iOS.
- **來源內版本數：** 1
- **目前列出的版本：** 9.34.4
- **最新列出的發布日期：** 2026-08-30

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.34.4 | 未提供 | 2026-08-30 | 未提供 | 99.26 MB (104,079,008 bytes) | [下載](https://github.com/Mark02-2012/MaxMusic/releases/download/YTMU%2B_9.34.4_2.4.1_%2884%29/YTMUltimate%2B_2.4.1_9.34.4.ipa) |

**版本說明：** **Changed** YTMusic version

### 4. Facebook

- **開發者：** IPA Vault
- **Bundle ID：** `com.facebook.Facebook`
- **副標題：** IPA Vault（2026-10-09）
- **分類：** social
- **主題色：** `78A5E3`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Facebook-Icons/Facebook-AppStore-1024x1024.png
- **功能／描述：** Facebook 582.0.0 with iQFace 1.2
- **來源內版本數：** 1
- **目前列出的版本：** 582.0.0
- **最新列出的發布日期：** 2026-10-09

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 582.0.0 | 未提供 | 2026-10-09 | 未提供 | 223.92 MB (234,797,502 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Facebook-582.0.0-iQFace.ipa) |

**版本說明：** IPA Vault build for Facebook (iQFace), version 582.0.0

### 5. Threads

- **開發者：** IPA Vault
- **Bundle ID：** `com.burbn.barcelona`
- **副標題：** IPA Vault（2026-10-13）
- **分類：** social
- **主題色：** `858585`
- **圖示：** https://pub-dd800571175348b6a2745b3396360028.r2.dev/App%20Icons/Threads-Icons/Threads-AppStore-1024x1024.png
- **功能／描述：** Threads 451.0 with ThreadSaver
- **來源內版本數：** 1
- **目前列出的版本：** 451.0
- **最新列出的發布日期：** 2026-10-13

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 451.0 | 未提供 | 2026-10-13 | 未提供 | 107.76 MB (112,995,145 bytes) | [下載](https://pub-dd800571175348b6a2745b3396360028.r2.dev/Threads-451.0-ThreadSaver.ipa) |

**版本說明：** IPA Vault build for Threads (ThreadSaver), version 451.0

### 6. Instagram

- **開發者：** AppTesters
- **Bundle ID：** `com.burbn.instagram`
- **副標題：** AppTesters（2026-06-10）
- **分類：** social
- **主題色：** `DC8FA1`
- **圖示：** https://raw.githubusercontent.com/apptesters-org/AppTesters_Repo/main/icons/com.burbn.instagram.png
- **功能／描述：** Injected with Premium
- **來源內版本數：** 1
- **目前列出的版本：** 433.0.0
- **最新列出的發布日期：** 2026-06-10

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 433.0.0 | 未提供 | 2026-06-10 | 未提供 | 269.47 MB (282,563,167 bytes) | [下載](https://github.com/apptesters-org/AppTesters_Repo/releases/download/10-06-2026/Instagram_433.0.0_Premium_%40thisismanpreets_apptesters.org.ipa) |

**版本說明：** Injected with Premium

### 7. EeveeSpotify Reincarnated

- **開發者：** SideloadLabs
- **Bundle ID：** `com.spotify.client.patched`
- **副標題：** SideloadLabs（2026-10-05）
- **分類：** entertainment
- **主題色：** `669878`
- **圖示：** https://files.catbox.moe/9fgova.JPG
- **功能／描述：** Spotify Version: v9.1.88, EeveeSpotify Version: 7.0.0. Patched version, use this only if you're using paid cert, jailbroken, or trollstore
- **來源內版本數：** 1
- **目前列出的版本：** 9.1.88
- **最新列出的發布日期：** 2026-10-05

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 9.1.88 | 未提供 | 2026-10-05 | 未提供 | 12.40 MB (13,000,000 bytes) | [下載](https://files.catbox.moe/ogibmn.ipa) |

**版本說明：** Updated to Spotify v9.1.88, Full release notes on github

## 五、自己的 Chi Source Personal 全部 App

- **Source URL：** https://ipap.chi.qzz.io
- **JSON：** https://raw.githubusercontent.com/tsai97216/chi-source-personal/main/apps.json
- **App 數量：** 8

### 1. SpooferPro Pokemon GO

- **開發者：** SpooferPro
- **Bundle ID：** `com.nianticlabs.pokemongo`
- **副標題：** SpooferPro（2026-10-12）
- **分類：** games
- **主題色：** `#FFA900`
- **圖示：** https://spooferpro.com/android-chrome-512x512.png
- **功能／描述：** SPOOF INTO THE World of PoGO SpooferPro for PoGO is an enhanced edition of the PoGO app, adding a joystick and ability to teleport! It also includes a lot of other features like, IV Previews, Modified Throw, Auto Walking, GPX, Fast Catch, a live feed and even a map with everything around you! No need for a computer and even works on non-jailbreak iPhones! We highly recommend it, so check it out!  FAKE LOCATION Telepo…（原始描述較長，已節錄）
- **截圖：** https://spooferpro.com/img/DCUE1687.PNG · https://spooferpro.com/img/AZAR2677.PNG · https://spooferpro.com/img/ARZR8718.PNG · https://spooferpro.com/img/DFLK2822.PNG（另有 11 張）
- **來源內版本數：** 8
- **目前列出的版本：** 0.431.1（build 0.736）
- **最新列出的發布日期：** 2026-10-12
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.431.1 | 0.736 | 2026-10-12 | 15.0 | 164.24 MB (172,215,785 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.736.RLS.ipa) |
| 0.431.1 | 0.734 | 2026-10-08 | 15.0 | 163.91 MB (171,877,289 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.734.RLS.ipa) |
| 0.431.1 | 0.733 | 2026-10-07 | 15.0 | 164.62 MB (172,621,260 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.733.RLS.ipa) |
| 0.431.1 | 0.732 | 2026-10-04 | 15.0 | 164.00 MB (171,969,850 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.732.RLS.ipa) |
| 0.431.1 | 0.731 | 2026-10-03 | 15.0 | 163.68 MB (171,629,436 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.731.RLS.ipa) |
| 0.431.1 | 0.729 | 2026-10-02 | 15.0 | 163.68 MB (171,633,917 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.431.1-0.729.RLS.ipa) |
| 0.429.1 | 0.727 | 2026-09-25 | 15.0 | 160.90 MB (168,715,979 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.429.1-0.727.RLS.ipa) |
| 0.429.1 | 0.726 | 2026-09-21 | 15.0 | 160.86 MB (168,671,593 bytes) | [下載](https://download.spooferpro.com/SpooferPro-0.429.1-0.726.RLS.ipa) |

**版本說明：** SpooferPro-0.431.1-0.736.RLS.ipa

### 2. Animeko

- **開發者：** openani
- **Bundle ID：** `org.animeko.animeko`
- **副標題：** openani（2026-10-13）
- **分類：** entertainment
- **主題色：** `#6c9cc4`
- **圖示：** https://avatars.githubusercontent.com/u/166622089
- **功能／描述：** 集找番、追番、看番的一站式弹幕追番平台，云收藏同步 (Bangumi)，离线缓存，BitTorrent，弹幕云过滤。
- **截圖：** https://raw.githubusercontent.com/open-ani/animeko/main/.readme/images/features/home.png · https://raw.githubusercontent.com/open-ani/animeko/main/.readme/images/features/anime-schedule.png · https://raw.githubusercontent.com/open-ani/animeko/main/.readme/images/features/subject-collection.png · https://raw.githubusercontent.com/open-ani/animeko/main/.readme/images/features/search-by-tag.png（另有 5 張）
- **來源內版本數：** 12
- **目前列出的版本：** 6.3.0（build 6.3.99）
- **最新列出的發布日期：** 2026-10-13
- **最低 iOS：** 14.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 6.3.0 | 6.3.99 | 2026-10-13 | 14.0 | 44.33 MB (46,485,035 bytes) | [下載](https://d2.myani.org/v6.3.0/ani-6.3.0.ipa) |
| 6.2.0 | 6.2.99 | 2026-09-26 | 14.0 | 43.30 MB (45,401,084 bytes) | [下載](https://d2.myani.org/v6.2.0/ani-6.2.0.ipa) |
| 6.1.0 | 60100 | 2026-08-28 | 14.0 | 42.37 MB (44,425,669 bytes) | [下載](https://d2.myani.org/v6.1.0/ani-6.1.0.ipa) |
| 6.0.0 | 60000 | 2026-08-01 | 14.0 | 39.47 MB (41,391,524 bytes) | [下載](https://d2.myani.org/v6.0.0/ani-6.0.0.ipa) |
| 5.7.1 | 50710 | 2026-07-09 | 14.0 | 29.09 MB (30,505,730 bytes) | [下載](https://d2.myani.org/v5.7.1/ani-5.7.1.ipa) |
| 5.7.0 | 50700 | 2026-06-28 | 14.0 | 29.09 MB (30,504,862 bytes) | [下載](https://d2.myani.org/v5.7.0/ani-5.7.0.ipa) |
| 5.6.0 | 50600 | 2026-05-28 | 14.0 | 28.93 MB (30,337,983 bytes) | [下載](https://d2.myani.org/v5.6.0/ani-5.6.0.ipa) |
| 5.5.2 | 50520 | 2026-05-26 | 14.0 | 28.54 MB (29,924,579 bytes) | [下載](https://d2.myani.org/v5.5.2/ani-5.5.2.ipa) |
| 5.5.1 | 50510 | 2026-05-24 | 14.0 | 28.54 MB (29,923,207 bytes) | [下載](https://d2.myani.org/v5.5.1/ani-5.5.1.ipa) |
| 5.4.4 | 50440 | 2026-05-13 | 14.0 | 33.72 MB (35,357,234 bytes) | [下載](https://d2.myani.org/v5.4.4/ani-5.4.4.ipa) |
| 5.4.3 | 50430 | 2026-04-12 | 14.0 | 33.72 MB (35,360,753 bytes) | [下載](https://d2.myani.org/v5.4.3/ani-5.4.3.ipa) |
| 5.4.2 | 50420 | 2026-04-11 | 14.0 | 33.72 MB (35,355,797 bytes) | [下載](https://d2.myani.org/v5.4.2/ani-5.4.2.ipa) |

**版本說明：** - 数据源选择支持手动查找模式，支持直接浏览数据源剧集并记住选择，方便后续切集，同时优化 BT 资源搜索、筛选和列表展示 - 新增热度排行页，可浏览完整的 Bangumi 动画热度榜 - 大幅提升分季拆分放送的动画的选集准确性 - Android 和 iOS 支持系统画中画播放 (#3466 by @GeneralK1ng) - 优化播放器截图体验，新增角落预览，支持查看、复制与系统分享 - 观看进度支持离线处理, 上线后自动同步 - 剧集列表按正片、特别篇等类型分组，上一集、下一集与自动连播只在同类型剧集之间切换…（版本說明已節錄）

### 3. Kazumi

- **開發者：** Predidit
- **Bundle ID：** `com.example.kazumi`
- **副標題：** Predidit（2026-10-07）
- **分類：** entertainment
- **主題色：** `#57cd67`
- **圖示：** https://github.com/Predidit/Kazumi/blob/main/assets/images/logo/logo_ios.png?raw=true
- **功能／描述：** 使用 Flutter 开发的基于自定义规则的番剧采集与在线观看程序。使用最多五行基于 Xpath 语法的选择器构建自己的规则。支持规则导入与规则分享。支持基于 Anime4K 的实时超分辨率。绝赞开发中 (～￣▽￣)～
- **截圖：** https://github.com/Predidit/Kazumi/blob/main/static/screenshot/img_1.png?raw=true · https://github.com/Predidit/Kazumi/blob/main/static/screenshot/img_2.png?raw=true · https://github.com/Predidit/Kazumi/blob/main/static/screenshot/img_3.png?raw=true · https://github.com/Predidit/Kazumi/blob/main/static/screenshot/img_4.png?raw=true（另有 2 張）
- **來源內版本數：** 100
- **目前列出的版本：** 2.3.8（build 20308）
- **最新列出的發布日期：** 2026-10-07
- **最低 iOS：** 13.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 2.3.8 | 20308 | 2026-10-07 | 13.0 | 29.05 MB (30,463,104 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.8/Kazumi_ios_2.3.8_no_sign.ipa) |
| 2.3.7 | 20307 | 2026-09-30 | 13.0 | 29.12 MB (30,538,813 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.7/Kazumi_ios_2.3.7_no_sign.ipa) |
| 2.3.6 | 20306 | 2026-09-23 | 13.0 | 29.00 MB (30,406,530 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.6/Kazumi_ios_2.3.6_no_sign.ipa) |
| 2.3.5 | 20305 | 2026-09-23 | 13.0 | 29.00 MB (30,404,211 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.5/Kazumi_ios_2.3.5_no_sign.ipa) |
| 2.3.4 | 20304 | 2026-09-22 | 13.0 | 27.76 MB (29,106,919 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.4/Kazumi_ios_2.3.4_no_sign.ipa) |
| 2.3.3 | 20303 | 2026-09-15 | 13.0 | 28.44 MB (29,823,335 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.3/Kazumi_ios_2.3.3_no_sign.ipa) |
| 2.3.2 | 20302 | 2026-09-15 | 13.0 | 28.44 MB (29,823,319 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.2/Kazumi_ios_2.3.2_no_sign.ipa) |
| 2.3.1 | 20301 | 2026-09-07 | 13.0 | 28.43 MB (29,812,172 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.1/Kazumi_ios_2.3.1_no_sign.ipa) |
| 2.3.0 | 20300 | 2026-08-28 | 13.0 | 28.28 MB (29,656,485 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.3.0/Kazumi_ios_2.3.0_no_sign.ipa) |
| 2.2.9 | 20209 | 2026-08-21 | 13.0 | 28.27 MB (29,638,292 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.9/Kazumi_ios_2.2.9_no_sign.ipa) |
| 2.2.8 | 20208 | 2026-08-15 | 13.0 | 28.26 MB (29,635,192 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.8/Kazumi_ios_2.2.8_no_sign.ipa) |
| 2.2.7 | 20207 | 2026-08-08 | 13.0 | 28.18 MB (29,554,015 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.7/Kazumi_ios_2.2.7_no_sign.ipa) |
| 2.2.6 | 20206 | 2026-08-01 | 13.0 | 28.18 MB (29,552,334 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.6/Kazumi_ios_2.2.6_no_sign.ipa) |
| 2.2.5 | 20205 | 2026-07-30 | 13.0 | 28.19 MB (29,556,445 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.5/Kazumi_ios_2.2.5_no_sign.ipa) |
| 2.2.4 | 20204 | 2026-07-30 | 13.0 | 27.89 MB (29,243,380 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.4/Kazumi_ios_2.2.4_no_sign.ipa) |
| 2.2.3 | 20203 | 2026-07-23 | 13.0 | 27.83 MB (29,182,954 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.3/Kazumi_ios_2.2.3_no_sign.ipa) |
| 2.2.2 | 20202 | 2026-07-23 | 13.0 | 27.83 MB (29,183,411 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.2/Kazumi_ios_2.2.2_no_sign.ipa) |
| 2.2.1 | 20201 | 2026-07-16 | 13.0 | 27.82 MB (29,172,455 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.1/Kazumi_ios_2.2.1_no_sign.ipa) |
| 2.2.0 | 20200 | 2026-07-09 | 13.0 | 26.85 MB (28,150,602 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.2.0/Kazumi_ios_2.2.0_no_sign.ipa) |
| 2.1.8 | 20108 | 2026-07-02 | 13.0 | 27.03 MB (28,346,335 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.8/Kazumi_ios_2.1.8_no_sign.ipa) |
| 2.1.7 | 20107 | 2026-06-25 | 13.0 | 27.03 MB (28,341,165 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.7/Kazumi_ios_2.1.7_no_sign.ipa) |
| 2.1.6 | 20106 | 2026-06-18 | 13.0 | 27.02 MB (28,334,562 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.6/Kazumi_ios_2.1.6_no_sign.ipa) |
| 2.1.5 | 20105 | 2026-06-11 | 13.0 | 26.74 MB (28,035,611 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.5/Kazumi_ios_2.1.5_no_sign.ipa) |
| 2.1.4 | 20104 | 2026-06-07 | 13.0 | 26.73 MB (28,025,683 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.4/Kazumi_ios_2.1.4_no_sign.ipa) |
| 2.1.3 | 20103 | 2026-05-29 | 13.0 | 26.73 MB (28,024,764 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.3/Kazumi_ios_2.1.3_no_sign.ipa) |
| 2.1.2 | 20102 | 2026-05-21 | 13.0 | 26.70 MB (28,000,908 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.2/Kazumi_ios_2.1.2_no_sign.ipa) |
| 2.1.1 | 20101 | 2026-05-08 | 13.0 | 26.73 MB (28,029,329 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.1/Kazumi_ios_2.1.1_no_sign.ipa) |
| 2.1.0 | 20100 | 2026-05-03 | 13.0 | 26.70 MB (27,997,661 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.1.0/Kazumi_ios_2.1.0_no_sign.ipa) |
| 2.0.9 | 20009 | 2026-05-02 | 13.0 | 26.70 MB (27,997,089 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.9/Kazumi_ios_2.0.9_no_sign.ipa) |
| 2.0.8 | 20008 | 2026-04-24 | 13.0 | 26.60 MB (27,886,967 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.8/Kazumi_ios_2.0.8_no_sign.ipa) |
| 2.0.7 | 20007 | 2026-04-09 | 13.0 | 26.58 MB (27,866,552 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.7/Kazumi_ios_2.0.7_no_sign.ipa) |
| 2.0.6 | 20006 | 2026-03-26 | 13.0 | 26.58 MB (27,869,237 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.6/Kazumi_ios_2.0.6_no_sign.ipa) |
| 2.0.5 | 20005 | 2026-03-07 | 13.0 | 26.47 MB (27,758,976 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.5/Kazumi_ios_2.0.5_no_sign.ipa) |
| 2.0.4 | 20004 | 2026-03-03 | 13.0 | 26.43 MB (27,717,501 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.4/Kazumi_ios_2.0.4_no_sign.ipa) |
| 2.0.3 | 20003 | 2026-02-20 | 13.0 | 26.43 MB (27,716,594 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.3/Kazumi_ios_2.0.3_no_sign.ipa) |
| 2.0.2 | 20002 | 2026-02-12 | 13.0 | 26.42 MB (27,705,875 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.2/Kazumi_ios_2.0.2_no_sign.ipa) |
| 2.0.1 | 20001 | 2026-02-08 | 13.0 | 26.46 MB (27,749,741 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.1/Kazumi_ios_2.0.1_no_sign.ipa) |
| 2.0.0 | 20000 | 2026-02-06 | 13.0 | 26.38 MB (27,665,049 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/2.0.0/Kazumi_ios_2.0.0_no_sign.ipa) |
| 1.9.6 | 10906 | 2026-01-30 | 13.0 | 26.52 MB (27,805,229 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.6/Kazumi_ios_1.9.6_no_sign.ipa) |
| 1.9.5 | 10905 | 2026-01-28 | 13.0 | 26.51 MB (27,796,964 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.5/Kazumi_ios_1.9.5_no_sign.ipa) |
| 1.9.4 | 10904 | 2026-01-09 | 13.0 | 26.18 MB (27,452,591 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.4/Kazumi_ios_1.9.4_no_sign.ipa) |
| 1.9.3 | 10903 | 2025-12-11 | 13.0 | 26.15 MB (27,422,458 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.3/Kazumi_ios_1.9.3_no_sign.ipa) |
| 1.9.2 | 10902 | 2025-12-05 | 13.0 | 26.33 MB (27,608,465 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.2/Kazumi_ios_1.9.2_no_sign.ipa) |
| 1.9.1 | 10901 | 2025-11-27 | 13.0 | 26.33 MB (27,607,497 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.1/Kazumi_ios_1.9.1_no_sign.ipa) |
| 1.9.0 | 10900 | 2025-11-19 | 13.0 | 26.30 MB (27,580,420 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.9.0/Kazumi_ios_1.9.0_no_sign.ipa) |
| 1.8.9 | 10809 | 2025-11-19 | 13.0 | 26.30 MB (27,580,433 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.9/Kazumi_ios_1.8.9_no_sign.ipa) |
| 1.8.8 | 10808 | 2025-11-15 | 13.0 | 21.10 MB (22,127,910 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.8/Kazumi_ios_1.8.8_no_sign.ipa) |
| 1.8.7 | 10807 | 2025-10-29 | 13.0 | 21.00 MB (22,020,941 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.7/Kazumi_ios_1.8.7_no_sign.ipa) |
| 1.8.6 | 10806 | 2025-10-22 | 13.0 | 20.98 MB (21,996,275 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.6/Kazumi_ios_1.8.6_no_sign.ipa) |
| 1.8.5 | 10805 | 2025-10-21 | 13.0 | 20.98 MB (21,995,635 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.5/Kazumi_ios_1.8.5_no_sign.ipa) |
| 1.8.4 | 10804 | 2025-10-14 | 13.0 | 20.97 MB (21,993,484 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.4/Kazumi_ios_1.8.4_no_sign.ipa) |
| 1.8.3 | 10803 | 2025-10-14 | 13.0 | 20.97 MB (21,993,496 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.3/Kazumi_ios_1.8.3_no_sign.ipa) |
| 1.8.2 | 10802 | 2025-09-25 | 13.0 | 20.98 MB (21,996,984 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.2/Kazumi_ios_1.8.2_no_sign.ipa) |
| 1.8.1 | 10801 | 2025-09-19 | 13.0 | 20.97 MB (21,990,221 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.1/Kazumi_ios_1.8.1_no_sign.ipa) |
| 1.8.0 | 10800 | 2025-09-18 | 13.0 | 20.97 MB (21,989,645 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.8.0/Kazumi_ios_1.8.0_no_sign.ipa) |
| 1.7.9 | 10709 | 2025-09-10 | 13.0 | 20.97 MB (21,992,363 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.9/Kazumi_ios_1.7.9_no_sign.ipa) |
| 1.7.8 | 10708 | 2025-09-04 | 13.0 | 20.93 MB (21,951,356 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.8/Kazumi_ios_1.7.8_no_sign.ipa) |
| 1.7.7 | 10707 | 2025-08-17 | 13.0 | 20.98 MB (22,002,778 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.7/Kazumi_ios_1.7.7_no_sign.ipa) |
| 1.7.6 | 10706 | 2025-08-11 | 13.0 | 37.60 MB (39,427,173 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.6/Kazumi_ios_1.7.6_no_sign.ipa) |
| 1.7.5 | 10705 | 2025-07-27 | 13.0 | 36.83 MB (38,615,274 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.5/Kazumi_ios_1.7.5_no_sign.ipa) |
| 1.7.4 | 10704 | 2025-07-01 | 13.0 | 36.83 MB (38,618,937 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.4/Kazumi_ios_1.7.4_no_sign.ipa) |
| 1.7.3 | 10703 | 2025-06-07 | 13.0 | 36.80 MB (38,592,780 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.3/Kazumi_ios_1.7.3_no_sign.ipa) |
| 1.7.2 | 10702 | 2025-05-21 | 13.0 | 36.69 MB (38,475,880 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.2/Kazumi_ios_1.7.2_no_sign.ipa) |
| 1.7.1 | 10701 | 2025-05-14 | 13.0 | 37.30 MB (39,110,772 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.1/Kazumi_ios_1.7.1_no_sign.ipa) |
| 1.7.0 | 10700 | 2025-05-08 | 13.0 | 37.29 MB (39,099,543 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.7.0/Kazumi_ios_1.7.0_no_sign.ipa) |
| 1.6.9 | 10609 | 2025-04-30 | 13.0 | 37.28 MB (39,090,210 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.9/Kazumi_ios_1.6.9_no_sign.ipa) |
| 1.6.8 | 10608 | 2025-04-24 | 13.0 | 37.28 MB (39,089,297 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.8/Kazumi_ios_1.6.8_no_sign.ipa) |
| 1.6.7 | 10607 | 2025-04-19 | 13.0 | 37.28 MB (39,088,354 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.7/Kazumi_ios_1.6.7_no_sign.ipa) |
| 1.6.6 | 10606 | 2025-04-13 | 13.0 | 37.25 MB (39,056,342 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.6/Kazumi_ios_1.6.6_no_sign.ipa) |
| 1.6.5 | 10605 | 2025-04-07 | 13.0 | 37.22 MB (39,030,869 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.5/Kazumi_ios_1.6.5_no_sign.ipa) |
| 1.6.4 | 10604 | 2025-04-02 | 13.0 | 37.24 MB (39,053,433 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.4/Kazumi_ios_1.6.4_no_sign.ipa) |
| 1.6.3 | 10603 | 2025-03-27 | 13.0 | 37.08 MB (38,879,766 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.3/Kazumi_ios_1.6.3_no_sign.ipa) |
| 1.6.2 | 10602 | 2025-03-20 | 13.0 | 37.05 MB (38,844,935 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.2/Kazumi_ios_1.6.2_no_sign.ipa) |
| 1.6.1 | 10601 | 2025-03-09 | 13.0 | 37.04 MB (38,841,421 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.1/Kazumi_ios_1.6.1_no_sign.ipa) |
| 1.6.0 | 10600 | 2025-03-03 | 13.0 | 37.04 MB (38,842,275 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.6.0/Kazumi_ios_1.6.0_no_sign.ipa) |
| 1.5.9 | 10509 | 2025-02-25 | 13.0 | 36.89 MB (38,683,704 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.9/Kazumi_ios_1.5.9_no_sign.ipa) |
| 1.5.8 | 10508 | 2025-02-19 | 13.0 | 36.88 MB (38,674,783 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.8/Kazumi_ios_1.5.8_no_sign.ipa) |
| 1.5.7 | 10507 | 2025-02-13 | 13.0 | 36.88 MB (38,668,054 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.7/Kazumi_ios_1.5.7_no_sign.ipa) |
| 1.5.6 | 10506 | 2025-02-08 | 13.0 | 36.82 MB (38,611,887 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.6/Kazumi_ios_1.5.6_no_sign.ipa) |
| 1.5.5 | 10505 | 2025-02-02 | 13.0 | 36.80 MB (38,590,388 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.5/Kazumi_ios_1.5.5_no_sign.ipa) |
| 1.5.4 | 10504 | 2025-01-26 | 13.0 | 36.69 MB (38,474,930 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.4/Kazumi_ios_1.5.4_no_sign.ipa) |
| 1.5.3 | 10503 | 2025-01-21 | 13.0 | 36.67 MB (38,455,538 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.3/Kazumi_ios_1.5.3_no_sign.ipa) |
| 1.5.2 | 10502 | 2025-01-16 | 13.0 | 36.63 MB (38,409,406 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.2/Kazumi_ios_1.5.2_no_sign.ipa) |
| 1.5.1 | 10501 | 2025-01-11 | 13.0 | 36.44 MB (38,213,255 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.1/Kazumi_ios_1.5.1_no_sign.ipa) |
| 1.5.0 | 10500 | 2025-01-04 | 13.0 | 36.44 MB (38,209,847 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.5.0/Kazumi_ios_1.5.0_no_sign.ipa) |
| 1.4.9 | 10409 | 2025-01-01 | 13.0 | 36.44 MB (38,211,105 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.9/Kazumi_ios_1.4.9_no_sign.ipa) |
| 1.4.8 | 10408 | 2024-12-25 | 13.0 | 36.38 MB (38,148,095 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.8/Kazumi_ios_1.4.8_no_sign.ipa) |
| 1.4.7 | 10407 | 2024-12-19 | 13.0 | 36.36 MB (38,127,057 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.7/Kazumi_ios_1.4.7_no_sign.ipa) |
| 1.4.6 | 10406 | 2024-12-13 | 13.0 | 36.32 MB (38,085,576 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.6/Kazumi_ios_1.4.6_no_sign.ipa) |
| 1.4.5 | 10405 | 2024-12-06 | 13.0 | 34.44 MB (36,112,149 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.5/Kazumi_ios_1.4.5_no_sign.ipa) |
| 1.4.4 | 10404 | 2024-11-23 | 13.0 | 31.90 MB (33,446,105 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.4/Kazumi_ios_1.4.4_no_sign.ipa) |
| 1.4.3 | 10403 | 2024-11-16 | 13.0 | 31.80 MB (33,341,370 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.3/Kazumi_ios_1.4.3_no_sign.ipa) |
| 1.4.2 | 10402 | 2024-11-09 | 13.0 | 31.74 MB (33,277,699 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.2/Kazumi_ios_1.4.2_no_sign.ipa) |
| 1.4.1 | 10401 | 2024-11-02 | 13.0 | 31.70 MB (33,237,080 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.1/Kazumi_ios_1.4.1_no_sign.ipa) |
| 1.4.0 | 10400 | 2024-10-25 | 13.0 | 31.68 MB (33,215,385 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.4.0/Kazumi_ios_1.4.0_no_sign.ipa) |
| 1.3.9 | 10309 | 2024-10-18 | 13.0 | 31.67 MB (33,212,466 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.3.9/Kazumi_ios_1.3.9_no_sign.ipa) |
| 1.3.8 | 10308 | 2024-10-18 | 13.0 | 31.67 MB (33,207,854 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.3.8/Kazumi_ios_1.3.8_no_sign.ipa) |
| 1.3.7 | 10307 | 2024-10-17 | 13.0 | 31.67 MB (33,211,333 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.3.7/Kazumi_ios_1.3.7_no_sign.ipa) |
| 1.3.6 | 10306 | 2024-10-10 | 13.0 | 31.64 MB (33,175,394 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.3.6/Kazumi_ios_1.3.6_no_sign.ipa) |
| 1.3.5 | 10305 | 2024-10-04 | 13.0 | 31.64 MB (33,172,651 bytes) | [下載](https://github.com/Predidit/Kazumi/releases/download/1.3.5/Kazumi_ios_1.3.5_no_sign.ipa) |

**版本說明：** - 优化截图交互 (#2599) (@Predidit) - 统一应用内下拉菜单样式 (@Predidit) - 修复大字体下番剧详情页追番按钮与其他按钮重叠而无法点击的问题 (#2622) (@Predidit) - 修复宽屏设置页重复点击已选中分类时二级页面重复嵌套的问题 (#2607) (@Predidit) - 修复鼠标悬停时播放器控制栏动画反复重启的问题 (@Predidit) - 修复分集评论标题栏显示多余副标题的问题 (@Predidit) - 其他UI改进 (@Predidit)

### 4. Aidoku

- **開發者：** Skitty
- **Bundle ID：** `app.aidoku.Aidoku`
- **副標題：** Skitty（2026-09-03）
- **分類：** entertainment
- **主題色：** `ff375f`
- **圖示：** https://aidoku.app/images/apple-touch-icon.png
- **功能／描述：** A free and open source manga reading application for iOS and iPadOS.
- **截圖：** https://aidoku.app/images/library.png · https://aidoku.app/images/source.png · https://aidoku.app/images/reader.png
- **來源內版本數：** 1
- **目前列出的版本：** 0.9（build 3）
- **最新列出的發布日期：** 2026-09-03
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.9 | 3 | 2026-09-03 | 15.0 | 14.05 MB (14,731,108 bytes) | [下載](https://github.com/Aidoku/Aidoku/releases/download/v0.9/Aidoku.ipa) |

**版本說明：** • OCR dictionary support (iOS 18+): import Yomitan•compatible dictionaries in the app and look up words while reading. • Suwayomi built•in source: read and track from a Suwayomi instance, just like Komga and Kavita. • Auto scroll for webtoon reader: enable and…（版本說明已節錄）

### 5. Photos Backup

- **開發者：** g8row
- **Bundle ID：** `com.g8row.photosbackup`
- **副標題：** g8row（2026-09-20）
- **分類：** other
- **主題色：** `#777777`
- **圖示：** https://raw.githubusercontent.com/g8row/PhotosBackup/main/App/Resources/Assets.xcassets/AppIcon.appiconset/AppIcon-1024.png
- **功能／描述：** ## New  - **The Google Photos app now counts what this app backs up.** ([#24](https://github.com/g8row/PhotosBackup/pull/24), thanks @saileshbro) Uploads showed as "not backed up" in the Google Photos app, and its own **Free up space** never offered them. It now recognises them, and its **Free up space** and **Delete from device** remove the photos from your iPhone. On one library of about 8,500 items, "Not backed up…（原始描述較長，已節錄）
- **來源內版本數：** 1
- **目前列出的版本：** 0.3.7
- **最新列出的發布日期：** 2026-09-20
- **最低 iOS：** 15.0

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 0.3.7 | 未提供 | 2026-09-20 | 15.0 | 2.59 MB (2,716,224 bytes) | [下載](https://github.com/g8row/PhotosBackup/releases/download/0.3.7/PhotosBackup.ipa) |

**版本說明：** ## New  - **The Google Photos app now counts what this app backs up.** ([#24](https://github.com/g8row/PhotosBackup/pull/24), thanks @saileshbro) Uploads showed as "not backed up" in the Google Photos app, and its own **Free up space** never offered them. It n…（版本說明已節錄）

### 6. AirCard-iOS

- **開發者：** Mak5er
- **Bundle ID：** `com.mak5er.aircard`
- **副標題：** Mak5er（2026-10-04）
- **分類：** utilities
- **主題色：** `#6750A4`
- **圖示：** https://raw.githubusercontent.com/Mak5er/AirCard-iOS/main/ios-app/Assets.xcassets/AppIcon.appiconset/AppIcon.png
- **功能／描述：** Customize Apple Wallet card artwork, passcode themes, and PosterBoard wallpapers on supported iOS versions.
- **來源內版本數：** 4
- **目前列出的版本：** 1.3.2（build v1.3.2）
- **最新列出的發布日期：** 2026-10-04

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 1.3.2 | v1.3.2 | 2026-10-04 | 未提供 | 4.42 MB (4,638,147 bytes) | [下載](https://github.com/Mak5er/AirCard-iOS/releases/download/v1.3.2/AirCard-iOS.ipa) |
| 1.3.1 | v1.3.1 | 2026-10-01 | 未提供 | 4.38 MB (4,597,510 bytes) | [下載](https://github.com/Mak5er/AirCard-iOS/releases/download/v1.3.1/AirCard-iOS.ipa) |
| 1.3 | v1.3 | 2026-09-20 | 未提供 | 4.25 MB (4,452,235 bytes) | [下載](https://github.com/Mak5er/AirCard-iOS/releases/download/v1.3/AirCard-iOS.ipa) |
| 1.2.5 | v1.2.5 | 2026-09-19 | 未提供 | 3.99 MB (4,180,858 bytes) | [下載](https://github.com/Mak5er/AirCard-iOS/releases/download/v1.2.5/AirCard-iOS.ipa) |

**版本說明：** ## What's Changed in v1.3.2 🚀  This update brings full feature parity with AirCard macOS v1.2.6, restores robust card discovery across all iOS versions, introduces automatic bank/network recognition with custom card nicknames, delivers an ultra-fast tunnel ca…（版本說明已節錄）

### 7. EnsWilde

- **開發者：** YangJiiii
- **Bundle ID：** `com.yangjiii.EnsWilde`
- **副標題：** YangJiiii（2026-02-25）
- **分類：** utilities
- **主題色：** `#6750A4`
- **圖示：** https://raw.githubusercontent.com/YangJiiii/EnsWilde/main/MyApp_Dark_1024.png
- **功能／描述：** An experimental on-device iOS customization app. Features and compatibility depend on the iOS version; back up your device before use.
- **來源內版本數：** 5
- **目前列出的版本：** 3.1.3（build EnsWilde3.1.3）
- **最新列出的發布日期：** 2026-02-25

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 3.1.3 | EnsWilde3.1.3 | 2026-02-25 | 未提供 | 12.96 MB (13,591,314 bytes) | [下載](https://github.com/YangJiiii/EnsWilde/releases/download/EnsWilde3.1.3/EnsWilde.ipa) |
| 3.1.2 | EnsWilde3.1.2 | 2026-02-01 | 未提供 | 12.98 MB (13,615,407 bytes) | [下載](https://github.com/YangJiiii/EnsWilde/releases/download/EnsWilde3.1.2/EnsWilde.ipa) |
| 3.1.1 | EnsWilde3.1.1 | 2026-01-22 | 未提供 | 12.94 MB (13,564,791 bytes) | [下載](https://github.com/YangJiiii/EnsWilde/releases/download/EnsWilde3.1.1/EnsWilde.ipa) |
| 3.1 | EnsWilde3.1 | 2026-01-19 | 未提供 | 12.70 MB (13,311,776 bytes) | [下載](https://github.com/YangJiiii/EnsWilde/releases/download/EnsWilde3.1/EnsWilde.ipa) |
| 3.0 | EnsWilde3.0 | 2026-01-18 | 未提供 | 12.18 MB (12,773,718 bytes) | [下載](https://github.com/YangJiiii/EnsWilde/releases/download/EnsWilde3.0/EnsWilde.ipa) |

**版本說明：** # EnsWilde v3.1.3  ## Updates - You can now download DDI, fully resolving all DDI-related issues (updated via Settings)  ## Features - Added an option to hide the Dynamic Island in Theme UI     *(A device restart is required for this feature to take effect)* -…（版本說明已節錄）

### 8. StikDebug

- **開發者：** StikDebug
- **Bundle ID：** `com.stik.stikdebug`
- **副標題：** StikDebug（2026-10-12）
- **分類：** other
- **主題色：** `#3B86F7`
- **圖示：** https://github.com/StikDebug/StikDebug/blob/main/assets/StikDebug.png?raw=true
- **功能／描述：** An on-device debugger and developer toolbox for iOS versions 17.4+ powered by idevice.  Note: Requires LocalDevVPN, cannot be natively used inside LiveContainer to enable JIT for the same LiveContainer.
- **截圖：** https://stikdebug.xyz/assets/source/home.png · https://stikdebug.xyz/assets/source/scripts.png · https://stikdebug.xyz/assets/source/settings.png
- **來源內版本數：** 1
- **目前列出的版本：** 3.1.14
- **最新列出的發布日期：** 2026-10-12
- **最低 iOS：** 17.4

**來源內所有版本紀錄**

| 版本 | Build | 發布日期 | 最低 iOS | 檔案大小 | 下載／版本連結 |
|---|---|---|---|---|---|
| 3.1.14 | 未提供 | 2026-10-12 | 17.4 | 12.92 MB (13,544,340 bytes) | [下載](https://github.com/StikDebug/StikDebug/releases/download/3.1.14/StikDebug-3.1.14.ipa) |

**版本說明：** Add Husk support  Full Changelog: https://github.com/StikDebug/StikDebug/compare/3.1.13...3.1.14

## 六、後續匯入與更新追蹤

| 工作項目 | 狀態 | 備註 |
|---|---|---|
| 逐項盤點 Moe AltStore | 已列入本文件 | 34 個 App |
| 逐項盤點 IPA Vault | 已列入本文件 | 63 個 App |
| 逐項盤點 AltGallery | 已列入本文件 | 43 個 App |
| 列出自己的兩個 Source 全部 App | 已列入本文件 | 15 個 App |
| 比對重複 App、Bundle ID、版本及 iOS 相容性 | 待處理 | 不應只因同名就視為同一 build；需核對 Bundle ID、下載檔與上游專案 |
| 決定要新增到 Chi Source 的項目 | 待確認 | 尚未修改 `apps.json` |
| **最後修改日期** | **2026-10-14** | 本文件本次更新日期 |
| **完成期限** | **待你指定** | 尚未自行設定截止日 |

## 資料與安全備註

- 版本日期是來源 JSON 所列日期，不一定等於上游專案最後 commit 日期。
- 下載連結可能失效，IPA 也可能被來源重新打包；正式匯入前應確認連結可用、簽署／安裝條件、最低 iOS 版本及 Bundle ID。
- 第三方修改版 App 的來源與完整性無法僅靠清單保證，應只匯入你信任且確實需要的項目。
