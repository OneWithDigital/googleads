# Google Ads Skills

12 Claude Code skills for Google Ads management, vendored from
[itallstartedwithaidea/agent-skills](https://github.com/itallstartedwithaidea/agent-skills)
(`skills/google-ads/`), under the MIT license (see `LICENSE`).

The original [google-ads-skills](https://github.com/itallstartedwithaidea/google-ads-skills)
repo is deprecated in favor of `agent-skills`, which is what these were pulled from.

Claude Code auto-discovers any `SKILL.md` under `.claude/skills/<name>/`, so these
load automatically in this repo — no further setup needed.

## Installed skills

| Skill | Description |
|-------|-------------|
| [google-ads-audit](google-ads-audit/SKILL.md) | Comprehensive, pattern-driven account audit using a 1,000-pattern knowledge base |
| [keyword-research](keyword-research/SKILL.md) | Keyword discovery, expansion, and optimization |
| [ad-copy-generation](ad-copy-generation/SKILL.md) | AI-driven responsive search ad (RSA) copy generation |
| [budget-optimization](budget-optimization/SKILL.md) | AI-driven forecasting and portfolio allocation across campaigns |
| [pmax-optimization](pmax-optimization/SKILL.md) | Performance Max campaign management |
| [shopping-ads](shopping-ads/SKILL.md) | Google Shopping campaigns and Merchant Center feed management |
| [audience-targeting](audience-targeting/SKILL.md) | Audience ecosystem targeting across the conversion funnel |
| [conversion-tracking](conversion-tracking/SKILL.md) | Conversion measurement infrastructure management |
| [quality-score-optimization](quality-score-optimization/SKILL.md) | Diagnosing and improving Quality Score |
| [remarketing-strategy](remarketing-strategy/SKILL.md) | Cross-channel remarketing architecture |
| [competitor-analysis](competitor-analysis/SKILL.md) | Auction insights turned into competitive intelligence |
| [landing-page-audit](landing-page-audit/SKILL.md) | Post-click experience and CRO evaluation |

## Updating

To pull newer versions of these skills:

```bash
git clone https://github.com/itallstartedwithaidea/agent-skills.git /tmp/agent-skills
cp -r /tmp/agent-skills/skills/google-ads/. .claude/skills/
```
