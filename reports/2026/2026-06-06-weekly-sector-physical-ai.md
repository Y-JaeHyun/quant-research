# [주간 섹터 리포트] Physical AI & 로보틱스 — 2026-06-06

- **데이터 기준일**: 2026-05-30(토) ~ 2026-06-06(토) (직전 7일)
- **공통 레이어 정의**: `docs/research/valuechain-layers-reference.md` 의 "B. Physical AI & 로보틱스 섹터" (L1~L7)
- **작성 규칙**: 7개 레이어(L1~L7) 모두 포함. catalyst 부재 레이어는 "7일 내 catalyst 미확인" 명시.

---

## 섹터 전체 요약

이번 주 Physical AI & 로보틱스 섹터의 단일 최대 이벤트는 **젠슨 황 엔비디아 CEO의 방한(6/5 입국)** 과 그 직전 **GTC Taipei 2026(6/1~6/4)** 에서의 Physical AI 메시지였다. GTC Taipei에서 엔비디아는 Physical AI용 오픈 파운데이션 모델 **Cosmos 3** 를 공개하면서, 이를 활용 중인 로보틱스 개발사로 **삼성전자·LG전자·두산로보틱스를 공식 호명** 했다 [머니투데이, 2026-06-02]. 황 CEO는 6/5 방한해 SK·현대차·LG·네이버 총수들과 만찬을 갖고 "한국을 위한 깜짝 선물"을 언급, K-로봇 밸류체인 전반의 기대감을 끌어올렸다 [한국일보, 2026-06-02; 한국경제·YTN, 2026-05-31].

레이어별로 보면, **L1(컴퓨팅·칩)** 은 Jetson Thor의 정식 양산(GA)과 Unitree H2 채택, Infineon TPM 보안 통합으로 견조했고 [NVIDIA Newsroom; CNBC, 2026-06-01], **L2(센서)** 는 Hesai의 사상 첫 흑자 전환 및 로보틱스 라이다 +425% 성장이라는 구조적 호재 vs. Luminar Chapter 11 파산이라는 명암이 동시에 부각됐다 [Automotive World; TechCrunch, 2026-01-05]. **L4(액추에이터·감속기, 모니터링 1순위)** 는 직전 7일 내 신규 수주·계약 공시는 확인되지 않았으나(보합), 현대차 휴머노이드 국산 감속기 채택 흐름과 에스비비테크 감속기 매출 본격화 스토리가 배경으로 유지됐다. **L6(로봇 OEM·휴머노이드 본체)** 는 황 CEO 방한 효과로 레인보우로보틱스·두산로보틱스 등 K-로봇 대장주에 수급이 집중됐고, **보스턴다이나믹스 IPO 풋옵션 만기(2026년 6월)** 라는 이벤트 드리븐 변수가 차주 핵심 관전 포인트다 [뉴스스페이스; 파이낸셜뉴스, 2026-06-02].

종합적으로 이번 주는 "마케팅 데모"가 아니라 **칩 GA + 라이다 흑자 전환 + 한국 빅테크 공식 파트너 호명**이라는 실질 catalyst가 다수 누적된 주간으로 평가한다.

### 이번주 white list (직전 7일 1순위)

| 순위 | 종목/ETF | 레이어 | 근거(날짜) |
|------|----------|--------|-----------|
| 1 | NVIDIA (NVDA) | L1·L3 | Jetson Thor GA + Cosmos 3 공개 + 황 방한 [NVIDIA, 2026; 머니투데이 2026-06-02] |
| 2 | 두산로보틱스(454910) | L6 | GTC Taipei Cosmos 3 파트너 공식 호명 + 외국인 순매수 상위 [머니투데이 2026-06-02; CBC 2026-05/06] |
| 3 | 레인보우로보틱스(277810) | L6 | 1Q 매출 +116.6%, 삼성향 26.6%, QDD 구동부 내재화 + 황 방한 수혜 [이코노믹리뷰; 머니투데이] |
| 4 | Hesai (HSAI) | L2 | FY2025 첫 흑자(+62.3M USD), 라이다 출하 1.62M대(+222.9%), 로보틱스 +425.8% [Automotive World] |
| 5 | KODEX 로봇액티브(445290) | L6·L4 | K-로봇 테마 자금 집중, 1년 수익률 +117.6%(4월 기준) [머니투데이; samsungfund] |

> 2순위 관찰 후보(신뢰도 낮음): 에스비비테크(388790, L4 — 7일 내 신규 catalyst 미확인), 에스피지(058610, L4), TIMEFOLIO 글로벌휴머노이드(2026-05-19 상장, 데이터 축적 부족).

---

## L1. AI 컴퓨팅·로봇용 칩·엣지

**요약**: 로봇 "두뇌"인 Jetson Thor가 정식 양산(GA) 단계에 진입하고 Unitree·Infineon 등 생태계 채택이 가시화. 이번 주 가장 실질적 catalyst가 누적된 레이어.

**주요 회사 — 글로벌**
- **NVIDIA (NVDA, Jetson·Thor)**: Jetson AGX Thor 개발자 키트·양산 모듈 정식 출시(GA). Blackwell 기반으로 전작 Orin 대비 AI 연산 7.5배·전력효율 3.5배. 개발자 키트 $3,499, T5000 모듈 1,000개 기준 $2,999 [NVIDIA Newsroom]. **6/1 엔비디아가 Unitree H2 휴머노이드 + Jetson Thor를 학계(스탠퍼드·ETH 취리히 등) 대상 첫 로보틱스 시스템으로 판매한다고 발표** [CNBC, 2026-06-01]. Infineon이 OPTIGA TPM(SLB 9672)을 Jetson Thor에 통합, Physical AI용 양자내성 보안 루트 제공 [TradingView/PRNewswire].
- Qualcomm(QCOM), Ambarella(AMBA), Tesla(Dojo), Mobileye(MBLY): 직전 7일 단독 신규 헤드라인 제한적.

**주요 회사 — 한국**
- 삼성전자 LSI(005930), 텔레칩스(054450), 넥스트칩(396270): 7일 내 칩 단독 catalyst 미확인. 단, 삼성전자는 L6/SW 레이어에서 Cosmos 3 파트너로 호명됨(아래 L3·L6 참조).

**금주 이슈(주가영향+차주전망)**
- (긍정) Jetson Thor GA → 휴머노이드·물류 로봇 양산 BOM에 엔비디아 엣지 칩 표준 채택 가능성. 차주 황 방한 후속 한국 파트너십 발표 시 NVDA·국내 팹리스 동반 모멘텀.
- (중립) 한국 로봇 전용 칩 업체(텔레칩스·넥스트칩)는 7일 내 직접 catalyst 부재 → 테마 수급에 연동되는 베타 플레이.

**관련 ETF**
- 글로벌: BOTZ, IRBO, ROBO (Jetson 생태계 비중 반영)
- 한국: TIGER 글로벌AI&로보틱스INDXX(464310)

**차주 레이어 점수: 8 / 10** (Jetson Thor GA + Unitree 채택 + 황 방한 후속 기대. 실질 catalyst 다수)

---

## L2. 비전·라이다·센서·imager

**요약**: 라이다 업계가 "흑자 전환 승자 vs 파산 패자"로 명확히 양극화. Hesai가 구조적 승자로 부상, Mobileye는 휴머노이드 진출 M&A 단행.

**주요 회사 — 글로벌**
- **Hesai (HSAI)**: FY2025 순이익 CN¥435.9M(약 US$62.3M)으로 **라이다 업계 최초 연간 흑자 달성**. 출하량 1.62M대(+222.9% YoY), 매출 CN¥3.03bn(+45.8%). **로보틱스용 라이다 +425.8%(239,273대)** — Unitree·가정용 로봇 파트너십 견인. 신형 ATX 장거리 라이다 누적 수주 400만대 초과, 2026년 4월 양산·납품 개시 [Automotive World; TechCrunch 2026-01-05].
- **Luminar (LAZR)**: Chapter 11 파산보호 신청 상태, 라이다 사업 매각 추진. 업계 컨솔리데이션 가속 [TechCrunch].
- **Mobileye (MBLY)**: Mentee Robotics를 약 $612M에 인수, 휴머노이드·Physical AI 진출 선언("AV + 휴머노이드 종합 리더") [optics.org/247WallSt]. *주: 인수 발표 시점은 7일 이전일 수 있어 (배경) 성격, 다만 섹터 구조 변화로 인과 있음.*
- Sony Semi(SONY, CMOS imager), Velodyne: 7일 내 단독 catalyst 미확인.

**주요 회사 — 한국**
- LG이노텍(011070, 카메라모듈), 픽셀플러스(087600): 7일 내 비전/센서 단독 신규 catalyst 미확인. LG는 황 방한 시 사옥 방문 대상으로 거론(L6/응용 효과).

**금주 이슈(주가영향+차주전망)**
- (긍정) Hesai 흑자 + 로보틱스 라이다 급성장 → 라이다의 "휴머노이드 감각기관" 내러티브 강화. 미국 라이아벌(Luminar) 탈락으로 중국·승자 독식 구도.
- (부정) Luminar 파산 → 라이다 테마 전반 옥석 가리기. 비검증 라이다주 디스카운트.

**관련 ETF**
- 글로벌: BOTZ, ROBO
- 한국: KODEX 로봇액티브(445290), TIGER 글로벌AI&로보틱스(464310)

**차주 레이어 점수: 7 / 10** (Hesai 구조적 호재 강하나, 한국 노출 제한 + 파산 노이즈로 일부 상쇄)

---

## L3. 시뮬레이션·로보틱스 소프트웨어·운영체제

**요약**: GTC Taipei 2026(6/1~6/4)에서 엔비디아가 Physical AI 소프트웨어 스택(Cosmos 3, Isaac, Omniverse)을 전면화하고 한국 빅테크를 파트너로 호명. SW 레이어의 한국 노출이 처음으로 구체화된 주간.

**주요 회사 — 글로벌**
- **NVIDIA (Isaac·Omniverse·Cosmos)**: GTC Taipei 2026(6/1~6/4, 황 6/1 키노트)에서 **Physical AI 오픈 파운데이션 모델 Cosmos 3 공개**. Isaac GR00T·시뮬레이션 라이브러리·Physical AI Data Factory Blueprint(FieldAI·Hexagon·Skild AI·Uber·Teradyne 등 채택) 발표 [NVIDIA Newsroom; 머니투데이 2026-06-02]. SK하이닉스가 Omniverse 기반 반도체 팹 디지털트윈 적용(6/5) [NVIDIA Blog].
- Cognex(CGNX), Symbotic(SYM): 7일 내 엔비디아 협력 단독 발표 미확인.

**주요 회사 — 한국**
- **삼성전자(005930)·LG전자·두산로보틱스(454910)**: GTC Taipei에서 **Cosmos 3 활용 로보틱스 개발사로 공식 호명** [머니투데이 2026-06-02; 시사저널]. SW/모델 레이어에서 한국 기업이 엔비디아 파트너 명단에 직접 오른 첫 사례 → L6 OEM과 직결.

**금주 이슈(주가영향+차주전망)**
- (긍정) Cosmos 3 한국 파트너 호명 → 두산로보틱스·삼성/LG 관련주 동반 강세 트리거. 차주 황 방한 후속 한·엔비디아 공동 발표 시 추가 재료.
- (중립) 한국 직접 상장 SW 플레이는 여전히 부재 → NVDA·OEM 우회 노출이 현실적.

**관련 ETF**
- 글로벌: BOTZ, ROBO
- 한국: 직접 노출 부재 (TIGER 글로벌AI&로보틱스 464310 간접)

**차주 레이어 점수: 8 / 10** (GTC Taipei + 한국 파트너 호명 + 황 방한 = 7일 내 강한 SW 재료)

---

## L4. 액추에이터·감속기·모터·구동계 (catalyst 모니터링 1순위)

**요약**: 휴머노이드 관절의 핵심 부품. **직전 7일 내 신규 수주·공급계약 공시는 확인되지 않음(보합)**. 다만 황 방한 테마 수급과 "현대차 국산 감속기 채택" 배경 모멘텀은 유지.

**주요 회사 — 글로벌**
- **Harmonic Drive (TSE:6324)**: 7일 내 단독 신규 수주 공시 미확인. 2026년 들어 단품 기어→통합 플러그앤플레이 액추에이터로 사업 전환 중(배경) [업계 자료].
- Nidec (TSE:6594), Fanuc (TSE:6954), ABB, Yaskawa: FANUC·YASKAWA는 GTC에서 엔비디아 Physical AI 파트너로 거론(L3 생태계). 액추에이터 단독 7일 catalyst 미확인.

**주요 회사 — 한국**
- **에스비비테크(388790)**: 하모닉 감속기 양산 본격화, 2025년 매출 72억 → 2026년 105억 추정. K9 자주포향 감속기 레퍼런스 확보·방산 4개 프로젝트 진행(배경) [아시아경제 2026-04-16; 뉴스핌]. **7일 내 신규 catalyst 미확인.**
- **에스피지(058610)**: 모터·감속기·드라이브 전문, 로봇 관절 모듈 기술력. 7일 내 단독 공시 미확인, 테마 수급 연동 상승(배경) [CBC뉴스].
- **로보티즈(108490)**: 액추에이터(다이나믹셀). 7일 내 단독 catalyst 미확인.
- **LG이노텍(011070)**: 액추에이터 일부. 7일 내 단독 catalyst 미확인.
- (배경) 현대차가 휴머노이드에 국산 감속기 채택 추진 [디일렉] → L4 한국 업체 중장기 수혜 논리 유지.

**금주 이슈(주가영향+차주전망)**
- (긍정) 황 방한·Cosmos 3 한국 호명으로 로봇 테마 전반 수급 유입 → L4 부품주 동반 상승(펀더멘털보다 베타).
- (부정/리스크) **실제 수주·공급계약은 7일 내 부재** → 테마 과열 후 차익실현 변동성 확대 가능. 차주 황 방한 후속 발표에서 부품 단위 계약이 나오는지가 점수 상향의 키.

**관련 ETF**
- 글로벌: BOTZ, ROBO
- 한국: KODEX 로봇액티브(445290), ACE K휴머노이드TOP2+, RISE 현대차그룹 Fixed Physical AI

**차주 레이어 점수: 6 / 10** (7일 내 catalyst 미확인 보합. 테마 수급은 강하나 실질 계약 부재로 신뢰도 하향)

---

## L5. 배터리·전원·전력관리

**요약**: 휴머노이드 전원. **7일 내 신규 catalyst 미확인(보합)**. 직전 분기 InterBattery 2026(3월)에서의 전고체·로봇 배터리 발표가 배경으로 유지.

**주요 회사 — 글로벌**
- CATL(300750.SZ), BYD(002594.SZ), Tesla(4680): 7일 내 휴머노이드 배터리 단독 catalyst 미확인.

**주요 회사 — 한국**
- **삼성SDI(006400)**: 휴머노이드용 파우치형 전고체("솔리드스택") 샘플 첫 공개, 2027년 하반기 양산 목표(배경, 3월 InterBattery) [EBN; 인더스트리뉴스; ZDNet]. 7일 내 신규 catalyst 미확인.
- **LG에너지솔루션(373220)**: CES 2026 가정용 로봇·드론용 고성능 원통형 배터리 시연(배경) [디일렉]. 7일 내 신규 catalyst 미확인.

**금주 이슈(주가영향+차주전망)**
- (중립) 7일 내 배터리 단독 재료 부재 → 황 방한 로봇 테마의 간접 수혜에 그침. 차주에도 전고체 양산(2027 H2) 일정상 단기 catalyst는 제한적.

**관련 ETF**
- 글로벌: LIT, BATT
- 한국: TIGER 2차전지테마(305540), KODEX 2차전지산업(305720)

**차주 레이어 점수: 5 / 10** (7일 내 catalyst 미확인 보합. 전고체 양산은 2027년 이슈로 시간적 거리 존재)

---

## L6. 로봇 OEM·휴머노이드 본체

**요약**: 이번 주 테마 수급 핵심 레이어. 황 방한·Cosmos 3 한국 호명으로 K-휴머노이드 대장주 강세. 보스턴다이나믹스 IPO 풋옵션 만기(6월)가 이벤트 드리븐 변수.

**주요 회사 — 글로벌**
- **Tesla (TSLA, Optimus)**: V3(양산용) 7~8월 공개·여름 Fremont 양산 개시 예정. **손 액추에이터 25개를 전완(forearm)으로 이전하는 V3 핸드 재설계** 확정(특허 공개) [RobotToday; ilovetesla]. 외부 판매는 2027년. *발표 일부는 7일 이전(배경)이나 여름 양산 임박으로 차주 영향.*
- **Figure AI (비상장)**: Figure 03이 BMW Spartanburg 가동 중, 전작 Figure 02가 10개월간 X3 3만대 생산 기여·판금 9만점 적재(배경, 실제 상업 배치) [GrabaRobot]. 2026~2027 물류·제조 스케일업 타깃.
- **Boston Dynamics (현대차 자회사)**: CES 2026서 "2026년 Atlas 생산분 완판" 언급(배경). **소프트뱅크와의 IPO 약정 2차 시한이 2026년 6월 — 풋옵션 만기 임박, 6월 내 나스닥 상장 여부 결정** [뉴스스페이스; 버핏연구소]. 한국 육군 'Army TIGER' 감시·정찰용 Atlas 공급 요청 거론.
- 1X·Apptronik·Agility(비상장): 7일 내 상업 계약 단독 확인 부족.

**주요 회사 — 한국**
- **레인보우로보틱스(277810)**: 1Q 매출 90.6억(+116.6% YoY, 분기 최대), 삼성향 24.1억(26.6%). QDD 구동부 내재화(고토크 모터 6종·경량 감속기 6종·액추에이터 제어기 4종 설계 완료), 3D 카메라 시제품 자체 제작. SIMTOS 2026서 산업용 양팔로봇 RB-Y2 공개(배경) [이코노믹리뷰; 머니투데이 2026-05-19]. 황 방한 수혜주.
- **두산로보틱스(454910)**: **GTC Taipei Cosmos 3 파트너 공식 호명** [머니투데이 2026-06-02]. 6/1 기준 138,400원, 외국인 코스피 순매수 상위(2,607억) [investing; CBC]. 황 방한 핵심 수혜.
- **유진로봇(056080)**: 7일 내 단독 catalyst 미확인.

**금주 이슈(주가영향+차주전망)**
- (긍정) 황 방한 + Cosmos 3 한국 호명 → 레인보우·두산 동반 강세, 외국인 수급 유입.
- (긍정/이벤트) 보스턴다이나믹스 6월 풋옵션 만기 → 현대차 그룹 리레이팅 가능성. 상장 가시화 시 K-로봇 밸류체인 전반 모멘텀.
- (부정/리스크) 테마 과열 → 차익실현 변동성. Optimus V3는 양산 임박이나 외판 2027년으로 시간차.

**관련 ETF**
- 글로벌: BOTZ, ROBO, Tema Robotics(RBOT)
- 한국: KODEX 로봇액티브(445290), TIMEFOLIO 글로벌휴머노이드(2026-05-19 상장), TIGER 코리아휴머노이드로봇산업, ACE K휴머노이드로봇산업TOP2+

**차주 레이어 점수: 8 / 10** (황 방한 + Cosmos 3 한국 호명 + 보스턴다이나믹스 IPO 이벤트 = 7일 내 다중 catalyst. 단 과열 변동성 유의)

---

## L7. 응용·인프라·자동차/물류/서비스 적용

**요약**: Physical AI의 실제 배치 시장. 현대차-엔비디아 "Atlas 동맹" 강화 내러티브와 Figure-BMW 상업 배치가 핵심. 직접 7일 신규 계약은 제한적이나 황 방한 현대차 사옥 방문이 차주 재료.

**주요 회사 — 글로벌**
- **BMW (BMW.DE)**: Figure 03이 Spartanburg 공장 가동 중(실제 배치, 배경) [GrabaRobot].
- Amazon(AMZN)·Walmart(WMT)·DHL: 7일 내 로봇 배치 단독 신규 catalyst 미확인.
- Mercedes-Benz(MBG.DE): 7일 내 단독 catalyst 미확인.

**주요 회사 — 한국**
- **현대차(005380)**: 보스턴다이나믹스 보유 + 엔비디아 자율주행·로보틱스 협력 확대. **황 방한 시 현대차 사옥 방문·정의선 회장 만찬 거론, "현대차-엔비디아 Atlas 동맹 강화" 기대** [파이낸셜뉴스 2026-06-02; 한국일보]. 미국 공장에 Spot·Stretch·Atlas 도입 계약(배경, 2025-04).
- 현대모비스(012330), 한국타이어(161390), CJ대한통운(000120): **7일 내 로봇 배치 단독 catalyst 미확인.** CJ대한통운-보스턴다이나믹스 직접 연계 뉴스 미확인.

**금주 이슈(주가영향+차주전망)**
- (긍정) 황 방한 현대차 방문 → 현대차/모비스 로보틱스 리레이팅 기대. Atlas 양산 완판·Army TIGER 공급 요청이 응용 수요 뒷받침.
- (중립) 물류(CJ대한통운 등) 단독 catalyst 7일 내 부재 → 테마 후순위.

**관련 ETF**
- 글로벌: First Trust Industrials/Producer Durables(FXR)
- 한국: TIGER 코리아휴머노이드로봇산업, RISE 현대차그룹 Fixed Physical AI

**차주 레이어 점수: 7 / 10** (황 방한 현대차 방문 + Figure-BMW 배치 지속. 단 7일 내 신규 응용 계약은 제한적)

---

## 관련 출처

### 직전 7일 (2026-05-30 ~ 2026-06-06, 1순위)
- [CNBC, 2026-06-01] Nvidia picks Unitree for humanoid robot platform — https://www.cnbc.com/2026/06/01/nvidia-unitree-humanoid-robotics-system-researchers.html
- [머니투데이, 2026-06-02] 'AI 메모리' 다음은 '로봇'..젠슨 황, 삼성·LG·두산 손잡았다 — https://www.mt.co.kr/industry/2026/06/02/2026060214522014085
- [한국일보, 2026-06-02] '한국 로봇' 콕 집은 젠슨 황…관련주 뛰고 동선 지도까지 — https://www.hankookilbo.com/news/article/A2026060214180000564
- [파이낸셜뉴스, 2026-06-02] K로봇 주목한 젠슨 황…현대차-엔비디아 '아틀라스 동맹' 강화하나 — https://www.fnnews.com/news/202606021125597728
- [시사저널, 2026-06-02] HBM·로봇 다 품는다…젠슨 황, 韓 총수들과 릴레이 '삼소 회동' — https://www.sisajournal.com/news/articleView.html?idxno=375451
- [YTN, 2026-05-31] 젠슨 황, 이번 주 방한...'제2의 깐부회동' 기대감 — https://www.ytn.co.kr/_ln/0102_202605311519148427
- [NVIDIA Newsroom] NVIDIA and Global Robotics Leaders Take Physical AI to the Real World / Omniverse·Cosmos 발표 (GTC Taipei 6/1~6/4) — https://nvidianews.nvidia.com/news/nvidia-and-global-robotics-leaders-take-physical-ai-to-the-real-world
- [NVIDIA Newsroom] Jetson Thor Now Available (GA) — https://nvidianews.nvidia.com/news/nvidia-blackwell-powered-jetson-thor-now-available-accelerating-the-age-of-general-robotics
- [NVIDIA Blog] Into the Omniverse: GTC Showcases Virtual Worlds Powering Physical AI (SK하이닉스 디지털트윈 6/5) — https://blogs.nvidia.com/blog/gtc-2026-virtual-worlds-physical-ai/
- [TradingView/PRNewswire] Infineon TPM for NVIDIA Jetson Thor — https://www.tradingview.com/news/prnewswire:8efe76e0571fc:0-infineon-advances-physical-ai-security/
- [Automotive World] Hesai posts first-ever profit as LiDAR shipments pass 1.6m units — https://www.automotiveworld.com/news/hesai-posts-first-ever-profit-as-lidar-shipments-pass-1-6m-units/

### 배경 (7일 외, 인과관계 명시)
- [TechCrunch, 2026-01-05] China's Hesai will double production / Luminar Chapter 11 — *(배경)* 라이다 컨솔리데이션 구도 → 이번 주 Hesai 흑자 전환 해석의 토대 — https://techcrunch.com/2026/01/05/chinas-hesai-will-double-production-as-lidar-sensor-industry-shakes-out/
- [optics.org / 247WallSt, 2026-03] Mobileye–Mentee Robotics $612M 인수 — *(배경)* L2 휴머노이드 진출 구조 변화, 차주 영향 — https://247wallst.com/investing/2026/03/14/mobileye-vs-luminar-two-autonomous-driving-visions-one-brutal-reality/
- [뉴스스페이스] 현대차·소프트뱅크 보스턴다이나믹스 나스닥 상장 6월 결정 — *(배경→7일 영향)* 풋옵션 만기 2026년 6월, 차주 핵심 이벤트 — https://www.newsspace.kr/news/article.html?no=13851
- [이코노믹리뷰] 레인보우로보틱스 1Q 매출 +117%, 삼성향 27% — *(배경)* 펀더멘털 근거, 황 방한 수혜 해석 토대 — https://www.econovill.com/news/articleView.html?idxno=740422
- [머니투데이, 2026-05-19] 레인보우로보틱스 삼성 핵심 파트너, 목표가 91.5만 — https://www.mt.co.kr/stock/2026/05/19/2026051908420757832
- [아시아경제, 2026-04-16 / 뉴스핌] 에스비비테크 감속기 성장 본격화 — *(배경)* L4 한국 부품 스토리 — https://core.asiae.co.kr/article/2026041609412114801
- [디일렉] 현대차, 휴머노이드에 국산 감속기 채택 — *(배경)* L4·L7 한국 수혜 논리 — https://www.thelec.kr/news/articleView.html?idxno=52966
- [EBN / 인더스트리뉴스 / ZDNet, 2026-03] 삼성SDI 전고체 '솔리드스택' 로봇 배터리 (InterBattery 2026) — *(배경)* L5, 2027 H2 양산 — https://www.ebn.co.kr/news/articleView.html?idxno=1702251
- [RobotToday / ilovetesla] Tesla Optimus V3 핸드 재설계(액추에이터 전완 이전), 여름 Fremont 양산 — *(배경→차주 영향)* — https://robottoday.com/article/tesla-s-optimus-hand-undergoes-redesign-gen-3-robot-may-adopt-gearbox-lead-screw-and-tendon-drive
- [GrabaRobot] Figure 03 BMW Spartanburg 배치, Figure 02 X3 3만대 생산 기여 — *(배경)* L6·L7 실제 상업 배치 — https://www.grabarobot.com/blog/humanoid-robot-workforce-deployment-2026/
- [삼성fund/k-etf] KODEX 로봇액티브(445290) 1년 +117.6%(4월 기준) — https://www.samsungfund.com/etf/product/view.do?id=2ETFH5
