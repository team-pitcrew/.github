# 현대자동차그룹 차량용 앱 개발 공모전 · PITCREW

> 가족이 차 안에서 나눈 대화를 여행의 기록으로 남깁니다.

<p align="center"><img width="640" src="https://raw.githubusercontent.com/team-pitcrew/.github/main/profile/pitcrew.jpg" alt="차 안에 함께 탄 PITCREW 캐릭터 넷" /></p>

## 소개

PITCREW는 Pleos 차량 앱 **가치타**를 만드는 네 사람의 팀입니다. 현대자동차그룹 차량용 앱 개발 공모전에 참가했으며, 어린 자녀와 함께 이동하는 가족이 차 안에서 나눈 말을 놓치지 않도록 돕고자 합니다.

## 가치타가 하는 일

| 언제 | 하는 일 |
|---|---|
| 달리는 동안 | 차량 마이크로 대화를 받아 적고, 좌석과 등록한 목소리로 누가 말했는지 차 안에서 가립니다 |
| 부탁이 나오면 | "화장실 가고 싶어"를 알아채 휴게소를 제안하고, 말로 수락하면 순정 내비에 경유지를 넣습니다 |
| 도착하면 | 그 장소에서 먼저 할 일과 살 것을 모아 보여 줍니다 |
| 여행이 끝나면 | 고른 장면을 캐릭터가 나오는 세로 쇼츠로 만들어 차와 폰에서 다시 봅니다 |

## 바로 가기

| 찾는 것 | 어디에 |
|---|---|
| 소스와 문서 | [team-pitcrew/gachita](https://github.com/team-pitcrew/gachita) |
| 제출용 APK | [릴리스 v1.0.0](https://github.com/team-pitcrew/gachita/releases/tag/v1.0.0) · 저장소의 [`apk/`](https://github.com/team-pitcrew/gachita/tree/develop/apk) |
| 실행 방법과 테스트 환경 | [README의 제출 안내](https://github.com/team-pitcrew/gachita#제출-안내) |
| 구조와 결정 기록 | [구조와 스택](https://github.com/team-pitcrew/gachita/blob/develop/docs/architecture.md) · [ADR](https://github.com/team-pitcrew/gachita/tree/develop/docs/adr) |
| 서비스 | [gachita.mangowhois.ai](https://gachita.mangowhois.ai) (API 서버와 폰 웹앱) |

## PITCREW

<table align="center">
  <tr>
    <td align="center"><img width="100" src="https://github.com/mangowhoiscloud.png" /></td>
    <td align="center"><img width="100" src="https://github.com/acrafti2020-lab.png" /></td>
    <td align="center"><img width="100" src="https://github.com/jiminsss02.png" /></td>
    <td align="center"><img width="100" src="https://github.com/yoodison.png" /></td>
  </tr>
  <tr>
    <td align="center"><b>류지환</b><br><sub><a href="https://github.com/mangowhoiscloud">@mangowhoiscloud</a></sub><br><sub>차량 앱 · 웹 · 인프라</sub></td>
    <td align="center"><b>김상현</b><br><sub><a href="https://github.com/acrafti2020-lab">@acrafti2020-lab</a></sub><br><sub>오픈소스 모델 API · 음성 재전사(ASR)</sub></td>
    <td align="center"><b>송지민</b><br><sub><a href="https://github.com/jiminsss02">@jiminsss02</a></sub><br><sub>팀장 · 기획</sub></td>
    <td align="center"><b>유민준</b><br><sub><a href="https://github.com/yoodison">@yoodison</a></sub><br><sub>기획 · 디자인</sub></td>
  </tr>
</table>

## 지금 상태

- 차량 앱은 Pleos Connect Emulator 2.1.0(Android 14, 2560 × 1440)에서 확인했습니다. 실차에서는 확인하지 않았습니다.
- 서버와 폰 웹앱은 2026년 11월 13일부터 AWS에서 돌고 있습니다.

## 저장소

| 저장소 | 내용 |
|---|---|
| [gachita](https://github.com/team-pitcrew/gachita) | 가치타 — Pleos 차량 앱, 동승자 웹, API 서버, 인프라, 문서 |

## 문의

질문과 제보는 [gachita 저장소의 Issues](https://github.com/team-pitcrew/gachita/issues)에 남겨 주세요.
