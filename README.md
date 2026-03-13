# Battle Shapers 한글패치 v1.0

> 공식 한국어 지원이 없는 Battle Shapers의 비공식 한글패치입니다.

---

## 📸 스크린샷

| | |
|---|---|
| ![메인 메뉴](assets/1.jpg) | ![게임플레이](assets/2.jpg) |
| ![UI](assets/3.jpg) | ![스킬](assets/4.jpg) |
| ![대사](assets/5.jpg) | ![아이템](assets/6.jpg) |

---

## 📋 번역 범위

| 분류 | 항목 수 | 상태 |
|------|--------|------|
| 대사 (Dialogue) | 4,200+ | ✅ 완료 |
| UI / 메뉴 | 1,500+ | ✅ 완료 |
| 아이템 / 스킬 설명 | 800+ | ✅ 완료 |
| 튜토리얼 | 300+ | ✅ 완료 |
| 기타 (로어, 통계 등) | 276 | ✅ 완료 |
| **합계** | **7,076개** | ✅ |

### 주요 용어

| 영문 | 한국어 | 비고 |
|------|--------|------|
| VerOS | 베로스 | 메인 빌런 (AI 오버로드) |
| JanOS | 야노스 | 이전 AI 운영체제 |
| Fortify | 방호 | 피해감소 버프 |
| Fury | 격노 | 피해증가 버프 |
| Reflect | 반사 | 투사체 반사 |
| Outburst | 아웃버스트 | 코어 어빌리티 |
| Meemo | 미모 | 아군 로봇 동료 |

---

## 💾 설치 방법

### 필요 조건
- PC (Windows) Steam 버전
- [BepInEx 5 (x64)](https://github.com/BepInEx/BepInEx/releases) 설치 필요

### 설치 순서

**1단계 - 다운로드**
아래 Releases에서 최신 ZIP 파일 다운로드

**2단계 - 압축 해제**
게임 설치 폴더에 **덮어쓰기**로 압축 해제
```
기본 경로: D:\SteamLibrary\steamapps\common\BattleShapers
```

**3단계 - 게임 실행**
게임을 실행하고 **설정 → 언어 → Chinese Traditional (繁體中文)** 선택
> ⚠️ 이 패치는 중국어 번체 슬롯을 한국어로 대체합니다. "繁體中文"을 선택하면 한국어가 표시됩니다.

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

---

## ❓ 자주 묻는 질문

**Q. 게임 업데이트 후 번역이 안 돼요**

A. 게임 업데이트 시 `resources.assets`가 초기화됩니다. 패치를 다시 설치해주세요.

**Q. 한글이 깨져서 표시돼요**

A. BepInEx 5가 올바르게 설치되어 있는지 확인해주세요. 폰트 패치 플러그인이 BepInEx를 통해 로드됩니다.

**Q. Steam 파일 무결성 검사 후 번역이 사라졌어요**

A. 무결성 검사는 패치 파일을 원본으로 되돌리므로, 검사 후 패치를 다시 설치하시면 됩니다.

---

## 🔧 기술 정보

- **번역 방식**: resources.assets 내 zht(중국어 번체) 로컬라이제이션 슬롯을 한국어로 대체
- **폰트**: Noto Sans KR (BepInEx Harmony 패치로 런타임 주입)
- **프레임워크**: BepInEx 5 + Harmony
- **번역 파일 위치**: `BattleShapers_Data/resources.assets` (path_id 352)

---

## 📝 오류 제보 / 기여

번역 오류나 누락된 텍스트는 아래로 알려주세요:
- **Issues**: [GitHub Issues](https://github.com/hanpaemo/battle-shapers-korean-patch/issues)
- **블로그**: https://hanpaemo.blogspot.com

---

## ❤️ 후원

번역이 도움이 되셨다면 응원 부탁드립니다!
- **Ko-fi**: https://ko-fi.com/hanpaemo

---

## 👤 제작

**한패모** — 인디게임 한글패치 모음
- GitHub: https://github.com/hanpaemo
- 블로그: https://hanpaemo.blogspot.com

---

## ⚖️ 라이선스

이 패치는 팬 제작 비공식 번역입니다.
게임 원작의 저작권은 **Metric Empire**에 있습니다.
상업적 이용을 금지합니다.
