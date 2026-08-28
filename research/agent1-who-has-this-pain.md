# Market Validation Research: Who Has This Pain (Redline)

Research goal: find real, sourced accounts of people harmed by contract/lease/ToS/freelance-agreement terms they did not understand or did not notice at signing time.

Method note: Direct Reddit search/fetch was largely blocked in this environment (site:reddit.com queries returned no Reddit results via the search tool, and reddit.com could not be fetched directly). Findings below come from Hacker News, Adobe's own community forum, Blind (teamblind.com), and a Yahoo/AOL Finance news article, all of which surfaced verbatim, sourced, first-person accounts. Search budget (12 searches) and fetch budget were both used before this could be broadened further.

---

## Findings

### 1. Auto-renewal trap — SaaS/Creative Cloud subscription
- **Quote:** "They say they send out a notice stating information about renewal, must have forgot all of us because thats a total lie... next they start charging more, just draft from your bank account without the price increase or amount notice... If you try and get out of this deal with them they all tell you that they contacted you about the auto renewal and you have to pay to get out of it."
- **Source:** https://community.adobe.com/t5/account-payment-plan-discussions/beware-of-adobe-cloud-auto-renewals/m-p/9185623
- **Context:** User "Bob224732" on Adobe's own community forum describing being auto-renewed into a paid Creative Cloud contract and charged an increased amount without (in their view) adequate notice, then being told they'd have to pay a cancellation fee to exit. A second user replying to the same thread added: "I too have been trapped by this nonsense."

### 2. Lease amendment forcing a mandatory add-on fee tenants didn't want
- **Quote:** "It's being forced. Take it, or leave. And nobody wants to break their lease on purpose. I know I'm not going to. But I don't want to feel that I'm going to be forced to do something because they want more money coming in."
- **Source:** https://www.aol.com/finance/las-vegas-tenants-speak-over-110000566.html
- **Context:** Loretta Byers, a resident at Intrigue Apartments in Las Vegas, describing being required (via a lease-term change/bulk-billing clause) to pay for a mandatory internet package she didn't want or need, with no real option to opt out short of breaking her lease.

### 3. IP-ownership clause in an employment contract drove a cross-country move
- **Quote:** "I moved from New York to California a bit over 20 years ago in large part because I personally encountered this (the IP ownership bit)"
- **Source:** https://news.ycombinator.com/item?id=44338562
- **Context:** Commenter "btilly" on a Hacker News thread ("Tell HN: Beware confidentiality agreements that act as lifetime non competes") describing how an overly broad IP-ownership clause in a New York employment contract was significant enough hardship that they relocated to California specifically because of more employee-favorable law there.

### 4. Perpetual, open-ended non-disparagement clause noticed only after signing
- **Quote:** "I recently signed a new employment contract that requires me not to disparage my new employer... forever. Literally: There is no end date."
- **Source:** https://news.ycombinator.com/item?id=44338562
- **Context:** Commenter "throwaway2037" (self-identified as working in finance) describing discovering, after signing, that a non-disparagement clause in their new employment contract had no expiration — an open-ended restriction they hadn't clocked at signing time.

### 5. Non-compete clause resurfaced during an unemployment insurance dispute
- **Quote:** "I had a non-compete cause in a contract, I wound up in a dispute over unemployment insurance and the contract came up"
- **Source:** https://news.ycombinator.com/item?id=44338562
- **Context:** Commenter "PaulHoule" on the same Hacker News thread describing how a non-compete clause they had signed became a live legal issue later, in a completely different context (an unemployment insurance claim), rather than at the time of signing when its implications weren't apparent.

### 6. Non-compete clause enforcement threat from a former employer
- **Quote:** "I have got a warning notice from my previous employer for violation of non compete." ... "they stated that it came to their attention that I may be currently working on project with Competitor that may be directly related to the work I performed during my tenure"
- **Source:** https://www.teamblind.com/post/warning-notice-for-violation-of-non-compete-ev84dhue
- **Context:** A tech worker posting on Blind (a professional/workplace forum) after receiving a formal warning letter from a former employer alleging violation of a non-compete clause in their old employment contract, despite (per the poster) not having worked on any active project or used proprietary software during their "bench" time there — i.e., a clause whose real-world reach surprised them after the fact.

---

## What I could not find

Despite targeted searches, I did not find sourced, verbatim evidence in these specific categories within the search/fetch budget for this task:

- **Freelance/creative work-for-hire IP loss ("client owns everything I made")** — found plenty of general commentary and advice content (Hacker News, law-firm blogs) about this being a common problem, but no first-person "this happened to me and it hurt" quote with a verifiable source URL. Reddit's r/freelance, which almost certainly has this exact story, was not reachable through the available search/fetch tools in this environment.
- **Freelancer hit with a surprise liability/indemnification clause** (e.g., held financially responsible for a client's downstream loss) — no sourced first-person account found.
- **Arbitration clause blocking someone from suing** (e.g., ToS in a consumer product) — search returned only explainer/legal-blog content, no first-person harmed account with a source.
- **Small business owner who signed a personal guarantee and lost personal assets** — found only explainer articles (Bankrate, NerdWallet) on the risk, no sourced personal story.
- **Timeshare high-pressure contract complaints** — a promising verbatim complaint snippet appeared in search results attributed to a ConsumerAffairs page, but a direct fetch of that page returned HTTP 403, so I could not verify the exact quote/URL and dropped it rather than include an unverified claim.
- **Gym membership auto-renewal complaint (verbatim)** — background stats were found (e.g., BBB gym complaints ~42% relate to contract disputes) but no individually sourced first-person quote; the one candidate page (JustAnswer) returned HTTP 403 on fetch.
- **Twitter/X threads** — none surfaced in the searches run; this channel was not explored due to the search-budget cap being reached.
- **Direct Reddit threads (r/legaladvice, r/personalfinance, r/freelance, r/Entrepreneur, r/talesfromtechsupport)** — the web search tool's `site:reddit.com` queries consistently failed to surface Reddit results (returning unrelated law-firm/reference pages instead), and directly fetching reddit.com URLs was blocked in this environment ("Claude Code is unable to fetch from www.reddit.com"). This is a significant gap given Reddit is likely the richest source of this kind of testimony; a follow-up pass with a Reddit-capable tool (official API, Pushshift, or a browser-automation path) is recommended.
