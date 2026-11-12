# QuantumSea 英文术语表 · v1.5

**状态**：修订冻结版（2026-11-12，v1.5 补注 ATTUNE 官方域名）  
**适用范围**：《换季》、World Code / 引擎、ATTUNE、余岸观测站、官网、Steam 商店页、代码与技术文档。  
**用途**：统一中文概念与英文名称，避免不同产品、文本和代码各自发明译名。

> 本版在 v1 基础上修正空间层级表达、统一补充相关措辞，并补入五行路由与四相交换的简要英文释义。五行路由的完整运行规则以引擎规则文档为准；本术语表不重复定义其算法。

---

## 一、命名原则

1. **专有概念固定大小写。** `World Code`、`The Ledger`、`Tidal Cloud Space`、`Cosmic Core`、`Buzhou Rift`、`Tear Bubble` 等按表中形式书写。进入代码后可转换为 `camelCase` 或 `SCREAMING_SNAKE_CASE`，但底层词汇保持一致。
2. **普通物理过程优先使用已有英语术语。** `Bonding`、`Ionization`、`Decomposition` 等沿用其既有含义，不为普通过程另造词。
3. **一个中文概念对应一个正式英文名称。** 首次出现时可以增加解释句，但不得在同一语境中混用第二套译名。
4. **术语表只规定名称和必要语义边界。** 引擎已有完整定义的机制，以引擎规则文档为准；本表不另行创造计算规则。
5. **区分概念层级。** 四个 Tear Bubbles 与 Cosmic Core 不是同一类别：潮汐云空间是四个泪泡之一，Cosmic Core 是参与五行关系的另一个空间，不是第五个泪泡。

---

## 二、核心术语总表

### A. 层级与空间结构

| 中文 | 正式英文 | 类型 | 定义 / 注记 |
| --- | --- | --- | --- |
| 量子海 | **Quantum Sea** | 基础层 | 能量、负能量、信息与熵所处的基础层。 |
| 泪泡 | **Tear Bubble** | 现实层结构 | 由四相失衡后排出多余相而形成的三相天体结构；完整定义见第三节。复数为 `Tear Bubbles`。 |
| 能量泡 | **Energy Bubble** | 泪泡 | 五行属性为火（Fire）。 |
| 物质泡 | **Matter Bubble** | 泪泡 | 五行属性为金（Metal）。 |
| 文明泡 | **Civilization Bubble** | 泪泡 | 五行属性为水（Water）。 |
| 潮汐云空间 | **Tidal Cloud Space** | 泪泡 / 中间层空间 | 四个泪泡之一，五行属性为木（Wood）；同时承担潮汐调配、向其他现实泪泡补充以及打破固化的中间层作用。它不是四个泪泡之外的独立设施。 |
| 银心 / 土锚 / 银河核心 | **Cosmic Core** | 独立空间结构 | 五行属性为土（Earth），承担现实结构的回收与稳定作用；参与五空间关系，但不是第五个泪泡。 |
| 不周山裂隙 | **Buzhou Rift** | 通道 / 入口 | 连接量子海与潮汐云空间的补充入口。首次出现可写 `The Rift of Mount Buzhou`，之后统一使用 `Buzhou Rift`。 |

### B. 机制与状态

| 中文 | 正式英文 | 类型 | 定义 / 注记 |
| --- | --- | --- | --- |
| 回收 | **Reclamation** | 过程 | 将现实层中符合回收条件的结构或信息带回量子海；不等同于简单销毁。 |
| 补充 | **Replenishment** | 过程 | 对缺失状态进行补足。不要用 `Injection` 作为正式术语。 |
| 稳定 | **Stabilization** | 过程 / 状态 | 使系统趋于动态稳定；不意味着系统失去继续演化的能力。 |
| 激活 | **Activation** | 过程 / 状态 | 使系统重新进入活动或演化过程。 |
| 潮汐补充 | **Tidal Replenishment** | 机制 | 经由潮汐云空间进行的补充。 |
| 潮汐补充（调度方式） | **Demand-Driven and Cyclical Replenishment** | 机制 / 调度 | 按需响应与周期节律并存：现实泪泡出现四相缺失、且存在对应产物供给条件时触发补充；随着宇宙演化时间增长，周期性逐渐增强，但不取代按需响应。四相缺失与产物仍决定交换是否成立、交换什么。 |
| 潮汐交换 | **Tidal Exchange** | 机制 | 潮汐云空间与其他泪泡之间发生的成分交换。 |
| 固化 | **Solidification** | 状态 | 结构的演化能力被锁定；此处不是普通物质由液态变为固态的相变。 |
| 破固化 | **Destabilization** | 机制 | 打破固化结构，使其重新开放演化可能。定义重点是“重新开放演化”，不是单纯破坏或摧毁。 |

### C. 五行路由与四相交互

| 中文 | 正式英文 | 类型 | 定义 / 注记 |
| --- | --- | --- | --- |
| 五行 | **Five Elements** | 路由属性体系 | 木、火、土、金、水；在本模型中用于空间交互路由，不是能量类型。 |
| 五行生克 | **Five-Element Generative and Restrictive Relations** | 关系体系 | 五行相生与相克关系的统称。 |
| 相生关系 | **Generative Relation** | 路由关系 | 生者流向被生者。 |
| 相克关系 | **Restrictive Relation** | 路由关系 | 被克者流向克者。 |
| 五行路由 | **Five-Element Routing** | 路由机制 | 依据五行生克关系确定空间交互方向。 |
| 四相 | **Four Phases** | 交互内容 | 能量、负能量、信息、熵。 |
| 四相流动 | **Four-Phase Flow** | 流动过程 | 四相在空间之间发生的流动。 |
| 四相交互 | **Four-Phase Interaction** | 交互机制 | 空间之间围绕四相发生的交互。 |
| 缺失 | **Deficit** | 状态 / 判定依据 | 用于判断某空间在四相上的缺失情况。 |
| 产物 | **Product** | 结果 / 判定依据 | 用于判断交互中可供交换的具体内容。 |
| 五空间交互 | **Five-Space Interaction** | 空间交互 | 四个泪泡与 Cosmic Core 之间依据五行关系发生的空间交互。 |

**简要规则说明（非算法定义）**

> **Five-Element Routing determines the direction of interaction, while phase deficits and products determine whether an exchange occurs and what is exchanged.**

中文释义：

> 五行生克决定交互方向；四相缺失与产物决定交换是否成立，以及具体交换什么。

本表只保留这一层英文释义。五行路由的完整关系、判定顺序和运行逻辑以引擎规则文档为准，不在术语表中重复展开或另设算法。

### D. 引擎与系统

| 中文 | 正式英文 | 类型 | 定义 / 注记 |
| --- | --- | --- | --- |
| 世界码 | **World Code** | 核心概念 | 用于标识或驱动一个世界状态的代码；同一世界码在相同规则下应能复现对应演化。 |
| 帧 | **Frame** | 引擎术语 | 一个进程步；在当前引擎语境中，Frame 是演化时间轴的基本单位。 |
| 一本账 | **The Ledger** | 系统专名 | 记录系统状态与变化的账本；不替代规则本身，也不承担解释或评价。派生写法：`Ledger Entry`、`Ledger Update`、`Ledger State`。 |
| 键合 | **Bonding** | 物理过程 / 事件 | 代码常量：`BONDING`。 |
| 电离 | **Ionization** | 物理过程 / 事件 | 代码常量：`IONIZATION`。 |
| 解构 | **Decomposition** | 物理过程 / 事件 | 指结构分解。不要写成 `Deconstruction`，后者更容易指向对构造逻辑的批判性拆解。代码常量：`DECOMPOSITION`。 |
| 到岸 | **Arrival** | 状态 / 事件 | 技术文本中的正式名称。若小说中作为纯文学意象使用 `Landfall`，必须明确其文学语境，不得与技术状态混用。 |

### E. 作品与品牌

| 中文 | 正式英文 | 注记 |
| --- | --- | --- |
| 拉面换来的引擎 | **The Engine That Cost a Bowl of Ramen** | 使用 `a bowl`，不用 `one bowl`；不要简写为 `The Ramen Engine`。 |
| 合拍 | **ATTUNE** | 产品名固定全大写；作为普通英语动词时写作 `attune`。不要将其扩展成未经确认的首字母缩写。官方域名为 `attunecut.com`：后缀 `cut` 只是注册可用性的结果，不属于品牌名，**不得写作 `ATTUNE CUT`**，也不要在文案里把域名当作品牌名使用。 |
| 每天happy | **Daily Happy** | 产品名固定为 `Daily Happy`，不使用 `Meitian Happy`、`MeitianHappy` 或全小写形式；域名 `meitianhappy.com` 保持不变。 |
| 分子实验室 | **Molecular Lab** | 网页实验台的名称，固定为 `Molecular Lab`；不要写成 `Molecular Laboratory`、`Lab` 或全大写 `MOLECULAR LAB`（全大写仅可用于版式标签，正文与代码一律用 `Molecular Lab`）。 |
| 余岸观测站 | **The Yu'an Observatory** | 固定拼写。不要写成 `Yu An Observatory` 或 `Yu'an Observation Station`。 |

---

## 三、Tear Bubble 正式定义

### English

> A Tear Bubble is a three-phase celestial structure formed when quantum self-reference drives a four-phase imbalance in the Quantum Sea, expelling the excess phase. Each bubble is enclosed by a dark-energy boundary that separates it from every other bubble.

### 中文对照

> 泪泡是三相天体结构：量子海中信息发生自指，四相失衡，系统排出多余的相，剩下的三相结构成为独立星体；每个泡都由暗能量边界与其他泡隔离。

### 命名依据

- `Tear` 表达量子海发生四相失衡后，多余相被排出的生成意象。
- `Bubble` 表达由暗能量边界隔离出来的独立空间结构。
- 两部分共同构成 `Tear Bubble` 的完整含义。

### 派生写法

| 中文 | 英文 |
| --- | --- |
| 泪泡（单数） | `Tear Bubble` |
| 泪泡（复数） | `Tear Bubbles` |
| 泪泡边界 | `Tear Bubble Boundary` |
| 泪泡内部 | `Tear Bubble Interior` |
| 泪泡之间的交互 | `Inter-Bubble Interaction` |
| 泪泡生成 | `Tear Bubble Formation` |

---

## 四、Cosmic Core 与 Buzhou Rift：功能不同的两个接口

两者相关，但不是同一层级上可以简单互换的输入口与输出口。其间存在潮汐云空间这一中间层。

| 维度 | Cosmic Core（银心 / 土锚） | Buzhou Rift（不周山裂隙） |
| --- | --- | --- |
| 连接方向 | 现实结构向量子海回收 | 量子海向潮汐云空间补充 |
| 核心功能 | Reclamation & Stabilization | Replenishment & Activation |
| 主要作用对象 | 信息自指结构，以及符合回收条件的稳定意识结构 | 经由裂隙进入潮汐云空间的资源与相成分 |
| 状态变化 | 回收、收敛与稳定 | 补充，并为后续演化提供条件 |
| 空间意象 | Core（核心） | Rift（裂隙） |
| 结果描述 | 参与维持现实层的动态稳定 | 为潮汐云空间的调配与补充提供入口 |

**关键区别**

- 回收不等于消灭。
- 补充不等于凭空创造。
- Buzhou Rift 的直接连接对象是 Quantum Sea 与 Tidal Cloud Space；不要写成它直接向其他三个现实泪泡逐一补充。
- 潮汐云空间再依据自身机制参与其他泪泡之间的潮汐补充与交换。

---

## 五、空间结构与关系说明

### 5.1 四个泪泡

四个泪泡分别是：

1. **Energy Bubble**（能量泡）
2. **Matter Bubble**（物质泡）
3. **Civilization Bubble**（文明泡）
4. **Tidal Cloud Space**（潮汐云空间）

其中，Tidal Cloud Space 同时承担中间层调配功能，但它仍然是四个泪泡之一，不应在图示或文字中被重复计算为第五个泪泡。

### 5.2 Cosmic Core

**Cosmic Core** 是参与五行关系的第五个空间，但它不属于四个 Tear Bubbles。它与四个泪泡处于五空间交互关系中。

### 5.3 概念关系示意

```text
                         Quantum Sea
                              │
                              │  Buzhou Rift
                              ▼
                    Tidal Cloud Space
                     （四个泪泡之一）
                              │
                 潮汐调配 / 潮汐补充与交换
                              │
             ┌────────────────┼────────────────┐
             │                │                │
       Energy Bubble     Matter Bubble   Civilization Bubble
             │                │                │
             └────────────────┴────────────────┘
                              │
                    Five-Space Interaction
                              │
                         Cosmic Core
                    （第五个空间，非泪泡）
                              │
                         Reclamation
                              ▼
                         Quantum Sea
```

**示意图说明：** 上图只用于说明主要连接角色，不表示所有空间交互都必须沿图中的上下顺序发生，也不表示 Cosmic Core 只与图中某一个空间发生联系。五空间之间的具体交互方向由 Five-Element Routing 确定；实际交换内容由四相缺失与产物决定。

---

## 六、禁用与易混词

| 不要写 | 应写 | 原因 |
| --- | --- | --- |
| `Droplet`（作为正式术语） | `Tear Bubble` | 丢失独立泡状边界及生成意象。 |
| `Bubble`（单独作为专名） | `Tear Bubble` | 信息不足，无法表达完整概念。 |
| `Galactic Anchor` / `Earth Anchor` | `Cosmic Core` | 前者尺度过窄，后者容易被理解为普通地锚。 |
| `Tidal Space` | `Tidal Cloud Space` | 缺少“云”这一专名组成部分。 |
| `Deconstruction` | `Decomposition` | 语义不同；本模型指结构分解。 |
| `Injection`（作为补充机制正式名称） | `Replenishment` | `Injection` 侧重注入动作，不能完整表达补足状态。 |
| `Book` / `Record`（替代系统专名） | `The Ledger` | `The Ledger` 是固定系统专名。 |
| `Yu An Observatory` | `The Yu'an Observatory` | 专名拼写不一致。 |
| `Yu'an Observation Station` | `The Yu'an Observatory` | 会被理解为普通观测站设施名称。 |
| 将潮汐云空间列为第五个泪泡 | 将其列为四个泪泡之一 | 避免空间层级错误。 |
| 将 Cosmic Core 列为第五个泪泡 | 将其列为五空间中的独立空间 | Cosmic Core 参与五行关系，但不是 Tear Bubble。 |

---

## 七、代码与文件名约定

| 场景 | 写法 |
| --- | --- |
| JSON 字段 / 变量 | `worldCode`、`tearBubble`、`energyBubble`、`matterBubble`、`civilizationBubble`、`tidalCloudSpace`、`cosmicCore`、`buzhouRift` |
| 枚举值 / 常量 | `WORLD_CODE`、`TEAR_BUBBLE`、`ENERGY_BUBBLE`、`MATTER_BUBBLE`、`CIVILIZATION_BUBBLE`、`TIDAL_CLOUD_SPACE`、`COSMIC_CORE`、`BUZHOU_RIFT` |
| 事件类型 | `BONDING`、`IONIZATION`、`DECOMPOSITION`、`ARRIVAL` |
| 机制标识 | `RECLAMATION`、`REPLENISHMENT`、`STABILIZATION`、`ACTIVATION`、`TIDAL_REPLENISHMENT`、`TIDAL_EXCHANGE` |
| 路由 / 交互标识 | `FIVE_ELEMENT_ROUTING`、`GENERATIVE_RELATION`、`RESTRICTIVE_RELATION`、`FOUR_PHASE_FLOW`、`FOUR_PHASE_INTERACTION` |
| 文件名 / URL slug | `world-code`、`tear-bubble`、`tidal-cloud-space`、`cosmic-core`、`buzhou-rift` |
| 仓库名 | `engine-5d`（沿用现有名称） |

代码标识仅用于命名一致性；具体字段结构、事件语义和算法以引擎代码及规则文档为准。

---

## 八、尚未定稿的概念

以下项目不在本版中擅自冻结。写作或开发时应暂时回避过度具体的定义，或明确标注为待确认。

1. ~~**潮汐补充的调度方式**~~ —— **已于 v1.4 确认**：`Demand-Driven and Cyclical Replenishment`（按需与周期并存，周期性随演化时间增强），详见第二节 B 表。
2. **回收的粒度**：整体回归量子海，还是只回收结构与部分状态信息；这会影响意识连续性的解释。
3. **三相 / 四相 / 四相缺一** 的完整术语体系：当前解释文本可使用 `three-phase`、`four-phase`、`four-phase imbalance` 等描述性表达；是否需要为“四相缺一”建立独立专名，尚未确认。
4. **信息自指、意识结构**：解释性表达暂用 `information self-reference`、`consciousness structure`；是否列为正式术语，尚未确认。
5. **到岸的文学用法**：技术文本使用 `Arrival`；小说纯文学语境是否单独采用 `Landfall`，按具体作品需要决定，不得与技术状态混用。
6. **破固化的术语边界**：本版暂用 `Destabilization`，其定义限定为打破固化并重新开放演化能力；若未来需要与一般“失稳”严格区分，再单独评估是否需要专门术语。

---

## 九、变更流程与版本记录

- 本文件是中英文术语映射的唯一依据。新增术语先进入“尚未定稿”区域，确认后再升入正式术语表。
- 修改已冻结术语视为一次全局重命名，需同步检查小说稿、官网、商店页、代码、UI 与技术文档，不得只修改单一位置。
- 引擎已有完整机制定义时，本术语表只保留名称和简要释义；不得在此另造一套与引擎不一致的规则。
- 每次修改应更新版本号、日期和变更说明。

| 版本 | 日期 | 变更 |
| --- | --- | --- |
| v1 | 2026-11-12 | 首版术语冻结：Tear Bubble / Cosmic Core / Buzhou Rift / Tidal Cloud Space 等核心名称确立。 |
| v1.1 | 2026-11-12 | 修正四个泪泡与 Cosmic Core 的层级表达；明确 Buzhou Rift 与 Tidal Cloud Space 的连接关系；统一 Replenishment 用语；补入五行路由与四相交换的简要英文释义；限定 Solidification 与 Destabilization 的语义边界。 |
| v1.2 | 2026-11-12 | 增补产品名：每天happy = `Daily Happy`（与 ATTUNE、The Yu'an Observatory 并列）。其余术语无变更。 |
| v1.3 | 2026-11-12 | 增补产品名：分子实验室 = `Molecular Lab`。四个产品名至此齐备。 |
| v1.4 | 2026-11-12 | 确认潮汐补充的调度方式为 `Demand-Driven and Cyclical Replenishment`：按需响应与周期节律并存，周期性随宇宙演化时间增长而增强，但不取代按需响应。并从“尚未定稿”移入正式术语表。 |
| v1.5 | 2026-11-12 | 补注 ATTUNE 的官方域名为 `attunecut.com`，明确 `cut` 不属于品牌名。 |
