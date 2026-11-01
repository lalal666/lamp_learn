# 灯与灯具知识库

> **面向**：硬件产品经理 / 照明门外汉
> **重点场景**：商用、办公、公共建筑照明
> **编制日期**：2026-11-01
> **使用方式**：先读本文「3 分钟速览」，再按问题索引跳转对应文档

---

## 0. 先记住一句话

**灯具不是「灯泡 + 外壳」，而是一个由光源、驱动、光学、热、结构、控制、安规组成的光电系统。**

商用照明的核心不是「亮不亮」，而是：**在标准和成本的双重约束下，稳定地提供正确的光，并让它活够年限。**

---

## 1. 七个问题 → 文档索引

| 你的问题 | 对应文档 | 读完你会得到 |
|---|---|---|
| 1. 不同领域有哪些灯？完整分类 | [01-灯具分类全景](01-灯具分类全景.md) | 一张可交叉检索的分类坐标系 + 全领域产品表 |
| 2. 各领域的评价参数维度 | [02-评价参数维度](02-评价参数维度.md) | 七层参数金字塔 + 各领域权重表 |
| 3. 各领域主要看哪些参数 | [03-分领域关键参数速查](03-分领域关键参数速查.md) | 14 个领域（含家用对照）的「必看参数 + 典型值 + 采购陷阱」 |
| 4. 灯亮起来的系统构成 | [04-一盏灯的系统构成](04-一盏灯的系统构成.md) | 能量流框图 + 8 大模块 + 每模块关键参数 |
| 5. 门外汉如何做好一盏灯 | [05-门外汉如何做好一盏灯](05-门外汉如何做好一盏灯.md) | 从立项到售后的 12 阶段流程 + 三条铁律 |
| 6. 影响品质的因素 | [06-影响品质的因素](06-影响品质的因素.md) | 品质四层次 + 鱼骨图 + 验证体系 |
| 7. 家用灯与商用/公共建筑灯的关系 | [07-家用灯与商用公共建筑照明的异同](07-家用灯与商用公共建筑照明的异同.md) | 同源不同赛道 + 12 维对比 + 同款产品差异 |
| 附：标准与认证 | [08-标准与认证清单](08-标准与认证清单.md) | 按安全/性能/设计/能效/国际分类的清单 |
| 附：术语 | [09-术语表](09-术语表.md) | 60+ 个高频术语的一句话解释 |
| 附：落地检查 | [10-项目落地检查清单](10-项目落地检查清单.md) | 可直接打印使用的逐项勾选表 |

---

## 2. 3 分钟速览：12 条结论

1. **分类不能只用一把尺子。** 一盏灯同时属于「应用领域 × 安装方式 × 光分布 × 环境防护 × 控制方式」五个维度。只按「家用/商用」分，会漏掉大量工程约束。
2. **评价参数分七层**：安全合规 → 光度 → 色度 → 时间稳定性 → 电气能效 → 环境可靠 → 体验商业。**安全层是一票否决，不能被其他层的分数抵消。**
3. **不同领域的差别，本质是「权重不同」，不是「参数不同」。** 办公最看重 UGR + 频闪 + LPD；医疗最看重显色 + 洁净 + 无眩光；道路最看重配光 + 光效 + 寿命；防爆最看重 Ex 等级 + 防护。
4. **一盏灯的能量链是**：市电 → 驱动 → LED → 光学 → 人眼，每一步都有损耗，**整灯效能 = 光源光效 × 驱动效率 × 光学效率 × 热损失系数**。
5. **光源光效 ≠ 灯具效能。** 前者是裸灯珠 lm/W，后者是整灯 lm/W（含驱动、光学、热损失）。用光源光效宣传整灯，是行业最常见的参数注水。
6. **做好一盏灯的顺序是**：先定义场景和标准 → 再写规格 → 再做光学/热/电/结构方案 → 再验证认证 → 最后量产。**顺序反了，后面全是返工。**
7. **品质是设计出来的，不是检出来的。** 来料、工艺、测试只能守住下限；上限由光源选型、散热设计、驱动方案决定。
8. **家用灯与商用灯同属「建筑照明」大类，产品形态和供应链高度重叠，但标准体系、可靠性要求、决策链、商业模式是两条赛道。**
9. **商用照明先看标准，再看参数。** 一个项目能不能验收，取决于 GB/T 50034-2024、GB/T 31831-2025、GB 55015-2021 等标准，而不是产品彩页。
10. **热是 LED 灯具的第一性约束。** 结温每升高约 10 °C，寿命大致减半（Arrhenius 量级规律）；散热不够，光效、寿命、色漂移会同时崩。
11. **频闪和眩光是工程灯最容易翻车的体验指标。** 它们不影响「亮不亮」，但直接影响验收、投诉和长期使用舒适度。
12. **认证是门槛，不是卖点。** CCC 只证明安全合规，不证明光品质；能效标识只证明能效等级，不证明显色和眩光。

---

## 3. 可信度标记

本文档所有关键数据尽量标注来源与可信度：

| 标记 | 含义 |
|---|---|
| ✅ | 标准原文 / 官方公告 / 法规 |
| ◐ | 行业常见口径、厂商公开资料、二手解读 |
| ⚠ | 数值随版本/项目变化大，**必须查标准原文或实测** |

> **重要提醒**：本知识库是「学习地图 + 检查清单」，**不替代标准原文、法定检测报告和项目技术规格书**。涉及验收、认证、招标的数值，一律以现行标准原文和具备资质的实验室报告为准。

---

## 4. 标准时效声明（截至 2026-11-01）

照明标准近两年集中换版，以下是**最容易踩坑的版本变化**：

| 标准 | 现行状态 | 关键变化 |
|---|---|---|
| **GB/T 50034-2024**《建筑照明设计标准》 | ✅ 2024-08-01 实施，替代 GB 50034-2013 | 由强制性转为推荐性；LPD 整体下调；新增健康照明、频闪、非视觉效应、LED 驱动选择 |
| **GB/T 7000.1-2023**《灯具 第1部分：一般要求与试验》 | ✅ 已实施，替代 GB 7000.1-2015（公开口径有 2024-07-01 / 2026-01-01，以官方平台为准） | 由强制性转为推荐性；新增 EMF、PELV、IPX9、直流耐压等要求；蓝光危害条款移出 |
| **GB/T 31831-2025**《LED 室内照明应用技术要求》 | ✅ 2026-04-01 实施，替代 GB/T 31831-2015 | 新增 PstLM/SVM、驱动电源分类与性能、碳足迹、多通道色度要求 |
| **GB 30255-2019**《室内照明用LED产品能效限定值及能效等级》 | ✅ 现行 | 覆盖筒灯、定向集成式 LED 灯、非定向自镇流 LED 灯；**GB 30255-2026 将于 2027-09-01 实施** |
| **GB 38450-2019**《普通照明用LED平板灯能效限定值及能效等级》 | ✅ 现行 | 平板灯单独管理，厚度 ≤85 mm |
| **GB 37478-2019**《道路和隧道照明用LED灯具能效限定值及能效等级》 | ✅ 现行 | **只管道路/隧道**，不适用于室内 |
| **GB 4599-2024**《汽车道路照明装置及系统》 | ✅ 2025-07-01 实施 | 整合原 GB 4599、GB 21259、GB 25991 等六项旧标准 |

> ⚠ **设计冻结、招标文件、认证申请前，必须到「全国标准信息公共服务平台」或标准原文复核版本号与实施日期。** 本表只反映编制时点的公开信息。

---

## 5. 不同角色怎么用这份知识库

| 你的角色/任务 | 建议阅读顺序 |
|---|---|
| 刚接手一个商用照明项目 | README → 05 → 10 → 03 |
| 要判断一款竞品/供应商产品 | 03 → 02 → 06 |
| 要写产品需求规格书（PRD） | 05 → 02 → 08 → 10 |
| 要做技术评审 / 设计评审 | 04 → 06 → 10 |
| 要决定做家用还是工程 | 07 → 03 → 05 |
| 要建供应商体系 | 06 → 08 → 10 |

---

## 6. 参考来源总表

> 以下链接为编制时公开可访问的来源。标准正文通常需要购买或通过官方平台查阅；链接用于确认标准号、名称、实施日期与公开解读。

### 6.1 中国标准与官方公告

- 住房城乡建设部：《建筑照明设计标准》公告（GB/T 50034-2024）— [mohurd.gov.cn](https://www.mohurd.gov.cn/gongkai/zc/wjk/art/2024/art_17339_777466.html)
- 住房城乡建设部：新版《建筑照明设计标准》公布 — [mohurd.gov.cn](https://www.mohurd.gov.cn/xinwen/gzdt/art/2024/art_304_777570.html)
- GB/T 50034-2024 电子书（中国建筑出版传媒）— [ebook.chinabuilding.com.cn](http://ebook.chinabuilding.com.cn/zbooklib/book/detail/show?SiteID=1&bookID=155780)
- GB/T 50034-2024 第 5.3 节「公共建筑」在线条文 — [gf.cabr-fire.com](https://gf.cabr-fire.com/m/article-67005.htm)
- GB/T 7000.1-2023 标准详情 — [std.samr.gov.cn](https://std.samr.gov.cn/gb/search/gbDetailedCNF?id=0DF2F72AE322403DE06397BE0A0A87C4)
- GB 7000.1-2015 标准详情（历史版本）— [ndls.org.cn](https://ndls.org.cn/standard/detail/9662647003710df4ab3a276f5057ccf9)
- GB 30255-2019 标准详情 — [std.samr.gov.cn](https://std.samr.gov.cn/gb/search/gbDetailed?mode=p&id=KuKTJyDAEwU%3D)
- GB 30255-2019 电子书 — [ebook.chinabuilding.com.cn](https://ebook.chinabuilding.com.cn/zbooklib/bookpdf/probation?SiteID=1&bookID=138005)
- GB/T 31831-2025 标准详情 — [openstd.samr.gov.cn](https://openstd.samr.gov.cn/bzgk/std/newGbInfo?hcno=23D6B489544AF0E3913606ADE5AD7271)
- GB/T 31831-2015 全文 PDF（长沙市市场监管局）— [amr.changsha.gov.cn](http://amr.changsha.gov.cn/zfxxgk/tzgg_1_1/202302/P020230818529923573893.pdf)
- GB/T 9473-2022 标准详情 — [spc.org.cn](https://www.spc.org.cn/online/6173bbd0e51f93a0a38f92bc5271ed84.html)
- GB/Z 39942-2021 标准详情 — [spc.org.cn](https://www.spc.org.cn/online/10eea21b6842a1d55af4c92513e2b735.html)
- GB 51309-2018 电子书 — [ebook.chinabuilding.com.cn](http://ebook.chinabuilding.com.cn/zbooklib/book/detail/show?SiteID=1&bookID=110780)
- GB 51309-2018 第 3.2 节「灯具」在线条文 — [gf.cabr-fire.com](https://gf.cabr-fire.com/m/article-28067.htm)
- 全国标准信息公共服务平台 — [std.samr.gov.cn](https://std.samr.gov.cn/)
- 国家标准全文公开系统 — [openstd.samr.gov.cn](https://openstd.samr.gov.cn/)

### 6.2 国际标准与行业组织

- CIE 224:2017《CIE 2017 Colour Fidelity Index》— [cie.co.at](https://cie.co.at/publications/cie-2017-colour-fidelity-index-accurate-scientific-use)
- CIE S 026:2018 官方教程资料 — [files.cie.co.at](https://files.cie.co.at/CIE_S_026_Tutorial2021_information.pdf)
- CIE S 025:2015 LED 测试方法介绍（United for Efficiency）— [united4efficiency.org](http://united4efficiency.org/wp-content/uploads/2017/01/CIE-LED-test-method_Tony-Bergen.pdf)
- IES LM-79 / LM-80 测试方案说明（LISUN）— [lisungroup.com](https://www.lisungroup.com/applications/lm-79-and-lm-80-test-solutions.html)
- IES TM-21 讨论资料（ENERGY STAR）— [energystar.gov](https://www.energystar.gov/ia/partners/prod_development/new_specs/downloads/luminaires/TM-21%20Discussion.pdf)
- DLC 制造商指南（含 LM-79、ISTMT、TM-21）— [designlights.org](https://designlights.org/wp-content/uploads/2021/01/DLC_Manufacturers_Guide_5-10-2019.pdf)
- Zhaga Book 26（线性可插拔 LED 模组）— [zhagastandard.org](https://www.zhagastandard.org/media/acfupload/Zhaga_Book_26_-_Linear_Socketable_LED_Module_for_non-SELV_applications_-_December_2024.pdf)
- 频闪与 TLA 测量说明（Gigahertz-Optik）— [gigahertz-optik.com](https://www.gigahertz-optik.com/zh-cn/app-groups/general-and-special-lighting/flicker-measurements-of-ssl-products-and-installations/)
- UL：灯具 IP 与 IK 测试说明 — [code-authorities.ul.com](https://code-authorities.ul.com/wp-content/uploads/sites/2/2018/06/IK-and-IP-Testing-for-Lighting-Products.pdf)

### 6.3 中国认证与检测

- 国家认监委：强制性产品认证目录界定相关批复 — [cnca.gov.cn](https://www.cnca.gov.cn/ywzl/qzxcprzzl/zfdwzq/hhpf/art/2023/art_f404ea9a6ff44a508d4b314576186138.html)
- 照明电器 CCC 目录与标准（第三方整理）— [ctb-lab.com](https://www.ctb-lab.com/index.php?s=index/category/index&id=1154)
- CQC：照明产品蓝光危害等级认证依据标准变更通知 — [cqc.com.cn](https://www.cqc.com.cn/www/col68/560487.html)

### 6.4 行业解读与工程资料（二手，需交叉验证）

- 新旧版《建筑照明设计标准》变化解析 — [wfsgtsczx.com](http://www.wfsgtsczx.com/contents/7/395.html)
- 办公照明功率密度「现行值/目标值」辨析 — [amoytest.com](https://www.amoytest.com/company/knowledge/office-lighting-power-density-current-and-target-values/)
- LED 光源光效与灯具效能辨析 — [saltnet.com.cn PDF](http://www.saltnet.com.cn/sdzg_admin/upload/myupload_2205.pdf)
- GB/T 24827-2026 标准文本（道路与街路照明灯具性能规范）— [lightingchina.com.cn PDF](https://www.lightingchina.com.cn/upload/article/174600/file/1781492706165063.pdf)
- 教室采光照明相关标准科普 — [thepaper.cn](https://www.thepaper.cn/newsDetail_forward_15253769)
- 中小学校教室采光和照明卫生标准修订（WTO TBT 通报）— [members.wto.org PDF](https://members.wto.org/crnattachments/2025/TBT/CHN/25_02491_00_x.pdf)
- 综合医院建筑设计规范 8.6 照明设计 — [gf.cabr-fire.com](https://gf.cabr-fire.com/m/article-69976.htm)
- 汽车前照灯标准整合工作报告（UNECE）— [wiki.unece.org PDF](https://wiki.unece.org/download/attachments/56591267/SLR-22-03e.pdf)
- 照明控制协议选型（0-10V / DALI / KNX / Zigbee / BLE Mesh）— [cnblogs.com](https://www.cnblogs.com/xinfan-li-xian-yu/p/23106042)
- 移动照明灯塔产品参数示例 — [b2b.bjx.com.cn](https://b2b.bjx.com.cn/product-409964.html)

---

## 7. 版本记录

| 日期 | 内容 |
|---|---|
| 2026-11-01 | 初版：7 个问题全覆盖 + 标准清单 + 术语表 + 检查清单 |
