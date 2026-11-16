# 🏰 Kingshot (킹샷) 이벤트 및 성장 최적화 연구 프로젝트 Rules

본 워크스페이스는 모바일 전략 게임 **킹샷 (Kingshot)** 의 이벤트 공략 및 소과금 성장 최적화를 연구하는 프로젝트다. 모든 대화와 전략 수립 시 본 규칙과 참조 문서를 기초 자료로 활용한다.

---

## 1. 공식 레퍼런스 및 로컬 문서
- **공식 위키 (한국어)**: https://kingshotwiki.com/ko/ (`events/` · `heroes/` · `buildings/`)
- **로컬 전략 문서**:
  - 일일 실행 To-Do (당일 / 익일): [`context/daily_todo.md`](./context/daily_todo.md) · [`context/next_todo.md`](./context/next_todo.md)
  - 거시 성장 마스터플랜 (`TC 24➔26` · 2세대 · 재화): [`context/macro_roadmap_strategy.md`](./context/macro_roadmap_strategy.md)
  - 플레이어 현재 상태 및 히스토리: [`context/player_profile.md`](./context/player_profile.md)
  - 영웅 육성 우선순위 (장비·스킬북·조각): [`context/hero_growth_strategy.md`](./context/hero_growth_strategy.md)
  - 공식 용어집 및 이벤트 카탈로그: [`context/kingshot_terminology_and_events.md`](./context/kingshot_terminology_and_events.md)
  - 자이언트 베어 사냥(곰사냥) 전략: [`context/bear_hunt_strategy.md`](./context/bear_hunt_strategy.md)
  - 연맹 총동원 전략: [`context/alliance_mobilization_strategy.md`](./context/alliance_mobilization_strategy.md)
  - **전 이벤트·콘텐츠 병과 비율(`보:기:궁`) 마스터 표**: [`context/troop_ratio_strategy.md`](./context/troop_ratio_strategy.md)
  - 연맹 챔피언십 편성 전략: [`context/alliance_championship_strategy.md`](./context/alliance_championship_strategy.md)
  - 최강 영주 & 영웅 룰렛 전략: [`context/hall_of_governors_strategy.md`](./context/hall_of_governors_strategy.md)
  - 사라진 유적 (영주 보석) 전략: [`context/eternitys_reach_strategy.md`](./context/eternitys_reach_strategy.md)
  - 스태미나 & 8대 상점 우선순위: [`context/stamina_and_shop_strategy.md`](./context/stamina_and_shop_strategy.md)
  - 오아시스 섬 (생명의 샘) 우선순위: [`context/oasis_island_strategy.md`](./context/oasis_island_strategy.md)
- **용어 원칙**: Kingshot 한국어 위키 공식 명칭(`도시 센터`, `최강 영주`, `지고의 영주`, `최강 왕국`, `성검 쟁탈`, `자이언트 베어 사냥` 등) 기준 표기.

---

## 2. 플레이어 현재 상태 요약 (Baseline Context)
> 상세 스펙·이력은 [`context/player_profile.md`](./context/player_profile.md) 참조. 유저가 성장 현황을 업데이트하면 즉시 두 파일을 동기화한다.

- **기준 일자 / 과금**: `2026-11-16` (4주 차 / 약 22일 차, `1세대 S1`) · 스마트 소·중과금 / **`VIP 4`**
- **건물 현황**: **`TC·대사관·아카데미·보병대·궁병대 Lv.23` · `기병대 Lv.22`** / **`도시 센터 Lv.24` 무가속 공사 중 (`11/20 금 16:00` 완공 예정)** ➔ 차기 `TC 25(영주 보석)` ➔ `TC 26(T9)` 직행
- **전투력 / 포지션**: **`15,107,467`** · 왕국 `#2581` 2위 연맹 **`[SHD]`** (88명 중 `13위`, 곰사냥 함정 단독 `2위` `7.68M` / `NAP 8`: `WAR·SHD·APX·BOG·KNG·WfR·TRK·WHC`)
- **병력 (`11/16 17:00` 실측)**: **총 `132,751명`** (`T8 48,169 [36.3%]` · `T7 72,822` · `T5~6 기병 1,979` · `T1 보·기 9,781` — 궁병 `1~6등급 0명` & 보병 `2~6등급 0명`) / **1부대 `92,400명`** · 병원 `63,800명` · 대열 `4개`
- **주요 재화**: 다이아 **`~120.7K+`**(`상단 70K+ · 가방 50,696`) · 성장 가속 **`368h 31m`**(`공용 103h 55m / 훈련 131h 18m / 건설 9h 59m / 연구 123h 19m`) · 스태미나 **`3,960`** · 영주 장비 **`초록 0성 6풀셋`**(`비단 1,187 · 금사 78` / 보석 `도면 42 · 매뉴얼 50`) · `단조 망치 17`
- **영웅 로스터 (`특훈병영` 동기화 `Lv.60`)**:
  - **전설**: `제이벨`(`Lv.63/3.2성`, 탐험 `4/4/4`·원정 `3/4/3`, 신화 `투구+51[Lv.1]·신발+38`) · `헬가`(`Lv.64/2.2성`, 원정 `3/3/3`, 신화 `갑옷+53[Lv.2]·장갑+45·신발+20`) · `살로`(`Lv.60/3.0성`, 건설 `Lv.4`) / 범용 전설 조각 `49개`(`마린` 봉인)
  - **에픽·레어** *(조각 에픽 `553`·레어 `256`개 `11/24` 개봉 대기, 에픽 원정 교범 `53권`)*: `퀸`(`Lv.64/3.2성`, 원정 `3/4`, 신화 4풀셋 `투구·신발+45[Lv.1]`) · `다이애나`(`Lv.60/4.0성`, **원정 `4/2`**) · `하워드`(`Lv.60/3.2성`, 탐험 `4/4/4`) · `첸코`(`Lv.60/3.2성`, **유일 원정 1스킬 `Lv.4 = +20%`**) · `연우`(`Lv.60/2.5성[3.0성 준비]`, 원정 `3/3`) · `아마네`(`2.5성`, 원정 `2/1`) · 채집 4인방 전원 `3.1성`(채집 `Lv.3`)

---

## 3. 전략 수립 및 작성 원칙 (필수 준수)
1. **답변 및 문서 양식 (서술형 X · 초간결 우선)**:
   - 줄글 형태의 장황한 서술, 사족, 앞 번호와 겹치는 중복 조건 표기를 전면 금지한다.
   - 모든 답변과 문서는 **`[상단] 핵심만 간략 표기(결론·순서·수치표)` / `[하단] 필요시 설명·근거 분리`** 2단 구조로 작성한다.
2. **자원 세이브 & 폭발 (Hoard & Burst)**: 가속·조각·장비 재료·스태미나는 평시 무득점 소모를 금하고 `최강 영주`, `철야 근무`, `기술 발전`, `연맹 총동원` 중복 구간에 투입한다.
3. **건물 착공 & 병영 무중단 절대 원칙**:
   - `더블 타임(-20%, 5분)` 발동 시 가속 돌파 후 5분 내 `1번·2번 건설 슬롯`을 모두 채워 착공한다.
   - **병영(`보병대·기병대·궁병대`)은 공사 중 훈련이 멈추므로 무가속 착공을 절대 금하며, 항상 병력 수령 직후 `더블 타임 + 지원 + 가속`으로 즉시 완공(공백 `0초`)** 한다.
4. **데이터 무결성 (Anti-Hallucination)**:
   - 유저 완료 보고/스크린샷 전까지 ‘예정/계획’을 완료된 팩트로 선반영하지 않으며, 성급(`3.0성`)과 스킬 레벨(`Lv.4`)을 혼동하지 않는다.
   - 영웅 UI 상단 빨간 점(`🔴`)은 무시하고 우하단 `▲` 아이콘 조합만 판독한다.
   - 가이드는 실시간 변하는 머릿수 대신 **슬라이더 비율(`%`)**과 **우선순위 계단표**로 작성하며, `"병영 완료분 수령"` 같은 당연한 루틴 문구는 적지 않는다.
