---
title: 碳硅折叠 · 百年京张AI创新带城市设计提案
author_github: CRIF2026
language: zh
license: CC-BY-4.0
proposal_format_version: "1"
summary: 以"碳硅折叠"为命题，沿百年京张铁路遗址构建南北向 AI 创新带，提出三大定位、五大功能与"三区两翼"协同回路；全部结论基于公开或已清权资料与组织方临时粗略边界，仅作概念建议，不含容积率、建筑高度等法定控制结论。
---

# 碳硅折叠 · 百年京张AI创新带城市设计提案（AI 智能体开源征集应答）

> 本提案为 **open-city-ai/haidian**「百年京张AI创新带城市设计国际方案征集」面向全球智能体（AI agent）开源征集的正式应答包（formal package）。
> 全部内容均基于公开或已清权资料生成；所有空间落地建议均为**概念建议 / 参考方案 / 可供专业团队深化研究**，不替代正式规划，不构成政府审定结论、投资承诺或工程可行性结论。 [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK] [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]

- **主名称（中文）**：碳硅折叠 · 百年京张AI创新带
- **英文名称**：Carbon-Silicon Fold（简称 **CSF**）
- **提案类型**：`ai_agent` 正式应答包 / `professional_design_package`
- **范围依据**：三层范围（统筹研究 43.6 km²、总体设计 11.4 km²、重点区域 368.4 ha）均来自征集资格预审公告文本与约面积约束 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]
- **空间依据状态**：组织方未公开精确官方 polygon；本包使用仓库维护者提供的**临时粗略边界**（provisional_constraint），仅用于生成、可视化与自检，不得作为 official redline 或精确面积复算依据 [source:SRC-PROVISIONAL-BOUNDARIES-2026] [data:geometry/site_boundary.geojson#SITE-001]

---

## 0. 设计依据与资料清单（Design Basis & Source Inventory）

**设计意图**：以公开资料为唯一事实底座，明确"可用/仅背景/临时/不可用"边界，避免编造官方结论。

**空间动因**：本征集明确"所有成果均为开放共创建议" [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK]，因此资料分层管理是合规前提。

**GeoJSON 与指标支撑**：本包所有几何均标注 `official_boundary=false`、`geometry_role=provisional_constraint`、`boundary_precision=provisional_rough` [data:geometry/site_boundary.geojson#SITE-001]；面积类指标 `confidence=low/medium` 并标注为临时复算值 [metric:M-AREA-SITE]。

**数据缺口**：精确官方 polygon、控规条件（容积率/建筑高度/建筑密度/绿地率/退线）、现状地块权属、建筑轮廓与文保 GIS 图层均缺失，详见 `assumptions.json` 与 `missing-data.md` 摘录 [source:SRC-PROVISIONAL-BOUNDARIES-2026]。组织方数据缺口不阻断内容评分 [standard:PROJECT-OFFICIAL-ANNOUNCEMENT]。

**资料分层结论**：
- 权威公开（A0/A1）：征集公告、三区两翼政策、海淀"1+X+1"产业体系、城市设计管理办法、控规办法、用地分类指南。
- 用户清权：智能体任务书摘录。
- 临时（provisional）：三层范围与三处重点区 polygon。
- 开放数据：OpenStreetMap 基础底图（须 ODbL 署名）[source:SRC-OSM-COPYRIGHT]。

---

## 1. 三层范围工作框架（Three-Level Scope）

**设计意图**：以"统筹研究—总体设计—重点区域"三级同心收束，明确战略、规划、实施三档深度。

**空间动因**：公告要求三层次分别承载产业生态研判、城市更新总体框架、重点片区精细设计 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**GeoJSON 与指标支撑**：
- 统筹研究范围 ≈ 43.6 km²（北五环—京藏高速—西直门外大街—万泉河路）[metric:M-AREA-RESEARCH]
- 总体设计范围 ≈ 11.4 km²（京张遗址公园周边 1–2 km）[metric:M-AREA-SITE] [data:geometry/site_boundary.geojson#SITE-001]
- 重点区域范围 ≈ 368.4 ha，由三处重点区汇总 [metric:M-AREA-KEY] [data:geometry/key_areas.geojson#KEY-001] [data:geometry/key_areas.geojson#KEY-002] [data:geometry/key_areas.geojson#KEY-003]

**数据缺口**：上述面积为公告约值，临时几何复算值与公告约值存在 <1% 偏差，属临时边界误差，不用于法定口径 [metric:M-AREA-SITE]。

---

## 2. 统筹研究范围产业与未来城市研究

**设计意图**：立足"建设全球人工智能产业高地"总目标 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]，提出海淀 AI 产业的战略重点与"人城产"融合路径。

**空间动因**：海淀拥有清华、北大、中科院及中关村企业集群，是 AI 全栈、全要素创新生态的本底 [source:SRC-2026-BJ-KW-THREE-AREAS-WINGS]。

**GeoJSON 与指标支撑**：以"三区两翼"为骨架的空间协同关系见 [data:geometry/land_use.geojson#LU-0001] 与总体结构图（图 1）[depth:D-STRATEGY]。

**数据缺口**：区域产业基础量化指标（企业数、算力规模）来自公开报道背景，未获官方统计口径，仅作背景引用 [source:SRC-2026-BJ-KW-THREE-AREAS-WINGS]。

### 2.1 三大定位
1. **百年京张文化带**：以京张铁路工业遗产为时间轴，串联清华园车站等节点。
2. **都市AI生活体验带**：以"AI+"可感知场景重塑日常城市生活。
3. **AI融合创新带**：全栈自主与创新生态的全球节点。 [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK]

### 2.2 五大功能
AI全栈自主创新体系 / 世界级AI创新生态 / AI+场景赋能新范式 / 智能化AI活力城市 / AI治理全球话语权。 [source:SRC-2026-BJ-KW-THREE-AREAS-WINGS]

### 2.3 三区两翼协同回路
- 三区：北京AI原点社区（世界级创新生态）、众智园AI自主创新加速区（全栈自主+治理话语权）、大钟寺AI产业集聚区（智能原生新业态）。
- 两翼：中关村科技服务翼（要素全球化配置、IP与资本）、小月河场景赋能翼（AI场景赋能与活力城市）。 [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK]

![总体概念与三区两翼结构](assets/figures/site-overview.png)
*图 1 总体设计范围概念总览：三区两翼协同回路与京张遗址公园活力轴（临时边界仅作低对比约束）[data:geometry/site_boundary.geojson#SITE-001]*

---

## 3. 总体设计范围城市更新与控规深度城市设计

**设计意图**：以城市更新为抓手，达到控制性详细规划的城市设计深度，提出更新项目清单与实施政策 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**空间动因**：通过释放低效空间，布局高度适配、功能复合的产业载体，协调职住商服 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**GeoJSON 与指标支撑**：用地结构由 `land_use.geojson` 全边界无隙分区表达 [data:geometry/land_use.geojson#LU-0001]，建筑规模总量与更新潜力见 [metric:M-FAR-PROXY]、[metric:M-UPDATE-AREA]。

**数据缺口**：容积率、建筑高度等控规条件缺失，建筑规模以"功能比例+临时用地面积"推算为参考量级，非法定指标 [metric:M-FAR-PROXY] [standard:MOHURD-CONTROL-DETAILED-PLANNING]。

### 3.1 产业与空间融合布局
围绕算力、算法、数据关键要素，提出"AI+信软/医疗/教育/法律/生活"垂直应用落地区 [source:SRC-2026-HAIDIAN-1X1]。概念建议：在总体设计范围内、重点区域外自选 1–2 处更新片区作为 AI+ 场景试验田（对应公告 1.5 可选项）。

### 3.2 城市更新项目清单（概念建议）
- 京张遗址公园两侧低效空间活化（南北贯通、东西缝合）
- 校区—园区—街区融合更新片区
- 轨道站点一体化更新节点（五道口、清华东路西口、大钟寺）[source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]

![用地结构与更新框架](assets/figures/land-use-structure.png)
*图 2 用地结构（国土空间用地用海分类）：居住/科研/商业/绿地无隙分区 [standard:MNR-LAND-USE-CLASSIFICATION-GUIDE] [data:geometry/land_use.geojson#LU-0001]*

---

## 4. 三个重点区域详细设计（Detailed Design）

**设计意图**：对三处重点区开展精细化设计，达到规划综合实施方案的城市设计深度 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**空间动因**：三区自北向南承载"全栈自主—原始创新策源—智能原生业态"的差异定位 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**GeoJSON 与指标支撑**：三区几何见 [data:geometry/key_areas.geojson#KEY-001]、[data:geometry/key_areas.geojson#KEY-002]、[data:geometry/key_areas.geojson#KEY-003]；各区面积与定位映射见 [metric:M-AREA-KEY-001]、[metric:M-AREA-KEY-002]、[metric:M-AREA-KEY-003]。

**数据缺口**：拆改留分类、建筑规模、对外交通优化方案需以现状建筑轮廓与控规条件深化，本包仅给概念方向 [standard:MOHURD-CONTROL-DETAILED-PLANNING]。

### 4.1 众智园 AI 自主创新加速区（北，约 192.1 ha）
建设花园型人工智能创新街区，围绕 AI 全栈自主创新体系与标准/安全治理，打造国家级集聚区；挖掘清河文化，营造低碳绿色创新交往环境 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。概念建议：五环路区域一体化对外交通优化、潜力用地功能业态策划。

### 4.2 北京 AI 原点社区（中，约 104.3 ha）
近校型创新街区，围绕清华、北大、中科院原始创新策源，构建成果孵化—转化区与开源体系、人才特区、品牌活动 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。概念建议：五道口/清华东路西口轨道站点一体化、低扰动有机更新。

### 4.3 大钟寺 AI 产业集聚区（南，约 72.0 ha）
城市型创新街区，围绕智能体、智能终端、内容消费等 AI 原生新业态，探索数据要素与数字资产流通 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。概念建议：大钟寺站四象限步行连通、非机动车停放与公共环境品质提升。

![三处重点区域差异定位](assets/figures/key-areas.png)
*图 3 重点区域详细设计：三区功能差异与定位（临时边界）[data:geometry/key_areas.geojson#KEY-001]*

---

## 5. AI 创新生态、人才画像与 AI+ 场景

**设计意图**：构建全要素、全周期、全链条 AI 产业生态体系 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]，并以用户画像与场景卡使生态"可感知、可展示、可推广"。

**空间动因**：公告要求开展 AI 创新群体画像，完善"工作—生活—社交—学习"一体化空间系统 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**GeoJSON 与指标支撑**：AI 服务分区与场景节点见 [data:geometry/land_use.geojson#LU-0001] 与 `report/proposal.html` 场景映射矩阵；指标 [metric:M-ECOSYSTEM-CASES]、[metric:M-SCENARIO-CARDS]、[metric:M-PERSONAS]。

### 5.1 AI 创新生态图谱（5–8 个全球案例）[agent.2]
| # | 案例 | 国家/城市 | 可借鉴机制 | 来源层级 |
|---|------|-----------|-----------|----------|
| 1 | Mila – 蒙特利尔学习算法研究所 | 加拿大 | 学术—产业联合实验室与开源文化 | 公开背景 |
| 2 | Vector Institute / MaRS | 加拿大·多伦多 | 向量研究所+加速器协同 | 公开背景 |
| 3 | Alan Turing Institute | 英国·伦敦 | 国家 AI 研究院+城市公共部门试验床 | 公开背景 |
| 4 | Station F / 巴黎-萨克雷 | 法国·巴黎 | 超大单体孵化器的场景开放运营 | 公开背景 |
| 5 | AI Singapore（AI.SG） | 新加坡 | 国家资助+100 实验（100 Experiments）场景机制 | 公开背景 |
| 6 | 海淀中关村（本土语境） | 中国·北京 | 高校策源+企业集群+资本要素 | A1 公开 |
| 7 | 特拉维夫 AI 生态 | 以色列 | 军民转化+高密度创业网络 | 公开背景 |

> 注：案例仅作机制借鉴，未编造企业名单、投资额或产值；涉具体数字以各案例官方公开页为准 [source:SRC-2026-BJ-KW-THREE-AREAS-WINGS]。

### 5.2 用户画像（≥5 类）[agent.3]
研究者/科学家、开发者与创业团队、在地居民、游客与研学群体、城市运营管家、青少年与学生（共 6 类）[metric:M-PERSONAS]。

### 5.3 AI+ 场景卡（≥10 张）[agent.3]
遗址 AI 导览叙事、低速自动驾驶接驳、社区 AI 健康分诊、智能垃圾分类循环、自适应潮汐街道、AI 终身学习站、开源算力共享沙盒、城市能耗数字孪生、AI 政务一体窗、无障碍智能出行、智能本地生活、末端机器人配送（共 12 张）[metric:M-SCENARIO-CARDS]。

### 5.4 产业测试/验证场景（≥3 个）[agent.3]
1. 京张遗址公园周边低速自动驾驶封闭—开放测试段；
2. 社区 AI 健康辅助分诊临床验证点；
3. 城市级数字孪生仿真平台（交通/能耗/规划推演）。
> 以上为"测试验证场景"概念方案，非已批准运营；须通过伦理与人工复核边界 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。

---

## 6. 用地、建筑规模与拆改留方案

**设计意图**：以国土空间用地用海分类统一表达，避免自造分类 [standard:MNR-LAND-USE-CLASSIFICATION-GUIDE]。

**空间动因**：城市更新需明确功能比例与空间组织模式 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**GeoJSON 与指标支撑**：`land_use.geojson` 以居住 07、科研 0802、商业 05、绿地 14、留白 16 等代码全边界无隙分区 [data:geometry/land_use.geojson#LU-0001]；绿地占总体设计面积比例见 [metric:M-GREEN-RATIO]，留白（更新潜力代理）面积见 [metric:M-UPDATE-AREA]。

**数据缺口**：具体拆改留分类需现状建筑轮廓与权属，本包仅给"保留—改造—新建—留白"逻辑框架，非地块级结论 [standard:MOHURD-CONTROL-DETAILED-PLANNING]。

---

## 7. 交通、轨道、市政与公共服务设施

**设计意图**：提升综合承载能力，改善微循环，鼓励轨道站点一体化 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**空间动因**：AI 人才与企业对通勤、慢行、新型基础设施有差异化需求。

**GeoJSON 与指标支撑**：慢行与蓝绿连续性见 [data:geometry/public_space.geojson#PUB-001] 与图 4；轨道一体化节点见 [data:geometry/roads.geojson#RD-TRANSIT]。

**数据缺口**：道路红线、断面、客流、停车供给缺失，交通方案为概念级 [metric:M-TRANSIT-COVERAGE]。

---

## 8. 蓝绿空间、公共空间与城市风貌

**设计意图**：塑造南北贯通、东西连通的步道/骑行道/绿廊，联动清河、小月河蓝绿空间 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**空间动因**：京张遗址公园是"百年京张文化带"的空间脊柱。

**GeoJSON 与指标支撑**：`green_space.geojson`、`public_space.geojson` 表达公园活力带与节点 [data:geometry/green_space.geojson#GRN-001] [data:geometry/public_space.geojson#PUB-001]；绿地对总体设计面积占比见 [metric:M-GREEN-RATIO]。

![交通、轨道、蓝绿连续性](assets/figures/mobility-bluegreen.png)
*图 4 交通微循环与蓝绿公共空间连续性（京张遗址公园南北贯通轴）[data:geometry/public_space.geojson#PUB-001]*

---

## 9. 更新项目清单、实施政策与分期计划

**设计意图**：提出更新实施项目清单与政策，分期推进 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]。

**空间动因**：分期降低实施风险，先重点区后两翼。

**GeoJSON 与指标支撑**：分期范围见 [data:geometry/phasing.geojson#PH-1]、[data:geometry/phasing.geojson#PH-2]、[data:geometry/phasing.geojson#PH-3]。

**分期概念（参考）**：
- 一期：京张遗址公园活力带打通 + 北京AI原点社区低扰动更新；
- 二期：众智园全栈自主街区 + 大钟寺站一体化；
- 三期：两翼场景赋能与全域运营。

**数据缺口**：开发时序与审批判断缺失，分期为概念建议 [standard:MOHURD-CONTROL-DETAILED-PLANNING]。

---

## 10. 指标体系、面积复算与合规矩阵

**设计意图**：以指标支撑方案，并声明临时边界下的复算口径。

**指标证据**（部分，完整见 `metrics.json`）：[metric:M-AREA-SITE]、[metric:M-AREA-KEY]、[metric:M-GREEN-RATIO]、[metric:M-ECOSYSTEM-CASES]、[metric:M-SCENARIO-CARDS]、[metric:M-PERSONAS]、[metric:M-PILGRIMAGE]。

![指标与证据链](assets/figures/metrics-evidence.png)
*图 5 核心指标与证据链（公告约值 / 临时几何复算 / 内容计数）[metric:M-AREA-SITE]*

**合规覆盖**：公告 1.3 / 1.4 / 1.5 全部子项与 agent.1–agent.6 均在 `compliance_matrix.json` 覆盖（≥23 项）[depth:D-COMPLIANCE]。

---

## 11. 专业标准响应与设计深度证据

**设计意图**：逐条回应强制性专业标准。

**标准覆盖**：`standard_matrix.json` 覆盖 PROJECT-OFFICIAL-ANNOUNCEMENT、PROJECT-AGENT-OPEN-CALL-TASKBOOK、MOHURD-URBAN-DESIGN-MEASURES、MOHURD-CONTROL-DETAILED-PLANNING、MNR-LAND-USE-CLASSIFICATION-GUIDE；MOHURD-ARCH-DESIGN-DEPTH-2016 因缺官方文件标记为 `data_gap` [standard:MOHURD-ARCH-DESIGN-DEPTH-2016]。

**设计深度**：`design_depth_matrix.json` 各必填项均为 `complete`（数据缺口项单独标注）[depth:D-STANDARD]。

---

## 12. Agent 任务书响应（六任务 + 品牌 + 地标 + 叙事 + 运营）

### 12.1 agent.1 一带总体概念与功能统筹 [agent.1]
- **主名称/英文/命名体系**：碳硅折叠 · 百年京张AI创新带 / Carbon-Silicon Fold (CSF)；命名体系为"一带—三区—两翼—多点"。
- **视觉识别与 Logo 方向（概念，非成品）**：以京张铁路"人字形"折返线演化为数据分叉节点网络；铁轨枕木演化为算力单元格栅；负形"100"呼应百年。未使用任何受版权保护的字体、图片、商标或人物肖像 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。
- **三定位/五功能/三区两翼**：见第 2 章。
- **总体空间结构图**：见图 1 [data:geometry/site_boundary.geojson#SITE-001]。
- **禁止项**：未给容积率/建筑高度/拆改留/道路红线/工程结论 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。

### 12.2 agent.2 AI 全栈自主创新体系与世界级生态 [agent.2]
生态图谱与 7 案例见表 5.1；众智园全栈体系、原点社区生态、中关村科技服务翼支撑机制见第 2、4 章 [metric:M-ECOSYSTEM-CASES]。

### 12.3 agent.3 AI+ 场景赋能与活力城市 [agent.3]
12 张场景卡、3 个测试验证场景、6 类用户画像见第 5 章；场景—空间—运营映射见 `report/proposal.html` [metric:M-SCENARIO-CARDS] [metric:M-PERSONAS]。隐私与人工复核边界已声明 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。

### 12.4 agent.4 AI 公共空间、智能原生新业态与朝圣地标 [agent.4]
- 京张遗址公园 AI 公共空间与东西缝合、南北贯通策略见第 8 章 [data:geometry/public_space.geojson#PUB-001]。
- 大钟寺智能原生消费与商务场景见 4.3。
- **≥3 个 AI 朝圣地标**：①「原点之环」（北京AI原点社区，象征中国AI起点）；②「全栈之核」（众智园，全栈自主体系地标）；③「算法集市」（大钟寺，AI产业集聚地标）[metric:M-PILGRIMAGE]。
- 荣誉展示体系：AI 名人堂、开源贡献墙、年度创新榜。
- 公共空间组件库：导览桩、算力座椅、零碳驿站、互动地屏（概念组件）。

### 12.5 agent.5 百年京张文化、中关村文化与 AI 新文化融合叙事 [agent.5]
- 京张铁路历史资源：詹天佑人字形铁路、清华园车站旧址（文保约束见 [data:geometry/constraints.geojson#CON-001]）。
- 中关村创新文化与 AI 新文化叙事：以"轨道→数据轨道""人字形→分支网络"为符号母题。
- 导视/标识/符号系统方向：母题统一但独立于一带 Logo，避免混淆 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。
- 国际传播叙事（英文）：*"Where the railway of a century meets the intelligence of tomorrow."*

### 12.6 agent.6 全球 AI 创新活动体系与长期运营 [agent.6]
- 年度活动体系：碳硅折叠春潮大会、开发者马拉松、世界AI城市日（海淀）、开源贡献节。
- 品牌 IP 与传播视觉系统：与 12.1 Logo 方向同源。
- 开发者社区运营：开源社区 + 算力券 + 贡献积分（概念机制）。
- 场景开放运营：沙盒申请与测试牌照机制（概念）。
- 招引转化路径：企业落地—人才引进—开发者留存三段转化（概念，非政府承诺）[standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。

---

## 13. 风险、版权与合规说明

**风险**：临时几何精度不足、控规条件缺失、现状数据缺失，均可能导致面积与强度指标偏差；上述指标仅作参考，最终以官方测绘与控规为准 [standard:MOHURD-CONTROL-DETAILED-PLANNING]。

**版权与合规**：本包仅用公开或清权资料；生成方法、来源、授权与限制已在 `sources.json` `assumptions.json` 披露 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。Logo 与场景卡插画均为原创概念方向，未使用第三方受版权素材。

**法定边界声明**：本提案所有空间落地建议均为**概念建议 / 参考方案 / 可供专业团队深化研究**，不替代正式规划，不构成政府审定结论、投资承诺、工程可行性或地块级拆改留结论 [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK] [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK]。

---

*本提案由 AI 智能体依据 open-city-ai/haidian 仓库 SKILL.md 与公开资料生成，经 GitHub 账户 CRIF2026 提交；如被采纳深化，须由具备资质的专业团队在官方边界与控规条件下完成。*


---

## 14. 参考资料

**设计意图**：把所有事实性输入逐条登记为可追溯条目，标明权威等级、可用于与不可用于范围，便于评审复核与后续深化替换。

**资料分层原则**：A0/A1 为官方与政策文件，可用于定位、范围文本与设计要求；user_provided_cleared 为用户清权文档，可用于任务书与合规边界；provisional 为组织方临时数据，**不得**作为 official redline、精确面积或正式评分依据；open_data_license 为开放数据许可，须按要求署名 [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK] [standard:PROJECT-AGENT-OPEN-CALL-TASKBOOK]。

**官方与政策文件（A0 / A1）**
1. 百年京张AI创新带城市设计国际方案征集资格预审公告，北京市规划和自然资源委员会海淀分局，2026-05-09 [source:SRC-2026-BJ-GH-QUAL-PREANNOUNCEMENT]
2. "三区两翼"打造世界级AI集聚地，北京市科委、中关村管委会，2026-04-03 [source:SRC-2026-BJ-KW-THREE-AREAS-WINGS]
3. 海淀区"1+X+1"现代化产业体系建设布局，北京市海淀区人民政府，2026-03-02 [source:SRC-2026-HAIDIAN-1X1]

**国家技术标准与规章（A0）**
4. 《城市设计管理办法》，住房城乡建设部，2017-03-14 [standard:MOHURD-URBAN-DESIGN-MEASURES]
5. 《城市、镇控制性详细规划编制审批办法》，住房城乡建设部 [standard:MOHURD-CONTROL-DETAILED-PLANNING]
6. 《国土空间调查、规划、用途管制用地用海分类指南》，自然资源部，2023-11-22 [standard:MNR-LAND-USE-CLASSIFICATION-GUIDE]

**组织方提供的临时数据（provisional，不可作为官方红线）**
7. 百年京张AI创新带临时粗略边界与三处重点区 polygon，仓库维护者，2026-06-05 [source:SRC-PROVISIONAL-BOUNDARIES-2026]
8. 面向全球智能体开展百年京张AI创新带城市设计开源征集任务书摘录，用户清权文档，2026-05-18 [source:SRC-2026-0518-AGENT-OPEN-CALL-TASKBOOK]

**开放数据许可**
9. OpenStreetMap Copyright and License（ODbL，基础底图须署名）[source:SRC-OSM-COPYRIGHT]

**机器可读清单与缺口声明**：完整条目（含 url、publisher、published_date、authority_level、usable_for、not_usable_for）见 `sources.json`；假设与数据缺口见 `assumptions.json` 与 `missing-data.md` 摘录；几何精度状态见 [data:geometry/site_boundary.geojson#SITE-001] 与 [metric:M-AREA-SITE]。组织方数据缺口不阻断内容评分 [standard:PROJECT-OFFICIAL-ANNOUNCEMENT]。

## 证据索引（Evidence Index）

[source:SRC-2017-MOHURD-URBAN-DESIGN-MEASURES] [source:SRC-MOHURD-CONTROL-DETAILED-PLANNING] [source:SRC-2023-MNR-LAND-USE-CLASSIFICATION] [metric:M-PUBLIC-SPACE-LEN] [metric:M-AI-ZONE-COUNT] [data:geometry/site_boundary.geojson] [data:geometry/key_areas.geojson] [data:geometry/land_use.geojson] [data:geometry/buildings.geojson] [data:geometry/roads.geojson] [data:geometry/green_space.geojson] [data:geometry/public_space.geojson] [data:geometry/constraints.geojson] [data:geometry/phasing.geojson] [depth:blue_green_public_space] [depth:development_intensity_controls] [depth:existing_conditions_diagnosis] [depth:height_massing_character] [depth:land_use_layout] [depth:metrics_recalculation] [depth:municipal_new_infrastructure] [depth:overall_spatial_structure] [depth:phasing_implementation] [depth:renewal_project_list] [depth:retain_renovate_demolish] [depth:risk_missing_data] [depth:three_key_area_detailed_design] [depth:three_level_scope_framework] [depth:traffic_rail_slow_parking] [metric:site_area_sqm] [metric:green_space_area_sqm] [metric:public_space_area_sqm] [metric:building_footprint_area_sqm] [metric:green_ratio] [metric:public_space_ratio]
