---
name: research-frame
description: "체계적 리서치 프레임 WHY·HOW·SCOPE + BLIND·EXPAND + 7층 사고·트리거연동. LIGHT↔DEEP↔TURBO 3모드 + EXPAND 전용모드. v2.6: 트리거사전 28도구 연동(홈즈·오컴·엄브렐러·제1원리·백본·틀밖·절대자·연역수렴·아날로지·줌·맥가이버·프리모르템·트리아지·스켈레톤·제출청소·타임스톤·수정4·작업설계자), 장르 5분류(공식·전문·커뮤니티·소셜·역설), MECE 맹점방어, 게임이론 rationale 분리. P1: 리서치프레임, 리서치설계, 리서치스킬, 가설검증, 교차분석, 연역수렴, 반대증거, 축별조사, 프레임설계, 라이트리서치, 딥리서치, 터보리서치, TURBO, EXPAND, 리서치맹점, 프레임맹점, MECE맹점, 맹점감지, 프레임밖, 가설외, 대안프레임, 7층사고, 장르분류, 트리거연동, 5장르. P2: 리서치해줘, 조사해줘, 축별분석해줘, 가설분석해줘, 라이트·딥·터보·확장 리서치 해줘, 리서치맹점 찾아줘, 프레임 밖도 봐줘, research, blindspot, expand research. P3: research frame, hypothesis verification, cross-analysis, blindspot detection, frame-external exploration, trigger orchestration, 5-genre matrix. P4: 본격 리서치, 다축 조사, 시간 병목, 가설 의심, 프레임 밖 필요. P5: _research/로, .md로. NOT: 정책기획(→policy-planning), 단순팩트체크(→직접수행), 소스인용(→UP §E)."
version: 2.6
---

# Research Frame — WHY·HOW·SCOPE + 7층 사고

🔗 **REQUIRES:** `trigger-dictionary` (선행 로드 필수) — §1~§5 전구간 정식명 발동. §0-0 HARD-FIRE 전제 (INV 9).

리서치 "왜·어떻게·어디까지"를 구조화. UP §E 위에 7층(L0 제1원리·L1 장르·L2 홈즈·L3 삼각측량·L4 연역수렴·L5 아날로지·L6 맥가이버·L7 오컴) 중첩.

**발동:** 다축·가설검증·교차분석 (단순 팩트체크는 UP §E)
**🛡️ INVARIANT·PREFLIGHT·RESET·STEALTH:** → `references/invariants.md` (필수)

---

## 모드 · 구조

**진입:** 🎯 작업설계자 → 트리아지 → 모드 선택 (§0-0 HARD-FIRE)

| | LIGHT | DEEP | TURBO | EXPAND |
|---|---|---|---|---|
| 트리거 | "라이트" | 기본 | "터보" | "확장리서치" |
| 용도 | 스캔 | 풀 파이프라인 | 병렬 가속 | 프레임밖 집중 |
| 확신도 | **50 cap** (INV 4) | 판정표 | DEEP | DEEP |
| BLIND | S1·S3 | S1·S2·S3 | DEEP+병렬 | DEEP+T연쇄 |
| EXPAND | **금지** | T1·T2·T3 (축수×0.5, 상한3) | DEEP+병렬 | 예산×2+맹점연쇄 |
| 산출 | `LIGHT_[축].md` | `[축].md` + `EXPAND_[T]_[축].md` | DEEP | DEEP+ |

LIGHT→DEEP: rename(mv). TURBO → `turbo.md`

**흐름:** `§1 WHY → [WHY게이트] → §2 HOW → [HOW게이트] → §3 SCOPE ↳§4 BLIND → §5 EXPAND → 편입`

**원칙:** 중복 회계 제거(반대증거=§2-2·ACH=§2-3·전제=§2-1·신뢰도=§3-5) · FIG 3블록 · 예산제 · 객관 메트릭 복귀 · 정식명 본문 노출 (INV 9)

| references/ | 역할 |
|---|---|
| `why.md` · `how.md` · `scope.md` | §1·§2·§3 |
| `blind.md` · `expand.md` | §4·§5 |
| `invariants.md` | INV 9 + PREFLIGHT·Self-Check |
| `rationale.md` | 설계 근거 (Nash·Schelling·5장르) |
| `output-template.md` · `turbo.md` · `gotchas-extended.md` | 템플릿·병렬·함정 |

---

## §1·§2·§3·§4·§5 요약

→ `why.md` · `how.md` · `scope.md` · `blind.md` · `expand.md`

- **§1 WHY:** 1-1 결정연결 **제1원리·백본** · 1-2 가설+경쟁 3개+ **백본** · 1-3 MECE·전제 **틀밖·절대자** 자기반박 → [WHY 게이트]
- **§2 HOW:** 2-1 축별 병렬·수렴4축·FIG **홈즈·엄브렐러·프리모르템** · 2-2 반대증거 단일허브 · 2-3 ACH **연역수렴·오컴·외과적** · 2-4 회귀 **수정4·틀밖** → [HOW 게이트]
- **§3 SCOPE:** 3-1 경계 · 3-2 한계 **맥가이버** · 3-3 깊이 **트리아지** · 3-4 종료 **스켈레톤·제출청소** · 3-5 신뢰도 **오컴** 이진·LIGHT cap 50
- **§4 BLIND:** S1 비대칭 **홈즈** · S2 부재 **절대자** · S3 반증공백 **홈즈**. 자기고발=회귀+1 보너스, 숨김=2tier↓. 연쇄 S1·S2→T1 / S3→T2 (별도 예산)
- **§5 EXPAND:** 예산=축수×0.5(상한3). T1 **틀밖**·T2 **아날로지**·T3 **줌**. 복귀=객관 메트릭(3턴·수렴4축 2축+), **트리아지** 판정, 셸링=주가설. 서약 **타임스톤** 4항 미선언=무효

---

## §6 트리거 오케스트레이션 (v2.6)

7층 × 정식명 × 주입 지점. **정식명 본문 노출 필수** (HARD-FIRE 조건, STEALTH 면제).

| 층 | 정식명 | 주입 지점 |
|---|---|---|
| L0 목적 | 제1원리·백본·작업설계자·트리아지 | §1-1 · 모드 진입 |
| L1 장르 | 엄브렐러·프리모르템 | §2-1 소스장르 |
| L2 관찰 | 홈즈 | §2-1 · §4 S1·S3 |
| L3 정량 | (수렴4축·FIG 내재) | §2-1·2-3·3-5 |
| L4 연역 | 연역수렴·오컴·외과적·수정4 | §2-3 L1→L2 · §2-4 · §3-5 |
| L5 유추 | 아날로지·줌 | §5 T2·T3 |
| L6 맥가이버 | 맥가이버·틀밖·절대자 | §3-2 · §1-3 · §5 T1 |
| L7 팩트 | 오컴·외과적 | §3-5 · FIG |
| 종료 | 스켈레톤·제출청소·타임스톤 | §3-4 · §5 서약 |

예: "홈즈 발동 — 비대칭 흔적 역추적" ✓ / "S1 신호 분석"(정식명 누락) ✗

---

## 산출물 · 피드백

| 유형 | 경로 |
|---|---|
| DEEP 축별 | `_research/[축].md` (맹점 로그 포함) |
| LIGHT 축별 | `_research/LIGHT_[축].md` (INV 5) |
| EXPAND 토큰 | `_research/EXPAND_[T1/T2/T3]_[축].md` (INV 8) |

내부 구조 → `output-template.md`

**피드백 루프:** 오발동·미발동·출력변동 감지 시 → `evals/cases.json`에 케이스 추가 → `python scripts/validate.py` 재실행. 반복 실패는 thumbs-down + CHANGELOG에 재현조건 기록.

---

## Gotchas (Top 7)

1. 중복 회계 재판정 → 단일 지점만
2. WHY 게이트 스킵 → 3개 채움 필수
3. 축 간 오염 → WebSearch 병렬 발행
4. LIGHT cap 초과 → 50 절삭 (INV 4)
5. FIG 미가동 → 수집+결론 필수
6. **트리거 정식명 누락** → §6 노출 필수 (INV 9)
7. EXPAND 자의 연장·서약 생략 → 객관 메트릭, 셸링=주가설 복귀

→ 전체: `gotchas-extended.md` · Self-Check: `invariants.md` · 버전: `CHANGELOG.md`
