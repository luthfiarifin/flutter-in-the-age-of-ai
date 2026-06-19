# Flutter in the Age of AI — Sourced Data Report

> Research compiled for a conference talk arguing that junior software engineering roles are shrinking while demand shifts toward senior / full-stack product engineers, with AI as a driver. Data range: 2023–2026. Every figure carries source, date, and link. Estimates/projections/opinions are flagged vs. measured figures.

## Executive Summary

The evidence that **junior/entry-level software roles have shrunk sharply since late 2022 is strong**, backed by multiple primary datasets (Indeed, SignalFire, ADP, Handshake). The evidence that **demand and pay are concentrating at senior levels is also solid** (Indeed experience-requirement data, Levels.fyi). The weakest link — and the one the thesis leans on hardest — is **causation: that AI is the *main* driver.** The strongest pro-AI signal (Stanford "Canaries in the Coal Mine") is real but contested, and three credible institutions (Yale Budget Lab, NY Fed, Goldman Sachs) find **no clear AI fingerprint**, pointing instead to macro factors that began *before* ChatGPT. Recommended framing: AI is a **demonstrated accelerant** of a multi-cause junior-hiring squeeze — not a proven sole cause.

---

## 1. Junior / Entry-Level Role Decline

- New grads were **~7% of Big Tech hires in 2024**, down ~25% vs 2023 and **>50% vs 2019** — SignalFire State of Tech Talent 2025 — May 2025 — https://www.signalfire.com/blog/signalfire-state-of-talent-report-2025 — *Measured (vendor, unaudited).*
- At startups, new grads fell to **under 6% of hires in 2024** (down >30% vs 2019) — SignalFire 2025 — May 2025 — *Measured.*
- Share of new CS grads at the "Magnificent Seven" **dropped >half since 2022** — SignalFire 2025 — May 2025 — *Measured.*
- **Junior titles down 34% vs Feb 2020; senior/manager down only 19%** — Indeed Hiring Lab — Jul 30, 2025 — https://www.hiringlab.org/2025/07/30/experience-requirements-have-tightened-amid-the-tech-hiring-freeze/ — *Measured (postings).*
- Junior roles **down 7% YoY** vs senior **up 4% YoY** (Aug 2024 → Aug 2025) — Indeed Hiring Lab — Sept 25, 2025 — https://www.hiringlab.org/2025/09/25/september-labor-market-squeeze-on-new-entrants/ — *Measured.*
- Class of 2025: Handshake job postings **fell ~15% YoY** while applications per job **rose ~30%** — Handshake — 2025 — https://joinhandshake.com/network-trends/class-of-2025-graduation/ — *Measured (platform).*
- Counter-signal: software developers/QA projected to **grow 15% 2024–2034** (~129,200 openings/yr) — BLS Occupational Outlook Handbook — https://www.bls.gov/ooh/computer-and-information-technology/software-developers.htm — *Projection (no seniority split).*

**Reliability:** Strong. Multiple independent primary datasets agree junior hiring fell harder than senior. SignalFire is vendor-reported (flag it); Indeed and Handshake are robust.

---

## 2. AI as the Driver

- Employment for **22–25-year-old software developers fell ~20% from its late-2022 peak to July 2025**, while older devs in the same role held flat/grew — Brynjolfsson, Chandar & Chen, Stanford Digital Economy Lab ("Canaries in the Coal Mine?") — first released Aug 26, 2025 (rev. Nov 2025) — https://digitaleconomy.stanford.edu/publication/canaries-in-the-coal-mine-six-facts-about-the-recent-employment-effects-of-artificial-intelligence/ — *Measured raw decline (ADP payroll).*
  - ⚠️ **Three numbers circulate:** ~6% (raw, all high-exposure jobs), ~13% (relative/regression-adjusted), ~20% (raw, software devs specifically). Different cuts, not contradictions — state which you mean.
- Young adults in high-AI-exposure jobs **down ~13% since 2022**, but authors find only *correlation* "for younger workers" and **explicitly decline to claim causation** — Dallas Fed (Atkinson & Yamco) — Jan 6, 2026 — https://www.dallasfed.org/research/economics/2026/0106 — *Measured + honest causation caveat.*
- Developers using GitHub Copilot completed a task **~55.8% faster**, with **less-experienced developers benefiting most** — GitHub / Kalliamvakou et al. — updated May 21, 2024 — https://github.blog/news-insights/research/research-quantifying-github-copilots-impact-on-developer-productivity-and-happiness/ — *Measured (single synthetic task; not production work).*
- AI cuts time to write/document code by **~half**, refactor by **~two-thirds**, gains concentrated in *routine* tasks — McKinsey — 2023 — https://www.mckinsey.com/capabilities/tech-and-ai/our-insights/unleashing-developer-productivity-with-generative-ai — *Measured lab study (vendor-adjacent).*
- AI coding capability: **SWE-bench performance rose 67.3 percentage points from 2023 to 2024** — Stanford HAI AI Index 2025 — Apr 2025 — https://hai.stanford.edu/ai-index/2025-ai-index-report — *Measured benchmark.*
- **40% of employers expect to reduce headcount where AI can automate tasks** (but 170M jobs created vs 92M displaced by 2030) — WEF Future of Jobs 2025 — Jan 2025 — https://www.weforum.org/publications/the-future-of-jobs-report-2025/ — *Survey/projection (employer intentions).*

**Reliability:** The age-vs-exposure gradient (young devs fall, senior devs don't) is the strongest fingerprint pointing at AI. But late-2022 also ended the cheap-money hiring boom — a confounder moving at the same time. Causation is suggestive and strengthening, **not proven**; the researchers themselves are cautious. Do not present AI as the sole proven cause.

---

## 3. Shift Toward Senior / Product / Full-Stack Engineers

- Share of US tech postings requiring **5+ years experience rose 37% → 42%** (Q2 2022 → Q2 2025); 2–4 yr postings fell 46% → 40% — Indeed Hiring Lab — Jul 30, 2025 — https://www.hiringlab.org/2025/07/30/experience-requirements-have-tightened-amid-the-tech-hiring-freeze/ — *Measured.* **(Strongest "shift up" stat.)**
- Comp concentrating up-level: **Staff Engineer median ~$457K (+7.5% YoY)** vs **Senior ~$312K (+4.2%)** — Levels.fyi 2025 End-of-Year Pay Report — Dec 2025 — https://www.levels.fyi/2025/ — *Measured (self-reported, large sample).*
- AI pay premium widens with seniority: **Staff +18.7%, Senior +14.2%, Mid +11.9%, Entry only +6.2% (down from 10.7% in 2024)** — Levels.fyi AI Engineer Compensation Trends Q3 2025 — https://www.levels.fyi/blog/ai-engineer-compensation-trends-q3-2025.html — *Measured.*
- "Forward-Deployed Engineer" postings **up 800%+ in 2025** (hard-data proxy for the generalist/product-engineer trend) — FT/Indeed via Fast Company — Sept 2025 — https://www.fastcompany.com/91435680/postings-for-this-ai-job-are-up-800 — *Measured (secondary; verify against FT).*
- **AI Engineer is LinkedIn's #1 fastest-growing role** (2025 & 2026) — LinkedIn Jobs on the Rise 2026 — Jan 2026 — https://www.linkedin.com/pulse/linkedin-jobs-rise-2026-25-fastest-growing-roles-us-linkedin-news-dlb1c — *Measured.*
- Skills: **70% of employers rate analytical thinking the #1 core skill**; AI & big data is the #1 fastest-growing skill — WEF Future of Jobs 2025 — Jan 2025 — https://www.weforum.org/publications/the-future-of-jobs-report-2025/ — *Survey.*
- **84% of developers use/plan to use AI tools, but only 3% "highly trust" outputs and 46% distrust accuracy** — Stack Overflow 2025 Developer Survey — Dec 2025 — https://survey.stackoverflow.co/2025/ai/ — *Survey.*

**Reliability:** The senior-vs-junior posting split and comp-by-level data are measured and primary — strong. **The "product engineer" title is mostly anecdotal** — no robust posting-growth dataset exists. Treat "product engineer" as a cultural/qualitative signal; use Forward-Deployed Engineer as the hard-data analog. "Full-stack demand" is mostly recruiter survey sentiment.

---

## 4. Flutter / Mobile Context

- **Flutter used by 9.4%** of all respondents; **Dart by 6.0%** (2024) → **Dart 5.9%** (2025, slight slip) — Stack Overflow Developer Surveys — 2024/2025 — https://survey.stackoverflow.co/2024/technology/ and https://survey.stackoverflow.co/2025/technology/ — *Measured (primary, self-selected sample).*
- **Over 1 million monthly active Flutter developers**; Flutter powers **nearly 30% of all new iOS apps** (up from ~10% in 2021, Apptopia data) — Google Developers Blog, "Celebrating Flutter's Production Era" — Dec 17, 2024 — https://developers.googleblog.com/celebrating-flutters-production-era/ — *First-party measured (Google is an interested party).* **Strongest Flutter growth stat.**
- Developer-usage share (Statista series): **Flutter 46% vs React Native 32% (2023)**; Flutter overtook RN ~2021 — Statista — 2023 — *Estimate/survey, paywalled, secondary-confirmed. Call it developer-usage share, NOT market share.*
- Google laid off staff across **Flutter/Dart/Python Core teams (~200 total, no per-team breakdown)** in April 2024 — TechCrunch — Apr 29, 2024 — https://techcrunch.com/2024/05/01/google-lays-off-staff-from-flutter-dart-python-weeks-before-its-developer-conference/ — *High reliability (the ~200 is across all teams, not Flutter alone).*
- Flutter forked as **"Flock"** (Oct 2024) by an ex-team member citing a ~50-person frozen team — DevClass — Oct 30, 2024 — https://www.devclass.com/development/2024/10/30/flutter-forked-as-flock-developer-cites-company-wide-issues-at-google/1628290 — *Event high-reliability; team-size claims are one ex-insider's estimate.*

**Reliability:** Stack Overflow and Google first-party stats are solid. **Mobile/Flutter-specific hiring data is genuinely thin** — no authoritative Flutter-specific job-count dataset (demand is bucketed under "mobile/iOS/Android developer"). 2025 SO pro-dev figures suggesting React Native edged ahead of Flutter need primary verification before quoting.

---

## 5. Counter-Evidence (lead with these for credibility)

- **No discernible AI labor disruption** 33 months after ChatGPT; impact on AI-exposed employment "close to zero and cannot be statistically distinguished from it" — Yale Budget Lab — Oct 2025 — https://budgetlab.yale.edu/research/evaluating-impact-ai-labor-market-current-state-affairs — *Measured (CPS data through Aug 2025).*
- "**Little indication of a distinct AI-driven decline**"; the relative decline in AI-exposed occupations **began before ChatGPT** and junior/senior demand "is moving broadly in parallel" — NY Fed Liberty Street Economics — May 14, 2026 — https://libertystreeteconomics.newyorkfed.org/2026/05/do-job-postings-show-early-labor-market-effects-of-ai/ — *Measured.* **(Directly rebuts "AI is singling out juniors.")**
- **No significant statistical correlation between AI exposure and job outcomes**; only ~2.5% of US employment at near-term displacement risk — Goldman Sachs Research — 2025 — https://www.goldmansachs.com/insights/articles/how-will-ai-affect-the-us-labor-market — *Measured + modeled.*
- **Section 174 tax change** (effective 2022): forces 5-yr amortization of US software dev costs, raising the cost of engineers; analyst estimate ~20,000 SWE jobs eliminated — Pragmatic Engineer — Jan 2024, upd. June 2025 — https://blog.pragmaticengineer.com/section-174/ — *Estimate.* **Nuance:** the author himself thinks the end of ZIRP mattered more — don't oversell.
- **End of ZIRP / pandemic overhiring**: aggressive Fed tightening from March 2022; AI-exposed-role postings began declining March–April 2022, *before* ChatGPT (Nov 2022) — The Hill — 2024 — https://thehill.com/policy/technology/4478773-why-tech-companies-are-laying-off-thousands-of-workers/ — *Expert opinion + measured timing.*
- **"The AI job scare needs better evidence"**: separation rates unchanged, CS wage weakness began early 2022 (pre-ChatGPT) — AEI (Pethokoukis) — Jan 12, 2026 — https://www.aei.org/economics/the-ai-job-scare-needs-better-evidence/ — *Opinion citing Fed data.*
- **Methodological critique of the Stanford study**: fails to control for immigration/OPT surge, survivorship bias — PolicySphere — Aug 27, 2025 — https://policysphere.com/morning-briefing/ — *Opinion/critique (not peer-reviewed).*
- **Entry-level struggles mirror a marketwide decline**, "not employers pulling back on junior roles specifically" — Indeed Hiring Lab — Sept 25, 2025 — https://www.hiringlab.org/2025/09/25/september-labor-market-squeeze-on-new-entrants/ — *Measured.*

**Sharpest counter-point:** the timing. Multiple independent sources show the entry-level/AI-exposed decline began **early-to-mid 2022, before ChatGPT** — if AI were the driver, you'd expect acceleration *after* Nov 2022, but the trend flattened.

---

## 6. Talk-Ready Data Points (the 5–7 strongest, most defensible)

1. **New grads were just ~7% of Big Tech hires in 2024 — down >50% vs 2019.** (SignalFire, May 2025)
2. **Tech postings requiring 5+ years experience rose from 37% to 42% (2022→2025); junior titles fell 34% vs senior titles' 19%.** (Indeed Hiring Lab, Jul 2025)
3. **Employment for 22–25-year-old software developers fell ~20% from its late-2022 peak to July 2025, while senior devs held flat.** (Stanford Digital Economy Lab / ADP, Aug 2025)
4. **Developers using GitHub Copilot finished a coding task ~55.8% faster — and less-experienced developers benefited most.** (GitHub, 2024)
5. **Staff Engineer median comp ~$457K (+7.5% YoY) vs Senior ~$312K (+4.2%) — pay accelerating fastest at the top.** (Levels.fyi, Dec 2025)
6. **Flutter powers nearly 30% of all new iOS apps (up from ~10% in 2021), with 1M+ monthly active developers.** (Google, Dec 2024)
7. **Honest counterweight: 33 months after ChatGPT, the Yale Budget Lab found no statistically discernible AI impact on employment in exposed occupations.** (Yale Budget Lab, Oct 2025)

---

## 7. Gaps & Cautions

- **Causation is the soft spot.** "AI is the *main* driver" is not provable from current data. The defensible claim is "young developers' employment is falling exactly where AI is most capable, while senior employment holds" — pair it with the macro caveat (ZIRP / Section 174 / overhiring all hit in 2022 too).
- **Watch the Stanford numbers.** ~6% (raw, all exposed), ~13% (regression-adjusted), ~20% (raw, software devs). Say which you're citing; the ~20% dev figure is most relevant but is the raw single-occupation cut.
- **SignalFire is vendor-reported** and unaudited — attribute it as such.
- **"Product engineer" has no hard posting-growth data** — present as qualitative; use Forward-Deployed Engineer (800%+) as the measured proxy, and verify it against the FT primary before a slide.
- **BLS (+15% growth) and CompTIA (~3–4% tech unemployment)** sit in tension with the postings-collapse story; reconcile as "overall/senior demand holds; the junior on-ramp is what's shrinking."
- **Flutter-specific hiring data effectively doesn't exist** — don't size the Flutter job market from any single source. The 2025 Stack Overflow figure hinting React Native overtook Flutter among pros needs primary verification.
- **Verify-before-slide list:** SignalFire exact percentages (own page), NY Fed recent-grad quarter, Layoffs.fyi live totals the week of the talk, FT/Indeed FDE 800% figure, Yale and EPI verbatim quotes (some fetches were blocked and rely on search summaries).
- **Drop this one:** a "129% higher unemployment rate for junior developers" stat circulates in WEF-adjacent coverage but **could not be verified against the WEF primary PDF** — do not present it as a WEF figure.
