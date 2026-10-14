# App 清單與新增追蹤（add.md）

> 資料快照：2026-10-14（UTC+8）  
> 用途：集中列出 Chi Source 與 Chi Source Personal 目前收錄的 App，以及本次指定的三個 App，方便後續核對版本與安排更新。  
> **注意：本文件只記錄清單與追蹤資訊，不會自動改動 apps.json，也不代表已將 Personal Source 的 App 搬到 Chi Source。**

## 本次指定的三個 App

| App | Bundle ID | 目前版本 | 上游版本日期 | 來源最後檢查／更新日期 | 上游專案 |
| --- | --- | --- | --- | --- | --- |
| Photos Backup | `com.g8row.photosbackup` | 0.3.7 | 2026-09-20 | 2026-10-14 | [g8row/PhotosBackup](https://github.com/g8row/PhotosBackup) |
| AirCard-iOS | `com.mak5er.aircard` | 1.3.2 | 2026-10-04 | 2026-10-14 | [Mak5er/AirCard-iOS](https://github.com/Mak5er/AirCard-iOS) |
| EnsWilde | `com.yangjiii.EnsWilde` | 3.1.3 | 2026-02-25 | 2026-10-14 | [YangJiiii/EnsWilde](https://github.com/YangJiiii/EnsWilde) |

## Chi Source 現有 App

來源：[`tsai97216/chi-source`](https://github.com/tsai97216/chi-source)  
Source URL：[`https://ipa.chi.qzz.io`](https://ipa.chi.qzz.io)  
README 顯示最近自動檢查：2026-10-14 19:12（UTC+8）。

| App | Bundle ID | 目前收錄版本 | 上游版本日期 | 上游專案／來源 |
| --- | --- | --- | --- | --- |
| PiliPlus | `com.bgg.piliplus` | 2.1.6.2 | 2026-10-10 | [bggRGjQaUbCoE/PiliPlus](https://github.com/bggRGjQaUbCoE/PiliPlus) |
| YTKACE | `com.google.ios.youtube` | 21.41.5 | 2026-10-11 | [itzzace/ytkace](https://github.com/itzzace/ytkace) |
| MaxMusic | `com.google.ios.youtubemusic` | 9.34.4 | 2026-08-30 | [Mark02-2012/YTMUltimatePLUS](https://github.com/Mark02-2012/YTMUltimatePLUS) |
| Facebook | `com.facebook.Facebook` | 582.0.0 | 2026-10-09 | [IPA Vault](https://github.com/927tx/IPA-Vault) |
| Threads | `com.burbn.barcelona` | 451.0 | 2026-10-13 | [IPA Vault](https://github.com/927tx/IPA-Vault) |
| Instagram | `com.burbn.instagram` | 433.0.0 | 2026-06-10 | [AppTesters](https://github.com/apptesters-org/AppTesters_Repo) |
| EeveeSpotify Reincarnated | `com.spotify.client.patched` | 9.1.88 | 2026-10-05 | [SideloadLabs/SideloasLabs-AltSource](https://github.com/SideloadLabs/SideloasLabs-AltSource) |

## Chi Source Personal 現有 App

來源：[`tsai97216/chi-source-personal`](https://github.com/tsai97216/chi-source-personal)  
Source URL：[`https://ipap.chi.qzz.io`](https://ipap.chi.qzz.io)  
README 顯示最近自動檢查：2026-10-14 20:08（UTC+8）。

| App | Bundle ID | 目前收錄版本 | 上游版本日期 | 上游專案／來源 |
| --- | --- | --- | --- | --- |
| SpooferPro Pokemon GO | `com.nianticlabs.pokemongo` | 0.431.1（build 0.736） | 2026-10-12 | [SpooferPro](https://spooferpro.com) |
| Animeko | `org.animeko.animeko` | 6.3.0 | 2026-10-13 | [openani/ani-altstore-source](https://github.com/maxchang3/ani-altstore-source) |
| Kazumi | `com.example.kazumi` | 2.3.8 | 2026-10-07 | [ChouChiu/Kazumi-AltStore-Source](https://github.com/ChouChiu/Kazumi-AltStore-Source) |
| Aidoku | `app.aidoku.Aidoku` | 0.9 | 2026-09-03 | [Aidoku/Aidoku](https://github.com/Aidoku/Aidoku) |
| Photos Backup | `com.g8row.photosbackup` | 0.3.7 | 2026-09-20 | [g8row/PhotosBackup](https://github.com/g8row/PhotosBackup) |
| AirCard-iOS | `com.mak5er.aircard` | 1.3.2 | 2026-10-04 | [Mak5er/AirCard-iOS](https://github.com/Mak5er/AirCard-iOS) |
| EnsWilde | `com.yangjiii.EnsWilde` | 3.1.3 | 2026-02-25 | [YangJiiii/EnsWilde](https://github.com/YangJiiii/EnsWilde) |
| StikDebug | `com.stik.stikdebug` | 3.1.14 | 2026-10-12 | [StephenDev0/StikDebug](https://github.com/StephenDev0/StikDebug) |

## 後續更新追蹤

- [ ] 核對本文件所列版本是否仍為上游最新版本。
- [ ] 評估 Photos Backup、AirCard-iOS、EnsWilde 是否需要同時收錄於 Chi Source；目前三者已列於 Chi Source Personal。
- [ ] 若決定跨來源收錄，先確認 Bundle ID 重複、安裝覆蓋與 AltStore 顯示行為，再修改來源 JSON。
- [ ] 更新版本時同步記錄版本號、上游發布日期、實際檢查日期及下載來源。
- **最後修改日期：** 2026-10-14
- **完成期限：** 尚未指定；確認後再填入，避免自行設定截止日。
