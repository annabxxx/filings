# HEAR SAY — Full Live-Site Audit

_Date: 23 August 2026 (NZST)_

## Scope

Every URL in the live sitemap at `https://hear-say-nz.vercel.app/sitemap.xml` was reviewed. All 12 public URLs returned HTTP 200 at the time of review.

## Executive finding

HEAR SAY has a clearer identity than it did at launch, but the content layer remains too thin. The site is visually energetic and unusually careful about labels, acquittals, right of reply and evidential status. Those are strengths. The weak point is that most clicks lead to pages that stop before the reporting becomes satisfying.

The site currently over-invests in framing (“bring the receipt”, “public square”, “what should be checked”) and under-invests in the thing a reader came for: the actual story, chronology, evidence, competing explanation and new development.

## Page audit

### `/`

**What works:** strong visual hierarchy, recognisable brand voice, clear topic lanes, politics/case/story entry points, public participation prompts.

**What weakens it:** too many slogans and category cards; stale countdown text; no true “latest” desk; few dated updates; the homepage does not immediately tell a repeat visitor what has changed since yesterday.

**Rebuild:** lead with one genuinely strong current item, then a compact live board with dated updates. Use a “NEW / UPDATED / EXPLAINER / OPEN QUESTION” vocabulary. Put evidence/status labels on cards. Make every homepage card link to a page with enough depth to justify the click.

### `/politics/election-2026/`

**What works:** neutral/non-endorsement framing, poll context, receipts concept, right of reply, public issue poll.

**What weakens it:** static snapshot; countdown still anchored to 17 August; two older poll reports dominate; receipts section explains the concept rather than actually checking enough claims.

**Rebuild:** running dated election desk. Add newest polling with date/methodology/source; claim-check entries; “changed position” entries with before/after quotes and sources; party reply status; coalition arithmetic only when sourced; a chronological update log.

### `/cold-cases/scott-guy/`

**What works:** accurate acquittal safeguard; clear legal-status rule; police/RNZ sources; falsifiable-theory standard.

**What weakens it:** three factual cards are not a case file. The reader receives almost no chronology, investigative background, evidential map or explanation of what remains unresolved.

**Rebuild:** public-record chronology; established facts; investigative milestones; evidence/source index; what the acquittal means legally; what remains unknown; clearly separated reader theories; corrections/right-of-reply box.

### `/cold-cases/scott-watson/`

**What works:** convictions and Supreme Court leave issue are accurately separated; primary court source is linked; opinion poll is labelled as opinion.

**What weakens it:** the reader is told the appellate question but not enough about the identification evidence, prior appeal history or why the issue matters.

**Rebuild:** procedural timeline from conviction through current Supreme Court appeal; explain the Guy Wallace identification issue in plain English; set out the competing appellate positions without deciding them; date every hearing update; link directly to primary judgments/case information.

### `/stories/erased-from-her-own-life/`

**What works:** lived-experience label; explicit warning that it is not a judicial finding; evidence under review; right of reply open.

**What weakens it:** this is only a short abstract of a potentially major feature. The reader never sees a meaningful chronology, concrete documented moments, turning points, consequences or the boundary between documented and disputed claims.

**Rebuild:** long-form structure with a human opening; chronology; “the contributor says”; “the record shows” where safe and verifiable; evidence matrix; disputed/unknown points; practical consequences; right-of-reply; corrections/update history. Do not publish private or restricted material merely to add drama.

### `/stories/the-justice-gap-has-numbers-now/`

**What works:** memorable Ministry-backed statistics and source link.

**What weakens it:** one statistic is being asked to carry an entire article.

**Rebuild:** explain the survey, concentration of legal problems, problem types where available, what “potentially legal issue” means, limitations, why people take no action, implications for policy and links to lived-experience reporting.

### `/stories/when-self-representation-means-doing-a-lawyers-job/`

**What works:** simple articulation of procedural tasks, primary Ministry source.

**What weakens it:** no depth beyond the four-task summary.

**Rebuild:** walk the reader through each procedural burden; distinguish legal right from practical capacity; explain assistance that does exist; include limitations/counterpoint; connect the issue to wider access-to-justice research.

### `/stories/half-of-family-violence-victims-go-without-help/`

**What works:** strong public-interest statistic and primary Ministry source.

**What weakens it:** the article does not unpack what “without help” means, survey limitations, service barriers or the significance of incident frequency.

**Rebuild:** explain methodology, definitions and limits; distinguish incidence, prevalence and help-seeking; add service-system context from reliable sources; avoid implying a reason for non-use that the source does not establish.

### `/about/`

**What works:** concise explanation of labels.

**What weakens it:** does not establish enough institutional trust. Readers cannot learn much about editorial responsibility, methodology or who is accountable for corrections.

**Rebuild:** mission, editorial model, independence/ownership statement, source hierarchy, right-of-reply method, funding/advertising position if applicable, contact/corrections route, beta status and limits.

### `/moderation/`

**What works:** strong safeguards for politics and old cases.

**What weakens it:** too short for a platform inviting public submissions.

**Rebuild:** moderation decision criteria, prohibited content, evidential threshold for serious allegations, privacy/doxxing rules, handling of named living persons, appeals/reconsideration process, repeat abuse/spam, correction vs removal policy.

### `/privacy/`

**What works:** tells users not to submit unnecessary sensitive information and distinguishes public comments from private submissions.

**What weakens it:** not yet a robust privacy notice.

**Rebuild:** what data is collected, why, where it is stored, retention, publication status, moderation access, deletion/correction request route, cookies/analytics when enabled, third-party processors, contact route, children/restricted material warning.

### `/corrections/`

**What works:** visible record of site changes and corrections principle.

**What weakens it:** currently more changelog than corrections register.

**Rebuild:** distinguish editorial update from factual correction; show date, original wording/issue, correction, reason and affected URL; link material replies to the story they answer.

## Cross-site structural weaknesses

### 1. Thin-content problem

Most substantive pages currently end after one statistic or proposition. Depth should come from reporting, not padding. Every major page should answer: what happened, what do reliable sources establish, what is disputed, what has changed, why does it matter, and where can the reader go next?

### 2. Freshness problem

A return visitor needs to see something dated and new. Static countdowns and older polling make the publication feel abandoned even when the infrastructure is live.

### 3. Internal journey problem

Pages need related stories, “next” links, topic hubs and source cross-links. A reader who finishes one piece should be given a compelling second click.

### 4. Search/social consistency

Every editorial page should have canonical URL, index directive, description, Open Graph/Twitter metadata, appropriate article structured data, publication/update dates and a large share image. Sitemap `lastmod`, RSS and news sitemap should reflect real publication/update dates.

### 5. Trust pages need depth

The site asks readers to entrust it with allegations, personal stories and source leads. Its About, Privacy and Moderation pages need to be substantially stronger than ordinary marketing copy.

### 6. Measurement gap

Do not infer readership from requests, serverless invocations or deployments. Add legitimate privacy-appropriate analytics if possible, then track page views, unique visitors, referral sources, story-to-story clicks, share-button use, comment starts/completions and submission conversions.

## Content template for future HEAR SAY articles

1. Headline: specific, non-generic, worth the click.
2. Standfirst: what the reader will actually learn.
3. Status row: type, published/updated date, evidence status, reply status.
4. The lead: the most important/new fact or human moment.
5. What happened: concise chronology.
6. What the record establishes: primary/reliable sources.
7. What remains disputed or unknown.
8. The strongest alternative/counter-position.
9. Why it matters in practice.
10. Sources and documents.
11. Right of reply / corrections.
12. Related reading / next step.

## Editorial rule

HEAR SAY becomes stronger by being more specific, more sourced and more useful — not by sounding angrier or making allegations more absolute.
