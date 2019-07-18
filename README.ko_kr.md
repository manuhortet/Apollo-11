# 🚀 Apollo-11

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
**한국어**

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

사령선 모듈 (Comanche055) 및 달 착륙선 모듈 (Luminary099)을 위한 아폴로 11호 유도 컴퓨터(AGC)의 소스코드입니다. [Virtual AGC][3] 및 [MIT Museum][4]에 의해 디지털화 되었습니다.
이 레포지토리는 아폴로 11호의 원본 소스코드를 완벽하게 재현하여 보관하는 것을 목표로 합니다. 따라서 원본과 본 디지털본 간에 발견된 모든 이슈, 또한 빠뜨렸을 듯한 파일들에 대해 PR을 환영합니다.

## 기여하기

PR을 열기 전에 [CONTRIBUTING.md][7] 을 읽어보시기 바랍니다.

## 컴파일

만약 컴파일을 원하신다면 [Virtual AGC][8] 을 확인하여 보십시오.

## 권한

| &nbsp;      | &nbsp;                                                                                                                                                                                                          |
| :---------- | :-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| 저작권      | 퍼블릭 도메인                                                                                                                                                                                                   |
| Comanche055 | Part of the source code for Colossus 2A, the Command Module's (CM) Apollo Guidance Computer (AGC) for Apollo 11<br>`Assemble revision 055 of AGC program Comanche by NASA`<br>`2021113-051. 10:28 APR. 1, 1969` |
| Luminary099 | Part of the source code for Luminary 1A, the Lunar Module's (LM) Apollo Guidance Computer (AGC) for Apollo 11<br>`Assemble revision 001 of AGC program LYM99 by NASA`<br>`2021112-061. 16:27 JUL. 14, 1969`     |
| 어셈블러    | yaYUL                                                                                                                                                                                                           |
| 연락처      | Ron Burkey <info@sandroid.org>                                                                                                                                                                                  |
| 웹사이트    | www.ibiblio.org/apollo                                                                                                                                                                                          |
| 디지털화    | 이 소스코드는 MIT Museum에서 하드카피본을 디지털화, 옮긴 것 입니다. 디지털화는 Paul Fjeld에 의해 이루어졌으며, Deborah Douglas가 정리하였습니다. 두 분께 깊은 감사를 표합니다.                                  |

### Contract and Approvals

_[CONTRACT_AND_APPROVALS.agc] 에서 파생 됨_

본 아폴로 유도 컴퓨터 프로그램은 다음에 의해 참조됩니다 : 콜로서스 2A

이 프로그램은 R-577에 명세된 사령선 모듈에 사용됩니다. DSR 프로젝트 55-23870 에 의해 준비되었으며, NASA 유인 우주선 센터가 MIT 기계 연구소 와의 NAS 9-4065 계약에 의해 스폰싱 하였습니다.

| 제출됨               | Role                                            | 일시            |
| :------------------- | :---------------------------------------------- | :-------------- |
| Margaret H. Hamilton | 콜로서스 프로그래밍 리더<br>아폴로 유도 및 항해 | 1969년 3월 28일 |

| 승인됨            | Role                                                     | 일시            |
| :---------------- | :------------------------------------------------------- | :-------------- |
| Daniel J. Lickly  | 감독, 임무 프로그램 개발<br>아폴로 유도 및 항법 프로그램 | 1969년 3월 28일 |
| Fred H. Martin    | 콜로서스 프로젝트 매니저<br>아폴로 유도 및 항법 프로그램 | 1969년 3월 28일 |
| Norman E. Sears   | 감독, 임무 개발<br>아폴로 유도 및 항법 프로그램          | 1969년 3월 28일 |
| Richard H. Battin | 감독, 임무 개발<br>아폴로 유도 및 항법 프로그램          | 1969년 3월 28일 |
| David G. Hoag     | 감독<br>아폴로 유도 및 항법 프로그램                     | 1969년 3월 28일 |
| Ralph R. Ragan    | 부감독<br>기계 연구소                                    | 1969년 3월 28일 |

[contract_and_approvals.agc]: https://github.com/chrislgarry/Apollo-11/blob/master/Comanche055/CONTRACT_AND_APPROVALS.agc
[1]: https://cdn.rawgit.com/aleen42/badges/c9246f74/src/nasa.svg
[2]: https://www.nasa.gov/mission_pages/apollo/missions/apollo11.html
[3]: http://www.ibiblio.org/apollo/
[4]: http://web.mit.edu/museum/
[5]: http://www.ibiblio.org/apollo/ScansForConversion/Luminary099/
[6]: http://www.ibiblio.org/apollo/ScansForConversion/Comanche055/
[7]: https://github.com/chrislgarry/Apollo-11/blob/master/CONTRIBUTING.md
[8]: https://github.com/rburkey2005/virtualagc
