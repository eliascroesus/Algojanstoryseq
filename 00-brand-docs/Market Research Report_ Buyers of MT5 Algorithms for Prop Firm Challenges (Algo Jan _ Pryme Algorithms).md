# Market Research Report: Buyers of MT5 Algorithms / EAs for Prop Firm Challenges (Creator: Algo Jan / Pryme Algorithms)

Algo Jan's real buyer is not a beginner hunting for a jackpot. The strongest evidence, his own application CRM plus EA review sites, points to an international trader with mostly 1–3+ years of experience who has already failed, either manually or with other bots. This buyer wants "consistency," "low dd" and "passive income," and will only pay for an algorithm whose track record he can check himself. The reason is that this market has been burned again and again by martingale bots, fake Myfxbook results and prop-firm collapses.

**Process note:** I couldn't run the final enrichment pass on this draft because the full text was over the tool's size limit. Every quote and figure below comes from the sources gathered during research. Items seen only in search snippets are labelled as such.

## TL;DR

- **Who buys:** Jan's own CRM shows applicants from about 50 countries (India, US, UK, Germany, Morocco, Pakistan, Ghana and others). Most have traded 1–3 or 3+ years. Their stated goals are "consistency," "minimal drawdown," "passive income," "quit 9-5 jobs"\[1\] and "pass prop firm challenges." Only 4 rows in the sheet are marked "Bought," and several of those buyers asked for a "verified track record on myfxbook" or a "trusted and tested EA."
- **What they believe:** The default stance is distrust. The same objections keep coming up: "if it worked, why sell it," "all prop EAs are martingale," "only works on demo," and "the myfxbook they showed me didn't match my account." The few positive reviews praise support and slow, steady results, not big returns.
- **What changed:** Since 2023 the market has been through the My Forex Funds shutdown (August 2023), MetaQuotes pulling MT4/MT5 licences from US-facing and grey-label prop firms (February 2024), the collapse of firms such as True Forex Funds and The Funded Trader, and tighter EA rules (HFT bans, limits on third-party and shared EAs). The key fact for copy: FTMO allows EAs but warns that a third-party EA can get you denied under its capital-allocation rule. Pass rates are low; FTMO's CEO has cited 8–10%.

---

## Summary: The 10 Most Important Findings

| # | Finding | Evidence type | Confidence |
|---|---|---|---|
| 1 | Jan's applicants are global, skewing to emerging markets plus UK/US/DACH.\[1\]\[2\] | Creator CRM (Google Drive sheet "Algo Access - By Application Only", 188 rows) | High (first-party) |
| 2 | Many applicants pick the lowest budget band ("Under $350/$400 - applications in this range are not reviewed") and are auto-marked "Not Qualified."\[2\] Price is the main filter.\[1\] | Creator CRM | High |
| 3 | Paying buyers talk about **proof and low stress**: "Stable EX5 access with verified track record on myfxbook," "reduce the amount of MENTAL capital," "a trusted and tested EA." | Creator CRM ("Bought" rows) | High |
| 4 | The top desire word is **consistency**, then **low drawdown** and **passive income**. | Creator CRM | High |
| 5 | Buyers have been burned by **martingale/grid EAs sold as "AI."** The usual story: profit for a few days, then a blown account.\[3\]\[4\] | Trustpilot (ForexKing EA, MechForex, PropEA, Propfirm EA) | High\[4\]\[5\] |
| 6 | **"Only works on demo / fake Myfxbook"** is a core objection.\[5\]\[6\] | Trustpilot, Forex Factory | High |
| 7 | **"If it worked, why sell it?"** is the reflex objection. Jan's line "99% of traders you follow online cannot prove they are profitable" already answers it with third-party verification.\[7\] | BabyPips, MQL5 forum, X (@algojan) | High |
| 8 | Prop firms **generally allow EAs but penalise shared/third-party EAs and HFT.**\[8\]\[9\]\[10\] | FTMO FAQ; algotradingspace.com | High |
| 9 | Odds of passing and getting paid are low. FTMO's CEO cited 8–10% passing the Challenge. Topstep reported that 33.3% of funded-level participants received a payout in 2025.\[11\] | Secondary write-ups | Medium |
| 10 | Trust in prop firms themselves was damaged in 2023–2024. Buyers now see the **platform and the firm** as risks, not just the strategy.\[12\]\[13\] | FX News Group, Finance Magnates, trackers | High |

**What this means for Uncapped:** Lead with verification (Myfxbook, a real FTMO payout), "not a jackpot" honesty, and low-drawdown consistency. Answer "why sell it," "martingale," "demo only" and "will my prop firm ban it" before the buyer asks. The licence lock (1 licence = 1 MT5 account number that can't be changed) can be presented as an anti-sharing feature.

---

## Research Coverage

| Channel | Status |
|---|---|
| Landing page (go.pryme-capital.com/algoaccess) | Accessed: full copy, offer contents, FTMO claims\[14\] |
| Whop (Algo World) | Home page only: 1,590 joined, "no posts yet."\[15\] **No Whop reviews collected** (reviews page wouldn't load) |
| X (@algojan) | Search snippet only (direct access blocked) |
| Instagram, YouTube, Facebook | **Not accessible.** No comments, views or transcripts collected |
| Creator CRM (Google Drive) | Accessed: 188 application rows plus a 460-row "Emails List" tab\[2\] |
| Reddit | **Not accessible.** Search returned no reddit.com thread URLs, and a dedicated sub-search confirmed this. **No Reddit quotes in this report** |
| MQL5 forum, BabyPips, EarnForex, Forex Factory (partial), Trustpilot EA vendors, Medium | Accessed or snippets |
| YouTube comments, Amazon reviews, Skool, Discord | **Not collected** |

---

## 1. Who They Are

### 1.1 Demographics

I found no published, reliable demographic data (age, gender, income, family) for retail EA or prop-firm buyers. The only hard data is Jan's CRM: https://docs.google.com/spreadsheets/d/1ctk11wYH4cLJoutOvefUSfxVprgeNZ-HkQd1g_8AIUY

| Data point | What the CRM shows | Confidence |
|---|---|---|
| Countries | India, US, UK, Germany, Morocco, Pakistan, Ghana, Nigeria, Algeria, Italy, Netherlands, Indonesia, Canada, UAE, Switzerland, Bangladesh, Malaysia, Singapore, Mexico, Türkiye, South Africa, Kenya, Korea, Brazil, Poland and others.\[1\] The email tab adds ISO codes incl. US, KE, GB, SA, DZ, PK, ZA, BD, ID, TR, IN, IT, MY, AU\[2\] | High |
| Age | Only "Are you at least 18" is confirmed; no age data\[2\] | High (that it's missing) |
| Trading experience | Mostly "1-3 years" and "3+ years," fewer "Less than 1 year"\[1\]\[2\] | High |
| Prior EA use | Mixed | High |
| Where they'll run it | "Both" (personal + prop) is the most common answer\[2\] | High |
| Capital to allocate | From "Less than $1,000" to "$10,000+"; "Less than $1,000" is common\[2\] | High |
| Budget for the algo | Bands changed over time (Under $350 / $350-$750 / $700-$1,500 / 1,500$+ / $400-$999 / Under $400). Many picked the lowest\[1\]\[2\] | High |
| Occupation | Few self-reports: software engineer and entrepreneur (Dubai); full-time worker (Germany); physics student (Germany); runs an investment fund (Switzerland) | Medium |
| Gender | Names are mostly male-presenting (guess). There is no gender field | Low (guess) |

| Quote (verbatim, CRM; anonymised) | Who |
|---|---|
| "Gain some capital passively to get rid of debt, to gain some freedom and to proceed my physics studys."\[1\] | Germany |
| "I can bring a lot of value to the table too. As a software engineer and entrepreneur. I'm hoping to use your strategy so to help save time and compound gains sooner."\[1\] | Dubai |
| "I love to see what a Bot can do… i working fulltime… so i had just a Little Timeline to trade by myself. I think it is the Future…"\[1\] | Germany |
| "Trader indépendant depuis 6 ans… je pourrais ensuite envisager une allocation d'une partie du portefeuille de mon fonds d'investissement à tes stratégies."\[1\] | Switzerland (Bought) |
| "Im low on funds with this one atm but If I learn how to do this I can pay back tripple"\[1\] | Latvia |
| "quit 9-5 jobs" | Norway\[2\] |
| "I'm lookin to increase my monthly income adding an asset"\[1\] | US |

**What it means for us:** There are two buyer clusters:
1. Cash-constrained emerging-market traders looking for a "glitch" or a way out.
2. Capitalised, often technical traders (engineers, fund allocators, people running multi-strategy "sleeves") who want diversification and proof.

The "Bought" rows lean towards cluster 2. Aim ads and setter qualification there (guess: age 30–55, employed, UK/US/DACH/Gulf).

### 1.2 Attitudes

| Quote | Source / link |
|---|---|
| "I see this as a glitch into system, and Im not greedy when I know how to use this glitch into matrix."\[1\] | CRM, Latvia |
| "I want to reduce the amount of MENTAL capital I'm investing by using a trusted and tested EA"\[1\] | CRM, US (Bought) |
| "99% of traders you follow online cannot prove they are profitable. Not because they are lying. Because nobody ever asked for proof."\[7\] | https://x.com/algojan |
| "do you think that people advertising EA's for sale have trading skills or marketing skills?"\[16\] | https://forums.babypips.com/t/do-you-advise-using-eas/1203856 |
| "These companies are interested in newbies with $10k accounts losing and buying again."\[17\] | https://www.forexfactory.com/thread/1270063-prop-firms-scam-alert |
| "Beating the market really isn't hard. People lose because they get impatient/unrealistic."\[18\] | https://www.mql5.com/en/forum/456749 |
| "However, there is always a risk that the Prop firm or Brooker will go bankrupt or your account will be violated, so my plan is to diversify"\[18\] | https://www.mql5.com/en/forum/456749 |
| "Sometimes I think if somebody finds such profitable strategy would he even feel comfortable to run it on an account and trust the broker. Or even trust the trading platform."\[18\] | https://www.mql5.com/en/forum/456749 |
| "I'm not looking for a get rich quick bot. But a bot that trades with tight risk management and overtime makes profits."\[1\] | CRM, Nigeria |

**What it means for us:** They see the 9–5 and manual trading as traps, but they distrust the people selling a way out even more. They value proof over personality. Copy should be anti-hype and numbers-first, and should talk about stress and "mental capital," not just money.

### 1.3 Hopes and dreams

| Quote | Source / link |
|---|---|
| "I want to have multiple passed challenges that just make me money without having to do much."\[1\] | CRM, US (Bought) |
| "I want a stability. A system that is consistent enough to help me turn trading into a full-time income."\[1\] | CRM, Canada |
| "Pass a few prop firms and let it work on it's own"\[1\] | CRM, Switzerland |
| "consistant passive income"\[1\] | CRM, US |
| "Financial freedom"\[1\] | CRM, Bulgaria |
| "To any passive income over time by compounding"\[1\] | CRM, Cabo Verde |
| "Balance with personal life and trading"\[1\] | CRM, Portugal |
| "I want to purely run this on propfirms account to pass them and get funded"\[1\] | CRM, Pakistan |
| "If you follow his game plan, you will be able to escape the rat race and live life on your terms. Isn't that what we all want?" | https://de.trustpilot.com/review/forexkingea.com \[4\] |
| "But with $1M in prop firm funding? It'll generate a 6-figure income, almost completely passive."\[18\] | https://www.mql5.com/en/forum/456749 |

**What it means for us:** The dream is hands-off income from other people's capital, plus a balanced life. Sell "funded without screen time," and pair it with Jan's "not a jackpot" stance so it reads as realistic.\[14\]

### 1.4 Victories and failures

| Quote | Type | Link |
|---|---|---|
| "ho appena passato una sfida FTMO da 200000$" | Win | https://de.trustpilot.com/review/forexkingea.com |
| "The first payout was received and everything was good." | Win | https://de.trustpilot.com/review/forexkingea.com |
| "I have finally passed both the Challenge and Verification for FTMO am finally a funded trader." | Win | https://www.forexfactory.com/thread/999648-my-journey-to-forex-prop-trading \[19\] |
| "like you took 6 months to pass a FTMO 2-step before blowing the account from oversizing and not being sensible with my trading."\[1\] | Failure | CRM, UK |
| "I wasn't able to clear a single challenge out of 7." | Failure | https://de.trustpilot.com/review/forexkingea.com |
| "I've already blown 7 Prop firm accounts."\[20\] | Failure | https://pl.trustpilot.com/review/vectoralgorithmics.com?page=4 |
| "I blew up the first account in only 3 days."\[18\] | Failure | https://www.mql5.com/en/forum/456749 |
| "after passing demo phase in 10 days the real account blew in minutes."\[21\] | Failure | https://mngz636.medium.com/4-prop-firm-accounts-blown-5ab3b0fd05e0 |
| "Forexking GoldKing EA lost my USD 16,000." | Failure | https://de.trustpilot.com/review/forexkingea.com |
| "I have failed couple of FTMO challenges and paid my tuition fees." | Failure | https://de.trustpilot.com/review/forexkingea.com |
| "Finally starting getting payouts on Live and Propfirm accounts… but I lack in consistency and discipline, that's why I want to switch to EA"\[1\] | Mixed | CRM, Germany |

**What it means for us:** The emotional high point is passing both phases and getting the first payout. People count their wounds in accounts and dollars. Show Phase 1 → Verification → Payout, as Jan's page already does.\[14\]

### 1.5 Outside forces they blame

| Quote | Blamed on | Link |
|---|---|---|
| "its a rigged game . the charts just freeze then unfreeze when removing them. ftmo and funddnext."\[22\] | Prop firms | https://www.earnforex.com/forum/threads/ea-useless-when-trading-with-prop-firms.49454/ |
| "Some prop firms using server plugins to prevent EA from profiting"\[18\] | Prop firms | https://www.mql5.com/en/forum/456749 |
| "I know of many people who don't get paid their profits for no reason, the rule is invented by the prop firms themselves."\[17\] | Prop firms | https://www.forexfactory.com/thread/1270063-prop-firms-scam-alert |
| "They tell you that you are a copycat of other people (this case happened to me)"\[17\] | Copy rules | same thread |
| "FundedNext terminated both my challenge accounts for grid trading." (snippet only)\[17\] | FundedNext | same thread |
| "Their email said that found some "inconsistencies using my EA" and they need to investigate my trades." (snippet only)\[23\] | Payout review | https://www.forexfactory.com/thread/1212177-help-with-prop-firm |
| "We originally ran a third-party EA on an FTMO-funded account, and FTMO eventually denied the payouts."\[24\] | Prop firm rules | https://algotradingspace.com/discover-the-best-forex-expert-advisor-for-your-ftmo-funded-account |
| "If it wouldn't be for the horrific slippage I'd probably be in Gold already"\[7\] | Slippage | https://x.com/algojan |
| "I double checked the myfxbook too late, they have a scam broker"\[6\] | Broker | https://de.trustpilot.com/review/robotforexpro.com |
| "Due to a non-sense reason, MetaQuotes has terminated our licenses"\[12\] | MetaQuotes | https://fxnewsgroup.com/forex-news/retail-forex/exclusive-prop-trading-firm-true-forex-funds-shut-down-by-metaquotes-move/ |
| "Owed 13K in payouts and was recently banned with zero explanation as to why."\[25\] | Prop firm | https://www.trustpilot.com/users/65ca3a5eabfd5c0012a2f1d3 |

**What it means for us:** Buyers blame prop-firm rules, payout denials, the platform and broker execution. Answer that with "built to fit prop-firm rules": set files plus a compatibility guide.

### 1.6 Prejudices

| Quote | Target | Link |
|---|---|---|
| "MQL Market offers a wide range of scammy products created by third-party developers, many of which come at exorbitant prices."\[16\] | MQL5 vendors | https://forums.babypips.com/t/do-you-advise-using-eas/1203856 |
| "The first goal is marketing for EA sellers."\[16\] | EA sellers | same |
| "This guys buy a $30 EA from MQL5 marketplace and resell for ridiculous fees($500) with the promise of customer service." | Resellers | https://ca.trustpilot.com/review/propfirm-ea.com \[5\] |
| "Anyone saying anything else is trying to sell you something other than advise."\[18\] | Sellers | https://www.mql5.com/en/forum/456749 |
| "It's all marketing BS, thier channel shows members account making profit even though the bot isn't on."\[26\] | Bot channels | https://de.trustpilot.com/review/simplifiedfxea.com |
| "Most tools promoted by crypto 'bros' are just 1980s RSI indicators wrapped in a sleek 2024 UI."\[27\] | "AI" promoters | https://medium.com/@fabulous_snow_manatee_698/i-tested-23-ai-bots-and-lost-14-000-the-brutal-reality-of-reddit-s-trading-hype-70dc6a780cb4 |
| "if this guy were such a millionare flaunting stupid,hilarious phots on Instagram tht he keeps sending people, why wld he even bother to have the headache of dealing with disatisfied cstomrs." | Lifestyle flexers | https://de.trustpilot.com/review/forexkingea.com |
| "Dont believe what they post on telegram its all a mirage." | Telegram sellers | https://ca.trustpilot.com/review/propfirm-ea.com |
| "I lost $200 on this one and 100 on another promoted by the same scam youtube channel"\[6\] | YouTube promoters | https://de.trustpilot.com/review/robotforexpro.com |

**What it means for us:** Avoid Lambo/lifestyle creative and "AI" labels. Show the real account and the red months. I found no evidence of contempt for "9–5 normies"; the 9–5 is something to escape, not someone to mock.

### 1.7 Core beliefs

"Trading can pay, but almost everyone selling it is lying. I only trust a third-party-verified record that has also passed a real prop firm. If a bot makes me consistent without my emotions getting in the way, I'll pay. If it smells like martingale or demo-only, I'm out." (My synthesis of the sources above.)

---

## 2. Existing Solutions

### 2.1–2.4 Use, experience, likes, hates

| Solution | Verbatim | Like/Hate | Link |
|---|---|---|---|
| Manual (ICT/SMC/MSNR) | "Other than this i trade ict smc and msnr strategy and trying to create one bot myself too"\[1\] | Context | CRM |
| Manual | "manual trading is hard and I've been following the EA results for about a year before I purchased my subscription plan" | Hate | https://ca.trustpilot.com/review/propfirm-ea.com |
| Strategy hopping | "Im this dead end loop, from strat to strat."\[1\] | Hate | CRM |
| DIY EA | "I've been trying alot for an alog to build it myself and i got close but not succeeded yet"\[1\] | Frustration | CRM |
| Multi-EA | "i do have a diversified book with more than 30 sleeves (different strategies on different symbols)"\[1\] | Advanced | CRM |
| ForexKing EA | "Slow and steady progress with ForexkingEA on a prop challenge. Minimal intervention needed" | Like | https://de.trustpilot.com/review/forexkingea.com |
| ForexKing EA | "This EA will do well for about a week and then hit Daily drawdown effortlessly until max drawdown is hit." | Hate | same\[4\] |
| Propfirm EA | "With their expert advisors, my metatrader terminals turned into money making machines."\[5\] | Like | https://ca.trustpilot.com/review/propfirm-ea.com |
| Passing service | "they told me they would approve my 100k account in approximately 40 days. However, seven months have passed and the account is negative -9873.00." | Hate | same\[5\] |
| Vendor support | "Most providers vanish after selling a generic product, leaving users stranded with confusing setup videos and zero support." | Hate | same\[5\] |
| Vector Algorithmics | "What they are great at is the algo that allows you to pass prop firm eval challenges in one trade"\[20\] | Like | https://pl.trustpilot.com/review/vectoralgorithmics.com?page=4 |
| Mentorship | "If you want to make money trading just take the money and get a mentor and learn to trade." | Mentor over bot | https://de.trustpilot.com/review/forexkingea.com |
| Free YouTube, Discord, Skool, signals, copy trading, books | No buyer quotes collected | — | — |

**What it means for us:** Buyers like support, steady results and "minimal intervention." They hate vendors who vanish and accounts that blow up after a good week. Make support visible in the offer.

### 2.5 Horror stories

| Quote | Link |
|---|---|
| "I bought EA and it blew my entire Real account after 3 days of trading.I asked support for refund,they aren't responding.Scammers all over the internet,I wonder what's true."\[28\]\[29\] | https://ch.trustpilot.com/review/forexa.shop |
| "The robot did not make any profit in 30 days and I lost 3 funded accounts of $ 10,000."\[28\] | https://es.trustpilot.com/review/forexa.shop |
| "I bought 3 EAs and 1 of them burned my account so quickly that I received a support message from my broker that their servers had been damaged, another EA didn't even have a license."\[29\] | https://ch.trustpilot.com/review/forexa.shop |
| "Both accounts blew almost instantly. Zero returns. 100% losses."\[5\] | https://ca.trustpilot.com/review/propfirm-ea.com |
| "The "results" they sent me — supposedly verified through MyFXBook — were completely different from what my account experienced during the exact same period." | same\[5\] |
| "I placed the EA on my charts and suffered 51 losses in a row"\[30\] | https://de.trustpilot.com/review/yoforex.org |
| "The stress is just constantly there because once it goes into drawdown you can't help but think there's no stoploss this could continue sending me into drawdown. Lo and behold, it did." | https://de.trustpilot.com/review/forexkingea.com |
| "It is just another failing martingale bot. After months I can tell that it blown all my accounts and the ones of my fellow traders, live 200k props." | same\[4\] |
| "The bot crashed the website is dead and client money is missing."\[31\]\[32\] | https://ch.trustpilot.com/review/responsibleforextrading.com |
| "How is the EA? Old Myfxbook has been deleted. The new one starts yesterday..." | https://www.forexfactory.com/thread/1302929-free-profitable-ea-on-mt4 \[33\] |
| "ive beaten 7 challeneges and was one week away from MFF payment of 1855."\[22\] | https://www.earnforex.com/forum/threads/ea-useless-when-trading-with-prop-firms.49454/ |

**License/account-lock complaints:** I found no direct ones. The closest are "another EA didn't even have a license" and "You have to give to them your MT ID and MT Password, keep that in mind." (https://ca.trustpilot.com/review/propfirm-ea.com). \[5\]

**What it means for us:** The pattern is quick profit, then a blow-up, then a vendor who disappears or blames the buyer, sometimes with a Myfxbook that changes. Jan's "I can't edit it and I can't remove the red months" should be a headline.\[14\]

### 2.6 Do they believe existing solutions work?

| Quote | Link |
|---|---|
| "Has anyone actually used an EA for passing their prop firm challenge and maintaining their prop firm accounts over a long period of time? If so, do you have proof?"\[18\] | https://www.mql5.com/en/forum/456749 |
| "There are EA that can pass challanges, but those I tested never have 100% pass rate or anything close to 100%."\[18\] | same |
| "The only EA which does the job all the time are the HFT EA's but then you have to abide by a lot of Hoops to fight the firm in actually getting the payout."\[18\] | same |
| "An EA should be an extension of your proven, profitable strategy, not some random one that someone else is selling."\[16\] | https://forums.babypips.com/t/do-you-advise-using-eas/1203856 |
| "scam company sell ea's not working on live acc - only demo looks good."\[6\] | https://de.trustpilot.com/review/robotforexpro.com |
| "I got to know forexkingea and David after 2 very bad experiences with other EA providers." | https://de.trustpilot.com/review/forexkingea.com |
| "Just trying to get in EA trading. Not many expectations. Currenlty experimenting things"\[1\] | CRM, Pakistan |

**What it means for us:** Scepticism is very high but not total. People buy again after bad vendors when the proof and support are better. The objection to beat is "prove it on a live account and a real prop firm."

---

## 3. Curiosity

### 3.1 Unusual approaches

| Approach | Quote | Link |
|---|---|---|
| Hedge EA | "the challenge account ultimately failed, breaching the challenge rules and incurring a loss of $15,244."\[34\] | https://algotradingspace.com/prop-ea-review |
| HFT bots | "No you cannot as prop firms do not allow the use of HFT EA's on funded accounts"\[35\] | https://forexblue.gumroad.com/l/fzfog \[35\] |
| Passing services | "I already passed 42 Prop Firm challenges for my clients." | https://www.forexfactory.com/thread/1193052-pass-prop-firm-challenges \[36\] |
| LLM strategy | "I told Claude: create a trading strategy for PineScript that will make me 1'000'000$ - he created smth for ETH that was rubbish."\[7\] | https://x.com/algojan |
| Ultra-slow EA | "Here's the catch: it will take 6-9 months to pass."\[18\] | https://www.mql5.com/en/forum/456749 |

### 3.2 Famous stories

| Story | What happened | Link |
|---|---|---|
| My Forex Funds | Shut down in August 2023. In May 2025 a US court dismissed the CFTC case with prejudice and sanctioned the CFTC\[37\]\[38\] | https://www.financemagnates.com/forex/my-forex-funds-parent-defeats-cftc-in-court-as-judge-imposes-sanctions/ |
| True Forex Funds | MetaQuotes terminated its licences in February 2024 and the firm shut down\[12\] | https://fxnewsgroup.com/forex-news/retail-forex/exclusive-prop-trading-firm-true-forex-funds-shut-down-by-metaquotes-move/ |
| The Funded Trader | Paused operations on March 28, 2024; trackers report $2M+ in denied payouts\[13\]\[39\] | https://propnavi.io/en/blog/prop-firm-shutdowns-history/ |
| ForexKing EA | Sold with an "AI technology" claim; reviewers describe martingale behaviour\[4\] | https://de.trustpilot.com/review/forexkingea.com |
| Renaissance, Turtle Traders, Myfxbook bot collapses | **Not researched; no sources gathered** | — |

### 3.3 Debates

| Debate | For | Against | Links |
|---|---|---|---|
| Why sell it? | "f you had a good EA that worked reliably, would you sell a few copies for $300 each…"\[16\] | "none of those individuals are interested in proving their worth to you"\[18\] | BabyPips; MQL5 |
| All EAs are martingale | "Martingale and Grid strategy is their bot."\[3\] | Vendor: "Non-Martingale Strategy"\[40\] | https://dk.trustpilot.com/review/propea.net |
| Prop firms are rigged | "100 percent rigged game and we need the regulators in ASAP"\[22\] | "You can easily trade with an EA with such low drawdown limits."\[18\] | EarnForex; MQL5 |
| AI is marketing | "1980s RSI indicators wrapped in a sleek 2024 UI"\[27\] | Vendor: "leverages advanced AI technology" | Medium; ForexKing\[4\] |

**What it means for us:** "Why sell it" is the debate to own in the VSL. Ask Jan for his real answer during onboarding; don't invent one.

---

## 4. What Changed

**4.1 Was it easier before?** The evidence is thin. I collected no direct "it used to be easier" quotes. Indirect signals: "a lot of ea are being sabotaged on prop challenges" (EarnForex, 2023),\[22\] and "I keep getting mixed information on whether EA's are allowed on funded accounts." (https://community.algotradingspace.com/forums/topic/prop-firm-robots-reward-program/, Nov 2025).\[41\]

**4.2 Forces**

| Force | Facts | Link |
|---|---|---|
| MFF shutdown | August 2023; case dismissed May 2025\[38\]\[42\] | Finance Magnates (above) |
| MetaQuotes licence pulls | True Forex Funds' licences terminated in February 2024; the firm was on the CFTC RED List\[43\] | https://www.forexfactory.com/news/1265600-prop-trading-firm-true-forex-funds-shut-down |
| US MT5 access | Most US-facing firms lost MetaTrader\[44\] | https://tradethepool.com/fundamental/which-prop-firms-offer-mt5/ |
| Firm collapses | Trackers estimate 80–100 firms closed in 2024\[13\] | https://propnavi.io/en/blog/prop-firm-shutdowns-history/ |
| EA rules | FTMO's third-party EA warning; reports that some firms ban specific commercial EAs\[8\]\[45\] | https://ftmo.oanda.com/faq/which-simulated-instruments-can-i-trade-and-what-strategies-am-i-allowed-to-use/ ; https://www.jptradingcapital.com/blog/en/prop-firm-allow-ea \[45\] |
| AI hype and clones | Gumroad sellers offer $12–$19.99 "100% success rate" prop EAs\[46\]\[47\]\[48\] | https://thetradelovers.gumroad.com/l/GrailFundingCrusherEA \[49\]\[50\] |

**What it means for us:** Buyers now ask three things. Will my firm allow it? Will my firm still exist? Will the vendor still be here?

---

## 5. Language

### 5.1 Top quotes (tagged)

The 40 strongest quotes appear verbatim, with links, in sections 1–3. Here are the most powerful ones, tagged:

| Quote | Tag |
|---|---|
| "I want to reduce the amount of MENTAL capital I'm investing by using a trusted and tested EA" | Desire |
| "I want to have multiple passed challenges that just make me money without having to do much." | Desire |
| "Stable EX5 access with verified track record on myfxbook."\[1\] | Desire |
| "Looking for profitable and low dd - a real edge."\[1\] | Desire |
| "Minimal drawdown! :)"\[1\] | Desire |
| "like you said in many of your videos the strategy is not the problem the problem is me i want to remove myself"\[1\] | Belief |
| "Im this dead end loop, from strat to strat." | Pain |
| "I wasn't able to clear a single challenge out of 7." | Pain |
| "Scammers all over the internet,I wonder what's true."\[29\] | Fear |
| "It is just another failing martingale bot." | Objection |
| "only demo looks good."\[6\] | Objection |
| "Old Myfxbook has been deleted. The new one starts yesterday..." | Objection |
| "They tell you that you are a copycat of other people" | Fear\[17\] |
| "'Set and forget' is a myth for 99% of Reddit bots."\[27\] | Belief |
| "99% of traders you follow online cannot prove they are profitable."\[7\] | Belief |

### 5.2 Vocabulary

EA/bot/algo; EX5/EX4; set files; VPS; DD/dd/daily DD/max DD; Phase 1/Challenge/Verification/2-step; funded; payout/profit split; blown/burned account; martingale/grid/averaging; HFT/tick scalping; copy trading/copier/copycat; equity protector; news filter; Myfxbook/verified/track record; passing service; sleeves/uncorrelation/edge/expectancy; ICT/SMC/MSNR; 1:500 broker; slippage; set and forget.

### 5.3 Titles that grab attention

View counts weren't available. Titles found:
- "Is there a reliable, proven, prop firm EA?" (MQL5, 4 pages)\[18\]
- "I Tested 23 'AI' Bots and Lost $14,000"\[27\]
- "4 Prop Firm Accounts Blown"\[21\]
- "How to Pass FTMO Challenge in 2026… (92% Fail)"\[51\]
- "Prop firms scam alert"
- Jan's pinned post: "I am going to say something the trading industry does not want you to read."\[7\]

Common patterns are a number plus a loss, proof words, and contrarian hooks.

---

## 6. Accuracy Check

| Claim | Verdict | Evidence / link |
|---|---|---|
| Most retail traders lose money | **TRUE** (CFDs) | ESMA: "Between 74-89% of retail investor accounts lose money when trading CFDs."\[52\] https://www.esma.europa.eu/sites/default/files/library/esma35-43-1912_cfd_renewal_3_-_notice_en.pdf |
| ~10% pass FTMO | **TRUE** (CEO statement, reported secondhand) | 8–10% https://www.tradeloggy.com/blog/how-many-prop-firm-traders-actually-succeed |
| ~7% of buyers ever get paid | **UNVERIFIED** | FPFX data via a secondary source\[53\] https://alexfirdaus.com/prop-firm-pass-rate/ |
| 1 in 3 funded traders get paid | **TRUE for Topstep 2025** (secondhand) | 33.3% (tradeloggy, above) |
| Prop firms ban EAs | **FALSE** as a blanket claim\[8\] | https://ftmo.com/en/faq/which-instruments-can-i-trade-and-what-strategies-am-i-allowed-to-use/ \[10\] |
| A third-party EA can get you denied | **TRUE** (FTMO) | "By using a third-party EA, you potentially run a risk of being denied the FTMO Account if you exceed the maximum capital allocation rule."\[8\]\[10\] (same) |
| FTMO $400K per-strategy cap | **UNVERIFIED** | https://www.eafunded.com/firms/ftmo \[54\] |
| HFT passes challenges but isn't allowed on funded accounts | **TRUE** (vendor's own admission) | https://forexblue.gumroad.com/l/fzfog |
| FundedNext bans specific EAs | **UNVERIFIED** | https://www.jptradingcapital.com/blog/en/prop-firm-allow-ea |
| Server plugins sabotage EAs | **UNVERIFIED** | Disputed on the MQL5 forum\[18\] |
| All prop EAs are martingale | **FALSE** as universal | Many reviewed products are, but not all\[49\]\[55\]\[56\]\[57\] |
| "100% pass rate" EAs | **UNVERIFIED** | Vendor claims only\[35\]\[47\] |
| "AI" bots are actually AI | **UNVERIFIED** | Users describe martingale behaviour\[4\] |
| MetaQuotes pulled licences in 2024 | **TRUE** | FX News Group |
| 80–100 firms closed in 2024 | **UNVERIFIED** (estimate) | propnavi |
| TFT denied $2M+ in payouts | **UNVERIFIED** | https://myforexfirms.com/blogs/prop-firm-scams-to-avoid \[58\] |
| MFF was proven a fraud | **FALSE** | Case dismissed for CFTC misconduct; https://barlaw.co.il/my-forex-funds-lawsuit-warning-to-the-proprietary-trading-sector/ \[42\] |
| Jan's FTMO pass, verification and payout | **UNVERIFIED** by us | Screenshots on https://go.pryme-capital.com/algoaccess \[14\] |
| Jan's Myfxbook record since May 2025 | **UNVERIFIED** by us | Creator's claim on X\[7\] |
| FTMO $100k costs €540, refunded with first payout | **TRUE** (secondary, consistent) | https://tradewize.io/blog/prop-firm-challenges \[59\] |

---

## Recommendations for Onboarding

| Area | Recommendation |
|---|---|
| Positioning | "The only algo I'll sell is the one on my own Myfxbook and FTMO account. Red months included."\[14\] |
| Objections | Get Jan's real answer to "why sell it." State the strategy facts on martingale/grid. Show the live account vs. demo, and the FTMO pass plus payout. |
| License lock | Present it as a limit on sharing. Check with Jan before linking it to prop-firm shared-strategy rules. |
| Avatar | 1–3+ year traders who use the words consistency, low dd, verified and diversify, with $1k–$10k+ to allocate. |
| Gaps | Pull IG/YouTube comments, Whop reviews, Discord questions, setter call notes and Reddit URLs. |

## Sources

Jan's CRM (Google Drive); go.pryme-capital.com/algoaccess; whop.com/algo-world-db94; x.com/algojan; mql5.com/en/forum/456749; forums.babypips.com (1203856, 1274029); earnforex.com thread 49454; forexfactory.com threads 1270063, 1212177, 999648, 1302929, 1193052, 1246260, news 1265600; Trustpilot: forexkingea.com, propfirm-ea.com, forexa.shop, robotforexpro.com, yoforex.org, simplifiedfxea.com, vectoralgorithmics.com, responsibleforextrading.com, propea.net, user 65ca3a5e…; Medium (two articles); algotradingspace.com (two pages + community); ftmo.com FAQ; ftmo.oanda.com FAQ; ESMA notice; financemagnates.com; barlaw.co.il; fxnewsgroup.com; propnavi.io; thepropfirmguide.com; tradethepool.com; myforexfirms.com; tradeloggy.com; alexfirdaus.com; tradewize.io; eafunded.com; jptradingcapital.com; Gumroad listings (thetradelovers, forexblue).

## Sources

1. mcp\_\_Google\_Drive\_\_download\_file\_content
2. mcp\_\_Google\_Drive\_\_read\_file\_content
3. [dk.trustpilot.com](https://dk.trustpilot.com/review/propea.net)
4. [de.trustpilot.com](https://de.trustpilot.com/review/forexkingea.com)
5. [Propfirm Ea LTD is rated "Average" with 3.3 / 5 on Trustpilot](https://ca.trustpilot.com/review/propfirm-ea.com)
6. [Robotforexpro Bewertungen 21](https://de.trustpilot.com/review/robotforexpro.com)
7. [Jan - Algo Trader (@algojan) on X](https://x.com/algojan)
8. [which simulated instruments can i trade and what strategies am i allowed to use](https://ftmo.oanda.com/faq/which-simulated-instruments-can-i-trade-and-what-strategies-am-i-allowed-to-use/)
9. [FTMO EA Rules Explained 2026 — EAFunded](https://www.eafunded.com/blog/ftmo-ea-rules)
10. [Which instruments can I trade, and what strategies am I allowed to use?](https://ftmo.com/en/faq/which-instruments-can-i-trade-and-what-strategies-am-i-allowed-to-use/)
11. [How Many Prop Firm Traders Actually Succeed? What Published Firm Data Shows](https://www.tradeloggy.com/blog/how-many-prop-firm-traders-actually-succeed)
12. [Exclusive: Prop trading firm True Forex Funds shut down by MetaQuotes move - FX News Group](https://fxnewsgroup.com/forex-news/retail-forex/exclusive-prop-trading-firm-true-forex-funds-shut-down-by-metaquotes-move/)
13. [A History of Prop Firm Shutdowns — What the 2024–2025 Collapse Teaches Traders](https://propnavi.io/en/blog/prop-firm-shutdowns-history/)
14. <https://go.pryme-capital.com/algoaccess>
15. [Algo World](https://whop.com/algo-world-db94/)
16. <https://forums.babypips.com/t/do-you-advise-using-eas/1203856>
17. [Prop firms scam alert](https://www.forexfactory.com/thread/1270063-prop-firms-scam-alert)
18. [Is there a reliable, proven, prop firm EA?](https://www.mql5.com/en/forum/456749)
19. [My Journey to Forex prop trading](https://www.forexfactory.com/thread/999648-my-journey-to-forex-prop-trading)
20. [Vector Algorithmics Recenzje 119](https://pl.trustpilot.com/review/vectoralgorithmics.com?page=4)
21. [4 Prop Firm Accounts Blown. 15k funded next account (November 2023)](https://mngz636.medium.com/4-prop-firm-accounts-blown-5ab3b0fd05e0)
22. [EA useless when trading with prop firms](https://www.earnforex.com/forum/threads/ea-useless-when-trading-with-prop-firms.49454/)
23. [Help with Prop Firm](https://www.forexfactory.com/thread/1212177-help-with-prop-firm)
24. [Best Expert Advisor for FTMO in 2026: Why I Build My Own (And You Should Too)](https://algotradingspace.com/discover-the-best-forex-expert-advisor-for-your-ftmo-funded-account)
25. [www.trustpilot.com](https://www.trustpilot.com/users/65ca3a5eabfd5c0012a2f1d3)
26. [Simplifiedfxea Bewertungen 28](https://de.trustpilot.com/review/simplifiedfxea.com)
27. [I Tested 23 'AI' Bots and Lost \$14,000 — The Brutal Reality of Reddit's Trading Hype](https://medium.com/@fabulous_snow_manatee_698/i-tested-23-ai-bots-and-lost-14-000-the-brutal-reality-of-reddit-s-trading-hype-70dc6a780cb4)
28. [es.trustpilot.com](https://es.trustpilot.com/review/forexa.shop)
29. [ch.trustpilot.com](https://ch.trustpilot.com/review/forexa.shop)
30. [Yoforex Bewertungen 17](https://de.trustpilot.com/review/yoforex.org)
31. [Responsible Forex Trading Reviews 57](https://ca.trustpilot.com/review/responsibleforextrading.com)
32. [Responsible Forex Trading Bewertungen 59](https://ch.trustpilot.com/review/responsibleforextrading.com)
33. [(FREE) Profitable EA on MT4](https://www.forexfactory.com/thread/1302929-free-profitable-ea-on-mt4)
34. [Testing Prop EA: Is It Worth Using for Prop Firm Challenges? - Algo Trading Space](https://algotradingspace.com/prop-ea-review)
35. [forexblue.gumroad.com](https://forexblue.gumroad.com/l/fzfog)
36. [Pass Prop Firm Challenges](https://www.forexfactory.com/thread/1193052-pass-prop-firm-challenges)
37. [In a Blow to the CFTC, US Court Throws Out My Forex Funds Lawsuit](https://www.financemagnates.com/forex/my-forex-funds-parent-defeats-cftc-in-court-as-judge-imposes-sanctions/)
38. [My Forex Funds Review & Lawsuit Dossier (2026): Nov 23 Relaunch, CFTC Dismissal & Is It Legit? · PropSikayet](https://propsikayet.com/en/my-forex-funds)
39. [Prop Firm Shutdowns: 80+ Firms That Closed (2020-2026)](https://thepropfirmguide.com/prop-firms-that-shut-down/)
40. [fxexpertise.gumroad.com](https://fxexpertise.gumroad.com/l/HFTBotMT4)
41. [Prop Firm Robots Reward Program](https://community.algotradingspace.com/forums/topic/prop-firm-robots-reward-program/)
42. [My Forex Funds Lawsuit: Warning to the Proprietary Trading Sector - Barnea](https://barlaw.co.il/my-forex-funds-lawsuit-warning-to-the-proprietary-trading-sector/)
43. [Prop trading firm True Forex Funds shut down by MetaQuotes move](https://www.forexfactory.com/news/1265600-prop-trading-firm-true-forex-funds-shut-down)
44. [Which Prop Firms Offer MT5? Full 2026 List and Answer](https://tradethepool.com/fundamental/which-prop-firms-offer-mt5/)
45. [Which Prop Firms Allow EAs? Product Rules and Permission](https://www.jptradingcapital.com/blog/en/prop-firm-allow-ea)
46. [atomfxstore.gumroad.com](https://atomfxstore.gumroad.com/l/DmfAIEAForFTMOAndPropFirmsMT4)
47. [thetradelovers.gumroad.com](https://thetradelovers.gumroad.com/l/GrailFundingCrusherEA)
48. [atomfxstore.gumroad.com](https://atomfxstore.gumroad.com/l/FTMOEAPassingPackMT4)
49. [thetradelovers.gumroad.com](https://thetradelovers.gumroad.com/l/ForexHackedEAMT4)
50. [thetradelovers.gumroad.com](https://thetradelovers.gumroad.com/l/ScalpingGridEAv2MT4)
51. [How to Pass FTMO Challenge in 2026: The Only Guide You Need (92% Fail)](https://tradelikemaster.com/blog/how-to-pass-ftmo-challenge-2026-complete-guide)
52. [Notice of ESMA's Product Intervention Renewal Decision in ...](https://www.esma.europa.eu/sites/default/files/library/esma35-43-1912_cfd_renewal_3_-_notice_en.pdf)
53. [Prop Firm Pass Rate 2026: What Percentage Get Paid?](https://alexfirdaus.com/prop-firm-pass-rate/)
54. [FTMO EA Rules & Policy 2026: Allowed, With Limits](https://www.eafunded.com/firms/ftmo)
55. [Best Forex EAs for Prop Firm Challenges 2026 — FTMO, FundedNext](https://www.fxroboteasy.com/prop-firm/best-ea-for-prop-firms)
56. [thetradelovers.gumroad.com](https://thetradelovers.gumroad.com/l/ForexWarriorProEAMT4)
57. [TSR FX MASTER EA](https://forexobroker.gumroad.com/l/rwgkl)
58. [Prop Firm Scams to Avoid in 2026: Real Cases & Red Flags](https://myforexfirms.com/blogs/prop-firm-scams-to-avoid)
59. [Prop Firm Challenges (2026): The Real Cost and Pass Rate](https://tradewize.io/blog/prop-firm-challenges)
