# brand-messaging-assets-skill

先看 [Shelfmark 信息包示例 / fictional messaging kit](examples/fictional-brand.md)：定位、主张证据、语气和可复用文案。[信息包模板 / template](templates/messaging-kit.md) · [Skill 入口](SKILL.md)。

## 中文
这是个人自用、持续更新中的营销工作流项目。首版聚焦可直接交给 AI agent 的轻量工作方法，不代表已经获得业务效果，也不是自动发布或投放工具。

用途：品牌定位、证据驱动的核心信息、语气和可复用文案素材。先复用已有且允许读取的业务资料，标明来源，再补充关键缺口。支持品牌账号、创始人/员工账号、合作方/客户账号的角色区分；不虚构背书。

使用：把整个目录复制到你的 agent 支持的 skill 目录（请按所用产品的说明安装），或让 agent 阅读 SKILL.md。提供业务目标、受众、资源、已有素材和事实依据，要求输出 templates/ 中的简报。examples/ 为明确标注的虚构示例，不能当作真实案例。无需 API key、付费测试或安装脚本。

示例请求：“基于我提供的读书会工具说明和已批准样文，做一份品牌信息包：定位、价值主张、两到三个信息支柱、语气卡、两版标题、简介和一组 hero/CTA。逐条核对主张证据，不编客户背书。”

交付：使用 [messaging kit](templates/messaging-kit.md) 汇总文案、主张台账与待确认项。先匹配用户已有语气；没有样文时把语气标为暂定，不强加两周活动排期。

## English
Personal-use marketing workflow, continuously updated as real use reveals improvements. This is a first usable version, not a claim of proven business performance.

Scope: Brand positioning, evidence-backed messaging, and reusable copy assets. Read SKILL.md with an AI agent, supply a brief and permitted source material, and use the output template. Copy the full folder only when your agent supports local skills; follow that agent's installation instructions. No runtime dependencies, credentials, paid tests, or automatic publishing are required.

Example: “Build a messaging kit from my book-club tool brief and approved voice samples: positioning, message pillars, voice, two headlines, descriptions and a hero/CTA set. Trace factual claims; do not invent endorsements.” Return the kit, claim ledger and review gaps.

Files: SKILL.md is the workflow; references/ contains the adapted method; templates/ contains the output structure; examples/ contains fictional practice material. THIRD_PARTY_NOTICES.md and licenses/ preserve upstream attribution and terms.

## Sources and license scope / 来源与许可
One narrowly adapted module from coreyhaines31/marketingskills: skills/copywriting/SKILL.md, pinned at 365b412152b9542499ca1439426f7fc3cc92bb65. Actual upstream MIT LICENSE checked on 2026-10-16. See THIRD_PARTY_NOTICES.md for exact links and modifications. No repository-wide license is assigned to original additions by this package; the preserved MIT license applies to its identified upstream material.
