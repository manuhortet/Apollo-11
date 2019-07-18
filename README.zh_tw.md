# 🚀 阿波羅 11 號

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
**正體中文**,
[简体中文][zh_cn],
[한국어][ko_kr]

[ar]: README.ar.md
[id]: README.id.md
[ca]: README.ca.md
[de]: README.de.md
[en]: README.md
[es]: README.es.md
[it]: README.it.md
[fr]: README.fr.md
[pt_br]: README.pt_br.md
[zh_tw]: README.zh_tw.md
[zh_cn]: README.zh_cn.md
[ko_kr]: README.ko_kr.md
[hi_in]: README.hi_in.md
[ru]: README.ru.md

最初用於阿波羅 11 號的導航電腦 (Apollo 11 Guidance computer, AGC) 裡頭駕駛艙 (Comanche055) 和登月艙 (Luminary099) 的原始程式碼，由 [Virtual AGC](http://www.ibiblio.org/apollo/) 及 [MIT Museum](http://web.mit.edu/museum/) 的工作人員進行數位化，著眼於建立阿波羅 11 號原始程式碼的封存。正因如此，若您發現文件抄錄或於查看 [Luminary 099](http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/) 和 [Comanche 055](http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/) 這兩部分原始程式碼過程中遇到問題的話，歡迎提交 pull request。當然，也包括那些我可能遺忘的檔案。

## 編譯

若您對編譯原始程式碼有興趣，請見 [Virtual AGC](https://github.com/rburkey2005/virtualagc) 。

## 資訊和專案屬性

| &nbsp;      | &nbsp;                                                                                                                                                                                                          |
| :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 授權聲明    | 公有領域 (Public domain)                                                                                                                                                                                        |
| Comanche055 | Part of the source code for Colossus 2A, the Command Module's (CM) Apollo Guidance Computer (AGC) for Apollo 11<br>`Assemble revision 055 of AGC program Comanche by NASA`<br>`2021113-051. 10:28 APR. 1, 1969` |
| Luminary099 | Part of the source code for Luminary 1A, the Lunar Module's (LM) Apollo Guidance Computer (AGC) for Apollo 11<br>`Assemble revision 001 of AGC program LYM99 by NASA`<br>`2021112-061. 16:27 JUL. 14, 1969`     |
| 組譯器      | yaYUL                                                                                                                                                                                                           |
| 連絡人      | Ron Burkey <info@sandroid.org>                                                                                                                                                                                  |
| 網站        | www.ibiblio.org/apollo                                                                                                                                                                                          |
| 數位化      | 這份原始程式碼整理自 MIT Museum 的數位化影像複印本。數位化由 Paul Fjeld 完成，並經過 MIT Museum 的 Deborah Douglas 整理，在此衷心感激兩位。                                                                     |

### Contract and Approvals

_Derived from [CONTRACT_AND_APPROVALS.agc]_

該 AGC 程式也可被稱作: COLOSSUS 2A

如同 R-577 報告指出，該程式主要用於阿波羅駕駛艙。此外，該程式是由 DSR 計劃 55-23870 籌劃，並由(美國)國家航空暨太空總署旗下的載人太空船中心經由合約 NAS 9-4065 資助。該合約是由(美國)實驗儀器公司、麻省理工學院、劍橋大學以及 MASS 共同簽定。

| 提交者               | Role                                          | 日期               |
| :------------------- | :-------------------------------------------- | :----------------- |
| Margaret H. Hamilton | Colossus 程式設計負責人<br>阿波羅導引導航系統 | 1969 年 3 月 28 日 |

| 核准人            | Role                                       | 日期                |
| :---------------- | :----------------------------------------- | :------------------ |
| Daniel J. Lickly  | 負責人, 任務程式開發<br>阿波羅導引導航程式 | 1969 年 3 月 28 日  |
| Fred H. Martin    | Colossus 專案經理<br>阿波羅導引導航程式    | 1969 年 3 月 28 日  |
| Norman E. Sears   | 負責人, 任務開發<br>阿波羅導引導航程式     | 1969 年 3 月 28 日  |
| Richard H. Battin | 負責人, 任務開發<br>阿波羅導引導航程式     | 1969 年 3 月 28 日  |
| David G. Hoag     | 負責人<br>阿波羅導引導航程式               | 1969 年 3 月 28 日  |
| Ralph R. Ragan    | 副負責人<br>(美國)實驗儀器公司             | 1969 年 3 月 2 8 日 |

[contract_and_approvals.agc]: https://github.com/chrislgarry/Apollo-11/blob/master/Comanche055/CONTRACT_AND_APPROVALS.agc
[1]: https://cdn.rawgit.com/aleen42/badges/c9246f74/src/nasa.svg
[2]: https://www.nasa.gov/mission_pages/apollo/missions/apollo11.html
[3]: http://www.ibiblio.org/apollo/
[4]: http://web.mit.edu/museum/
[5]: http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[6]: http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[7]: https://github.com/chrislgarry/Apollo-11/blob/master/CONTRIBUTING.md
[8]: https://github.com/rburkey2005/virtualagc
