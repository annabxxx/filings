# HEAR SAY — Project Source of Truth

_Last rebuilt: 23 August 2026 (NZST)_

## Read this first

This file is the durable working context for HEAR SAY. Before changing, auditing or discussing the project, read this file and the current live site first so the project history does not have to be reconstructed from memory each time.

## What HEAR SAY is

HEAR SAY is an independent New Zealand public-interest publication intended to make difficult stories readable, testable and visible. It covers lived experience, access to justice, politics, old cases, evidence, public questions, right of reply and visible corrections.

The editorial idea is not “publish accusations”. It is: make a clear distinction between account, evidence, dispute, response and outcome. Serious claims must not be upgraded into fact merely because they are serious.

## Standing goals

HEAR SAY must become something a reader would deliberately open, read, share and return to. It should feel like a living publication rather than a collection of worthy information cards.

The standing priorities are:

- stronger journalism and narrative, not just slogans or mission statements;
- fresh dated updates and a clear reason to return today;
- evidence status and primary sources visible beside claims;
- right of reply and corrections kept on the same record;
- useful public participation: comments, polls, source leads and story submissions;
- excellent mobile reading and shareable social previews;
- search indexing, internal linking, RSS/news discovery and external visibility;
- reliable measurement of readership when a real analytics source exists;
- never invent visitor, reader, like, follower or engagement numbers.

## Live system

Public site: https://hear-say-nz.vercel.app

Hosting project: Vercel project `hear-say-nz`.

Backend: Supabase stores HEAR SAY comments, private story submissions, poll votes and news/article records.

Source repository currently used for durable project work: `annabxxx/filings`, folder `hear-say/`.

### Important source/deployment warning

The live Vercel publication and the `hear-say/` folder in GitHub have not always been the same build source. The live site currently contains a Political Circus section, Scott Guy room, Scott Watson tracker and several story pages that are not represented by the same file tree in the connected GitHub folder. Do not assume a GitHub commit is live. Verify the public URL after every deployment-related change.

## Live pages reviewed on 23 August 2026

The current sitemap contains 12 public URLs and all 12 were read and returned HTTP 200:

1. `/` — homepage
2. `/politics/election-2026/`
3. `/cold-cases/scott-guy/`
4. `/cold-cases/scott-watson/`
5. `/stories/erased-from-her-own-life/`
6. `/stories/the-justice-gap-has-numbers-now/`
7. `/stories/when-self-representation-means-doing-a-lawyers-job/`
8. `/stories/half-of-family-violence-victims-go-without-help/`
9. `/about/`
10. `/moderation/`
11. `/privacy/`
12. `/corrections/`

`robots.txt` allows crawling and points to a working sitemap. The site has had little or no reliable public-search footprint so far.

## Current editorial diagnosis

The problem is no longer simply visual design. The live site has strong headlines, labels and responsible disclaimers, but most substantive pages are too thin to reward a click.

Typical current pattern: one proposition or statistic, one or two paragraphs, one source link, then the page ends. That is a briefing card, not yet a compelling article.

The next standard for substantive pages should include, where the evidence supports it:

- a strong, specific lead that tells the reader why this matters now;
- a dated “what changed” or update line;
- a concise chronology/timeline;
- what is established by primary or reliable sources;
- what remains disputed or unknown;
- the strongest counter-position or alternative interpretation;
- why the issue matters in practice;
- source links and evidence status;
- right-of-reply status where relevant;
- related reading / next story;
- update and correction history;
- social-sharing metadata and a strong preview image.

Do not pad pages to hit a word count. Add depth only where there is evidence, context or useful explanation.

## Page-specific diagnosis

### Homepage

Energetic but still too category-led. It needs a real front-page hierarchy: one dominant lead, fresh dated updates, a “what changed today” strip, stronger secondary headlines and fewer generic slogans. Any countdown must be calculated from the current date rather than left stale.

### Election 2026

Good structure for poll watch, receipts and participation, but it is static. It needs current dated claims, policy changes, polling updates, source checks and a visible update log. A politics desk should feel live.

### Scott Guy

Responsible acquittal safeguard and source links, but the room is far too thin. It needs a factual chronology, public-record map, what is established, what remains unknown, key investigative milestones and a clear separation between public-record evidence and reader theories.

### Scott Watson

Correctly states the current legal position and limited Supreme Court issue, but it needs a fuller procedural timeline, what the disputed identification evidence was, why the appellate issue matters, the competing arguments and dated hearing updates.

### Erased from her own life

This is potentially the central lived-experience feature but is currently only a few paragraphs. It should become a structured long-form account with a chronology, clearly labelled first-person account, an evidence matrix, documented events that can safely be published, disputed points, right of reply, and practical consequences. Private legal material must not be published automatically.

### Justice gap / self-representation / family-violence stories

Each currently rests mainly on one statistic or proposition plus a source link. They need context: methodology, what the number does and does not prove, who is most affected where known, practical implications, counterpoints/limitations and links into related HEAR SAY lived-experience reporting.

### About / Moderation / Privacy / Corrections

These trust pages are useful but too short. They should explain ownership/editorial responsibility, how evidence is checked, how submissions are handled, moderation criteria, privacy practices, corrections workflow, right-of-reply process, and how readers can challenge an error.

## Data and privacy boundary

Connected Gmail contains extensive private legal, court and personal correspondence. Gmail may be used to understand chronology or locate material when specifically relevant, but private email content is **not** a HEAR SAY content feed and must never be published automatically.

Before any private document or email becomes public HEAR SAY material, it must be checked for relevance, accuracy, privacy, court restrictions, identifying information about children, legal risk and whether publication is genuinely necessary.

## Audience and measurement

The public site currently has forms for comments, story submissions and polls. Earlier checks showed no reader comments, no story submissions and no poll votes. Re-check the connected database rather than relying on this historical state.

Do not treat HTTP requests, runtime invocations, deployments or bot traffic as readership. If a proper Web Analytics or first-party visitor metric is not available, state that readership is unavailable.

## Discovery / SEO state

Crawl access and sitemap exist. The historical problem has been indexing and authority, not a robots block. Continue improving canonical tags, article metadata, Open Graph/Twitter cards, structured data, dated sitemaps/news sitemap/RSS, internal links and — crucially — genuinely useful reporting that other sites have a reason to link to.

## Build order from here

1. Resolve or document the live-source/deployment path so source changes reliably reach production.
2. Replace stale homepage material with a true current front page.
3. Turn the four thin story pages into real articles using primary sources and clearly labelled uncertainty.
4. Expand Scott Guy and Scott Watson into public-record case files, not theory landing pages.
5. Turn Election 2026 into a dated running desk with fresh claim checks.
6. Expand trust/policy pages.
7. Add legitimate analytics and conversion events if available and privacy-appropriate.
8. Build distribution around individual useful stories rather than generic HEAR SAY promotion.

## Non-negotiables

- Do not fabricate evidence, facts, readership, comments or engagement.
- Do not publish private Gmail/court material merely because it exists.
- Do not describe acquitted or unconvicted people as guilty.
- Do not confuse lived experience with a judicial finding.
- Keep corrections visible.
- Keep substantive right of reply connected to the criticism it answers.
- Verify the live site after changes; repository state alone is not proof of deployment.
