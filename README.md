# 电商运营专家团

> 抖音电商 10 岗协作技能包：一个项目，十种视角，一次会诊。

把一个电商项目拆给 10 个专业岗位**各自独立评估**，再由运营总监汇总拍板。
核心价值是**避免单点视角**——你问投放，投放只会让你加预算；10 岗会诊才会告诉你问题其实在详情页和客服口径。

- 技能名：`douyin-ecom-ops-team`
- 版本：v1.1.0
- 归属：沈艳朝（策划组-沈艳朝）｜ 维护：Emperor
- 适用：抖音电商 / 抖店矩阵 / 直播间 / 千川投放 / 生鲜与特产类目
- 仓库：<https://github.com/ITemperor/douyin-ecom-ops-team>
- 许可：MIT

> 说明：GitHub 仓库名不支持中文，「电商运营专家团」这个中文名放在项目标题与描述中，仓库 slug 用 `douyin-ecom-ops-team`（与 WorkBuddy 专家包 ID 一致）。

---

## 一、安装

### 方式 1：放到 WorkBuddy 技能目录（推荐）

```bash
# 把整个目录放到本机技能目录
C:\Users\Administrator\.workbuddy\skills\douyin-ecom-ops-team\
```

放好后**重启 WorkBuddy** 即可在技能列表中看到。

### 方式 2：从 GitHub 拉取

```bash
git clone https://github.com/ITemperor/douyin-ecom-ops-team.git \
  "C:\Users\Administrator\.workbuddy\skills\douyin-ecom-ops-team"
```

### 方式 3：作为专家包注册（多角色协作模式）

本仓库的 `agents/` + `plugin.json` 结构可直接作为 Team 型专家包注册到
`C:\Users\Administrator\.workbuddy\plugins\marketplaces\my-experts\plugins\`，注册后会在 WorkBuddy 右侧显示为「电商运营专家团」。

---

## 二、快速开始

**① 单岗直调**（问题明确时）

> "帮我写一套牛羊肉直播间的憋单话术" → 自动路由到「主播」
> "这店的详情页转化太差了" → 自动路由到「设计」
> "千川 ROI 掉到 1.2 了怎么办" → 自动路由到「千川优化师」

**② 全岗会诊**（项目/方案待评估时，默认行为）

> "我这有一款奶皮子酥想打爆，帮我从各岗位角度评估一下"

会输出：10 份岗位评估 →《全岗评估矩阵》→ 总评（是否推进 / 优先级 / 先补哪块短板）。

**③ 完整作战方案**

> "给我一套完整的开播方案，含主播话术、客服承接和利润测算"

---

## 三、10 岗职能与能力

| # | 岗位 | 花名 | Agent ID | 核心职能 | 关键能力 |
|:--:|---|---|---|---|---|
| 1 | 运营总监（主理人） | 沈运达 | `douyin-ecom-ops-team-lead` | 统筹编排、策略决策、方案拍板 | 全局操盘 / 直播间打法 / 团队调度裁决 |
| 2 | 抖店运营 | 窦振商 | `douyin-store-ops` | 日常运营、货盘、价格、体验分、售后履约 | 货盘与定价 / 体验分与履约 / 增长诊断 |
| 3 | 视频策划 | 石画策 | `video-planner` | 选题、脚本结构、创意方向、种草节奏 | 三段式脚本 / 风格匹配 / 内容排期 |
| 4 | 千川优化师 | 钱川流 | `qianchuan-optimizer` | 千川计划、出价、放量节奏、ROI 控制 | 计划搭建 / 三阶段出价 / 付费撬自然 |
| 5 | 视频剪辑 | 简艺修 | `video-editor` | 成片剪辑、节奏卡点、字幕包装 | 3 秒钩子 / 信息密度 / A/B 版本迭代 |
| 6 | 广告优化师 | 郜放 | `ad-optimizer` | 创意优化、素材测试、转化与 ROI | 创意拆解 / 素材赛马 / 漏斗漏点 |
| 7 | 主播 | 朱波 | `live-anchor` | 直播话术、节奏把控、憋单逼单 | 五段话术 / 憋单放单 / 实时调控 |
| 8 | 客服 | 顾晓 | `customer-service` | 售前转化、售后处理、差评安抚、复购 | 话术库 / 售后 SOP / 会员分层触达 |
| 9 | 会计 | 惠算 | `accountant` | 毛利核算、投流 ROI 财务口径、税务现金流 | 利润测算 / 预算红线 / 经营报表 |
| 10 | 设计 | 商美陈 | `designer` | 商品详情页、店铺装修、视觉资产体系 | 8 屏详情页 / 装修八件套 / 合规自查 |

每个岗位的完整职能、能力、工作流程、输出规范与评估模板见 **[`references/members.md`](references/members.md)**。

**单岗路由表**

| 你想问什么 | 调谁 |
|---|---|
| 直播间节奏 / 打法 / 整体操盘 | `douyin-ecom-ops-team-lead` |
| 抖店货盘 / 体验分 / 店铺运营 | `douyin-store-ops` |
| 短视频选题 / 脚本 / 创意方向 | `video-planner` |
| 千川计划搭建 / 出价 / 放量 | `qianchuan-optimizer` |
| 视频剪辑 / 成片 / 节奏 | `video-editor` |
| 广告创意 / ROI / 素材优化 | `ad-optimizer` |
| 直播话术 / 憋单逼单 / 主播节奏 | `live-anchor` |
| 售前售后话术 / 差评安抚 / 复购 | `customer-service` |
| 毛利核算 / 投流 ROI 财务 / 报表 | `accountant` |
| 商品详情页 / 店铺装修 / 主图 SKU 图 | `designer` |

---

## 四、预设 Workflow

| Workflow | 触发 | 编排 |
|---|---|---|
| A 直播间开播作战 | 「策划一场直播 / 新号起号」 | 诊断 →（并行）策划+投放+抖店+设计 → 剪辑 → 整合 |
| B 千川放量提效 | 「ROI 低 / 放量不动」 | 定位 → 千川+广告并联 → 节奏建议 |
| C 抖店增长诊断 | 「GMV 上不去 / 详情页转化差」 | 抖店诊断 → 设计优化 → 货盘建议 |
| D 全链路直播作战 | 「要一套完整开播方案」 | （并行）6 岗 → 剪辑 → 会计出利润口径 → 整合 |
| E 项目全岗会诊 | 交来项目且未指定 | 10 岗独立评估 → 评估矩阵 → 总评 |

详细编排与依赖见 **[`references/workflows.md`](references/workflows.md)**。

---

## 五、目录结构

```
电商运营专家团/
├── README.md              使用文档（本文件）
├── SKILL.md               技能主文档（Agent 读这个）
├── references/
│   ├── members.md         10 岗职能与能力手册
│   └── workflows.md       5 个 Workflow 详细编排
└── agents/                10 个岗位的完整角色定义（可直接作为子 Agent）
    ├── douyin-ecom-ops-team-lead.md
    ├── douyin-store-ops.md
    ├── video-planner.md
    ├── qianchuan-optimizer.md
    ├── video-editor.md
    ├── ad-optimizer.md
    ├── live-anchor.md
    ├── customer-service.md
    ├── accountant.md
    └── designer.md
```

---

## 六、合规红线（所有产出必过）

| # | 红线 |
|---|---|
| F1 | 禁功效（牛羊肉/特产不得讲治病、养生、滋补疗效） |
| F2 | 禁绝对化用语（最 / 第一 / 国家级 / 顶级） |
| F3 | 禁虚构原价 |
| F4 | 禁诋毁具体竞品品牌 |
| F5 | 禁私自承诺售后（生鲜退货统一店铺口径） |
| F6 | 禁虚假产地 |
| F7 | 禁无法兑现承诺（如"现宰现发"）；冷链按事实表述 |
| F8 | 禁跨店复用无编号素材 |
| F9 | 禁盗图与未授权字体（设计岗主责） |

---

## 七、版本记录

| 版本 | 日期 | 变更 |
|---|---|---|
| v1.0.0 | 2026-09-15 | 初版：9 岗（运营总监 / 抖店运营 / 视频策划 / 千川优化师 / 视频剪辑 / 广告优化师 / 客服 / 会计 / 主播） |
| v1.1.0 | 2026-09-20 | **新增第 10 岗「设计·商美陈」**（商品详情页 + 店铺装修）；同步主理人 SOP、评估矩阵、路由表；补齐 `settings.json`；汇总为独立 Skill 并出使用文档 |
