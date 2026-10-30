# 科研写作基本功

Date: 2026-10-30
范围：以生物医学为主的可迁移写作指导。本文综合已核查的经典论文、作者课程文字、大学教学资料及报告规范；**是可选择的工作方法，不是固定文风或万能文章模板**。来源版本、实际读取范围和课程缺口见[来源索引](foundations-sources.md)。

## F0 使用与原则层级

按问题只读相关部分：选体裁读 **F1**；明确章节任务读 **F2**；组织段落读 **F3**；精修语言读 **F4**；积累引用读 **F5**；评估修改读 **F6**。可用 `rg -n '^##|^###'` 定位标题后读取片段。

先区分三层：**科学事实与证据**决定能说什么；**研究设计和期刊要求**决定应报告什么；**写作方法**帮助决定如何让读者理解。EQUATOR 明确将报告指南与研究设计标准、质量评价工具区分开，也不要求按清单顺序组织文章。[R02 EQUATOR](https://equator-network.org/about/reporting-guidelines.html)

本轮选源重视出处可靠、互补性与可读到的内容，不声称存在客观的“最佳课程”排名。专家指导、教学经验和正式报告规范的证据性质不同。下面的段落模式和诊断动作是结合来源作出的工作化提炼，不是原作者规定的英文模板。

## F1 先判断贡献类型，再判断研究设计

**贡献类型决定叙述重心，研究设计决定证据责任。** “临床论文”不能单独决定写法，因为临床研究可以是试验、观察研究或预测模型研究；方法或资源论文也可能包含实验。这是本指南对下列要求的综合。

### F1.1 文章主要交付什么

| 类型 | 读者需要理解的贡献 | 写作重心与容易混淆之处 |
| --- | --- | --- |
| 原创实证研究 | 关于一个明确问题的新证据 | 问题与比较、设计、观察结果及可支持的解释。发现顺序不必等于实验发生顺序；证据矛盾必须保留。 |
| 方法 / 算法 / 软件 | 在给定用途下可工作的技术方法 | 障碍、设计选择、适当验证、比较条件和可复现使用；区分已验证能力与可能用途。 |
| 数据库 / 数据集 / 资源 | 可以被可靠获取和使用的信息资源 | 收录与组织对象、来源/处理、质量和覆盖边界、访问及实际用途；更新文章说明变化。案例证明具体用途，不自动证明普遍性能或机制。 |
| 系统综述 / meta-analysis | 对明确问题的可追溯证据综合 | 检索、纳排、偏倚、合成及确定性；meta-analysis 是可能的合成方式，不能与所有系统综述等同。 |
| 叙述性 / 概念性综述 | 对知识、争议、解释或研究方向的综合判断 | 交代范围与选材，按问题或概念比较研究；不是逐篇摘要，也不能无依据声称检索全面。 |
| 病例报告 | 一个临床过程带来的有限但有意义的认识 | 病程、诊断推理、处理与随访，说明可学习之处及局限；单例不能承担总体疗效结论。 |

原创论文的章节功能参照 [R01 ICMJE](https://www.icmje.org/recommendations/browse/manuscript-preparation/preparing-for-submission.html)；方法/工具/数据库的用途与验证参照 [R08 PLOS One](https://journals.plos.org/plosone/s/submission-guidelines#loc-methods-software-databases-and-tools)。综述与病例另按下表路由。上述分类用于选择写作任务，允许一篇论文兼有多种贡献。

期刊特例单独处理：NAR Database Issue 强调数据库内容、检索与可用性，明确其定位不同于发表新的实验或计算结果；这不是禁止所有资源文章呈现验证、覆盖分析或用例的通则。[R09 NAR](https://academic.oup.com/nar/pages/Ms_Prep_Database)

### F1.2 该设计还需要交代什么

| 设计 / 任务 | 按需调用 | 写作时优先检查的信息 |
| --- | --- | --- |
| 随机试验 | [R03 CONSORT 2025](https://journals.plos.org/plosmedicine/article?id=10.1371/journal.pmed.1004587) | 分配、预设结局、参与者流程、分析人群、效应及不确定性、获益与伤害；适用时另查扩展指南 |
| 队列、病例对照、横断面流行病学 | [R04 STROBE](https://www.strobe-statement.org/) | 选人、暴露/结局、混杂、缺失、估计精度与偏倚；并非所有“观察性”工作都直接落入此范围 |
| 系统综述 | [R05 PRISMA 2020](https://www.prisma-statement.org/prisma-2020) | 检索日期/策略、筛选、偏倚与合成来源，区分证据本身的局限与综述过程的局限；按题型查扩展 |
| 临床预测模型开发或评估 | [R07 TRIPOD+AI](https://www.bmj.com/content/385/bmj-2023-078378) | 明确模型用途和数据角色、开发与评估过程及适用人群；该指导不限于机器学习，也不等于所有算法论文的通则 |
| 临床病例 | [R06 CARE](https://www.care-statement.org/checklist) | 时间线、诊断选择、干预、随访、患者观点与知情同意等适用事项 |
| 其他实验 / 特殊设计 | [R02 EQUATOR](https://equator-network.org/about/reporting-guidelines.html)及目标期刊 | 按实际对象和设计定位相应指南；本页不替代完整清单 |

这些是报告要求的导航，不是方法学质量合格证，也不是逐段写作顺序。正式应用时检查现行版本及目标期刊要求。

## F2 章节承担的任务

先给目标章节写一句“读者读完应理解什么”，再分配段落。IMRAD 有助组织原始研究，但体裁和期刊可采用其他结构；章节标题与功能不能混为一谈。[W08 Gastel–Day，已读样章](https://assets.cambridge.org/97813166/40432/excerpt/9781316640432_excerpt.pdf)

| 部分 | 读者任务 | 内容选择与边界 |
| --- | --- | --- |
| 标题 | 快速判断对象、问题或贡献 | 让核心贡献可辨认；描述性或结论性标题取决于证据与体裁，不能夸大因果或普遍性。 |
| 摘要 | 不读全文也能把握研究做了什么及得到什么 | 覆盖目的、必要的设计/材料、关键发现与有界结论；原始研究、资源介绍及综述的重点不同，结构式小标题按期刊要求。 |
| Introduction | 理解为什么这个具体问题值得研究 | 从目标读者需要的背景进入，连接已有证据、尚未解决的具体问题与本研究目标；不要为了“填空白”而贬低既有工作或虚构空白。 |
| Methods | 判断工作怎样完成、能否复核 | 对象/材料、选择与处理、测量及分析，必要时解释关键选择；描述实际发生的过程，清楚区分预设和探索。 |
| Results | 理解观察到了什么及其直接含义 | 按证据关系组织，保留必要动机和局部解释；不要抄写图表每个数字，也不要把扩展推测写成结果。 |
| Discussion | 理解发现改变了什么认识、哪里仍不确定 | 回答问题，与文献比较，讨论可能解释、适用范围及限制，再给出与这些限制相关的下一步。 |
| Conclusion（如设置） | 带走与研究目标对应的主要回答 | 收束已获支持的认识及意义；是否单独成节依体裁，不以重复全部结果或增加新主张收尾。 |
| 图注 / 表注 | 看懂实际展示的证据 | 解释对象、分组、单位、符号及适用的统计信息，使读者能准确解读；制作细节与方法分工，按期刊格式处理。 |

具体内容选择分别参照 [W02 Mensh–Kording](https://doi.org/10.1371/journal.pcbi.1005619)、[W05 MIT Introduction](https://mitcommlab.mit.edu/be/commkit/journal-article-introduction/)、[MIT Results](https://mitcommlab.mit.edu/be/commkit/journal-article-results/)、[MIT Discussion](https://mitcommlab.mit.edu/be/commkit/journal-article-discussion/)及 [R01 ICMJE](https://www.icmje.org/recommendations/browse/manuscript-preparation/preparing-for-submission.html)。表格是这些材料的操作化综合，不规定段数或固定句式。

**两个容易误用的层次：**引言内的文献回顾服务于当前研究问题；独立综述则必须完成它自己的综合任务。Results 可以解释分析动机与数据的直接含义，而更广的机制解释或外推通常放在 Discussion；遇到合并 Results and Discussion 的期刊格式再调整分工。[L08 老刘的引言内综述讲解](https://blog.wenxuecity.com/myblog/74915/201908/25817.html)、[W09 Pautasso](https://doi.org/10.1371/journal.pcbi.1003149)、[MIT Results](https://mitcommlab.mit.edu/be/commkit/journal-article-results/)

## F3 段落功能与可调整模式

这里的箭头表示信息关系，不表示必须各写一句。某一步已由邻段承担时可省；一段不能承载清楚时可拆。下面均为本指南的综合示意，方括号为真实材料待填位置。

### P1 背景 → 具体问题

**适用：**引言，需要说明为何研究一个问题。

`读者需要知道的现状 → 已有解释/做法及其证据 → 尚不能回答的具体问题 → 本研究目标`

自拟句架：`[Prior work] establishes [known point]. However, [specific question] remains unresolved under [conditions]. We therefore examined [objective].`

“现状”和“未解决”都需要来源与时间范围。也可从问题直接开篇后补背景，不要求每篇都从宏大重要性开始。老刘强调读者连接和目标合理性，MIT 强调反推必要背景；两者共同支持按目标读者控制起点。[L-INTRO](https://blog.wenxuecity.com/myblog/74915/201904/8225.html)、[W05 MIT Introduction](https://mitcommlab.mit.edu/be/commkit/journal-article-introduction/)

### P2 处理 / 方法选择

**适用：**Methods，或理解结果所必需的方法概述。

`对象与具体处理需求 → 实际操作及选择理由 → 决定结果解释的参数/范围 → 输出或评价方式`

自拟句架：`To [specific purpose], we applied [procedure] to [defined inputs], using [relevant settings].`

目的必须与实际处理相符；读者已明白时不必每段再写目的句。成熟方法可引用，新方法或实质变化需解释。操作多时按处理逻辑展开，不强求每段都有“结论”。[R01 ICMJE Methods](https://www.icmje.org/recommendations/browse/manuscript-preparation/preparing-for-submission.html)

### P3 结果 / 比较

**适用：**原创研究 Results；技术论文的验证结果。

`本次比较回答什么 → 条件和必要数据 → 数据支持的局部回答 → 后续问题（需要时）`

自拟句架：`We compared [A] and [B] under [matched conditions]. [Measured difference and uncertainty]. This finding supports [bounded conclusion].`

并非每段都需要最后一句。先核对比较是否成立，再决定如何突出差异；与主张有关的矛盾结果不能因叙事流畅被省略。[W05 MIT Results](https://mitcommlab.mit.edu/be/commkit/journal-article-results/)

### P4 解释 / 与文献对照

**适用：**Discussion 中讨论一项发现。

`发现的含义 → 与已有证据的相同/不同 → 条件差异或可能解释 → 限制及可检验的下一步`

自拟句架：`This observation is consistent with [prior evidence]. One possible explanation is [hypothesis]; however, [limitation] prevents us from distinguishing it from [alternative].`

只有确有替代解释或鉴别限制时使用对应部分；可能机制仍是可能机制。讨论可以围绕多项发现重复这个思考过程。[W05 MIT Discussion](https://mitcommlab.mit.edu/be/commkit/journal-article-discussion/)、[W06 Phrasebank](https://www.phrasebank.manchester.ac.uk/discussing-findings/)

### P5 资源 / 工具用途

**适用：**数据库、数据集、软件功能或用例。

`用户任务或信息困难 → 实际提供的对象/功能 → 能核实的范围或示例 → 使用边界`

自拟句架：`The resource links [defined objects] through [documented relation], enabling users to [demonstrated task].`

此处 `enabling` 需要真实功能支持。覆盖数用于交代规模，用例用于说明可完成的任务；两者不能自动证明性能最优或临床有效。[R08 PLOS One](https://journals.plos.org/plosone/s/submission-guidelines#loc-methods-software-databases-and-tools)

### P6 文献综合

**适用：**综述主体、引言中的证据归纳、Discussion 的比较。

`一个综合问题 → 同一维度下对照研究 → 共识/差异及其条件 → 有界判断或尚缺证据`

自拟句架：`Studies agree on [shared finding] but differ in [outcome or interpretation], partly because [documented differences]. Evidence for [remaining claim] is still limited to [scope].`

不要无证据归因研究差异，也不要只挑支持预设故事的文献。系统综述的选材与合成必须服从其明确方法。[W09 Pautasso](https://doi.org/10.1371/journal.pcbi.1003149)、[R05 PRISMA](https://www.prisma-statement.org/prisma-2020)

## F4 句子与段落如何变得清楚

1. **沿读者已有认识引入新信息。** 检查句首是否接得上前文，句子的强调位置是否承载想让读者记住的信息。若跳跃来自缺少科学关系，先补足有依据的关系，再调整语序。[W01 Gopen–Swan](https://courses.ems.psu.edu/styleforstudents/print/c10_p6.html)
2. **让主语、动作及对象容易辨认。** 过长插入语可后移或拆开，空泛名词化可改成具体动词；必要的限定不能顺手删掉。[W04 Sainani Lecture 1](https://www.stanford.edu/~kcobb/writing/lecture1.ppt)、[Lecture 3](https://www.stanford.edu/~kcobb/writing/lecture3.ppt)
3. **语态服务焦点。** 需要说明执行者时主动表达往往更清楚；需要延续对象焦点时被动表达可能更好。不要自动把所有被动句改成 `We...`。[W03 Swales–Feak 样章](https://press.umich.edu/pdf/9780472034758-unit1.pdf)
4. **连贯先靠关系，再靠连接词。** 稳定的对象、合理顺序与关键词承接共同作用。`however` 应有真实转折，`therefore` 应有推理依据；反复添加它们不能补足逻辑。[L-COH 老刘](https://blog.wenxuecity.com/myblog/74915/201901/28371.html)
5. **比较使用可比较的语法与内容。** 相同维度可采用平行结构；术语重复可以帮助读者确认谈的是同一对象，不要为词汇多样性制造概念漂移。[W02 Mensh–Kording](https://doi.org/10.1371/journal.pcbi.1005619)
6. **简洁以保存意思为前提。** 删除重复、空话和不必要的铺垫；解释、条件和定义可能值得增加。清楚不等于全部短句，优先修复读者容易误解的位置。[L-CLEAR 老刘](https://blog.wenxuecity.com/myblog/74915/201901/28351.html)、[W01 Gopen–Swan](https://courses.ems.psu.edu/styleforstudents/print/c10_p6.html)
7. **措辞准确表达主张类型。** 区分观察、估计、解释和预测；对具体不确定性作限定，不把所有句子机械加 `may`。语料库提供表达选项，不能替作者证明一个命题。[W06 Cautious language](https://www.phrasebank.manchester.ac.uk/using-cautious-language/)、[W07 EASE 历史指南](https://pmc.ncbi.nlm.nih.gov/articles/PMC4130677/)

一个自拟的诊断例子：`This improved the results.` 若 `This` 和 `results` 指代不明，首先找出真实操作、评价指标和比较对象；这些信息未知时先回查依据。不能直接把它润色成“显著提高准确率”。

## F5 阅读、论据积累与引用

老刘将阅读区分为探索并细化问题、围绕目标提取证据两个阶段；Pautasso 同样强调阅读时记录而非等读完再写。对 agent 的实现是：先确定缺什么材料，再定向读取、保存可用片段，并根据新证据调整问题；不把最初构想当成只能被支持的结论。[L06](https://blog.wenxuecity.com/myblog/74915/201908/14138.html)、[W09 Pautasso](https://doi.org/10.1371/journal.pcbi.1003149)

每遇到有用材料，留下一条最小可用记录：**出处与原文位置—原句或准确指针—可转述论点—对象/时间/条件—拟用段落**。表达技巧与科学论据可以来自同一片段，但分别判断其用途；这与老刘强调来源可追回、按论点整理文献的做法相通。[L07](https://blog.wenxuecity.com/myblog/74915/201908/20265.html) 文件规则见[工作记忆与论据](memory-and-evidence.md)。

原文、转述和自己的推断分开。引用前检查来源实际支持该句的范围，并验证书目信息；转述观点仍保留归属。首稿暂不编引用编号时，在项目素材中保留句子与来源的对应，之后随句子变化更新。[R01 ICMJE References](https://www.icmje.org/recommendations/browse/manuscript-preparation/preparing-for-submission.html)

## F6 取舍、修改与学习反馈

### F6.1 不同指导如何共同使用

| 看似冲突的建议 | 可执行的判断 |
| --- | --- |
| “段首先给主题句”与“先建立 context” | 老刘给初学者直接定位段意的办法，Mensh–Kording 强调背景、内容和收束的关系；读者已具备背景可直接给主张，否则先建立必要前提。按读者任务选择，不规定同一开头。 |
| “尽量简短”与“完整交代证据” | 删除不承担功能的文字，保留复核、理解和避免误读所需的信息。篇幅限制通过组织与主文/补充分工处理，不靠遗漏关键证据。 |
| “讲好一个故事”与“如实报告” | 用线索帮助理解证据；不能为整齐的故事删掉反证或虚构因果。资源、综述与病例可以有不同的组织逻辑。 |
| “被引次数更多，就说明文章写得更有效” | 被引次数、读者理解、可复核性和投稿接受不是同一目标。Weinberger 等研究的是写作特征与被引次数的关联，不能据此得到因果性改稿指令。 |

前两行综合 [L-CLEAR](https://blog.wenxuecity.com/myblog/74915/201901/28351.html)、[W01](https://courses.ems.psu.edu/styleforstudents/print/c10_p6.html)、[W02](https://doi.org/10.1371/journal.pcbi.1005619)与 [W07](https://pmc.ncbi.nlm.nih.gov/articles/PMC4130677/)；后两行参照 [MIT Results](https://mitcommlab.mit.edu/be/commkit/journal-article-results/)及 [W10 Weinberger et al.](https://doi.org/10.1371/journal.pcbi.1004205)。这些综合判断属于本指南，不冒充来源原话。

### F6.2 一次修改怎样知道有没有进步

先反向概括现有段落每句的作用，再选择需要解决的问题；只有结构确实有问题时才重组，否则做必要的局部修改。[W04 Sainani Lecture 4](https://www.stanford.edu/~kcobb/writing/lecture4.ppt)

比较时问：中心意思是否更容易理解？来源和推理是否能追溯？对象、数值、否定和限定是否保持？相邻句是否更连贯？作者要保留的语气或解释有没有被误删？这些是本指南的检查问题，不是一个必须逐项输出的评分表。

将有用反馈写入该论文工作区，记录具体例子、为什么接受/拒绝和作用范围。更短、词更复杂、更接近某篇范文都不是独立成功标准；某次有效的办法先保留局部条件，再决定是否跨文章复用。
