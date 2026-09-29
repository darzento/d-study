# AI 활용 연수회 - Design Spec

## I. Project Information
| Item | Value |
|---|---|
| Project Name | AI 활용 한 단계 더 디자인 수정 |
| Canvas Format | PPT 4:3, 960 × 720 |
| Page Count | 9 |
| Design Style | swiss-minimal, diplomat_study_ppt identity |
| Target Audience | 디프로매트 임직원 |
| Use Case | 수요연수회 |
| Delivery Purpose | presentation |
| Content Strategy | Re-architect source deck per user direction; preserve retained slide wording and values |
| Template Adherence | adaptive |
| Created Date | 2026-09-29 |
> Note: User selected Apple in the confirmation UI; adapt its sparse composition and retain its Master identity. Explicit Diplomat branding, font, logo and 4:3 canvas override conflicting Apple defaults.
> Structure note: `spec_lock.md` maps pages to the project's 4:3 adapted SVG prototypes in `templates/adapted_*.svg`. The original Apple template files remain unchanged as visual references.

## II. Canvas Specification
| Property | Value |
|---|---|
| Format | PPT 4:3 |
| Dimensions | 960 × 720 |
| viewBox | 0 0 960 720 |
| Margins | 48 left/right, 44 top |
| Content Area | x 48–912, y 182–615 |

## III. Visual Theme
- Mode: instructional
- Visual style: swiss-minimal
- Theme: Light
- Tone: 정돈된 사내 교육 자료
| Role | HEX | Purpose |
|---|---|---|
| Background | #FFFFFF | Canvas |
| Secondary bg | #F4F6F8 | Sparse panels |
| Primary | #000000 | Titles |
| Accent | #DA1F28 | Rules and key emphasis |
| Secondary accent | #39639D | Summary |
| Body text | #464646 | Body |
| Secondary text | #69737D | Auxiliary labels |
| Border | #D9DEE3 | Dividers |

## IV. Typography System
| Role | Korean | Latin | Fallback tail |
|---|---|---|---|
| Title / Body / Emphasis | 맑은 고딕 | Malgun Gothic | Arial, sans-serif |
| Code | Not used | Not used | Not used |
- Title: 'Malgun Gothic', '맑은 고딕', Arial, sans-serif
- Body: 'Malgun Gothic', '맑은 고딕', Arial, sans-serif
- Emphasis: same as Body
- Code: None
| Role | Size | Weight |
|---|---|---|
| Body | 18.67 | Regular |
| Title | 32 | Bold |
| Subtitle / Lead | 21.33 | Regular / Bold |
| Annotation / Footnote | 13.33 | Regular |
| Subheading | 24 | Bold |
| Cover title | 48 | Bold |
| Agenda | 26 | Regular |
| Ending | 42.67 | Bold |
> Note: Malgun Gothic is installed on this Windows host; preserve user-requested font. Target software requires this font or an equivalent Korean font. Use explicit Korean/Latin typefaces in export and verify PowerPoint rendering.

## V. Layout Principles
| Area | Bounds / rule |
|---|---|
| Header | Title at 48,72; red rule y=98; blue summary y=140 |
| Content | 3-column comparison, open rows, or 2-row process |
| Footer | Red hairline y=653; original logo x=682, y=676, w=230; page index centered |
| Spacing | 24–36 gaps; 28–32 body line height |
| Panels | Square corners; no shadows; no decorative fill behind every text block |

## VI. Icon Usage Specification
No decorative icons. Preserve the source ❌ and ⭕ characters as text. The original Diplomat logo is a provided image.

## VII. Visualization Reference List (if needed)
No data charts or native tables. P09 is an ordered six-stage process diagram.
| Page | Template | Path | Summary-quote | Usage |
|---|---|---|---|---|
| P09 | no-template-match | diagram-design/references/type-flowchart.md | Not applicable | Six ordered steps in two rows; preserve five source arrows |
> Note: Source-specific two-row workflow uses explicit node/edge geometry; no fabricated chart data.

## VIII. Image Resource List
| Filename | Dimensions | Type | Acquire Via | Status | Usage |
|---|---|---|---|---|---|
| image1.png | 547 × 42 | Logo | provided | Ready | Every page; no crop; original reference image bytes |

## IX. Content Outline

#### Slide 01

- **Cover impact**: “AI 활용, 한 단계 더” is the hook; use a typographic poster with the large left-aligned title above a single red rule and keep event details secondary.
- **Layout**: 01_title: spacious left cover
- **Content** (retained source blocks):
- **Content** (verbatim source blocks):

제OOO회 수요연수회

AI 활용, 한 단계 더

2026년 9월 30일

기술연구소

성진영 프로

#### Slide 02

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 02_agenda: four aligned rows
- **Content** (verbatim source blocks):

목차

- AI 활용, 어디까지 왔을까?
- 어떻게 하면 AI를 진짜 잘 쓸 수 있을까?
- 라이브 시연: SKILL·AGENT·PLUGIN 활용
- 질문이 없을 때: 지속 가능한 AI 협업 워크플로우

#### Slide 03

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 05_feature_grid: three open columns
- **Content** (verbatim source blocks):

AI 활용, 어디까지 왔을까?

텍스트 한 줄로 시공간을 넘나드는 고품질 영상을 구현하는 시대

- 영상 사례 1:
- 타임머신 여행

- 영상 사례 2:
- 산업 현장 AI

- 임직원을 위한
- 시사점

- 텍스트 프롬프트 기반
- 역사적 시공간 초고속 복원
- 사실적 영상 자동 생성
- (유튜브 쇼츠 실습 영상)

- 도면·사진 3D 변환
- 회의록 화자 분리 및 요약
- 단순 작업 즉각 자동화
- (업무 생산성 혁신)

- 연구용 기술 탈피
- 실무에 즉시 투입 가능한
- 일상 업무 가속 도구

핵심: AI는 상상을 시각화하고 단순 업무를 초고속화하는 실전 도구입니다.

#### Slide 04

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 05_feature_grid: three open columns
- **Content** (verbatim source blocks):

우리가 AI를 쓰며 느끼는 흔한 좌절

기대와 다른 두루뭉술한 답변과 매번 반복되는 설명에 지치는 현실

- 두루뭉술한 답변
- 교과서적 일반론 나열
- 사내 맥락·규정 미반영
- “알아서 써줘”의 한계

- 반복 설명의 피로
- 새 대화창마다 복사·붙여넣기
- 서식·규칙 재설명 피로
- 세션 종료 시 기억 망각

- 실무 적용 포기
- “그냥 내가 쓰고 말지”
- 결국 수작업으로 회귀
- 도구 활용의 단절

원인은 AI의 한계가 아닌, '일 시키는 방식(디렉팅)'의 부재였습니다.

#### Slide 05

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 05_feature_grid: three open columns
- **Content** (verbatim source blocks):

어떻게 하면 AI를 진짜 잘 쓸 수 있을까?

AI는 자판기가 아니라, 사내 맥락을 모르는 '유능한 신입 사원'입니다.

- 배경
- (Context)

- 제약
- (Constraints)

- 완료 기준
- (Format)

- 작성 목적 & 보고 대상
- 사내 상황과 타깃을
- 명확히 사전 공유

- 필수 포함 & 금지 기준
- 분량 제한·핵심 수치·
- 주의사항 사전 지정

- 최종 출력 양식 규격화
- 3줄 요약·표 형식 지정
- (AI 자체 검증 유도)

핵심은 배경·제약·완료조건 3가지를 명확히 분리하여 지시하는 것입니다.

#### Slide 06

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 08_comparison: wider two-column comparison
- **Content** (verbatim source blocks):

프롬프트 작성 전과 후 비교 예시

같은 메모도 요약을 넘어 분석과 판단을 요청하면 업무에 바로 쓸 수 있는 결과로 바뀝니다.

- 공통 메모: 외주 업체 설비 점검으로 부품 입고 5일 지연. 시제품 조립 10/16 예정. 완제품 재고 12대, 최근 주 평균 출고 8대. 고객 영향과 대체 일정은 확인 중.

- ❌ 요약만 요청 ("보고용으로 정리해줘")
- • 결과: 사실을 문장으로 재배열
- • 부품 입고가 5일 지연되어 조립은 10/16 예정. 재고 12대, 주 평균 출고 8대이며 고객 영향·대체 일정은 확인 중.

- ⭕ 판단까지 요청 (목적·계산·조치·제약 지정)
- • 지시: "팀장용 리스크 브리프 작성. 확정 사실·영향·미확정을 구분하고, 재고 여력을 계산해. 우선 조치 제안. 고객 영향·일정·담당자는 추정 금지."
- • 결과: 재고 여력 약 1.5주분 (최근 평균 출고 기준)
- • 고객 영향·대체 일정: 확인 필요
- • 우선 조치: 고객별 납기 확인

요약을 넘어 분석과 판단을 요청하면 업무에 바로 쓸 결과가 됩니다.

#### Slide 07

- **Core message**: Preserve the source slide's existing core message verbatim; do not add a new visible assertion.

- **Layout**: 05_feature_grid: three open columns
- **Content** (verbatim source blocks):

한 단계 더: 단발성 질문을 넘어 시스템으로

도구(Tool), 스킬(Skill), 에이전트(Agent)의 결합으로 완성하는 자동화

- 스킬 (Skill)
- 반복 업무 표준 매뉴얼
- 규칙 영구 기억 (SOP)
- 예: 디프로매트 보고서 양식

- 에이전트 (Agent)
- 목표를 완수하는 전담 비서
- 스스로 작업 수행
- 예: 회의록 요약, 품질 분석 담당

- 플러그인 (Plugin)
- 외부 도구·기능 연결 연장
- AI의 실행 손발
- 예: 파일 읽기·쓰기, 검색 도구

비유하면: 스킬은 업무 매뉴얼, 에이전트는 전담 비서, 플러그인은 손발 도구입니다.

#### Slide 08

- **Core message**: Thank the audience and open the floor for questions and discussion.
- **Layout**: 13_closing: spacious closing
- **Content**:

경청해 주셔서 감사합니다.

( 질의응답 및 자유 토론 )

#### Slide 09

- **Closing impact**: Leave the audience with the idea that repeatable AI work compounds; use the six-step workflow to culminate in a bold one-line takeaway.
- **Core message**: Optional closing reference, shown after the thank-you slide only when there are no questions.
- **Layout**: 05_feature_grid: two rows of three stages
- **Content** (retained source blocks):

지속 가능한 AI 협업 워크플로우

업무의 발견부터 자산화까지 이어지는 전사 업무 선순환 사이클

1. 문제 정의

→

2. 공정 분해

→

3. 완료 기준

→

4. AI 실행

→

5. 검토·확인

→

6. 지식 자산화

- 귀찮음·관성 포착
- 5 Whys 본질 규명

- 큰 단위 업무를
- 작은 원자 작업 분할

- 통과 조건 수립
- 3줄 요약·양식 규격화

- 맥락 재료 투입
- 스킬 기반 초안 도출

- 디렉터 팩트체크
- 수치·논리 최종 검증

- 해결법 템플릿화
- 다음 시간 50% 단축

핵심: 1회성 질문에 그치지 않고, 템플릿으로 자산화하여 복리 효율을 만듭니다.

## X. Speaker Notes Requirements

None requested
