# LLM Price Radar · 大模型价格仪表盘 / Bilingual README

[中文说明](#中文说明) · [English](#english)

---

## 中文说明

### 这是什么

一页看透 **10 家国产大模型**（DeepSeek、Kimi、MiMo、GLM、通义千问、豆包、MiniMax、阶跃星辰、混元、文心一言）与 **OpenAI / Anthropic / Google** 三家海外厂商的 API 单价、免费额度与 Coding Plan 订阅价。

### 亮点

- 单文件静态页，零依赖，`index.html` 即全部
- 工业仪表 × Editorial 风格：暖纸白底、墨黑、中国红强调色、顶部价格跑马灯、衬线巨型标题、红色「低价推荐」印章
- 按典型负载（输入:输出 ≈ 3:1）折算「综合指数」，低价模型自动盖上推荐印章
- 海外厂商价格按当日人民币汇率中间价折算为元/百万 tokens，美元原价见页面卡片备注
- 数据每日 08:00 自动抓取各厂商官方定价页刷新

### 本地使用

直接用浏览器打开 `index.html` 即可，无需构建、无需服务器。

### 数据更新

编辑 `index.html` 底部 `<script>` 中的 `MODELS` 数组与 `FX` 汇率常量即可，卡片、对比表、跑马灯与推荐印章会自动重新渲染。

数据来源为各厂商官方定价页（页面 Sources 区有完整链接）。本页面为价格信息聚合工具，与所列厂商无隶属关系；不构成任何采购建议。

---

## English

### What is this

A single page that puts the **API prices, free tiers, and Coding Plan subscriptions** of **10 Chinese LLM vendors** (DeepSeek, Kimi, MiMo, GLM, Qwen, Doubao, MiniMax, StepFun, Hunyuan, ERNIE) alongside **OpenAI / Anthropic / Google** in one view.

### Highlights

- Single-file static page with zero dependencies — `index.html` is the whole app
- Industrial instrument × Editorial style: warm paper background, ink black, Chinese red accents, top price ticker, serif display headline, and a red "Lowest Price" stamp
- A "composite index" (input × 3 + output) simulates a typical 3:1 input/output workload; the cheapest models get stamped automatically
- Overseas prices are converted to CNY per million tokens at the daily central parity rate; original USD prices are noted on each card
- Data is refreshed automatically at 08:00 (UTC+8) every day from official vendor pricing pages

### Local usage

Open `index.html` in any browser. No build step, no server required.

### Updating data

Edit the `MODELS` array and the `FX` rate constant in the `<script>` block at the bottom of `index.html`. Cards, the comparison table, the ticker, and the recommendation stamps all re-render automatically.

Data comes from official vendor pricing pages (full links in the Sources section of the page). This page is a price aggregation tool, is not affiliated with any listed vendor, and does not constitute purchasing advice.
