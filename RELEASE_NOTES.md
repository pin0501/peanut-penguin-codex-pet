# 2026-09-15 翅膀與跳躍大小修正

- 第三排左跑：從完整的右跑影格逐格鏡像，修復翅膀斷裂、分離翅尖與直線截斷，保留八格順序。
- 第五排跳躍：所有五格共用 1.075 倍等比例放大，頭身與五官一起恢復至原始不動版的大小。縮短垂直位移，讓完整頭頂與腳掌留在每格內。
- 修正後跳躍各格實體高度為 190–192 像素，不動基準為 191 像素；每格均無碰到裁切邊界。
- 其他九排與安裝前備份逐像素相同。
- 這次修正屬於現有影格的切格、鏡像與尺寸配置，沒有重新生成角色插畫。

下載包內只有可安裝資料夾及 pet.json、spritesheet.webp。覆蓋舊版後，重新載入或重新選擇 Peanut Penguin。

---

# Peanut Penguin — 首次公開版本

可下載並安裝的 Codex 桌面寵物，以 Jellycat Peanut Penguin 鑰匙圈版為原型，採用柔和插畫風格與少量毛絨筆觸。

- 完整 v2 圖集：九組動作、十六個注視方向。
- 已依原始不動影格修正左右跑的頭身比與五官、腳掌比例。
- 提供寵物素材 ZIP、透明背景主圖與動畫預覽。

下載本次發行的 `peanut-penguin-codex-pet.zip`，解壓縮後將 `peanut-penguin-illustrated` 資料夾放入 Codex 的 `pets` 目錄。預設為 Windows 的 `%USERPROFILE%\.codex\pets\`，或 macOS/Linux 的 `~/.codex/pets/`；自訂 `CODEX_HOME` 時請使用該目錄下的 `pets`。

在 **設定 → 寵物** 重新整理，選擇 **Peanut Penguin** 並喚醒。完整說明與預覽見 [專案首頁](https://github.com/pin0501/peanut-penguin-codex-pet)。

AI 協助繪製的非官方 fan art。原型：[Jellycat Peanut Penguin Bag Charm](https://jellycat.com/peanut-penguin-bag-charm/)。非 Jellycat 或 OpenAI 官方作品。
