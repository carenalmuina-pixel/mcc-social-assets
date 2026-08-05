# MCC Social Assets — Project Doctrine

Raw video and image content-production library for Monarch Claims Consultants / JLAC Corp — Caren Almuina's licensed Florida public-adjusting brand. See `/root/.claude/CLAUDE.md` for the cross-venture doctrine this repo inherits, and `monarch-landing`'s CLAUDE.md (the canonical MCC marketing-site repo — see its duplicate-repo flag re: `carenatmonarch`) for the brand config, license number, and compliance detail this repo's content must follow. This repo holds finished/near-finished assets only — no captions, no metadata, no README of its own beyond this file; treat `monarch-landing/mcc-pipeline/brand_config.json` as the source of truth for footer text, DM triggers, hashtags, and content pillars referenced below.

## Real state, verified 2026-08-05

- **Content:** 317MB of video (`videos/`) + 6.5MB of images (`posts/`), all real finished assets — checked file sizes and git-tracked status; working tree is clean and everything present is actually committed. Single commit in this repo's history (`5ac0e99`, on `master`).
- **What's here, by filename pattern** (no manifest exists, so this is inferred from naming plus the commit message, not read off a spec):
  - `d1`–`d4`: short damage-type explainers (roof/wind, water, hurricane, hail), English only.
  - `p1`–`p6`: process/education pieces (walkthrough, deductible, roof, identity), several bilingual (EN/ES), plus two TikTok-formatted slideshow videos with matching carousel slides in `posts/`.
  - `w1`–`w3`: storm-watch content ("watch issued," "first 72 hours," "night before"), several bilingual.
  - `videos/seriesA/` (11 files): voiceover-narrated reels citing specific FL claims-process rules and deadlines — deadline, landfall, supplemental, 60-day window, fees, AOB (assignment of benefits), the "25% rule," roof age. Per the last commit message these were "approved + signed off 2026-07-28." **This is the most legally load-bearing content in the repo** — it cites specific statutory deadlines/rules, so it needs the highest compliance scrutiny of anything here. Don't reuse or re-cut it without a compliance pass confirming the underlying deadlines/rules it cites are still current — insurance statutes change; verify before recycling old Series A content into a new post.
- **IG handle:** not stored in this repo (no text/caption files exist here) — confirmed via the canonical site repo: `@yenclaims`.
- Similar in spirit to Kuleana's `kuleanaclaimsolutions` voiceover pipeline (per the global doctrine), though nothing here confirms the two share a production process — that's a pattern match, not a verified fact.

## Compliance

Same regulatory bar as `monarch-landing` — this is licensed FL public-adjuster marketing content. **The `pa-advertising-compliance` skill does not currently exist in this account** (checked `/root/.claude/skills/`, not present under that or any close name) — see `monarch-landing`'s CLAUDE.md for the full flag and the rules to apply directly in its place (license number on everything, 48-hour post-catastrophe solicitation ban, no outcome promises, no fee percentages, hedged settlement language, imagery disclosure). This applies with extra weight to `seriesA`'s statute-citing content specifically.

## Subagents

This repo doesn't carry its own `.claude/agents/` — `compliance-content-director` and `social-publishing-lead` live in `monarch-landing/.claude/agents/` as the single source of truth, and apply to work done with this asset library too. If working in this repo standalone, read those two files from the canonical repo before drafting captions or scheduling anything sourced from here.

## Related repos

`monarch-landing` (canonical marketing site + `mcc-pipeline`, the content pipeline these assets feed) and `carenatmonarch` (its byte-identical duplicate, flagged for archival).
