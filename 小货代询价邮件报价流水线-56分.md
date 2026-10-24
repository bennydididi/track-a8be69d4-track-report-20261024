这个产品帮助小型国际货代的报价员，在客户通过邮件询问海空运价格的场景下，解决反复录入、查费率和核对费用后才能发出报价的问题。

# 小货代询价邮件报价流水线

研究日：2026-10-24。**建议：保留需求，先做付费试点；当前不建议直接立项，也不优先靠 SEO 铺站。**

## 一分钟判断

### 钉死的研究对象

| 项目 | 本次固定口径 |
|---|---|
| 谁使用／谁付钱 | 发达市场的小型国际海空运货代报价员使用，公司负责人付费；货代是帮客户安排运输的中间商 |
| 输入 | 客户询价邮件和附件＋客户有权提供的有效买价表／代理回价＋公司加价规则及报价条款 |
| 输出 | 人工确认后可发给客户的报价草稿：费用明细、来源、有效期、包含／排除项；信息不足则生成补问草稿，并保留记录 |
| **只判一个任务** | **把一封询价处理成可审核的客户报价，减少重复录入和核对时间** |
| 最小试点 | 单港口对、整柜普货、自有有效 Excel 费率；先生成邮件正文报价，由报价员确认发送 |
| 远程成交边界 | 卖报价软件订阅；通过在线演示和文件导入交付。运输、订舱、报关由客户自己安排 |

这是研究定位，尚未做客户访谈或产品实测。流程可与[Freitt 的公开说明](https://freitt.com/how-it-works)对照。

### 首屏三维决策

| 维度 | 判断 | 最关键依据／限制 |
|---|---|---|
| **有没有相关需求** | **有相关需求；样本有限，推广污染已降权** | 从业者明确描述邮件、查费率、审批、报价的连续流程；也有人认为可靠承诺比抢快更有用。半年全量未取得。[用户原声](https://www.reddit.com/r/freightforwarding/comments/1wcl4n3/how_long_does_an_ocean_quote_actually_take_your/) |
| **当前切口能否独立收费** | **待验证；同任务公开标价已找到，独立付费/续费 PMF 未找到** | Freitt 提供“邮件＋自有费率→审核草稿”，Starter **$55／用户／月**；真实付费客户数、续费率未找到。标价、套件评价不能直接证明该切口已达到产品市场匹配（PMF）。[价格](https://freitt.com/pricing) |
| **是否优先靠 SEO** | **暂不优先；未取得主任务可靠正搜索量，非英语指定国家 Google 前十未完成** | 正数全部来自相邻运价管理词；原标零值存在缺失值转零风险。年轻域名不能弥补搜索量和买家未知。[供应商](https://api.pxany.com/v1/keyword-volumes)、[核心词复查](https://www.google.com/search?q=freight+email+quote+workflow&gl=us&hl=en&num=10)；审计见附件 |

**会改变决定的未知：**匹配公司的负责人，是否会为这个独立流程付款并续费；自然搜索能否带来这类公司，而非寻找运输报价的货主。下一步做真实样本付费试点，同时只留少量产品页观察搜索获客。首付、复用、续费分开验，具体停止条件见下文。

## 判断依据

### 需求存在，但等待海外代理的时间不能全算成软件可节省工时

原帖中的具体步骤对得上本次任务；部分引语和买家身份需要纠正。下表的日期、票数是网页／搜索缓存快照，不是实时数据；“未找到”不补猜。

| 用户、日期／帖级票数 | 原话与抱怨步骤 | 现用工具、付费及证明边界 |
|---|---|---|
| 海运报价从业者；**2026-09-10／+1** | “the booking tends to go to whoever answered first”；等代理及毛利审批拖长邮件到报价时间。评论又说可靠交付时间比纯速度更重要。[原帖](https://www.reddit.com/r/freightforwarding/comments/1wcl4n3/how_long_does_an_ocean_quote_actually_take_your/) | 有人用运价管理软件，但费率必须及时更新。支持审核流程和时效检查；不能证明软件消除时差等待，也未提付多少钱。原页本次直开失败，以检索缓存核对 |
| 发帖人寻求货代自动化；精确日期／票数**未找到** | “from the stage of receiving emails to quoting to the customer”；想保留公司记录，不想逐条喂给聊天工具。[原帖](https://www.reddit.com/r/freightforwarding/comments/1qf9l67/automating_my_pricing_flow/) | 提到 n8n、Make；评论者自称做物流自动化，主帖作者随后愿介绍供应商，存在导流可能。支持流程需求，不能算独立购买证明 |
| 小型远程物流公司员工，评论确认主要国际海空运；**2024-03-20／+2**，旧样本 | “would prefer a free option/DIY solution”；说公司日收 **30–40 次**询价，用 Excel 和 Outlook 签名模板，并愿为合适工具付少量月费。[原帖](https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/) | 已有 CargoWise，但认为生成报价费事；明确拒绝附件，要求邮件正文。证明具体工作流与预算约束，不能把该公司频次当行业均值；付费交易未找到 |
| 新入行货代；精确日期／票数本次**未找到** | “never ending loop of emails and copy pasting”；询价、等伙伴回复、比较再发客户不断重复。[原帖](https://www.reddit.com/r/freightforwarding/comments/1smuiw6/half_my_day_is_just_quoting_and_im_starting_to/) | 评论含产品推广。旧档案记为 **2026-04-16／+7**，本次未重新取得绝对日期，不按近半年新增样本使用 |
| 货代从业者；**2026-04-20／+7**，半年窗口外 | 查多个承运人表格里的航线与附加费耗时；“It consumes all our time.”[原帖](https://www.reddit.com/r/freightforwarding/comments/1sr1ovp/carrier_forwarder_rates_hassle/) | 评论有免费早期产品招募及自动化服务推广。支持查表负担，不能证明免费方案已令用户满意或有人购买 |
| 自称资深货代、同时考虑开发产品；**2026-05-14／+2** | “Excel + eyeball + hope?”；担心把承运人总价直接抄给客户，漏掉适用费用。评论强调列清条件和报价有效期。[原帖](https://www.reddit.com/r/freightforwarding/comments/1td9lrf/how_do_you_verify_carrier_quotes_dont_have_hidden/) | 只是费用核对步骤的支持证据，带开发者调研动机；不把其损失金额当行业数据，也不单独提升付费分 |

**原需求日报的三处修正：**“花人力省一点运费”的帖子是[货主采购侧](https://www.reddit.com/r/freightforwarding/comments/1q0irvk/how_much_time_does_your_team_spend_on_quote/)，不证明货代买软件；“20 min to a couple hours”和历史价那句在[小 3PL 调研帖](https://www.reddit.com/r/supplychain/comments/1smans8/how_are_smaller_3pl_teams_handling_quoting/)可读正文中未找到，且正文提 DAT／Truckstop，偏公路经纪；[数据分散帖](https://www.reddit.com/r/logistics/comments/1szz5vp/how_do_freight_forwarders_actually_manage_rates/)正文已删除、评论有近似表述和推广，只作低权重补充。

### 同任务已有收费供给；独立付费与续费证据仍不够

**竞品存在是需求验证线索。**当前障碍是尚未核到本切口的小客户持续付款，不能用整个物流软件市场的收入补齐。

| 对标／重合程度 | 已核到的功能与公开价格（美元） | 能证明什么，不能证明什么 |
|---|---|---|
| **Freitt：最贴近本次任务** | 转发询价、上传 Excel 买价、补问草稿、费用来源追溯、过期价拦截、人工确认；Starter **$55**、Growth **$89／用户／月**。原生 Gmail／Outlook 连接仍列待推出。[流程](https://freitt.com/how-it-works)、[价格](https://freitt.com/pricing) | 同任务作为产品公开销售。真实付费客户数、收入、续费率、独立差评**未找到**；页面演示不作客户数据 |
| **Wisor：同流程模块，套件更广** | 官网覆盖邮件抽取、费率匹配、报价和异常审核；具体价格**未找到**，需演示。[邮件产品](https://wisor.ai/solution/freight-email-automation/) | [具名案例](https://wisor.ai/case-studies/)及[G2 用户评价](https://www.g2.com/products/wisor-ai-wisor-ai/reviews)支持实际使用；小公司为“仅邮件到报价”独立支付多少、付费客户数、模块续费率**未找到** |
| **Quotiss：更宽的商用套件** | 询价整理、费率、报价、客户管理和分析；**$125／用户／月，至少 2 人**，不能按单席价格比较最低公司账单。[官网](https://quotiss.com/)、[定价](https://quotiss.com/pricing/) | 提供上位替代方案和商业报价；其套件价格不计作本切口独立付费证明 |
| **Lead Quote Track：部分重合** | 邮件发起询价、读取代理回价、比较再形成报价。官网 FAQ 写单用户月付发布价 **$35**，有效至 **2026-12-31**；标准月价 **$49**，页面也有年付折算显示，不能混用。[官网／FAQ](https://www.leadquotetrack.com/) | 支持轻量工具供给；仍有代理比价等不同任务。付费数量、收入、续费**未找到**，不借这些相邻功能给本切口加分 |

经营核验：Wisor 的投资方确认其 **$8m 种子轮**，这是融资，不是收入或当前累计融资。[Team8](https://team8.vc/wisor-ai-digitally-rewiring-the-freight-industry/) 其余上述直接／部分重合产品的可核融资、模块营收与利润**未找到**。竞品自然访问量及搜索渠道占比**未找到**，[Freitt](https://www.similarweb.com/website/freitt.com/)与[Wisor](https://www.similarweb.com/website/wisor.ai/)的 Similarweb 页面本次不可读，不能断言它们靠 SEO 成交。

### 可以做窄方案，但“有追溯＋人工审核”已经不是独有卖点

[Freitt](https://freitt.com/how-it-works)已明确展示费用追溯、有效期、人工审核，因此旧报告提出的这些功能不能再写成未被满足的缺口。真正待验证的是：**目标公司的实际邮件／费率格式，现有产品是否处理不好，而且客户愿意为处理好它单独付钱。**

[Wisor 的 G2 评价](https://www.g2.com/products/wisor-ai-wisor-ai/reviews)中，**2025-04-22**有用户称复杂费率更新可能等数日；**2026-02-25**有用户肯定 Outlook 提取及报价省时。前者给出导入与自助修订的测试方向，后者证明已有产品有用；都不能证明现在仍存在同样缺陷。旧报告关于 **2025-08-27**“承诺功能交付慢、上传出错”的具体说法，本次在可读页面中**未找到**，不沿用。

Freitt 的[计算器说明](https://freitt.com/tools/freight-quote-roi-calculator)明确说尚无可预填的已测客户省时数字；这支持谨慎使用效果证据，不能推出它没有付费客户。

**可试的缝隙（假设，尚未成立）：**用一个客户反复出现的代理回价格式，做到费用逐项映射、未知项显式留空、客户自己的报价正文直接可用。用同一批真实样本与 Freitt 对比；若现有工具已满足，当前方案没有必要重做。

AI 适合抽取杂乱邮件、识别缺字段、生成补问与解释；算费、汇率、有效期和加价规则用确定性计算，发送由人确认。通用聊天工具无法自然替代持续收件、版本记录与审批，但如果每次都要人工重做，产品价值就不成立。[从业者关于人工复核的讨论](https://www.reddit.com/r/freightforwarding/comments/1qf9l67/automating_my_pricing_flow/)

### SEO：有对口页面可竞争，尚未证明有足够的搜索买家

**关键词与实际搜索结果要分开看。**主任务候选词存在，但网页结果混入货主找运费、承运人服务、公路报价和通用解析；不能把行业同词当作同一个软件需求。[软件意图示例](https://wisor.ai/solution/freight-email-automation/)、[公路履约示例](https://haulier.ai/blog/freight-quote-automation)

| 同一任务下的表达 | 已提供国家结果中的代表页面／意图 | 对判断的影响 |
|---|---|---|
| `freight forwarder quoting software` | US：Quotiss、Quotable、Freightify；UK／AU 也出现专业软件。CA 混入货主找价平台。[Quotiss](https://quotiss.com/)、[Quotable 行业页](https://getquotable.ai/industries/freight-forwarders) | 软件意图存在；排名页可能承诺完整商用系统，不能只用解析表单承接 |
| `freight email quote workflow` | US 包含 Wisor 与通用工作流；UK／CA／AU 有 FRAI。[Wisor](https://wisor.ai/solution/freight-email-automation/)、[FRAI](https://www.frai.global/blog/email-to-quote-automation-freight-forwarders) | 与本任务更接近，但未取得可靠正月搜；不能从排名推出成交量 |
| `freight RFQ email automation` | US／UK／AU 见 FRAI、Zavin；CA 的结果更杂。[FRAI](https://www.frai.global/)、[Zavin](https://zavin.ai/platform/email-automation) | 既有专业供给，也有较年轻站点；独立客户、自然流量和新站获客成本未找到 |
| `email to quote for freight forwarders` | 软件与货代运输服务混杂。[直接软件](https://wisor.ai/solution/freight-email-automation/) | 产品页必须明说“使用你自己的费率生成草稿”；不承诺向货主提供运输报价 |

**影响结论的数据限制：**已提供的地区 SERP 一共 **88 份**，均不足前十：**86 份为 9 条、2 份为 8 条**。其中 AU 的 `freight quote generation from rate sheets` 返回政府利率／统计等离题页面，整份排除竞争判断；按本任务保留的有效地区样本仅为 **US／UK／CA 各 11 份，AU 10 份**。以上为附件原始 `serp.json` 复算，[供应商 SERP 接口](https://api.pxany.com/v1/serp?q=freight+email+quote+workflow&gl=us&hl=en&num=10)可作复查入口，搜索结果会变化。

**域名年龄只留观察：**原数据记录 FRAI 注册于 **2025-10-30**、Zavin 于 **2026-07-08**，两者公开页确实覆盖邮件到报价；本次 RDAP 重查不可读，只沿用供应商档案，不能视为已独立复核。[FRAI 页面](https://www.frai.global/blog/email-to-quote-automation-freight-forwarders)、[Zavin 页面](https://zavin.ai/platform/email-automation)、[FRAI RDAP](https://rdap.org/domain/frai.global)、[Zavin RDAP](https://rdap.org/domain/zavin.ai) 另一个原入榜站 Aeralis 官网已公告 **2026-10-02 关闭**，原产品是通用 Gmail 草稿插件；Haulier 是英国集装箱公路运输服务，两者均不贡献本任务的竞争评分。[关闭公告](https://aeralis.ai/blog/ai-email-freight-broker-quotes)、[Haulier 自述](https://haulier.ai/blog/freight-quote-automation)

因此，“有年轻域名出现”只能说明值得继续查。**当前没有可靠依据给这个切口承诺 SEO 优先级。**也不能反向断言搜索需求为零：供应商零值口径有疑问，日本等市场大量词未返回，非英语国家前十尚缺。

### 最小验证与停止条件

以下全部是**本研究设定的实验参数，不是行业均值、已发生交易或营收预测**；报价参考[同任务现有标价](https://freitt.com/pricing)，验证对象为前述单一流程。

| 阶段 | 动作及通过线 | 停止／收缩条件 |
|---|---|---|
| 样本与可交付性 | 两周接触 **15 家**匹配公司，取得 **3 家**授权数据，各回放 **30 条**历史询价；同时与现用流程及 Freitt 比较。净人工处理时间中位数降低 **50%**，测试集中的过期价／缺费陷阱全部被拦截 | 取不到授权样本，或客户主要卡在等待代理而非整理核对，就停止当前输入范围；现有工具同样满足且无可付费增量，也停止当前方案 |
| **首付** | 独立软件试点价 **$149／公司／月，最多 3 人**，至少 **2 家真实付款**；接入劳务若收费另列，不能当软件首付 | 认可、免费试用、订金意向均不算；无人为该流程单独付款，停止开发完整产品 |
| **复用** | 首月每家在至少 **3 个不同工作周**使用，各处理至少 **20 条真实询价**；扣除查错／补录后仍省时 | 只演示时用、靠研究者代操作或查错抵消收益，收缩格式支持或停止；套餐内再用不算第二次付款 |
| **续费** | 到第二个计费周期，试点公司至少 **2 家主动续费且继续使用**；记录拒绝续费原因 | 首月内不能宣布已续费；若只肯按次买，需另测按次价格与第二单再付，不能拿复用代替 |
| SEO 渠道单独验证 | 仅做工作流、费率导入样例和定价演示页；记录非品牌自然搜索→匹配公司演示→首付。**90 天**目标为 **3 个合格自然搜索线索、1 个可归因首付** | 无合格线索则维持 SEO 非优先，不扩大内容；有收录无买家不算通过。该停止线是预算规则，不证明整个赛道无搜索需求 |

**价值／维护敏感性（假设→推算）：**若月处理 **100 次**、每次净省 **6 分钟**、人工价值 **$30／小时**，时间价值约 **$300／月**；只有 **20 次**则约 **$60／月**，不足覆盖试点月费。再假设基础直接成本 **$25／公司／月**，另需 **2 小时**维护、同按 **$30／小时**计，则月贡献约 **$64＝149−25−60**，尚未扣销售和开发。价格、工时、成本均待实单验证，不能把模型当利润证明；可用[竞品计算器](https://freitt.com/tools/freight-quote-roi-calculator)核对参数思路，勿照抄其示例为行业数据。

## 附录：评分、审计与词表

### 五项复核与综合评分

按指定筛选标准，每项 **1–5 分**，等权；原日报维度与新标准不同，不能机械照搬。下列分数均为研究判断，证据入口随行列出。

| 新标准 | 专员原分 | 核实后分 | 关键依据 |
|---|---|---:|---|
| ①需求真实 | 4 | **4** | 连续流程原声成立，样本与推广问题降权。[原帖](https://www.reddit.com/r/freightforwarding/comments/1wcl4n3/how_long_does_an_ocean_quote_actually_take_your/) |
| ②付费意愿／当前切口 PMF | 3 | **2** | 同任务标价成立；独立付费客户和续费未找到，未过 PMF 证据门槛。这是证据不足，不是断言无人付费。[Freitt](https://freitt.com/pricing) |
| ③好服务 | **未给**；原③是“AI 友好4” | **2** | 用户是专业报价员，错误价格伤害客户关系，不能因 B 端就认定容易服务。[用户讨论](https://www.reddit.com/r/freightforwarding/comments/1qf9l67/automating_my_pricing_flow/) |
| ④小团队做得动 | 4（原⑤） | **3** | 单格式、单航线草稿可做；费率更新与个性化仍有持续负担。[评价](https://www.g2.com/products/wisor-ai-wisor-ai/reviews) |
| ⑤形态简单 | **未给**；原④是“B 端5” | **3** | 前台能简单，后台需处理缺项、版本、有效期与审批。[对标流程](https://freitt.com/how-it-works) |

**综合分：56／100＝(4＋2＋2＋3＋3)÷25×100。**②低于推荐线，不建议直接立项；仅保留低成本付费验证。原深挖 **66 分**采用另一套六维权重且夹带相邻市场证据，本次不沿用，也不把两者差值解释成市场下滑。**此总分不代表 SEO 获客可行性**；AI 赋能另在正文判断，不重复加分。原表的 B 端身份只用于确定买家。

### 搜索量与国家审计

数据来自本批已提供的 PXAny 各国 Google 关键词查询，时间戳 **2026-10-24 19:28:01**，未注明时区；地区／语言依原配置。**610 条是市场×词记录，不是独立需求数；同义词及国家数值不相加估市场。**[供应商接口](https://api.pxany.com/v1/keyword-volumes)

| 市场／语言 | 全部查询 | 完整任务候选 | 候选：正数／原标0待核／未返回 | 本国 Google 有效样本份数 |
|---|---:|---:|---|---:|
| US／英语 | 62 | 17 | 0／17／0 | 11 |
| UK／英语 | 62 | 17 | 0／17／0 | 11 |
| CA／英语 | 62 | 17 | 0／17／0 | 11 |
| AU／英语 | 62 | 17 | 0／17／0 | 10 |
| DE／德语 | 51 | 14 | 0／14／0 | 未取得 |
| FR／法语 | 52 | 16 | 0／16／0 | 未取得 |
| ES／西语 | 52 | 14 | 0／14／0 | 未取得 |
| IT／意语 | 52 | 15 | 0／15／0 | 未取得 |
| NL／荷语 | 51 | 15 | 0／14／1 | 未取得 |
| JP／日语 | 52 | 15 | 0／1／14 | 未取得 |
| KR／韩语 | 52 | 15 | 0／14／1 | 未取得 |

本表由附件最终判定表复算；可复查[美国工作流词](https://www.google.com/search?q=freight+email+quote+workflow&gl=us&hl=en&num=10)、[德国邮件报价词](https://www.google.com/search?q=E-Mail+zu+Frachtangebot&gl=de&hl=de&num=10)，这些链接不承诺保留采集时排名。

四态审计：**返回正数 7 条**，全部是相邻运价管理，排除主判定；**原标“供应商返回0”541 条**；**未返回 62 条**；原清单内**未查询 0 条**。但采集代码将 `avgMonthlySearches=null` 也写为 0，原始响应未保存，故不能把这 541 条都认证为供应商显式返回零。原值不改，逐条加“不确定零值来源”标记；本次抽样重查 DNS 失败，已留日志。**不写“全部无搜索”，也不把未返回视为≤200。**[供应商入口](https://api.pxany.com/v1/keyword-volumes)

全部词逐条标记：完整任务候选 **172 条**、步骤词 **230 条**、相邻任务 **180 条**、当前不承接 **28 条**，均按市场×词计；只有完整任务候选进入主任务 SEO 判断。步骤词有导入、解析、模板等不同输入／输出，只留审计。全部 **610 行**含原值、四态、分类原因、是否计入主判定，见附件 `evidence/keyword-audit.csv`；最终口径见 `final-judgments.json`，`serp.json`／`serp.md`同步读取。

### 核心表达与排除记录

最终英文核心保留完整任务／报价系统表达，**11 个词**；原核心里的独立运价管理、邮件解析、费率导入、代理比价、跟进统计移出主核心。原生 Outlook／Gmail 插件词列为当前不承接，不能用转发邮箱假装插件。

| 国家 | 本地核心候选例词 | 搜索量状态／实际检索边界 |
|---|---|---|
| DE | `Speditionsangebote automatisieren` | 原标0待核；补搜有面向货代的自动化页面。[本地用语参照](https://logispot.io/de/) |
| FR | `créer une cotation depuis un mail` | 原标0待核；补搜有同任务法语页面。[参照](https://logispot.io/fr/) |
| ES | `software de cotizaciones para transitarios` | 原标0待核；补搜有 transitarios 软件页。[参照](https://www.freightools.com/es) |
| IT | `creare preventivi spedizioni da email` | 原标0待核；补搜有软件与运输服务混合。[参照](https://www.freightools.com/it) |
| NL | `vrachtoffertes maken vanuit e-mail` | 未返回；局部词能找到报价模块，完整邮箱流程覆盖待核。[参照](https://www.logipulse.com/nl/features/) |
| JP | `メールから見積作成 フォワーダー` | 未返回；返回通用报价与货代系统，不证明专门邮件流水线有量。[参照](https://www.prolayer.com/accel/) |
| KR | `이메일로 포워딩 견적 작성` | 未返回；返回招聘／物流报价等，未找到可直接比较的独立邮件报价 SaaS。[意图反例](https://www.samsungsds.com/kr/digital-forwarding-platform/cello-square.html) |

上述本地词均已补实际一般网页搜索，**不能冒充指定国家 Google 前十**。原 `core.txt` 只有英语，导致非英语核心被零值／缺失门槛跳过；最终核心已补本地表达并记录待补状态。`E-Mail zu Frachtangebot`、`cotizaciones de fletes desde correos` 的补搜主要偏运输／邮政服务，已剔出主任务候选。完整各语种词表随附件，未硬凑新词数量。

**相邻机会仅列，不计搜索量、付费或竞争分：**独立运价管理／报价后催单与输赢统计／货主向多家货代采购比价／独立邮件解析 API／欧洲公路运价情报／美国公路经纪报价／运输和报关履约。原报告的 Cargobloom 官方服务描述为欧洲道路货运情报与 API，不作为本任务付费对标。[企业页](https://cargobloom.io/enterprise)、[官方服务描述](https://cargobloom.io/terms)

### 方法、来源与交付限制

- 先读新版 `sop-v3.md`、`sop-criteria.md`、`reddit-method.md`，沿用已存在需求日报入口；未另跑其他赛道。原报告与原词表只作待复核材料。
- Reddit 窗口为 **2026-04-24—2026-10-24**。优先 r/freightforwarding、r/CargoWise；通过[Arctic Shift 接口](https://arctic-shift.photon-reddit.com/api/posts/search?subreddit=freightforwarding&after=2026-04-24&before=2026-10-25&limit=100&sort=asc)请求，首试和稍后重试均 DNS 失败；相邻请求间隔至少 **3 秒**，未换 IP 或绕限制。网页工具也不可访问，退回 `site:reddit.com` 和逐页打开。**未完成半年全量、翻页及评论 API 抓取**。
- 正文列出的流程／步骤支持线程共 **6 条**，其中本次核到明确近半年日期的 **2 条**；不是独立付费买家样本。按线程编码、每痛点每线程最多一次；低权重步骤帖另标，不因重复评论多计。排序及痛点计数见 `evidence/reddit-sample.json`、`reddit-ranked.csv`、`pain-counts.json`。评论总数**未找到**，不伪称已按完整评论数排序，也不推行业发生率。
- SERP 的地区参数沿原供应商结果；本次原页访问核实产品范围与变动，未登录试用竞品。对年龄按精确注册日复算，不用四舍五入年数判阈值；原始“年轻”标签只在原档案保留，不作最终结论。
- 证据包保留原 SERP、最终判定、完整词表、HTTP／DNS 错误、来源卡、计算及计时；不包含 API 密钥或会话日志。网页价格和内容以本次可读版本为准，搜索缓存与当前页冲突时优先当前可读官网。
- 公开报告网页：**未发布**。本地 GitHub API 连通性检查失败；已准备本地静态阅读页，未生成虚假的公开地址。各核心结论仍附可打开的原始公开来源。

<!-- TIMING -->

**用时（北京时间，本机日志）：**本批扩词 8.6 分钟；已提供 SERP 采集 41.5 分钟；本轮核验、报告及打包前检查 19.2 分钟；批次合计 69.4 分钟。起点为 2026-10-24 18:37:52，报告阶段起点 19:28:01，本次记录终点 19:47:13。此前扩词／SERP 为复用材料，不计作本轮新查询。计时来源随附件 `timing.txt`、`evidence/timing-audit.json`。
