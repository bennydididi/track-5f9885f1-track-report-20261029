这个产品帮助手里有合法可转换电子书的读者和学生，在通勤或不方便看屏幕的场景下，解决 EPUB/PDF 难以转成可下载、可跳章节的离线有声书的问题。

## 需求判断卡

| 项目 | 判断 |
|---|---|
| ①结论 | **不做：暂缓完整独立站立项，保留新域名单页的首付验证。** 需求真实，但当前切口的真实付款未找到，尚未通过 PMF（用户持续愿意为这个交付买单）门槛；不能把学习工具订阅当成章节文件的付费证明。[直接对标](https://libritalk.com/) |
| ②只判一个任务 | **谁**：有待听电子书、愿意使用自己的播放器的个人读者。**输入**：有权转换、无 DRM（数字版权保护）的 EPUB／可提取文字的 PDF，加选定声音。**输出**：带章节的 M4B 有声书，或分章 MP3 ZIP。**任务**：把整份原文转成可永久保存的离线听书文件。一句话产品：上传、核对目录与正文、试听，按本购买并下载。 |
| 三维决策 | **有相关需求：是；当前切口能否独立收费：待验证；是否优先靠 SEO 扩站：暂不，先验证收费，再测搜索获客。** 有竞品支持市场存在，不能据此证明这一个交付已被购买。 |
| ③核心词与首批页面 | 首页 `/`：`epub to audiobook`、`convert epub to audiobook`；`/pdf-to-audiobook`：`pdf to audiobook`、`convert pdf to audiobook`；`/epub-to-m4b`：`epub to m4b`。同义词共用页面，首页只承接文件转换意图。[词证据](evidence/final-judgments.json) |
| ④关键数字 | 美国月搜：PDF 主词 **880**、EPUB 主词 **390**、PDF 转换词 **170**；均为返回正数，**不相加当独立人数**。PDF 样本 **8 条**，最弱独立站 VoiceBrief **DR17**；`convert epub to audiobook` 样本 **8 条**，Eist、Voice-generator **DR3**，但前者主卖阅读器。KD／KGR／精确链接预算：**未取得**。最大同任务对手访问量：**未找到**；LibriTalk 公布按本 **$0.99／$2.49／$4.99**。[量与SERP](evidence/final-judgments.json) · [竞品价](https://libritalk.com/) |
| ⑤付费证据 | LibriTalk＝**按件价，仅定价页**；本次未找到可核验交易或付费人数。VoiceBrief 有 **6 个活跃订阅**，但属于学习套件，**不计入本任务付费分**。[Stripe 验证页，更新于2026-10-28](https://trustmrr.com/startup/voicebrief) |
| ⑥最小版本与成本 | 限英文 EPUB＋文字 PDF：目录/正文核对→短段试听→异步逐章合成→下载并检查播放。建议验证价 **$4.99／本，上限50万字符**，是实验方案。该字符数的 TTS 理论费用 **$0.495**；其余处理、存储、失败重做、退款和客服成本未实测。[合成单价](https://deepinfra.com/hexgrad/Kokoro-82M) |
| ⑦凭什么赢 | 待验证的优势是“免安装、转换前能改目录与正文、失败只重做出错章节、文件能直接进常用播放器”；**M4B 格式本身已不是独家能力**。[免费同任务方案](https://github.com/kingfish600/Audiobook-NightForge) |
| ⑧增长路径 | 英文 EPUB 转换首页→PDF 转换页→M4B 导入指南→有实付后再做西语 PDF 页面；暂不扩出版工作室、摘要播客和泛 TTS。[各国数据](evidence/keyword-summary.json) |
| ⑨最大风险与改判未知 | 最大风险是用户实际只要“听”，免费阅读器已够用；另有免费章节导出工具。会改决定的证据：用户明确需要可带走的文件，且愿意为省安装、纠错和可靠交付付款。ChatGPT 原生整书章节导出能力本次**未找到完整证明，也不能断言做不到**。[免费朗读与离线听](https://www.paper2audio.com/) · [免费章节导出](https://github.com/DrewThomasson/ebook2audiobook) |
| ⑩下一步与验收 | 先做有字符上限的付费交付实验；首付、再次使用、再次购买分别记账。通过后才 D0 发布并提交 GSC→收录→曝光/排名→自然搜索真实付款；未到节点不买外链。具体天数待哥飞顾问按内页生命周期模型补。 |

## 分数：64／100，暂不推荐投入完整站

原日报和交接卡只给“推／信心中”，**五项原分未找到**，不补造。以下只评本次单一任务；按五项合计÷25×100换算，总分不是 SEO 难度分。[初筛记录](evidence/source-demand.md) · [交接卡](evidence/source-handoff.md)

| 项目 | 专员原分 | 核实后／5 | 关键证据与边界 |
|---|---|---:|---|
| 需求真实 | 未找到 | 4 | 有文件转音频的直接求助；是否必须下载章节文件仍需筛选。[用户原帖](https://www.reddit.com/r/audiobooks/comments/1x1gzyn/speechify_alternatives/) |
| 付费意愿 | 未找到 | 2 | 同任务只有公开报价；“在用”“愿意买”不足以证明付款。[直接对标报价](https://libritalk.com/) |
| 好服务 | 未找到 | 3 | 用户不会安装 GitHub 工具，但也要求复杂 PDF 提取准确。限定文字 PDF 后可服务，不能承诺所有教材。[原帖评论](https://www.reddit.com/r/audiobooks/comments/1x1gzyn/speechify_alternatives/) |
| 小团队做得动 | 未找到 | 4 | 已有开源转换管线和低价合成；仍须做长任务恢复与文件兼容。[开源项目](https://github.com/DrewThomasson/ebook2audiobook) · [单价](https://deepinfra.com/hexgrad/Kokoro-82M) |
| 形态简单 | 未找到 | 3 | 入口像上传表单，交付包含切章、清洗、长音频、重试和播放器检查，不能按一次 API 调用估工。[同任务实现](https://github.com/kingfish600/Audiobook-NightForge) |

付费项低于3，未通过本批筛选门槛。**未找到付款不是断言无人付款**；当前建议是暂缓完整站投资，继续做最小收费验证。[筛选依据](evidence/sop-criteria.md)

## 关键词作战表：重新启动时先做这些词

数据截面：2026-10-29，PXAny／Google 规划师口径。CPC 为页首出价低/高值，USD，**不是实际获客费**；Ads competition 是广告竞争，不能代替 SEO 难度。SERP 以预跑最终表为准，**全部样本不足十条**；大站分类含平台/商店及样本 DR≥60 的站，UGC 含论坛、视频和代码社区。[完整数据与来源说明](evidence/keyword-serp-full.md)

|关键词／市场语言|月搜|12月趋势|KD／KGR|CPC低/高；广告竞争|SERP构成与年龄线索|最弱占位|意图／页面／优先级|
|---|---|---|---|---|---|---|---|
|[epub to audiobook](evidence/final-judgments.json)／US英语|390（返回正数）|已取得，见趋势表|未取得／未取得|$1.39–$4.97；MEDIUM|大站6／独立0／社区3；样本9条；18个月新域名0个；不采信：疑似丢词|未取得（结果意图异常）|文件转换；首页，P0|
|[convert epub to audiobook](evidence/final-judgments.json)／US英语|70（返回正数）|未取得|未取得／未取得|$1.59–$4.89；MEDIUM|大站0／独立5／社区3；样本8条；18个月新域名3个|[eist.app](https://eist.app/blog/how-to-listen-to-epub-files-as-audiobooks) DR3；同DR3另有转换站voice-generator.com，Eist偏阅读器|文件转换；首页，P0|
|[pdf to audiobook](evidence/final-judgments.json)／US英语|880（返回正数）|已取得，见趋势表|未取得／未取得|$1.19–$5.92；MEDIUM|大站2／独立1／社区5；样本8条；18个月新域名1个|[voicebrief.io](https://voicebrief.io/blog/how-to-convert-pdf-to-audiobook) DR17|文件转换；PDF工具页，P0|
|[convert pdf to audiobook](evidence/final-judgments.json)／US英语|170（返回正数）|已取得，见趋势表|未取得／未取得|$1.63–$8.10；MEDIUM|大站2／独立3／社区3；样本8条；18个月新域名1个|[voicebrief.io](https://voicebrief.io/blog/how-to-convert-pdf-to-audiobook) DR17|文件转换；PDF工具页，P0|
|[epub to m4b](evidence/final-judgments.json)／US英语|10（返回正数）|未取得|未取得／未取得|$0.00–$0.00；LOW|大站4／独立1／社区4；样本9条；18个月新域名0个；不采信：疑似丢词|未取得（结果意图异常）|文件转换；M4B指南/工具入口，P1|

**先做哪5个词、放哪页：** 首页承接 `epub to audiobook`＋`convert epub to audiobook`；PDF 页承接 `pdf to audiobook`＋`convert pdf to audiobook`；M4B 页承接 `epub to m4b`。先做好这三个真实可用页面，避免一词一页。

**不做的词：** `text to speech`、`tts` 是更大且不同的输入任务；品牌替代词容易吸来只需阅读器的人；`mp3 to m4b` 输入已经是音频；Kindle/Audible 去 DRM、作者商用发行不在本次任务内。这些相邻机会只列表，不贡献本任务搜索量、付费或竞争分。

**补查与缺口：** 已用公开搜索复核 PDF/EPUB 转有声书、EPUB→M4B、AI audiobook generator 的结果意图；它们不是指定国家的 Google 完整前十。美国 `epub to audiobook`、`epub to m4b` 的预跑结果疑似丢词，不能据它判红海；三个 converter 同义词月搜仍未返回。认证接口补查因 DNS 失败，未补齐十席。[补查样本](evidence/web-core-serpcheck.json) · [接口失败](evidence/volume-recheck-error.json)

## 词族与红海处理

**宽词必须覆盖，但不能把作者出版需求加到个人转换任务里。** 下表为已查询的头部和工具形态词；宽词中只有上传现成电子书并下载自用音频的部分对口，因此不合计成主任务规模。[原始与最终表](evidence/final-judgments.json)

|父词/形态词（美国英语）|月搜状态|CPC低/高|处理|
|---|---|---|---|
|[audiobook maker](evidence/final-judgments.json)|590（返回正数）|$1.25–$5.31|P2，混合个人转换与作者制作；不绑首页、不合计市场量|
|[audiobook generator](evidence/final-judgments.json)|210（返回正数）|$1.27–$5.90|P2，混合个人转换与作者制作；不绑首页、不合计市场量|
|[ai audiobook generator](evidence/final-judgments.json)|260（返回正数）|$1.77–$8.21|P2，混合个人转换与作者制作；不绑首页、不合计市场量|
|[ai audiobook maker](evidence/final-judgments.json)|50（返回正数）|$1.37–$4.91|P2，混合个人转换与作者制作；不绑首页、不合计市场量|
|[ai audiobook creator](evidence/final-judgments.json)|30（返回正数）|$2.04–$8.53|P2，混合个人转换与作者制作；不绑首页、不合计市场量|
|[pdf to audiobook app](evidence/final-judgments.json)|10（返回正数）|$1.63–$8.02|PDF页同义词，先不另建App/软件页|
|[pdf to audiobook software](evidence/final-judgments.json)|10（返回正数）|$0.00–$0.00|PDF页同义词，先不另建App/软件页|
|[ebook to audiobook app](evidence/final-judgments.json)|10（返回正数）|$0.00–$0.00|偏阅读器，P2，不另起页|
|[ai audiobook software](evidence/final-judgments.json)|未返回|$0.00–$0.00|已查核心SERP；原0无法认证，P2暂不投入|
|[audiobook generation software](evidence/final-judgments.json)|未返回|$0.00–$0.00|已查核心SERP；原0无法认证，P2暂不投入|
|[online audiobook generator](evidence/final-judgments.json)|未返回|$0.00–$0.00|已查核心SERP；原0无法认证，P2暂不投入|
|[epub to audiobook converter](evidence/final-judgments.json)|未返回|未取得–未取得|转换同义词，首页正文承接；量未返回也已查SERP|

宽词观察：`ai audiobook generator` 8条样本＝大站5／独立工具商2／社区1，独立站最低DR14；`audiobook maker` 9条＝大站6／独立3，最低DR14。它们有工具意图，但期望功能更宽，不据此提高本任务竞争分。[最终构成](evidence/final-judgments.json)

首页只绑定 EPUB 文件转换，不用 `ai audiobook generator` 同时承接创作、配音、出版三种任务。格式与导入指南应链接回转换工具，而不是靠低量格式词撑整站。

**主词暂不能判“前十全被大站占满”**：PDF 结果里有独立低 DR 站，EPUB 主词结果又有意图异常。宽词竞争与需求混杂时，先比较以下同任务尾词，不以年轻域名推导排名容易。[最终SERP](evidence/final-judgments.json)

| 替代词／美国 | 月搜状态 | 最弱占位与边界 | 意图一致？ | 页面 |
|---|---|---|---|---|
| convert epub to audiobook | 70，返回正数 | Eist DR3 是阅读器内容页；Voice-generator DR3 为转换页；8条样本 | 文件→音频，对口；下载格式需说明 | 首页 |
| convert pdf to audiobook | 170，返回正数 | VoiceBrief DR17；8条样本 | 对口，也混有朗读需求 | PDF页 |
| epub to audiobook converter | 未返回 | Voice-generator DR3、AudiobookGen DR4；8条样本 | 更偏工具，适合作首页同义词 | 首页 |
| epub to m4b | 10，返回正数 | 9条样本疑似丢词，最弱占位未取得 | 任务很纯，量少且SERP待补 | 格式指南＋转换入口 |

以上每项来源：[逐词量、DR与落地页](evidence/final-judgments.json)。低 DR 只描述样本，链接预算仍未取得。

**对标内页能学什么：** LibriTalk 已做 `/epub-to-audiobook`、`/pdf-to-audiobook`、`/epub-to-m4b` 与比较页；预跑可见它的 EPUB 页出现在美国 `ebook to m4b` 的第6位，该词月搜不能认证为0，也不能当拉量证明。VoiceBrief 的 `/blog/how-to-convert-pdf-to-audiobook` 出现在美国 PDF 主词第1位。**对标各内页真实流量、全站出词、来源占比均未取得**，只能说看到了落地页。[LibriTalk内页](https://libritalk.com/epub-to-audiobook) · [VoiceBrief内页](https://voicebrief.io/blog/how-to-convert-pdf-to-audiobook) · [排名快照](evidence/final-judgments.json)

**市场顺序：** 先英文，再西语。PDF 主词在 US／UK／CA／AU 分别为880／110／210／90；西班牙 `pdf a audiolibro` 为320，但SERP含未解析跳转，不能直接判竞争。其它市场完整代表词见附录；日、韩、荷没有可用正数，**不等于需求为零**。[各国数据](evidence/final-judgments.json)

## 趋势：有历史月量，Google Trends 未取得

Google Trends 美国 [1年](https://trends.google.com/trends/explore?date=today%2012-m&geo=US&q=pdf%20to%20audiobook%2Cepub%20to%20audiobook)／[5年](https://trends.google.com/trends/explore?date=today%205-y&geo=US&q=pdf%20to%20audiobook%2Cepub%20to%20audiobook)：**未取得**，页面未能读取。不能据此判断增长或衰退。

初筛留存了三词的逐月量，区间为2025-10至2026-09，不是实时需求预测。PDF 主词先降后回升；EPUB 多数月份为390，但并非全年都390。[逐月归档](evidence/keyword-monthly-trends.json) · [供应商接口](https://api.pxany.com/v1/keyword-volumes)

|月份|pdf to audiobook|epub to audiobook|convert pdf to audiobook|来源|
|---|---:|---:|---:|---|
|2025-10|1300|390|210|[归档](evidence/keyword-monthly-trends.json)|
|2025-11|880|320|210|[归档](evidence/keyword-monthly-trends.json)|
|2025-12|590|260|140|[归档](evidence/keyword-monthly-trends.json)|
|2026-01|1000|390|260|[归档](evidence/keyword-monthly-trends.json)|
|2026-02|1000|320|170|[归档](evidence/keyword-monthly-trends.json)|
|2026-03|1000|390|170|[归档](evidence/keyword-monthly-trends.json)|
|2026-04|880|390|140|[归档](evidence/keyword-monthly-trends.json)|
|2026-05|720|390|140|[归档](evidence/keyword-monthly-trends.json)|
|2026-06|590|390|170|[归档](evidence/keyword-monthly-trends.json)|
|2026-07|590|390|140|[归档](evidence/keyword-monthly-trends.json)|
|2026-08|720|390|140|[归档](evidence/keyword-monthly-trends.json)|
|2026-09|1000|390|210|[归档](evidence/keyword-monthly-trends.json)|

## 需求原声：有求助，章节下载的刚需仍要单独验

日期和赞/评论数采用10月28日 Arctic Shift 归档的北京时间；网页正文能打开的已复核。热度是快照，不是当前数。[归档与方法](evidence/reddit-audit.json)

| 用户／日期／快照热度 | 原声、卡在哪一步 | 现用工具与付款 | 能证明什么 |
|---|---|---|---|
| 想转换教材的读者；2026-10-09；0赞／32评 | “though I have never tried it”；评论又说明不会安装 GitHub 项目，并称 ElevenReader 的 PDF 提取差 | 询过 Speechify，试过 ElevenReader；未找到付款 | 需求与免安装、提取纠错缺口存在；不能证明章节下载会收费。[原帖](https://www.reddit.com/r/audiobooks/comments/1x1gzyn/speechify_alternatives/) |
| 公交通勤学生；2026-09-09；0赞／27评 | 想把 PDF 转成音频；在评论说更想要免费版，并准备找现成有声书 | 未找到已付费工具 | 有通勤场景，也有免费和现成音频替代，不能把这位用户直接算付费线索。[原帖](https://www.reddit.com/r/audiobooks/comments/1wayh4n/whats_the_best_pdf_to_audiobook_convertion_app/) |
| EPUB 持有者；2026-08-28；0赞／5评 | “upload a EPUB and it converts it to an audio file” | 现用工具、付款未找到 | 最贴近文件转换；未明确要求 M4B/章节。网页重开失败，正文仅从归档核对。[原帖入口](https://www.reddit.com/r/audiobooks/comments/1w07aei/) · [归档](evidence/reddit-selected.json) |
| 大文件读者；2026-10-25；0赞／4评 | 800页 PDF 该用什么工具转音频 | 现用工具、付款未找到 | 长文处理有需求，不能据页数推字符数或成本；网页重开失败。[原帖入口](https://www.reddit.com/r/audiobooks/comments/1xewht8/) · [归档](evidence/reddit-selected.json) |

本地检查找到上述4条直接求助，**都未明确同时要求章节文件并声称已付款**。这不是半年全量频次：r/audiobooks、r/ebooks 的归档时间不足半年，且原帖不一定区分“生成文件”和“在App里听”。[计数及逐帖判定](evidence/reddit-audit.json)

## 对标拆解与付费证据

### LibriTalk：产品完全对口，成交规模未找到

已核实输入 EPUB/文字 PDF、选声音、交付章节 M4B，首本受长度限制免费；之后按本报价，输出文件可带走。它已经覆盖“按本、不订阅、章节文件”这一基础卖点；扫描 PDF 要先做 OCR（图片转文字）。**真实月流量、付费人数、营收、续购率、融资：未找到**。不能把它上线和有价格当成 PMF。[官网](https://libritalk.com/) · [条款](https://libritalk.com/tos)

切入应放在转换质量与可修复性：让用户确认切章、跳过目录页脚、纠正人名读音，失败时保留已完成章节。原帖存在不会安装和 PDF 提取失败的抱怨，说明有可调查的缝隙；**这些人是否愿意另付钱尚未证明**。[抱怨及现用工具](https://www.reddit.com/r/audiobooks/comments/1x1gzyn/speechify_alternatives/)

### VoiceBrief：已核实有人付款，但出售的是学习套件

当前官网价 **$14.99/月或$99.99/年**，含原文朗读、讲解、测验、笔记等，Pro 可下载 MP3；未找到原生章节 M4B 交付证明。[当前定价](https://voicebrief.io/pricing) · [产品事实](https://voicebrief.io/product-facts)

TrustMRR 的2026-10-28更新页显示 **MRR $254、6个活跃订阅、累计收入$2,276**，并标明通过 Stripe API 验证。**6个活跃订阅不等于6个累计付费用户**，更不是为 M4B 单项付费的人数。官网当前价与验证页旧产品介绍不一致，不反算人数。真实月流量未找到；Toolmage 的 **13.6K/月**未注明统计月份和清晰口径，不作为可信流量使用。[付款规模来源](https://trustmrr.com/startup/voicebrief) · [流量线索，未采信](https://www.toolmage.com/en/compare/ai-exam-analyzer-vs-voicebrief/)

**最多三条付费相关原话：**

1. LibriTalk：“Pay once per audiobook. No subscriptions.”——**按件价／仅定价页**，不算真实成交。[来源](https://libritalk.com/)
2. TrustMRR：“Revenue is verified with Stripe API key.”——**真实订阅收入验证**，但对应学习套件，隔离于主任务付费评分。[来源](https://trustmrr.com/startup/voicebrief)
3. 初筛 Speechify 帖：“I am fine paying for the premium but I want it to be worth it.”——**意愿，非付款**；其输入是粘贴长故事，属于相邻任务，不计主评分。网页未重开，使用归档核对。[原帖](https://www.reddit.com/r/audiobooks/comments/1vqiwdg/) · [归档](evidence/reddit-selected.json)

### 按本还是订阅：先按本，不能把讨厌订阅等同于肯付费

建议先卖有字符上限的单本交付，原因是每次输出可保存、用户未证明有连续月需求，且按本报价可在生成前确定。**“全书、不限长度”会把超长文件风险留给我们。** LibriTalk 的模式是供给侧证据；Reddit 同时有希望免费的人，也有重度听众偏好不限本数订阅的帖子，后者购买的可能是内容库，不能混为文件转换的接受度。[按本对标](https://libritalk.com/) · [通勤用户偏免费](https://www.reddit.com/r/audiobooks/comments/1wayh4n/whats_the_best_pdf_to_audiobook_convertion_app/) · [内容订阅相邻讨论](https://www.reddit.com/r/tts/comments/1u4pa1p/anyone_else_completely_tired_of_the_1_credit_per/)

**成本演算，仅作明确假设：** 假设一单实际送入 TTS 的文本为50万字符，DeepInfra Kokoro 单价$0.99/百万字符，则TTS为$0.495。若采用美国 Stripe 标准本地卡费率2.9%＋$0.30，$4.99订单支付费约$0.445，合计约$0.940，尚余$4.050覆盖其它成本，**不叫净利润或实测毛利**。相同文本若只收$0.99，两项之后仅余约$0.166，稍有重做或客服就可能亏损。实际团队主体、跨境卡、税费及退款费用均须另核。[模型单价](https://deepinfra.com/hexgrad/Kokoro-82M) · [美国费率](https://stripe.com/pricing)

## AI压力测试与额外深挖

| 问题 | 核实结论／对产品的影响 |
|---|---|
| ①LibriTalk／VoiceBrief真实流量与付费人数 | LibriTalk 两项均未找到；VoiceBrief 真实流量和累计付费人数未找到，只取得6个活跃订阅的验证快照。它的套件收入不能为章节文件背书。[验证页](https://trustmrr.com/startup/voicebrief) |
| ②版权与Stripe风控 | **无DRM不等于有权转换，更不等于自动合法。** 美国版权法的复制/改编权与例外需要按具体使用判断；“仅个人使用”声明不是通行证。Stripe 禁止侵权及帮助侵权的产品和服务。最小产品限自有作品、公版或明确获准转换的文件，不做破解、代找书或公开音频库；权利声明、删除和投诉处理是产品约束，不能保证支付审核通过。[美国版权法§106–107](https://www.copyright.gov/title17/92chap1.html) · [Stripe政策](https://stripe.com/legal/restricted-businesses) · [直接对标条款](https://libritalk.com/tos) |
| 中国团队远程成交 | 软件可远程交付，但 Stripe 全球可用地区列表未列中国大陆直接开户，列有香港；现有合格主体和收款能力本次未取得，不能写“中国团队必能直接接Stripe”。[官方地区列表](https://stripe.com/global) |
| ③按本vs订阅 | 优先按本、有长度上限、试听后付费；这是验证设计。当前未找到同任务购买人群的可靠偏好比例或续费数据。到观察到重复需求后再评估订阅。[供给侧模式](https://libritalk.com/) |
| ④AI旁白反感会否影响自用 | **会影响质量预期，不能说自用就不在乎。** 反感帖既抱怨未披露AI，也抱怨重音与人物区分；自用用户主动选声可减少“被骗”的感觉，仍须试听检验。另有用户认可AI读没有有声版的书，但属于定性反馈，不能推接受率。[反例](https://www.reddit.com/r/audiobooks/comments/1v4iobz/what_are_your_ai_narrator_tells/) · [认可反馈](https://www.reddit.com/r/tts/comments/1wwgyxp/i_think_audiobooktts_is_about_to_get_weird/) |
| ChatGPT或大平台原生免费替代 | 本次未找到 ChatGPT “上传整书→逐章原文→可导入M4B”原生完整交付的官方证明；也未做账号实测，不能断言其无法做到。OpenAI API已有文本产音频能力，证明合成层可被通用能力覆盖，不能据API推断ChatGPT产品限制。[官方API](https://developers.openai.com/api/reference/resources/audio/subresources/speech/methods/create) |
| Google免费音频概览 | Google官方说明 Audio Overview 是讨论/概览，可下载音频；不能把“可下载概览”当“整书逐字章节转换”，也不能把“可下载音频”本身当壁垒。[官方说明](https://support.google.com/gemininotebook/answer/16212820?hl=en) |
| 更直接的免费压力 | ebook2audiobook 已覆盖章节与M4B；NightForge 已支持手机端离线切章和导出；Paper2Audio 有每周56小时免费生成及App离线听。免费文件导出确实存在，是否好用到让目标人群放弃付费须比较实测。[开源转换](https://github.com/DrewThomasson/ebook2audiobook) · [手机端](https://github.com/kingfish600/Audiobook-NightForge) · [免费听书](https://www.paper2audio.com/) |

**AI越强，声音与PDF结构处理越好，但竞争者同样受益。** 用户继续付钱的理由只能是少折腾、原文不漏读、错误能局部修、播放器可用和交付可靠。若免费方案在同一组目标文件上已经满足这些要求，或平台原生免费交付同等文件，应停止这个收费切口；仅做API包装不足以支撑长期收费。

## 验收节点：先付款与交付，再看SEO，指标分开

以下数量是**建议的内部实验闸门，不是行业基准或PMF证明**：先找10位确实手里有待转文件、明确要求拿走音频的陌生用户；免费短段试听后，以$4.99/50万字符上限售卖。记录每次文件解析、人工修正、合成失败、下载及退款。

| 节点 | 验什么 | 通过与停止条件 |
|---|---|---|
| 首付 | 陌生用户实际完成支付，音频可导入其播放器 | 目标先取得3位不同用户的真实首单与可用成品；若10位合格用户中0人付款，暂停该报价/交付切口；1–2人仅作继续访谈信号，不能宣布成立。排除熟人、全额返现和只生成免费样本。 |
| 复用 | 首单后是否再次上传自己的另一份文件、为什么再来 | 记录再次使用人数与文件，不把套餐内使用或重做同一文件算再次付款；观察期限随用户下一份实际待听文件确定。 |
| 再次购买／续费 | 按本看第二笔实际订单；订阅看进入下一计费期后成功扣款及退款 | 本方案按本，月续费暂不适用；不能用一次充值后第二次使用冒充复购。未来改月订阅才另设续费指标。 |
| D0→收录→出词→SEO付款 | 发布工具、sitemap与GSC Request Indexing；确认收录，再看曝光/排名和自然搜索订单 | 收录窗口、起量天数：待哥飞顾问按内页生命周期模型补。合成成本加真实人工服务成本无法被售价覆盖，或免费方案已满足目标用户时停；没有可比实付前不扩语种、不买外链。 |

## 老站内页验证

按提供的业务介绍，RapAI（rapai.video，AI说唱视频）和 burning-bridges（TikTok热梗视频）虽涉及音视频，但没有已证实的电子书清洗、切章与听书导入能力；parkcapi（停车价格）、html-to-url（静态页面发布）主题也不对口。**四站均不建议硬挂这个转书工具页**；现有后台能力未独立检查。[站点用途依据](evidence/report-format-v3.md)

如果继续验证，用不带他人商标的新域名单页，把EPUB/PDF输入、原文试听、章节成品和字符计价讲清。先通过首付闸门，再建设上述首页与两个内页。这是最小验证建议，当前没有发布网站。

## 附录

### A. 页面简报

下列为相关SERP中前三个可核对的竞品/工具商页面，**不是同一关键词完整前三名**；Title按抓取可见页面标题记录，HTML头部未单独复抓。[SERP位置](evidence/final-judgments.json)

| 页面与出处 | 可见Title／H1 | 首屏做什么 |
|---|---|---|
| VoiceBrief，PDF主词样本第1位 | Title：PDF to Audiobook Free: Convert & Download MP3；H1：How to Convert a PDF to Audiobook Free (2026 Step-by-Step) | 解释免费试听与Pro下载整份MP3，并分流OCR、朗读和章节规划。[页面](https://voicebrief.io/blog/how-to-convert-pdf-to-audiobook) |
| AudiobookGen，convert EPUB样本第2位 | Title：AI Audiobook Generator \| Convert EPUB to Audiobook in Minutes；H1：AI Audiobook Generator. | 上传自己的书，先看声音样本与价格，转换后下载MP3；不将其当M4B证明。[页面](https://audiobookgen.com/) |
| NarrationBox，convert EPUB样本第3位 | Title：Converting EPUB Book into an Audiobook Using AI；正文可见两个一级标题，后者为完整2026 Guide | 面向作者/教育者，介绍出版旁白流程；属于同词下相邻商业意图，不贡献个人转换的付费分。[页面](https://narrationbox.com/blog/converting-epub-book-into-audiobook-using-ai) |

| 我们的页 | 建议Title | H1 | H2 |
|---|---|---|---|
| `/` | EPUB to Audiobook Converter — Download M4B with Chapters | Turn Your EPUB into a Chaptered Audiobook | Check chapters and text；Hear your selected voice；Pay for this book；Download and import |
| `/pdf-to-audiobook` | PDF to Audiobook — Check Text, Keep Chapters, Download | Convert a Text PDF into an Audiobook | Check reading order；Remove page headers；Fix chapter breaks；Download M4B or chapter MP3s |
| `/epub-to-m4b` | EPUB to M4B — Convert and Import Chaptered Audio | Make an M4B Audiobook from Your EPUB | What chapters contain；Check your sample；Import into your player |

第一屏应放文件选择、权利确认、真实可播放样本、输入限制和按字符报价说明；失败文件在付款前提示。播放器兼容性要实测，不能从扩展名直接保证“支持所有App”。

### B. 数据口径、缺口与修正

| 项目 | 已取得／未取得 | 对结论的影响与来源 |
|---|---|---|
| 扩词覆盖 | 612个市场×词；97个唯一核心词；220条核心市场组合均已跑SERP，另1条外围词过门槛 | 只覆盖指定11市场、8种语言；数量不是完成或市场规模指标。[审计](evidence/keyword-summary.json) |
| 搜索量状态 | 最终120条返回正数、492条未返回；显式供应商0无法确认；本批原查询组合中未查询0条 | 原脚本381条记为“供应商返回0”，但代码会把空值也写0，且原始metrics未留存；全部保守改为未返回。不得写零需求。[最终表](evidence/final-judgments.json) · [原始表](evidence/original-serp.json) |
| 补查失败与未查询 | 已实际请求接口，但DNS失败；这不把原正数清零。相邻词未作本轮主任务查询 | 未返回不是≤200；没有扩查的市场/词不冒充查询过。[错误记录](evidence/volume-recheck-error.json) |
| SERP样本 | 221组；101组9条、89组8条、31组7条，完整十条0组 | PDF主词8条；EPUB主词/EPUB→M4B疑似丢词；西语短主词有6条未解析跳转。只修正证据质量，不假装重抓十席。[最终表](evidence/final-judgments.json) |
| 域名年龄 | 保留注册日；按2026-10-29回看12/18个月，以独立域名去重 | 只为观察线索；有年轻站不代表获客容易，也不能推外链预算。部分地区注册日缺失。[明细](evidence/keyword-serp-full.md) |
| KD／KGR／链接预算 | 未取得；allintitle结果数未查询 | 不用广告竞争代替KD；经验阈值全部待项目复核，不作为扣分硬线。 |
| 趋势 | 三个词12个月归档已取得；Google Trends一年/五年未取得 | 其它词逐月趋势未取得；不由平均月搜编出趋势。[逐月原数](evidence/keyword-monthly-trends.json) |
| 流量／出词／估值 | 最大同任务站真实访问量、SEO流量词、精确来源占比、估值、Stripe引荐数据均未取得 | 不采信无统计月份的流量数字，不拿Speechify全品类流量填空；公开收入与估值是两回事。 |
| PMF、成本、实测 | 同任务真实付款、复购、净成本、转换质量实测未取得 | 价格、开源功能声明和理论算式均不能代替这些验证；暂缓完整站。 |
| 初筛五项原分 | 未找到 | 已有初筛报告和必填任务/关键词/证据类型；无法完成原分逐项差值比较，保留“未找到”。[源卡](evidence/source-handoff.md) |

**修正初筛三处推断：** CPC和Ads competition不能证明“长期有人投放”；低DR和域名年轻不能证明外链要求低；在用Speechify和愿意买premium不能证明已为章节文件付款。均已在最终报告中撤去相应推断。[初筛原文](evidence/source-demand.md)

### C. 各国代表词与全量表

|市场／当地语言|代表词|月搜状态|建议|
|---|---|---|---|
|US／en|pdf to audiobook|880（返回正数）|先做英文|
|UK／en|pdf to audiobook|110（返回正数）|英文共用，暂不拆国家页|
|CA／en|pdf to audiobook|210（返回正数）|英文共用，暂不拆国家页|
|AU／en|pdf to audiobook|90（返回正数）|英文共用，暂不拆国家页|
|DE／de|pdf in hörbuch umwandeln|50（返回正数）|P2，量小先不扩|
|FR／fr|convertir epub en livre audio|10（返回正数）|P2，量小先不扩|
|ES／es|pdf a audiolibro|320（返回正数）|P2，英文交付有实付后再测|
|IT／it|convertire pdf in audiolibro|10（返回正数）|P2，量小先不扩|
|NL／nl|pdf omzetten naar luisterboek|未返回|P2，先不扩；未知量不能按0处理|
|JP／ja|pdf オーディオブック 変換|未返回|P2，先不扩；未知量不能按0处理|
|KR／ko|pdf 오디오북 변환|未返回|P2，先不扩；未知量不能按0处理|

各行来源：[最终关键词表](evidence/final-judgments.json)。日/韩/荷未找到可信正数量，未用英语硬套当地市场。完整扩词、各国量/CPC、SERP逐条和不足十席标注见 [全量附表](evidence/keyword-serp-full.md)；核心词见 [core.txt](kw/core.txt)，[英语](kw/en.txt)、[德语](kw/de.txt)、[法语](kw/fr.txt)、[西语](kw/es.txt)、[意语](kw/it.txt)、[荷语](kw/nl.txt)、[日语](kw/ja.txt)、[韩语](kw/ko.txt)。相邻机会仅列表于 [adjacent.txt](kw/adjacent.txt)。

### D. Reddit方法与证据等级

先选相关中小社区 r/TTS；r/audiobooks、r/ebooks 较大，使用初筛已有归档补充。本轮 Arctic 请求及稍后重试均DNS失败，没有换IP；随后用 site:reddit.com 与完整原帖地址核对。引用原帖时打开正文，无法打开的明确标归档来源。[失败记录](evidence/arctic-probe-error.json) · [重试](evidence/arctic-retry-error.json)

| 社区归档 | 帖子数 | 北京时间覆盖 | 限制 |
|---|---:|---|---|
| r/audiobooks | 2500 | 2026-07-07至10-28 | 不满半年，上游日志有422错误，不能叫近半年全量 |
| r/ebooks | 1500 | 2026-09-16至10-28 | 不满半年，开发者自荐多 |
| r/TTS | 145 | 2026-04-29至10-26 | 日期跨度覆盖半年目标的主要区间，最新几天未取得；不宣称抓取无遗漏 |

数据源：[覆盖审计](evidence/reddit-audit.json)；帖子语义筛选后57条候选＝56条正则召回＋1条初筛种子帖，已按 [点赞](evidence/reddit-ranked-score.json) 和 [评论](evidence/reddit-ranked-comments.json) 分别排序。人工仅把4条列作直接转换求助，2条仅标题不足，其余为自荐、已有音频同步/播放等相邻内容。痛点计数以帖子为单位、未做作者去重；不推总体发生率，不把自荐数量算需求强度。网页评论只定性核对，不伪造评论全量统计。[逐帖判定](evidence/reddit-candidates.json)

评级：官网功能与价格＝供给证据；用户说愿付＝意愿；Stripe验证页＝该产品收入证据；当前任务的独立付款和复购仍未找到。所有研究网页摘录及失败信息保存在 evidence 内，证据包不包含密钥。

### E. 用时与交付

时区：Asia/Shanghai。扩词与预跑从2026-10-28 22:50:44开始，关键词完成于22:54:17；SERP结束于2026-10-29 00:48:31。报告调查从00:48:31至2026-10-29 01:20:54，墙钟1943秒；全流程墙钟9010秒。[计时记录](evidence/timing-final.json) · [原始日志](evidence/original-timing.txt)

报告、命名副本与SERP摘要使用同一份最终判定数据。未创建公开网页，公开链接未取得；本次交付本地Markdown及可携带的证据包。
