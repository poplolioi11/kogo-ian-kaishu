# 庚午醫案會集（RB00002360） / Kōgo ian kaishū: Transcription Dataset

底本為京都大學附屬圖書館富士川文庫藏抄本 RB00002360，索書號 コ/148。京都大學附屬圖書館富士川文庫藏一冊和裝中本抄本。館目題為「庚午医案会集」，卷首原題「庚午醫案會集」。 [館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00002360) · [館藏 IIIF](https://rmda.kulib.kyoto-u.ac.jp/iiif/metadata_manifest/RB00002360/manifest.json)

《庚午醫案會集》是一冊日本醫案手抄本，分上下卷。卷首由帶日期的「宿題」開始，案文用漢字與片假名夾寫。卷中可見方名與「評曰」相接，呈現病例敘述、處方與評語的編排。這冊可用於比較歷史上的日本醫案書寫及醫學教學中的病例討論。本資料集以京都大學附屬圖書館富士川文庫藏抄本 RB00002360 為底本，共取 21 幅固定影像，其中 19 幅用於轉錄正文，提供 JSON、TXT、TEI 和逐項覆核紀錄。此版為 AI 校讀稿，1395 項比對中原有 594 項未解。人工全文二校待完成。

Kōgo ian kaishū is a Japanese manuscript of medical cases in two parts bound as one volume. It opens with a dated assignment and records cases in a mixture of kanji and katakana. Formula names accompanied by passages introduced as comments show how case narratives, prescriptions and criticism were arranged. The manuscript offers evidence for the study of case writing and case-based medical instruction in historical Japan. This dataset uses 21 fixed images from the Fujikawa Collection, Kyoto University Main Library, record RB00002360. The main text is transcribed from 19 pages. The AI-reviewed JSON, TXT and TEI transcription records 594 unresolved comparison items from the primary review. Full human collation is outstanding.

館目未著錄撰者或抄成年。卷首可見入藏章日期「大正7.3.31」（1918 年 3 月 31 日）及登錄號 184782。 [京都大學館目](https://rmda.kulib.kyoto-u.ac.jp/item/rb00002360)

[p002 左面右側卷首題名、日期小題與上端入藏章](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002360%2FRB00002360_00002_0.ptif/full/2000,/0/default.jpg) · [p012 右面方名、評語及近書口上卷終題](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002360%2FRB00002360_00012_0.ptif/full/2000,/0/default.jpg) · [p020 右面近書口下卷終題](https://rmda.kulib.kyoto-u.ac.jp/iiif/3/RB00002360%2FRB00002360_00020_0.ptif/full/2000,/0/default.jpg)

## 資料與校讀

- data/document.json 保留歷史文字、原圖位置、疑讀與缺口。
- data/text.txt 與 data/text.tei.xml 為全文與 TEI，附文字單位的對應檔。
- data/review.json 保留 1395 項比對、594 項原裁定未解、補充回圖後仍待確認的 594 項及採用紀錄。
- data/manifest.json 與 PACKAGE-SHA256SUMS.txt 記錄固定發行的檔案雜湊。

底本為同一冊的 21 幅 IIIF 影像，包含書衣、上下卷正文及卷末。稿本的漢字、片假名、題署、日期與評語依圖面位置轉錄。

The source consists of 21 IIIF images of one physical volume, including the covers, the text of both parts and their closing statements. The transcription follows the location of kanji, katakana, headings, dates and comments in the source images.

初錄與第二路讀稿各以同一批固定原圖為據。Claude 完成第 1–21 幅初錄與第 1–21 幅第二路讀稿。Claude 依原圖覆核 119 項比對。Codex 依原圖覆核 1276 項比對。程式列出的 1395 項比對均有逐項紀錄。採入 59 項有影像依據的更正，保留未解位置與候選。另有 96 項異讀保留原讀及候選。程式驗收確認公開 JSON、TXT 和 TEI 的逐欄內容一致。TEI 通過 P5 4.12.0 Relax NG。人工全文二校、專家審定和準確率量測待完成。

The two independent readings used the same fixed source images. Claude produced the first reading for images 1–21 and the second reading for images 1–21. Claude reviewed 119 comparison items against the images. Codex reviewed 1276 comparison items against the images. The dataset records 1395 comparison items. The edition incorporates 59 corrections supported by the images. The initial readings and alternatives remain recorded for 96 further proposed changes. Automated validation confirmed that the transcription content agrees column by column across JSON, TXT and TEI. The TEI passed P5 4.12.0 Relax NG validation. Full human collation, expert assessment and accuracy measurement are outstanding.

## 權利與引用

京都大學公告原資料保護期已滿及所藏圖像二次利用條件。新增且受著作權保護的說明與整理編排採 CC BY 4.0。 [權利說明](LICENSE.md)

曲宸宇（Chu, Chen-Yu）。2026。庚午醫案會集（RB00002360） / Kōgo ian kaishū: Transcription Dataset。v0.1.0。資料集。 [固定發行](https://github.com/poplolioi11/kogo-ian-kaishu/releases/tag/v0.1.0) · [ORCID](https://orcid.org/0009-0003-9738-6914)
