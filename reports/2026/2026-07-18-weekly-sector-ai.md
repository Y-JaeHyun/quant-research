# [주간 섹터 리포트] AI — 2026-07-18

**데이터 기준일**: 2026-07-13 ~ 2026-07-17 (직전 7일 영업일 1순위, [JAE-88](/JAE/issues/JAE-88) 규칙 7~9 적용)
**레이어 구조**: 공통 문서 `valuechain-layers-reference.md` A섹션(5개 레이어) 전 레이어 포함
**관점**: 산업 분석 (투자 추천 아님)

---

## 0. 섹터 전체 요약 및 금주 White List

이번 주는 **메모리 사이클 "피크아웃(peak-out)" 공포와 TSMC 사상 최대 실적이 충돌**한 극단적 변동성 주간이었다. 한국 시장은 삼성전자·SK하이닉스 두 종목에 의해 사상 최악의 롤러코스터를 겪었다.

- **(하방) 7/13 "검은 월요일"**: **SK하이닉스가 HBM4 증설 대신 고마진 DDR5로 무게중심을 이동한다는 보도**가 AI 메모리 수요 둔화 시그널로 해석되며 -15%대 급락, 코스피 **-8.95% 6,806.93 마감**(2026년 7번째 서킷브레이커·사이드카 발동). 삼성전자 -10.70%(₩254,500), SK하이닉스 -15.37%(₩1,845,000). 미국 반도체도 동반 셀오프(AMD -7~8%, Micron 장중 -13%) [이투데이/투데이, 2026-07-13](https://www.etoday.co.kr/news/view/2603195); [gurufocus, 2026-07-13](https://www.gurufocus.com/news/8954963/nvidia-broadcom-amd-lead-ai-chip-stock-selloff-after-sk-hynix-slump).
- **(상방) 7/15 급반등 +6.24%**: 미국 6월 CPI +3.5%(예상 +3.8% 하회)로 긴축 우려 완화, 외국인 2.32조원 순매수 복귀. 코스피 **+6.24% 7,284.41**, SK하이닉스 +8.8%(₩2,082,000), 삼성전자 +6%(₩279,500) [Businesskorea, 2026-07-15](https://www.businesskorea.co.kr/news/articleView.html?idxno=273112).
- **(재하락) 7/16 -6.38%**: **CoreWeave의 메모리 가격 헤지 검토**(로이터 7/14)와 **중국 CXMT 증설** 우려 재부각으로 메모리주 재급락, 코스피 -6.38% 6,820.60 [Newspim, 2026-07-16](https://www.newspim.com/news/view/20260716001003).
- **(상방 구조) 7/16 TSMC 사상 최대 실적**: 매출 ~$40.2B(+36% YoY), 순이익 NT$706.56B(+77.4% 사상최대), 마진 67.7%, **캐펙스 $60~64B로 상향**(기존 $52~56B), FY2026 성장 "40% 초과" 가이던스. 그럼에도 ADR -3.5% — "good news sold" 시그널 [TechTimes, 2026-07-16](https://www.techtimes.com/articles/320696/20260716/tsmc-posts-record-quarter-ai-chip-demand-pushes-full-year-growth-outlook-past-40.htm).

관통하는 두 축: **① 소프트웨어→하드웨어로의 캐펙스 이동**(IBM이 직접 "고객이 서버·스토리지·메모리로 캐펙스를 전환"이라 진단), **② 메모리 사이클 피크아웃 논쟁**(HBM4 지연 + CXMT + CoreWeave 헤지). L1(반도체)은 최대 진앙, L4(SaaS)는 IBM 쇼크로 최대 음(-) 이벤트.

### White List — 1순위 (직전 7일 명확한 catalyst)

| 종목 | 레이어 | 근거 (직전 7일) | 출처 |
|------|--------|------------------|------|
| **TSMC** | L1 | 7/16 2분기 사상 최대 실적 + 캐펙스 $60~64B 상향 + FY성장 40%+ — AI 수요 구조 확인 | TechTimes/Investing.com, 2026-07-16 |
| **삼성전자(005930)** | L1 | 7/15 +6% 반등, HBM 대장. 단 7/13 -10.7% 급락 후 회복 — 양방향 고변동 | Businesskorea, 2026-07-15 |
| **SK하이닉스(000660)** | L1 | 7/15 +8.8% 반등. 단 7/13 -15.37% HBM4 지연 우려 급락 촉발주 — 양방향 | Investing.com KR, 2026-07-15 |

### White List — 2순위 관찰 후보 (신뢰도 낮음 / 음(-) catalyst / 양방향)

| 종목 | 레이어 | 사유 |
|------|--------|------|
| Micron(MU) | L1 | 7/13~14 장중 -13%(음), 단 CY2026 HBM 완판·HBM4 36GB Vera Rubin 출하 — 양방향 |
| Intel(INTC) | L1 | 7/15 $100 지지선 붕괴(음), JPMorgan 톱숏 지정, 7/23 실적 대기 |
| CoreWeave(CRWV) | L2 | 7/14 메모리 가격 헤지 검토(로이터) — **수요 피크 우려 시그널**, 5일 연속 하락(음) |
| IBM | L4 | 7/14 2분기 실적 경고 -24~25%(**음, 사상 최악**) — SaaS 전반 셀오프 촉발 |

---

## L1. 반도체·HBM·AI 가속기

> **요약**: 금주 시장의 진앙. SK하이닉스 HBM4 증설 지연 우려(7/13)로 -15% 급락→코스피 8.95% 붕괴, 7/15 CPI로 반등, 7/16 CXMT·CoreWeave 헤지로 재급락. TSMC 사상 최대 실적(7/16)이 유일한 구조적 상방 앵커.

**주요 회사 (글로벌)**
- **TSMC**: 7/16 2분기 매출 ~$40.2B(+36% YoY)·순이익 사상 최대·마진 67.7%·HPC 매출 66%. **캐펙스 $60~64B 상향**, 애리조나 $100B 증설. 실적 서프라이즈에도 ADR -3.5% [TechTimes/Investing.com, 2026-07-16].
- **Micron(MU)**: 7/13~14 ~$937에서 7/16 ~$853(-5.6%). CY2026 HBM 물량·가격 완판, NVIDIA Vera Rubin용 HBM4 36GB 12H 양산 출하 개시 [TradingKey, 2026-07].
- **Intel(INTC)**: 7/15 ~$102.99로 $100 지지선 붕괴, 18A/파운드리 우려 + JPMorgan 톱숏. 7/23 실적(윈도 밖) [FXLeaders, 2026-07-16].
- **AMD·Broadcom·Marvell·Qualcomm**: 7/13 셀오프 동반 -4~8%(AMD -7~8%, Marvell 월 -32%) [24/7 Wall St., 2026-07-13].

**주요 회사 (한국)**
- **삼성전자(005930)**: 7/13 -10.70%(₩254,500) → 7/15 +6%(₩279,500). HBM4 지연 우려·반등의 양방향 진폭. IBK투자증권 7월 톱픽 유지 [Businesskorea/Investing.com, 2026-07-13~15].
- **SK하이닉스(000660)**: **7/13 -15.37%(₩1,845,000) 급락 촉발주** — HBM4 증설 지연→DDR5 우선 보도 + 나스닥 ADR 상장($26.5B) 후 차익실현. 7/15 +8.8%(₩2,082,000) 반등. KB증권 Buy(TP ₩4.2m)·"과도한 셀오프", 한국투자증권은 2026/27 OP 9%/11% 하향 [Investing.com KR/Daum, 2026-07-13~15].
- **한미반도체(042700)·리노공업(058470)·이오테크닉스(039030)**: 7일 내 종목 단독 catalyst 미확인 — HBM 밸류체인 베타로 동반 급락(월)·반등(수)·재하락(목).

**금주 주요 이슈·이벤트**
- (−) 7/13 SK하이닉스 HBM4 지연 우려 → 코스피 -8.95% 검은 월요일, 미 반도체 시총 대량 증발.
- (−) 7/16 CXMT 증설 + CoreWeave 메모리 헤지 → 피크아웃 공포 재점화.
- (+) 7/16 TSMC 사상 최대 실적·캐펙스 상향 → AI 수요 구조 견조 확인. 7/15 CPI로 반등.
- 차주 영향: Intel(7/23)·삼성전자(7/24 그룹)·GEV(7/22) 등 실적 시즌에서 HBM 피크아웃 논쟁 향방 결정.

**관련 ETF**
- 글로벌: **SMH** $590.77(7/15, -1.59%/일, +65% YTD), **SOXX** 1년래 최악 주간. 고변동 지속 [ts2.tech].
- 한국: ACE AI반도체포커스(469150)·KODEX 반도체(091160) — 삼성·SK하이닉스 급락→반등에 연동, 단일종목+매크로 이중 리스크.

**차주 투자 관점 레이어 점수: 5/10** — TSMC 실적은 구조적 우호이나 HBM4 지연·CXMT·CoreWeave 헤지·피크아웃 공포로 단기 변동성 극심. 직전 주(6)에서 하향.

---

## L2. 클라우드·하이퍼스케일러·인프라

> **요약**: 하이퍼스케일러 실적은 7월 말이라 윈도 내 부재. 단 **CoreWeave 메모리 헤지 검토(7/14)**가 수요 피크 논쟁을 촉발, 코스피 7/16 재급락의 방아쇠가 됨.

**주요 회사 (글로벌)**
- **CoreWeave(CRWV)**: 7/14 로이터 단독 — **메모리 가격 하락 헤지 위해 파생·풋옵션 검토**(Micron·SanDisk 장기 공급계약 가격하단 대응, 2026 캐펙스 $31~35B). 수요 피크 우려 시그널로 해석. 7배 레버리지 우려로 5일 연속 하락 [Reuters via Investing.com, 2026-07-14](https://www.investing.com/news/stock-market-news/exclusiveai-cloud-company-coreweave-explores-wall-street-playbook-to-hedge-memorychip-price-risk-4792033).
- **Microsoft·Amazon·Alphabet·Meta·Oracle**: 캐펙스 백로그 구조 견조(Azure ~$80B 미충족 백로그·전력 제약, AWS $244B, Oracle $523B) — 배경. 윈도 내 개별 단독 catalyst 부재.

**주요 회사 (한국)**
- **네이버(035420)·카카오(035720)·KT(030200)**: 윈도 내 확정 단독 catalyst 미확인 → **7일 내 catalyst 미확인**. (카카오뱅크는 금융 방어주로 강세 — 그 외 동향 리포트 참조)

**금주 주요 이슈·이벤트**
- (−) CoreWeave 헤지 = 고객이 메모리 가격 하락을 예상한다는 시그널 → 수요 피크 우려.
- (양방향) 캐펙스 백로그·전력 제약은 구조적 수요 확인이나, ROI 회의론 병존.
- 차주 영향: 7월 말~8월 미 빅테크 2분기 실적의 AI 캐펙스 가이던스가 핵심.

**관련 ETF**
- 글로벌: CLOU·SKYY·WCLD — 캐펙스 회의론·메모리 헤지 여파 변동.
- 한국: TIGER 미국나스닥100(133690) 간접 노출.

**차주 투자 관점 레이어 점수: 5/10 (신뢰도 낮음)** — 하이퍼스케일러 단독 catalyst 부재, CoreWeave 헤지로 수요 피크 논쟁. 직전 주(5) 유지.

---

## L3. 파운데이션 모델·LLM·기반 AI

> **요약**: 모델 출시 러시 주간 — OpenAI GPT-Live/GPT-5.6, xAI Grok 4.5, Google Gemini 3.5 Pro GA(7/17 유출). 상장 노출은 여전히 제한적.

**주요 회사 (글로벌)**
- **OpenAI**: **GPT-Live**(전이중 음성 모델·실시간 번역·라이브 웹검색) + **GPT-5.6 계열(Sol/Terra/Luna)** 출시 [buildfastwithai, 2026-07-13](https://www.buildfastwithai.com/blogs/ai-news-today-july-13-2026).
- **xAI Grok 4.5**: 코딩·지식작업 성능 향상 + 토큰 효율화 [buildfastwithai, 2026-07-13].
- **Google Gemini 3.5 Pro**: GA 날짜 **7/17** 유출 — 2M 토큰 컨텍스트, Deep Think($250/mo Ultra), ~$1.25/$10 per M 토큰 [buildfastwithai, 2026-07-13].
- **Anthropic**: 사이버보안 프로그램 "Project Glasswing"(Claude Mythos) 50→150개 조직(15개국) 확대 [AI Weekly](https://aiweekly.co/ai-news-today/anthropic-news).

**주요 회사 (한국)**
- **네이버 HyperCLOVA X / LG AI연구원**: 7일 내 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (+) 모델 cadence 가속, "tokenmaxxing→efficiency" 내러티브.
- (구조적) 프론티어 랩 간 커모디티화·가격 경쟁 심화.
- **7일 내 상장주 직접 catalyst 제한적** — 점수 신뢰도 낮음.
- 차주 영향: Gemini 3.5 Pro GA 실사용·엔터프라이즈 채택 데이터.

**관련 ETF**
- 글로벌: CHAT·AIQ — 모델 테마 간접.
- 한국: TIGER 글로벌AI&로보틱스INDXX(464310) 간접.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 모델 출시 활발하나 직접 상장주 catalyst 제한적. 직전 주(5) 유지.

---

## L4. AI 응용·SaaS·생산성 (Copilot·Agentic AI)

> **요약**: 금주 SaaS 최대 사건은 **IBM 2분기 실적 경고(-24~25%, 사상 최악)** → SaaS 전반 셀오프. 단, Palantir는 +14.55% 역주행. 엔터프라이즈 AI 표준 연합도 형성.

**주요 회사 (글로벌)**
- **IBM**: 7/14 잠정 2분기 매출 ~$17.2B(예상 ~$17.85B 하회), 비GAAP EPS $2.93(예상 $3.02). **-24~25% ~$217 폭락(1968년 이래 최악 일간)**. CEO Krishna — 대형 SW 딜 정체 + **고객이 공급제약 하드웨어(서버·스토리지·메모리)로 캐펙스 전환** 진단 [Motley Fool, 2026-07-14](https://www.fool.com/coverage/stock-market-today/2026/07/14/stock-market-today-july-14-ibm-plunges-on-second-quarter-warning-as-enterprise-spending-shifts/).
- **SaaS 전염(7/14)**: ServiceNow -5.5%, Adobe -4.26%($220.78), Appian -2.9%, Salesforce·Workday 하락. 반면 사이버보안(CrowdStrike·Okta·Zscaler) 랠리 — 로테이션 [StockStory/Yahoo, 2026-07-14](https://finance.yahoo.com/markets/stocks/articles/adobe-servicenow-appian-stocks-trade-211111822.html).
- **Palantir(PLTR)**: 주간 +14.55% — AI 인프라 트레이드 리테일 재유입, SaaS 약세 속 역주행 [24/7 Wall St., 2026-07-13](https://247wallst.com/investing/2026/07/13/forget-palantir-as-it-bounces-back-and-get-in-salesforce-before-wall-street-wakes-up-to-real-value/).
- **엔터프라이즈 AI 표준 연합(7/13, The Information)**: Google·Microsoft·Salesforce·Snowflake·ServiceNow + Cisco·Databricks·GitHub·Hugging Face·NVIDIA가 공용 에이전트 프로토콜(A2A, Linux Foundation Agentic AI Foundation) 지지 — OpenAI/Anthropic 대항 [The Information, 2026-07](https://www.theinformation.com/newsletters/applied-ai/google-microsoft-team-beat-back-anthropic-openai).

**주요 회사 (한국)**
- **더존비즈온(012510)·한글과컴퓨터(030520)**: 7일 내 단독 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (−) IBM 경고 = 엔터프라이즈 SW 예산이 하드웨어에 잠식되는 구조적 역풍 시그널 — 레이어 전반 압박.
- (+) Palantir 역주행, SaaS 벤더 에이전트 연합으로 엔터프라이즈 해자 강화.
- 차주 영향: 7월 말 미 SW 실적 시즌에서 agentic AI 매출 기여 확인.

**관련 ETF**
- 글로벌: AIQ·WTAI — IBM 쇼크로 변동.
- 한국: HANARO Fn K-AI플러스(417810).

**차주 투자 관점 레이어 점수: 5/10** — IBM 쇼크로 엔터프라이즈 SW 예산 압박 구조 노출. Palantir 예외. 직전 주(6)에서 하향.

---

## L5. 데이터·MLOps·벡터DB·검색

> **요약**: 조용한 주간. Snowflake·ServiceNow의 엔터프라이즈 에이전트 프로토콜 연합 참여(L4)가 유일한 전략적 접점. Confluent·Elastic은 7일 내 catalyst 부재.

**주요 회사 (글로벌)**
- **Snowflake(SNOW)**: 엔터프라이즈 AI 에이전트 프로토콜 연합 참여(L4 참조). 직전 blowout 분기(FY27 제품매출 가이던스 $5.84B/+31%)는 배경, 윈도 내 신규 단독 catalyst 미확인 [24/7 Wall St., 2026-07-07](https://247wallst.com/investing/2026/07/07/snowflakes-80-billion-data-bet-is-starting-to-show-results/).
- **MongoDB(MDB)**: Citi 톱3 SW픽(배경), 윈도 내 단독 catalyst 미확인.
- **Confluent(CFLT)·Elastic(ESTC)**: **7일 내 catalyst 미확인** — 1차 소스 부재.

**주요 회사 (한국)**
- 직접 상장 노출 부재.

**금주 주요 이슈·이벤트**
- (중립) 데이터 인프라는 매크로 셀오프에 동조, 개별 단독 catalyst 부재.
- **7일 내 강한 단독 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: SW 실적 시즌에서 데이터 소비량·AI 워크로드 지표 확인.

**관련 ETF**
- 글로벌: AIQ·WTAI (포함).
- 한국: 직접 노출 부재.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 에이전트 연합 참여 외 단독 catalyst 부재. 직전 주(5) 유지.

---

## 관련 출처

**직전 7일 (1순위)**
- [이투데이 — 반도체 투매 검은 월요일 코스피 -8.95%, 2026-07-13](https://www.etoday.co.kr/news/view/2603195)
- [gurufocus — Nvidia/Broadcom/AMD selloff after SK Hynix slump, 2026-07-13](https://www.gurufocus.com/news/8954963/nvidia-broadcom-amd-lead-ai-chip-stock-selloff-after-sk-hynix-slump)
- [24/7 Wall St. — Intel/AMD/Applied Materials drop 4%, 2026-07-13](https://247wallst.com/investing/2026/07/13/intel-amd-and-applied-materials-drop-4-as-sk-hynix-rout-and-oil-spike-hit-chip-stocks/)
- [Reuters via Investing.com — CoreWeave memory-chip hedge, 2026-07-14](https://www.investing.com/news/stock-market-news/exclusiveai-cloud-company-coreweave-explores-wall-street-playbook-to-hedge-memorychip-price-risk-4792033)
- [Motley Fool — IBM plunges on Q2 warning, 2026-07-14](https://www.fool.com/coverage/stock-market-today/2026/07/14/stock-market-today-july-14-ibm-plunges-on-second-quarter-warning-as-enterprise-spending-shifts/)
- [StockStory/Yahoo — Adobe/ServiceNow/Appian trade down, 2026-07-14](https://finance.yahoo.com/markets/stocks/articles/adobe-servicenow-appian-stocks-trade-211111822.html)
- [Businesskorea — 코스피 6.24% 폭등 7284, 2026-07-15](https://www.businesskorea.co.kr/news/articleView.html?idxno=273112)
- [Newspim — 코스피 6.38% 급락 6820, 2026-07-16](https://www.newspim.com/news/view/20260716001003)
- [TechTimes — TSMC record quarter, FY growth >40%, 2026-07-16](https://www.techtimes.com/articles/320696/20260716/tsmc-posts-record-quarter-ai-chip-demand-pushes-full-year-growth-outlook-past-40.htm)
- [FXLeaders — Intel below $100 on chip panic, 2026-07-16](https://www.fxleaders.com/news/2026/07/16/intel-stock-intc-falls-below-100-as-chip-sector-panic-and-gelsinger-criticism-highlights-long-term-challenges/)
- [The Information — Google/Microsoft alliance vs OpenAI/Anthropic, 2026-07](https://www.theinformation.com/newsletters/applied-ai/google-microsoft-team-beat-back-anthropic-openai)
- [24/7 Wall St. — Palantir +14.55% week, 2026-07-13](https://247wallst.com/investing/2026/07/13/forget-palantir-as-it-bounces-back-and-get-in-salesforce-before-wall-street-wakes-up-to-real-value/)
- [buildfastwithai — AI News July 13 2026](https://www.buildfastwithai.com/blogs/ai-news-today-july-13-2026)

**배경 (7일 외)**
- [24/7 Wall St. — Snowflake $80B data bet, 2026-07-07](https://247wallst.com/investing/2026/07/07/snowflakes-80-billion-data-bet-is-starting-to-show-results/)
- [Investing.com — TSMC Q2 profit record, capex raise, 2026-07-16](https://www.investing.com/news/earnings/tsmc-q2-profit-blows-past-estimates-on-robust-aifueled-demand-4794650)

---

*본 리포트는 산업 분석이며 투자 추천이 아니다. 모든 핵심 주장은 직전 7일(2026-07-13~17) 1차 소스를 1순위로 인용했으며, 7일 외 데이터는 `(배경)` 표시. 레이어 구조는 `valuechain-layers-reference.md` A섹션 정의를 따른다.*
