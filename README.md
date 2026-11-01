# 亞洲與亞美研究期刊 · 最新一期 / Asian & Asian American Studies Journals — Latest Issues

每月自動抓取 47 本亞洲研究、亞美研究與歷史學期刊（40 本英文、7 本臺灣中文期刊）的最新一期目錄與摘要，發佈成公開網頁與 RSS。
Every month this repository collects the latest-issue tables of contents (with abstracts) of 47 Asian studies, Asian American studies and history journals (40 in English, 7 Taiwanese journals in Chinese) and publishes them as a web page and an RSS feed.

## 訂閱 / Subscribe

- **網頁 / Web page**：本 repo 的 GitHub Pages（Settings → Pages 顯示網址）
- **RSS**：網頁網址後加 `feed.xml`。加到 Feedly、Inoreader 等閱讀器，任一期刊出新一期就會收到一則。
- **Email**：把 RSS 網址貼到 Blogtrottr、Feedrabbit 等免費 RSS-to-email 服務。

## 期刊 / Journals (`journals.csv`)

選刊條件：同儕審查；英文期刊為 SCImago (SJR) Q1，或在亞洲研究／亞美研究／歷史學領域公認具學術聲望（例如 *Verge*、*Harvard Journal of Asiatic Studies*）；中文期刊為臺灣人文學核心期刊（THCI）中的重要史學與文化研究期刊。
Selection: peer-reviewed; English journals are SJR Q1 or widely recognised as leading in Asian / Asian American studies or history; Chinese journals are leading Taiwanese (THCI core) history and cultural studies journals.

- 亞洲研究 20 本：綜合（JAS、*positions*、MAS、Inter-Asia Cultural Studies、Critical Asian Studies、JCA、Asian Studies Review、Pacific Affairs、HJAS）；中國（China Quarterly、China Journal、Modern China、*Prism*、MCLC）；台灣（IJTS）；日本（JJS、Japan Forum）；韓國（JKS）；東南亞（JSEAS）；南亞（*South Asia*）。
- 亞美／全球亞洲研究 7 本：*Verge*、JAAS、*Amerasia*、ADVA、J. American Ethnic History、MELUS、Asian American J. of Psychology。
- 歷史學（英文）13 本：一般史（*American Historical Review*、*Past & Present*、*Journal of American History*、CSSH、*Journal of World History*、*Journal of Global History*）；亞洲史與亞美史（*Pacific Historical Review*、*Late Imperial China*、*Twentieth-Century China*、*Journal of Chinese History*、*Monumenta Nipponica*、JESHO、*Indian Economic and Social History Review*）。
- 中文 7 本：《臺灣史研究》、《新史學》、《中央研究院近代史研究所集刊》、《中央研究院歷史語言研究所集刊》、《漢學研究》、《臺大歷史學報》、《文化研究》。
- 已查得的 SJR 分級記在 `sjr_note` 欄（2026 年 11 月）。人文類期刊（如 HJAS、*Amerasia*）引用率低，SJR 分級偏低，但為領域核心刊物。

## 資料來源 / Data sources

Crossref、OpenAlex（英文；摘要由 OpenAlex 補齊）；《新史學》官網 newhistory.org.tw；其他中文期刊用月旦知識庫 lawdata.com.tw 公開目錄頁（通常比期刊官網晚一期左右）。部分出版社登記期別較慢，新文章會列在「Online first」。

## 修改 / Editing

- 增刪期刊：編輯 `journals.csv`，存檔後會自動重跑。
- 手動執行：Actions → *Update Asian studies journals* → Run workflow。
- 寄信給自己（選用）：在 Settings → Secrets → Actions 加 `GMAIL_USER`、`GMAIL_APP_PASSWORD`、`MAIL_TO`。
