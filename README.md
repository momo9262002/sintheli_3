# Tâi-gí tī Sin-thé Lāi-té（台語佇身體內底）

互動式台語醫學／護理主題簡報與講義教材。

- **GitHub Pages**：https://momo9262002.github.io/sintheli_3/
- **GitHub Repository**：https://github.com/momo9262002/sintheli_3

## 檔案說明

| 檔案 | 說明 |
| --- | --- |
| `index.html` | GitHub Pages 入口頁面（與 `taigi_sintheli_slides.html` 同步） |
| `taigi_sintheli_slides.html` | 互動式網頁簡報主檔（支援白話字 / 漢羅切換與講者備忘錄） |
| `taigi_sintheli_print.html` | 簡報列印版頁面 |
| `taigi_sintheli_handout.md` | Markdown 格式講者與學員講義 |
| `ebook_qr.png` | Slide 7 電子冊 QR Code 圖片（電子冊由杜信龍老師製作） |
| `README.md` | 專案說明與修訂紀錄 |

---

## History Record（修訂紀錄）

### 2026-11-15
- **語詞、排版與講稿同步更新（四份教材同步）**
  - **全份教材**：將所有 `chhiūⁿ`／`Chhiūⁿ` 統一改為 `chhiōⁿ`／`Chhiōⁿ`；Slide 3 與 Slide 17「留言區 (`liû-giân-khu`)」改為「留話區 (`lâu-ōe-khu`)」。
  - **Slide 2**：「對病房看護到母語傳承」改為「對病房看護婦到母語傳承」（`Tùi Pēⁿ-pâng Khàn-hō͘-hū kàu Bó-gí Thoân-sêng`）。
  - **Slide 3**：放寬標題容器（`max-w-5xl`）並設定單行顯示，使「請佇留話區拍 1、2、3！敢知你 ê 身體講啥物話？」完整排在同一排。
  - **Slide 4**：「酸素／氧氣 (`Sàng-soh / Ióng-khì`)」移除「／氧氣 (` / Ióng-khì`)」，保留「酸素 (`Sàng-soh`)」。
  - **Slide 5**：全部「三餐」改為「三頓」（`Saⁿ-tǹg`）；全部「X 光 (`X-kng`)」改為「電光 (`tiān-kng`)」。
  - **Slide 6**：移除「少年」（`Siàu-liân `），改為「護理師若聽無『揻 (`ui`)』」。
  - **Slide 7**：放大杜信龍老師製作之電子冊 QR Code 並調整版面欄位比例（`5:7`），使右側說明與網址單行完整顯示。
  - **Slide 8（《身體理》解剖圖）**：
    - 移除全部 6 個器官項目中之「`臨床看護：`」與全羅「`Lîm-chhn̂g khàn-hō͘: `」前綴。
    - **頭殼佮腦髓**：移除 `(Náu-chhóe)` 與 `sîn-keng (náu-kun, náu-sòaⁿ)`；`tiān-sìn-sòaⁿ` 改為 `tiān-sòaⁿ`（電線）；「神智 (`sîn-chì`)」改為「意識 (`ì-sek`)」。
    - **心臟佮血脈**：「捒血流行全身」移除「行」，改為「捒血流全身」（`sak huih lâu choân-sin`）。
    - **腸肚佮脾胃**：古冊描寫改為「《身體理》：食道落胃，消化食物；小腸吸收養分，大腸排出大便。」
    - **腰子佮膀胱**：移除「腎臟 (`Sīn-chōng`)」；`su-jiō-kúng` 改回 1917 原書拼法 `su-jiō-kńg`；問診句後加上「下身 (`ē-sin`) 會刺刺 (`chhì-chhì`) 無？」。
    - **筋骨佮手節**：移除 `kun-bah`，統一保留 `kin-bah`。
  - **Slide 9（1917 內外科看護學 第 20 章）**：「查脈 (`chhâ me̍h`)」改為「看脈 (`khòaⁿ me̍h`)」；「用度針下佇舌下」改為「用度針 `khǹg` 佇舌下」。
  - **Slide 10（母語是上好 ê 安慰）**：加大 `Suh`／`Thò͘` 呼吸圓圈尺寸並置中文字，避免圓圈框線蓋住字元。
  - **Slide 11**：標題冒號後換行顯示（「當台語入去下一代 ê 喙內：<br/>兩 ê 囡仔笑詼，看見母語釘根」）。
  - **Slide 15 講稿**：新增 2025 超高齡社會與 2020 人口普查（65 歲以上長者主要使用台語比例達 65.9%）數據，以及學生分享想在開刀房當醫師以為不用講台語、卻忽略術前評估仍需與病人溝通的真實故事。
  - **Slide 17（結語 ＆ 提問）**：「台語毋免等破病才講」改為「台語毋是古董」（`Tâi-gí m̄ sī kó͘-tóng`）；「麥克風 (`be̍k-khek-hong`)」改為「聲音 (`siaⁿ-im`)」；移除「逐家定問 ê 問題（Q1～Q3）」問答卡片，改為置中醒目的放大字體 **`Q & A`** 與線頂交流邀請。

### 2026-11-14
- **GitHub 首次完整部署與 GitHub Pages 上線**（Commit `bfdd41f95cda55860492af4c5aa8dddc4776ffd6`）
  - 推送 `index.html`、`taigi_sintheli_slides.html`、`taigi_sintheli_print.html`、`taigi_sintheli_handout.md` 與 `ebook_qr.png` 至 `main` 分支，並透過 `main` `/ (root)` 部署至 GitHub Pages。
- **語詞與內容細部修訂（四份教材同步更新）**
  - **Slide 7**：新增電子冊 QR Code（`ebook_qr.png`），標註「電子冊由杜信龍老師製作」。
  - **身體部位與臨床用語調整**：
    - `腎臟（腰子）佮膀胱` 臨床看護改為「檢查敢有 `kōaⁿ chúi`」、移除 `(尿脬 jiō-pha)` 與 `hā jiō`（改為「放尿 (`pàng-jiō`)」）。
    - 調整 `kái-phò͘`、`su-jiō-kúng`、`kha-āu-teⁿ`、`kòe-hīⁿ-khang`、`去 teh 著`、`鬢邊一陣一陣 tiuh！`、`雙手共褲頭搝牢牢`、`有可能跋倒`、`體溫 ＆ 度針` 等用字，並移除「（原意）」、「（走精）」、「幫浦」、「按脈」、「體溫器／檢溫器」等字樣。
  - **Slide 10（半暝病房 ê 故事）**：
    - 將「機器叫無停」移至句首並改為「機器叫袂 soah」（`Ke-khì kiò bē soah`）。
    - 將「我顧佇遮喔」改為「有代誌會使 `ji̍h-lêng` 共我叫」（`ū tāi-chì ē-sái ji̍h-lêng kā góa kiò`）。
  - **Slide 11 & Slide 12（囡仔學台語笑詼）**：
    - 「兩則」改為「兩 ê」（`Nn̄g ê`）。
    - Slide 11 坎站 A 改為說明「中台發音分袂清 ê 誤會」：中語「糖」佮台語「蟲」發音分袂清，想欲討糖食，煞講做「欲食蟲」。
    - Slide 12 延伸一致敘述，並將情境畫面與插圖改為「營隊洗 ò-giô，囡仔欲加糖，毋過囡仔講：『老師，我欲食蟲！』」。
  - **Slide 14（三个坎站）**：
    - 「三則笑詼」改為「三 ê 笑詼」（`Saⁿ ê chhiò-khoe`）。
  - **Slide 15（結語）**：
    - `po-lê-chhiûⁿ` 改為 `po-lê-chhiôⁿ`。
  - **Slide 16（生活日常對話）**：
    - 移除「來食糖 (`chia̍h-thn̂g`) 喔！」（`“Lâi chia̍h-thn̂g--o͘h!”`）。
- **新增 `README.md`**
  - 建立專案說明與修訂歷史紀錄。
