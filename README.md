# Delta · Good Things, Going Places — Strategy Portfolio

An independent brand & social strategy case study for Delta, a curated circular lifestyle concept built for people who move often.

单文件 HTML，无外部依赖、无构建步骤，GitHub Pages 直接部署。

---

## 文件

| 文件 | 用途 |
|---|---|
| `index.html` | **主站（编辑版，英文）** — 七段式结构，包含全部 9 条内容与 7 张 mock 的交互式画廊 |
| `zh.html` | **中文版（编辑版）** — 与主站同构同设计，全部叙事中文化，9 条内容的英文成稿原文保留 |
| `zh-archive.html` | 原始中文长文版（完整保留，未删改内容） |
| `en.html` | 原始英文长文版（完整保留，含逐平台文案与判断） |

`zh-archive.html` / `en.html` 为历史归档版，顶部有指向新版编辑版的提示条。
两个编辑版共用同一套 CSS 与交互，仅文案语言与局部排版（中文字距）不同。

## 主站结构（七段，中英一致）

| 段落 | 内容 |
|---|---|
| 01 Overview | 品牌标语、项目定位、作者与能力范围 |
| 02 The Challenge | 搬家与所有物的矛盾 + 核心策略问题 + 四条张力 + 项目约束（可展开） |
| 03 The Thinking | ICP、三个排除项、定位图、三轴竞品对比、品牌定位、机制、平台角色分工（长表格折叠） |
| 04 The Creative | 4 个内容支柱（目标 / 洞察 / 方法 / 指标 / 视觉示例）、语气三原则、视觉方向 |
| 05 The Work | 9 条内容 × 7 张 mock 的编辑式网格，点击展开完整英文文案、判断、受众、目标、CTA |
| 06 The Rollout | 4 周可切换的 30 天日历 + 目标与 KR + 分层 KPI + 决策规则 + 投入分级（均标明来源） |
| 07 The Reflection | Beyond the Strategy — 观察如何转为决策、优先级、创意与商业目标、上线前测试、数据迭代 |

## 设计原则

- 编辑式排版：Georgia 展示级标题 + 系统无衬线正文，暖象牙底 + 炭黑字 + 鼠尾草绿强调色。
- 证据分级贯穿全站：Observation / Strategic hypothesis / Proposed solution / Assumption to validate。
- 无实测数据。所有 KPI 标注为行业基准或项目假设；mock 图片为 CSS 占位，价格与物件为示意。
- 无障碍：语义化结构、键盘可操作画廊与折叠面板、`prefers-reduced-motion` 支持、无横向溢出。

## 核心判断

- **ICP**：搬得动，但不愿将就的人。三个排除项恰好对应三个竞品的核心用户——人群定义与竞品选择互相印证。
- **第一优先级是抢定义权**，不是涨粉：Delta 极易被误读为「二手店」或「租赁」。
- **把「四道题」从卖点升级为栏目**：竞品在结构上给不出公开标准。
- **把「搬家」从机制理由提升为内容场景**：唯一能对齐外部日历（毕业季 / 开学季 / 换约季）的节奏。
- **平台适配的代价各不相同**：Pinterest 放弃调性换搜索流量，Reddit 放弃 CTA 换信任。

## 免责声明

Spec work，非客户项目。品牌依据来自公开仓库 [emersoncaiye/Delta](https://github.com/emersoncaiye/Delta) 的 philosophy / aesthetic / story / for_whom / circularity / charity 原文。
竞品账号量级为公开可见估算，KPI 基线为同品类新号的行业经验值，实测后需重设。Mock 中的图片为 CSS 占位、数据为示意。

品牌概念站当前使用「Objects in Motion / 好东西，不该停在原地」；本作品集沿用更早的「Good Things, Going Places.」与上市句「nothing good stays behind.」，作为历史项目文案保留，不做静默替换。

---

## 本地预览

```bash
python3 -m http.server 8777
# 打开 http://localhost:8777/index.html
```
