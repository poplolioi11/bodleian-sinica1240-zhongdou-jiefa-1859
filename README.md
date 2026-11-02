# 種痘捷法（1859；Bodleian Sinica 1240） / zhong dou jie fa: Transcription dataset

## 摘要 / Abstract

《種痘捷法》（zhong dou jie fa）是帶咸豐九年（1859）刊記的中文種痘小冊，由博濟醫局刊行，館目歸於 John Glasgow Kerr（J. G. Kerr）。其種痘論述、醫局刊記與醫士題署，可供研究晚清種痘知識的中文傳播、醫療機構出版與醫學印刷文化。v0.2.0 依 Bodleian Sinica 1240 的 8 幅影像轉錄 9 個原印文字面，提供 TXT、JSON、TEI XML 與官方影像來源對應。文字為 AI 暫定轉錄，未經人類全文雙校或專家審定。

Zhong dou jie fa (種痘捷法) is a Chinese vaccination pamphlet bearing an 1859 imprint, published by 博濟醫局 (Boji Medical Institution) and attributed in the Bodleian catalogue to John Glasgow Kerr (J. G. Kerr). Its medical discourse, institutional imprint and physician’s signature provide material for studying the circulation of knowledge in Chinese and late Qing medical print culture. Version 0.2.0 transcribes nine original-print text faces across eight images of Bodleian Sinica 1240, providing TXT, JSON and TEI XML with references to the official source images. The text is a provisional AI transcription without human double collation or expert review.

原件與書目入口 / Source witness and catalogue:

- [館藏原件 / Source witness](https://digital.bodleian.ox.ac.uk/objects/657cb8d8-0323-48b5-9053-566eccc6421a/)
- [館藏書目 / Catalogue](https://east-asian.bodleian.ox.ac.uk/catalog/volume_944)
- [IIIF manifest](https://iiif.bodleian.ox.ac.uk/iiif/manifest/657cb8d8-0323-48b5-9053-566eccc6421a.json)
- [館方固定書目 XML / Fixed official catalogue XML](https://github.com/bodleian/east-asian-mss/blob/c177d5a6db8585168b744d38a6bff02186d1968f/collections/chinese/Sinica%201240.xml)

**v0.2.0｜AI獨立影像校讀及主代理回圖裁定，保留9筆未解疑讀；尚未人類雙校或專家審定。**

整理者：曲宸宇（Chu, Chen-Yu；GitHub：poplolioi11；[ORCID](https://orcid.org/0009-0003-9738-6914)）。本資料是1859年博濟醫局《種痘捷法》的醫學史文獻數位化成果，供原文檢索、引用、來源對照與後續校訂。歷史作者與現代整理者分開；不代表館方背書。用途限醫學史文獻數位化，未進行生物研究、實驗或提供現代操作指引。

底本為Bodleian Libraries Sinica 1240，題頁本版讀作「咸豐九年新鋟」。8影像幀含10內頁物理面，其中9面有歷史原印字；幀數不是葉數。p02透印不重錄，封面及現代館藏注記只描述；未見版心字不補，未見清晰獨立圖式不補畫。

原初錄69欄／題署全部已比較；另有15筆實見版心與頁碼，共84單位、1189個Unicode碼點。39個既有單位字串變動，含字形與原刻點位置訂正，不等於39個錯字。9筆疑讀含字形、附筆與刻點位置爭議，原理由及候選保留；不以通行語句覆蓋底本字形。[訂正](CORRECTIONS.json) · [校讀摘要](COLLATION.md)。

- [TXT](book.txt)：`〔unit:...〕`為現代導航，非原文。
- [JSON](book.json)／[TEI](book.tei.xml)：原單位ID、層別、字串與順序可相互對照；無字形級bbox。
- [疑讀](uncertainties.json)、[來源](source-pages.json)、[驗證](VALIDATION.json)、[權利](RIGHTS.md)、[引用](CITATION.cff)。

兩批獨立Gemini影像讀字實際模型為gemini-3.8-flash-high，各批3圖，合計6幅讀字影像；再依固定影像裁定原字形與原刻點。原生Codex實際細分型號未回報，保持未知；私有三維追溯因此仍標incomplete。未經人類雙校、專家審定或同儕審查，沒有量測逐字準確率。格式、DOI與模型一致不能證明讀字無誤。

初錄v0.1.0及[其DOI](https://doi.org/10.5281/zenodo.23870178)保留；本版另行封存，不覆寫初錄。本版已於2026-11-02正式發布：[Zenodo v0.2.0](https://doi.org/10.5281/zenodo.23870679) · [GitHub Release](https://github.com/poplolioi11/bodleian-sinica1240-zhongdou-jiefa-1859/releases/tag/v0.2.0)。公開檔案已匿名下載並核對SHA-256。封存包及固定標籤保留建立當下的「預留／候選」文字，不覆寫歷史版本；此主分支說明反映上架後狀態。

原文、異體與原刻點編碼照固定裁定稿保存；不新增現代句讀。歷史文字、自有原創說明與館藏影像分層權利；本包不含掃描、裁片、技能、提示或私有程式，也不提供從原圖完整重跑方法。引用請附版本、單位ID與官方原頁。

## English summary

An independently AI-read and source-adjudicated transcription of the 1859 Chinese medical-history booklet *Zhong dou jie fa*, Bodleian Sinica 1240. All 69 column/title units were compared, with 15 observed running-title/page-number units retained separately. Thirty-nine unit strings changed; nine located uncertainties remain. Eight source frames cover ten interior physical faces, nine with historical print. This is a provisional historical-document research aid, without human double collation, expert review or measured accuracy. Source scans and private processing materials are excluded. The first transcription remains separately citable.

Keywords: 種痘捷法; Sinica 1240; 博濟醫局; 醫學史; 清代醫籍; 傳教醫療史; 醫學印刷史; history of medicine; Chinese medical texts; medical missions history; medical print culture; Qing dynasty; digital humanities; AI-assisted transcription; TEI XML; 1859.

已發布版本 DOI： https://doi.org/10.5281/zenodo.23870679
