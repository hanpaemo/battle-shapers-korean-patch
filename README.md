# Battle Shapers 한글패치

**Battle Shapers** 비공식 한글패치 — 한패모 (hanpaemo)

## 설치 방법

> **사전 준비**: [BepInEx 5 (x64)](https://github.com/BepInEx/BepInEx/releases) 가 게임 폴더에 설치되어 있어야 합니다.

1. [Releases](https://github.com/hanpaemo/battle-shapers-korean-patch/releases) 에서 최신 ZIP 파일을 다운로드합니다.
2. ZIP 파일의 내용물을 게임 폴더에 **덮어쓰기** 합니다.
   - Steam 기본 경로: `D:\SteamLibrary\steamapps\common\BattleShapers`
3. 게임을 실행하고 **설정 > 언어 > Chinese Traditional (繁體中文)** 을 선택합니다.
4. 한국어가 표시됩니다.

### 파일 구조

```
BattleShapers/
  BattleShapers_Data/
    resources.assets          ← 한글 번역 데이터 (zht 슬롯 대체)
  BepInEx/
    plugins/
      Hanpaemo.BattleShapers.KoreanPatch.dll   ← 한글 폰트 패치 플러그인
      NotoSansKR-Regular.otf                    ← 한국어 폰트
```

> **참고**: 이 패치는 중국어 번체(Chinese Traditional) 슬롯을 한국어로 대체합니다. 게임 내 언어 설정에서 "繁體中文"을 선택하면 한국어가 표시됩니다.

## 번역 범위

| 분류 | 행 수 | 상태 |
|------|-------|------|
| 대사 (Dialogue) | ~4,200 | 완료 |
| UI / 메뉴 | ~1,500 | 완료 |
| 아이템 / 스킬 설명 | ~800 | 완료 |
| 튜토리얼 | ~300 | 완료 |
| 기타 (로어, 통계 등) | ~276 | 완료 |
| **합계** | **7,076** | **완료** |

## 주요 용어

| 영문 | 한국어 | 비고 |
|------|--------|------|
| VerOS | 베로스 | 메인 빌런 (AI 오버로드) |
| JanOS | 야노스 | 이전 AI 운영체제 |
| Fortify | 방호 | 피해감소 버프 |
| Fury | 격노 | 피해증가 버프 |
| Reflect | 반사 | 투사체 반사 |
| Outburst | 아웃버스트 | 코어 어빌리티 |
| Meemo | 미모 | 아군 로봇 동료 |

## 오류 제보

- [GitHub Issues](https://github.com/hanpaemo/battle-shapers-korean-patch/issues)
- [한패모 블로그](https://hanpaemo.com) 댓글

## 크레딧

- 번역: 한패모 (hanpaemo)
- 폰트: [Noto Sans KR](https://fonts.google.com/noto/specimen/Noto+Sans+KR) (Google Fonts, OFL)
- 프레임워크: [BepInEx 5](https://github.com/BepInEx/BepInEx)
