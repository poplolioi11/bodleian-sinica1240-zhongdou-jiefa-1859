# 種痘捷法 · Bodleian Sinica 1240

## 摘要 / Abstract

本資料以牛津大學 Bodleian Libraries 藏 Sinica 1240《種痘捷法》（1859，博濟醫局刊本）為底本，將歷史文獻轉錄與來源影像連結，供醫學史檢索、定位、引用及後續訂正。v0.2.0 以獨立 AI 讀稿比較初錄，再回圖修訂，涵蓋 8 幅影像中的 9 個原印文字面，共 84 單位、1,189 個 Unicode 碼點，保留 9 筆疑讀或記號問題。公開 TXT、JSON、TEI XML 及訂正資料；成果仍屬未經人類雙校的 AI 轉錄，僅供歷史文獻研究。

This dataset links a transcription of Zhong dou jie fa (1859, Boji Medical Institution edition), Bodleian Libraries Sinica 1240, to its source images for research in medical history, discovery, citation and further correction. Version 0.2.0 compares the initial transcription with independent AI readings and revises it against the images. It covers nine original-print text faces across eight source frames, comprising 84 units and 1,189 Unicode code points, with nine unresolved reading or mark records. Public TXT, JSON, TEI XML and correction data support reuse; the text remains an AI transcription without human double collation and is intended for historical-document research.

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
