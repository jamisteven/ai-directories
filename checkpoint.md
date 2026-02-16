# AI Directories Project — Checkpoint

**Product:** goMacro.ai
**URL:** https://gomacro.ai
**Date:** 2026-02-16

---

## Directory Database (`directories.json`)

| Metric | Count |
|---|---|
| **Total entries** | 827 |
| Active | 489 |
| Not found | 162 |
| Domain dead | 64 |
| Timeout | 30 |
| Cloudflare blocked | 20 |
| Error | 32 |
| Invalid URL | 12 |
| Facebook group | 11 |
| Domain parked | 7 |

### Auth Type Breakdown (all 827)

| Auth Type | Count |
|---|---|
| unknown | 308 |
| none (open submit) | 296 |
| google_only | 142 |
| email_password | 36 |
| facebook | 22 |
| google_and_email | 14 |
| other combos | 9 |

---

## Submission Plan (`submission_plan.json`)

**Product:** goMacro.ai — Institutional grade insights for economic calendar events
**Total entries:** 318
**Copy variations:** 30 unique title/description pairs rotated across all directories
**Credentials:** Configured (replace YOUR_* placeholders before running)

---

## goMacro.ai Submission Results

### Auto-Submit Pass 1

Ran `submit_directories.py` on 107 discovered entries:
- 53 raw submissions (form filled + button clicked)
- After verification: **32 high-confidence**, 21 false positives (wrong buttons)

### Auto-Submit Pass 2

Ran form discovery on 30 timeout + 51 no_fields_matched entries, then auto-submitted 102 entries:
- 35 raw submissions
- After verification: **4 additional high-confidence**, 31 false positives

### Manual Browser Submissions

Ran targeted Playwright scripts on 25 discovered + false-positive entries:
- **9 submitted** (Cipinet, Crowd Reviews, The AI Generation, SaaSHub, AI Tools Marketer, AI Agents Directory, Foundr, Familyfriendlysites, Linkorado)
- 3 filled but no submit button found
- 13 no fields matched (JS-heavy sites)

Attempted 16 high-value directories (There's An AI For That, Toolify.ai, AlternativeTo, Futurepedia, G2, Capterra, Crunchbase, etc.):
- **2 submitted** (Toolify.ai, AlternativeTo)
- Most use React/Next.js multi-step wizards requiring manual browser interaction

### Final Submission Plan Status (318 entries)

| Status | Count | Description |
|---|---|---|
| **skipped** | 94 | Not relevant directories |
| **no_fields_matched** | 77 | Forms exist but fields didn't match |
| **submitted** | 45 | Confirmed form submissions |
| **no_form_found** | 45 | No submission form on page |
| **false_positive** | 18 | Clicked wrong button (login/register/etc.) |
| **skipped_paid** | 17 | Requires payment |
| **cloudflare_blocked** | 6 | Bot protection blocked |
| **filled_no_submit** | 5 | Fields filled but no submit button |
| **skipped_login_required** | 3 | Requires account creation |
| **submit_timeout** | 3 | Timed out during submission |
| **domain_parked** | 2 | Dead sites |
| **timeout** | 1 | Page didn't load |
| **blocked_cloudflare** | 1 | Cloudflare block |
| **submit_error** | 1 | Error during submission |

### Confirmed Submissions (45 directories)

| # | Directory | URL |
|---|---|---|
| 1 | App Rater | apprater.net |
| 2 | Business Software | business-software.com |
| 3 | EU-Startups | eu-startups.com |
| 4 | Exact Seek | exactseek.com |
| 5 | How to buy SaaS | howtobuysaas.com |
| 6 | Launching Next | launchingnext.com |
| 7 | LaunchingNext | launchingnext.com |
| 8 | Open Startup List | openstartuplist.com |
| 9 | Software Suggest | softwaresuggest.com |
| 10 | Startup Collections | startupcollections.com |
| 11 | Tech Faster | techfaster.com |
| 12 | Unboxing Startups | unboxingstartups.com |
| 13 | Viral Indian Diary | viralindiandiary.com |
| 14 | Webrazzi | webrazzi.com |
| 15 | Advanced Innovation | advanced-innovation.io |
| 16 | AI Directory | aidirectory.org |
| 17 | AI To Grow | aitogrow.com |
| 18 | AI Tools Guide | aitoolsguide.com |
| 19 | Anyfp | anyfp.com |
| 20 | Apps and Websites | mycloudmedia.co.uk |
| 21 | Free AI Tools Directory | free-ai-tools-directory.com |
| 22 | Future Tools | futuretools.io |
| 23 | Insidr AI | insidr.ai |
| 24 | Saas Po | saaspo.com |
| 25 | Smart Tools | smart-tools.ai |
| 26 | Super Tools | supertools.therundown.ai |
| 27 | AI Tools Club | aitoolsclub.com |
| 28 | AI Pulse | aipulse.ai |
| 29 | RankmyAI | rankmyai.com |
| 30 | NoCodeList | nocodelist.co |
| 31 | AI Tools Corner | aitoolscorner.com |
| 32 | AI Tools Love | aitools.love |
| 33 | AI Hustle | aihustle.tools |
| 34 | Cloudbooklet AI | cloudbooklet.net |
| 35 | Toolkitly | toolkitly.com |
| 36 | Freewebsubmission | freewebsubmission.com |
| 37 | Cipinet | cipinet.com |
| 38 | Crowd Reviews | crowdreviews.com |
| 39 | The AI Generation | theaigeneration.com |
| 40 | SaaSHub | saashub.com |
| 41 | AI Tools Marketer | aitoolsmarketer.com |
| 42 | AI Agents Directory | aiagentsdirectory.com |
| 43 | Foundr | foundr.ai |
| 44 | Familyfriendlysites | familyfriendlysites.com |
| 45 | Linkorado | linkorado.com |

---

## GitHub PRs Created

| Repo | Stars | PR | Status |
|---|---|---|---|
| wilsonfreitas/awesome-quant | 24,233 | [PR #256](https://github.com/wilsonfreitas/awesome-quant/pull/256) | Open |
| mahseema/awesome-ai-tools | 4,393 | [PR #619](https://github.com/mahseema/awesome-ai-tools/pull/619) | Open |
| paperswithbacktest/awesome-systematic-trading | 7,143 | [PR #22](https://github.com/paperswithbacktest/awesome-systematic-trading/pull/22) | Open |
| wangzhe3224/awesome-systematic-trading | 3,606 | [PR #41](https://github.com/wangzhe3224/awesome-systematic-trading/pull/41) | Open |

---

## Cumulative Totals

| Category | Count |
|---|---|
| **Directories submitted** | 45 |
| **GitHub PRs** | 4 (combined ~39K stars reach) |
| **Total submissions** | 49 |
| **Skipped (various reasons)** | 94 |
| **Paid directories** | 17 |
| **Google-login directories (untapped)** | ~105 |

---

## What Couldn't Be Automated

Most high-value directories use React/Next.js multi-step wizards requiring:
- **Manual browser interaction** (Playwright MCP in Cursor)
- **Google OAuth login** (user must complete auth)
- **CAPTCHA solving** on some sites

### Top candidates for manual follow-up:
- There's An AI For That (theresanaiforthat.com)
- Product Hunt (producthunt.com)
- G2 (g2.com)
- Capterra (capterra.com)
- Crunchbase (crunchbase.com)
- BetaPage (betapage.co)
- DevPost (devpost.com)

### Directories requiring payment:
AI Parabellum ($99+), Best of AI ($29), Futurepedia (free tier sold out), Jasmine Directory (review fee)

---

## Assets

| File | Purpose |
|---|---|
| `site-image.png` | goMacro.ai product screenshot |
| `logo.png` | goMacro.ai product logo |
