# Formula SAE 2027 規則翻譯索引 — IC（燃油車）適用範圍

**來源文件**：`C:\Users\ohona\OneDrive\Desktop\FSAE_IC\FSAE_Rules_2027_V1.pdf`
**文件**：Formula SAE Rules 2027 Version 1.0（© 2026 SAE International, 1 Sept 2026），共 147 頁
**建立日期**：2026-09-25
**目的**：整理所有適用於 IC（Internal Combustion，燃油車）的車輛設計、製造、技術要求、檢驗、操作與競賽運行規則，翻譯為繁體中文。
**對照年份**：與 `FSAE_Rules_2026_V1.pdf`（145 頁）逐規則比對，標記 2027 新增與修訂規則。

> **圖例**
> - 🆕 **新增**：2027 出現、2026 不存在的規則。
> - ✏️ **修訂**：2027 與 2026 內容實質不同（措辭、數值、結構重編或要求變動）。
> - 未標記者 = 與 2026 相同（或僅行內換行/標點微調，無實質變動）。

## 範圍定義

- ✅ 包含 IC 車專屬規則（IC 章、F.9、IN.12、IN.14.2）。
- ✅ 包含所有車輛通用規則（GR、AD、PS、V、F（除 F.10/F.11）、T（除 T.5.3）、VE（除 VE.2.4）、IN（除 EV-only 項）、S、D）。
- ❌ 排除僅適用 EV 且與 IC 完全無關的規則（EV 整章、F.10、F.11、T.5.3、VE.2.4、AD.5.2/5.3、IN.5、IN.10、IN.13、IN.14.3）。
- ✅ 通用章節中引用的其他章節內容，若 IC 車必要則納入（已在各 chunk 備註）。

> **2027 重大結構變動（IC 相關）**
> - **EV 章整章重編**：EV.5/6/7/8/9/10/11/12 全面重新編號（新增 EV.13、EV.6 Status Indicators 等）。**不影響 IC 翻譯**（EV 全章排除），但頁碼整體位移 +2～+5 頁。
> - **T.6.1（Compressed Gas）重編**：T.6.1.4–9 重新編排並新增 **T.6.1.10（車手防護罩）**。
> - **GR.9.3（參賽資格）重編**：GR.9.3.1–3 結構改寫，新增 **GR.9.3.4（第三年車禁賽）**。
> - **S.3.15（Cost Scenario）重編**：改為 S.3.15.1–5 子規則，並影響 S.3.16.3/4。
> - **AD.4.1/4.2 重編**：AD.4.1.1/4.1.2 移除、AD.4.2.3/4.2.4 調整，新增 **AD.3.7 Career Profile**。
> - **F.7.8.6–8 改寫**（monocoque 固定背板要求變動）。

## 一、需翻譯章節索引（通用 + IC 專屬）

### GR - General Regulations（一般規則）p5–11

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| GR.1 | Formula SAE Competition Objective | 5 | 通用 | 是 | — |
| GR.2 | Organizer Authority | 6 | 通用 | 是 | — |
| GR.3 | Team Responsibility | 6–7 | 通用 | 是 | — |
| GR.4 | Rules Authority and Issue | 7 | 通用 | 是 | — |
| GR.5 | Rules of Conduct | 8 | 通用 | 是 | — |
| GR.6 | Rules Format and Use | 8–9 | 通用 | 是 | — |
| GR.7 | Rules Questions | 9 | 通用 | 是 | ✏️ GR.7.1/7.2.1 措辭微調 |
| GR.8 | Protests | 9–10 | 通用 | 是 | — |
| GR.9 | Vehicle Eligibility | 10–11 | 通用 | 是 | ✏️ GR.9.3.1–3 重編；🆕 GR.9.3.4 第三年車禁賽 |

### AD - Administrative Regulations（行政規則）p12–15

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| AD.1 | The Formula SAE Series | 12 | 通用 | 是 | — |
| AD.2 | Official Information Sources | 12 | 通用 | 是 | — |
| AD.3 | Individual Participation Requirements | 12–13 | 通用 | 是 | 🆕 AD.3.7 Career Profile；✏️ AD.3.4 |
| AD.4 | Individual Registration Requirements | 13 | 通用 | 是 | ✏️ AD.4.1 重編（移除 4.1.1/4.1.2）、AD.4.2.3/4.2.4 |
| AD.5.1 | Faculty Advisor | 13 | 通用 | 是 | — |
| AD.5.2 | Electrical System Officer | 14 | EV Only | 否 | — |
| AD.5.3 | Electric System Advisor | 14 | EV Only | 否 | ✏️（EV，僅備註） |
| AD.6 | Competition Registration | 14 | 通用 | 是 | — |
| AD.7 | Competition Site | 15 | 通用 | 是 | — |

### PS - Pre-Competition Submissions（賽前提交）p16–18

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| PS.1 | Documentation | 16 | 通用 | 是 | ✏️ PS.1.2.x 提交清單調整 |
| PS.2 | Submission Details | 16–17 | 通用 | 是 | ✏️ PS.3.1.3/3.2.x 措辭 |
| PS.3 | Submission Penalties | 17–18 | 通用 | 是 | ✏️ PS.3.3.1（移除 PS.3.4.3） |

### V - Vehicle Requirements（車輛要求）p19–22

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| V.1 | Configuration | 19 | 通用 | 是 | — |
| V.2 | Driver | 20 | 通用 | 是 | — |
| V.3 | Suspension and Steering | 20–21 | 通用 | 是 | — |
| V.4 | Wheels and Tires | 21–22 | 通用 | 是 | — |

### F - Chassis and Structural（底架與結構）p23–54

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| F.1 | Definitions | 23–25 | 通用 | 是 | ✏️ F.1.13 |
| F.2 | Documentation | 25 | 通用 | 是 | 🆕 F.2.2.2；✏️ F.2.1.2 |
| F.3 | Tubing and Material | 25–28 | 通用 | 是 | 🆕 F.3.4.4；✏️ F.3.5 |
| F.4 | Composite and Other Materials | 28–31 | 通用 | 是 | ✏️ F.4.3.1 |
| F.5 | Chassis Requirements | 31–37 | 通用 | 是 | 🆕 F.5.7.8；✏️ F.5.3.1、F.5.9.3、F.5.12.x |
| F.6 | Tube Frames | 38–40 | 通用 | 是 | ✏️ F.6.3.6、F.6.4.2、F.6.6.3 |
| F.7 | Monocoque | 40–44 | 通用 | 是 | 🆕 F.7.8.9；✏️ F.7.8.6–8 改寫、F.7.9.1 |
| F.8 | Front Chassis Protection | 44–49 | 通用 | 是 | — |
| F.9 | Fuel System | 49 | IC 專屬 | 是 | — |
| F.10 | Tractive Battery Container | 50–53 | EV Only | 否 | — |
| F.11 | Tractive System | 53–55 | EV Only | 否 | — |

### T - Technical Aspects（技術面）p55–76

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| T.1 | Cockpit | 56–59 | 通用 | 是 | ✏️ T.1.2.3、T.1.4.1/4.3、T.1.8.3 |
| T.2 | Driver Accommodation | 59–64 | 通用 | 是 | ✏️ T.2.3.1、T.2.4.1/4.5、T.2.8.5 |
| T.3 | Brakes | 65–66 | 通用 | 是 | ✏️ T.3.3.1 |
| T.4 | Electronic Throttle Components | 66–68 | 通用 | 是 | — |
| T.5.1 | Transmission and Drive | 68 | 通用 | 是 | — |
| T.5.2 | Drivetrain Shields and Guards | 69 | 通用 | 是 | — |
| T.5.3 | Motor Protection | 70 | EV Only | 否 | — |
| T.5.4 | Coolant Fluid | 70 | 通用 | 是 | — |
| T.5.5 | System Sealing | 70 | 通用 | 是 | — |
| T.5.6 | Catch Cans | 70–71 | 通用 | 是 | — |
| T.6 | Pressurized Systems | 71 | 通用 | 是 | ✏️ T.6.1.4–9 重編；🆕 T.6.1.10 車手防護罩 |
| T.7 | Bodywork and Aerodynamic Devices | 72–74 | 通用 | 是 | — |
| T.8 | Fasteners | 74 | 通用 | 是 | ✏️ T.8.2.1 |
| T.9 | Electrical Equipment | 75–76 | 通用 | 是 | ✏️ T.9.1.1（措辭） |

### VE - Vehicle and Driver Equipment（車輛與車手裝備）p77–80

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| VE.1 | Vehicle Identification | 77 | 通用 | 是 | — |
| VE.2.1 | Jacking Point | 77 | 通用 | 是 | — |
| VE.2.2 | Push Bar | 77 | 通用 | 是 | — |
| VE.2.3 | Fire Extinguisher | 77 | 通用 | 是 | — |
| VE.2.4 | Electrical Equipment | 78 | EV Only | 否 | — |
| VE.2.5 | Camera Mounts | 78 | 通用 | 是 | — |
| VE.3 | Driver Equipment | 79–80 | 通用 | 是 | — |

### IC - Internal Combustion Engine Vehicles（燃油車）p81–91 ⭐ IC 專屬

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| IC.1 | General Requirements | 81 | IC 專屬 | 是 | — |
| IC.2 | Air Intake System | 81–83 | IC 專屬 | 是 | ✏️ IC.2.5.3 |
| IC.3 | Throttle | 82–83 | IC 專屬 | 是 | — |
| IC.4 | Electronic Throttle Control | 83–86 | IC 專屬 | 是 | — |
| IC.5 | Fuel and Fuel System | 86–87 | IC 專屬 | 是 | ✏️ IC.5.4.4（燃油視窗管免核准） |
| IC.6 | Fuel Injection | 88 | IC 專屬 | 是 | — |
| IC.7 | Exhaust and Noise Control | 88–89 | IC 專屬 | 是 | — |
| IC.8 | Electrical | 90 | IC 專屬 | 是 | — |
| IC.9 | Shutdown System | 90–91 | IC 專屬 | 是 | ✏️ IC.9.4.2 |

### IN - Technical Inspection（技術檢驗）p115–124

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| IN.1 | Inspection Requirements | 115–115 | 通用 | 是 | 🆕 IN.1.2.3（檢驗員可延遲/跳過） |
| IN.2 | Inspection Conduct | 115–116 | 通用 | 是 | ✏️ IN.2.1 |
| IN.3 | Inspection Parts | 116 | 通用 | 是 | ✏️ IN.3.1 |
| IN.4 | Initial Inspection / Gear Check | 116 | 通用 | 是 | — |
| IN.5 | Tractive Battery Pack and Charger Inspection | 116–117 | EV Only | 否 | — |
| IN.6 | Vehicle Inspection | 117–118 | 通用（含 IC-only 小節） | 是 | ✏️ IN.6、IN.6.1、IN.6.5.x（標題改 Vehicle Inspection） |
| IN.7 | Driver Template Inspections | 118 | 通用 | 是 | ✏️ IN.7.2 |
| IN.8 | Cockpit Template Inspections | 118 | 通用 | 是 | ✏️ IN.8.2 |
| IN.9 | Driver Cockpit Checks | 118–119 | 通用 | 是 | — |
| IN.10 | Active Inspection (EV only) | 119–120 | EV Only | 否 | — |
| IN.11 | Tilt Test | 120 | 通用 | 是 | — |
| IN.12 | Noise and Switch Test (IC Only) | 120–121 | IC 專屬 | 是 | ✏️ IN.12.3 |
| IN.13 | Rain Test (EV Only) | 121 | EV Only | 否 | — |
| IN.14 | Brake Test | 122 | 通用（IN.14.2 IC-only，IN.14.3 EV-only） | 是（排除 IN.14.3） | — |
| IN.15 | Inspection Approval | 122–123 | 通用 | 是 | — |
| IN.16 | Modifications and Repairs | 123–124 | 通用 | 是 | — |
| IN.17 | Reinspection | 124 | 通用 | 是 | ✏️ IN.17.3.2 |

### S - Static Events（靜態賽事）p125–131

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| S.1 | General Static | 125 | 通用 | 是 | — |
| S.2 | Presentation Event | 125–126 | 通用 | 是 | ✏️ S.2.4.3 |
| S.3 | Cost and Manufacturing Event | 126–130 | 通用 | 是 | 🆕 S.3.15.1–5；✏️ S.3.16.3/4（移除 S.3.16.5） |
| S.4 | Design Event | 130–131 | 通用 | 是 | ✏️ S.4.4.1 |

### D - Dynamic Events（動態賽事）p132–147

| 規則編號 | 原文標題 | PDF 頁碼 | 適用性 | 需翻譯 | 2027 變動 |
|---|---|---|---|---|---|
| D.1 | General Dynamic | 132 | 通用 | 是 | — |
| D.2 | Pit and Paddock | 132–133 | 通用 | 是 | ✏️ D.2.3 |
| D.3 | Driving | 133 | 通用 | 是 | — |
| D.4 | Flags | 134 | 通用 | 是 | ✏️ D.4.1.2/4.1.3 |
| D.5 | Weather Conditions | 134–135 | 通用 | 是 | — |
| D.6 | Tires and Tire Changes | 135 | 通用 | 是 | — |
| D.7 | Driver Limitations | 135–136 | 通用 | 是 | — |
| D.8 | Definitions | 136 | 通用 | 是 | — |
| D.9 | Acceleration Event | 136–137 | 通用 | 是 | ✏️ D.9.2.1 |
| D.10 | Skidpad Event | 137–139 | 通用 | 是 | ✏️ D.10.2.1 |
| D.11 | Autocross Event | 139–141 | 通用 | 是 | ✏️ D.11.2.1 |
| D.12 | Endurance Event | 141–145 | 通用 | 是 | ✏️ D.12.4.2、D.12.10.4、D.12.13.3 |
| D.13 | Efficiency Event | 145–147 | 通用 | 是 | — |
| D.14 | Post Endurance | 147 | 通用 | 是 | ✏️ D.14.3.3 |

## 二、排除的 EV-only 章節

| 規則編號 | 原文標題 | PDF 頁碼 | 排除原因 |
|---|---|---|---|
| AD.5.2 / AD.5.3 | Electrical System Officer / Electric System Advisor | 14 | EV Only — 電動系統人員要求，IC 車無對應需求 |
| F.10 | Tractive Battery Container | 50–53 | EV Only — 動力電池箱 |
| F.11 | Tractive System | 53–55 | EV Only — 動力系統（電池/充電器安裝） |
| T.5.3 | Motor Protection | 70 | EV Only — 電動馬達防護 |
| VE.2.4 | Electrical Equipment (EV Only) | 78 | EV Only — 電動車用電氣設備 |
| EV.1 ~ EV.13 | EV - Electric Vehicles 整章 | 92–114 | EV Only — 電動車輛整章（2027 全章重新編號，新增 EV.13） |
| IN.5 | Tractive Battery Pack and Charger Inspection | 116–117 | EV Only — 動力電池與充電器檢驗 |
| IN.10 | Active Inspection (EV only) | 119–120 | EV Only — 電動車動態電氣檢驗 |
| IN.13 | Rain Test (EV Only) | 121 | EV Only — 淋水測試 |
| IN.14.3 | Brake Test Conduct (EV Only) | 122 | EV Only — 煞車測試電動車執行方式 |

## 三、通用章節中的 EV-only 子節（翻譯時跳過）

| 章節 | PDF 頁碼 | 說明 |
|---|---|---|
| AD.5 | 14 | AD.5.2 / AD.5.3 標註 EV Only，翻譯時排除 |
| T.5 | 68–70 | T.5.3 標註 EV Only，翻譯時排除；其餘 T.5 子節通用 |
| VE.2 | 78 | VE.2.4 標註 EV Only，翻譯時排除 |
| IN.14 | 122 | IN.14.2 為 IC 專屬、IN.14.3 為 EV Only（排除） |

## 四、翻譯分塊計劃（每個 chunk 一個 subagent）

| Chunk ID | 內容 | PDF 頁碼 | 適用性 | 輸出檔案 | 2027 變動摘要 |
|---|---|---|---|---|---|
| 01_GR | GR 一般規則 | p5–11 | 通用 | `FSAE_IC_chunks_2027/01_GR_p5-p11.md` | ✏️ GR.7/9.3；🆕 GR.9.3.4 |
| 02_AD_PS | AD 行政規則 + PS 賽前提交 | p12–18 | 通用（AD.5.2/5.3 EV-only 跳過） | `02_AD_PS_p12-p18.md` | 🆕 AD.3.7；✏️ AD.4/3.4、PS.1.2/3.x |
| 03_V | V 車輛要求 | p19–22 | 通用 | `03_V_p19-p22.md` | — |
| 04_F1-F3 | F.1–F.3 定義/文件/管材材料 | p23–28 | 通用 | `04_F1-F3_p23-p28.md` | 🆕 F.2.2.2、F.3.4.4；✏️ F.1.13/2.1.2/3.5 |
| 05_F4-F5 | F.4–F.5 複合材料/底架要求 | p28–37 | 通用 | `05_F4-F5_p28-p37.md` | 🆕 F.5.7.8；✏️ F.4.3.1/5.3.1/5.9.3/5.12.x |
| 06_F6-F7 | F.6–F.7 管架/單體殼體 | p38–44 | 通用 | `06_F6-F7_p38-p44.md` | 🆕 F.7.8.9；✏️ F.6.3.6/6.4.2/6.6.3/7.8.6–8；含 F.7.9.2 測試角表格 |
| 07_F8 | F.8 前部防護 | p44–49 | 通用 | `07_F8_p44-p49.md` | 含 F.8.8.4b–d/F.8.8.5–7 溢至 p49 |
| 08_F9 | F.9 燃油系統（IC Only） | p49–50 | IC 專屬 | `08_F9_p49-p50.md` | ✏️ F.9.1.1（inside→in 措辭）；F.10/F.11（EV Only, p50–55）已排除 |
| 09_T1-T2 | T.1–T.2 座艙/車手容納 | p56–65 | 通用 | `09_T1-T2_p56-p65.md` | 含 T.2.9（p65，T.3 前）；✏️ T.1.2.3/1.4.x/1.8.3、T.2.3.1/2.4.x/2.8.5 |
| 10_T3-T4 | T.3–T.4 煞車/電子油門元件 | p65–68 | 通用 | `10_T3-T4_p65-p68.md` | 含 T.4.3（BSE）溢至 p68；✏️ T.3.3.1 |
| 11_T5-T6 | T.5–T.6 動力傳動/加壓系統 | p68–72 | 通用（跳過 T.5.3 EV Only） | `11_T5-T6_p68-p72.md` | 🆕 T.6.1.4（PRV 新規則）/T.6.1.10，✏️ T.6.1.8，T.6.1.5–9 純重新編號 |
| 12_T7-T9 | T.7–T.9 車身空力/螺絲/電氣 | p72–76 | 通用 | `12_T7-T9_p72-p76.md` | ✏️ T.7.7.1/T.7.7.2（inside→inner surface、Inside→Between）、T.8.2.1（d 項）、T.9.2.1；T.9 內 EV.7→EV.8 為交叉引用重編號 |
| 13_VE | VE 車輛與車手裝備 | p77–80 | 通用（VE.2.4 EV-only 跳過） | `13_VE_p77-p80.md` | — |
| 14_IC1-IC5 | IC.1–IC.5 一般/進氣/油門/ETC/燃油 | p81–88 | IC 專屬 | `14_IC1-IC5_p81-p88.md` | ✏️ IC.1.2、IC.2.5.3（刪 RQ 句）、IC.4.1.1、IC.5.4.4（新增 a–c 要求） |
| 15_IC6-IC9 | IC.6–IC.9 噴油/排氣/電氣/關斷 | p88–91 | IC 專屬 | `15_IC6-IC9_p88-p91.md` | ✏️ IC.9.4.2 |
| 16_IN1-IN4 | IN.1–IN.4 檢驗要求/初檢 | p115–116 | 通用 | `16_IN1-IN4_p115-p116.md` | 🆕 IN.1.2.3；✏️ IN.2.1/3.1 |
| 17_IN6-IN9 | IN.6–IN.9 車輛檢驗/模板/座艙檢查 | p117–119 | 通用（含 IN.6.4 IC-only） | `17_IN6-IN9_p117-p119.md` | ✏️ IN.6 標題改 VEHICLE INSPECTION、IN.6/6.1 術語、IN.6.2.1（措辭）、IN.6.5.x（含 EV.11→EV.12 交叉引用）、IN.7.2/8.2、IN.9.1（their driving position）、IN.9.3.2 |
| 18_IN11-IN12 | IN.11–IN.12 傾斜測試/噪音開關 | p120–121 | 通用 + IC 專屬 | `18_IN11-IN12_p120-p121.md` | ✏️ IN.11.1.b（their driving position）、IN.12.3（措辭）、IN.12.4.3（up to→thru） |
| 19_IN14-IN17 | IN.14–IN.17 煞車測試/核准/複驗 | p122–124 | 通用（IN.14.3 EV-only 跳過） | `19_IN14-IN17_p122-p124.md` | ✏️ IN.17.3.2 |
| 20_S | S 靜態賽事 | p125–131 | 通用 | `20_S_p125-p131.md` | 🆕 S.3.15.1–5；✏️ S.2.4.3/3.16.3-4/4.4.1 |
| 21_D1-D8 | D.1–D.8 動態總則/維修區/駕駛/旗語 | p132–136 | 通用 | `21_D1-D8_p132-p136.md` | ✏️ D.1.2（定義）、D.2.1（pushing 措辭）、D.2.3、D.3.3（措辭）、D.4.1.2/4.1.3（旗語） |
| 22_D9-D11 | D.9–D.11 加速/圓圈/彎道 | p136–140 | 通用 | `22_D9-D11_p136-p140.md` | ✏️ D.9.2.1/10.2.1/11.2.1 |
| 23_D12-D14 | D.12–D.14 耐力/效率/耐力後 | p141–147 | 通用 | `23_D12-D14_p141-p147.md` | ✏️ D.12.4.2（up to→maximum）、D.12.10.4.a（inside→in）、D.12.13.3（up to→maximum 25 分）、D.14.3.2（罰時下限 120→60 sec）、D.14.3.3（up to→thru） |

> 每個 subagent 只處理一個 chunk，只能讀取上表指定的預提取 txt（`C:\Users\ohona\fsae27_chunks\fsae27_<cid>_<label>_p<a>-p<b>.txt`），不得讀整份 PDF。完成後只回報：Completed / 規則範圍 / 頁碼 / 檔案路徑 / ≤100 tokens 摘要。

## 五、2027 新增 / 修訂規則明細（IC 相關，供翻譯與核對）

### 🆕 全新規則（2026 不存在）

| 規則 | 位置 | 內容摘要 |
|---|---|---|
| GR.9.3.4 | p11 | 第三年車（Third Year Vehicles）不得參加任何 Formula SAE 比賽 |
| AD.3.7 Career Profile | p13 | 所有學生隊員必須在 Onsite Registration 前完成並維持 Event Website 上的 Student Career Profile；未完成者可能被禁止參賽 |
| AD.4.2.4 | p13 | Onsite registration 必須在車輛卸載/開箱/任何作業前完成（原 AD.4.2.3 內容，重編號） |
| F.2.2.2 | p25 | SES 審查者的所有意見與要求必須被解決 |
| F.3.4.4 | p27 | 結構焊縫形狀不得以機械方式改變 |
| F.5.7.8 | p34 | 前 hoop 外緣頂部不應有凹面 |
| F.7.8.9 | p43 | monocoque 固定點與 F.7.5 Side Impact Structure 間的負載路徑必須使用帶芯連續層壓板 |
| T.6.1.10 | p71 | 車手必須由鋼或鋁（≥1 mm 厚）防護罩隔絕於加壓系統，距離 ≥25 mm |
| IN.1.2.3 | p115 | 技術檢驗員得依首席技術檢驗員裁量，以任何理由延遲、後移或拒絕檢驗任何送檢車輛 |
| S.3.15.1–5 | p128–129 | Cost Scenario 改以子規則呈現（提供/內容/事前提交/評分/罰分） |

### ✏️ 實質修訂規則（與 2026 不同，IC 相關重點）

| 規則 | 位置 | 變動說明 |
|---|---|---|
| GR.9.3.1–3 | p11 | 參賽資格結構重編（First/Second/Third Year Vehicle 條目重新組織） |
| AD.3.4 | p13 | 措辭調整（SAE 會員證明） |
| AD.4.1 | p13 | 重編：移除 AD.4.1.1/4.1.2，改為單段「Preliminary Registration」 |
| AD.4.2.3 | p13 | 改為「未完成 Career Profile 可能禁止參賽」 |
| F.1.13 | p25 | 定義微調 |
| F.2.1.2 | p25 | 文件要求措辭 |
| F.3.5 | p27 | 鋁管（Aluminum Tubing）要求調整 |
| F.4.3.1 | p28–29 | 複合材料要求調整 |
| F.5.3.1 / F.5.9.3 / F.5.12.x | p32–36 | 底架 hoop/brace 幾何與連接要求改寫（F.5.9.3 改用表格） |
| F.6.3.6 / F.6.4.2 / F.6.6.3 | p38–40 | 管架要求微調 |
| F.7.8.6–8 | p42–43 | monocoque 固定背板（mounting/backing plates）要求改寫（連續近圓/橢形外緣、不得有切孔等） |
| F.7.9.1 | p43 | 駕駛束帶固定點負載要求微調 |
| T.1.2.3 / T.1.4.1 / T.1.4.3 / T.1.8.3 | p56–59 | 座艙要求措辭/數值調整 |
| T.2.3.1 / T.2.4.1 / T.2.4.5 / T.2.8.5 | p59–64 | 車手容納/頭枕固定（T.2.8.5 頭枕固定改為「頂部與底部固定且須承受…」） |
| T.3.3.1 | p65 | 煞車要求微調 |
| T.6.1.4–9 | p71 | Compressed Gas 子規則全部重新編號與改寫（壓力 relief valve、管線、絕緣、氣瓶位置等重排） |
| T.8.2.1 / T.9.1.1 | p74–75 | 螺絲/電氣定義措辭 |
| IC.2.5.3 | p82 | 進氣系統要求調整 |
| IC.5.4.4 | p87 | 透明燃油加油頸管可作視窗管——**移除「須經 Rules Question 或檢驗員核准」**，改為明確條件（耐汽油/乙醇、保護於 >60°C 熱源、連接處有凸脊固定） |
| IC.9.4.2 | p90–91 | 關斷系統要求調整 |
| IN.2.1 / IN.3.1 | p115–116 | 檢驗執行/零件要求調整 |
| IN.6 / IN.6.1 / IN.6.5.x | p117–118 | 標題由 Mechanical/Electrical Inspection 改為 **Vehicle Inspection**；子節措辭調整 |
| IN.7.2 / IN.8.2 | p118 | 模板檢查要求調整 |
| IN.12.3 | p120–121 | 噪音/開關測試要求調整 |
| IN.17.3.2 | p124 | 複驗要求調整 |
| S.2.4.3 | p125 | 簡報要求調整 |
| S.3.16.3 / S.3.16.4 | p129 | Cost 評分重編（原 S.3.16.3 計分項目移除，改由 S.3.16.3 罰分、S.3.16.4 正規化/縮放） |
| S.4.4.1 | p130 | 設計簡報要求調整 |
| D.2.3 / D.4.1.2 / D.4.1.3 | p132–134 | 維修區/旗語要求調整 |
| D.9.2.1 / D.10.2.1 / D.11.2.1 | p136–139 | 加速/圓圈/彎道執行要求調整 |
| D.12.4.2 / D.12.10.4 / D.12.13.3 | p141–145 | 耐力賽要求調整 |
| D.14.3.3 | p147 | 耐力後要求調整 |

> 上述「措辭/數值調整」為逐句比對偵測出的實質差異；翻譯時以 2027 原文為準。若某段無法確定是否適用 IC，subagent 應標註 ⚠️ 適用性待確認，不得自行刪除。

## 六、備註

- 頁碼以 2027 PDF 頁腳標示為準（1-based，共 147 頁）。因 EV 章重編，IN/S/D 等章節頁碼較 2026 整體位移 +2～+5 頁，本索引已逐節用文字搜尋校正。
- F.9（Fuel System, IC Only）與 F.10（EV Only）同頁起始於 p49–50，翻譯時僅取 F.9 內容。
- IN.12（Noise and Switch Test）標註 IC Only，為 IC 專屬。IN.14.2 為 IC 專屬煞車測試執行方式；IN.14.3（EV Only）排除。
- 預提取 txt 已存放於 `C:\Users\ohona\fsae27_chunks\`，subagent 只讀對應檔案。
- 新增/修訂標記已嵌入各 chunk 目標，subagent 翻譯時應在對應規則標題旁加 🆕 或 ✏️ 標記（保留原文，不改內容）。
