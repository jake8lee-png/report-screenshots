# [UBS] Memory Semis Monthly — Further pricing upside amidst LTA negotiations (2026-07-03) | 작성자 : 잠실개미

**보고서 개요**: UBS Global Research가 2026년 7월 3일 발간한 Memory Semis Monthly의 7월호로, 총 15명의 애널리스트(Nicolas Gaudois, Timothy Arcuri, Kenji Yasui, Jimmy Yoon, Gianmarco Vella, Atsuhiro Kinoshita, Sunny Lin, Jimmy Yu, Randy Abrams, Francois-Xavier Bouvignies 등)가 공동 작성한 글로벌 반도체 산업 리포트다. 총 28페이지 분량으로 DRAM·NAND 가격 사이클, HBM 수요, LTA(Long-Term Agreement) 협상 진전, 하이퍼스케일러 조달 동향, 서버·스마트폰·SSD 등 애플리케이션별 수급을 종합 다룬다.

![메인 프라이싱 요약](https://raw.githubusercontent.com/jake8lee-png/report-screenshots/main/UBS_Memory_Semis_Monthly_260703/01_main_pricing_summary.png)

## 1. 핵심 주장 — 2H26 메모리 가격 추가 상승 여지

UBS는 이번 7월호에서 **자사의 2H26 메모리 가격 전망을 재차 상향 조정**하며, 산업 체크 결과 DDR 컨트랙트 가격의 QoQ 상승 폭이 종전 추정치를 크게 뛰어넘고 있다고 진단했다. 구체적으로 base-line DDR 컨트랙트 가격을 **3Q26 +32% QoQ(종전 +17%), 4Q26 +18% QoQ(종전 +12%)로 상향**했는데, 이는 2Q26에 이미 +67% QoQ의 급등을 시현한 이후에도 상승 궤적이 이어진다는 뜻으로 사실상 지난 30년 반도체 사이클 중 유례가 없는 상승 국면임을 강조했다. NAND 플래시 역시 3Q26 +30% QoQ(종전 +17%), 4Q26 +12% QoQ(unchanged)로 조정되었고, 2Q26 +67% QoQ 이후 최소 4Q27까지 upcycle이 지속될 것으로 전망된다. **DRAM 산업은 최소 2Q28까지 undersupplied 상태**가 이어지며, LTA·HBM 프라이싱·믹스에 따라 벤더별 ASP QoQ 비교치는 편차가 있으나 전반적 상승 방향성은 확고하다. 종합적으로 UBS는 메모리 산업 매출이 **2026년 US$992bn, 2027년 US$1,763bn**에 도달할 것으로 예상하며, 이번 unprecedented upcycle의 유일한 리스크 요인은 하이퍼스케일러의 affordability(비용 감내 능력) — 즉 자본시장 지속 조달을 통한 capex 유지 여부 — 로 규정했다.

## 2. DDR contract pricing 궤적 — 2Q26 +67% → 3Q26 +32% → 4Q26 +18%

DDR 컨트랙트 가격의 재상향은 이번 리포트의 가장 핵심적인 변화다. UBS는 2Q26에 DDR ASP가 QoQ +80.3%, YoY +293.1% 상승했음을 인정한 뒤, 3Q26에는 종전 전망치 +17% QoQ에서 **+32% QoQ로 대폭 상향**했으며 4Q26에도 +12%에서 +18% QoQ로 조정했다. UBS의 DRAM S/D 요약(Figure 33)에 따르면 blended DRAM ASP(HBM 포함)는 2026E $2.25/Gb에서 2027E $2.69/Gb로 상승하고, DDR-only ASP는 2026E $2.30/Gb에서 2027E $2.67/Gb로 각각 상승한다. 이러한 상승은 지난 사이클 대비 훨씬 더 가파른 궤적을 그리며, UBS 자체 사이클 분석(Figure 15)에서도 현재 국면의 QoQ 누적 상승률이 **+766%**로 표시되어 있어 과거 어떤 사이클과도 비교되지 않는 폭발적 국면임을 보여준다. Sufficiency ratio 기준으로도 **2027E -13.6% (2026E -8.1%)로 부족분이 오히려 심화**되는 방향이며, 이는 2027년 bit 수요 증가율 +36.2% YoY 대비 공급 증가율이 +19.3%에 그치는 격차가 너무 커서 인벤토리 리빌드 없이도 갭이 좁혀지지 않는다는 산업 구조의 직접적 결과다.

![DRAM 수급 요약](https://raw.githubusercontent.com/jake8lee-png/report-screenshots/main/UBS_Memory_Semis_Monthly_260703/02_dram_supply_demand.png)

## 3. NAND flash pricing — 2Q26 +67% → 3Q26 +30% → 4Q26 +12%

NAND 플래시 사이클은 DDR과 시차를 두면서도 유사한 상승 패턴을 그린다. UBS의 NAND S/D 요약(Figure 41)에 따르면 NAND ASP는 2Q26 QoQ +67.0%, YoY +294.5%로 급등한 뒤 3Q26에는 종전 +17%에서 **+30% QoQ로 상향**, 4Q26에는 +12% QoQ가 유지된다. UBS는 이번 NAND upcycle이 **최소 4Q27까지 지속**될 것으로 전망하며, 이는 서버 SSD 수요 폭증(2026E 31% → 2027E 37% 비중, Figure 19-20)이 견인하는 구조적 요인에 근거한다. Sufficiency ratio 역시 2026E -9.3%, 2027E -1.0%로 부족분이 지속되고, wafer out은 2026E 1,349k → 2027E 1,355k로 사실상 정체돼 공급 확장이 극히 제한적이다. NAND 벤더별 bit shipment 성장률(Figure 43)을 보면 SK Hynix가 2Q26에 +11.8% QoQ, 4Q26 +15% QoQ로 가장 공격적이며, 삼성은 2Q26 +7.5%, Micron은 +5% 수준으로 상대적으로 완만하다. UBS는 이러한 사이클 지속성을 반영해 NAND ASP 예측치를 2026E $0.26/GB에서 2027E $0.37/GB로 상향하며, 이는 **YoY +42.7%의 강한 프라이싱 파워**를 의미한다.

![NAND 수급 요약](https://raw.githubusercontent.com/jake8lee-png/report-screenshots/main/UBS_Memory_Semis_Monthly_260703/03_nand_supply_demand.png)

## 4. DRAM 수급 — 2028년까지 undersupplied

이번 리포트의 가장 구조적인 통찰은 **DRAM 산업이 2Q28까지 undersupplied 상태를 유지**한다는 진단이다. UBS는 2027년 bit 수요 성장률이 +36.2% YoY, 공급 성장률이 +19.3% YoY로 갭이 **17%p** 벌어져 있어, 인벤토리 조정을 하지 않는다는 가정(즉 하이퍼스케일러의 2H26 인벤토리 리빌드가 없다고 가정)만으로도 sufficiency ratio가 -13.6%까지 악화된다고 계산했다. 참고로 -8.1%(2026E) → -13.6%(2027E) 궤적은 지난 30년 사이클 중 unprecedented level이라고 UBS는 명시했다. DRAM 산업 wafer capacity(Figure 9)를 보면 2027YE 기준 총 2,245k wpm 중 DDR용은 1,555k(사실상 정체), HBM용은 690k로 30% 증가하는 반면, 서버·모바일·PC 등 conventional 수요가 여전히 강한 증가세를 보인다. 삼성·SK하이닉스·마이크론의 wafer 배분(Figure 10)에서도 세 벤더 모두 HBM 비중을 확대하는 방향이며, 이는 DDR 공급 여력을 더욱 압박한다. CXMT의 캡파 확장(2026E 265k wpm, 2027E 305k wpm, 산업 대비 13-14%)도 언급되지만 산업 전체 부족분을 메우기에는 역부족이라는 것이 UBS의 판단이다. Samsung과 SK Hynix의 DRAM finished wafer/die 재고(Figure 23)는 4Q25 3.0주 수준까지 하락해 정상 레벨(4주 red dashed line)을 하회하며, 이는 즉시 출하 가능한 물량이 극단적으로 부족함을 시사한다.

## 5. LTA negotiations 진전 — Micron SCAs vs 한국사 60-70% 고정

이번 사이클의 특징은 **LTA(장기공급계약) 협상이 실제로 진행되고 있다는 점**이며, UBS는 벤더별 계약 구조의 차이를 비교적 상세히 설명한다. Micron은 SCAs(Strategic Contract Agreements) 형태로 가격에 **"floor"와 "ceiling"**을 두어 상하방을 제한하는 방식을 채택하고 있으며, 이는 사이클 리스크를 양방향으로 관리하려는 접근이다. 반면 한국 메모리 3사(삼성·SK하이닉스)는 **일정 비중(대략 60-70%)의 볼륨을 5년 계약으로 고정 가격에 묶고**, 나머지에 볼륨·가격의 가변 컴포넌트를 추가하는 구조를 취한다. UBS는 삼성이 3Q 중 대형 고객사 몇 곳과의 revised LTA를 완료해가는 과정에 있다고 파악했고, 특히 **DDR5에 초점이 맞춰져 있으며 볼륨의 50-70%가 LTA로 묶여가는 중**이라고 명시했다. SK하이닉스의 경우 DDR5와 NAND 플래시 모두에서 대형 하이퍼스케일러 고객과의 협상이 진행 중이라고 언급된다. 이러한 LTA 확대는 벤더 관점에서 사이클 볼륨 리스크를 헤지하고 CAPEX 회수 가시성을 높이는 동시에, 고객 관점에서는 향후 가격 급등 시 조달 가격을 사전에 확보하는 이중적 이해관계가 반영된 결과다. 다만 UBS는 LTA 구조 차이 때문에 **벤더별 blended ASP QoQ 성장률에는 상당한 편차가 있을 수 있음**을 지적한다.

## 6. 하이퍼스케일러 affordability 리스크

**하이퍼스케일러의 조달 능력이 이번 unprecedented upcycle의 최대 리스크 요인**이라고 UBS는 명시적으로 지목했다. Figure 40의 UBS bottom-up server procurement model에 따르면 Top 8 하이퍼스케일러(Alphabet, AWS, Microsoft, Meta, Baidu, Alibaba, Tencent, ByteDance)의 총 서버 조달량은 2025년 12,858k units에서 2026E 16,153k(+25.6% YoY), 2027E 19,541k(+21.0% YoY)로 지속 확대된다. 특히 Alphabet은 2026E 2,350k → 2027E 2,950k(+25.5% YoY), Meta는 2026E 4,180k(+22.6% YoY) → 2027E 4,990k(+19.4% YoY), Microsoft는 2026E 3,090k(+25.7% YoY) → 2027E 3,740k(+21.0% YoY)로 강한 조달을 유지한다. AI 서버 DRAM 수요(Figure 39)는 2025년 20,952 mn Gb에서 **2026E 44,111mn Gb (+110.5% YoY), 2027E 95,464mn Gb (+130.3% YoY)** 로 폭증하는데, 이러한 조달을 지속 뒷받침하려면 하이퍼스케일러들이 자본시장에서 지속적으로 자금을 조달해야 한다는 조건이 필수적이다. 또한 최근 언론에 보도된 **Meta의 노후 자산 매각을 통한 외부 고객 컴퓨트 판매 가능성**이 부정적으로 메모리 반도체 주가에 영향을 미쳤으나, UBS는 이는 Blackwell/Rubin 및 MTIA 캐파 확대에 앞서 노후 자산의 monetization일 뿐 HBM 조달 자체에는 영향을 미치지 않는다고 해석했다. 스마트폰 BOM(Figure 21-22) 관점에서도 메모리 비중이 프리미엄폰 40% 이상, 중저가폰 60% 이상까지 급등하며 최종 소비자 가격 전가 압력이 커지고 있다.

## 7. HBM 수요 상향 및 인벤토리 정상화

UBS는 HBM 산업 수요 예상을 2026년 **33.1bn Gb (+90% YoY, 종전 32.9/58.0bn 상향)**, 2027년 **58.7bn Gb (+77% YoY)** 로 tweak up 했다. 배경은 (1) 최근 CoWoS 추정치 revision에 따라 HBM 조달을 8.5백만 NVIDIA AI GPU 유닛(2026E), 11.0백만(2027E)에 맞춘 것, (2) Google TPU 유닛 추정치를 2026E 4.2백만/2027E 9.1백만으로 조정, (3) AMD/AWS의 2027년 HBM 조달 상향 등이다. HBM 벤더별 bit shipment(Figure 3)를 보면 SK Hynix가 2026E 17,711mn Gb(+40% YoY), Samsung 11,034mn Gb(+155% YoY), Micron 7,778mn Gb(+70% YoY)로 삼성의 성장률이 가장 가파르다. HBM ASP(Figure 7)는 1Q24 $1.10/Gb에서 4Q27E $3.20/Gb 수준까지 상승하는 궤적이며, HBM이 DRAM 전체 매출에서 차지하는 비중은 2025년 22%에서 2026E 9%로 일시적으로 낮아지나 2027E 13%로 다시 상승한다(Figure 5-6). HBM 벤더 시장 점유율(Figure 8)은 2027E 기준 SK Hynix 39%, Samsung 41%, Micron 20%로 삼성이 리더십을 회복하는 그림이다.

## 8. 결론 — 투자 함의

- ① **2H26 메모리 사이클 재상향**: DDR 3Q26 +32% QoQ(→종전 +17%), 4Q26 +18% QoQ(→종전 +12%)로 대폭 상향, NAND 3Q26 +30% QoQ 재조정
- ② **2Q28까지 DRAM undersupplied**: 2027E 수요 +36.2% vs 공급 +19.3%로 17%p 갭, sufficiency ratio -13.6%로 unprecedented 부족
- ③ **NAND upcycle 4Q27까지**: SSD 서버 비중 2027E 37%까지 확대, ASP 2027E $0.37/GB(+42.7% YoY)
- ④ **LTA 협상 실제 진전**: Micron SCAs(floor/ceiling) vs 한국사 5년 60-70% 볼륨 고정, 삼성 3Q 중 대형 고객 완료 예정
- ⑤ **메모리 산업 매출 2026E $992bn, 2027E $1,763bn**: 2027 FCF US$1.2tn 접근, 주주환원 step-up 가능성
- ⑥ **하이퍼스케일러 affordability 리스크**: capex 자본시장 조달 지속 여부가 유일한 실질 리스크
- ⑦ **UBS 커버리지 Buy 유지**: Samsung(Key Call, PT ₩550k), SK Hynix(PT ₩3.20m from ₩3.00m), Micron(PT US$1,625), Kioxia(PT ¥132,000), Nanya Tech(PT NT$495)

## 9. 잠실개미 종합

UBS의 이번 7월호는 **메모리 사이클 상승 각도를 재차 가팔라지게 반영한 것이 핵심**이다. 3Q26 DDR을 +17%에서 +32%로, NAND를 +17%에서 +30%로 각각 대폭 상향한 점은 단순한 소폭 조정이 아니라 산업 체크의 결론이 이전보다 훨씬 강한 상승 시그널을 가리키고 있음을 뜻한다. 특히 2Q26에 이미 +67% QoQ의 폭발적 상승이 나온 상태에서 이후 분기에도 두 자릿수 QoQ 상승이 지속된다는 궤적은 지난 30년간 반도체 사이클에서 유례가 없는 국면이며, UBS 자체 사이클 분석에서 누적 +766% 상승으로 표기된 것도 이러한 unprecedented 성격을 뒷받침한다. 특히 sufficiency ratio가 2026E -8.1%에서 2027E -13.6%로 오히려 악화된다는 계산은, 심지어 하이퍼스케일러들이 인벤토리를 리빌드하지 않는다는 보수적 가정 하에서도 공급 부족이 심화됨을 의미한다는 점에서 매우 강력한 매수 시그널이다.

한편 LTA 협상의 실제 진전은 향후 사이클의 지속성과 변동성 관리 측면에서 양날의 검이다. 한국 메모리 3사가 볼륨의 60-70%를 5년 고정 가격으로 묶고 있는 구조는 벤더에게 CAPEX 회수 가시성을 제공하지만, 동시에 사이클 정점에서 프라이싱 업사이드를 일부 포기하는 트레이드오프이기도 하다. 반면 Micron의 floor/ceiling 방식 SCAs는 리스크를 양방향으로 관리하는 접근이므로, 향후 사이클 리스크가 실제로 발생할 때 벤더별 성과 편차가 뚜렷하게 드러날 가능성이 있다. 하이퍼스케일러 affordability 리스크는 실질적으로 매크로/유동성 리스크와 동치이며, 자본시장 조달 창구가 열려 있는 한 실제 조달 축소로 이어질 개연성은 낮다는 판단이 합리적이다. 다만 Meta의 노후 자산 매각 뉴스처럼 시장이 하이퍼스케일러의 조달 지속가능성을 의심하는 이벤트가 발생할 때마다 메모리 주가에 단기 조정 압력이 나타날 것이므로, 이러한 조정을 매수 기회로 활용하는 전략이 유효하다.

> **잠실개미 한 줄 요약**: UBS는 2H26 DDR·NAND 컨트랙트 가격을 각각 +32%/+30% QoQ로 재상향하며 메모리 사이클이 최소 2Q28까지 undersupplied 상태로 지속될 것임을 강조했고, 하이퍼스케일러 조달 지속과 LTA 확대라는 두 축이 이번 unprecedented upcycle의 지속가능성을 뒷받침한다. 삼성전자·SK하이닉스의 5년 고정 볼륨 LTA 구조는 사이클 정점의 프라이싱 업사이드 일부를 포기하는 트레이드오프지만, 사이클 지속성과 CAPEX 회수 가시성을 확보한다는 점에서 중장기 밸류에이션에 우호적이다.
