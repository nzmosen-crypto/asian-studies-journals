# 亞洲與亞美研究期刊 · 最新一期 / Asian & Asian American Studies Journals — Latest Issues

每月自動抓取 26 本英語亞洲研究與亞美研究期刊的最新一期目錄與摘要，發佈成公開網頁與 RSS。
Every month this repository collects the latest-issue tables of contents (with abstracts) of 26 English-language Asian studies and Asian American studies journals and publishes them as a web page and an RSS feed.

## 訂閱 / Subscribe

- **網頁 / Web page**：本 repo 的 GitHub Pages（Settings → Pages 顯示網址）
- **RSS**：網頁網址後加 `feed.xml`。加到 Feedly、Inoreader 等閱讀器，任一期刊出新一期就會收到一則。
- **Email**：把 RSS 網址貼到 Blogtrottr、Feedrabbit 等免費 RSS-to-email 服務。

## 期刊 / Journals (`journals.csv`)

選刊條件：英語、同儕審查；SCImago (SJR) Q1，或在亞洲研究／亞美研究領域公認具學術聲望（例如 *Verge*、*Harvard Journal of Asiatic Studies*）。
Selection: English-language, peer-reviewed; SJR Q1 or widely recognised as leading in Asian / Asian American studies (e.g. *Verge*, *HJAS*).

- 亞洲研究 19 本：綜合（JAS、*positions*、MAS、Inter-Asia Cultural Studies、Critical Asian Studies、JCA、Asian Studies Review、Pacific Affairs、HJAS）；中國（China Quarterly、China Journal、Modern China、*Prism*）；台灣（IJTS）；日本（JJS、Japan Forum）；韓國（JKS）；東南亞（JSEAS）；南亞（*South Asia*）。
- 亞美／全球亞洲研究 7 本：*Verge*、JAAS、*Amerasia*、ADVA、J. American Ethnic History、MELUS、Asian American J. of Psychology。
- 已查得的 SJR 分級記在 `sjr_note` 欄（2026 年 11 月）。人文類期刊（如 HJAS、*Amerasia*）引用率低，SJR 分級偏低，但為領域核心刊物。

## 資料來源 / Data sources

Crossref；摘要由 OpenAlex 補齊。部分出版社登記期別較慢，新文章會列在「Online first」。

## 修改 / Editing

- 增刪期刊：編輯 `journals.csv`，存檔後會自動重跑。
- 手動執行：Actions → *Update Asian studies journals* → Run workflow。
- 寄信給自己（選用）：在 Settings → Secrets → Actions 加 `GMAIL_USER`、`GMAIL_APP_PASSWORD`、`MAIL_TO`。
