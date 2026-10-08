# 场景应用 · antiques（古玩·古董场景实例层）

> 本仓为**通用监控体系**；古玩·古董场景的行业特定内容在此。通用渠道/机制见 `01~04` 目录，本目录只放古玩特定实例与指针。
> **本实例重点**：覆盖鉴藏总域 `heritage/03_antiques`，新增并重点维护**「杂项器物」支线**（鼻烟壶、铜器、漆器、竹木牙角、文房器物）。

## 古玩·古董场景要点（来源：矩阵 v1 §3.3 + 杂项器物补充 2026-10-07）

### 品类覆盖（四支线 · 交叉不重复）

- **陶瓷支线（指针引用，不在本目录重复维护）**：五大名窑/景德镇艺术瓷/产业瓷/日瓷/欧瓷/伊斯兰瓷 → 行业包正文见技能库 `industry-packs.md` §ceramics；古瓷拍卖行情复用嘉德/保利/雅昌，建独立陶瓷场景实例时另行落地（`场景应用/ceramics/`，未建）。
- **杂项器物支线（本目录重点新增）**：
  - **鼻烟壶（snuff bottle）**：料器/玻璃、内画、陶瓷、玉石、珐琅（铜胎画珐琅/掐丝珐琅）、竹木牙角等材质——经典古玩门类，藏家客群与珠宝/沉香重叠
  - **铜器**：青铜器、宣德炉、香炉/佛造像（造像另见宗教艺术支线）
  - **漆器**：剔红/雕漆、螺钿
  - **竹木牙角**：笔筒、臂搁、文房摆件
  - **文房器物**：笔筒/砚台/印章/田黄/古墨/供石
  - **高古玉/明清玉**：归 jewelry 古玩体系（§6 第 8 体系），本目录只做行情指针，不重复维护词库
- **宗教艺术支线（观望归并）**：佛造像、唐卡、景泰蓝/点翠（景泰蓝已在 jewelry 中华体系）→ 拍行同（嘉德/保利/匡时佛教艺术专场），不单列建包
- **文人收藏支线（观望归并）**：古籍善本、碑帖、信札手迹 → 学术性强、流动性低，归并不单列

### 主阵地

- **拍场成交/行情**：雅昌艺术网（auction.artron.net 图录 + AMMA 监测）+ 嘉德/保利/西泠官网（第一落点）
- **鉴宝/藏家讨论**：抖音鉴宝、小红书收藏圈、知乎（断代/避坑长文）、贴吧
- **线下**：潘家园、各地古玩城（潘家园为通用古玩渠道，复用不重复）

### 高价值渠道速记（含杂项特定调研源）

- **综合拍行（通用古玩渠道，复用 jewelry §6 古玩体系）**：中国嘉德、北京保利、西泠印社、朵云轩；2025 文物艺术品成交市占：嘉德 28.4 亿/22.1%、保利 23.7 亿/18.4%、西泠 11.8 亿（来源：industry-packs §jewelry-ai §6）
- **杂项特定 · 国内专场（西泠"文房清玩"系列为杂项标杆门类）**：
  - 西泠「文房清玩·古玩杂项/杂件专场」——鼻烟壶、铜器、漆器、竹木牙角主成交场；2025-12-28 专场含"清·银质、螺钿、烧蓝等各式鼻烟壶一组十六件"（无底价，成交 6,900 元）✅ http://www.xlysauc.net/mobile/auction/lists/cid/1851/order/lot_no/sort/desc.html
  - 西泠（绍兴）2026 秋拍「文房清玩·古玩杂项专场」2026-10-12 见排期 ✅ http://www.xlysauc.net/mobile/index/index.html
  - 西泠「文房清玩·历代名砚暨古墨专场」上拍 155/成交 143/成交率 92.26%/含佣成交 3,828.35 万 ✅ http://www.xlysauc.net/mobile/auction/result_list/id/1143.html
  - 西泠「文馨阁藏珍文房清供集萃专场」上拍 72/成交 67/93.06%/含佣 1,479.015 万 ✅ http://www.xlysauc.com/mobile/auction/result_list/id/1658.html
  - 西泠"文房清玩"为其特色门类（2008 首届历代供石专场、2009 陆俨少自用文房雅具专场、首届明清毛笔专场）✅ http://www.xlysauc.net/mobile/business/index/id/29.html
  - 雅昌新闻 2026 西泠秋拍文房杂项珍赏（拍前专题）✅ https://m-news.artron.net/20260928/n1154317.html
  - 保利鼻烟壶在拍例：清 青花釉里红鼻烟壶（六件）估价 1–2 万、含佣成交 11,500 元 ✅ https://cszn.polypm.com.cn/assest/detail/34/art5225550798/34/40
- **杂项特定 · 海外鼻烟壶专拍（私人珍藏系列，海外风向）**：
  - 苏富比「Snuff Bottles from a German Private Collection 德国私人珍藏鼻烟壶」✅ https://www.sothebys.com/en/digital-catalogues/snuff-bottles-from-a-german-private-collection
  - 苏富比「壺趣閑心：雪月藏中國鼻煙壺」（Tuyet Nguyet & Stephen Markbreiter 珍藏）✅ https://www.sothebys.com/en/digital-catalogues/snuff-bottles-from-the-tuyet-nguyet-and-stephen-markbreiter-collection-part-i
  - Bonhams 香港 Mary and George Bloch 珍藏——乾隆款料胎画珐琅"西洋题材"鼻烟壶 2011 年创鼻烟壶世界纪录 US$3,328,400 ✅ https://artdaily.cc/news/52052/Bonhams-in-Hong-Kong-sells-world-record-Chinese-snuff-bottle-for-US-3-328-400 ；Bonhams Paul Braga 鼻烟壶珍藏专拍 ✅ https://artdaily.cc/news/58908/undefined
  - 佳士得「Chinese Ceramics, Works of Art and Textiles」含掐丝珐琅/碧玺鼻烟壶 ✅ https://www.christies.com/en/auction/auction-10419-csk/browse-lots
- **数据/行情工具**：雅昌艺搜拍品库（auction.artron.net 按品类检索成交价）、ArtPro、AMMA 艺术市场监测中心
- **合规提示（沿用 jewelry §6）**：正规拍行不收前期费用、只在成交后收佣金；"送拍要先交费"为典型骗局——调研古玩渠道优先官方拍行，勿信主动联系收前期费的"代拍"

> ⚠️ 待验证（不硬引用）：豆丁网系列"鼻烟壶行业市场规模/材质占比（玉质 31.5%、玻璃内画 27.8%）/三大拍行占 79.4%"等数字为第三方报告转引（🟡），正式引用前需以雅昌 AMMA 年报或拍行官方数据替换。

## 指向矩阵（唯一权威源）

- 行业×渠道匹配总表：`../01_渠道矩阵/行业细分_鉴藏总域_行业渠道匹配_v1_20261007.md` **§3.3（古玩·古董）** 与 **§四（观望行业含文玩杂项归并说明）**
- 行业包正文：`research-toolkit` 技能（行业包 `industry-packs.md`，技能目录；找不到请用户安装） §ceramics + §jewelry-ai §6 古玩体系行
- 通用渠道（抖音/小红书/B站/微博/知乎/海外）：`../01_渠道矩阵/珠宝AI渠道矩阵_v1.1_20261006.md`，本目录不重复

## 古玩场景下一步（待办）

- [ ] 关键词库首批实测：用本目录关键词库 2–3 条查询模板跑一周，回填"哪个操作符在雅昌/拍行官网失效"
- [ ] 杂项专场节奏表：整理嘉德/保利/西泠每年春拍、秋拍的"文房/瓷杂/鼻烟壶"固定专场日历，拍前一周加密监控
- [ ] 杂项专组词扩容：鼻烟壶内画名家（周乐元/叶仲三/马少宣等）、宣德炉/漆器鉴定断代术语随监控高频词回填关键词库
