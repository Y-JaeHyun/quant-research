# [주간 섹터 리포트] Physical AI & 로보틱스 — 2026-07-11

**데이터 기준일**: 2026-07-06 ~ 2026-07-10 (직전 7일 영업일 1순위, [JAE-88](/JAE/issues/JAE-88) 규칙 7~9 적용)
**레이어 구조**: 공통 문서 `valuechain-layers-reference.md` B섹션(7개 레이어) 전 레이어 포함
**관점**: 산업 분석 (투자 추천 아님)

---

## 0. 섹터 전체 요약 및 금주 White List

이번 주 Physical AI 섹터 최대 catalyst는 **중국 Unitree Robotics의 STAR마켓 IPO 등록 승인(7/2, 배경 인접)과 이로 촉발된 A주 로봇 테마 랠리**, 그리고 **Tesla Optimus Gen3 양산 램프 로드맵 구체화**였다. 휴머노이드 상업화 내러티브가 "자랑(showing off)에서 매출(getting paid)"로 전환하는 국면을 확인시켰다.

- **Unitree IPO 승인 → A주 로봇 테마 폭발**: 7/2 중국 증감회(CSRC)가 Unitree IPO 등록 승인(약 $619M 조달, STAR마켓). 7/3 **A주 로봇 컨셉주 30개+ 상한가**. Unitree 순이익률 35.13%로 섹터 밸류에이션 벤치마크 제시([BigGo Finance, 2026-07](https://finance.biggo.com/news/78bee93b-d0a2-4ffe-8c61-918a97f63938); [Caixin, 2026-07-03](https://www.caixinglobal.com/2026-07-03/unitree-robotics-wins-approval-for-618-million-star-market-ipo-102460136.html)). 이르면 7월 말 상장 가능. 한국 로봇주(레인보우·두산로보틱스)에도 테마 스필오버.
- **Tesla Optimus Gen3 양산 로드맵**: Fremont 구 Model S/X 라인을 Optimus Gen3 자동화 라인으로 전환(연산 100만 대 설계). 생산 계획 — 6월 주당 수십 대 → 7월 100~150대 → 8월 ~300대 → 9월 1,000대/주. 단, **2026년 생산분은 사내 공장 테스트·데이터 수집용(외부 상용 아님)**([blog.robozaps / BigGo, 2026-07](https://blog.robozaps.com/b/tesla-model-s-optimus-robot-factory-conversion)).
- **Figure·Boston Dynamics 배치 진전**: Figure 03가 시간당 1대 마일스톤 이후 유료 배치 확대(BMW Spartanburg 시퀀싱). Boston Dynamics 전기 Atlas는 현대차·Google DeepMind 파일럿 진행([humanoid.press / Meta-Intelligence, 2026-07](https://www.meta-intelligence.tech/en/insight-physical-ai)).
- **신규 진입**: 전(前) Tesla Optimus 과학자가 파리 기반 스타트업 UMA 설립, 경량 휴머노이드 "Northstar" 유럽 우선 출시 계획(50개 잠재 고객 논의)([Bloomberg, 2026-07-07](https://www.bloomberg.com/news/articles/2026-07-07/ex-tesla-scientist-unveils-plans-for-european-humanoid-robot)).

L1(로봇 칩)·L6(로봇 OEM)·L7(응용)이 이번 주 강세 진앙. L4(액추에이터)·L5(배터리)는 catalyst 상대 부재.

### White List — 1순위 (직전 7일 명확한 catalyst)

| 종목/대상 | 레이어 | 근거 (직전 7일) | 출처 |
|----------|--------|------------------|------|
| **Unitree Robotics(비상장→STAR 상장 예정)** | L6 | 7/2 IPO 등록 승인($619M), 7/3 A주 로봇 30종+ 상한가 촉발 | Caixin/BigGo, 2026-07-02~03 |
| **Tesla(TSLA)** | L6 | Optimus Gen3 Fremont 라인 전환·월별 양산 램프(7월 100~150대/주) 로드맵 구체화 | blog.robozaps/BigGo, 2026-07 |

### White List — 2순위 관찰 후보 (신뢰도 낮음 / 7일 외 / 양방향)

| 종목/대상 | 레이어 | 사유 |
|----------|--------|------|
| 레인보우로보틱스(277810) | L6 | Unitree 테마 스필오버 기대(양)이나 개별 7일 확정 catalyst 미확인 + 삼성 자회사 프리미엄 |
| 두산로보틱스(454910) | L6 | PalletizHD+ 발표(Automate 2026, 6/22~25 배경), 7일 내 신규 catalyst 미확인 |
| Figure AI(비상장) | L6 | Figure 03 유료 배치 확대(BMW), 비상장 접근성 제약 |
| 레인보우/한화 계열 비전(L2) | L2 | 개별 7일 catalyst 미확인 |

---

## L1. AI 컴퓨팅·로봇용 칩·엣지

> **요약**: NVIDIA Jetson·Thor가 휴머노이드 두뇌 표준 지위 유지. 이번 주 AI 반도체 셀오프(NVIDIA -2.5%, 7/7 DeepSeek 자체칩)에 동조 변동했으나, 로봇 엣지 수요 구조는 견조.

**주요 회사 (글로벌)**
- **NVIDIA(NVDA, Jetson·Thor)**: 7/7 DeepSeek 자체칩 보도로 -2.5%(음, AI 섹터 L1 참조). 단 로봇 엣지 컴퓨팅 표준 지위는 유지, Unitree·Figure 등 휴머노이드 두뇌 채택 지속.
- **Qualcomm(QCOM)·Ambarella(AMBA)·Tesla(Dojo)·Mobileye(MBLY)**: 윈도 내 개별 단독 catalyst 미확인, 반도체 매크로 동조.

**주요 회사 (한국)**
- **삼성전자 LSI(005930)·텔레칩스(054450)·넥스트칩(396270)**: 7일 내 단독 catalyst 미확인. 삼성은 메모리 어닝 서프라이즈(AI L1)로 그룹 센티먼트 우호.

**금주 주요 이슈·이벤트**
- (양방향) DeepSeek 자체칩(7/7)은 NVIDIA 데이터센터 GPU엔 음(-)이나, 로봇 엣지(Jetson/Thor) 수요와는 직접 관련 낮음.
- (+) Unitree IPO·휴머노이드 양산 램프로 로봇 칩 중장기 수요 확대 시그널.
- 차주 영향: NVIDIA Robotics(Isaac·Thor) 관련 후속, 휴머노이드 양산 램프와 칩 채택.

**관련 ETF**
- 글로벌: BOTZ·IRBO·ROBO — 휴머노이드 테마 우호.
- 한국: TIGER 글로벌AI&로보틱스INDXX(464310).

**차주 투자 관점 레이어 점수: 6/10** — 로봇 엣지 수요 구조 견조하나 반도체 매크로 변동 노출.

---

## L2. 비전·라이다·센서·imager

> **요약**: 로봇·자율주행 겸용 센서 계층. 이번 주 개별 단독 catalyst 제한적. LG이노텍 카메라모듈 휴머노이드 공급망 내러티브 지속(지난주 부각).

**주요 회사 (글로벌)**
- **Sony Semi(SONY, CMOS)·Mobileye(MBLY)·Luminar(LAZR)·Hesai(HSAI)**: 윈도 내 개별 단독 catalyst 미확인. Hesai 등 중국 라이다는 Unitree 테마 간접 수혜 관찰.

**주요 회사 (한국)**
- **LG이노텍(011070)**: 지난주 휴머노이드 카메라모듈 공급망 부각(7/3) 여진. 윈도 내 신규 확정 단독 catalyst 미확인.
- **픽셀플러스(087600)·삼성전기(009150)**: 7일 내 단독 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (중립) 센서 계층은 개별 catalyst 부재, 휴머노이드 양산 램프 수혜는 배경.
- **7일 내 강한 단독 catalyst 제한적** — 점수 신뢰도 다소 낮음.
- 차주 영향: 휴머노이드 비전·라이다 채택 스펙 공개, LG이노텍 공급 계약 진전.

**관련 ETF**
- 글로벌: BOTZ·ROBO.
- 한국: KODEX 로봇액티브(445290), TIGER 글로벌AI&로보틱스(464310).

**차주 투자 관점 레이어 점수: 5/10 (신뢰도 낮음)** — 개별 단독 catalyst 부재.

---

## L3. 시뮬레이션·로보틱스 소프트웨어·운영체제

> **요약**: NVIDIA Isaac·Omniverse 표준 지위, Boston Dynamics·Google DeepMind Atlas 파일럿 진전이 SW·시뮬레이션 수요 견인. 상장 노출은 제한적.

**주요 회사 (글로벌)**
- **NVIDIA(Isaac·Omniverse)**: 휴머노이드 시뮬레이션·SDK 표준. Boston Dynamics Atlas·Google DeepMind 협업이 시뮬레이션 SW 수요 견인(배경 진전).
- **Cognex(CGNX)·Symbotic(SYM)**: 윈도 내 개별 단독 catalyst 미확인. Symbotic은 지난주 ARMS 인수(7/2) 여진.

**주요 회사 (한국)**
- 직접 상장 미미.

**금주 주요 이슈·이벤트**
- (+) Atlas 현대차·DeepMind 파일럿 진전으로 로봇 SW·시뮬레이션 수요 우호(배경).
- **7일 내 상장주 직접 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: NVIDIA Isaac 생태계 확장, 휴머노이드 학습 SW 채택.

**관련 ETF**
- 글로벌: BOTZ·ROBO.
- 한국: 직접 노출 부재.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 상장주 직접 catalyst 부재.

---

## L4. 액추에이터·감속기·모터·구동계

> **요약**: 휴머노이드 관절 핵심 부품(1순위 모니터링). 이번 주 개별 확정 단독 catalyst는 제한적이나, Unitree IPO·Tesla Optimus 양산 램프가 중장기 감속기·액추에이터 수요 기대를 견인.

**주요 회사 (글로벌)**
- **Harmonic Drive(TSE:6324)·Nidec(TSE:6594)·Fanuc(TSE:6954)**: 윈도 내 개별 단독 catalyst 미확인. Optimus·Unitree 양산 램프로 감속기 수요 기대(배경).

**주요 회사 (한국)**
- **에스피지(058610)·에스비비테크(388790)·로보티즈(108490)**: 7일 내 단독 확정 catalyst 미확인. Unitree 테마·Optimus 양산 램프의 부품 스필오버 기대는 존재하나 개별 검증 부족 → **신뢰도 낮음**.

**금주 주요 이슈·이벤트**
- (양방향) Optimus 9월 1,000대/주 램프는 감속기 수요 기대(양)이나 2026 생산분은 사내용(외부 매출 지연, 음).
- **7일 내 단독 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: Optimus 양산 램프 진척·부품 공급망(감속기) 발주 보도.

**관련 ETF**
- 글로벌: BOTZ·ROBO.
- 한국: KODEX 로봇액티브(445290), ACE K휴머노이드TOP2+.

**차주 투자 관점 레이어 점수: 5/10 (보합, 신뢰도 낮음)** — 7일 내 catalyst 미확인, 양산 기대는 배경.

---

## L5. 배터리·전원·전력관리

> **요약**: 휴머노이드·모바일 로봇 전원. 이번 주 로봇 전용 catalyst 부재. 2차전지 대형주는 에너지 섹터 ESS 이슈와 연동(에너지 L3 참조).

**주요 회사 (글로벌)**
- **CATL(300750.SZ)·BYD(002594.SZ)·Tesla(4680)**: 로봇 전용 단독 catalyst 윈도 내 미확인.

**주요 회사 (한국)**
- **LG에너지솔루션(373220)·삼성SDI(006400)**: 로봇 전용 7일 catalyst 미확인 (ESS·EV 배터리 이슈는 에너지 섹터 참조).

**금주 주요 이슈·이벤트**
- (중립) 로봇 전원 계층 7일 내 단독 catalyst 부재.
- **7일 내 catalyst 미확인** — 점수 신뢰도 낮음.
- 차주 영향: 휴머노이드 양산 시 전원·배터리 스펙 공개.

**관련 ETF**
- 글로벌: LIT·BATT.
- 한국: TIGER 2차전지테마(305540), KODEX 2차전지산업(305720).

**차주 투자 관점 레이어 점수: 4/10 (보합, 신뢰도 낮음)** — 로봇 전용 catalyst 지속 공백.

---

## L6. 로봇 OEM·휴머노이드 본체

> **요약**: **이번 주 섹터 최강 레이어**. Unitree IPO 승인(7/2)·A주 로봇 30종+ 상한가(7/3), Tesla Optimus Gen3 양산 램프, Figure 03 유료 배치, UMA 신규 진입까지 휴머노이드 본체 내러티브 총집합.

**주요 회사 (글로벌)**
- **Unitree(비상장→STAR 상장 예정)**: 7/2 CSRC IPO 등록 승인($619M), 104일 최단 심사 기록. 순이익률 35.13% — 섹터 밸류 벤치마크. 7/3 A주 로봇 컨셉주 30개+ 상한가 촉발. 이르면 7월 말 상장 [Caixin/BigGo, 2026-07-02~03].
- **Tesla(TSLA, Optimus)**: Gen3 Fremont 라인 전환(연 100만 대 설계). 7월 100~150대/주 → 9월 1,000대/주 램프. 단 2026 생산분 사내 테스트용 [blog.robozaps/BigGo, 2026-07].
- **Figure AI(비상장)**: Figure 03 시간당 1대 이후 유료 배치 확대(BMW Spartanburg) [Meta-Intelligence, 2026-07].
- **UMA(비상장, 신규)**: 전 Tesla 과학자 창업, 경량 휴머노이드 Northstar 유럽 우선, 50개 고객 논의 [Bloomberg, 2026-07-07].

**주요 회사 (한국)**
- **레인보우로보틱스(277810)·두산로보틱스(454910)**: Unitree 테마 스필오버 기대. 삼성(레인보우)·두산의 휴머노이드 상용화 선언 경쟁 지속. 두산 PalletizHD+(Automate 2026, 6/22~25 배경). 윈도 내 개별 확정 단독 catalyst 미확인 → **신뢰도 낮음** [BigGo/v.daum, 2026-07].
- **유진로봇(056080)**: 7일 내 단독 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (+) Unitree IPO 승인이 글로벌 휴머노이드 밸류에이션·테마 재점화, "자랑→매출" 전환 시그널.
- (+) Optimus 양산 램프 로드맵·Figure 유료 배치로 상업화 진척.
- (음) Optimus 2026 생산분 사내용 — 외부 상용 매출 지연.
- 차주 영향: Unitree 실제 상장(7월 말)·공모가, A주 로봇 테마 지속성, Optimus 8월 ~300대/주 램프 확인.

**관련 ETF**
- 글로벌: BOTZ·ROBO·RBOT — 휴머노이드 테마 강세.
- 한국: KODEX 로봇액티브(445290), TIMEFOLIO 글로벌휴머노이드.

**차주 투자 관점 레이어 점수: 8/10** — Unitree IPO·Optimus 램프·Figure 배치 삼중 catalyst. 섹터 최강. 직전 주 대비 상향.

---

## L7. 응용·인프라·자동차/물류/서비스 적용

> **요약**: Physical AI 실배치 1차 시장. BMW Spartanburg의 Figure 03 시퀀싱 배치, 현대차 Atlas 파일럿이 응용 계층 진전. 지난주 Symbotic ARMS 인수 여진.

**주요 회사 (글로벌)**
- **BMW(BMW.DE)**: Figure 03 Spartanburg 시퀀싱 유료 배치 — 자동차 제조 현장 휴머노이드 실배치 [Meta-Intelligence, 2026-07].
- **Amazon(AMZN, 물류)·Walmart(WMT)**: 윈도 내 개별 단독 catalyst 미확인, 물류 자동화 배경 지속.

**주요 회사 (한국)**
- **현대차(005380)**: Boston Dynamics 전기 Atlas 현대차·Google DeepMind 파일럿 진전 — 산업 현장 실증 [Meta-Intelligence, 2026-07].
- **현대모비스(012330)·CJ대한통운(000120)**: 7일 내 단독 catalyst 미확인.

**금주 주요 이슈·이벤트**
- (+) BMW·현대차 휴머노이드 실배치 진전으로 응용 계층 매출 가시성 개선.
- 차주 영향: 자동차·물류 현장 휴머노이드 배치 규모·ROI 데이터 공개.

**관련 ETF**
- 글로벌: FXR.
- 한국: TIGER K휴머노이드, RISE 현대차그룹 Fixed Physical AI.

**차주 투자 관점 레이어 점수: 6/10** — BMW·현대차 실배치로 응용 가시성 개선.

---

## 관련 출처

**직전 7일 (1순위)**
- [Caixin — Unitree wins approval for $618M STAR Market IPO, 2026-07-03](https://www.caixinglobal.com/2026-07-03/unitree-robotics-wins-approval-for-618-million-star-market-ipo-102460136.html)
- [BigGo Finance — Unitree IPO approval, A-share 30+ robot stocks limit-up, 2026-07](https://finance.biggo.com/news/78bee93b-d0a2-4ffe-8c61-918a97f63938)
- [Bloomberg — Ex-Tesla scientist unveils European humanoid (UMA Northstar), 2026-07-07](https://www.bloomberg.com/news/articles/2026-07-07/ex-tesla-scientist-unveils-plans-for-european-humanoid-robot)
- [BigGo Finance — Humanoids on eve of mass production; Unitree IPO ignites A-share, 2026-07](https://finance.biggo.com/news/3bf8df38-4754-4491-bed4-5e018280441f)

**배경 (7일 외)**
- [Meta-Intelligence — Humanoid Robots 2026: Optimus, Figure 03, NVIDIA Isaac status](https://www.meta-intelligence.tech/en/insight-physical-ai)
- [blog.robozaps — Tesla Model S line converted to Optimus factory](https://blog.robozaps.com/b/tesla-model-s-optimus-robot-factory-conversion)
- [v.daum — Samsung's bet: Rainbow Robotics, K-Humanoid Wars](https://v.daum.net/v/20260223100942003)

---

*본 리포트는 산업 분석이며 투자 추천이 아니다. 모든 핵심 주장은 직전 7일(2026-07-06~10) 1차 소스를 1순위로 인용했으며, 7일 외 데이터는 `(배경)` 표시. 레이어 구조는 `valuechain-layers-reference.md` B섹션 정의를 따른다.*
