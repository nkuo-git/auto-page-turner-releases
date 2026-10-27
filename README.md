# 自動翻譜

會聽你彈琴、自動翻頁的樂譜 App（鋼琴、吉他）。這裡只放發布檔。

- **Android**：到 [Releases → latest](https://github.com/nkuo-git/auto-page-turner-releases/releases/latest) 下載 `auto-page-turner.apk` 安裝（需允許「安裝不明來源的應用程式」）。之後 App 內會自己提示更新。
- **iPhone／iPad**：用 Safari 打開 https://nkuo-git.github.io/auto-page-turner-releases/ ，按「分享 → 加入主畫面」。

樂譜辨識用的是 [Audiveris](https://github.com/Audiveris/audiveris)（AGPL-3.0）。我們對它的修改在每個 release 的 `audiveris-changes.tar.gz` 裡（`server/audiveris/patch.sh` 套在 Audiveris 5.11.0 上，`server/Dockerfile` 是編譯方式）。

這個 repo 的內容（`latest` release 和 `gh-pages` 分支）由主程式的 GitHub Actions 自動更新，請不要手動修改。
