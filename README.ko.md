# 리서치 프레임워크

> 🇺🇸 [English README](./README.md)

**체계적 리서치 프레임워크: LIGHT 및 DEEP 모드 — 폭 유지 스캔 또는 풀 조사 파이프라인**

## 사전 요구사항

- **Claude Cowork 또는 Claude Code** 환경
- **웹 검색 접근** — DEEP 모드 리서치 권장

## 목적

구조 없는 리서치는 무관한 세부사항에서 시간을 낭비하거나 중요한 인사이트를 놓칩니다. Research-Frame은 3축 방법론(WHY, HOW, SCOPE)을 제공하여 빠른 폭 스캔(LIGHT 모드)에서 엄밀한 다단계 조사(DEEP 모드)까지 확장되며, 당신의 발견이 완전하고 편향 인식적이며 실행 가능함을 보장합니다.

## 사용 시점 및 방법

빠른 회귀 시간이 필요한 폭 스캔이 필요하면 LIGHT 모드를 호출하세요 — 깊이를 최소화하면서 넓은 범위를 유지합니다. 위험도가 높거나 의사결정이 전략적이면 DEEP 모드를 호출하세요 — 편향 방지 게이트와 교차축 검증을 통한 풀 파이프라인을 실행합니다. WHY는 목적과 가설을 프레이밍; HOW는 편향 체크를 통한 축별 조사를 구조화; SCOPE는 경계 및 종료 기준을 설정합니다. 의사결정 위험도에 따라 모드를 선택합니다.

## 사용 예시

| 상황 | 프롬프트 | 결과 |
|---|---|---|
| 빠른 시장 규모 추정 | `"LIGHT research: TAM of AI consulting in Southeast Asia"` | WHY (범위)→HOW (3축)→SCOPE (경계); 폭 유지, 20분 내 발견 |
| 깊은 정책 분석 | `"DEEP research: regulatory impact of carbon tax on automotive"` | 편향 게이트, 교차축 검증, 모순 조화, 40개 이상 출처가 포함된 풀 파이프라인 |
| 경쟁사 인텔 | `"research-frame LIGHT on competitor's go-to-market"` | WHY (의도)→HOW (포지셔닝/가격/채널)→SCOPE (100개 회사); 경관 매핑 |
| 전략적 채용 의사결정 | `"DEEP on candidate's track record in scaling sales"` | 평판축→역량축→문화적합성축; 반례 포함; 위험 신호 표면화 |
| 기술 채택 연구 | `"LIGHT research on enterprise adoption barriers for blockchain"` | 목적→주요 장벽 가설→3축 스캔; 한 세션 내 의사결정 준비 |

## 핵심 기능

- 2모드 운영: LIGHT (폭, 최소 깊이, 빠름) 및 DEEP (풀 파이프라인, 게이트, 교차검증)
- 3축 구조: WHY (목적, 가설, 프레이밍), HOW (조사 방법론, 편향 방지, 교차분석), SCOPE (경계, 리소스, 종료 기준)
- 각 단계에서의 내장 편향 감지 및 방지
- 교차축 검증은 모순이 표면화되고 조화됨을 보장
- 도메인 확장성: 시장 리서치, 정책 분석, 경쟁사 인텔, 채용, 기술 평가


## 연관 스킬

- **[planning-skill](https://github.com/jasonnamii/planning-skill)** — planning-skill은 P2 (리서치 단계)에서 research-frame을 호출합니다
- **[policy-planning](https://github.com/jasonnamii/policy-planning)** — policy-planning은 research-frame을 기본 단계로 활용합니다
- **[person-profiler](https://github.com/jasonnamii/person-profiler)** — person-profiler는 포괄적 지원자 분석을 위해 DEEP 모드 호출 가능
- **[biz-skill](https://github.com/jasonnamii/biz-skill)** — biz-skill은 research-frame 발견을 전략 패턴 매칭과 연결

## 설치

```bash
git clone https://github.com/jasonnamii/research-frame.git ~/.claude/skills/research-frame
```

## 업데이트

```bash
cd ~/.claude/skills/research-frame && git pull
```

`~/.claude/skills/`에 배치된 스킬은 Claude Code 및 Cowork 세션에서 자동으로 사용할 수 있습니다.

## Cowork 스킬 생태계

25개 이상의 커스텀 스킬 중 하나입니다. 전체 카탈로그: [github.com/jasonnamii/cowork-skills](https://github.com/jasonnamii/cowork-skills)

## 라이선스

MIT 라이선스 — 자유롭게 사용, 수정, 공유하세요.
