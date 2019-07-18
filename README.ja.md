# 🚀 アポロ 11 号

[![NASA][1]][2]

:crossed_flags:
[Bahasa Indonesia][id],
[Català][ca],
[Deutsch][de],
[English][en],
[Español][es],
[Français][fr],
[Italiano][it],
[Português][pt_br],
[Русский][ru],
[العربية][ar],
[हिंदी][hi_in],
[正體中文][zh_tw],
[简体中文][zh_cn],
[한국어][ko_kr],
**日本**

[ar]: README.ar.md
[id]: README.id.md
[ca]: README.ca.md
[de]: README.de.md
[en]: README.md
[es]: README.es.md
[it]: README.it.md
[fr]: README.fr.md
[ja]: README.ja.md
[pt_br]: README.pt_br.md
[zh_tw]: README.zh_tw.md
[zh_cn]: README.zh_cn.md
[ko_kr]: README.ko_kr.md
[hi_in]: README.hi_in.md
[ru]: README.ru.md

司令船・機械船(Comanche055)および月着陸船(Luminary099)用のオリジナルのアポロ 11 号誘導コンピュータ(AGC)のソースコード。
[Virtual AGC][3] と [MIT Museum][4] によってデジタル化された。
このリポジトリは、オリジナルのアポロ 11 号のソースコードを完全に再現して保管することを目的としています。
そのため、このリポジトリと [Luminary 099][5] および [Comanche 055][6] の間に発見された問題や見落としがある可能性のあるファイルに対しての PR は歓迎します。

## 貢献

プルリクエストを開く前に [CONTRIBUTING.md][7] をお読みください。

## コンパイル

もしコンパイルをご希望の場合 [Virtual AGC][8] を確認してください。

## 権限

| &nbsp;       | &nbsp;                                                                                                                                                                                           |
| :----------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 著作権       | パブリックドメイン                                                                                                                                                                               |
| Comanche055  | アポロ 11 号用の司令船・機械船用のアポロ 11 号誘導コンピュータ、Colossus 2A のソースコードの一部<br>`Assemble revision 055 of AGC program Comanche by NASA`<br>`2021113-051. 10:28 APR. 1, 1969` |
| Luminary099  | アポロ 11 号用の月着陸船用のアポロ 11 号誘導コンピュータ、Luminary 1A のソースコードの一部<br>`Assemble revision 001 of AGC program LYM99 by NASA`<br>`2021112-061. 16:27 JUL. 14, 1969`         |
| アセンブラ   | yaYUL                                                                                                                                                                                            |
| コンタクト   | Ron Burkey <info@sandroid.org>                                                                                                                                                                   |
| ウェブサイト | www.ibiblio.org/apollo                                                                                                                                                                           |
| デジタル化   | このソースコードは、MIT Museum からハードコピーをデジタル化、移したものです。 デジタル化は Paul Fjeld によって行われ, Deborah Douglas がまとめました。                                           |

### 契約と承認

- [CONTRACT_AND_APPROVALS.agc] から派生\*

本アポロ誘導コンピュータプログラムは、コロッサス 2A から参照されます。

このプログラムは、 `R-577` に指定された司令船モジュールに使用されます。 このプロジェクトは、DSR project `55-23870` の元で準備され、NASA の有人宇宙船センターが MIT 機械研究所との `NAS 9-4065` 契約により始まりました。

| Submitted by         | Role                                                  | Date               |
| :------------------- | :---------------------------------------------------- | :----------------- |
| Margaret H. Hamilton | コロッサス プログラミングリーダー<br>アポロ誘導と航海 | 1969 年 3 月 28 日 |

| Approved by       | Role                                                                   | Date               |
| :---------------- | :--------------------------------------------------------------------- | :----------------- |
| Daniel J. Lickly  | ディレクター, ミッションプログラムの開発<br>アポロ誘導と航法プログラム | 1969 年 3 月 28 日 |
| Fred H. Martin    | コロッサス プロジェクトマネージャー<br>アポロ誘導と航法プログラム      | 1969 年 3 月 28 日 |
| Norman E. Sears   | ディレクター, ミッションプログラムの開発<br>アポロ誘導と航法プログラム | 1969 年 3 月 28 日 |
| Richard H. Battin | ディレクター, ミッションプログラムの開発<br>アポロ誘導と航法プログラム | 1969 年 3 月 28 日 |
| David G. Hoag     | ディレクター<br>アポロ誘導と航法プログラム                             | 1969 年 3 月 28 日 |
| Ralph R. Ragan    | 副ディレクター<br>機械研究所                                           | 1969 年 3 月 28 日 |

[contract_and_approvals.agc]: https://github.com/chrislgarry/Apollo-11/blob/master/Comanche055/CONTRACT_AND_APPROVALS.agc
[1]: https://rawcdn.githack.com/aleen42/badges/c9246f74/src/nasa.svg
[2]: https://www.nasa.gov/mission_pages/apollo/missions/apollo11.html
[3]: http://www.ibiblio.org/apollo/
[4]: http://web.mit.edu/museum/
[5]: http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[6]: http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[7]: https://github.com/chrislgarry/Apollo-11/blob/master/CONTRIBUTING.md
[8]: https://github.com/rburkey2005/virtualagc
