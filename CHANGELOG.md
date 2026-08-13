# 更新日志 Changelog

本文件记录 `EthosBtc-seedance-lab` 的所有重要变更。
All notable changes to `EthosBtc-seedance-lab` are documented in this file.

格式基于 [Keep a Changelog](https://keepachangelog.com/)。
The format is based on [Keep a Changelog](https://keepachangelog.com/).

---

## [1.1.0] — 2026-08-13

### 变更 Changed

- **改名 Rebranded** — 项目更名为 `EthosBtc-seedance-lab`，由 [@EthosBtc](https://github.com/Ethosbtc) 维护 | Project renamed, now maintained by @EthosBtc
- **install.sh** — 支持 Windows (Git Bash)，默认安装到 Claude Code 技能目录 `~/.claude/skills`，可用 `CLAUDE_SKILLS_DIR` 覆盖 | Windows (Git Bash) support; installs to Claude Code's `~/.claude/skills` by default, overridable via `CLAUDE_SKILLS_DIR`
- **README** — 更新安装说明和仓库结构 | Updated install instructions and repository structure
- **规格更新 Specs refresh** — Seedance 2.0 现支持 480p/720p/1080p/原生 4K 输出（此前文档只写 720p）| Seedance 2.0 now outputs up to native 4K on Higgsfield; docs previously said 720p only

### 修复 Fixed

- `04-comic-to-video` — 修正 "IGGSFIELD" 拼写错误 | Fixed "IGGSFIELD" typo
- README 仓库结构中引用了不存在的 `LICENSE` 和 `logs.md` | README structure section referenced nonexistent `LICENSE` and `logs.md`

### 移除 Removed

- `init-repo.sh` 和 `GITHUB_SETUP.md` — 仓库已上线，不再需要 | Repo is live; setup scripts no longer needed

---

## [1.0.0] — 2026-04-09

### 新增 Added

- **15 个 Claude 技能 15 Claude Skills** — 完整的 Seedance 2.0（Higgsfield）提示词工程技能集 | Complete prompt engineering skills collection for Seedance 2.0 on Higgsfield

#### 创意风格 Creative Styles
- `01-cinematic` — 电影风格 | Film/movie quality with dramatic lighting, camera language
- `02-3d-cgi` — 3D CGI | Pixar, Unreal Engine, photorealistic rendering
- `03-cartoon` — 卡通动画 | 2D animation, cel-shaded, hand-drawn, flat vector
- `04-comic-to-video` — 漫画转视频 | Animate comics, manga, webtoons, storyboards
- `05-fight-scenes` — 打斗场景 | Martial arts, sword fights, action choreography
- `08-anime-action` — 动漫 | Shonen, seinen, mecha, anime openings

#### 商业营销 Commercial & Marketing
- `06-motion-design-ad` — 动态设计广告 | Software/SaaS product launches
- `07-ecommerce-ad` — 电商广告 | Product ads for online selling
- `09-product-360` — 产品 360° | Turntable, multi-angle product showcase
- `11-social-hook` — 社交钩子 | TikTok/Reels/Shorts viral hooks
- `12-brand-story` — 品牌故事 | Company narrative, origin stories

#### 行业专项 Industry-Specific
- `10-music-video` — 音乐视频 | Beat-synced performance and visualizers
- `13-fashion-lookbook` — 时尚型录 | Fashion lookbooks, model showcases
- `14-food-beverage` — 美食饮品 | Restaurant promos, food ASMR
- `15-real-estate` — 房地产 | Property tours, architecture

### 核心特性 Core Features
- **2 秒钩子框架 2-Second Hook Framework** — 每个技能包含 10-12 种注意力抓取模式 | Each skill includes 10-12 attention-grabbing patterns
- **双语支持 Bilingual** — 所有技能提供 English + 简体中文
- **制作级示例 Production Examples** — 每个技能 5+ 个大型示例提示词（15-25 行）| 5+ large example prompts per skill
- **平台优化 Platform Optimization** — 抖音/TikTok、Instagram、YouTube、LinkedIn 适配 | Cross-platform guidance
- **摄像机百科 Camera Encyclopedia** — 每个技能 15-20+ 镜头运动技术 | 15-20+ camera techniques per skill

### 统计 Stats
- 30 个 SKILL.md 文件 | 30 SKILL.md files (15 EN + 15 ZH)
- 31,725 总行数 | total lines
- 1.9 MB 仓库大小 | repo size

---

## [未来计划 Roadmap]

### 即将推出 Coming Soon
- 更多语言翻译 Additional language translations (ja, ko, de, fr, es, pt, tr)
- 社区贡献的技能 Community-contributed skills
- 基于真实生成结果的迭代优化 Iteration based on real generation results
- 视频示例展示 Video example gallery
- API 集成技能 API integration skills
