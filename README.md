# Raymund

**AI Product Manager · Product Builder**

我把模糊的业务问题，转化为可验证、可交付的 AI 产品：从用户研究与产品判断出发，设计人机协作工作流，并用原型、评估和真实反馈持续迭代。

商科训练让我关注商业价值与用户选择，动手构建让我理解模型能力、系统边界与落地成本。中南大学会计学本科（AI 智能财务方向），有券商研究与审计实习经历，对数据准确性高度敏感。现在正在寻找 **AI 产品经理** 机会（Shanghai / Remote）。

[代表项目](#代表项目--selected-work) · [产品思考](#产品思考--product-thinking) · [简历 PDF](https://github.com/du24601-png/du24601-png/blob/main/DuRui_Resume.pdf) · [作品集](https://raymund-portfolio-rouge.vercel.app/) · [联系我](mailto:du24601@gmail.com)

## 关于我 · About

<table>
<tr>
<td width="50%" valign="top">
<strong>Product Judgment · 产品判断</strong><br>
从用户问题和商业目标出发，明确产品边界、优先级与成功标准。
</td>
<td width="50%" valign="top">
<strong>AI Fluency · AI 系统理解</strong><br>
理解模型能力与局限，把 Prompt、Agent、RAG 和评估转化为产品机制。
</td>
</tr>
<tr>
<td width="50%" valign="top">
<strong>User Insight · 用户洞察</strong><br>
通过访谈、观察与任务拆解，找到真实摩擦点，而不是追逐伪需求。
</td>
<td width="50%" valign="top">
<strong>Delivery &amp; Validation · 交付与验证</strong><br>
用原型、数据和反馈快速验证判断，并推动产品从概念走向可用。
</td>
</tr>
</table>

## Toolbox

`Product Discovery` `Workflow Design` `PRD` `Figma` `SQL` `Python`  
`Agent / RAG` `Prompt Design` `LLM Evals` `Human-in-the-loop`

## 代表项目 · Selected Work

<table>
<tr>
<td width="50%" valign="top">
<h3>01 · <a href="https://github.com/du24601-png/research-canvas">Research Canvas</a></h3>
<p><strong>可溯源 AI 投研分析 Agent</strong> — 把上市公司财务比较，变成「每个数字都能点开看来源」的可验证研究画布：自然语言提问，图表先预览、用户采纳才进入画布。源自券商实习中「查数、导表、制图占掉大半分析时间」的真实痛点。</p>
<p><strong>My role</strong> — 0→1 产品设计与构建：定义 Preview → Adopt 的人机边界，设计「数值 → Dataset → 来源」的溯源机制。</p>
<p><strong>Proof</strong> — 模型做选择、代码做计算，AI 不手编数字、不擅改画布；场景用例评测中，针对「该停时没停」「用相近指标冒充查不到的指标」等失败模式持续修订规则，通过率从 75% 提升到 <strong>91.6%</strong>。附完整产品演示视频，可自托管。</p>
<p><code>AI Agent</code> <code>0→1</code> <code>人机协作</code></p>
<p><a href="https://github.com/du24601-png/research-canvas">Repository</a> · <a href="https://github.com/du24601-png/research-canvas#先看产品">产品演示</a></p>
</td>
<td width="50%" valign="top">
<h3>02 · <a href="https://github.com/du24601-png/OMNA">OMNA 知我</a></h3>
<p><strong>跨 Agent 本地个人记忆管理</strong> — 「换一个 AI，也不用重新介绍自己。」多个 AI 工具的记忆互不共享、上云又有隐私风险：把记忆保存在本机，通过 MCP 按授权提供给 Claude Code、Codex 等客户端。</p>
<p><strong>My role</strong> — 0→1 产品设计：核心机制是「AI 提议、用户确认才记住」，每个 Agent 单独授权，谁读了什么每一次都有记录。</p>
<p><strong>Proof</strong> — 2.0 版本已上线（Windows 桌面端）：待确认队列、Agent 授权与读取留痕完整落地；已适配 Claude Code 等 <strong>6 个客户端</strong>，模拟中文查询 Top-5 命中率 <strong>95%</strong>。</p>
<p><code>AI Product</code> <code>Privacy-first</code> <code>Desktop</code></p>
<p><a href="https://github.com/du24601-png/OMNA">Repository</a> · <a href="https://github.com/du24601-png/OMNA/blob/HEAD/docs/competitive-analysis.md">竞品分析</a></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3>03 · <a href="https://github.com/du24601-png/hs-copilot-web">HS Copilot</a></h3>
<p><strong>面向中小出海电商的 AI 报关归类助手</strong> — 在 1.2 万条税则中为商品找到 10 位 HS 编码，填错会多缴税或清关受阻；直接问大模型，常得到看似专业的错误编码。HS Copilot 用自然语言理解商品、自动追问关键属性，编码与税率只从既定税则库读取。</p>
<p><strong>My role</strong> — 产品与工程一体：设计 HS 编码查询与决策 AI 工作流，让每个结论带依据；用 Node.js + SQLite 实现运行时零第三方依赖的后端。</p>
<p><strong>Proof</strong> — 已部署阿里云（PM2 + Nginx）真实可用；自建两套测试集：出海电商常见商品准确率 <strong>80%</strong>，海关疑难判例经多轮迭代从 10% 提升到 <strong>35%</strong>。</p>
<p><code>Vertical AI</code> <code>Workflow</code> <code>Deployed</code></p>
<p><a href="https://github.com/du24601-png/hs-copilot-web">Repository</a></p>
</td>
<td width="50%" valign="top">
<h3>What I optimize for</h3>
<p>不是展示功能数量，而是讲清楚问题、关键判断、我的角色，以及产品如何被验证。</p>
<p><strong>Case study structure</strong> — Context → Decision → Build → Evidence → Learning</p>
<p><strong>三个项目的同一件事</strong> — AI 提出方案，人保留决定权：Preview → Adopt、确认后才记住、结论必带依据。</p>
</td>
</tr>
</table>

## 产品思考 · Product Thinking

- <a href="https://github.com/du24601-png/OMNA/blob/HEAD/docs/competitive-analysis.md"><strong>OMNA 竞品分析</strong></a> — AI 记忆产品的差异化：本地优先、用户确认、可审计的读取记录。 <code>Product Teardown</code>
- <a href="https://github.com/du24601-png/OMNA/blob/HEAD/docs/gtm/OMNA_US_GTM_Strategy_v1.pdf"><strong>OMNA 美国市场 GTM 方案（23 页）</strong></a> — 从产品定位到推广执行的完整规划。 <code>GTM</code>
- <a href="https://github.com/du24601-png/research-canvas#三个核心差异"><strong>Research Canvas 的三个核心差异</strong></a> — 真实数据、用户控制、数字可追溯：如何让 AI 的产出值得信任。 <code>AI Product</code>

> **Product belief** — AI 产品的价值不在于“能生成”，而在于能否进入真实工作流、被可靠验证，并把最终决定留给人。

## 联系我 · Contact

📧 [du24601@gmail.com](mailto:du24601@gmail.com) · 🎨 [作品集](https://raymund-portfolio-rouge.vercel.app/) · 📄 [简历 PDF](https://github.com/du24601-png/du24601-png/blob/main/DuRui_Resume.pdf)
