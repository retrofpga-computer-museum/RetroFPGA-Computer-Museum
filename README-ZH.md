# RetroFPGA Computer Museum

## 開場章節 — 專案介紹

## 🌐 RetroFPGA Computer Museum — 開放原始碼電腦歷史保存計畫
**一塊 FPGA，一台電腦，一個時代。**

RetroFPGA Computer Museum 是一個開放原始碼的工程、教育與數位保存計畫，致力於透過現場可程式化邏輯閘陣列（FPGA）技術，重建世界計算歷史。

從先驅微處理器與經典家用電腦，到商業大型主機、工業系統、軍事電腦、航空航太導航設備、太空船導引系統，以及經典電子遊戲主機，我們的使命是讓歷史上的計算架構重新活起來。

隨著原始硬體變得越來越稀少、昂貴且難以維護，FPGA 技術提供了一個強大的方法，讓這些機器背後的數位邏輯與工程知識得以保存與傳承。

**我們的目標不只是展示復古電腦，而是讓這些架構能被未來世代理解、研究與重新運作。**

### 🔗 透過 GitHub 探索專案
[**RetroFPGA Computer Museum — GitHub**](https://github.com/johnschoolworks/RetroFPGA-Computer-Museum)

探索開發路線圖、FPGA 實作、教育教程、技術文件，以及計畫中的展品。

我們歡迎來自世界各地的工程師、學生、教育者、研究者與復古電腦愛好者關注進度，並共同保存計算歷史。

## 歷史電腦畫廊

這些經典系統代表了博物館希望透過 FPGA 重建與研究的電腦類型。

<div align="center">
  <table>
    <tr>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Apple_II.jpg" width="300" alt="Apple II"><br>
        <b>Apple II</b>
      </td>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/4/4f/Commodore_PET_2001.jpg" width="300" alt="PET"><br>
        <b>PET</b>
      </td>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/8/8a/Commodore64.jpg" width="300" alt="Commodore 64"><br>
        <b>Commodore 64</b>
      </td>
    </tr>
    <tr>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/5/5f/Altair_8800_Computer.jpg" width="300" alt="Altair 8800"><br>
        <b>Altair 8800</b>
      </td>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/0b/Amiga_500.jpg" width="300" alt="Amiga"><br>
        <b>Amiga</b>
      </td>
      <td align="center">
        <img src="https://upload.wikimedia.org/wikipedia/commons/0/01/LM_lunar_lander.jpg" width="300" alt="Apollo lunar module"><br>
        <b>航太與太空船</b>
      </td>
    </tr>
  </table>
</div>

## 為什麼這個博物館存在：保存計算歷史

歷史上的電腦正變得越來越難以 **尋找、取得、維護與運作**。許多仍存留的機器已經年代久遠。它們的電容、儲存媒體、鍵盤、顯示器、電源供應器與特殊晶片都可能失效；替代零件稀少、昂貴，甚至已不再生產。能正常工作的一手實機常常價格高昂、地理位置不便、僅存放於機構內部，或因脆弱材質而不適合頻繁操作展示。這種情況對特殊工業控制器、主機、航空航太與太空船電腦，以及具有歷史意義的軍事系統特別明顯。即使硬體仍然存在，軟體、文件與操作所需的知識也可能逐漸消失。

**RetroFPGA Computer Museum 之所以存在，是因為單純保存原物並不足夠，而且實際上不可能得到每一台原始機器。** 透過在 FPGA 硬體中重建其數位邏輯，這個計畫希望讓歷史上的計算架構能對學生、開發者、研究者與愛好者可及，而不需要每個展品都依賴一台稀有且可用的原機。

FPGA 重建是 **物理保存的補充，而不是替代品**。FPGA 實作無法保留原始機器的材質、工業設計、模擬行為，或每一個未記錄的怪異特性。因此，博物館將記錄原始硬體、電路圖、軟體、歷史背景，以及每個重建版本與參考系統之間的差異。只要可行，展品都會優先重視可複現性、可修復性、開放文件與動手學習。

## 願景

RetroFPGA Computer Museum 是一個開放、以 FPGA 為核心的教育專案，致力於重建、研究與操作世界各地的歷史計算架構——從早期科學與工業機器，到商業系統、家用電腦、航空航太與太空船電腦、國防計算、遊戲機，以及現代開放指令集。

這個博物館的核心不是螢幕截圖，而是 **真正可運作的展品**：每個展品最終都應該能讓參觀者載入程式、檢查 CPU 狀態，並與 FPGA 上實際運行的邏輯互動。

我們遵循的原則是 **一次一個展品，而不是把所有展品塞進一個 bitstream**。這樣能保持擴展性，同時避免 FPGA 資源被耗盡。

## 五個計算時代

這些時代是 **策展分類**，而非嚴格的 CPU 位寬界線。處理器發布年份與某個完整系統成為關鍵影響力的時代可能不同；展品應該同時記錄兩者。

| 時代 | 期間 | 主題 | 典型展品 |
| --- | --- | --- | --- |
| **I — 計算先驅** | 1940–1976 | 計算基礎與早期微處理器 | SAP-1（教育模型）、Intel 4004/8008/8080、Altair 8800 |
| **II — 8 位黃金時代** | 1977–1986 | 家用電腦與個人電腦興起 | MOS 6502、Z80、Apple II、ZX81、Commodore 64、NES、IBM PC/XT、PC/AT |
| **III — 16/32 位革命** | 1987–1994 | 更大位址空間、圖形系統與進階家用電腦 | 80386/80486、Motorola 68000 系列、Amiga、Atari ST、Macintosh、Game Boy、SNES |
| **IV — 多媒體與網際網路** | 1995–2005 | 主流多媒體 PC、3D 圖形與連網計算 | Pentium 系列 PC、PowerPC 系統、PlayStation、Nintendo 64 |
| **V — 現代與開放計算** | 2006–至今 | SoC、64 位元計算與開放硬體 | ARM、RISC-V、x86-64 概念、FPGA SoC 實驗 |

**歷史註記：** 這些時間範圍用來組織博物館，並不表示每一個列出的處理器都在該時期首度問世。例如 80286 發表於 1982 年，80386 發表於 1985 年，Pentium 發表於 1993 年。

## 全球範圍：東、西與更遠的世界

這是一個 **全球計算遺產計畫**，而非僅限於美國家用電腦或西方個人電腦時間線的博物館。它致力於呈現來自 **北美、歐洲、東亞、前蘇聯與其他地區** 的計算傳統與創新，同時承認國際合作、技術轉移與平行發明的事實。

展品依據 **三個獨立軸線** 來整理：

1. **歷史時代：** 上述五個時代，各個實際發表日期會單獨記錄。
2. **地理與歷史脈絡：** 機器設計、製造、部署與影響力所在；同一機器可能屬於多個區域。
3. **應用領域：** 計算機是為了什麼目的而建造，而不只是是否銷往家用市場。

### 計算領域

| 展廳 | 範圍 | 典型歷史候選（尚非已完成 FPGA 展品） |
| --- | --- | --- |
| **科學與教育** | 早期計算、大学機器、教學 CPU、科學儀器 | EDSAC、PDP-8、SAP-1 教學設計、Hack CPU |
| **家用與個人** | 家用微電腦、個人電腦、區域計算生態 | Apple II、Commodore 64、ZX81、BBC Micro、NEC PC-8801/PC-9801、Fujitsu FM-7、Sharp X68000 |
| **商業與企業** | 商業資料處理、小型電腦、大型主機、工作站、POS | IBM System/360、DEC PDP-11/VAX、IBM PC/AT、選定商用工作站 |
| **工業與嵌入式** | 工廠自動化、PLC、流程控制、儀器與嵌入式控制器 | 早期可程式控制器、工業微處理器板、8051-based 控制器 |
| **航空與航太** | 飛行器導航、飛行電腦、航電、發射載具導引 | 公開文獻中的航電架構與歷史導引計算機設計 |
| **太空船與太空探索** | 載人太空船、衛星、探測器、機載導引與控制 | Apollo Guidance Computer、選定公開文獻的太空船電腦 |
| **國防與軍事計算** | 歷史指揮與控制、導航、雷達處理、堅固型計算 | 公開文獻中的歷史系統如 SAGE 和選定軍事電腦架構 |
| **遊戲與互動娛樂** | 街機硬體、專用主機、掌機、視訊與音效晶片 | Atari 2600/7800、NES、Game Boy、Sega Mega Drive、SNES、PlayStation（研究） |

表格中包含 **八個展廳**：科學/教育計算保留為獨立分類，同時並列七個應用領域。一台機器可能出現在多個展廳——例如某顆處理器可能同時被用於工業與太空船系統。

### 區域計算歷史

- **北美：** 早期電子計算、IBM 與 DEC 系統、家用電腦、工業控制、航太與遊戲機歷史。
- **西歐與北歐：** EDSAC、Sinclair、Acorn/BBC Micro、Amiga 時代生態、工業與科學計算。
- **日本與東亞：** NEC PC-88/PC-98、Fujitsu FM 系列、Sharp MZ/X1/X68000、MSX 生態、日本街機與主機硬體，以及台灣、韓國與中國在資料可得時的相關系統。
- **蘇聯與東歐計算：** BESM、ES EVM、Elektronika、BK 系列，以及區域性工業與科學系統（以可取得文件為前提）。
- **其他地區：** 具有歷史重要性的本地開發或改造系統，研究與貢獻者可協助填補收藏缺口。

區域分類是研究導向 **而非排他性國籍宣稱**。目錄條目應盡可能引用主要資料來源，區分已記錄事實與重建假設，避免將某一地區視為計算史的唯一正典。

### 特殊硬體保存與負責任重建

工業、航太、太空船與軍事電腦可能比消費型硬體更難取得，因為存留機器稀少、由機構持有、價格高昂、物理上脆弱，或文件不足。部分設計也涉及專有資訊、出口管制、安全關鍵行為或機密細節。

博物館僅使用 **合法公開、可適當授權的資訊**。我們不會尋求受限制的電路圖、受保護韌體或可直接操作軍事能力的內容。歷史國防與飛行電腦展品僅用於 **教育、架構研究與保存**，而非用於武器、飛機或太空船的部署。重建結果 **不是認證的飛行、工業安全或任務關鍵硬體**。

每個特殊展品都應明確標示其證據等級：**已記錄重建**、**部分子系統**、**架構示範** 或 **概念模擬**。當資料不完整時，博物館應明確說明，而不是捏造缺失功能。

### 實驗計算展廳

教學用途與虛構架構被單獨列出，不納入歷史產品時間線：

- **SAP-1 / Ben Eater 風格教育 CPU**
- *nand2tetris* 中的 **Hack CPU**
- *0x10c* 中的 **DCPU-16**
- 原始實驗性 CPU 和周邊設備

這些展品可依其所教概念連結到某個時代，但不應被描述為該時代的商業電腦。

## FPGA 平台：從入門到高階

博物館是 **FPGA 優先且多層級** 的計畫。**Digilent Basys 3 仍是主要開發與教育基線**，但博物館也會支援 **中階與高階 FPGA 平台**，使後期計算時代不被入門板子的資源限制所拘束。

| 層級 | 平台／候選系列 | 角色 | 典型目標 |
| --- | --- | --- | --- |
| **基礎** | **Digilent Basys 3 — Artix-7 XC7A35T** | **主要開發與教學平台**；VGA、開關、按鈕、7 段顯示、USB-JTAG/UART | ERA I–II 核心、簡單完整系統、CPU 教學 |
| 基礎／探索 | RealDigital Boolean Board — Spartan-7 XC7S50 | 次要開發板、替代視訊介面與可移植性測試 | 選定 ERA I–II 展品 |
| SoC／探索 | Digilent Zybo Z7-10 — Zynq-7000 | ARM + FPGA 協同設計、控制層與周邊實驗 | 選定跨時代或 SoC 展品 |
| **中階擴展** | 更大規模 Artix-7 / Kintex-7、AMD Artix UltraScale+ 或同級 Intel FPGA 板 | 更多邏輯、BRAM、記憶體頻寬、I/O 與外部 RAM | 更完整的 ERA III 系統；選定 ERA IV 組件 |
| **高階研究** | AMD Kintex/Virtex UltraScale(+) 或同級高容量 Intel FPGA 平台 | 大型 CPU/系統重建、複雜記憶體與視訊子系統 | 選定 ERA IV–V 研究展品與部分重建 |

*中階與高階系列是 **候選目標**，不是已擁有、已購買、已支援或已驗證的板子。確切板型將在評估成本、可用工具鏈、邏輯資源、外部 DDR/SDRAM、視訊介面、授權與建置可重現性之後才做選擇。*

### 依時代分配平台

- **ERA I–II：** 先用 Basys 3；只有在量測後發現需求超出範圍時才搬到其他板。
- **ERA III：** Basys 3 用於 CPU 導向展示；中階 FPGA 配外部記憶體用於更完整的 16/32 位元電腦重建。
- **ERA IV：** 依 CPU、晶片組、多媒體與記憶體需求選中階或高階 FPGA。並不假設可完全兼容原始系統。
- **ERA V：** 高階 FPGA 或 FPGA SoC 用於 **選定教育、開放 ISA 或子系統層級展示**。不承諾完整現代商用 CPU/PC 可交付。

**一塊 FPGA 不需要包含整座博物館。** 每個展品可能有自己的 bitstream、記憶體映像、支援板型矩陣與資源預算。高階硬體擴展收藏，同時不會排擠可接近的 Basys 3 教學路徑。

## 架構

```text
Linux Host
  ├── Museum CLI / exhibit catalog
  ├── Toolchains and assemblers
  ├── Bitstream manager ──────────────── USB-JTAG ─┐
  └── ROM / program uploader + debugger ─ USB-UART ┤
                                                    ▼
                                         FPGA Museum Platform
                                         ├── Clock / reset
                                         ├── VGA / PS/2 / UART
                                         ├── Buttons / switches / 7-segment
                                         └── Active exhibit bitstream
                                             ├── CPU or complete system
                                             ├── Memory and peripherals
                                             └── Debug / monitor interface
```

### 兩種不同的載入操作

1. **FPGA 設定：** 選擇一個硬體展品，並使用 JTAG 載入其 **bitstream**。不同 CPU 或電腦實作可能會有不同 bitstream。
2. **程式載入：** 當相容展品正在運作時，透過 UART（或其他支援介面）傳送 **ROM/RAM 映像**。這不需要重新綜合 FPGA。

傳統 SAP-1 只有 **16 bytes** 的可定址記憶體。為它製作 UART 載入器是一個很有教育意義的里程碑，但大型應用如 Tetris 則需要更強的 CPU/系統，或是獨立硬體實作。

### 為什麼不把所有內容一起綜合？

未啟用的硬體模組即使包含在同一個 bitstream 中，也仍會消耗 FPGA 資源。當前的 SAP-1/Calculator/Tetris 整合已說明，模組化、逐展品設計優於一個巨大的頂層實作。

## 展品設計標準

每個展品都應盡量包含：

- **身份：** 名稱、歷史脈絡、發表年份、時代、區域、展廳分類與技術註記。
- **硬體：** 可綜合的 RTL、頂層整合、限制條件、記憶體地圖與支援板卡。
- **軟體：** 組譯器/工具鏈資訊、範例程式、可重新分發的 ROM 映像。
- **互動：** 顯示器、輸入控制、程式上傳與可選除錯。
- **驗證：** 模擬、lint、綜合利用率、時序收斂與板載驗收結果。
- **文件：** 構建說明、操作指南、原始碼來源、保存理由、證據等級、限制條件與已知偏差。

CPU 核心與完整電腦是 **不同層級的展品**：一個可工作的 6502 核心並不等於 Apple II 硬體已完整完成。

## 初步展品路線圖

| 里程碑 | 交付物 | 狀態 |
| --- | --- | --- |
| **M001 — 博物館基礎** | 儲存庫結構、目錄 Schema、展品介面、文件 | 計畫中 |
| **M002 — SAP-1 展品** | 將現有 SAP-1 CPU 和 Calculator 工作整理為驗證展品；若需要，將實驗性 Tetris 保持獨立 | 既有工作待整理 |
| **M003 — UART 程式載入器** | HALT、LOAD、VERIFY、RUN、STATUS；主機端 Linux CLI | 計畫中 |
| **M004 — 多 bitstream 啟動器** | 從 Linux 選擇展品並對 FPGA 編程 | 計畫中 |
| **M005 — 經典 CPU 展廳** | Hack、MOS 6502、Z80、Motorola 68000、DCPU-16 | 計畫中／逐步實作 |
| **M006 — 經典電腦展廳** | ZX81、Apple II、C64、NES、Game Boy、Atari 7800 | 長期 |
| **M007 — 進階系統與平台擴展** | 評估中階/高階 FPGA 板、外部 RAM、選定 286/386 時代系統與現代教育核心 | 研究／可行性 |
| **M008 — 世界計算遺產目錄** | 交叉對照五個時代、地理歷史與八個應用展廳 | 計畫中 |
| **M009 — 特殊系統研究** | 公開文獻中的商業、工業、航空、太空船與歷史國防計算展品 | 研究／可行性 |

在任何儲存庫遷移之前，應保留現有 RetroFPGA-Basys3 教程與測試結果。新的展品工作不得悄悄覆蓋先前已驗證的基線。

## 擬定儲存庫結構

```text
RetroFPGA-Computer-Museum/
├── README.md
├── museum/
│   ├── catalog.yaml
│   ├── eras/
│   ├── regions/
│   ├── galleries/
│   ├── sources/
│   └── exhibits/
├── platform/
│   ├── basys3/
│   ├── boolean-board/
│   └── zybo-z7/
├── cores/
│   ├── sap1/
│   ├── hack/
│   ├── mos6502/
│   ├── z80/
│   ├── m68000/
│   └── dcpu16/
├── systems/
│   ├── zx81/
│   ├── apple2/
│   ├── c64/
│   ├── nes/
│   ├── gameboy/
│   ├── atari7800/
│   ├── commercial/
│   ├── industrial/
│   ├── aerospace/
│   ├── spacecraft/
│   └── defense-history/
├── software/
│   ├── assemblers/
│   ├── examples/
│   └── roms/
├── tools/
│   ├── museum-cli/
│   ├── rom-loader/
│   └── debugger/
├── tests/
├── tutorials/
└── releases/
```

*這是擬定目標結構，不表示這些目錄已存在。*

## 開發流程

```text
Select exhibit → Simulate/test RTL → Synthesize → Check LUT/BRAM/timing
       → Build bitstream → Program FPGA → Run hardware acceptance
       → (Optional) Upload program image → Inspect and debug
```

博物館優先採用 **Linux** 上可重現、命令列驅動的工作流。工具可能包括 Verilator、Icarus Verilog、Vivado、Python、C/C++ 以及適合每個 CPU 的開放原始碼組譯器。每個展品在驗證後，將記錄其命令與版本資訊。

## 資源與相容性政策

- 記錄每個 bitstream 的 **LUT、FF、BRAM、DSP、I/O、外部記憶體需求與時序** 結果。
- 發布板卡相容性矩陣，並說明何時需要中階或高階 FPGA。
- 保存原始機器文件，並記錄重建差異、限制與來源。
- 不要只依靠模擬就將展品標示為硬體就緒。
- 優先使用共用介面與可重用模組，但不要強迫不相關系統塞進同一個 bitstream。
- 在最佳化或遷移前保留可工作的參考實作。
- 尊重韌體、ROM、BIOS、遊戲與商標權；僅分發有適當授權的資產。
- 明確標示教育近似值；未有證據前，不宣稱週期精確或完整相容。

## 貢獻方式

我們歡迎在 CPU RTL、周邊設備、驗證、文件、Linux 工具鏈、歷史研究、保存來源、國際計算歷史、特殊系統研究，以及原始展示軟體等領域做出貢獻。請提供可重現的測試流程，並區分模擬結果與實際硬體測試。

## 結束章節 — 加入博物館

## 🚀 加入 RetroFPGA Computer Museum

### 保存計算歷史是共同責任
計算機歷史屬於每個人。

每台歷史電腦背後都藏著工程創新、科學發現與人類想像的故事。然而，許多機器正在消失，因為原始零件日漸老化，而其技術知識也越來越難以恢復。

RetroFPGA Computer Museum 希望透過開放原始碼協作、歷史研究與實際 FPGA 工程來改變這一點。

無論你的興趣包含：

- FPGA 開發、Verilog 與 SystemVerilog
- CPU 架構與數位邏輯
- 復古電腦與歷史作業系統
- 組合語言與軟體保存
- 工業、航太與太空船計算
- 軍事計算歷史
- 電玩主機與街機硬體
- Linux 開發工具與硬體除錯
- 技術文件與計算教育
**這個專案歡迎你。**

### 🔗 訪問我們的 GitHub 儲存庫
[**RetroFPGA Computer Museum — Open-Source Project**](https://github.com/johnschoolworks/RetroFPGA-Computer-Museum)

你可以透過 Star 儲存庫、提出 GitHub Issues 建議歷史系統、貢獻文件，或提交 Pull Requests 來分享硬體實作與開發工具。

我們長期的願景，是建立一座活的互動式博物館，讓不同時代與文明的電腦透過現代可程式化硬體再次運作。

**我們不只是重建舊電腦，我們是在保存讓現代計算成為可能的工程知識。**

### RetroFPGA Computer Museum
*一塊 FPGA，一台電腦，一個時代。*

**為未來世代重建世界計算遺產。**

## 授權

**待定。** 儲存庫擁有者將選擇一個授權條款。第三方核心、ROM、文件與資產可能有各自的授權，並且必須保留其聲明。
