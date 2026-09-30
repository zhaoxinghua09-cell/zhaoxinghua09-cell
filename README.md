# Steven Zhao · China — AI Governance Engineering

> Profile README · 全景入口与权属宣告 · Public site: <https://medxpert.cn>

## What I build — and why it matches ITU FG-TIDA

I engineer **machine-checkable** AI-governance primitives. The work most relevant to **ITU FG-TIDA** (themes **#6** *Verifier-side requirements and failure semantics* and **#7**) is:

- **[silent-failure-catalog](https://github.com/zhaoxinghua09-cell/silent-failure-catalog)** — a named catalog of **14 silent-failure modes** (validation that passes while nothing is checked), each with a runnable reproduction, a fix, and a **negative control**. Submitted to FG-TIDA as a verifier-side challenge reference (**PR [#23](https://github.com/FG-TIDA/use-cases/pull/23)** in `FG-TIDA/use-cases`); cited in themes #6/#7.
- **[uibc-core](https://github.com/zhaoxinghua09-cell/uibc-core)** — evidence / registry / validator core for autonomous-system lifecycle governance (Apache-2.0).
- **[lgd-theory](https://github.com/zhaoxinghua09-cell/lgd-theory)** — the Lifecycle Governance Doctrine (registry · evidence · gates).

### How the pieces connect / 流转关系

```mermaid
graph LR
  A[silent-failure-catalog<br/>verifier-side challenge ref] -->|negative controls| B[FG-TIDA #6 / #7<br/>verifier-side failure semantics]
  C[uibc-core<br/>evidence + registry] --> D[LGD lifecycle governance]
  A -->|C7 checks-in-path| E[AVS 0.3 candidates]
  B --> E
```

## Repositories by track / 按主线

| Track | Representative repos |
|---|---|
| LGD doctrine | `lgd-theory`, `lgd-hub`, `xlgd`, `xcgs-manifesto` |
| UIBC autonomous things | `uibc-core`, `uibc-competition` |
| Verifier-side / silent failure | `silent-failure-catalog`, `assayance` |
| MedXpert medical-device compliance | `medxpert-reg-kb`, `medxpert-reg-connector`, `medxpert-skills` |
| Agents & memory | `agent-skills`, `agent-memory-service` |

## Rights notice · 权利宣告

All account content is **All Rights Reserved** (text, methodology, theory terms, specs, examples, scripts). Code is released under MIT / Apache-2.0 / AGPL-3.0 per repo. Attribution-only citation is permitted with named source + link + rights holder *Zhao Xinghua / Steven Zhao·China*.

**Brand status:** MedXpert, SynomosAI, LGD, UIBC, Nomos, XLGD are project identifiers only — **no entity or trademark registration filed**. Their appearance is source identification, not a claim of legal-entity or trademark rights.

## Contact · 联系

- Email: zhaoxinghua09@gmail.com
- ORCID: 0009-0001-0512-1237
- Site: <https://medxpert.cn>

---

*Maintained by the rights holder. Public information only; not legal, regulatory, or registration advice.*

---

# 中文说明

本账号聚焦于**可机器核验的 AI 治理构件**。与 **ITU FG-TIDA**（主题 **#6** 验证方失败语义、**#7**）最直接相关的工作：

- **[silent-failure-catalog](https://github.com/zhaoxinghua09-cell/silent-failure-catalog)** —— 14 种"静默失败"模式的命名目录，每条含可运行复现、修法、反向对照。已作为验证方挑战参考实现提交（`FG-TIDA/use-cases` **PR [#23](https://github.com/FG-TIDA/use-cases/pull/23)**），并在 #6/#7 被引用。
- **[uibc-core](https://github.com/zhaoxinghua09-cell/uibc-core)** —— 自治系统全生命周期治理的证据/注册/验证内核（Apache-2.0）。
- **[lgd-theory](https://github.com/zhaoxinghua09-cell/lgd-theory)** —— 全程治理论（注册·证据·门禁）。

**权利宣告**：本账号全部内容保留所有权利；代码依各仓许可证（MIT/Apache-2.0/AGPL-3.0）使用。署名引用须标注权利人「赵兴华 / Steven Zhao·China」。MedXpert、SynomosAI、LGD、UIBC 等仅为项目标识，**均未申请实体/商标注册**。
