# Changelog

All notable changes to `EthosBtc-seedance-lab` are documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/).

---

## [1.2.0] — 2026-08-13

### Changed

- **English-first documentation** — README, CHANGELOG, CONTRIBUTING, SECURITY, CODE_OF_CONDUCT, and install.sh are now in English. Simplified Chinese remains available via `README.zh-CN.md` and the `skills/XX-name/zh-CN/` translations.

---

## [1.1.0] — 2026-08-13

### Changed

- **Rebranded** — Project renamed to `EthosBtc-seedance-lab`, maintained by [@EthosBtc](https://github.com/Ethosbtc)
- **install.sh** — Windows (Git Bash) support; installs to Claude Code's `~/.claude/skills` by default, overridable via `CLAUDE_SKILLS_DIR`
- **README** — Updated install instructions and repository structure
- **Specs refresh** — Seedance 2.0 now outputs up to native 4K on Higgsfield (docs previously said 720p only)

### Fixed

- `04-comic-to-video` — Fixed "IGGSFIELD" typo
- README structure section referenced nonexistent `LICENSE` and `logs.md`

### Removed

- `init-repo.sh` and `GITHUB_SETUP.md` — repo is live; setup scripts no longer needed

---

## [1.0.0] — 2026-04-09

### Added

- **15 Claude Skills** — Complete prompt engineering skills collection for Seedance 2.0 on Higgsfield

#### Creative Styles
- `01-cinematic` — Film/movie quality with dramatic lighting and camera language
- `02-3d-cgi` — Pixar, Unreal Engine, photorealistic rendering
- `03-cartoon` — 2D animation, cel-shaded, hand-drawn, flat vector
- `04-comic-to-video` — Animate comics, manga, webtoons, storyboards
- `05-fight-scenes` — Martial arts, sword fights, action choreography
- `08-anime-action` — Shonen, seinen, mecha, anime openings

#### Commercial & Marketing
- `06-motion-design-ad` — Software/SaaS product launches
- `07-ecommerce-ad` — Product ads for online selling
- `09-product-360` — Turntable, multi-angle product showcase
- `11-social-hook` — TikTok/Reels/Shorts viral hooks
- `12-brand-story` — Company narrative, origin stories

#### Industry-Specific
- `10-music-video` — Beat-synced performance and visualizers
- `13-fashion-lookbook` — Fashion lookbooks, model showcases
- `14-food-beverage` — Restaurant promos, food ASMR
- `15-real-estate` — Property tours, architecture

### Core Features
- **2-Second Hook Framework** — Each skill includes 10-12 attention-grabbing patterns
- **Bilingual** — All skills available in English + Simplified Chinese
- **Production Examples** — 5+ large example prompts per skill (15-25 lines)
- **Platform Optimization** — TikTok, Instagram, YouTube, LinkedIn guidance
- **Camera Encyclopedia** — 15-20+ camera techniques per skill

### Stats
- 30 SKILL.md files (15 EN + 15 ZH)
- 31,725 total lines

---

## [Roadmap]

### Coming Soon
- Additional language translations (ja, ko, de, fr, es, pt, tr)
- Community-contributed skills
- Iteration based on real generation results
- Video example gallery
- API integration skills
