# [주간 섹터 리포트] AI — 2026-06-06

**데이터 기준일**: 2026-05-30 ~ 2026-06-06 (직전 7일)
**작성**: WUBU 퀀트 리서치팀 (섹터 애널리스트)
**레이어 참조**: `docs/research/valuechain-layers-reference.md` A. AI 섹터 (L1~L5 전 레이어 포함)

---

## 섹터 전체 요약

이번 주 AI 섹터는 **두 개의 상반된 힘**이 충돌했다.

1. **상단 인프라(L1~L2)의 메가 catalyst**: 엔비디아의 **Vera Rubin 플랫폼 풀 양산** 발표(GTC Taipei 2026, 6/1)와 **삼성·SK하이닉스·마이크론 HBM4 공급사 인증**, 그리고 **젠슨 황의 방한(6/5 입국)** 기대감이 한국 증시를 사상 최고치로 끌어올렸다. 코스피는 6월 첫 거래일 신고가, 삼성전자 시총 2,000조 원 돌파 [서울신문/MBC, 2026-06-01]. 하이퍼스케일러 2026 capex는 $660~690B 규모로 전년 대비 ~36% 급증, 약 75%가 AI 인프라에 직결 [Futurum/IEEE ComSoc, 2026].

2. **하단 SaaS(L4)의 밸류에이션 리셋 + Broadcom 가이던스 쇼크**: Broadcom이 FY26 Q2 실적 호조에도 **Q3 AI 칩 매출 가이던스($16B)가 컨센서스($17.2B)를 하회**하면서 6/4 -12.6% 급락, 반도체 섹터 전반에 이틀 연속 매도세 유발(NVDA -1.4%, AMD -2.8%, MU -3.3%) [Stocktwits/TradingView, 2026-06-04~05]. 동시에 L4 응용 SaaS(ServiceNow·Adobe·Salesforce)는 AI 에이전트의 시트 라이선스 잠식 우려로 연초 대비 큰 폭 하락.

3. **데이터·MLOps(L5)는 명확한 승자**: Snowflake가 첫 10억 달러 분기(+32% YoY)와 AWS 대형 딜로 +36% 급등, MongoDB도 가이던스 상향 [CNBC/SiliconANGLE, 2026-05-27~28]. "SaaSpocalypse"를 데이터 레이어가 정면 반박.

**핵심 메시지**: 자금은 명백히 **AI 밸류체인 상단(메모리·HBM·클라우드 인프라)**과 **데이터 레이어**로 집중되고 있고, **응용 SaaS 미들레이어는 디레이팅** 중이다. 한국 노출은 L1(HBM)에 압도적으로 편중.

### 이번주 white list (1순위 — 직전 7일 데이터 기준)

| 종목/ETF | 레이어 | 한 줄 근거 (날짜) |
|----------|--------|-------------------|
| **SK하이닉스(000660)** | L1 | Vera Rubin HBM4 ~60~70% 점유, 2026 물량 완판, NH 목표가 180→310만원 상향, 젠슨 황 "Please Make More" [UPI/TradingKey, 2026-06-02] |
| **삼성전자(005930)** | L1 | NVDA·AMD HBM4 품질테스트 통과 → 6월 공급 개시, 시총 2,000조 돌파(+10%대 급등) [글로벌이코노믹/MBC, 2026-06-01] |
| **Snowflake(SNOW)** | L5 | 첫 10억 달러 분기(+32% YoY)·AWS 멀티빌리언 딜·가이던스 상향 → +36% 급등 [CNBC/SiliconANGLE, 2026-05-27~28] |
| **네이버(035420)** | L2/L3 | 젠슨 황 방한 회동 + 엔비디아 협력 기대로 급등(연초 +13%), AI 수익 청신호 [뉴시스/서울신문, 2026-06-02] |
| **SOXX / SMH (반도체 ETF)** | L1 | Vera Rubin 양산·HBM4 사이클 직접 노출. 단, Broadcom 쇼크로 단기 변동성 확대 [TradingView, 2026-06-04] |

### 2순위 관찰 후보 (신뢰도 낮음 — 7일 catalyst 약함)

- **MongoDB(MDB)** — FY Q1 +25%·가이던스 상향(4/30 종료 분기 실적) [Benzinga, 2026-05]. 호재이나 보고 시점이 7일 경계선.
- **Palantir(PLTR)** — 에이전틱 AI 플랫폼 내러티브 지속이나 7일 내 1차 catalyst 미확인.
- **더존비즈온(012510)·한글과컴퓨터(030520)** — 한국 L4. 7일 내 개별 catalyst 미확인.

---

## L1. 반도체·HBM·AI 가속기

> **요약**: 이번 주 AI 섹터 최대 catalyst 집중 레이어. Vera Rubin 풀 양산 + HBM4 3사 인증 + 젠슨 황 방한으로 한국 메모리주가 폭발. 단 Broadcom 가이던스 쇼크가 주말 변동성 유발.

### 주요 회사

**글로벌**
- **NVIDIA(NVDA)**: GTC Taipei 2026(6/1) 키노트에서 **Vera Rubin AI 플랫폼 풀 양산** 공식화, HBM4 공급사로 삼성·SK하이닉스·마이크론 지명. 여름부터 AWS·GCP·Azure·Oracle에 출하 시작, 하반기 광범위 공급 [TechTimes/Investing.com, 2026-06-02]. 현금배당 $0.25(ex-date 6/4) 발표, RTX Spark 로컬 AI 칩 공개 [Yahoo Finance, 2026-06]. Broadcom 쇼크로 6/4 -1.4%.
- **Broadcom(AVGO)**: FY26 Q2 매출·이익 컨센 상회했으나 **Q3 AI 칩 매출 가이던스 $16B(컨센 $17.2B 하회)**, FY27 전망 $100B 동결 → **6/4 -12.6% 급락(2025년 1월 이후 최대 낙폭)** [Stocktwits, 2026-06-04]. 섹터 전반 매도 트리거.
- **AMD**: HBM4 차세대 가속기 주공급사로 삼성 지명(긍정). 단 AVGO 쇼크로 이틀 연속 하락 -2.8% [TradingView, 2026-06-05].
- **Micron(MU)**: HBM4 인증 확보(긍정)이나 6/5 프리마켓 -3.3%, 섹터 매도 주도 [Stocktwits, 2026-06-05].

**한국**
- **SK하이닉스(000660)**: Vera Rubin HBM4 물량 **~60~70% 점유** 추정, 글로벌 HBM 점유율 58%, 2026 물량 완판. 최태원 회장 Computex에서 5년 내 웨이퍼 캐파 2배 발표, 연 capex 30조원+ [Startup Fortune/UPI, 2026-06-02]. 젠슨 황이 HBM4E 웨이퍼에 "Please Make More" 서명. NH투자증권 목표가 180→310만원 상향, 노무라 400만원 [민들레/TradingKey, 2026-06]. **15% 급등·신고가**.
- **삼성전자(005930)**: **NVDA·AMD HBM4 최종 품질테스트 통과 → 6월 본격 공급 개시**, AMD 차세대 가속기 주공급사 지명. HBM 점유율 1Q 30%대 회복. 시총 **2,000조원 돌파**(+10%대 급등), 노무라 목표가 59만원 [글로벌이코노믹/MBC, 2026-06-01].
- **한미반도체(042700)·리노공업·이오테크닉스**: HBM 후공정·테스트 사이클 동반 수혜. 젠슨 황 방한 기대로 반도체·로봇 관련주 동반 급등 [뉴시스, 2026-06-02].

### 금주 주요 이슈·이벤트

- **(긍정·실현)** Vera Rubin 풀 양산 + HBM4 3사 인증 → 한국 메모리주 폭등, 코스피 신고가. 실제 주가 영향 매우 큼.
- **(긍정·실현)** 젠슨 황 6/5 방한, 9개+ 한국 기업 회동(SK·LG·현대차·네이버) → 6/1부터 선반영 급등 [중앙이코노미/서울경제, 2026-06-01].
- **(부정·실현)** Broadcom Q3 AI 가이던스 미스 → 6/4~05 글로벌 반도체 매도, NVDA/AMD/MU 동반 하락. **차주 영향**: 단기 차익실현·밸류에이션 리셋 변동성 지속 예상. 단 HBM 공급 부족(2028까지) 구조는 견고.

### 관련 ETF

- **글로벌**: SOXX, SMH, SOXL(3x). 이번 주 Vera Rubin 양산 호재 vs AVGO 쇼크가 상충 → 주중 변동성 확대.
- **한국**: ACE AI반도체포커스(469150), TIGER 미국필라델피아반도체나스닥(381180), KODEX 반도체(091160). HBM4 사이클·젠슨 황 방한 직접 수혜.

### 차주 투자 관점 레이어 점수: **9 / 10**

구조적 HBM 부족(2028까지)·Vera Rubin 양산·젠슨 황 방한이라는 강력한 catalyst 3종 중첩. Broadcom발 단기 변동성은 -1점 요인이나 펀더멘털 훼손 아님.

---

## L2. 클라우드·하이퍼스케일러·인프라

> **요약**: 2026 하이퍼스케일러 capex $660~690B(약 75% AI 직결)로 사상 최대. Vera Rubin 초기 도입처(AWS·GCP·Azure·Oracle) 확정. 전력 제약이 새로운 병목.

### 주요 회사

**글로벌**
- **Microsoft(MSFT, Azure)**: FY26 capex $120B+ 트래킹, 최근 분기만 $37.5B 지출. **전력 제약으로 채울 수 없는 Azure 주문 백로그 $80B** 공개 → 수요 초과 시그널(긍정)이나 공급 병목 리스크 [Futurum, 2026].
- **Amazon(AMZN, AWS)**: 2026 capex $200B 목표, Q1 $43.2B(+60% YoY). 단 **FCF가 전년 $26B → $1.2B로 급감** → 자본 부담 가시화(부정) [Futurum, 2026].
- **Alphabet(GOOGL, GCP)**: 2026 capex $175~185B. Vera Rubin 초기 도입처. (L3 Gemini도 참조)
- **Oracle(ORCL, OCI)**: **RPO $523B(+438% YoY)**, OCI IaaS 매출 $4.1B. OpenAI·Meta·NVIDIA 장기계약. SoftBank 일본 소버린 클라우드 OCI 채택. 단 9개월 capex $39.2B(전년 $12.1B), TTM FCF -$24.7B로 자본 부담 심화. **6/10 FY Q4 실적 예정**(차주 핵심 이벤트) [TECHi/247WallSt, 2026-05~06].

**한국**
- **네이버(035420)**: **젠슨 황 방한 회동 + 엔비디아 AI 협력 기대로 급등**, AI 수익 청신호. 연초 +13% [뉴시스/서울신문, 2026-06-02]. HyperCLOVA X·자체 데이터센터 노출(L3 동시).
- **카카오(035720)**: 창사 첫 전면 파업 가결·플랫폼 규제·AI 전략 불확실로 **연초 -11% 부진**, 목표가 하향 [hellot/메트로서울, 2026-05~06]. (부정)
- **KT(030200)**: 데이터센터·소버린 AI 인프라 노출(개별 7일 catalyst 약함).

### 금주 주요 이슈·이벤트

- **(긍정·실현)** 하이퍼스케일러 capex 사상 최대 + Vera Rubin 도입처 확정 → 상단 인프라 수요 확정적.
- **(긍정·실현)** 네이버 엔비디아 협력 기대 급등. **차주**: 젠슨 황 방한 회동 결과(6/5~) 구체화 시 추가 모멘텀.
- **(부정·실현)** AWS FCF 붕괴·MSFT 전력 병목 → AI capex의 수익성·전력 제약 우려 부상. **차주**: 6/10 Oracle 실적의 OCI 성장률·순신규 RPO가 클라우드 인프라 센티먼트 분수령.
- **(부정·실현)** 카카오 파업 리스크 지속.

### 관련 ETF

- **글로벌**: CLOU, SKYY, WCLD. capex 사상 최대 호재 vs FCF 압박 우려 혼재.
- **한국**: TIGER 미국나스닥100(133690) 간접 노출.

### 차주 투자 관점 레이어 점수: **7 / 10**

수요는 확정적이나 capex 수익성·전력 병목·6/10 Oracle 실적 불확실성으로 상단(L1) 대비 디스카운트.

---

## L3. 파운데이션 모델·LLM·기반 AI

> **요약**: 모델 출시 속도는 사상 최고(평균 3일당 1개)이나 상장 노출은 제한적. 7일 내 한국·글로벌 상장사 직접 주가 catalyst는 약함.

### 주요 회사

**글로벌(대부분 비상장)**
- **Anthropic(비상장)**: Claude Opus 4.8 출시(5/28, AA Intelligence Index 61.4, 1M 컨텍스트) — 7일 경계선상 [llm-stats, 2026-06].
- **OpenAI(비상장)**: GPT-5.4(AA Index 56.8, 1M 컨텍스트, $2.50/$15 per 1M). Oracle·Meta와 인프라 장기계약(L2 RPO 반영).
- **Alphabet(GOOGL, Gemini)**: I/O 컨퍼런스 신규 Gemini 모델 예상 — GPT-5.5급의 점진적 업그레이드로 평가(프런티어 돌파 아님) [eWeek, 2026].
- **Meta(META, Llama)**: 오픈소스 라인 지속.

**한국**
- **네이버(035420, HyperCLOVA X)**: 엔비디아 협력 기대로 상승(L2 참조).
- **LG(003550, LG AI연구원 EXAONE 우회 노출)**: 7일 내 개별 catalyst 미확인.

### 금주 주요 이슈·이벤트

- **(중립)** 모델 출시 가속(3일당 1개, 302+ 누적)은 산업 활력 시그널이나 **상장 직접 수혜 종목 부재**. Anthropic Opus 4.8·OpenAI GPT-5.4는 비상장 → 주가 직결 catalyst 아님.
- **(긍정·간접)** 네이버 HyperCLOVA X가 엔비디아 협력 내러티브로 유일하게 주가 반영.

> **7일 내 상장사 직접 catalyst 미확인** (네이버 제외 — 네이버는 L2에서 주로 반영). 점수 신뢰도 보통.

### 관련 ETF

- **글로벌**: Roundhill Generative AI & Tech(CHAT), Global X AIQ. 모델 출시 가속의 광의 수혜.
- **한국**: TIGER 글로벌AI&로보틱스INDXX(464310) 간접.

### 차주 투자 관점 레이어 점수: **5 / 10**

산업 모멘텀은 강하나 상장 노출 제한적·7일 내 직접 주가 catalyst 약함 → 보합. Google I/O Gemini 발표가 차주 변수.

---

## L4. AI 응용·SaaS·생산성 (Copilot·Agentic AI)

> **요약**: AI 에이전트의 시트 라이선스 잠식 우려로 미들레이어 SaaS 디레이팅. Salesforce Agentforce $1B ARR 돌파는 긍정이나, 모네타이제이션 의문이 멀티플 압박.

### 주요 회사

**글로벌**
- **Salesforce(CRM)**: **Agentforce ARR $10억 돌파**(FY27 Q1, 5/27 보고), 분기 매출 +13% $11.13B, FY27 가이던스 $46B 상향(긍정). 단 MS Copilot·OpenAI 에이전트의 CRM 해자 잠식 우려로 연초 -31% [VaaSBlock/247WallSt, 2026-05-27].
- **ServiceNow(NOW)**: 에이전트 거버넌스·오케스트레이션 레이어 포지셔닝(긍정 내러티브)이나 **연초 -40%로 최악 퍼포머**. 시트 라이선스 압박 [247WallSt, 2026-04].
- **Adobe(ADBE)**: 연초 -31%, AI 디스럽션 우려 지속.
- **Microsoft(Copilot)·Palantir(PLTR)**: 에이전틱 플랫폼 내러티브 우위. PLTR은 7일 내 개별 catalyst 미확인.

**한국**
- **더존비즈온(012510)·한글과컴퓨터(030520)**: 7일 내 개별 catalyst 미확인.

### 금주 주요 이슈·이벤트

- **(긍정·실현)** Salesforce Agentforce $1B ARR — 에이전틱 매출 본격화 증거.
- **(부정·실현)** ServiceNow·Adobe·Salesforce 연초 큰 폭 하락 — AI가 SaaS 시트 라이선스를 잠식한다는 "SaaS 디스럽션" 공포가 멀티플 리레이팅. **차주**: 에이전트 매출의 시트 잠식 상쇄 여부가 관전 포인트.

### 관련 ETF

- **글로벌**: Global X AIQ, WisdomTree AI & Innovation(WTAI).
- **한국**: HANARO Fn K-AI플러스(417810).

### 차주 투자 관점 레이어 점수: **5 / 10**

Agentforce 같은 개별 호재 vs 섹터 전반 디레이팅이 상충. 방향성 불확실 → 보합. 한국 종목은 7일 catalyst 미확인.

---

## L5. 데이터·MLOps·벡터DB·검색

> **요약**: 이번 주 SaaS 내 가장 명확한 승자. Snowflake 첫 10억 달러 분기 + AWS 대형 딜로 +36% 급등, MongoDB 가이던스 상향. "SaaSpocalypse"를 데이터 레이어가 정면 반박.

### 주요 회사

**글로벌**
- **Snowflake(SNOW)**: **1Q26 매출 +32% YoY → 첫 10억 달러 분기**(전분기 +29%, 전년 +25%에서 가속), 실적 대폭 서프라이즈, 가이던스 상향, **AWS 멀티빌리언 클라우드 딜** 확대 → **+36% 급등(2026 고점)** [CNBC/SiliconANGLE/Fast Company, 2026-05-27~28]. AI 데이터클라우드 수요가 소프트웨어 랠리의 불씨.
- **MongoDB(MDB)**: FY Q1(4/30 종료) 매출 +25% $687.6M, Atlas +29%(매출의 ~75%), **가이던스 상향**, 보고 익일 추가 상승 [Benzinga, 2026-05].
- **Datadog**: 5/7 블록버스터 실적으로 +31% 급등(배경, 7일 경계 밖) — AI 소프트웨어 승자 부상 흐름의 연속.
- **Confluent(CFLT)·Elastic(ESTC)**: 7일 내 개별 실적·catalyst 미확인.

**한국**
- 직접 상장 노출 미미. 7일 내 catalyst 미확인.

### 금주 주요 이슈·이벤트

- **(긍정·실현)** Snowflake 서프라이즈 + AWS 딜 → 데이터 레이어가 AI 수혜 명확히 증명, 소프트웨어 랠리 견인. **차주**: 데이터 인프라가 AI capex 사이클의 "곡괭이·삽" 수혜주로 재평가될 여지.
- **(긍정·실현)** MongoDB 가이던스 상향 — Atlas 클라우드 DB 성장 가속.

### 관련 ETF

- **글로벌**: Global X AIQ(포함), WisdomTree WTAI.
- **한국**: 직접 노출 부재.

### 차주 투자 관점 레이어 점수: **8 / 10**

L4 응용 SaaS가 디레이팅되는 가운데 데이터 레이어는 명확한 실적 증명으로 차별화. SNOW·MDB가 AI 사이클의 구조적 수혜주로 부상.

---

## 레이어별 점수 요약

| 레이어 | 점수 | 핵심 근거 |
|--------|------|-----------|
| L1 반도체·HBM | **9** | Vera Rubin 양산·HBM4 3사 인증·젠슨 황 방한 3종 catalyst |
| L2 클라우드·인프라 | **7** | capex 사상 최대 vs FCF 압박·전력 병목·6/10 Oracle 실적 |
| L3 파운데이션 모델 | **5** | 모델 출시 가속이나 상장 직접 catalyst 약함 (보합) |
| L4 응용 SaaS | **5** | Agentforce $1B 호재 vs 섹터 디레이팅 상충 (보합) |
| L5 데이터·MLOps | **8** | Snowflake +36%·MongoDB 상향, 명확한 AI 승자 |

---

## 관련 출처

### 직전 7일 (2026-05-30 ~ 06-06, 1순위)

- [TechTimes — Nvidia Vera Rubin Full Production, HBM4 Suppliers, 2026-06-02](https://www.techtimes.com/articles/317539/20260602/nvidia-vera-rubin-enters-full-production-samsung-sk-hynix-micron-named-hbm4-suppliers.htm)
- [Investing.com — Nvidia certifies Samsung, SK Hynix, Micron for Vera Rubin HBM4, 2026-06](https://www.investing.com/news/stock-market-news/nvidia-certifies-samsung-sk-hynix-and-micron-for-vera-rubin-hbm4-supply-4728612)
- [UPI — Nvidia CEO urges SK hynix to make more HBM chips, 2026-06-02](https://www.upi.com/Top_News/World-News/2026/06/02/ai-partnership-ai-chips-HBM4E-wafer/9611780439702/)
- [Startup Fortune — SK Hynix to double wafer capacity, 2026-06](https://startupfortune.com/sk-hynix-pledges-to-double-wafer-capacity-within-five-years-as-ai-memory-shortage-deepens-toward-2030/)
- [Stocktwits — NVDA, INTC, AMD, MU fall after AVGO soft AI guidance, 2026-06-04~05](https://stocktwits.com/news-articles/markets/equity/nvda-intc-amd-mu-major-chip-stocks-fall-for-second-day-after-avgo-s-soft-ai-guidance/cZ0FhbSRez6)
- [TradingView — AMD, Broadcom, Qualcomm lead chip selloff, 2026-06-05](https://www.tradingview.com/news/gurufocus:6456707da094b:0-amd-broadcom-and-qualcomm-lead-chip-stock-sell-off-ahead-of-nvidia-earnings/)
- [서울신문 — "엔비디아♥네이버" 젠슨황 한마디에 상한가, 2026-06-01](https://www.seoul.co.kr/news/economy/securities/2026/06/01/20260601500156)
- [뉴시스 — 엔비디아에 네이버 날고 카카오는 파업에 하락, 2026-06-02](https://www.newsis.com/view/NISX20260602_0003654077)
- [MBC — 날아가는 반도체 업고 삼성전자 시총 2천조 돌파, 2026-06-01](https://imnews.imbc.com/replay/2026/nwdesk/article/6826849_37004.html)
- [TradingKey — SK하이닉스 15% 급등 신고가, HBM 부족 2028까지, 2026-06](https://www.tradingkey.com/kr/analysis/stocks/more/261879259-sk-hynix-hbm-shortage-samsung-tracker-valuation-tradingkey)
- [중앙이코노미뉴스 — 방한 앞둔 젠슨 황 동선, 2026-06](https://www.joongangenews.com/news/articleView.html?idxno=523265)
- [CNBC — Snowflake stock surges 36% on AI frenzy, 2026-05-28](https://www.cnbc.com/2026/05/28/snowflake-snow-software-stock-rally.html)
- [SiliconANGLE — Snowflake surges on earnings beat + AWS deal, 2026-05-27](https://siliconangle.com/2026/05/27/snowflakes-stock-surges-hours-solid-earnings-beat-multibillion-dollar-aws-cloud-deal/)
- [Benzinga — Snowflake beat, MongoDB raised outlook: This Week in Tech, 2026-05](https://www.benzinga.com/markets/tech/26/05/52894060/dell-snowflakes-earnings-beat-mongodbs-raised-outlook-and-more-this-week-in-tech)
- [VaaSBlock — Enterprise SaaS in Agentic AI Era (Agentforce $1B ARR), 2026](https://www.vaasblock.com/news/enterprise-saas-agentic-ai-salesforce-servicenow-workday-2026/)
- [Motley Fool — Software's big laggard, Snowflake spark, 2026-05-31](https://www.fool.com/investing/2026/05/31/software-was-the-markets-big-laggard-this-year-sno/)
- [Futurum — AI Capex 2026: The $690B Infrastructure Sprint](https://futurumgroup.com/insights/ai-capex-2026-the-690b-infrastructure-sprint/)
- [TECHi — Oracle earnings preview: OCI backlog, AI capex test (6/10 실적 예정)](https://www.techi.com/oracle-earnings-preview-oci-backlog-ai-capex-test/)

### 배경 (7일 외 — 인과관계 명시)

- (배경) [Korea Herald — Nvidia 16-layer HBM push, 2026](https://www.koreaherald.com/article/10645471) — 16-Hi HBM4 요구가 금주 3사 인증·캐파 확대 발표의 배경.
- (배경) [llm-stats — AI Updates June 2026](https://llm-stats.com/llm-updates) — Anthropic Opus 4.8(5/28)·OpenAI GPT-5.4 출시 가속이 L3 산업 모멘텀의 배경(주가 직결 아님).
- (배경) [CNBC — Datadog +31% on earnings, 2026-05-07](https://www.cnbc.com/2026/05/07/ai-winners-software-datadog-stock.html) — 금주 Snowflake 급등으로 이어진 "AI 소프트웨어 승자" 흐름의 전조.
- (배경) [eWeek — Google Gemini at I/O](https://www.eweek.com/news/google-gemini-model-io-ai-agents/) — 차주 L3 변수인 Gemini 발표 맥락.
