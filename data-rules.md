Public Dashboard — Data Rules

This file (wh-agent-office.html) lives in a SEPARATE, PUBLIC repo from wh-marketing, on purpose — so this dashboard can be public without exposing anything from the private repo that holds real account data.

The rule, absolute, no exceptions

This dashboard may only ever show:

Agent names (Carl, Chip, Duke, Scout, Radar, Nest)
Status words (working / done / waiting / flagged)
Short, qualitative notes ("spend on pace," "all gates clear," "nothing to report")

This dashboard must NEVER show:

Real dollar amounts or budget figures
Real percentages (CTR, conversion rates, any specific metric)
Account IDs, Customer IDs, Measurement IDs, or any identifying numbers
Real dates tied to specific findings if they could be cross- referenced with anything sensitive
Anything copied directly from ads-team-log.md or any agent's raw report in the private wh-marketing repo
Search engine protection

This page includes <meta name="robots" content="noindex, nofollow"> in its <head>. This is not real security — anyone with the direct link can still open it — but it does keep the page out of Google and other search results, so it won't be findable by strangers searching around. If this file is ever rebuilt from scratch, keep this tag. Combined with not sharing the link publicly and the data rule above (nothing sensitive ever appears here anyway), this is a reasonable free middle ground — not a substitute for real password protection (GitHub Pro / Netlify Pro) if genuine privacy is ever needed.

Why this matters

wh-marketing (the private repo) contains real business data — Google Ads account numbers, GA4 property IDs, real performance figures, compliance findings. This dashboard repo is intentionally public for easy hosting (GitHub Pages requires a public repo on the free plan). Anything written into this file is visible to anyone with the link, indefinitely. The separation between the two repos only works if this rule is followed every single time this file is updated — not just at the start.

When asked to update this dashboard with "live" data

Whoever (Claude Code or otherwise) updates this file using real information from ads-team-log.md must translate specifics into qualitative status before writing anything here — e.g. "conversions down 22%" becomes "performance dipped, under review," never the actual number. If in doubt about whether something is safe to include, leave it out and describe the situation in general terms instead.
