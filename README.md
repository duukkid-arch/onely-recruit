# Onely Recruit — 运营人员批量招募平台

> 3 天内找到、触达并促成 100 名具备美国社媒运营能力的运营人员入驻 Onely 平台

**产品链接：** [Onely Recruit MVP](https://claude.ai/artifact/TQkN57HDhfz6TjUHkPKTiy)

---

## 一、增长方案总览

### 1.1 目标拆解

| 指标 | 数值 | 说明 |
|------|------|------|
| 最终入驻 | 100 人 | 完成注册 + 进入 Discord/Telegram 社群 |
| 漏斗倒推（兴趣→入驻 60%） | ~167 人表示兴趣 | |
| 漏斗倒推（回复→兴趣 50%） | ~333 人回复 | |
| 漏斗倒推（触达→回复 25%） | ~1,333 人触达 | |
| 漏斗倒推（线索→触达 70%） | ~1,900 条线索 | |

### 1.2 人员画像

- **地域：** 菲律宾（首选）、尼日利亚、肯尼亚、南非、印度、巴基斯坦、加纳
- **能力：** 有为美国/欧洲创作者运营 Instagram、TikTok、Twitter/X、YouTube 的经验
- **语言：** 英语流利或母语
- **工作模式：** 远程 freelance，时区覆盖美国 EST/PST

### 1.3 线索来源与采集策略

| 来源 | 预计线索量 | 获取方式 | 优先级 |
|------|-----------|----------|--------|
| **OnlineJobs.ph** | 400+ | 搜索 "social media manager" / "content creator assistant"，导出简历 | P0 |
| **Upwork** | 300+ | 筛选有 US client 评价的 social media freelancer，提取 profile | P0 |
| **LinkedIn** | 300+ | 搜索 "social media manager" + 目标国家，Sales Navigator 或手动采集 | P0 |
| **Facebook Groups** | 200+ | 加入 "Virtual Assistants PH"、"Nigerian Freelancers" 等群组，发帖招募 | P1 |
| **Freelancer.com** | 200+ | 类似 Upwork 策略 | P1 |
| **推荐裂变** | 100+ | 已入驻人员推荐，$5/人奖励 | P2 |
| **Reddit/Twitter** | 100+ | r/VirtualAssistant、r/WorkOnline 发帖 | P2 |

### 1.4 筛选标准（自动打分）

每条线索按以下维度打分，总分 100，分级 A/B/C/D：

| 维度 | 权重 | A 级标准 |
|------|------|---------|
| 美国社媒平台经验 | 25% | 熟练运营 Instagram + TikTok + YouTube 中至少 3 个 |
| 工作年限 | 25% | 3 年以上 creator/agency 运营经验 |
| 英语水平 | 25% | 母语或流利（可通过 profile 评估） |
| 平台覆盖广度 | 25% | 覆盖 4+ 主流平台 |

**分级：** A (≥75) → 优先触达 | B (55-74) → 正常触达 | C (35-54) → 备选 | D (<35) → 暂不触达

### 1.5 触达与转化漏斗

```
Day 1: 线索采集 + A/B 级触达
├── 上午：OnlineJobs.ph + Upwork 批量采集，导入系统去重
├── 下午：LinkedIn 搜索 + 采集，所有 A 级线索当天触达
└── 晚间：Facebook Group 发帖，Reddit/Twitter 发帖

Day 2: 跟进 + C 级触达
├── 上午：跟进 Day 1 未回复的 A/B 级线索（换渠道触达）
├── 下午：新线索入库，C 级线索触达
└── 晚间：首批意向者引导入 Discord/Telegram

Day 3: 冲刺入驻 + 裂变
├── 上午：所有 Interested 状态推进到 Onboarding
├── 下午：启动推荐裂变，已入驻者邀请同行
└── 晚间：社群 welcome session，完成 100 人目标
```

**多渠道触达策略：**

1. **第一触达：** LinkedIn DM 或 Email（根据来源选择）
2. **24h 未回复：** 换渠道跟进（Email → LinkedIn，反之亦然）
3. **48h 未回复：** Telegram/WhatsApp 短消息提醒
4. **已回复未入驻：** 1v1 答疑 + 社群邀请链接

### 1.6 入驻后管理、培训与留存

#### 社群架构（Discord 为主）

```
Onely Operators (Discord)
├── #welcome          — 自我介绍 + 入驻引导 bot
├── #announcements    — 平台更新、新 creator 匹配机会
├── #general-chat     — 日常交流
├── #training         — 教程视频、操作指南、FAQ
├── #platform-tips    — Instagram / TikTok / YouTube 分频道
├── #showcase         — 运营成果展示
├── #support          — 技术问题、提款问题
└── #referrals        — 推荐奖励追踪
```

#### 培训体系

| 阶段 | 内容 | 交付方式 |
|------|------|---------|
| Day 0 入驻 | Onely 平台操作教程、AI 工具使用指南 | 5 min 视频 + 文档 |
| Week 1 | 创作者沟通规范、内容排期流程 | Discord live session |
| 持续 | 平台功能更新、新 creator 类型培训 | 异步文档 + 录播 |

#### 留存策略

- **激励机制：** 绩效排行榜，top 运营者获更多 creator 匹配机会和更高费率
- **社群运营：** 每周 AMA session，运营者互相分享 tips
- **成长路径：** 初级运营 → 高级运营 → 团队 lead → 区域负责人
- **推荐裂变：** 每成功推荐 1 人入驻奖励 $5

---

## 二、产品功能说明

### 2.1 已实现功能 ✅

| 功能模块 | 说明 |
|---------|------|
| **Dashboard** | 关键指标总览（总线索 / 已触达 / 回复率 / 已入驻），转化漏斗可视化，来源分布饼图，Grade × Region 堆叠柱状图，实时活动时间线 |
| **进度追踪** | 侧边栏 100 人目标进度环，实时反映 Onboarded 人数占比 |
| **线索导入 + 去重** | CSV 批量导入，自动按 email 去重，重复记录跳过并计数 |
| **自动打分** | 基于平台经验 × 年限 × 英语水平 × 美国平台覆盖度的四维评分模型，自动分级 A/B/C/D |
| **AI 智能触达文案** | 接入 Claude API（sample capability），根据候选人完整画像实时生成个性化触达消息；无 AI 时自动回退到模板引擎 |
| **模板触达文案** | 4 渠道（LinkedIn DM / Email / Discord / Telegram）× 3 语调（Professional / Friendly / Urgent）= 12 套模板，自动填充变量 |
| **Send & Track** | 一键标记消息已发送，自动将线索状态从 New 推进到 Contacted |
| **Pipeline 看板** | 6 阶段可视化看板（New → Contacted → Responded → Interested → Onboarding → Onboarded），一键推进 |
| **批量操作** | 多选线索 + 批量更新状态，适合大规模触达后统一推进 |
| **CSV 导出** | 一键导出全量线索数据为 CSV 文件 |
| **社群管理** | Discord 频道结构可视化、Telegram 群组管理、培训进度追踪、留存与推荐数据看板 |
| **活动时间线** | Dashboard 实时记录所有操作（导入、状态变更、删除等），便于团队协作追溯 |
| **搜索与筛选** | 按姓名/邮箱搜索，按 Grade / Source / Status 筛选 |
| **数据持久化** | localStorage 存储，刷新不丢失 |
| **暗色模式** | 自动跟随系统主题，支持 light/dark 切换 |
| **Demo 数据** | 预置 25 条真实画像的模拟线索，覆盖菲律宾、尼日利亚、印度、肯尼亚、加纳、巴基斯坦、南非 |

### 2.2 仍需验证的假设 🔍

| 假设 | 验证方式 |
|------|---------|
| 菲律宾/尼日利亚是最优线索来源 | A/B 测试不同地区的回复率和入驻率 |
| LinkedIn DM 回复率 > Email | 记录各渠道触达→回复转化率 |
| A 级线索入驻率 > 60% | 跟踪各 Grade 的漏斗转化数据 |
| 推荐裂变可贡献 20% 新线索 | 追踪推荐来源的线索占比 |
| AI 个性化文案比通用模板回复率高 30% | 对照组测试 |
| Discord 比 Telegram 留存率更高 | 30 天留存数据对比 |
| $5-12/hr 费率对目标人群有吸引力 | 入驻者薪资满意度调查 |

### 2.3 自动化降低人工成本

| 环节 | 手动方式 | 自动化方式 | 效率提升 |
|------|---------|-----------|---------|
| 线索采集 | 逐个复制粘贴 | CSV 批量导入 + API 抓取 | 10x |
| 去重 | 肉眼比对 | Email 自动去重 | 50x |
| 筛选分级 | 人工逐条评估 | 四维评分自动打分 | 20x |
| 触达文案 | 每条手写 | 模板引擎 + 变量填充 | 15x |
| 状态跟踪 | Excel 手动更新 | Pipeline 看板一键推进 | 5x |
| 数据统计 | 手动计算 | Dashboard 实时更新 | 即时 |

---

## 三、运行方式

### 在线访问

直接打开产品链接即可使用，无需安装任何依赖。

### 本地运行

```bash
# 克隆仓库
git clone <repo-url>
cd onely-recruit

# 直接用浏览器打开
open index.html
# 或使用任意静态服务器
npx serve .
```

### CSV 导入格式

```csv
name,email,country,city,platforms,experience,english,rate,source,notes
Maria Santos,maria@gmail.com,Philippines,Manila,Instagram|TikTok|YouTube,4,Fluent,8,Upwork,Managed US creators
```

- `platforms` 字段用 `|` 或 `;` 分隔
- 所有字段均为可选（除 email 用于去重）

---

## 四、技术架构

```
┌─────────────────────────────────────────┐
│            Frontend (Single HTML)        │
│  ┌──────────┬──────────┬───────────┐    │
│  │Dashboard │  Leads   │ Outreach  │    │
│  │ Charts   │ Import   │ Templates │    │
│  │ Metrics  │ Dedup    │ Generate  │    │
│  │ Funnel   │ Grade    │ Copy      │    │
│  └──────────┴──────────┴───────────┘    │
│  ┌──────────────────────────────────┐   │
│  │         Pipeline Board           │   │
│  │  New→Contact→Reply→Interest→Done │   │
│  └──────────────────────────────────┘   │
│         │                               │
│    localStorage (Data Persistence)      │
│    Chart.js (Visualization)             │
│    Tailwind CSS (Styling)               │
└─────────────────────────────────────────┘
```

**设计决策：**

- **单文件架构：** 零依赖部署，任何浏览器直接运行，降低评审者使用门槛
- **localStorage：** MVP 阶段无需后端，数据持久化在浏览器
- **模板引擎：** 变量化触达文案，避免每条手写
- **自动评分：** 可配置的多维度打分模型，可随业务调整权重

---

## 五、后续迭代方向

1. **接入 LLM API：** 用 Claude API 生成更智能的个性化触达文案
2. **Upwork/LinkedIn API 对接：** 自动化线索采集，替代 CSV 手动导入
3. **邮件自动发送：** 集成 SendGrid/Mailgun，批量自动触达
4. **Discord Bot：** 自动化入驻流程、角色分配、培训 push
5. **协作后端：** 多人协同操作，数据不依赖单机浏览器
6. **数据分析：** 渠道 ROI 追踪，触达时间优化，A/B 测试框架
