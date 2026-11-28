## 3. Free edu email providers & alumni/lifelong routes

**First, the distinction that decides everything.** A *real mailbox on a school domain* (you can send, reset, and log in) behaves very differently from a *forwarding alias* (receive-only), and both differ from a *lookalike domain* (`edumaili.com`, `.edu.pl`). SheerID's own product team now says a college address "is no longer enough to verify student enrollment. Many graduates still have access to these accounts, creating a major student offer loophole" ([SheerID, May 2026](https://www.sheerid.com/business/blog/prevent-student-offer-abuse-replace-edu-email-verification/)). So alumni routes buy you *deliverability* and *institutional legitimacy*, not automatic discount eligibility. SheerID only verifies graduates if the brand enabled the US-only **"University graduates"** sub-segment ([SheerID knowledge base](https://sheerid.zendesk.com/hc/en-us/articles/26408738570779-Student-audience-overview)); UNiDAYS expires your student membership and downgrades you to **GRADLiFE** for 3 years, with a reduced benefit set ([UNiDAYS GRADLiFE FAQ](https://www.myunidays.com/GB/en-GB/content/gradlife-download)).

### 3.1 Alumni retention: the ones that still work, and the wave that killed the rest

Some universities still run genuine alumni mailboxes or forwarding, and are the cheapest legitimate route if you already hold the degree:

- **MIT** — `@alum.mit.edu` is a full Outlook mailbox marketed as "Email for Life" ([tracker](https://www.dukebrokenpromises.com/tracker)).
- **Stanford** — free `@alumni.stanford.edu` mailbox for anyone enrolled three quarters or more, no membership fee, though terms reserve the right to end it.
- **Yale** — YaleMail on `@aya.yale.edu`, 5 GB cap.
- **Princeton** — free alumni Workspace mailbox replaced plain forwarding; Class of 2026 onward get no forwarding.
- **Michigan** — `@umich.edu` forwarding retained free.
- **Harvard** — reversed its 2022 shutdown after a ~2,800-signature petition; `@post.harvard.edu` / `@alumni.harvard.edu` forwarding still runs through an outside vendor — **forward-only, cannot send**, which matters for SheerID email-loop codes.
- **Cambridge (UK)** — free `@cantab.ac.uk` mailbox for graduates and former postdocs; you must activate it before your `@cam` account closes ([Cambridge alumni email FAQ](https://www.alumni.cam.ac.uk/benefits/alumni-email/faqs)).

The counter-list is the useful part, because it shows how little "lifetime" means contractually: **Duke** is shutting forwarding off 31 Jan 2027 with no replacement; **Temple** closed accounts in 2025 and now expires them one year after graduation; **Ohio State** ended forwarding 31 Dec 2024 and deleted accounts 1 Apr 2025, data unrecoverable; **CU Boulder** announced termination, was sued in a class action, and only extended access to alumni who opted in and had used the account. Duke's FAQ states "lifetime" never guaranteed perpetuity — the service was always subject to "technological feasibility" ([Duke Chronicle](https://dukechronicle.com/article/duke-university-ends-alumni-lifetime-access-to-email-address-forwarding-edu-service-20260518)). **Oxford** discontinued alumni addresses outright; only legacy users are supported ([petition](https://www.change.org/p/bring-back-oxford-university-alumni-email-addresses-for-all-graduates)). **UC Davis** moved its alumni address behind an **$850 lifetime association membership** ([Inside Higher Ed](https://www.insidehighered.com/news/tech-innovation/2023/07/25/college-email-life-risk-google-limits-free-storage)).

Driver of the whole collapse: Google ended free education storage, caps institutions at a pooled 100 TB, and bulk-sender authentication rules (Google/Yahoo Feb 2024, Microsoft May 2025) made naive forwarding fail SPF/DKIM/DMARC. Vendors now sell schools cheap authenticated forwarding instead — [Alumni Forwarding](https://alumniforwarding.com) quotes ~$1,400/yr for 10k alumni vs ~$36,000 for Workspace — which is why some programmes survive as aliases rather than mailboxes.

### 3.2 Enrollment routes that cost ~nothing (community-college adjacent)

If you need *active student* status rather than an alumni alias, the cheapest hinges are open-access community colleges and free-tuition states:

- **Foothill College (CA)** — non-credit courses are tuition-free, open to anyone 18+, unlimited repeats, and enrolled students can request an `@student.foothill.edu` account. The catch is explicit on the college's own page: the account is "only intended for registered students" and is **deactivated one quarter** after you stop taking classes ([Foothill email policy](https://www.foothill.edu/apply-and-register/email-communications.html), [non-credit FAQ](https://www.foothill.edu/non-credit/faq.html)).
- **New Mexico** — Opportunity Scholarship covers up to 100% of tuition and required fees at 29 public institutions for established residents enrolled in at least 6 credit hours ([NM HED](https://hed.nm.gov/free-college-for-new-mexico)).
- **Senior waivers (60+)** — several states waive tuition and fees for older residents, e.g. NVCC for Virginia residents 60+ ([NVCC](https://www.nvcc.edu/admissions/apply/senior-citizens.html)), MassBay for 60+ ([MassBay](https://www.massbay.edu/senior-citizen-student)). This is the closest thing to a genuine "lifelong learner" mailbox: cheap, renewable, and *real* enrollment.
- **University of the People** — tuition-free, accredited, but not free: $60 application (waivers exist) plus $120–240 per course assessment, email issued after admission ([walkthrough](https://www.freetricksworld.com/how-to-get-edu-email-for-free)). Address is on a subdomain (`@my.uopeople.edu`).

### 3.3 What does *not* work anymore (commonly recommended, now dead)

- **ASU Universal Learner Courses** — was the standard "no application needed" trick. ASU now says plainly: no, you don't get an `asu.edu` address; emails are only issued where a course requires one, and access ends when you stop ([ASU ULC FAQ](https://ulc.asu.edu/help-center/faqs)).
- **edX/Coursera verified certificates** — no institutional mailbox at all.
- **Disposable "edu" temp mail** — `edumaili.com` sells it honestly: "an address from Edumaili is a privacy tool, not a student credential… a disposable address will not pass their checks," and `.edu.pl` is Polish, not US `.edu` ([edumaili](https://edumaili.com)). Useful for grabbing a confirmation link, useless for Spotify.

### 3.4 Bought accounts

Marketplaces like [Accsmarket](https://www.accsmarket.com/en/rules) sell working institutional logins. Read the terms before paying: the guarantee is **48 hours of validity only**, responsibility transfers to you on purchase, order downloads vanish after 30 days, and the seller keeps no history. You typically must change the password immediately, and login hygiene matters (their rules demand one clean residential IP and one device per account). That is fine for a one-off discount; it is not a durable identity.

### 3.5 Comparison

| Provider | How obtained | Cost | Works for SheerID/UNiDAYS? | Risk of revocation |
|---|---|---|---|---|
| MIT / Stanford / Yale / Princeton / Michigan alumni mail | Graduate, then activate | $0 | Sometimes — only if brand enabled SheerID's graduate segment; UNiDAYS → GRADLiFE | Low–medium; terms reserved, storage caps |
| Harvard `@post.harvard.edu` | Alumni registration | $0 | Weak — forward-only, can't send or receive loop code reliably | Medium; survived one shutdown attempt |
| Cambridge `@cantab.ac.uk` | Graduate, activate before `@cam` closes | $0 | Sometimes — UK institution, not US graduate segment | Low–medium; limited to Outlook web |
| Foothill / De Anza non-credit | Apply, register any free non-credit class | $0 (CA) | Yes while enrolled | High — deactivated one quarter after you stop |
| NM public college (Opportunity Schl.) | Residency + 6 credit hours | $0 tuition (resident) | Yes while enrolled | Medium — residency and credit-load rules |
| Senior waiver (NVCC, MassBay, etc.) | Age 60+ + state residency | $0 | Yes while enrolled (credit courses) | Medium — course cap, residency |
| University of the People | Apply, pay, enroll | $60 + $120–240/course | Yes (accredited), address on subdomain | Medium — fees, subdomain oddities |
| UC Davis alumni address | $850 lifetime association membership | $850 once | Sometimes (graduate segment) | Low |
| Illinois Alumni Association | Open to general public, annual membership | $150/yr | Weak — membership, not enrollment | Low cost, high ongoing spend |
| Bought login (Accsmarket et al.) | Purchase | ~$2–20 | Inconsistent; passes suffix checks only | High — 48h guarantee, seller may hold recovery |
| Temp "edu" mail (edumaili, Boomlify) | Instant web form | $0 | No — not a credential | Total — expires in minutes |

**Flag as scammy or oversold:** any site promising a "lifetime .edu for $10"; resold accounts advertised as *your own* (the original registrant can reclaim via the school's password reset); `.edu.xx` lookalikes sold as ".edu"; and YouTube/Instagram "instant .edu" methods that are really just temp mail. Reputable schools never sell addresses, so a mailbox you cannot log into the school portal for is a rental, not an identity.

**Practical note:** if the goal is a discount, an alumni alias usually beats a bought login only when the brand accepts graduates; if it must be *student* status, a free non-credit community-college class is the cheapest honest route, and you must stay enrolled to keep it. Either way, set the address as a forwarding target to a mailbox you control, and never make it your only recovery address.