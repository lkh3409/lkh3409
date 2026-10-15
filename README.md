<p>
  <a href="https://impossible-capricorn-64c.notion.site/AI-242c4f7d232c42bf9251a0127062b482?pvs=4" target="_blank"><img src="https://img.shields.io/badge/Notion-000000?style=flat-square&logo=Notion&logoColor=white"/></a>
  <a href="https://velog.io/@lkh3409"><img src="https://img.shields.io/badge/Velog-20C997?style=flat-square&logo=Velog&logoColor=white"/></a>
  <a href="mailto:kanghun340964@gmail.com" target="_blank"><img src="https://img.shields.io/badge/kanghun340964@gmail.com-EA4335?style=flat-square&logo=Gmail&logoColor=white"/></a>
  <a href="https://www.instagram.com/7ro._hu22.__/" target="_blank"><img src="https://img.shields.io/badge/Instagram-E4405F?style=flat-square&logo=Instagram&logoColor=white"/></a>
</p>

## Hi, I'm Kanghoon Lee

**AI로 문제를 정의하고, 실제로 돌아가는 결과물까지 만듭니다.**

경희대학교 인공지능학과에 재학 중입니다. 데이터 분석 학회에서 모델링을 익혔고, 지금은 LLM 서비스를 만들고 실제 고객에게 웹 서비스를 납품하고 있습니다.

- **코드보다 문제 정의가 먼저:** 무엇을 만들지, 어디까지가 완성인지부터 정합니다.
- **AI의 결과를 그대로 믿지 않기:** AI가 만든 결과는 근거와 기준으로 다시 확인합니다.
- **배운 것은 나누기:** 새로 익힌 도구와 지식은 스터디와 강의로 함께 씁니다.

<br/>

## Featured Projects

### [CodePulse](https://github.com/khuda-data/9th-NLP-team4) · 2026 · KHUDA 9th NLP·AIE Track · 5인 팀
GitHub 저장소를 입력하면 그 코드와 관련 있는 AI 트렌드만 골라 주는 서비스입니다. ([Demo](https://9th-nlp-team4-git-main-hoon5.vercel.app/) · [시연 영상](https://www.youtube.com/watch?v=1qKTwCagfvQ))
- LangGraph로 arXiv·Hacker News·GitHub 트렌드를 수집하고, 저장소와 비교해 *영향 / 대체 후보 / 신규 적용* 3가지로 분류합니다.
- **맡은 부분: 3단 검증 구조 설계.** LLM이 무관한 트렌드를 그럴듯하게 연결하는 문제를 막기 위해 Rule Gate → GPT-4o-mini 분류 → GPT-4o Judge 재채점 순으로 거릅니다. 점수 70점 이상만 사용자에게 보여 줍니다.
- `LangGraph` `GPT-4o` `FastAPI` `React` `Vercel` `Render`

### 고객 이탈 · LTV 2단계 예측 · 2026 · 한국데이터과학회 × SAS Korea 경진대회 · 5인 팀
카드·금융 고객의 1개월 내 이탈 확률과 1년 LTV를 함께 예측했습니다.
- 두 과제를 따로 풀지 않고, 이탈 확률로 LTV를 보정하는 구조를 설계했습니다: `LTV_final = LTV_model × (1 − p_churn)`
- **맡은 부분:** 팀 전략 문서 작성, 세 테이블(고객·거래·금융) 결합 피처 엔지니어링(RFM, 구매 추세, 연체·현금서비스 지표)
- `LightGBM` `XGBoost` `Optuna` `SAS Viya`

### Client Work · 2026 · 1인 개발
- **중앙예닮학교 입학 면접 예약 시스템:** 본인 인증 후 면접 시간을 선착순으로 예약하는 서비스입니다. 시간대당 1명, 수험번호당 1기기, 정해진 시각 자동 개방 같은 운영 규칙을 먼저 정의한 뒤 구현했고, 동시 접속 시 중복 예약이 생기지 않는지 테스트 시나리오로 검증했습니다. `Next.js` `TypeScript` `Vercel`
- **[삼정코칭파트너스 홈페이지](https://sjcoachingpartners.com):** 부산의 조직개발 컨설팅사 홈페이지입니다. 기획부터 디자인, 개발, 배포까지 맡았습니다. `Astro` `Tailwind` `Cloudflare Workers`
- 두 프로젝트 모두 Claude Code에 작업별 스킬과 검수 절차를 구성해 진행했습니다. 구현은 AI가 맡고, 저는 요구사항 정의·설계 판단·품질 검증에 집중했습니다.

<br/>

## Other Projects

| Year | Project | Description |
|---|---|---|
| 2026 | [우리들의 목장 일기](https://haneuldream.vercel.app) | 목장 모임을 지도와 앨범으로 남기는 웹앱 (Next.js + Supabase) |
| 2026 | [TGwinG_official_web](https://github.com/TG-WinG/TGwinG_official_web) | T.G.winG 동아리 공식 웹사이트 ([Site](https://tgwing.dpdns.org)) |
| 2024 | [Data_Business_FOODLENDAR](https://github.com/lkh3409/Data_Business_FOODLENDAR) | Prophet으로 농산물 70종의 월별 최저가 시기를 예측한 캘린더 (KHUDA 5th) |
| 2024 | [5th-ML-team3](https://github.com/khuda-data/5th-ML-team3) | XGBoost 기반 개인 맞춤 기대수명 예측 (KHUDA 5th) |
| 2023 | [Prediction_of_Location_based_RoadView](https://github.com/cho-jang-hyun/Prediction_of_Location_based_RoadView) | 교내 거리뷰 이미지 기반 위치 예측 프로그램 (KHUDA 4th CV) |
| 2023 | [ml_toy_project_team1](https://github.com/lkh3409/ml_toy_project_team1) | 댓글 33,731개로 KoBERT 파인튜닝, 유튜브 영상 호감도 평가 (KHUDA 4th) |
| 2023 | [Gram](https://github.com/lkh3409/Gram) | 인스타그램 피드 기반 궁합 분석, ViT 이미지 특징 추출·Flask 백엔드 담당 |
| 2023 | [Market-YOLO-checkout](https://github.com/lkh3409/Market-YOLO-checkout) | YOLOv8 상품 인식 무인 계산 시스템 (경희대 인공지능프로그래밍 AI100200) |
| 2023 | [23TGTHON](https://github.com/lkh3409/23TGTHON) | FaceNet 얼굴 인식 웹 프로젝트 (2023 티지톤) |
| 2023 | [GAN-paper-implementation](https://github.com/lkh3409/GAN-paper-implementation) | GAN·DCGAN PyTorch 구현 (MNIST) |
| 2023 | [Python-term-project](https://github.com/lkh3409/Python-term-project) | 해외축구 선수 몸값과 포지션·나이·골 수의 상관 분석 (경희대 웹/파이썬프로그래밍 SWCON10401) |

<br/>

## Activities

| Period | Organization · Role | |
|---|---|---|
| 2026.06 ~ | **삼성 사장단·임원 AX 부트캠프** · 보조강사 | 전 계열사 사장단·임원 대상 생성형 AI 실습 교육에서 질의응답·실습 지원 |
| 2026.03 ~ | **T.G.winG** (경희대 컴퓨터공학부 학술동아리) · 교육부장 | 신입생 Python·Notion·GitHub 교육, 해커톤 '티지톤' 기획·운영, Claude Code 스터디·AI 논문 리뷰 스터디 운영 |
| 2026.02 ~ | **KHUDA 9th** (경희대 데이터분석·AI 학회) · NLP·AIE Track | LLM·텍스트 분석 스터디, 정기학술제 프로젝트 진행 |
| 2024.02 ~ 2024.06 | **KHUDA 5th** · 대외협력부장, Data Business 트랙장 | 중앙대 Dart-B 교류 성사, 현대모비스 SW 우수동아리 선정 기여, 트랙 스터디 운영 |
| 2024.02 ~ 2024.06 | **대딩코딩 6기** (대학생 연합 코딩 교육 봉사) · 강사 | AI 논문 리뷰 스터디 대표 튜터, 고등학생 대상 Python 1:1 수업 |
| 2023.06 ~ 2023.12 | **KHUDA 4th** · Computer Vision Track | CV 모델 스터디, 교내 위치 예측·댓글 감정 분석 프로젝트 |
| 2023.03 ~ 2023.12 | **경희대 컴퓨터공학부 학생회** · 관리부원 | |
| 2023.03 ~ | **T.G.winG** · 부원 | |

**Certificates** · SQLD (2024) · 정보처리기능사 (2025)

<br/>

## Tech Stack

**AI / Data**<br/>
<img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54"/>
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"/>
<img src="https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white"/>
<img src="https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white"/>
<img src="https://img.shields.io/badge/LightGBM-02569B?style=for-the-badge"/>
<img src="https://img.shields.io/badge/XGBoost-337AB7?style=for-the-badge"/>
<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white"/>

**AI-assisted Development**<br/>
<img src="https://img.shields.io/badge/Claude_Code-D97757?style=for-the-badge&logo=claude&logoColor=white"/>
<img src="https://img.shields.io/badge/OpenAI_API-412991?style=for-the-badge&logo=openai&logoColor=white"/>
<img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white"/>
