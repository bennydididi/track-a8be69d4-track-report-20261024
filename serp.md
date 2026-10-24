# 邮件询价到可审核报价：最终 SERP 判定

本文件与 report.md、serp.json、公开页（若发布）均读取 final-judgments.json。原始数据另存 evidence/original-serp.json 与 original-serp.md。

| 相关需求 | 当前切口独立收费 | SEO优先级 |
|---|---|---|
| 有相关需求；样本有限，推广污染已降权 | 待验证；同任务公开标价已找到，独立付费/续费 PMF 未找到 | 暂不优先；未取得主任务可靠正搜索量，非英语指定国家 Google 前十未完成 |

口径：A完整任务候选；B步骤词、C相邻任务、D不承接均不贡献主搜索量/付费/竞争评分。供应商原始响应未保存，原标0不能排除null转0；不是已核实的精确零需求。

| 市场 | 全部查询 | A类任务词 | A类正数/原标0待核/未返回 | A类地区SERP可用份数 |
|---|---:|---:|---|---:|
| US | 62 | 17 | 0/17/0 | 11 |
| UK | 62 | 17 | 0/17/0 | 11 |
| CA | 62 | 17 | 0/17/0 | 11 |
| AU | 62 | 17 | 0/17/0 | 10 |
| DE | 51 | 14 | 0/14/0 | 0 |
| FR | 52 | 16 | 0/16/0 | 0 |
| ES | 52 | 14 | 0/14/0 | 0 |
| IT | 52 | 15 | 0/15/0 | 0 |
| NL | 51 | 15 | 0/14/1 | 0 |
| JP | 52 | 15 | 0/1/14 | 0 |
| KR | 52 | 15 | 0/14/1 | 0 |

所有地区样本不足10条；没有完整前十结论。AU 的 rate sheets 生成词结果全部偏离任务，排除。非英语仅补一般网页检索，指定地区Google仍待补。

## 完整市场×词审计

| 市场 | 词 | 任务口径 | 原数值/状态 | 最终判定 |
|---|---|---|---|---|
| US | freight forwarder quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | freight forwarding quotation system | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | quoting software for small freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | cloud freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | freight quotation management software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | freight quote automation software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | AI freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | freight email quote workflow | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | email to quote for freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | freight RFQ email automation | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | freight quote request management | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | freight quote shared inbox | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote email parser | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight RFQ attachment extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | extract shipment details from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote data entry automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote missing information detection | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote reply automation | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote email draft generator | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | freight quotation PDF generator | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quoting Outlook add in | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quoting Gmail extension | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate management software | C 相邻任务 | 30 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight forwarding rate management system | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | air freight rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | ocean freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate database software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate sheet import software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate extraction from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | PDF freight rate sheet extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | Excel freight rate sheet import | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate sheet consolidation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight agent rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight carrier rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight buy and sell rate management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight contract rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight spot rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight rate validity tracking | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight surcharge management software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote margin calculation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote markup rules | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote generation from rate sheets | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | air freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | ocean freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| US | FCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | LCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| US | multimodal freight quoting software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote approval workflow | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote version management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quotation templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote email templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote history management | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight customer specific pricing software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote follow up software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote reminder automation | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote response tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote acceptance tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote status dashboard | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight quote win loss tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| US | freight agent rate request automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight agent reply rate extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| US | freight RFQ email to TMS | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight forwarder quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | freight forwarding quotation system | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | quoting software for small freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本8条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | cloud freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | freight quotation management software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | freight quote automation software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | AI freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | freight email quote workflow | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | email to quote for freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | freight RFQ email automation | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | freight quote request management | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | freight quote shared inbox | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote email parser | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight RFQ attachment extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | extract shipment details from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote data entry automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote missing information detection | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote reply automation | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote email draft generator | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | freight quotation PDF generator | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quoting Outlook add in | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quoting Gmail extension | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight forwarding rate management system | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | air freight rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | ocean freight rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate database software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate sheet import software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate extraction from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | PDF freight rate sheet extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | Excel freight rate sheet import | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate sheet consolidation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight agent rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight carrier rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight buy and sell rate management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight contract rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight spot rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight rate validity tracking | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight surcharge management software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote margin calculation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote markup rules | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote generation from rate sheets | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | air freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | ocean freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| UK | FCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | LCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| UK | multimodal freight quoting software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote approval workflow | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote version management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quotation templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote email templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote history management | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight customer specific pricing software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote follow up software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote reminder automation | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote response tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote acceptance tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote status dashboard | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight quote win loss tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight agent rate request automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight agent reply rate extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| UK | freight RFQ email to TMS | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight forwarder quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | freight forwarding quotation system | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | quoting software for small freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | cloud freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | freight quotation management software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | freight quote automation software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | AI freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | freight email quote workflow | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | email to quote for freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | freight RFQ email automation | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | freight quote request management | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | freight quote shared inbox | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote email parser | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight RFQ attachment extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | extract shipment details from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote data entry automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote missing information detection | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote reply automation | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote email draft generator | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | freight quotation PDF generator | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quoting Outlook add in | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quoting Gmail extension | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight forwarding rate management system | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | air freight rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | ocean freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate database software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate sheet import software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate extraction from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | PDF freight rate sheet extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | Excel freight rate sheet import | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate sheet consolidation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight agent rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight carrier rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight buy and sell rate management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight contract rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight spot rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight rate validity tracking | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight surcharge management software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote margin calculation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote markup rules | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote generation from rate sheets | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | air freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | ocean freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| CA | FCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | LCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| CA | multimodal freight quoting software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote approval workflow | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote version management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quotation templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote email templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote history management | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight customer specific pricing software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote follow up software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote reminder automation | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote response tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote acceptance tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote status dashboard | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight quote win loss tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight agent rate request automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight agent reply rate extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| CA | freight RFQ email to TMS | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight forwarder quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | freight forwarding quotation system | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | quoting software for small freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | cloud freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | freight quotation management software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | freight quote automation software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | AI freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | freight email quote workflow | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | email to quote for freight forwarders | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | freight RFQ email automation | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | freight quote request management | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | freight quote shared inbox | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote email parser | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight RFQ attachment extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | extract shipment details from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote data entry automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote missing information detection | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote reply automation | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote email draft generator | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | freight quotation PDF generator | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quoting Outlook add in | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quoting Gmail extension | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight forwarding rate management system | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | air freight rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | ocean freight rate management software | C 相邻任务 | 10 / 返回正数 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate database software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate sheet import software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate extraction from emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | PDF freight rate sheet extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | Excel freight rate sheet import | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate sheet consolidation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight agent rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight carrier rate comparison software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight buy and sell rate management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight contract rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight spot rate management software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight rate validity tracking | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight surcharge management software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote margin calculation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote markup rules | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote generation from rate sheets | A 主任务候选 | 0 / 供应商返回0 | 异常离题样本，排除竞争判断；9条均为政府利率/统计等页面 |
| AU | air freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | ocean freight quoting software | A 主任务候选 | 0 / 供应商返回0 | 主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先 |
| AU | FCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | LCL quotation software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| AU | multimodal freight quoting software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote approval workflow | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote version management | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quotation templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote email templates | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote history management | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight customer specific pricing software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote follow up software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote reminder automation | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote response tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote acceptance tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote status dashboard | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight quote win loss tracking | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight agent rate request automation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight agent reply rate extraction | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| AU | freight RFQ email to TMS | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Angebotssoftware für Speditionen | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Angebotserstellung für kleine Speditionen | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Angebotsmanagement Spedition | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Angebotsverwaltung Spedition Software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Speditionsangebote automatisieren | A 主任务候选 | 0 / 供应商返回0 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| DE | KI Angebotserstellung Spedition | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Frachtangebote online erstellen | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Speditionsanfragen automatisch bearbeiten | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Frachtanfragen aus E-Mails erfassen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | E-Mail zu Frachtangebot | D 当前不承接 | 未返回 / 未返回 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| DE | E-Mail Auswertung Frachtanfragen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtdaten aus E-Mails auslesen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Packlisten für Angebote auslesen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Speditionsanfragen gemeinsam bearbeiten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Antworten auf Frachtanfragen automatisieren | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| DE | Angebotsmails für Speditionen erstellen | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Frachtangebote als PDF erstellen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtangebote in Outlook erstellen | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| DE | Ratenmanagement Software Spedition | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtratenverwaltung Software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Luftfrachtraten verwalten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Seefrachtraten verwalten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtratendatenbank | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtraten aus E-Mails auslesen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtraten aus PDF importieren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtraten aus Excel importieren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Ratenblätter zentral verwalten | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Agentenraten vergleichen Software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Einkaufsraten und Verkaufsraten verwalten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtkontrakte und Raten verwalten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Spotraten verwalten | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Gültigkeit von Frachtraten überwachen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtzuschläge verwalten Software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtangebote mit Marge kalkulieren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Kundenspezifische Frachtraten verwalten | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtangebote aus Ratenlisten erstellen | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Luftfrachtangebote erstellen Software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Seefrachtangebote erstellen Software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | LCL Angebote kalkulieren Software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | FCL Angebote kalkulieren Software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| DE | Freigabeprozess für Frachtangebote | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Speditionsangebote Vorlagen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Versionen von Frachtangeboten verwalten | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Angebotshistorie Spedition | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Frachtangebote automatisch nachfassen | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Wiedervorlage Frachtangebote | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Kundenantworten zu Frachtangeboten zuordnen | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Angebotsstatus Spedition verfolgen | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Annahme von Frachtangeboten erfassen | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| DE | Ratenanfragen an Agenten automatisieren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| DE | Agentenantworten automatisch auswerten | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | logiciel de cotation pour transitaire | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | outil de devis pour petit transitaire | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | logiciel de gestion des cotations fret | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | cotation fret en ligne pour transitaires | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | automatisation des cotations fret | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | IA pour cotation transitaire | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | traitement des demandes de cotation | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | gestion des demandes de prix transitaire | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | créer une cotation depuis un mail | A 主任务候选 | 0 / 供应商返回0 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| FR | automatiser les demandes de cotation par mail | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | extraction des données de fret par email | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | extraction des pièces jointes de cotation | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | lecture automatique des listes de colisage | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | boîte mail partagée cotations fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | réponse automatique aux demandes de cotation | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| FR | générer un mail de cotation fret | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | générer un devis de fret PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | créer des cotations fret dans Outlook | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| FR | logiciel de gestion des tarifs fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion tarifaire pour transitaires | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | base de données tarifs fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des tarifs de fret aérien | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des tarifs de fret maritime | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | extraire les tarifs fret des emails | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | importer des tarifs fret PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | importer des tarifs fret Excel | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | centraliser les grilles tarifaires fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | comparaison des tarifs agents transitaire | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | comparer les tarifs transporteurs logiciel | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion tarifs achat vente transitaire | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des tarifs contractuels fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des tarifs spot fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | suivi de validité des tarifs fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des surcharges fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | calcul de marge cotation fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | tarifs clients transitaire logiciel | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | générer des cotations depuis les tarifs | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | logiciel de cotation fret aérien | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | logiciel de cotation fret maritime | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | logiciel cotation conteneur complet | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | logiciel cotation groupage maritime | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| FR | validation des cotations fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | modèle de cotation transitaire | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | modèle mail devis transitaire | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | gestion des versions de cotations fret | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | historique des cotations transitaire | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | relance automatique devis transitaire | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | suivi des réponses clients aux cotations | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | suivi des cotations acceptées refusées | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | suivi du statut des cotations fret | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| FR | automatiser les demandes de tarifs agents | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| FR | extraire les tarifs des réponses agents | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | software de cotizaciones para transitarios | A 主任务候选 | 0 / 供应商返回0 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| ES | software de cotización para agentes de carga | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | cotizador para pequeños transitarios | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | sistema de gestión de cotizaciones de fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | automatización de cotizaciones de fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | inteligencia artificial para cotizar fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | gestión de solicitudes de cotización de fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | cotizaciones de fletes desde correos | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| ES | automatizar cotizaciones de fletes por correo | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | extraer datos de carga de correos | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | extraer datos de adjuntos para cotizar fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | lectura automática de listas de empaque | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | bandeja compartida cotizaciones de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | automatizar respuestas a cotizaciones de fletes | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| ES | generador de correos de cotización de fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | generar cotizaciones de fletes en PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | cotizar fletes desde Outlook | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| ES | software de gestión de tarifas para transitarios | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestor de tarifas de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | base de datos de tarifas de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de tarifas aéreas para agentes de carga | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de tarifas marítimas para transitarios | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | extraer tarifas de fletes de correos | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | importar tarifas de fletes desde PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | importar tarifas de fletes desde Excel | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | centralizar tarifarios de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | comparar tarifas de agentes de carga | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | software para comparar tarifas de navieras | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de tarifas de compra y venta de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de tarifas de contrato de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de tarifas spot de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | control de vigencia de tarifas de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | gestión de recargos de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | cálculo de margen en cotizaciones de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | tarifas por cliente para transitarios | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | crear cotizaciones desde tarifarios de fletes | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | software cotización flete aéreo | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | software cotización flete marítimo | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | cotizador FCL para transitarios | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | cotizador LCL para agentes de carga | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| ES | aprobación de cotizaciones de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | plantilla de cotización de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | plantilla correo cotización de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | control de versiones de cotizaciones de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | historial de cotizaciones de fletes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | seguimiento automático de cotizaciones de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | recordatorios de cotizaciones de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | seguimiento de respuestas a cotizaciones de fletes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | control de cotizaciones de fletes aceptadas | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | estado de cotizaciones para agentes de carga | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| ES | automatizar solicitudes de tarifas a agentes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| ES | extraer tarifas de respuestas de agentes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | software preventivi per spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | gestione preventivi piccoli spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | software gestione quotazioni spedizioni | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | preventivatore per spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | automazione quotazioni spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | intelligenza artificiale preventivi spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | gestione richieste di quotazione spedizionieri | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | creare preventivi spedizioni da email | A 主任务候选 | 0 / 供应商返回0 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| IT | automatizzare richieste preventivo spedizioni | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | estrarre dati spedizione dalle email | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | estrazione dati allegati per preventivi spedizioni | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | lettura automatica distinte colli | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | casella condivisa preventivi spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | automatizzare risposte preventivi spedizioni | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| IT | generare email preventivo spedizioni | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | generare preventivi spedizioni PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | preventivi spedizioni da Outlook | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| IT | software gestione tariffe spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestionale tariffe trasporti internazionali | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | banca dati tariffe spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione tariffe aeree spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione tariffe marittime spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | estrarre tariffe noli dalle email | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | importare tariffe spedizioni da PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | importare tariffe spedizioni da Excel | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | centralizzare listini spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | confronto tariffe agenti spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | software confronto tariffe vettori | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione tariffe acquisto vendita spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione tariffe contrattuali spedizioni | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione tariffe spot spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | controllo scadenza tariffe spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione supplementi noli | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | calcolo margine preventivi spedizioni | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | listini personalizzati clienti spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | creare preventivi da listini spedizioni | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | software preventivi trasporto aereo | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | software preventivi trasporto marittimo | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | software quotazioni FCL | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | software quotazioni LCL | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| IT | approvazione preventivi spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | modello preventivo spedizioni internazionali | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | modello email preventivo spedizioni | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione revisioni preventivi spedizioni | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | storico preventivi spedizionieri | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | solleciti automatici preventivi spedizioni | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | promemoria preventivi spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | monitoraggio risposte clienti preventivi spedizioni | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | gestione preventivi accettati spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | stato quotazioni spedizionieri | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| IT | automatizzare richieste tariffe agli agenti | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| IT | estrarre tariffe dalle risposte degli agenti | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | offertesoftware voor expediteurs | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offertetool voor kleine expediteurs | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offertebeheer expediteur | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offertesysteem expeditie | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | vrachtoffertes automatiseren | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | AI offertes expediteur | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offerteaanvragen beheren expediteur | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | vrachtoffertes maken vanuit e-mail | A 主任务候选 | 未返回 / 未返回 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| NL | vrachtaanvragen automatisch verwerken | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | vrachtgegevens uit e-mails halen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | bijlagen uitlezen voor vrachtoffertes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | paklijsten automatisch uitlezen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | gedeelde inbox vrachtoffertes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachtaanvragen automatisch beantwoorden | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| NL | offertemails maken expediteur | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | vrachtoffertes als PDF maken | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachtoffertes maken in Outlook | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| NL | tarievenbeheer software expediteur | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachttarieven beheren | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | tarievendatabase expediteur | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | luchtvrachttarieven beheren | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | zeevrachttarieven beheren | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachttarieven uit e-mails halen | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachttarieven importeren uit PDF | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachttarieven importeren uit Excel | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | tarievenlijsten centraliseren expediteur | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | agenttarieven vergelijken software | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vervoerderstarieven vergelijken software | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | inkoop en verkooptarieven expeditie | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | contracttarieven beheren expediteur | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | spottarieven beheren expediteur | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | geldigheid vrachttarieven bewaken | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachttoeslagen beheren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | marge berekenen vrachtoffertes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | klantspecifieke tarieven expediteur | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachtoffertes maken uit tarievenlijsten | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offertesoftware luchtvracht | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | offertesoftware zeevracht | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | FCL offertes berekenen software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | LCL offertes berekenen software | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| NL | vrachtoffertes goedkeuren | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | offertesjabloon expediteur | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | offertehistorie expediteur | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | versiebeheer vrachtoffertes | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| NL | vrachtoffertes automatisch opvolgen | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | herinneringen vrachtoffertes | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | klantreacties op vrachtoffertes bijhouden | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | geaccepteerde vrachtoffertes bijhouden | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | offertestatus expediteur | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | tariefaanvragen aan agenten automatiseren | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| NL | tarieven uit antwoorden van agenten halen | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積システム | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 小規模フォワーダー 見積ソフト | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | フォワーダー 見積管理 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 国際物流 見積作成 クラウド | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | フォワーダー 見積自動化 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | フォワーダー AI 見積 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | フォワーダー 見積依頼 管理 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | メールから見積作成 フォワーダー | A 主任务候选 | 未返回 / 未返回 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| JP | 運賃見積依頼 メール 自動処理 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 見積依頼メール 貨物情報 抽出 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 見積依頼 添付ファイル 自動読取 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | パッキングリスト データ抽出 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積依頼メール 共有 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積回答 自動化 | D 当前不承接 | 未返回 / 未返回 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積回答メール 作成 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 国際輸送 見積書 PDF 作成 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー Outlook 見積作成 | D 当前不承接 | 未返回 / 未返回 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 運賃管理システム | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー レート管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 運賃データベース | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 航空貨物 運賃管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 海上運賃 管理システム | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 運賃メール 自動取込 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 運賃表 PDF データ化 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 運賃表 Excel 取込 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 運賃表 一元管理 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 海外代理店 運賃 比較ツール | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 船社レート 比較システム | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 仕入運賃 販売運賃 管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 契約運賃 管理システム | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | スポット運賃 管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 運賃 有効期限 管理 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | サーチャージ 管理システム | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積 利益率 計算 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 顧客別運賃 管理 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 運賃表から見積書 自動作成 | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 航空貨物 見積作成システム | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | 海上貨物 見積作成システム | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | FCL 見積作成 ソフト | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | LCL 見積作成 ソフト | A 主任务候选 | 未返回 / 未返回 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| JP | フォワーダー 見積承認 システム | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 国際輸送 見積書 テンプレート | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積回答メール 例文 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積 版管理 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積履歴 管理 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積 フォロー 自動化 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積 リマインド | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 見積メール 顧客返信 管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積 受注失注 管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | フォワーダー 見積案件 進捗管理 | C 相邻任务 | 未返回 / 未返回 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| JP | 海外代理店 運賃問い合わせ 自動化 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| JP | 海外代理店 回答メール 運賃抽出 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워더 견적 프로그램 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 소규모 포워딩 견적 시스템 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적 관리 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적 클라우드 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적 자동화 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워더 AI 견적 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적 요청 관리 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 이메일로 포워딩 견적 작성 | A 主任务候选 | 未返回 / 未返回 | 核心词待补指定国家Google；已补一般网页搜索，不能替代本国前十；SEO未判易做 |
| KR | 포워딩 견적 문의 자동 처리 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 견적 메일 화물 정보 추출 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 견적 요청 첨부파일 자동 인식 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 패킹리스트 데이터 추출 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 메일 공동 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 회신 자동화 | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 회신 메일 작성 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적서 PDF 생성 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 아웃룩 포워딩 견적 자동화 | D 当前不承接 | 0 / 供应商返回0 | D 当前不承接；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 운임 관리 프로그램 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워더 요율 관리 시스템 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 운임 데이터베이스 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 항공 운임 관리 시스템 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 해상 운임 관리 시스템 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 운임 메일 자동 수집 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 운임표 PDF 데이터 추출 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 운임표 엑셀 업로드 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 운임표 통합 관리 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 해외 파트너 운임 비교 프로그램 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 선사 운임 비교 프로그램 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 매입 매출 운임 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 계약 운임 관리 시스템 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 스팟 운임 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 운임 유효기간 관리 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 할증료 관리 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 마진 계산 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 고객별 운임 관리 | B 步骤词 | 未返回 / 未返回 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 운임표 기반 견적서 자동 작성 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 항공 화물 견적 프로그램 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 해상 화물 견적 프로그램 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | FCL 견적 프로그램 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | LCL 견적 프로그램 | A 主任务候选 | 0 / 供应商返回0 | 外围候选未达>200的扩查条件或未返回数值；仅留量，不作SERP结论 |
| KR | 포워딩 견적 승인 시스템 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적서 양식 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 회신 메일 예시 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적서 버전 관리 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 이력 관리 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 후속 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 알림 자동화 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 견적 메일 고객 답변 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 수주 실주 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 포워딩 견적 진행 상태 관리 | C 相邻任务 | 0 / 供应商返回0 | C 相邻任务；不贡献主任务搜索量、付费或竞争评分 |
| KR | 해외 파트너 운임 문의 자동화 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |
| KR | 해외 파트너 회신 운임 추출 | B 步骤词 | 0 / 供应商返回0 | B 步骤词；不贡献主任务搜索量、付费或竞争评分 |

## 已返回地区搜索样本（原顺序；不补齐不存在的第十条）

### US · freight forwarder quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | getquotable.ai | 2025-03-04 | https://getquotable.ai/industries/freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | quora.com | 2000-03-29 | https://www.quora.com/What-is-the-best-freight-forwarder-quote-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | gofreight.com | 1999-03-30 | https://gofreight.com/product/rate-management-quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | buske.com | 1996-06-03 | https://www.buske.com/what-is/freight-quote-software | 保留排名观察；未据域名年龄推断可进入性 |

### US · quoting software for small freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/best-freight-forwarding-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gofreight.com | 1999-03-30 | https://gofreight.com/product/rate-management-quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/top-13-freight-quoting-software-shippers-2026-verified-jay-oliver-hvwzc | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quotation management software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | shipthis.co | 未找到 | https://www.shipthis.co/solutions/freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/future-of-freight-quote-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | magaya.com | 2000-12-13 | https://www.magaya.com/quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote automation software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | magaya.com | 2000-12-13 | https://www.magaya.com/quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | tabiconnect.com | 2023-03-07 | https://tabiconnect.com/freight-quote-automation-the-complete-guide-for-freight-brokers/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ai-powered-freight-quote-management-automating-rate-analysis-px6kc | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | drumkit.ai | 2024-07-01 | https://www.drumkit.ai/blog/revolutionizing-rate-quotes-the-future-of-freight-broker-financials | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight email quote workflow

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | aeralis.ai | 2025-11-19 | https://aeralis.ai/blog/ai-email-freight-broker-quotes | 已关闭的通用 Gmail 草稿插件；排除直接竞争 |
| 9 | haulier.ai | 2026-07-09 | https://haulier.ai/blog/freight-quote-automation | 英国集装箱公路运输服务；排除本任务直接竞争 |

### US · email to quote for freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/your-freight-is-ready-your-quote-is-still-pendingif-you-ship-internationally-or-/1843334491135391/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/features-2/quotes-air-shipping-freight-international-quotes-2/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | arcb.com | 2000-05-18 | https://view.arcb.com/nlo/tools/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | f5-out.io | 2022-07-07 | https://f5-out.io/blog/freight-broker-email-templates | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | facebook.com | 1997-03-29 | https://www.facebook.com/groups/278061703990102/posts/1642703640859228/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/why-follow-up-on-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight RFQ email automation

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | frai.global | 2025-10-30 | https://www.frai.global/resources/what-is-email-to-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 2 | zavin.ai | 2026-07-08 | https://zavin.ai/blog/freight-forwarder-email-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | fasterquotes.io | 2025-12-28 | https://fasterquotes.io/blog/best-freight-email-automation-tools-brokers-2026 | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Gmtcim-tzeM | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | wove.com | 1998-10-27 | https://wove.com/email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | aeralis.ai | 2025-11-19 | https://aeralis.ai/blog/ai-email-freight-broker-quotes | 已关闭的通用 Gmail 草稿插件；排除直接竞争 |

### US · freight quote request management

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | chrobinson.com | 1994-06-22 | https://www.chrobinson.com/en-us/contact/request-a-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/instant-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | azfreight.com | 1997-06-22 | https://azfreight.com/news/how-to-manage-your-freight-quote-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | shipperguide.com | 2012-11-13 | https://blog.shipperguide.com/ftl-freight-quote-request | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | gofmi.com | 2001-03-01 | https://gofmi.com/fmi-rate-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=96kymnzzMi4 | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote email parser

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightquote.com | 1998-12-28 | https://www.freightquote.com/customer-service/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | fasterquotes.io | 2025-12-28 | https://fasterquotes.io/blog/best-ai-email-parsing-tools-freight-brokers | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote reply automation

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargofive.com | 2018-04-24 | https://cargofive.com/best-practices-for-digital-freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | tabiconnect.com | 2023-03-07 | https://tabiconnect.com/freight-quote-automation-the-complete-guide-for-freight-brokers/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | linkedin.com | 2002-11-02 | https://www.linkedin.com/top-content/supply-chain-management/automation-tools-for-supply-chain-efficiency/freight-quote-automation-for-faster-replies/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | trinetix.com | 2011-02-15 | https://www.trinetix.com/insights/freight-quoting-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/automated-quoting | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quoting Outlook add in

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | microsoft.com | 1991-05-02 | https://marketplace.microsoft.com/en-in/product/wa200006939 | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | fasterquotes.io | 2025-12-28 | https://fasterquotes.io/blog/manage-freight-quotes-in-outlook | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | acumatica.com | 2008-02-07 | https://community.acumatica.com/distribution-6/freight-in-cr-sales-quote-12776 | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | dmsiworks.com | 2015-05-08 | https://kb.dmsiworks.com/knowledge-base/freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | dynamics.com | 1994-04-12 | https://community.dynamics.com/forums/thread/details/?threadid=33b33e90-c961-4675-a323-c836bb580568 | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | arcb.com | 2000-05-18 | https://view.arcb.com/nlo/tools/quotes | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quoting Gmail extension

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wearewarp.com | 2022-01-28 | https://www.wearewarp.com/freight-chrome-extension | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | wordpress.org | 2003-03-28 | https://wordpress.org/plugins/freight-shipping-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | google.com | 1997-09-15 | https://chromewebstore.google.com/detail/fr8quote/ddoakkmdjdhibcmlpeonccfhfganncld | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/triumphforbrokers_triumphintelligence-freighttech-logistics-activity-7406351901988052993-GnM- | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | eniture.com | 2014-07-18 | https://eniture.com/woocommerce-freightquote-ltl-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightwaves.com | 2017-02-17 | https://www.freightwaves.com/news/sonar-releases-sonar-quick-rates-chrome-extension | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | github.com | 2007-10-09 | https://github.com/dkautomation23/freight-quote-drafts | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight rate management software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightender.com | 2020-01-01 | https://www.freightender.com/freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | terminal-industries.com | 2023-01-22 | https://terminal-industries.com/all-resources/freight-rate-management-software-automate-optimize-costs | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightview.com | 2003-09-28 | https://www.freightview.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | tilt.ai | 2017-12-16 | https://tilt.ai/blog/freight-rate-management-software-guide-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | magaya.com | 2000-12-13 | https://www.magaya.com/catapult-freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight forwarding rate management system

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/what-is-a-freight-rate-management-system | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/global-price-management/freight-rate-management-system-rms | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | transporeon.com | 2000-03-01 | https://www.transporeon.com/en/platform/transport-execution-visibility-hub/carrier-lsp/rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightender.com | 2020-01-01 | https://www.freightender.com/rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight rate sheet import software

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | magaya.com | 2000-12-13 | https://www.magaya.com/freight-forwarding-software-for-import-operations/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | terminal-industries.com | 2023-01-22 | https://terminal-industries.com/all-resources/freight-rate-management-software-automate-optimize-costs | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargotransinc.com | 1999-11-11 | https://cargotransinc.com/atlas-tms/rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/gofreight-platform-overview | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Vx6B2Z9tdvs | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1nyvxov/is_there_software_for_fetching_results_from/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight rate extraction from emails

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | synetra.de | 未找到 | https://synetra.de/en/pulse/freight-rate-and-booking-requests | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | turingitlabs.com | 2020-12-12 | https://turingitlabs.com/automate-freight-rate-confirmations/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | keelway.com | 2026-04-17 | https://www.keelway.com/solutions/rate-extraction | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/true-cost-of-quoting-freight-in-spreadsheets-and-emails | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/most-freight-still-gets-quoted-the-slow-way-an-email-a-phone-call-a-spreadsheet-/1833370038798503/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight agent rate comparison software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | transfix.io | 2013-12-21 | https://transfix.io/freight-pricing-software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | goodship.io | 2021-12-22 | https://www.goodship.io/blog/what-is-the-best-pricing-software-for-freight-brokers | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | arktms.com | 2023-06-26 | https://arktms.com/blog/best-tms-platforms-freight-brokers-2026 | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | truckstop.com | 1995-07-10 | https://truckstop.com/blog/freight-broker-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | brokerpro.com | 1999-02-03 | https://www.brokerpro.com/compare/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/transparent-freight-software-pricing | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | somersetlogistics.com | 2004-07-22 | https://somersetlogistics.com/2026/05/25/how-to-compare-freight-agent-programs-before-moving-your-book/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote generation from rate sheets

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | gofreight.com | 1999-03-30 | https://gofreight.com/product/rate-management-quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | reddit.com | 2005-04-29 | https://www.reddit.com/r/googlesheets/comments/1gothda/how_to_create_a_freight_rate_table_for_quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/understanding-freight-rate-sheet | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | arcb.com | 2000-05-18 | https://view.arcb.com/nlo/tools/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-rate-free-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | dmsiworks.com | 2015-05-08 | https://kb.dmsiworks.com/knowledge-base/freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=W7WDdR9wSM0 | 保留排名观察；未据域名年龄推断可进入性 |

### US · air freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | gnu.org | 1995-11-24 | https://www.gnu.org/software/bash/manual/html_node/Quoting.html | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | goodreads.com | 2002-12-09 | https://www.goodreads.com/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | ctan.org | 1998-03-11 | https://ctan.org/pkg/quoting?lang=en | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | sfu.ca | 2000-10-10 | https://www.lib.sfu.ca/about/branches-depts/slc/writing/sources/quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | pandadoc.com | 2013-03-07 | https://www.pandadoc.com/quoting-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | hubspot.com | 2005-02-06 | https://knowledge.hubspot.com/quotes/set-up-legacy-quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | floodsmart.gov | 2004-04-14 | https://www.floodsmart.gov/policy-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | stroustrup.com | 1999-06-29 | https://www.stroustrup.com/quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | smartliving365.com | 2011-05-09 | https://smartliving365.com/quotes-to-inspire-courage-hope-and-hanging-in-there/ | 保留排名观察；未据域名年龄推断可进入性 |

### US · ocean freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | hapag-lloyd.com | 1996-08-08 | https://www.hapag-lloyd.com/en/online-business/quotation/quick-quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/ocean/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | icontainers.com | 2003-06-24 | https://www.icontainers.com/ocean-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gofreight.com | 1999-03-30 | https://gofreight.com/solutions/ocean-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | modaltrans.com | 2013-01-09 | https://modaltrans.com/blog/comparison-of-ocean-rate-management-services | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightview.com | 2003-09-28 | https://www.freightview.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gartner.com | 1994-03-15 | https://www.gartner.com/reviews/market/ocean-cargo-software | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote follow up software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | emergemarket.com | 2014-10-07 | https://www.emergemarket.com/post/best-freight-quoting-software-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/future-of-freight-quote-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |

### US · freight quote response tracking

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | journeyfreight.com | 2003-06-12 | https://journeyfreight.com/2026/02/11/how-to-compare-freight-quotes-without-losing-sight-of-the-big-picture/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | x.com | 1993-04-02 | https://x.com/Freightquote | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | getafreightquote.com | 2023-07-10 | https://feeds.getafreightquote.com/service/shipping-quote-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | ultracart.com | 1998-11-26 | https://www.ultracart.com/resources/documentation/white-papers/shipping/freightquote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | rippey.ai | 2022-07-12 | https://rippey.ai/blog/1/the-state-of-freight-forwarder-response-time-2025-industry-update | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | transvirtual.com | 2004-03-26 | https://www.transvirtual.com/ca/blog/your-complete-guide-to-freight-spot-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | fitsmallbusiness.com | 2013-05-15 | https://fitsmallbusiness.com/how-to-get-a-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | getafreightquote.com | 2023-07-10 | https://feeds.getafreightquote.com/service/freight-tracking | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | freight-tec.com | 2002-02-28 | https://freight-tec.com/cargo-tracking-how-to-monitor-shipments-in-real-time/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight forwarder quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | getquotable.ai | 2025-03-04 | https://getquotable.ai/industries/freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | quora.com | 2000-03-29 | https://www.quora.com/What-is-the-best-freight-forwarder-quote-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | globalialogisticsnetwork.com | 2016-04-20 | https://www.globalialogisticsnetwork.com/FreightViewer-home.php | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | quotio.eu | 未找到 | https://quotio.eu/blog/what-is-freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightos.com | 2012-06-09 | https://www.freightos.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · quoting software for small freight forwarders

主任务候选；混合意图；样本8条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | softwareadvice.co.uk | 2016-11-24 | https://www.softwareadvice.co.uk/directory/567/freight-broker-software/software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/how-a-digital-solution-helps-freight-forwarders-increase-quote-profits/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/quotiss-freight-software-explained/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightmynd.com | 2026-03-13 | https://freightmynd.com/blog/best-ai-freight-quoting-software-2026/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/top-13-freight-quoting-software-shippers-2026-verified-jay-oliver-hvwzc | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/the-best-freight-rate-management-software-4-unique-ways-to-use-quotiss/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quotation management software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/future-of-freight-quote-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | mycargomanager.com | 2025-01-24 | https://www.mycargomanager.com/resources/blog/how-quotation-management-software-helps-forwarders-win-more-business/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/freight-quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | storenshipfast.com | 2018-09-12 | https://www.storenshipfast.com/latest-news/quotation-management-software-optimizes-sales-cycle/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote automation software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | github.com | 2007-10-09 | https://github.com/dtolnay/quote | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | civilservicepensionscheme.org.uk | 2014-04-30 | https://www.civilservicepensionscheme.org.uk/quotes-hub | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | cambridge.org | 1998-04-18 | https://dictionary.cambridge.org/dictionary/english/quote | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | ac.uk | 未找到 | https://quote.qub.ac.uk/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gov.uk | 未找到 | https://www.buckinghamshire.gov.uk/planning-building-and-environment/building-regulations-and-control/request-a-building-control-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | goodreads.com | 2002-12-09 | https://www.goodreads.com/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | reddit.com | 2005-04-29 | https://www.reddit.com/r/quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | gov.uk | 未找到 | https://www.publiccontractsscotland.gov.uk/userguides/Quick%20Quote%20-%20Purchaser%20Guide.pdf | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | stroustrup.com | 1999-06-29 | https://www.stroustrup.com/quotes.html | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight email quote workflow

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | frai.global | 2025-10-30 | https://www.frai.global/case-studies/freight-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 4 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | haulier.ai | 2026-07-09 | https://haulier.ai/blog/freight-quote-automation | 英国集装箱公路运输服务；排除本任务直接竞争 |
| 7 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | youtube.com | 2005-02-15 | https://www.youtube.com/shorts/ICTjvhfQZPM | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |

### UK · email to quote for freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | barringtonfreight.co.uk | 2006-12-05 | https://www.barringtonfreight.co.uk/quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ways-improve-quotation-process-your-freight-forwarder-marina-fel%C3%ADcio-vdcaf | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/features-2/quotes-air-shipping-freight-international-quotes-2/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/your-freight-is-ready-your-quote-is-still-pendingif-you-ship-internationally-or-/1843334491135391/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/why-follow-up-on-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | profreight.co.uk | 2001-05-03 | https://www.profreight.co.uk/get-in-touch/get-a-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | virtualworkforce.ai | 2023-05-28 | https://virtualworkforce.ai/save-time-on-freight-forwarding-emails/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | eship360.com | 2026-02-23 | https://eship360.com/blogs/why-freight-forwarders-are-moving-away-from-email-based-quotations/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight RFQ email automation

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | frai.global | 2025-10-30 | https://www.frai.global/resources/what-is-email-to-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 2 | zavin.ai | 2026-07-08 | https://zavin.ai/blog/freight-forwarder-email-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 3 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | inboxpilot.co | 未找到 | https://www.inboxpilot.co/use-cases/rfq-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/wend-ai_intelligentrfqmanagement-activity-7513576794747215872-Wp13 | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/freight-forwarding-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | rfqautopilot.com | 2026-02-09 | https://rfqautopilot.com/blog/rfq-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | zavin.ai | 2026-07-08 | https://zavin.ai/platform/email-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |

### UK · freight quote request management

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | azfreight.com | 1997-06-22 | https://azfreight.com/news/how-to-manage-your-freight-quote-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | maersk.com | 1995-10-10 | https://www.maersk.com/onlinequote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/request-for-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | zendeq.com | 2021-04-24 | https://www.zendeq.com/logistics-term/freight-quote-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/freight-quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote email parser

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightsuite.com | 2009-03-18 | https://www.freightsuite.com/blog/email-parsing-logistics | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=vuOnqlIa_rw | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | quotio.eu | 未找到 | https://quotio.eu/blog/what-to-look-for-in-a-logistics-email-parsing-tool | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | getshipmatch.com | 2025-11-29 | https://getshipmatch.com/blog/ai-email-parser-shipbrokers | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | skills.rest | 2025-10-24 | https://skills.rest/skill/freight-email-parser | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | frai.global | 2025-10-30 | https://www.frai.global/resources/how-to-automate-freight-quote-requests | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 9 | aftership.com | 2012-01-01 | https://www.aftership.com/docs/parser/d1bc872974d0e-parse-an-email | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote reply automation

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargofive.com | 2018-04-24 | https://cargofive.com/best-practices-for-digital-freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | linkedin.com | 2002-11-02 | https://www.linkedin.com/top-content/supply-chain-management/automation-tools-for-supply-chain-efficiency/freight-quote-automation-for-faster-replies/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | frai.global | 2025-10-30 | https://www.frai.global/case-studies/freight-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/solutions/freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | agentomte.com | 2026-07-19 | https://www.agentomte.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/automated-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/freight-automation-8-smart-ways-to-win-more-deals/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quoting Outlook add in

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | microsoft.com | 1991-05-02 | https://marketplace.microsoft.com/en-in/product/wa200006939 | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | fasterquotes.io | 2025-12-28 | https://fasterquotes.io/blog/manage-freight-quotes-in-outlook | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightsuite.com | 2009-03-18 | https://www.freightsuite.com/instant-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | vimeo.com | 2004-12-15 | https://vimeo.com/1051524926 | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-quoting-tools-simplified-what-they-are-and-how-they-drive-value-for-forwarders-webcargo/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Q8TjGhVnW3k | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | frai.global | 2025-10-30 | https://www.frai.global/integrations/outlook | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |

### UK · freight quoting Gmail extension

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wordpress.org | 2003-03-28 | https://wordpress.org/plugins/freight-shipping-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | google.com | 1997-09-15 | https://chromewebstore.google.com/detail/fr8quote/ddoakkmdjdhibcmlpeonccfhfganncld | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | github.com | 2007-10-09 | https://github.com/dkautomation23/freight-quote-drafts | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | google.com | 1997-09-15 | https://play.google.com/store/apps/details?id=com.freightamigo.faosApp&hl=en_GB | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightsuite.com | 2009-03-18 | https://www.freightsuite.com/instant-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | mozilla.org | 1998-01-24 | https://addons.mozilla.org/en-GB/firefox/addon/unquote-for-gmail/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight rate management software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | transporeon.com | 2000-03-01 | https://www.transporeon.com/en/platform/transport-execution-visibility-hub/shipper/rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightender.com | 2020-01-01 | https://www.freightender.com/freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | prologistik.com | 1998-03-18 | https://www.prologistik.com/en/ai-deep-dive/which-software-solutions-exist-for-freight-rate-management-in-logistics/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | tilt.ai | 2017-12-16 | https://tilt.ai/blog/freight-rate-management-software-guide-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight forwarding rate management system

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/what-is-a-freight-rate-management-system | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | transporeon.com | 2000-03-01 | https://www.transporeon.com/en/platform/transport-execution-visibility-hub/shipper/rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/rate-management-system-benefits-best-practices | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | tier2systems.com | 2020-11-06 | https://tier2systems.com/en/blog/freight-rate-management-guide/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/global-price-management/freight-rate-management-system-rms | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight rate sheet import software

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | shipsy.ai | 2021-02-24 | https://www.shipsy.ai/insights/freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | prologistik.com | 1998-03-18 | https://www.prologistik.com/en/ai-deep-dive/which-software-solutions-exist-for-freight-rate-management-in-logistics/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Vx6B2Z9tdvs | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/how-to-complicate-freight-ratesheets-1/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | shipthis.co | 未找到 | https://www.shipthis.co/blog/freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | reddit.com | 2005-04-29 | https://www.reddit.com/r/googlesheets/comments/1gothda/how_to_create_a_freight_rate_table_for_quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | cargoson.com | 2018-08-09 | https://www.cargoson.com/en/blog/freight-surcharge-management-software | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight rate extraction from emails

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | gov.uk | 未找到 | https://www.gov.uk/find-business-rates | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cambridge.org | 1998-04-18 | https://dictionary.cambridge.org/dictionary/english/rate | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | bankofengland.co.uk | 1996-06-14 | https://www.bankofengland.co.uk/monetary-policy/the-interest-rate-bank-rate | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | prisonstudies.org | 2000-01-27 | https://www.prisonstudies.org/world-prison-data/highest-lowest/highest-lowest-prison-population-rate?language_content_entity=en-gb | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | livingwage.org.uk | 2002-02-07 | https://www.livingwage.org.uk/what-real-living-wage | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gov.uk | 未找到 | https://ratesonline.finance-ni.gov.uk/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gov.uk | 未找到 | https://www.ons.gov.uk/economy/inflationandpriceindices/bulletins/consumerpriceinflation/august2026 | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | mygov.scot | 2014-07-15 | https://www.mygov.scot/non-domestic-rates-guidance/rates-calculations | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gov.uk | 未找到 | https://www.nidirect.gov.uk/services/pay-your-rates-online | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight agent rate comparison software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | ibm.com | 1986-03-19 | https://www.ibm.com/think/topics/ai-agents | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | agentmarketing.co.uk | 2006-05-08 | https://agentmarketing.co.uk/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | datadoghq.com | 2010-07-09 | https://docs.datadoghq.com/agent/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | langchain.com | 2019-12-03 | https://www.langchain.com/blog/what-is-an-agent | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | owasp.org | 2001-09-21 | https://genai.owasp.org/resource/agent-control-standard-acs/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | agent-project.eu | 未找到 | https://agent-project.eu/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gov.uk | 未找到 | https://www.gov.uk/government/publications/agent-update-issue-146/issue-146-of-agent-update | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | simonwillison.net | 2005-03-09 | https://simonwillison.net/2025/Sep/18/agents/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | greeneheaton.co.uk | 1999-01-05 | https://greeneheaton.co.uk/agents/imogen-morrell | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote generation from rate sheets

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | reddit.com | 2005-04-29 | https://www.reddit.com/r/googlesheets/comments/1gothda/how_to_create_a_freight_rate_table_for_quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/freight-rate-sheet-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | gofreight.com | 1999-03-30 | https://gofreight.com/product/rate-management-quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/understanding-freight-rate-sheet | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | tradetech.net | 1996-09-20 | https://site.tradetech.net/freight-rate-management-for-freight-forwarders/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ai-powered-freight-quote-management-automating-rate-analysis-px6kc | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-rate-free-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Vx6B2Z9tdvs | 保留排名观察；未据域名年龄推断可进入性 |

### UK · air freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/air/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | 7lfreight.com | 2006-10-18 | https://www.7lfreight.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | transglobalexpress.co.uk | 1999-09-27 | https://www.transglobalexpress.co.uk/air-freight/rates/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | icontainers.com | 2003-06-24 | https://www.icontainers.com/calculator/air-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/air-freight-software-solutions | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/air-freight-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightfinders.com | 2004-07-10 | https://freightfinders.com/air-freight/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargo.one | 2016-08-19 | https://www.cargo.one/press/ai-quoting-and-operational-control-tools | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | guideflow.com | 2009-11-03 | https://www.guideflow.com/blog/air-freight-software | 保留排名观察；未据域名年龄推断可进入性 |

### UK · ocean freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | hapag-lloyd.com | 1996-08-08 | https://www.hapag-lloyd.com/en/online-business/quotation/quick-quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/ocean/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | icontainers.com | 2003-06-24 | https://www.icontainers.com/ocean-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | modaltrans.com | 2013-01-09 | https://modaltrans.com/blog/comparison-of-ocean-rate-management-services | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | buyco.co | 未找到 | https://buyco.co/blog/digital-transformation/ocean-freight-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gofreight.com | 1999-03-30 | https://gofreight.com/solutions/ocean-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargorates.ai | 2023-03-21 | https://www.cargorates.ai/BCOs | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote follow up software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/freight-quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotio.eu | 未找到 | https://quotio.eu/blog/what-is-freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |

### UK · freight quote response tracking

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | transvirtual.com | 2004-03-26 | https://www.transvirtual.com/ca/blog/your-complete-guide-to-freight-spot-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | deliveryquotecompare.com | 2008-11-02 | https://www.deliveryquotecompare.com/freight-forwarders/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightnet.com | 1996-02-25 | https://www.freightnet.com/freight-quote.php | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | instagram.com | 2004-06-04 | https://www.instagram.com/p/Dd064QnAWsx/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargopoint.one | 2022-02-02 | https://www.cargopoint.one/post/guide-to-freight-quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | postkodes.com | 2021-06-04 | https://blog.postkodes.com/immediate-air-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightamigo.com | 2015-08-11 | https://www.freightamigo.com/en/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightrate.com | 1996-06-11 | https://freightrate.com/blog/freight-quotes-transit-time/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | facebook.com | 1997-03-29 | https://www.facebook.com/internationalaircargoairparcelexpress/posts/waiting-days-for-a-freight-quote-kills-momentum-one-instant-estimate-shows-the-r/1557619419738125/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight forwarder quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightviewer.com | 2017-09-13 | https://www.freightviewer.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-forwarding-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | verifiedmarketresearch.com | 2018-05-30 | https://www.verifiedmarketresearch.com/blog/best-freight-quoting-software-a-buyers-guide-to-faster-smarter-freight-decisions/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | shipthis.co | 未找到 | https://www.shipthis.co/solutions/freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | capterra.ca | 2020-08-05 | https://www.capterra.ca/directory/30670/freight/pricing/free/software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/top-13-freight-quoting-software-shippers-2026-verified-jay-oliver-hvwzc | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightera.com | 2014-03-31 | https://www.freightera.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |

### CA · quoting software for small freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/forwarder-tms/freight-forwarding-software-for-small-business | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/best-freight-forwarding-software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | getquotable.ai | 2025-03-04 | https://getquotable.ai/industries/freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/top-13-freight-quoting-software-shippers-2026-verified-jay-oliver-hvwzc | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotio.eu | 未找到 | https://quotio.eu/freight-forwarding-software | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quotation management software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/future-of-freight-quote-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | shipthis.co | 未找到 | https://www.shipthis.co/solutions/freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | storenshipfast.com | 2018-09-12 | https://www.storenshipfast.com/latest-news/quotation-management-software-optimizes-sales-cycle/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote automation software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | magaya.com | 2000-12-13 | https://www.magaya.com/quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | haulier.ai | 2026-07-09 | https://haulier.ai/blog/freight-quote-automation | 英国集装箱公路运输服务；排除本任务直接竞争 |
| 5 | cartage.ai | 2023-08-15 | https://www.cartage.ai/best-freight-quoting-software-for-manufacturers | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargofive.com | 2018-04-24 | https://cargofive.com/best-practices-for-digital-freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=FewWomoUExA | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight email quote workflow

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | frai.global | 2025-10-30 | https://www.frai.global/blog/email-to-quote-automation-freight-forwarders | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 4 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | haulier.ai | 2026-07-09 | https://haulier.ai/blog/freight-quote-automation | 英国集装箱公路运输服务；排除本任务直接竞争 |
| 7 | youtube.com | 2005-02-15 | https://www.youtube.com/shorts/ICTjvhfQZPM | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |

### CA · email to quote for freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/features-2/quotes-air-shipping-freight-international-quotes-2/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/your-freight-is-ready-your-quote-is-still-pendingif-you-ship-internationally-or-/1843334491135391/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ways-improve-quotation-process-your-freight-forwarder-marina-fel%C3%ADcio-vdcaf | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/why-follow-up-on-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | virtualworkforce.ai | 2023-05-28 | https://virtualworkforce.ai/save-time-on-freight-forwarding-emails/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | f5-out.io | 2022-07-07 | https://f5-out.io/blog/freight-broker-email-templates | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight RFQ email automation

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | forwardia.net | 2025-12-07 | https://forwardia.net/en/solutions/email-automation-for-freight-forwarders/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | virtualworkforce.ai | 2023-05-28 | https://virtualworkforce.ai/reduce-email-workload-freight-forwarding/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | globaltrademag.com | 2010-11-15 | https://www.globaltrademag.com/can-automated-freight-quoting-solve-the-inbound-email-bottleneck/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | gmelius.com | 2011-08-23 | https://gmelius.com/blog/freight-operations-software | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1b3v140/do_you_automate_your_email_communication/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | fleetx.ai | 2022-06-21 | https://blog.fleetx.ai/request-for-quote-rfq-management-made-easy-with-tms-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=7pRT3y6iVec | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | truckertools.com | 2007-12-01 | https://www.truckertools.com/trucker-tools-email-parsing-and-automation-reduces-costs-creates-better-experience-for-carriers/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | loadsnap.io | 2024-03-11 | https://www.loadsnap.io/blog/posts/email-templates-freight-dispatchers/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote request management

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | chrobinson.com | 1994-06-22 | https://www.chrobinson.com/en-us/contact/request-a-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | azfreight.com | 1997-06-22 | https://azfreight.com/news/how-to-manage-your-freight-quote-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/request-for-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | csatransportation.com | 2003-11-01 | https://www.csatransportation.com/freight-quote-online | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | queensu.ca | 2000-10-06 | https://www.queensu.ca/procurement/sites/procwww/files/uploaded_images/Qship/Request%20for%20Freight%20Quote.pdf | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | transvirtual.com | 2004-03-26 | https://www.transvirtual.com/ca/blog/your-complete-guide-to-freight-spot-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote email parser

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightsuite.com | 2009-03-18 | https://www.freightsuite.com/blog/email-parsing-logistics | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=vuOnqlIa_rw | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | quotio.eu | 未找到 | https://quotio.eu/blog/what-to-look-for-in-a-logistics-email-parsing-tool | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | getshipmatch.com | 2025-11-29 | https://getshipmatch.com/blog/ai-email-parser-shipbrokers | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | skills.rest | 2025-10-24 | https://skills.rest/skill/freight-email-parser | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote reply automation

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargofive.com | 2018-04-24 | https://cargofive.com/best-practices-for-digital-freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | linkedin.com | 2002-11-02 | https://www.linkedin.com/top-content/supply-chain-management/automation-tools-for-supply-chain-efficiency/freight-quote-automation-for-faster-replies/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | frai.global | 2025-10-30 | https://www.frai.global/case-studies/freight-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/solutions/freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/automated-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | agentomte.com | 2026-07-19 | https://www.agentomte.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | magaya.com | 2000-12-13 | https://www.magaya.com/quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quoting Outlook add in

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | microsoft.com | 1991-05-02 | https://marketplace.microsoft.com/en-in/product/wa200006939 | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | fasterquotes.io | 2025-12-28 | https://fasterquotes.io/blog/manage-freight-quotes-in-outlook | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | dmsiworks.com | 2015-05-08 | https://kb.dmsiworks.com/knowledge-base/freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | wordpress.org | 2003-03-28 | https://en-ca.wordpress.org/plugins/freight-shipping-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | ettransport.ca | 2012-06-05 | https://www.ettransport.ca/blog/ultimate-freight-quote-guide-how-to-get-accurate-freight-quotes-in-canada/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-quoting-tools-simplified-what-they-are-and-how-they-drive-value-for-forwarders-webcargo/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quoting Gmail extension

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wordpress.org | 2003-03-28 | https://wordpress.org/plugins/freight-shipping-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | google.com | 1997-09-15 | https://chromewebstore.google.com/detail/fr8quote/ddoakkmdjdhibcmlpeonccfhfganncld | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | github.com | 2007-10-09 | https://github.com/dkautomation23/freight-quote-drafts | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | google.com | 1997-09-15 | https://play.google.com/store/apps/details?id=com.freightamigo.faosApp&hl=en_CA | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | ups.com | 1992-04-07 | https://www.ups.com/ca/en/supplychain/instant-freight-quote | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/triumphforbrokers_triumphintelligence-freighttech-logistics-activity-7406351901988052993-GnM- | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight rate management software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightender.com | 2020-01-01 | https://www.freightender.com/freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/digital-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | tilt.ai | 2017-12-16 | https://tilt.ai/blog/freight-rate-management-software-guide-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | startupstash.com | 2014-09-04 | https://startupstash.com/best-freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight forwarding rate management system

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/what-is-a-freight-rate-management-system | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/digital-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | tier2systems.com | 2020-11-06 | https://tier2systems.com/en/blog/freight-rate-management-guide/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | transporeon.com | 2000-03-01 | https://www.transporeon.com/en/platform/transport-execution-visibility-hub/shipper/rate-management | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight rate sheet import software

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/freight-rate-sheet-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/global-price-management/freight-pricing-software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-rate-free-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Vx6B2Z9tdvs | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/how-to-complicate-freight-ratesheets-1/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/transparent-freight-software-pricing | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightender.com | 2020-01-01 | https://www.freightender.com/freight-rate-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | shipthis.co | 未找到 | https://www.shipthis.co/blog/freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight rate extraction from emails

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | synetra.de | 未找到 | https://synetra.de/en/pulse/freight-rate-and-booking-requests | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | turingitlabs.com | 2020-12-12 | https://turingitlabs.com/automate-freight-rate-confirmations/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | fygurs.com | 2022-02-18 | https://www.fygurs.com/use-cases/freight-email-quote-response | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/most-freight-still-gets-quoted-the-slow-way-an-email-a-phone-call-a-spreadsheet-/1833370038798503/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | truckertools.com | 2007-12-01 | https://www.truckertools.com/trucker-tools-email-parsing-and-automation-reduces-costs-creates-better-experience-for-carriers/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight agent rate comparison software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | truckstop.com | 1995-07-10 | https://truckstop.com/blog/freight-broker-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=pmdfPaZN8Uo | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/global-price-management/freight-pricing-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | aljex.com | 1997-11-06 | https://www.aljex.com/news/best-freight-broker-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | agrichain.com | 2013-07-28 | https://agrichain.com/blog/freight-broker-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | mycargoagent.com | 2021-12-27 | https://mycargoagent.com/blog/top-10-price-comparison-websites-for-freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=ZYEWP_eOPx4 | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote generation from rate sheets

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/googlesheets/comments/1gothda/how_to_create_a_freight_rate_table_for_quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/freight-rate-sheet-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/freight-rate-free-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gofreight.com | 1999-03-30 | https://gofreight.com/product/rate-management-quoting/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/understanding-freight-rate-sheet | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | dmsiworks.com | 2015-05-08 | https://kb.dmsiworks.com/knowledge-base/freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | arcb.com | 2000-05-18 | https://view.arcb.com/nlo/tools/quotes | 保留排名观察；未据域名年龄推断可进入性 |

### CA · air freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/air/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | 7lfreight.com | 2006-10-18 | https://www.7lfreight.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | icontainers.com | 2003-06-24 | https://www.icontainers.com/calculator/air-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/air-freight-software-solutions | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | forwardair.com | 1997-08-21 | https://www.forwardair.com/tools/quote | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | capterra.ca | 2020-08-05 | https://www.capterra.ca/directory/30670/freight/software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | riege.com | 1996-02-16 | https://www.riege.com/solutions/freight-forwarding-software/air-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | guideflow.com | 2009-11-03 | https://www.guideflow.com/blog/air-freight-software | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/ | 保留排名观察；未据域名年龄推断可进入性 |

### CA · ocean freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | hapag-lloyd.com | 1996-08-08 | https://www.hapag-lloyd.com/en/online-business/quotation/quick-quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | icontainers.com | 2003-06-24 | https://www.icontainers.com/ocean-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/ocean/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gartner.com | 1994-03-15 | https://www.gartner.com/reviews/market/ocean-cargo-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gofreight.com | 1999-03-30 | https://gofreight.com/solutions/ocean-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | modaltrans.com | 2013-01-09 | https://modaltrans.com/blog/comparison-of-ocean-rate-management-services | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote follow up software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | goodreads.com | 2002-12-09 | https://www.goodreads.com/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | crates.io | 2014-01-22 | https://crates.io/crates/quote | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | reddit.com | 2005-04-29 | https://www.reddit.com/r/quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | eisenhowerlibrary.gov | 2019-05-06 | https://www.eisenhowerlibrary.gov/eisenhowers/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | acadiau.ca | 2000-09-26 | https://library.acadiau.ca/research/tutorials/you-quote-it-you-note-it-2.html | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | merriam-webster.com | 1999-02-08 | https://www.merriam-webster.com/dictionary/quote | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | stroustrup.com | 1999-06-29 | https://www.stroustrup.com/quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | tei-c.org | 1999-03-22 | https://www.tei-c.org/release/doc/tei-p5-doc/en/html/ref-quote.html | 保留排名观察；未据域名年龄推断可进入性 |

### CA · freight quote response tracking

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightquote.com | 1998-12-28 | https://www.freightquote.com/blog/how-to-track-freight-shipments/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | ups.com | 1992-04-07 | https://www.ups.com/ca/en/supplychain/instant-freight-quote | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/education/quote-faster-win-more-speed-to-lead | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | echo.com | 1991-12-03 | https://www.echo.com/quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | facebook.com | 1997-03-29 | https://www.facebook.com/quickloadapp/videos/what-does-it-take-to-get-a-freight-quotefor-many-shippers-and-brokers-it-still-m/1816214376026792/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightquote.com | 1998-12-28 | https://www.freightquote.com/blog/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | aftership.com | 2012-01-01 | https://carriers.aftership.com/freightquote | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | fedex.com | 1991-02-26 | https://www.fedex.com/en-us/shipping/freight/resources/calculate-freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight forwarder quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | getquotable.ai | 2025-03-04 | https://getquotable.ai/industries/freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | softwareadvice.com.au | 未找到 | https://www.softwareadvice.com.au/software/270920/air-trak | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightos.com | 2012-06-09 | https://www.freightos.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | globalialogisticsnetwork.com | 2016-04-20 | https://www.globalialogisticsnetwork.com/FreightViewer-home.php | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/what-is-freight-forwarding-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | kynection.com.au | 未找到 | https://www.kynection.com.au/australian-freight-forwarders-8-software-tools-you-need-in-2026/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · quoting software for small freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | softwareadvice.com.au | 未找到 | https://www.softwareadvice.com.au/directory/567/freight-broker-software/software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | getquotable.ai | 2025-03-04 | https://getquotable.ai/industries/freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | quotio.eu | 未找到 | https://quotio.eu/freight-forwarding-software | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | kynection.com.au | 未找到 | https://www.kynection.com.au/australian-freight-forwarders-8-software-tools-you-need-in-2026/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/gofreight-platform-overview | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quotation management software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/blog/future-of-freight-quote-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | softwareadvice.com.au | 未找到 | https://www.softwareadvice.com.au/directory/567/freight-broker-software/software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | storenshipfast.com | 2018-09-12 | https://www.storenshipfast.com/latest-news/quotation-management-software-optimizes-sales-cycle/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote automation software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=FewWomoUExA | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/freight-quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software-alternatives | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | frai.global | 2025-10-30 | https://www.frai.global/resources/how-to-automate-freight-quote-requests | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/cargofive_ai-powered-freight-quoting-how-automation-activity-7408141676499652608-mv5o | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/quotiss-freight-software-explained/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | tallemucrm.com | 2008-11-10 | https://tallemucrm.com/quoting/freight/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/freight-automation-8-smart-ways-to-win-more-deals/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/what-is-freight-forwarding-software/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight email quote workflow

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | frai.global | 2025-10-30 | https://www.frai.global/blog/email-to-quote-automation-freight-forwarders | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 5 | haulier.ai | 2026-07-09 | https://haulier.ai/blog/freight-quote-automation | 英国集装箱公路运输服务；排除本任务直接竞争 |
| 6 | youtube.com | 2005-02-15 | https://www.youtube.com/shorts/ICTjvhfQZPM | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/founders-insight/accelerate-your-quote-turnaround-the-hidden-costs-and-solutions-in-freight-forwarding.html | 保留排名观察；未据域名年龄推断可进入性 |

### AU · email to quote for freight forwarders

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wisor.ai | 2021-08-24 | https://wisor.ai/solution/freight-email-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | frai.global | 2025-10-30 | https://www.frai.global/blog/email-to-quote-automation-freight-forwarders | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 4 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/your-freight-is-ready-your-quote-is-still-pendingif-you-ship-internationally-or-/1843334491135391/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/features-2/quotes-air-shipping-freight-international-quotes-2/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightforwarderquoteonline.com.au | 未找到 | https://www.freightforwarderquoteonline.com.au/get-free-freight-quote-online-australia/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ways-improve-quotation-process-your-freight-forwarder-marina-fel%C3%ADcio-vdcaf | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | facebook.com | 1997-03-29 | https://www.facebook.com/groups/278061703990102/posts/1642703640859228/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/why-follow-up-on-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight RFQ email automation

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | frai.global | 2025-10-30 | https://www.frai.global/resources/what-is-email-to-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 2 | zavin.ai | 2026-07-08 | https://zavin.ai/platform/email-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 3 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | inboxpilot.co | 未找到 | https://www.inboxpilot.co/use-cases/rfq-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/wend-ai_intelligentrfqmanagement-activity-7513576794747215872-Wp13 | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/freight-forwarding-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | rfqautopilot.com | 2026-02-09 | https://rfqautopilot.com/blog/rfq-email-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | zavin.ai | 2026-07-08 | https://zavin.ai/blog/freight-forwarder-email-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |

### AU · freight quote request management

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/request-for-freight-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | azfreight.com | 1997-06-22 | https://azfreight.com/news/how-to-manage-your-freight-quote-request/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | explorate.co | 未找到 | https://www.explorate.co/quote-formulary | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | linkedin.com | 2002-11-02 | https://www.linkedin.com/pulse/ai-powered-freight-quote-management-automating-rate-analysis-px6kc | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | nationalfreightmanagement.com.au | 未找到 | https://www.nationalfreightmanagement.com.au/expertise/instant-online-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/founders-insight/accelerate-your-quote-turnaround-the-hidden-costs-and-solutions-in-freight-forwarding.html | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote email parser

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightools.com | 2019-10-13 | https://www.freightools.com/help/how-to-send-a-quotation-to-your-customer-by-email | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | fillme.com.au | 未找到 | https://fillme.com.au/quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | mailgun.com | 2003-12-20 | https://www.mailgun.com/glossary/email-parsing/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | capterra.com.au | 未找到 | https://www.capterra.com.au/software/153243/mailparser-io | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/md-sadikul-islam-849067243_logistics-shipping-shippers-activity-7410684276196835328-quEJ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | sfi.com | 2000-12-13 | https://sfi.com/blog/how-to-ask-for-a-freight-quote | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | seatram.com.au | 未找到 | https://www.seatram.com.au/tag/how-to-compare-freight-quotes-australia/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | linkedin.com | 2002-11-02 | https://www.linkedin.com/top-content/writing/email-writing-best-practices/freight-broker-email-reply-rate-strategies/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | mailparser.io | 2013-04-08 | https://mailparser.io/quote/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote reply automation

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargofive.com | 2018-04-24 | https://cargofive.com/best-practices-for-digital-freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | linkedin.com | 2002-11-02 | https://www.linkedin.com/top-content/supply-chain-management/automation-tools-for-supply-chain-efficiency/freight-quote-automation-for-faster-replies/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | frai.global | 2025-10-30 | https://www.frai.global/case-studies/freight-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 6 | nexcade.ai | 2024-10-18 | https://nexcade.ai/solutions/freight-quote-automation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | agentomte.com | 2026-07-19 | https://www.agentomte.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | lanesurf.com | 2025-04-23 | https://feeds.lanesurf.com/blog/automated-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | trinetix.com | 2011-02-15 | https://www.trinetix.com/insights/freight-quoting-automation | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quoting Outlook add in

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | webmd.com | 1998-04-06 | https://www.webmd.com/add-adhd/childhood-adhd/add-vs-adhd | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | verywellmind.com | 2017-10-18 | https://www.verywellmind.com/add-and-attention-deficit-disorders-2161810 | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | gov.au | 未找到 | https://tfnswforms.transport.nsw.gov.au/45065893-add-change-delete-authorised-contact-for-an-organisation.pdf | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | co-add.org | 2014-10-27 | https://www.co-add.org/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | instagram.com | 2004-06-04 | https://www.instagram.com/reel/DQMwlEEjqsb/?hl=en | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gov.au | 未找到 | https://nt.gov.au/industry/business-grants-funding/agricultural-value-add-grant-program | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gov.au | 未找到 | https://www.afsa.gov.au/professionals/resource-hub/forms/add-debt-bankruptcy | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=46yvviQW4Zo | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gov.au | 未找到 | https://www.tga.gov.au/resources/resources/forms/add-or-remove-agent-your-organisation | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quoting Gmail extension

D 当前不承接；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | wordpress.org | 2003-03-28 | https://wordpress.org/plugins/freight-shipping-quote/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | google.com | 1997-09-15 | https://chromewebstore.google.com/detail/fr8quote/ddoakkmdjdhibcmlpeonccfhfganncld | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | github.com | 2007-10-09 | https://github.com/dkautomation23/freight-quote-drafts | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | google.com | 1997-09-15 | https://play.google.com/store/apps/details?id=com.freightamigo.faosApp&hl=en | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightsuite.com | 2009-03-18 | https://www.freightsuite.com/instant-quoting | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | senditt.au | 未找到 | https://senditt.au/blog/how-to-compare-freight-quotes-like-for-like/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | quotio.eu | 未找到 | https://quotio.eu/freight-quoting-software | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight rate management software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | transvirtual.com | 2004-03-26 | https://www.transvirtual.com/freight-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/best-rate-management-system | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | prologistik.com | 1998-03-18 | https://www.prologistik.com/en/ai-deep-dive/which-software-solutions-exist-for-freight-rate-management-in-logistics/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | guideflow.com | 2009-11-03 | https://www.guideflow.com/blog/freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | mitti.com | 1998-08-13 | https://mitti.com/apps/freight-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | infios.com | 2022-12-14 | https://www.infios.com/en/knowledge-center/blog/reinvent-your-freight-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | frayto.com | 2024-12-07 | https://frayto.com/blogs/freight-rate-management-software-what-importers-and-exporters-need-to-know | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | transporeon.com | 2000-03-01 | https://www.transporeon.com/en/platform/transport-execution-visibility-hub/carrier-lsp/rate-management | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight forwarding rate management system

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | oyaso.com | 2015-05-21 | https://oyaso.com/en/rate-management-systems-better-manage-freight-rates-offers-freight-rates-spot-and-daily-prices/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | xeneta.com | 2012-02-06 | https://www.xeneta.com/blog/what-is-a-freight-rate-management-system | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | wisor.ai | 2021-08-24 | https://wisor.ai/freight-rate-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-rate-management | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | transvirtual.com | 2004-03-26 | https://www.transvirtual.com/freight-management-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | cario.com.au | 未找到 | https://cario.com.au/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | tier2systems.com | 2020-11-06 | https://tier2systems.com/en/blog/freight-rate-management-guide/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | etowertech.com | 2015-04-30 | https://www.etowertech.com/news/what-is-a-freight-rate-management-system.html | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight rate sheet import software

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | cargoson.com | 2018-08-09 | https://www.cargoson.com/en/blog/freight-surcharge-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | tilt.ai | 2017-12-16 | https://tilt.ai/blog/freight-rate-management-software-guide-for-shippers | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | quotiss.com | 2016-05-02 | https://quotiss.com/blog/how-to-complicate-freight-ratesheets-1/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | freightos.com | 2012-06-09 | https://www.freightos.com/freight-resources/choosing-a-freight-rate-management-system-rms/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=Vx6B2Z9tdvs | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | shipthis.co | 未找到 | https://www.shipthis.co/blog/freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/gofreight-platform-overview | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight rate extraction from emails

B 步骤词；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | synetra.de | 未找到 | https://synetra.de/en/pulse/freight-rate-and-booking-requests | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | parabola.io | 2015-09-30 | https://parabola.io/use-cases/freight-quote-request-email-parsing | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | turingitlabs.com | 2020-12-12 | https://turingitlabs.com/automate-freight-rate-confirmations/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | miragemetrics.com | 2024-01-30 | https://miragemetrics.com/guides/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | linkedin.com | 2002-11-02 | https://www.linkedin.com/posts/aeb_freight-rates-shouldnt-live-in-excel-email-activity-7472676875753099264-Pkbj | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1lbg0bk/anyone_here_still_doing_freight_quotes_manually/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | freightmynd.com | 2026-03-13 | https://freightmynd.com/solutions/rate-sheet-intelligence/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | frai.global | 2025-10-30 | https://www.frai.global/case-studies/freight-quote-automation | 厂商公开页覆盖邮件到报价；独立价格/付费规模未找到 |
| 9 | facebook.com | 1997-03-29 | https://www.facebook.com/Exfreightzetainc/posts/most-freight-still-gets-quoted-the-slow-way-an-email-a-phone-call-a-spreadsheet-/1833370038798503/ | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight agent rate comparison software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | capterra.com.au | 未找到 | https://www.capterra.com.au/directory/30670/freight/software | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/freight-rate-management-software-comparison/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/transparent-freight-software-pricing | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/top-10-best-freight-rate-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | youtube.com | 2005-02-15 | https://www.youtube.com/watch?v=pmdfPaZN8Uo | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | wisor.ai | 2021-08-24 | https://wisor.ai/best-freight-quoting-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | mycargoagent.com | 2021-12-27 | https://mycargoagent.com/blog/top-10-price-comparison-websites-for-freight-forwarders | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | pulsify.tech | 2025-08-18 | https://www.pulsify.tech/free-tools/carrier-rate-comparison-tool/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | descartes.com | 1995-08-07 | https://www.descartes.com/solutions/broker-and-forwarder-enterprise-systems/global-price-management/freight-pricing-software | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote generation from rate sheets

异常离题样本，排除竞争判断；9条均为政府利率/统计等页面

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | gov.au | 未找到 | https://www.abs.gov.au/media-centre/media-releases/unemployment-rate-47-september | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | gov.au | 未找到 | https://www.arc.gov.au/ncgp-trends-success-rates | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | gov.au | 未找到 | https://www.rba.gov.au/media-releases/2026/mr-26-19.html | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | gov.au | 未找到 | https://www.ipart.nsw.gov.au/Home/Industries/Local-Government/For-Ratepayers/The-rate-peg | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gov.au | 未找到 | https://revenuesa.sa.gov.au/stamp-duty/rate-of-stamp-duty | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gov.au | 未找到 | https://www.dva.gov.au/access-benefits/pensions-and-payments/support-when-you-cannot-work/eligibility-for-disability-compensation-payments/special-and-intermediate-rates | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | gov.au | 未找到 | https://www.abs.gov.au/media-centre/media-releases/unemployment-rate-rises-46-august | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | gov.au | 未找到 | https://www.courts.qld.gov.au/types-of-cases/money-disputes/interest-on-debts/interest-rates | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | gov.au | 未找到 | https://www.rba.gov.au/media-releases/2026/mr-26-03.html | 保留排名观察；未据域名年龄推断可进入性 |

### AU · air freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/air/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | couriersandfreight.com.au | 未找到 | https://www.couriersandfreight.com.au/air-freight-courier/air-freight-quote | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | icontainers.com | 2003-06-24 | https://www.icontainers.com/calculator/air-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/air-freight-software-solutions | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | 7lfreight.com | 2006-10-18 | https://www.7lfreight.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | teamglobalexp.com | 2022-06-21 | https://teamglobalexp.com/air-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/guides/air-freight-software/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | rohlig.com | 1996-07-29 | https://www.rohlig.com/digital-services-tools/online-freight-quotation/ | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | softwareadvice.com.au | 未找到 | https://www.softwareadvice.com.au/directory/567/freight-broker-software/software?page=3 | 保留排名观察；未据域名年龄推断可进入性 |

### AU · ocean freight quoting software

主任务候选；混合意图；样本9条，不足10条；年龄仅观察，SEO暂不优先

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | hapag-lloyd.com | 1996-08-08 | https://www.hapag-lloyd.com/en/online-business/quotation/quick-quotes.html | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | icontainers.com | 2003-06-24 | https://www.icontainers.com/ocean-freight-calculator/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | freightos.com | 2012-06-09 | https://www.freightos.com/forwarders/rate-quote/ocean/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightquote.com | 1998-12-28 | https://www.freightquote.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | gartner.com | 1994-03-15 | https://www.gartner.com/reviews/market/ocean-cargo-software | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | gofreight.com | 1999-03-30 | https://gofreight.com/solutions/ocean-freight | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | cargorates.ai | 2023-03-21 | https://www.cargorates.ai/BCOs | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote follow up software

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | freightify.com | 2012-04-07 | https://www.freightify.com/products/core-platform/quotation | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | quotiss.com | 2016-05-02 | https://quotiss.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | velocityos.ai | 2025-04-08 | https://www.velocityos.ai/quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | reddit.com | 2005-04-29 | https://www.reddit.com/r/logistics/comments/1bjp80x/quoting_system_for_logistics_company/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | nexcade.ai | 2024-10-18 | https://nexcade.ai/perspectives/freight-quoting-software-landscape/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cargoez.com | 2000-03-17 | https://cargoez.com/blog/freight-quote-automation | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | logitudeworld.com | 2011-07-25 | https://www.logitudeworld.com/freight-quote-management/ | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | descartes.com | 1995-08-07 | https://www.descartes.com/resources/knowledge-center/what-freight-quote-management-software | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | softwareadvice.com.au | 未找到 | https://www.softwareadvice.com.au/directory/567/freight-broker-software/software | 保留排名观察；未据域名年龄推断可进入性 |

### AU · freight quote response tracking

C 相邻任务；不贡献主任务搜索量、付费或竞争评分

| 位次 | 域名 | 注册日 | 原页 | 审计备注 |
|---|---|---|---|---|
| 1 | nationalfreightmanagement.com.au | 未找到 | https://www.nationalfreightmanagement.com.au/expertise/instant-online-freight-quotes/ | 保留排名观察；未据域名年龄推断可进入性 |
| 2 | teamglobalexp.com | 2022-06-21 | https://teamglobalexp.com/ | 保留排名观察；未据域名年龄推断可进入性 |
| 3 | gofreight.com | 1999-03-30 | https://gofreight.com/blog/education/quote-faster-win-more-speed-to-lead | 保留排名观察；未据域名年龄推断可进入性 |
| 4 | freightforwarderquoteonline.com.au | 未找到 | https://www.freightforwarderquoteonline.com.au/track-and-trace-for-international-shipments/ | 保留排名观察；未据域名年龄推断可进入性 |
| 5 | facebook.com | 1997-03-29 | https://www.facebook.com/Parcelhero/posts/freight-without-the-48-hour-wait-for-a-quote-compare-trusted-carriers-in-one-pla/1086512394130214/ | 保留排名观察；未据域名年龄推断可进入性 |
| 6 | cario.com.au | 未找到 | https://cario.com.au/uses/compare-freight-quotes-before-you-book-a-consignment | 保留排名观察；未据域名年龄推断可进入性 |
| 7 | transdirect.com.au | 未找到 | https://www.transdirect.com.au/quotes | 保留排名观察；未据域名年龄推断可进入性 |
| 8 | aftership.com | 2012-01-01 | https://carriers.aftership.com/freightquote | 保留排名观察；未据域名年龄推断可进入性 |
| 9 | dhl.com | 1989-05-25 | https://www.dhl.com/au-en/home/ship/freight-quote.html | 保留排名观察；未据域名年龄推断可进入性 |
