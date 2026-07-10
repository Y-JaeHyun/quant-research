# [주간 섹터 리포트] AI — 2026-07-11

**데이터 기준일**: 2026-07-06 ~ 2026-07-10 (직전 7일 영업일 1순위, [JAE-88](/JAE/issues/JAE-88) 규칙 7~9 적용)
**레이어 구조**: 공통 문서 `valuechain-layers-reference.md` A섹션(5개 레이어) 전 레이어 포함
**관점**: 산업 분석 (투자 추천 아님)

---

## 0. 섹터 전체 요약 및 금주 White List

지난주 "Meta Compute 쇼크"(7/1)의 여진이 이번 주 전반부를 지배했으나, 후반부는 **삼성전자 2분기 어닝 서프라이즈**와 **저가매수 반등**으로 급격히 방향을 틀었다. 두 개의 대립하는 힘이 한 주를 규정했다.

- **(하방) AI 캐펙스 회의론 + DeepSeek 자체 칩 리스크**: 7/6~7/8 미국 반도체 셀오프가 재점화되며 시총 1조 달러 이상이 증발했다. **Intel은 7/8 -20%+ 급락**([Forbes, 2026-07-08](https://www.forbes.com/sites/petercohan/2026/07/08/intel-stock-down-21-inside-the-july-2026-semiconductor-selloff/)), Micron·Marvell·Broadcom·AMD 동반 하락, SMH -3%+. 원인은 수요 붕괴가 아니라 **① AI 인프라 투자 회수율(ROI) 의심, ② 닷컴급 밸류에이션, ③ 매파적 Fed**의 복합 우려였다([Forbes, 2026-07-08](https://www.forbes.com/sites/petercohan/2026/07/08/intel-stock-down-21-inside-the-july-2026-semiconductor-selloff/)). 여기에 **7/7 로이터 보도 — 중국 DeepSeek가 추론(inference) 전용 자체 AI 칩 개발** 소식이 겹치며 NVIDIA -2.5% 등 추가 하락을 유발했다([Mezha/Reuters, 2026-07-07](https://mezha.net/eng/bukvy/8450321d_nasdaq_set_to/)).
- **(상방) 삼성 어닝 서프라이즈 + HBM4**: 7/9 **삼성전자 2분기 영업이익 전년비 19배(19-fold) 급증** 잠정 실적 발표([Yahoo Finance, 2026-07-09](https://finance.yahoo.com/markets/stocks/articles/samsung-blowout-quarter-still-spooks-152704421.html)). 동시에 **삼성 HBM4가 NVIDIA 메모리 병목을 해소**한다는 기술 진전 보도가 이어졌다([science-technology.news, 2026-07-09](https://science-technology.news-articles.net/content/2026/07/09/samsung-s-hbm4-breakthrough-solves-nvidia-s-memory-bottleneck.html)). 다만 시장은 "blowout quarter가 오히려 chip trade를 겁준다(spooks)"는 역설적 반응(피크아웃 경계)도 보였다.
- **주간 결산(코스피)**: 7/6 +2.71%(삼성 +4.04%) 회복 출발 → 중반 변동성 → **7/10 코스피 +2.52%(+184.03p) 7,475.94 마감**([Seoul Economic Daily, 2026-07-10](https://en.sedaily.com/finance/2026/07/10/kospi-closes-up-18403-points-at-747594)). 다만 7월 월간으로는 반도체 변동성에 코스피가 여전히 큰 폭 하락 구간에 있었고, 방어적 은행주로의 로테이션이 병행됐다([Seoul Economic Daily, 2026-07-09](https://en.sedaily.com/finance/2026/07/09/bank-stocks-rally-as-kospi-slumps-shine-as-defensive-plays)).

L1(반도체·HBM)은 여전히 최대 변동성 진앙 — 셀오프(전반)와 삼성 어닝·HBM4(후반)의 교차. L2(클라우드)는 Meta Compute 여진 지속, L4(SaaS)는 상대적 디커플 방어.

### White List — 1순위 (직전 7일 명확한 catalyst)

| 종목 | 레이어 | 근거 (직전 7일) | 출처 |
|------|--------|------------------|------|
| **삼성전자(005930)** | L1 | 7/9 2분기 영업이익 전년비 19배 급증 잠정 실적 + HBM4 NVIDIA 병목 해소 보도, 7/6 +4.04% 회복 출발 | Yahoo Finance/science-technology.news, 2026-07-09 |
| **SK하이닉스(000660)** | L1 | 7/6 +1.77% 회복, 7/10 코스피 반등 주도, HBM 대장주 | TradingKey/Sedaily, 2026-07-06~10 |

### White List — 2순위 관찰 후보 (신뢰도 낮음 / 음(-) catalyst / 양방향)

| 종목 | 레이어 | 사유 |
|------|--------|------|
| Intel(INTC) | L1 | 7/8 **-20%+ 급락** — 셀오프 최대 피해주, **음(-) catalyst**, 12개월 목표가 이미 초과 |
| Micron(MU) | L1 | 7/7 -4.7% 셀오프 동조(음)이나 12개월 목표가 상단 +66% 여력 — 양방향 |
| NVIDIA(NVDA) | L1/L2 | 7/7 DeepSeek 자체칩 보도로 -2.5%(음), 단 목표가 +56% 여력 — 양방향 watch |
| DeepSeek(비상장) | L3 | 7/7 추론 전용 자체 AI칩 개발 보도 — NVIDIA 의존도 축소 시그널(구조적) |

---

## L1. 반도체·HBM·AI 가속기

> **요약**: 전반부 AI 캐펙스 회의론 셀오프(Intel -20%+, 7/8)와 DeepSeek 자체칩 리스크(7/7)로 급락, 후반부 삼성 2분기 어닝 서프라이즈(+19배)·HBM4 진전(7/9)으로 반전. "펀더멘털은 견조, 센티먼트는 극단 변동"의 한 주.

**주요 회사 (글로벌)**
- **Intel(INTC)**: 7/8 **-20%+ 급락**. AI 인프라 지출 회의론 셀오프의 최대 피해주. 이례적으로 주가가 12개월 목표가를 8% 상회하는 상태 — **음(-) catalyst** [Forbes, 2026-07-08].
- **Micron(MU)**: 7/7 -4.7%, 7/8 프리마켓 -5%. 셀오프 동조. 단 애널리스트 12개월 목표가 +66% 상방 여력 [Forbes/CNBC, 2026-07-07~08].
- **NVIDIA(NVDA)**: 7/7 **-2.5%** — 로이터의 **DeepSeek 추론 전용 자체 AI칩 개발** 보도로 의존도 축소 우려. 단 목표가 +56% 여력 [Mezha/Reuters, 2026-07-07].
- **KLA·Lam Research·Applied Materials·Marvell·Broadcom·AMD·Qualcomm**: 7/7~8 셀오프 동반 -4%+ [CNBC/Forbes, 2026-07-07~08].
- **TSMC**: 7일 내 단독 catalyst 미확인 (셀오프 동조 변동).

**주요 회사 (한국)**
- **삼성전자(005930)**: 7/9 **2분기 영업이익 전년비 19배(19-fold) 급증** 잠정 실적 발표 — HBM·메모리 업황 회복 확인. 동시 **삼성 HBM4가 NVIDIA 메모리 병목 해소** 기술 보도. 7/6 +4.04%(322,500원) 회복 출발. 단, 시장은 "blowout quarter"에도 피크아웃 경계로 양가 반응 [Yahoo Finance/science-technology.news/TradingKey, 2026-07-06~09].
- **SK하이닉스(000660)**: 7/6 +1.77%(2,468,000원) 회복. HBM 대장주로 7/10 코스피 +2.52% 반등 주도. 지난주 Meta쇼크 급락(-14.57%)에서 회복 국면 [TradingKey/Sedaily, 2026-07-06~10].
- **한미반도체(042700)·이오테크닉스(039030)·리노공업(058470)**: 7일 내 단독 catalyst 미확인 (HBM 장비 수혜 배경, 셀오프·반등 동반 변동).

**금주 주요 이슈·이벤트**
- (−) 7/6~8 AI 캐펙스 회의론 재점화 셀오프 — 시총 1조 달러+ 증발, Intel -20%+. DeepSeek 자체칩(7/7)이 NVIDIA 의존도 구조 논쟁 촉발.
- (+) 7/9 삼성 2분기 영업이익 +19배 어닝 서프라이즈 + HBM4 병목 해소 진전 → 메모리 펀더멘털 확인. 7/6·7/10 코스피 회복.
- (양방향) 어닝 호조가 오히려 "피크아웃" 경계를 부추긴 역설. HBM 수요 논쟁 지속.
- 차주 영향: 삼성 확정 실적·컨퍼런스콜 세부(HBM4 NVIDIA 공급 시점), DeepSeek 자체칩 양산 로드맵 후속 보도가 방향타.

**관련 ETF**
- 글로벌: SOXX·SMH·SOXL — 7/7~8 SMH -3%+ 급락, 후반 삼성 어닝에 부분 회복. 고변동 지속.
- 한국: ACE AI반도체포커스(469150)·KODEX 반도체(091160) — 삼성·SK하이닉스 급락→반등에 연동, 단일종목 쏠림+매크로 이중 리스크.

**차주 투자 관점 레이어 점수: 6/10** — 삼성 어닝·HBM4는 펀더멘털 우호이나, AI 캐펙스 ROI 논쟁·DeepSeek 자체칩·Fed 매파 우려로 단기 변동성 극심. 직전 주(6) 유지.

---

## L2. 클라우드·하이퍼스케일러·인프라

> **요약**: 지난주 Meta Compute(7/1) 진입의 여진 지속. 이번 주 단독 신규 catalyst는 제한적이나, AI 캐펙스 ROI 회의론이 하이퍼스케일러 밸류에이션 논쟁으로 확산. 순수 GPU클라우드(neocloud)의 변동성 잔존.

**주요 회사 (글로벌)**
- **Meta(META)·Microsoft(MSFT)·Amazon(AMZN)·Alphabet(GOOGL)**: Meta Compute 여진 속 AI 캐펙스 회수율 논쟁의 중심. 윈도(7/6~10) 내 개별 단독 catalyst 확정 보도 제한적 → 셀오프 매크로에 동조.
- **Oracle(ORCL)**: 지난주 -19% 낙폭 후 AI capex 자금부담 우려 잔존(배경). 7일 내 신규 단독 catalyst 미확인.
- **neocloud (CoreWeave·Nebius)**: Meta Compute + DeepSeek 자체칩 이중 압박으로 변동성 지속 관찰.

**주요 회사 (한국)**
- **네이버(035420)·카카오(035720)·KT(030200)**: 윈도 내(7/6~10) 확정 단독 catalyst 미확인 → **7일 내 catalyst 미확인**. (카카오 계열은 카카오뱅크가 방어 은행주로 강세 — 금융 섹터 참조)

**금주 주요 이슈·이벤트**
- (−) AI 캐펙스 ROI 회의론이 하이퍼스케일러 지출 지속가능성 논쟁으로 확산.
- (양방향) Meta Compute 잉여 컴퓨트 수익화 모델의 실효성 검증은 여전히 진행형.
- **7일 내 클라우드 단독 catalyst 제한적** — 점수 신뢰도 다소 낮음.
- 차주 영향: 7월 말~8월 미국 빅테크 2분기 실적에서 AI capex 가이던스가 핵심.

**관련 ETF**
- 글로벌: CLOU·SKYY·WCLD — AI 캐펙스 회의론 여파로 변동.
- 한국: TIGER 미국나스닥100(133690) 간접 노출.

**차주 투자 관점 레이어 점수: 5/10 (신뢰도 낮음)** — 신규 단독 catalyst 부재, capex 회의론 지속. 구조 재편기 유지.

---

## L3. 파운데이션 모델·LLM·기반 AI

> **요약**: 이번 주 최대 이슈는 **DeepSeek 자체 추론 칩 개발 보도(7/7)** — 모델 기업이 하드웨어 수직계열화로 이동하는 구조적 시그널. 상장 노출은 여전히 제한적.

**주요 회사 (글로벌)**
- **DeepSeek(비상장)**: 7/7 로이터 — **추론(inference) 전용 자체 AI칩 개발** 보도. 학습이 아닌 추론 단계용으로, NVIDIA·Huawei 칩 의존도 축소 목표. NVIDIA -2.5% 유발 [Mezha/Reuters, 2026-07-07].
- **OpenAI·Anthropic·Google Gemini·Meta(Llama)·xAI**: 윈도 내 개별 상장 노출 단독 catalyst 미확인. 모델 효율성·가격 경쟁 트렌드 지속(배경).

**주요 회사 (한국)**
- **네이버 HyperCLOVA X / LG AI연구원**: 7일 내 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (구조적) DeepSeek 자체칩은 모델↔하드웨어 수직계열화 신호 — 중장기 NVIDIA·메모리 수요 구조 논쟁. 단기 상장주 직접 catalyst는 NVIDIA 하락(음)으로 발현.
- **7일 내 상장주 직접 catalyst 제한적** — 점수 신뢰도 낮음.
- 차주 영향: DeepSeek 칩 양산 파트너(파운드리)·성능 세부가 반도체 밸류체인에 파급.

**관련 ETF**
- 글로벌: CHAT·AIQ — 모델 테마 간접.
- 한국: TIGER 글로벌AI&로보틱스INDXX(464310) 간접.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — DeepSeek 이슈는 비상장·하드웨어 파급 중심, 직접 상장주 catalyst 제한적.

---

## L4. AI 응용·SaaS·생산성 (Copilot·Agentic AI)

> **요약**: 반도체 셀오프 속 SaaS는 상대적 하드웨어 디커플 방어. 지난주 Palantir NGC2 모멘텀 여진 지속. 단, 윈도 내 강한 신규 단독 catalyst는 제한적.

**주요 회사 (글로벌)**
- **Palantir(PLTR)**: 지난주 미 육군 NGC2 + NVIDIA 파트너십(7/1) 모멘텀 여진. 윈도 내 신규 확정 계약 단독 보도는 제한적, agentic·정부 AI 내러티브 지속.
- **Salesforce(CRM)·ServiceNow(NOW)·Adobe(ADBE)·Microsoft(Copilot)**: SaaS 전반 반도체 셀오프 대비 상대 방어. 윈도 내 개별 단독 catalyst 제한적.

**주요 회사 (한국)**
- **더존비즈온(012510)·한글과컴퓨터(030520)**: 7일 내 단독 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (+) SaaS는 AI 하드웨어 셀오프와 상대적 디커플 — 방어적 성격.
- **7일 내 강한 신규 단독 catalyst 제한적** — Palantir 여진 중심.
- 차주 영향: 미국 SW 2분기 실적 시즌(7월 말~) 진입, agentic AI 매출 기여 확인이 관건.

**관련 ETF**
- 글로벌: AIQ·WTAI — SaaS 상대 방어.
- 한국: HANARO Fn K-AI플러스(417810).

**차주 투자 관점 레이어 점수: 6/10** — 하드웨어 디커플 방어이나 신규 단독 catalyst 약화. 직전 주(7)에서 소폭 하향.

---

## L5. 데이터·MLOps·벡터DB·검색

> **요약**: 이번 주 조용. 반도체 매크로 셀오프에 동조 변동. Snowflake·MongoDB 등 데이터 인프라 개별 단독 catalyst 윈도 내 제한적.

**주요 회사 (글로벌)**
- **Snowflake(SNOW)·MongoDB(MDB)·Confluent(CFLT)·Elastic(ESTC)**: 지난주 BofA H2 톱픽(SNOW·MDB) 여진(배경). 윈도(7/6~10) 내 강한 신규 단독 catalyst 미확인 → **7일 내 catalyst 미확인**. Confluent-IBM 인수 계류 지속.

**주요 회사 (한국)**
- 직접 상장 노출 부재.

**금주 주요 이슈·이벤트**
- (중립) 데이터 인프라는 매크로 셀오프에 동조, 개별 단독 catalyst 부재.
- **7일 내 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: SW 실적 시즌에서 데이터 소비량·AI 워크로드 지표 확인.

**관련 ETF**
- 글로벌: AIQ·WTAI (포함).
- 한국: 직접 노출 부재.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 7일 내 강한 단독 catalyst 부재.

---

## 관련 출처

**직전 7일 (1순위)**
- [Forbes — Semiconductor selloff deepens, Intel -21%, 2026-07-08](https://www.forbes.com/sites/petercohan/2026/07/08/intel-stock-down-21-inside-the-july-2026-semiconductor-selloff/)
- [CNBC — Stock market news July 7, 2026 (chip selloff)](https://www.cnbc.com/2026/07/06/stock-market-today-live-updates.html)
- [Motley Fool — Samsung & DeepSeek news for NVDA/MU/INTC/AMD, 2026-07-09](https://www.fool.com/investing/2026/07/09/samsung-and-deepseek-deliver-massive-news-for-nvid/)
- [Mezha/Reuters — DeepSeek own AI chip, Nasdaq lower, 2026-07-07](https://mezha.net/eng/bukvy/8450321d_nasdaq_set_to/)
- [Yahoo Finance — Samsung's blowout quarter spooks chip trade, 2026-07-09](https://finance.yahoo.com/markets/stocks/articles/samsung-blowout-quarter-still-spooks-152704421.html)
- [science-technology.news — Samsung HBM4 solves NVIDIA memory bottleneck, 2026-07-09](https://science-technology.news-articles.net/content/2026/07/09/samsung-s-hbm4-breakthrough-solves-nvidia-s-memory-bottleneck.html)
- [TradingKey — Samsung/SK Hynix rally 4%+, chip surge, 2026-07-06](https://www.tradingkey.com/analysis/stocks/more/262011345-kospi-nekki-kioxia-samsung-skhynix-ai-softbank-spacex-tradingkey)
- [Seoul Economic Daily — KOSPI closes 7,475.94 +2.52%, 2026-07-10](https://en.sedaily.com/finance/2026/07/10/kospi-closes-up-18403-points-at-747594)

**배경 (7일 외)**
- [Investing.com — European chip stocks dip after Samsung selloff on results](https://www.investing.com/news/stock-market-news/european-chip-stocks-dip-after-samsung-selloff-on-quarterly-results-4778297)
- [Intellectia — AI Semiconductor Stocks July 2026 (NVDA vs AMD)](https://intellectia.ai/blog/ai-semiconductor-stocks-july-2026)

---

*본 리포트는 산업 분석이며 투자 추천이 아니다. 모든 핵심 주장은 직전 7일(2026-07-06~10) 1차 소스를 1순위로 인용했으며, 7일 외 데이터는 `(배경)` 표시. 레이어 구조는 `valuechain-layers-reference.md` A섹션 정의를 따른다.*
