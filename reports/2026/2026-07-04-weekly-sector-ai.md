# [주간 섹터 리포트] AI — 2026-07-04

**데이터 기준일**: 2026-06-29 ~ 2026-07-03 (직전 7일 영업일 1순위, [JAE-88](/JAE/issues/JAE-88) 규칙 7~9 적용)
**레이어 구조**: 공통 문서 `valuechain-layers-reference.md` A섹션(5개 레이어) 전 레이어 포함
**관점**: 산업 분석 (투자 추천 아님)

---

## 0. 섹터 전체 요약 및 금주 White List

이번 주 AI 섹터는 **"Meta Compute" 쇼크**가 모든 것을 압도했다. **7/1 Meta가 자사 데이터센터의 유휴 GPU 컴퓨트를 임대·판매하는 클라우드 사업("Meta Compute")을 발표**하며 AWS·Azure·GCP·CoreWeave·Nebius와 정면 경쟁을 선언했고([Tom's Hardware/Yahoo Finance, 2026-07-01](https://www.tomshardware.com/tech-industry/meta-reportedly-plans-to-rent-out-its-ai-compute)), 이는 **"AI 컴퓨트 공급 부족" 프리미엄의 붕괴 → 메모리·GPU 수요 피크아웃 우려**로 번졌다. 7/1 미국 칩주 급락(Micron -10%+, CoreWeave -14%, Nebius -17%)에 이어 **7/2 코스피가 -7.89%(-655.32p) 폭락한 "Meta 쇼크"**([Sedaily/KED Global, 2026-07-02](https://en.sedaily.com/markets/2026/07/02/kospi-plunges-789-percent-on-meta-shock-sk-hynix-sinks-14)), SK하이닉스 -14.57%·삼성전자 -9.06%로 직전 주 시총 1위 랠리를 되돌렸다. 단, **7/3 코스피는 +5.76%(8,088.34)로 저가매수 반등**(삼성 +8.2%, SK하이닉스 +11%)하며 낙폭을 상당 부분 회복했다([Korea JoongAng Daily, 2026-07-03](https://www.koreajoongangdaily.com/business/kospi-jumps-nearly-6-as-investors-snap-up-bargainpriced-chip-stocks/12754471)). 한국 정부의 **₩392조 반도체 투자 패키지(7/2)**도 같은 날 발표됐으나 매크로 공포에 묻혔다.

L1(반도체·HBM)은 이번 주 최대 변동성·최대 하방 catalyst의 진앙, L2(클라우드)는 Meta의 신규 진입으로 경쟁 구도 재편, L4(AI SaaS)는 **Palantir 미 육군 NGC2 수주(7/1)**로 역주행 강세를 보였다.

### White List — 1순위 (직전 7일 명확한 catalyst)

| 종목 | 레이어 | 근거 (직전 7일) | 출처 |
|------|--------|------------------|------|
| **Palantir(PLTR)** | L4 | 7/1 미 육군 NGC2 Foundry 채택 + NVIDIA 파트너십, +6.78% | StocksToTrade, 2026-07-01 |
| **Meta(META)** | L2 | 7/1 Meta Compute 클라우드 진입, +8.81% 사상 최고 $796.25 | Cryptopolitan, 2026-07-01 |
| **삼성전자(005930)·SK하이닉스(000660)** | L1 | 7/2 Meta쇼크 급락(-9.06%/-14.57%) 후 7/3 반등(+8.2%/+11%) + ₩392조 투자패키지 | Sedaily/JoongAng, 2026-07-02~03 |

### White List — 2순위 관찰 후보 (신뢰도 낮음 / 음(-) catalyst / 양방향)

| 종목 | 레이어 | 사유 |
|------|--------|------|
| Micron(MU) | L1 | 7/1 -10%+ (Meta쇼크 최대 피해주) — **음(-) catalyst**, watch |
| Oracle(ORCL) | L2 | 주간 -19%(2001년 이후 최대 낙폭), AI capex 우려 — **음(-)**, 실적은 6/10(배경) |
| Snowflake(SNOW) | L5 | BofA H2 톱픽 + Unlimitail 리테일미디어 딜(6/27), 단 단독 트리거 약함 |
| ServiceNow(NOW)·Adobe(ADBE)·Salesforce(CRM) | L4 | SaaS 반등(+4%대), Guggenheim CRM Buy 상향 — 개별 catalyst는 sell-side성 |

---

## L1. 반도체·HBM·AI 가속기

> **요약**: Meta Compute 발표로 "AI 컴퓨트 공급부족" 논리가 흔들리며 **주간 최대 하방 catalyst**. Micron -10%+, 삼성·SK하이닉스 7/2 급락 후 7/3 반등. 한국 정부 ₩392조 투자패키지가 중장기 완충. 단기 변동성 극심.

**주요 회사 (글로벌)**
- **Micron(MU)**: 7/1 Meta쇼크 최대 피해주로 **-10%+**. HBM 수요 피크아웃 우려 직격 [Yahoo Finance/Tom's Hardware, 2026-07-01].
- **NVIDIA(NVDA)**: Meta쇼크에도 상대적 방어(7/1 -1.25%)했으나 주변 기간 -13.43%(레인지 $189.80~$232.28). 6/30 주총서 이사회·거버넌스 안건 통과, EVP Ajay Puri(Worldwide Field Ops) 사임(6/28) [Yahoo Finance/CNBC, 2026-06-28~30].
- **AMD·Broadcom(AVGO)·Marvell(MRVL)**: 7/1 Meta쇼크로 -6.9~-10.6% 동반 급락(AMD·Intel·SanDisk 계열) [Yahoo Finance, 2026-07-01]. AVGO~$376·MRVL~$294, 신규 단독 catalyst는 부재 [24/7 Wall St., 2026-07-01].
- **TSMC**: 7일 내 단독 catalyst 미확인 (5월 매출 +30.1% ~$13.2B는 배경).
- **DRAM/HBM 가격담합 소송(6/30)**: 삼성·SK하이닉스·Micron 대상, HBM 전환이 DDR3/4 공급을 축소해 DRAM 가격을 급등시켰다는 집단소송 제기 — **음(-) 헤드라인 리스크** [Gizmochina/Tom's Hardware, 2026-06-30].

**주요 회사 (한국)**
- **SK하이닉스(000660)**: 7/2 Meta쇼크로 **-14.57%(₩2,187,000)** 급락 — 직전 주 코스피 시총 1위 랠리를 되돌림. 단 **7/3 +11% 반등**으로 상당 회복. Nasdaq DR 상장(최대 ₩45.45조/~$29.4B, 7/10 거래 개시 예정)·HBM 인력 확보 경쟁 지속 [Sedaily/Digitimes/TradingKey, 2026-06-30~07-03].
- **삼성전자(005930)**: 7/2 **-9.06%(₩286,000)** 급락 후 7/3 +8.2% 반등. **₩392조 투자패키지 중 삼성 ₩56조(HBM 전용 팹+패키징)** 발표 [DataCenterDynamics, 2026-07-02].
- **정부 ₩392조($252.5B) 반도체 투자 패키지(7/2)**: SK하이닉스 청주 NAND/선단패키징 허브 ₩100조(패키징 ₩20조), 충청권 신규 HBM 패키징 팹. 중장기 공급망 강화 시그널 [DataCenterDynamics, 2026-07-02].
- **한미반도체(042700)·이오테크닉스(039030)·리노공업(058470)**: 7일 내 단독 catalyst 미확인 (HBM 장비 수혜는 배경, Meta쇼크 동반 변동성 노출).

**금주 주요 이슈·이벤트**
- (−) Meta Compute(7/1) → AI 컴퓨트 공급부족 프리미엄 붕괴 우려 → 메모리·GPU 수요 피크아웃 공포, 코스피 -7.89%(7/2). DRAM 가격담합 소송(6/30)도 헤드라인 부담.
- (+) 7/3 저가매수 반등(코스피 +5.76%, 삼성·SK하이닉스 두 자릿수 반등) → 급락은 매크로·센티먼트성, 펀더멘털(HBM 수주) 훼손 근거는 미약. 정부 ₩392조 투자패키지는 중장기 우호.
- 차주 영향: SK하이닉스 Nasdaq DR 상장(7/10 예정) 수급 이벤트. Meta Compute의 실제 GPU 임대 규모·가격이 HBM 수요 논쟁의 핵심 — 관련 후속 보도 주시.

**관련 ETF**
- 글로벌: SOXX·SMH·SOXL — 7/1~2 Meta쇼크로 반도체지수 -6.3% 급락, 7/3 부분 회복. 고변동 구간.
- 한국: ACE AI반도체포커스(469150)·KODEX 반도체(091160) — SK하이닉스·삼성 급락→반등에 연동, **단일종목 쏠림+매크로 변동성 이중 리스크**.

**차주 투자 관점 레이어 점수: 6/10** — HBM 펀더멘털은 견조하나 Meta 쇼크 후폭풍·수요 피크아웃 논쟁·DR 상장 수급으로 단기 변동성 극심. 직전 주(9)에서 대폭 하향.

---

## L2. 클라우드·하이퍼스케일러·인프라

> **요약**: **Meta의 클라우드 시장 진입(7/1)이 이번 주 최대 구조 변화**. Meta +8.81% 사상 최고, 반면 Oracle 주간 -19%로 AI capex 자금부담 재부각. 신규 경쟁자 등장으로 하이퍼스케일러 가격·마진 논쟁 격화.

**주요 회사 (글로벌)**
- **Meta(META)**: 7/1 "Meta Compute" 발표 — 데이터센터 유휴 GPU + 호스팅 모델 판매로 클라우드 시장 직접 진입. Zuckerberg는 AI 빌드아웃 잉여 컴퓨트 수익화로 규정. **+8.81% 사상 최고 $796.25** [Cryptopolitan/Tom's Hardware, 2026-07-01].
- **Oracle(ORCL)**: 주간 **-19%**(2001년 8월 이후 최대 낙폭), $138.83~$147.06 거래(7/3 ~$141.01), FY ~$70B AI capex 부담 재부각 — **음(-)**. 실적(Q4 +21% $19.2B, RPO $638B)은 6/10(배경) [Yahoo Finance/CNN, 2026-07-03].
- **Amazon(AWS)**: Meta 대응 차원 **AWS ~20% 가격 인상 검토** 보도 — 경쟁 격화 시그널 [TECHi, ~2026-07-01].
- **AWS–Google Cloud 멀티클라우드 네트워킹** 제품 출시(Azure 2026 합류 예정) [Network World, ~윈도 인접].

**주요 회사 (한국)**
- **네이버(035420)·카카오(035720)·KT(030200)**: 카카오–KT Cloud AI 안전 MOU(6/26, 배경), KT는 KT Cloud 재흡수 검토. 윈도 내(6/29~7/3) 확정 단독 catalyst 미확인 → **7일 내 catalyst 미확인**.

**금주 주요 이슈·이벤트**
- (양방향) Meta 진입은 클라우드 경쟁 격화(가격압박)이나, "잉여 컴퓨트 수익화"는 하이퍼스케일러 capex 회수 모델 검증이라는 양면. Meta 주가는 +8.81%로 긍정 반응, 반면 순수 GPU클라우드(CoreWeave·Nebius)는 급락.
- (−) Oracle -19%로 AI capex 자금조달 우려 재점화.
- 차주 영향: Meta Compute 실제 가격·용량 공개가 하이퍼스케일러 마진 논쟁의 방향타. AWS 가격정책 대응 주시.

**관련 ETF**
- 글로벌: CLOU·SKYY·WCLD — Meta쇼크 여파로 주간 변동, Meta 편입 ETF는 상대 방어.
- 한국: TIGER 미국나스닥100(133690) 간접 노출.

**차주 투자 관점 레이어 점수: 5/10** — Meta 진입으로 경쟁구도 불확실성↑, Oracle capex 우려. 구조 재편기.

---

## L3. 파운데이션 모델·LLM·기반 AI

> **요약**: 상장 노출은 여전히 제한적. 이번 주는 **Google Gemini 인력 이탈(→Anthropic)**과 **Gemini 3.5 Flash 저가 경량모델** 공개가 주요 흐름. 효율성 경쟁("tokenmaxxing→efficiency") 전환.

**주요 회사 (글로벌)**
- **Anthropic**: Amazon·Microsoft·Google과 업계 공통 jailbreak 심각도 스코어링 프레임워크 제안(~7/1). Claude Code 스테가노그래피 지문 기능 롤백(v2.1.197) [aiweekly/llm-stats, ~2026-07-01].
- **Google Gemini**: 핵심 기여자 Jonas Adler·Alexander Pritzel의 Anthropic 이직설 [Search Engine Journal, 윈도 내]. **Gemini 3.5 Flash** 공개 — 동급 프론티어 대비 1/2~1/3 가격 경량모델 [llm-stats/aiweekly, ~2026-07 초].
- **업계 트렌드**: 사용자 "tokenmaxxing→효율성" 이동, OpenAI/Anthropic 성장 압력 [CNBC, 2026-06-26(배경)].

**주요 회사 (한국)**
- **네이버 HyperCLOVA X / LG AI연구원**: 7일 내 catalyst 미확인 (HyperCLOVA 최신은 2025-12-26 SEED 32B THINK 등, 배경).

**금주 주요 이슈·이벤트**
- (양방향) Gemini 인력 이탈은 Google 부정·Anthropic 긍정. 저가 경량모델 경쟁 심화는 모델 마진 압박(음)이나 응용 확산(양) 양면.
- **7일 내 상장주 직접 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: 모델 가격경쟁이 L4 SaaS 원가·L2 클라우드 수요에 파급.

**관련 ETF**
- 글로벌: CHAT·AIQ — 모델 테마 간접.
- 한국: TIGER 글로벌AI&로보틱스INDXX(464310) 간접.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 7일 내 상장주 단독 catalyst 부재, 인력·가격 이슈는 비상장 중심.

---

## L4. AI 응용·SaaS·생산성 (Copilot·Agentic AI)

> **요약**: **Palantir가 주간 최강 개별 catalyst** — 미 육군 NGC2 Foundry 채택 + NVIDIA 파트너십으로 +6.78%. SaaS 전반 "SaaSpocalypse 종료" 반등(ADBE·CRM·NOW). Meta쇼크 속 역주행 강세.

**주요 회사 (글로벌)**
- **Palantir(PLTR)**: 7/1 **미 육군 차세대 지휘통제(NGC2) 클라우드 데이터 레이어로 Foundry 채택** + **NVIDIA 파트너십**(Nemotron 모델 기반 sovereign 배포). **+6.78%(~$124.68)**, DA Davidson Buy 상향·PT $175 [StocksToTrade/financialcontent, 2026-07-01~02].
- **ServiceNow(NOW)**: IBM watsonx 통합 심화, ~$106.50(7/2), sell-side Buy 상향 [StockStory, 2026-07-01~02].
- **Adobe(ADBE) +4%·Salesforce(CRM) +4.2%**: SaaS 반등, Guggenheim CRM Buy 상향 [StockStory/TradingView, 윈도 내].

**주요 회사 (한국)**
- **더존비즈온(012510)·한글과컴퓨터(030520)**: 7일 내 단독 catalyst 미확인 (7월 브랜드평판은 시장 catalyst 아님).

**금주 주요 이슈·이벤트**
- (+) Palantir 정부·방산 AI 수주 + NVIDIA 동맹 → agentic AI 실매출·주권 AI 내러티브 강화. SaaS 밸류에이션 반등.
- 차주 영향: Palantir NGC2 확산 여부가 정부 AI SaaS 테마 확대의 관전 포인트. Meta쇼크에도 SaaS는 상대적 AI 하드웨어 디커플링.

**관련 ETF**
- 글로벌: AIQ·WTAI — Palantir·SaaS 반등 수혜.
- 한국: HANARO Fn K-AI플러스(417810).

**차주 투자 관점 레이어 점수: 7/10** — Palantir 정부 수주 + SaaS 반등으로 하드웨어 쇼크와 디커플. 직전 주(5)에서 상향.

---

## L5. 데이터·MLOps·벡터DB·검색

> **요약**: BofA H2 톱픽에 Snowflake·MongoDB 재확인. Snowflake–Unlimitail 리테일미디어 딜(6/27). Confluent는 IBM 인수 계류로 단독 catalyst 소멸. 전반적으로 조용.

**주요 회사 (글로벌)**
- **Snowflake(SNOW)**: BofA H2 2026 톱 소프트웨어 픽(AI 성장·실적 비트) + **Unlimitail 리테일미디어 딜**(6/27) 주가 견인 [CoinCentral/Timothy Sykes, 2026-06-27~07초].
- **MongoDB(MDB)**: BofA 톱픽 포함, 7/1 종가 $359.38(스팟, catalyst 아님) [CoinCentral/MacroTrends].
- **Confluent(CFLT)**: **IBM 인수 확정계약**(전량 인수) 계류 — 윈도 내 업데이트 없음 → **7일 내 catalyst 미확인**.
- **Elastic(ESTC)**: 7일 내 catalyst 미확인 (최신은 3월 Q4 실적, 배경).

**주요 회사 (한국)**
- 직접 상장 노출 부재.

**금주 주요 이슈·이벤트**
- (+) BofA H2 톱픽으로 데이터 인프라 센티먼트 우호, 단 Meta쇼크 매크로에 상쇄.
- 차주 영향: Confluent-IBM 딜 클로징 진행이 데이터 인프라 M&A 온도계.

**관련 ETF**
- 글로벌: AIQ·WTAI (포함).
- 한국: 직접 노출 부재.

**차주 투자 관점 레이어 점수: 6/10** — BofA 톱픽 우호이나 7일 내 강한 단독 catalyst는 부족.

---

## 관련 출처

**직전 7일 (1순위)**
- [Tom's Hardware — Meta to rent out AI compute, 2026-07-01](https://www.tomshardware.com/tech-industry/meta-reportedly-plans-to-rent-out-its-ai-compute)
- [Yahoo Finance — Meta Compute sends AI stocks tumbling, 2026-07-01](https://finance.yahoo.com/technology/ai/articles/meta-compute-launch-sends-ai-015258040.html)
- [Cryptopolitan — Meta +8% on AI compute plan, 2026-07-01](https://www.cryptopolitan.com/meta-shares-jump-over-8-on-plans-to-sell-ai-compute-shaking-up-the-cloud-market/)
- [Sedaily — KOSPI -7.89% Meta Shock, SK hynix -14%, 2026-07-02](https://en.sedaily.com/markets/2026/07/02/kospi-plunges-789-percent-on-meta-shock-sk-hynix-sinks-14)
- [KED Global — Meta's AI pivot triggers global chip sell-off, 2026-07-02](https://www.kedglobal.com/korean-stock-market/newsView/ked202607020001)
- [Korea JoongAng Daily — KOSPI +5.76% rebound, 2026-07-03](https://www.koreajoongangdaily.com/business/kospi-jumps-nearly-6-as-investors-snap-up-bargainpriced-chip-stocks/12754471)
- [DataCenterDynamics — Samsung/SK Hynix ₩392T capacity scale-up, 2026-07-02](https://www.datacenterdynamics.com/en/news/samsung-and-sk-hynix-to-scale-up-memory-production-capacity-in-2026-to-meet-ai-demand/)
- [Gizmochina — Samsung/Micron/SK Hynix DRAM price-fixing suit, 2026-06-30](https://www.gizmochina.com/2026/06/30/samsung-micron-and-sk-hynix-sued-over-artificial-ram-shortage-and-price-hikes/)
- [StocksToTrade — Palantir Army NGC2 + NVIDIA, 2026-07-01](https://stockstotrade.com/news/palantir-technologies-inc-pltr-news-2026_07_01/)
- [StockStory — ServiceNow trades up, 2026-07-01](https://stockstory.org/us/stocks/nyse/now/news/why-up-down/servicenow-now-stock-trades-up-here-is-why-7)
- [Timothy Sykes — SNOW Unlimitail deal, 2026-06-27](https://www.timothysykes.com/news/snowflakeinc-snow-news-2026_06_27/)

**배경 (7일 외)**
- [24/7 Wall St. — Broadcom vs Marvell, 2026-07-01](https://247wallst.com/investing/2026/07/01/broadcom-vs-marvell-why-broadcoms-custom-silicon-dominance-crushes-marvells-premium-priced-ai-growth/)
- [CoinCentral — BofA bullish SNOW/MDB](https://coincentral.com/snowflake-datadog-and-mongodb-why-bofa-is-bullish-on-these-software-stocks/)
- [Search Engine Journal — Google loses AI researchers](https://www.searchenginejournal.com/google-loses-two-top-ai-researchers-to-openai-anthropic/580201/)

---

*본 리포트는 산업 분석이며 투자 추천이 아니다. 모든 핵심 주장은 직전 7일(2026-06-29~07-03) 1차 소스를 1순위로 인용했으며, 7일 외 데이터는 `(배경)` 표시. 레이어 구조는 `valuechain-layers-reference.md` A섹션 정의를 따른다.*
