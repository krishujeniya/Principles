# Google UX & Psychology Principles: Full 283-Entry Mapping (2026)

**Research and comparison date:** 15 November 2026
**Reference:** user-provided `Principles_List.md` — original 283 numbered entries preserved exactly.
**Scope:** Google Search, YouTube (including Shorts), Gmail, Google Maps, Chrome, Gemini, Android/Material Design, Google Play, and Google Account privacy controls; some illustrative Docs/Drive features are included.

> **Definition of “used”:** `F` means an observable or documented product feature maps to a principle—not proof that Google consciously implemented that theory or that the mechanism produced the intended effect. `I` is a plausible inference, not confirmed fact. `G` is a general lens only. `N` is unestablished in this audit, not a claim of absolute absence.
> **Crucial:** Personalization, autoplay, habit, problematic use and clinical addiction are different. Do not claim Google intentionally creates addiction or engineers dopamine effects from an interface observation. Product versions, regions, accounts and ages vary.

## Results and confidence

| Classification | Count | Interpretation |
|---|---:|---|
| **F — Feature mapping** | 84 | Observed/documented UX feature connects to principle; behavioral result not automatically proven |
| **I — Interpretation** | 55 | Plausible psychological explanation of feature; intention and causality unverified |
| **G — General/qualified** | 81 | Potentially useful design heuristic or audit lens, not Google-specific adoption evidence |
| **N — Not established** | 63 | No sufficient evidence to attribute the mechanism to a specific Google product |
| **Total** | **283** | Every original entry retained once |

**These counts are classification judgments made for this mapping; they are not official Google research results or experimental findings.**

## Fast answer: most visible Google product patterns

| Product | Strongest directly observable or documented patterns |
|---|---|
| **Google Search / Chrome** | #6 progressive disclosure; #7 recognition; #82 information scent; #160 contextual personalization (for some services); #273 Search/results; Autocomplete predicts queries, rankers prioritize relevance |
| **YouTube** | #85 novelty; #144 social proof (displayed signals); #160 personalization; #264 satisfaction signals; #279 Shorts scroll; #280 autoplay; #281 recommender controls |
| **Gmail** | #2 chunking; #27 defaults; #59 Undo Send recovery; #160 personalized writing suggestions; #272 nudges; #275 settings |
| **Maps** | #65 explained conditions; #75 visual pop-out; #82 information scent; #103 mental models; #144 review/rating information; #281 optional personalization |
| **Gemini** | #172 source transparency; #181 intent-first interaction; #186 trust calibration support; #191 sources; #197 conversation; #274 AI surfaces |
| **Android / Material** | #45 visual similarity; #52 motion synchrony; #79 hierarchy; #168 microinteractions; #204 color roles; #223 token/component system |
| **Google Play** | #117 visible progress; #121 points/level gamification (Play Points, country-dependent) |
| **Safety and control** | #173 privacy controls; #260 Undo Send and optional stop cues; #261 time limits/reminders; #267 age-appropriate autoplay and bedtime defaults |

## Important interpretive distinctions

1. **Search vs YouTube:** Search is typically intentional question answering, while YouTube prominently supports algorithmic discovery and continued viewing. Do not treat Search as an infinite-scroll entertainment product.
2. **YouTube recommendations are not only watch-time maximization:** YouTube documents viewer satisfaction surveys, dislikes and “Not interested” controls as signals alongside watch history and subscriptions. [S3]
3. **Material is a design system, not compliance proof:** A toolkit offering motion, dynamic color or target sizes does not establish that every Google property uses it or conforms to every accessibility criterion. [S9]
4. **Gmail nudges are task reminders:** They need not be equated with addictive notification loops. [S16]
5. **Gemini source links are limited:** Links may be offered, but outputs and citations can be inaccurate; do not present generated text as verified without checking. [S10] [S11]
6. **Color has no universally addictive wavelength:** Brand palettes and red badges are attention/meaning cues; color cannot be equated with dopamine release or addiction.
7. **Not reviewed:** No user-specific Google account data, experiments, internal design documents or confidential engineering choices were accessed.

## Detailed mapping — every original principle

**Status legend:** F = documented/observable feature · I = inferred psychological connection · G = generic/qualified connection · N = not established.

### Information processing and cognitive capacity

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 1 | Working memory and Miller's Law | **G** | Search, Gmail | Results and inbox layouts externalize memory, but no universal item limit is proven. | [S1] [S5] |
| 2 | Chunking | **F** | Gmail, Maps | Inbox categories and grouped route information organize related items. | [S5] [S8] |
| 3 | Cognitive Load Theory (Sweller) | **G** | Search, Gmail | A simple search entry and automatic email categorization may reduce interface effort; cognitive load was not measured here. | [S1] [S5] |
| 4 | Selective attention | **I** | YouTube, Gmail | Suggestions and inbox nudges can compete for selective attention; specific effects depend on person and context. | [S3] [S16] |
| 5 | Paradox of the Active User (Carroll and Rosson, 1987) | **G** | Search, Maps | Users can search or navigate immediately instead of completing a mandatory tutorial; no internal rationale verified. | [S1] [S8] |
| 6 | Progressive disclosure | **F** | Search, Gmail | Autocomplete unfolds while typing and Gmail advanced settings are separate from basic actions. | [S2] [S5] |
| 7 | Recognition over recall | **F** | Search, Chrome | Autocomplete predicts queries while Chrome's omnibox may display familiar searches. | [S2] |
| 8 | Signal-to-noise ratio | **G** | Search | Search home keeps input visually prominent; measured signal-to-noise improvement unverified. | [S1] |
| 9 | Dual-process theory (System 1 and System 2, Kahneman and Tversky) | **I** | Search, YouTube | Fast search selection and effortless playback may favor low-deliberation decisions, not evidence of intended System-1 manipulation. | [S1] [S4] |
| 10 | Dynamic friction | **N** | — | No verified Google feature was identified that algorithmically changes friction specifically after inferring hesitation or ability. | — |
| 11 | Information bias | **I** | Search | Related-search prompts provide extra information; whether that exploits information bias is unknown. | [S2] |
### Decision dynamics and choice architecture

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 12 | Hick's Law (Hick-Hyman) | **G** | Search, Gmail | Suggestions and compact Smart Reply choices can simplify decisions, but Hick-Hyman effects have not been measured. | [S2] [S6] |
| 13 | Choice overload (Paradox of Choice) | **G** | Gmail, Search | Categorization and result ranking prioritize options without proving a choice-overload causal effect. | [S1] [S5] |
| 14 | Pareto Principle (80/20) | **G** | Search | Top-ranked results emphasize relevance; Pareto 80/20 is only a heuristic, not a Google-validated law. | [S1] |
| 15 | Occam's Razor | **G** | Search | Prominent search box reflects simplicity as a design outcome, not proof of adopting Occam's Razor. | [S1] |
| 16 | Parkinson's Law | **N** | — | No Google-specific Parkinson's-Law use was established. | — |
| 17 | Confirmation bias | **I** | YouTube, Search | Personalized recommendations could reinforce familiar views for some people; confirmation bias is not verified for every feed. | [S3] [S1] |
| 18 | Priming | **N** | — | No credible product-specific priming experiment or intentional use established. | — |
| 19 | Anchoring | **I** | Play | Displayed reference prices might anchor shoppers; no specific Google Play reference-price intervention established. | — |
| 20 | Compromise effect (extremeness aversion) | **N** | — | No verified Google example of a deliberate middle-option compromise effect. | — |
| 21 | Decoy effect (asymmetric dominance, Huber, Payne and Puto, 1982) | **N** | — | No verified asymmetric-decoy pricing use in the assessed products. | — |
| 22 | Availability heuristic | **I** | Search | Prominent ranked examples may influence availability judgments, but this is not an established Search design intention. | [S1] |
| 23 | Affect heuristic | **I** | YouTube, Maps | Video thumbnails and review imagery can evoke emotions; affect-heuristic impacts are contextual. | [S3] [S7] |
| 24 | Framing effect | **I** | Search | Result snippets frame what a destination offers, but no particular framing experiment is documented here. | [S1] |
| 25 | Loss aversion | **I** | YouTube | Notifications about new uploads may evoke fear of missing out; loss-aversion effects remain untested here. | [S3] |
| 26 | Status quo bias | **F** | YouTube, Gmail | Recommendation surfaces and inbox settings have defaults that users can alter through controls. | [S3] [S5] |
| 27 | Default effect | **F** | Gmail, YouTube | Smart Compose settings and autoplay controls have configurable defaults; teen autoplay defaults differ. | [S21] [S4] |
| 28 | Negativity bias | **I** | YouTube | Negative comments and headlines may attract attention; no claim Google uses negativity bias intentionally. | [S3] |
| 29 | Optimism bias | **N** | — | No Google-specific optimism-bias use established. | — |
| 30 | Planning fallacy | **N** | — | No Google-specific planning-fallacy use established. | — |
| 31 | Projection bias | **N** | — | No Google-specific projection-bias use established. | — |
| 32 | Present bias (hyperbolic discounting, Laibson beta) | **I** | YouTube | An immediately available next video may make short-term entertainment attractive; present-bias effects not established. | [S4] |
| 33 | Sunk cost fallacy | **I** | Gmail, Photos | Accumulated content and archives may raise switching costs; this does not demonstrate sunk-cost fallacy. | — |
| 34 | Opportunity cost neglect | **I** | YouTube | Long viewing sessions may crowd out other activities, but opportunity-cost neglect is not a verified design objective. | [S4] |
| 35 | IKEA effect | **I** | Drive, Docs | User-created documents may be valued more due to their own effort; IKEA-effect mechanism unmeasured. | — |
| 36 | Endowment effect | **I** | Drive, Photos | Personal ownership of stored content could increase subjective value; not a verified experimental outcome. | — |
| 37 | Bandwagon effect | **I** | YouTube | View, like, and subscriber counts can function as popularity cues, not evidence they cause bandwagon behavior. | [S3] |
| 38 | Survivorship bias | **N** | — | No product-specific survivorship-bias design use established. | — |
| 39 | Zero-risk bias | **N** | — | No verified deliberate zero-risk-bias mechanism identified. | — |
| 40 | Ambiguity aversion (Ellsberg) | **G** | Maps | Live traffic and route information can reduce uncertainty, but ambiguity-aversion theory is only a lens. | [S8] |
| 41 | Dunning-Kruger effect | **N** | — | Dunning-Kruger is not an established feature design basis. | — |
| 42 | Curse of knowledge | **G** | Search | Autocomplete can help novice query formulation without proving it is a response to curse-of-knowledge research. | [S2] |
| 43 | Hindsight bias | **N** | — | No hindsight-bias mechanism evidenced. | — |
### Gestalt principles of visual perception

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 44 | Proximity | **F** | Gmail, Search | Grouped email threads and result cards visibly place related content together. | [S5] [S1] |
| 45 | Similarity | **F** | Android | Material components apply consistent styling to related controls; toolkit availability differs from implementation. | [S9] |
| 46 | Common region | **F** | Search, Gmail | Result groupings and inbox categories visually distinguish related content. | [S1] [S5] |
| 47 | Closure | **G** | Android | Simple icons in Material may be read through closure; explicit closure-driven testing unverified. | [S9] |
| 48 | Continuity | **F** | Gmail, YouTube | Email threads and sequential video browsing visibly group ordered content. | [S5] [S3] |
| 49 | Prägnanz (good figure) | **G** | Android | Material's shape and icon grammar are compatible with good-figure perception; no Google-wide experiment established. | [S9] |
| 50 | Uniform connectedness | **F** | Maps, Gmail | Route lines and email thread groupings indicate connected elements. | [S8] [S5] |
| 51 | Figure-ground | **F** | Android, Gemini | Overlays and active surfaces are addressed by Material hierarchy; not all apps share one implementation. | [S9] |
| 52 | Synchrony (common fate) | **F** | Android | Material motion specifications can animate related elements together. | [S9] |
### Ergonomics, interaction physics and responsiveness

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 53 | Fitts's Law (1954) | **G** | Android, Maps | Navigation targets and controls may be designed for reachability, but Fitts-law timing not audited. | [S9] [S8] |
| 54 | Touch target sizing | **G** | Android | Material offers touch-target guidance; this is a documented design-system principle, not all-app conformance proof. | [S9] |
| 55 | Thumb zone and peripheral vision | **G** | Android | Mobile layouts can prioritize reachable actions, but no universal thumb-zone compliance proven. | [S9] |
| 56 | Spatial memory and gesture ergonomics | **F** | YouTube, Maps | Familiar swipes and map gestures support repeated spatial actions; actual motor learning not measured. | [S3] [S8] |
| 57 | Doherty threshold (1982 / 1988) | **G** | Search | Google documents efforts to reduce result latency; 400 ms is not a verified product-specific threshold. | [S1] |
| 58 | Nielsen's response time limits | **G** | Search | Search emphasizes low latency, without promising universal 0.1/1/10-second guarantees. | [S1] |
| 59 | Optimistic UI | **G** | Gmail | Undo Send is a short cancellation window, not proof of an optimistic backend update; true optimistic UI adoption not established. | [S15] |
| 60 | Skeleton screens vs spinners | **G** | Android | Material includes progress components; no blanket claim that all Google apps use skeletons instead of spinners. | [S9] |
| 61 | Progress bar psychology | **F** | Android | Material supports progress indicators, which show processing state, not a proven progress-bar psychology effect. | [S9] |
| 62 | Operational transparency (Buell and Norton, 2011) | **G** | Maps | Live route/traffic information makes ongoing conditions visible; service-value effect not measured. | [S8] |
| 63 | Maister's waiting principles | **G** | Maps | Estimated routes and traffic information reduce some waiting uncertainty; Maister effects not tested. | [S8] |
| 64 | Duration neglect | **I** | YouTube | Remembered sessions may depend on peaks and endings, but no measured duration-neglect deployment. | [S3] |
| 65 | Explained uncertainty | **F** | Maps | Routes and live traffic give explicit conditions and alternatives instead of unexplained delay. | [S8] |
| 66 | Gamified waits | **G** | Android | Material animated progress elements can add interest to waits, not proof of gamified waiting effects. | [S9] |
| 67 | Flow (Csikszentmihalyi, 1990) | **I** | YouTube, Docs | Watching or creating may support flow; flow state cannot be inferred solely from interface. | [S3] |
| 68 | Tesler's Law (conservation of complexity) | **G** | Gmail, Maps | Smart Compose and automated route calculation absorb task complexity, but Tesler's Law is an analogy. | [S21] [S8] |
| 69 | Postel's Law (robustness) | **G** | Gmail | Recipient suggestions and tolerant search may reduce rigid formatting; no broad robustness audit performed. | [S15] |
| 70 | Weber-Fechner (just noticeable difference) | **N** | — | No verified deliberate use of Weber-Fechner psychophysical thresholds. | — |
### Attention and perception

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 71 | Banner blindness | **G** | Search | Search-result labeling helps distinguish ads from results; banner-blindness exploitation unverified. | [S1] |
| 72 | Change blindness | **G** | Gmail | Nudges surface follow-up reminders, but change-blindness rationale unverified. | [S16] |
| 73 | Inattentional blindness | **G** | Gmail | Important messages may be missed in busy inboxes; no established inattentional-blindness exploitation. | — |
| 74 | Cocktail party effect | **I** | Gmail | Personally relevant inbox nudges could draw attention; mechanism is not independently measured. | [S16] |
| 75 | Preattentive processing (pop-out) | **F** | Maps, Android | Traffic coloration and prominent Material controls make some states visually distinctive. | [S7] [S9] |
| 76 | Von Restorff (isolation) effect | **F** | Android | Material expressive color/shape choices enable isolated visual emphasis; not a verified memory gain. | [S9] |
| 77 | F-pattern | **G** | Search | Result snippets suit quick scanning, but no universal F-pattern behavior verified. | [S1] |
| 78 | Z-pattern and Gutenberg diagram | **N** | — | No product-specific Z-pattern or Gutenberg-diagram claim established. | — |
| 79 | Visual hierarchy and visual weight | **F** | Search, Android | Search prioritizes query/results; Material provides layout, typography and emphasis tools. | [S1] [S9] |
| 80 | Mere exposure effect (Zajonc, 1968) | **I** | Google ecosystem | Repeated brand symbols could contribute to familiarity; mere-exposure causality not established. | — |
| 81 | Curiosity gap (Loewenstein, 1994) | **I** | YouTube, Search | Unknown next videos and related topics create discovery gaps; curiosity mechanism inferred. | [S3] [S2] |
| 82 | Information scent (Pirolli and Card, 1999) | **F** | Search, Maps | Search snippets and map directions signal what lies behind results and paths. | [S1] [S8] |
| 83 | Saliency and iso-feature suppression | **F** | Maps, Android | Traffic indicators and contrasting Material components create visual saliency. | [S7] [S9] |
| 84 | Top-down guidance | **G** | Search | Queries guide ranked-result attention, consistent with top-down search goals. | [S1] |
| 85 | Novelty | **F** | YouTube, Search | Fresh recommendations and trending queries can introduce novel content. | [S3] [S2] |
### Memory, learning and experience evaluation

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 86 | Peak-end rule (Kahneman and Fredrickson, 1993) | **I** | YouTube | Creators and viewers may remember high points and endings differently, but Google's adoption of peak-end rule is unverified. | — |
| 87 | Serial position effect | **G** | Search | Ranked top results have position prominence; serial-position memory effect not validated. | [S1] |
| 88 | Zeigarnik effect (1927) | **I** | Gmail | Unreplied message nudges resemble interrupted-task resumption; Zeigarnik memory advantage is not established. | [S16] |
| 89 | Aesthetic-usability effect (Kurosu and Kashimura, 1995) | **G** | Android | Material emphasizes attractive visual design; attractiveness does not prove usability. | [S9] |
| 90 | Forgetting curve (Ebbinghaus, 1885) | **N** | — | No Google feature directly validates a fixed forgetting curve. | — |
| 91 | Spacing effect | **G** | YouTube | Repeated learning videos can support spaced practice, but no general spaced-repetition engine is established. | [S3] |
| 92 | Testing effect (Roediger and Karpicke, 2006) | **N** | — | No specific Google platform-wide retrieval-practice effect established. | — |
| 93 | Verbatim effect | **N** | — | No product-specific verbatim-memory intervention established. | — |
| 94 | Picture superiority effect | **F** | YouTube, Maps | Video thumbnails and maps combine images with content labels. | [S3] [S8] |
| 95 | Dual coding (Paivio, 1971) | **F** | Maps | Visual routes plus voice navigation are available, consistent with dual channels without proving dual-coding effect. | [S8] |
| 96 | Google effect (digital amnesia) | **I** | Search | External retrieval may reduce need to remember details; 'Google effect' is a psychology study, not a feature Google claims to deploy. | [S1] |
| 97 | Misinformation effect (Loftus) | **N** | — | No deliberate misinformation-effect design identified. | — |
| 98 | Scaffolding (Vygotsky) | **G** | Gmail | Smart Compose can scaffold email writing; not a verified Vygotsky-style learning outcome. | [S21] |
| 99 | Generation effect (Slamecka and Graf, 1978) | **I** | Docs | Writing content oneself may improve recall, but no Google generation-effect intervention verified. | — |
| 100 | Spatial and procedural memory | **F** | Maps, Gmail | Repeated navigation gestures and email routines use learned procedural patterns. | [S8] [S5] |
| 101 | Interrupted-task resumption and off-hours rumination | **F** | Gmail | Reply/follow-up nudges help resume incomplete conversation tasks; rumination effects unverified. | [S16] |
### Usability heuristics and mental models

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 102 | Jakob's Law | **G** | Android, Chrome | Familiar navigation patterns are compatible with Jakob's Law; no brand-wide test established. | [S9] [S2] |
| 103 | Mental models | **F** | Maps, Search | Common search bars and route alternatives align with recognizable user task models. | [S1] [S8] |
| 104 | Nielsen's 10 heuristics | **G** | Google ecosystem | Nielsen's heuristics can audit the products, but no claim Google universally uses the checklist. | — |
### Motivation, habit and engagement

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 105 | Fogg Behavior Model (B = MAP) | **I** | YouTube, Gmail | An easy action plus notifications as prompts resembles Fogg's conceptual model; no internal framework adoption proven. | [S3] [S16] |
| 106 | Hook model (Eyal) | **I** | YouTube | Recommendations/notifications followed by watching, likes, subscriptions resemble Eyal's Hook loop, not proof of company intent. | [S3] |
| 107 | Habit loop (cue, routine, reward; Duhigg, Wood and Neal) | **I** | YouTube, Gmail | Recurrent cues may generate checking routines; habitual checking is not clinical addiction. | [S3] [S16] |
| 108 | COM-B (Capability, Opportunity, Motivation) | **G** | Maps | Navigation removes ability barriers while value motivates use; COM-B use not verified. | [S8] |
| 109 | PSYCH framework | **N** | — | No evidence Google directly implemented the commercial PSYCH framework. | — |
| 110 | Operant conditioning (Skinner) | **I** | YouTube, Play | Likes and Play Points are rewards, but operant-conditioning schedule and behavior change unverified. | [S3] [S14] |
| 111 | Schedules of reinforcement | **I** | YouTube | Uncertain next recommendation is not by itself a formal variable-ratio reinforcement schedule. | [S3] |
| 112 | Variable rewards (Eyal) | **I** | YouTube | Recommendations can bring unexpectedly enjoyable videos; variable-reward interpretation is plausible. | [S3] |
| 113 | Dopamine reward prediction error | **N** | — | No evidence Google engineers specific dopamine-prediction-error pathways; dopamine claims would be overreach. | — |
| 114 | Investment and stored value | **F** | Gmail, YouTube | Stored messages, subscriptions, playlists and histories accumulate user value. | [S3] [S5] |
| 115 | Self-Determination Theory (Deci and Ryan) | **I** | YouTube, Docs | Audience connection and authoring may support relatedness/competence/autonomy; effects vary by user. | [S3] |
| 116 | Overjustification effect (Lepper, Greene and Nisbett, 1973) | **N** | — | No verified overjustification-effect intervention. | — |
| 117 | Progress principle (Amabile and Kramer, 2011) | **F** | Play | Play Points levels show observable accumulated progress; motivational effects not proven. | [S14] |
| 118 | Goal-gradient effect (Hull, 1932; Kivetz et al., 2006) | **I** | Play | Showing progress toward next Play Points level could suggest goal-gradient, not an established causal effect. | [S14] |
| 119 | Endowed progress effect (Nunes and Dreze, 2006) | **N** | — | No independently verified endowed-progress manipulation. | — |
| 120 | Streaks and loss-framed momentum (Duolingo) | **N** | — | No general Google-product daily streak akin to Duolingo documented in this review. | — |
| 121 | Gamification (points, badges, leaderboards) | **F** | Play | Play Points tiers and perks are a documented points-and-levels gamification system. | [S14] |
| 122 | Customization and ownership | **F** | Android, Maps | Material adaptive themes and saved places provide customization/ownership. | [S9] [S13] |
| 123 | Fresh start effect (Dai, Milkman and Riis, 2014) | **N** | — | No verified fresh-start-effect initiative. | — |
| 124 | Commitment devices and deadlines (Ariely and Wertenbroch, 2002) | **F** | YouTube | Shorts time limits and bedtime reminders can serve user-chosen commitments; self-control impact varies. | [S17] [S18] |
| 125 | Temptation bundling (Milkman, Minson and Volpp, 2014) | **N** | — | No general verified temptation-bundling feature. | — |
| 126 | Effort heuristic (Kruger et al., 2004) | **I** | Gmail | Automated drafting may change perceived effort or value, but effort-heuristic effect unverified. | [S21] |
| 127 | Anticipation | **I** | YouTube | Upcoming content recommendations may create anticipation; mechanism unverified. | [S3] |
| 128 | Intrinsic vs extrinsic framing of engagement | **G** | YouTube, Play | Content interests and extrinsic Play Points rewards represent differing incentive types, not a controlled comparison. | [S3] [S14] |
| 129 | Fogg's Six Ability Factors | **G** | Gmail | Smart Reply reduces typing, consistent with lower effort barriers; Fogg six factors not tested. | [S6] |
| 130 | Reinforcement learning | **N** | — | Recommendation algorithms are not proof of Skinnerian reinforcement learning or a user-conditioning experiment. | — |
| 131 | Self-monitoring and self-chosen goals | **F** | YouTube | Shorts daily limit and time-watched settings let users monitor and set personal use goals. | [S17] |
### Pricing and economic psychology

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 132 | Mental accounting (Thaler) | **I** | Play | Points earned per spending amount may be mentally tracked separately from currency; mental accounting unverified. | [S14] |
| 133 | Zero-price effect (Shampanier, Mazar and Ariely, 2007) | **F** | Search, Gmail | Core Search and Gmail services offer free-to-use entry points, but zero-price psychological effects unverified. | [S1] [S5] |
| 134 | Partitioned and drip pricing (Morwitz et al., 1998) | **N** | — | No specific verified drip-pricing tactic across assessed Google products. | — |
| 135 | Bundling | **G** | Google ecosystem | Product bundles/integrations exist, but experimental bundling psychology not tested. | — |
| 136 | Currency confusion | **N** | — | No specific currency-confusion design was established. | — |
| 137 | Pricing page psychology | **N** | — | No audited price-page framing or decoy experiment. | — |
| 138 | Nudge theory (Thaler and Sunstein) | **G** | Gmail, YouTube | Nudges and available defaults resemble choice architecture; explicit Nudge Theory adoption unknown. | [S16] [S4] |
| 139 | Choice architecture and friction design | **F** | Gmail, YouTube | Configurable Smart Compose and autoplay settings shape user choices. | [S21] [S4] |
| 140 | Partitioned Pricing & Drip Pricing | **N** | — | No verified partitioned or drip-pricing tactic. | — |
| 141 | Bundling & Temptation Bundling | **G** | Google ecosystem | Service integrations could function as bundles; temptation-bundling claim not established. | — |
### Persuasion and influence (Cialdini plus)

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 142 | Reciprocity | **I** | YouTube | Creators and fans may reciprocate subscriptions or comments; effect not established experimentally. | [S3] |
| 143 | Commitment and consistency | **I** | YouTube | Subscriptions may support repeated engagement; commitment-consistency mechanism unverified. | [S3] |
| 144 | Social proof | **F** | YouTube, Maps | Likes, ratings, reviews and view counts present social information; does not validate behavioral influence in each context. | [S3] [S7] |
| 145 | Authority | **G** | Search | Ranking considers source expertise; an authority cue is present, but user authority-bias effects untested. | [S1] |
| 146 | Liking | **I** | YouTube | Preference for favorite creators could reflect liking; mechanism unverified. | [S3] |
| 147 | Scarcity | **N** | — | Busy-area indicators signify demand/popularity, not verified scarce supply or a scarcity-based intervention. | [S7] |
| 148 | Unity (Cialdini's 7th principle) | **I** | YouTube | Creator communities can serve group identity; Cialdini unity mechanism not measured. | [S3] |
| 149 | Foot-in-the-door (Freedman and Fraser, 1966) | **N** | — | No verified foot-in-the-door request sequence. | — |
| 150 | Door-in-the-face (Cialdini, 1975) | **N** | — | No verified door-in-the-face persuasion sequence. | — |
| 151 | Fear appeals (EPPM, Witte, 1992) | **N** | — | No verified designed fear appeal campaign. | — |
| 152 | Authority bias and social-proof under uncertainty | **I** | Search, Maps | Ranked sources and popularity indicators may influence perceived authority/social norms; context-dependent. | [S1] [S7] |
### Social and group psychology

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 153 | Conformity (Asch, 1951) | **I** | YouTube | Visible popularity can create perceived social norms, not proof of conformity shifts. | [S3] |
| 154 | Social comparison theory (Festinger, 1954) | **I** | YouTube | Subscriber, like and view counts facilitate comparison; individual effects vary. | [S3] |
| 155 | FOMO (Przybylski et al., 2013) | **I** | YouTube | Subscriptions and new uploads might elicit FoMO, but no deterministic link or addiction conclusion. | [S3] |
| 156 | Belonging and relatedness | **F** | YouTube | Subscriptions and creator interactions support belonging and ongoing relationships. | [S3] |
| 157 | Collaboration and shared value | **F** | Docs, Gmail | Shared documents and group email threads support collaboration; not proof of a particular cooperation theory. | [S5] |
| 158 | Social feedback as reward | **I** | YouTube | Comments and likes can be rewarding social feedback, but exact reinforcement impact is unverified. | [S3] |
| 159 | Social desirability bias (research) | **N** | — | Social desirability bias is a research risk, not a demonstrated shipped feature. | — |
| 160 | Personalization / personality fit | **F** | YouTube, Maps, Gmail | YouTube recommendations, Maps AI personalization and Gmail writing-style suggestions adapt to user context. | [S3] [S13] [S21] |
### Emotion, aesthetics and delight

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 161 | Norman's three levels of emotional design | **G** | Android | Material Expressive addresses visual and motion experience; Norman three levels are an analytical framework. | [S9] |
| 162 | Microinteractions and delight | **F** | Android, Gmail | Material motion and Gmail action feedback provide microinteractions. | [S9] [S15] |
| 163 | Voice and humor | **G** | Gemini | Conversational response style can express voice; no general Google humor-psychology claim. | [S20] |
| 164 | Emotional contagion | **N** | — | No Google-specific emotional-contagion feature/measurement verified. | — |
| 165 | Peak-moment design (Heath and Heath, 2017) | **I** | Play | Play Points level upgrades can mark notable moments; deliberate peak-moment theory use unverified. | [S14] |
| 166 | Cognitive dissonance and post-purchase reassurance (Festinger, 1957) | **I** | Play | Post-purchase support may reduce buyer concern; cognitive-dissonance mechanism unverified. | — |
| 167 | Emotionally intelligent interfaces (2026) | **N** | — | No verified emotion detection from tap/scroll/typing or established 'emotionally intelligent interface' system. | — |
| 168 | Micro-interactions & Delight | **F** | Android | Material design includes expressive motion, components and state transitions. | [S9] |
| 169 | Color Psychology (use with caution) | **G** | Android | Material color choices are real, but universal trust/urgency effects of hues are not. | [S9] |
### Trust, credibility and error handling

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 170 | Stanford Web Credibility Guidelines | **G** | Search | Google discusses reliable Search results; no external credibility-score audit has been performed. | [S1] |
| 171 | Trust seals and checkout validation | **N** | — | No specific Google-wide checkout-trust-seal intervention verified. | — |
| 172 | Transparency as differentiator | **F** | Search, Gemini | Search ranking explanations and Gemini source links make some product information inspectable. | [S1] [S10] |
| 173 | Privacy control and the privacy paradox | **F** | Account, Gmail | Web & App Activity and Workspace smart features provide privacy/personalization controls. | [S12] [S5] |
| 174 | Error prevention (poka-yoke) | **F** | Gmail | Undo Send and configurable suggestions help prevent/recover from errors; impact not quantified. | [S15] [S21] |
| 175 | Blame-free error messages | **G** | Gmail | Undo control offers recovery path; quality of error-message wording not audited. | [S15] |
| 176 | Service recovery paradox | **N** | — | No documented service-recovery-paradox experimental effect. | — |
| 177 | Consistency builds trust | **G** | Android | Material provides consistent components, but trust effects not validated across every product. | [S9] |
| 178 | Third-party validation | **G** | Search | Search prioritizes reputed sources; external-validation persuasion impact untested. | [S1] |
| 179 | Perceived security | **G** | Account | Account activity controls may support perceived safety; perception not measured. | [S12] |
| 180 | Progressive permission | **F** | Maps, Gmail | Permissions for Maps location and Gmail smart features can be managed; exact prompt timing varies. | [S8] [S5] |
### AI-era human-AI interaction

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 181 | Shift from command to intent | **F** | Gemini, Search | Natural-language questions and conversational responses shift some tasks from commands to intent. | [S20] [S1] |
| 182 | Automation bias (Skitka and Mosier, 1996) | **I** | Gemini | Users could over-rely on generated answers; Google warns that responses can be wrong. | [S11] |
| 183 | Automation complacency | **I** | Gemini, Maps | Automation can tempt users to skip checking output or routes; complacency not proven. | [S11] [S8] |
| 184 | Algorithm aversion (Dietvorst et al., 2015) | **I** | Gemini | Some users may reject generated suggestions after errors; algorithm aversion not directly measured. | [S11] |
| 185 | Algorithm appreciation (Logg et al., 2019) | **I** | Gemini | Other users may prefer generated suggestions; algorithm appreciation not directly measured. | [S11] |
| 186 | Trust calibration (Lee and See, 2004) | **F** | Gemini | Google provides model limitations and sometimes related sources to support appropriate reliance. | [S10] [S11] |
| 187 | ELIZA effect (Weizenbaum, 1966) | **I** | Gemini | Conversational text may invite attributions of understanding; ELIZA effect remains a hypothesis. | [S20] |
| 188 | Anthropomorphism (Epley et al., 2007) | **I** | Gemini | Conversational interactions may prompt anthropomorphism, not evidence of actual feelings or intent. | [S20] |
| 189 | Uncanny valley (Mori, 1970) | **N** | — | No specific uncanny-valley design case established. | — |
| 190 | AI disclosure effects (Luo et al., 2019) | **F** | Gemini | Gemini is presented as an AI assistant, and Google documents the limits of its responses. | [S20] [S11] |
| 191 | Explainability (XAI) and four-lens framework | **F** | Gemini | Related source links can support checking evidence; they do not make explanations infallible. | [S10] [S11] |
| 192 | Uncertainty communication | **F** | Gemini | Explicit warnings that generated responses may be inaccurate communicate uncertainty at a general level. | [S11] |
| 193 | Human approval before action | **G** | Gemini | Users can review content before they act on it; universal approval-before-tool-action not verified. | [S20] |
| 194 | Context and memory controls | **F** | Gemini, Account | Gemini has activity controls and Google accounts expose data settings. | [S12] [S20] |
| 195 | Streaming and perceived intelligence | **G** | Gemini | Visible response generation can affect perceived latency; no specific streaming psychology test reviewed. | [S20] |
| 196 | Co-creation and authorship | **F** | Gemini, Docs | Users prompt, edit and reuse generated drafts, supporting co-creation; authorship outcomes vary. | [S20] |
| 197 | Conversational UX | **F** | Gemini | Chat-based conversational input and replies are directly documented. | [S20] |
| 198 | Amershi et al. 18 Human-AI guidelines | **G** | Gemini | Human-AI guidelines can evaluate Gemini, but no proof Google adopted all 18 Microsoft research guidelines. | — |
| 199 | AI companion dark patterns (CDT) | **N** | — | No demonstrated Google-wide AI-companion dark-pattern design. | — |
| 200 | Spatial UI, WebXR and Haptics 2.0 | **G** | Android | Material supports motion and touch feedback, but broad spatial WebXR-specific use not audited. | [S9] |
| 201 | Regulation | **G** | Google ecosystem | Regulation is a compliance context, not itself a UI principle Google 'uses'. | — |
### Color psychology and color systems

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 202 | Color-in-context theory (Elliot and Maier) | **G** | Android | Color context varies; Material palettes do not validate particular emotional effects. | [S9] |
| 203 | Evidence status | **G** | Google ecosystem | Evidence labels are research governance rather than deployed Google interface behavior. | — |
| 204 | Hue, lightness and saturation | **F** | Android | Material design works with color roles, typography, lightness and contrast. | [S9] |
| 205 | RGB vs RYB | **G** | Android | Displays use digital color, but RGB-versus-RYB is not a consumer psychology feature. | — |
| 206 | Personality and saturation tolerance | **N** | — | No credible personality-based saturation tolerance implementation found. | — |
| 207 | Saliency and the unique color singleton | **F** | Android | Material color and shape emphasize selected controls; perceptual impact not measured. | [S9] |
| 208 | 60-30-10 rule | **G** | Android | 60-30-10 may be used by designers, but no blanket Google proportion rule established. | [S9] |
| 209 | Harmonies | **F** | Android | Material provides color theme guidance; no single harmony scheme applies everywhere. | [S9] |
| 210 | Semantic mapping | **F** | Maps, Android | Map traffic states and Material semantic colors communicate meanings; color alone must not bear critical meaning. | [S7] [S9] |
| 211 | Button hierarchy by color | **F** | Android | Material visual hierarchy differentiates primary and secondary button actions. | [S9] |
| 212 | Red notification badge as cue | **G** | YouTube, Gmail | Notification badges may use salient colors; no verified universal red-badge engineering or involuntary response claim. | — |
| 213 | Chromatic gamification | **F** | Play | Points/levels make gaming-style progress explicit, but color-induced reward effects are unverified. | [S14] |
| 214 | Retail trading red and green (Robinhood) | **N** | — | Robinhood trading red/green is a non-Google case, not evidence for Google. | — |
| 215 | Losses disguised as wins (LDWs) | **N** | — | No evidenced losses-disguised-as-wins Google feature. | — |
| 216 | Color accessibility (WCAG 2.2) | **G** | Android | Material incorporates accessibility guidance, but no claim of every Google screen passing all WCAG 2.2 criteria. | [S9] |
| 217 | Color vision deficiency | **G** | Android | Color-vision accessibility is a design constraint, not proof of per-app testing. | [S9] |
| 218 | APCA | **N** | — | No established Google-wide APCA implementation or specific Lc adoption. | — |
| 219 | Dark mode | **F** | Gemini, Android | Gemini offers dark theme and Android supports theme variants, not proof dark mode always reduces strain. | [S9] [S20] |
| 220 | OKLCH and CSS Color 4 | **F** | Android | Material modern dynamic color and semantic color roles overlap with modern color-space workflows; specific OKLCH engineering unverified. | [S9] |
| 221 | Cultural variation | **G** | Google ecosystem | International products must consider cultural differences, but no universal mapping verified. | — |
| 222 | CTA color myths | **G** | Android | Google's variable colors demonstrate no single inherently best CTA hue; empirical outcome not measured. | [S9] |
| 223 | Semantic token architecture and design-system workflow | **F** | Android | Material offers themed components and design tokens; implementations vary. | [S9] |
| 224 | Humane color interventions | **G** | YouTube | Time limits and pause prompts are wellbeing controls, not evidence they change color salience. | [S17] |
| 225 | Visual engagement is not clinical addiction | **G** | YouTube | Engagement metrics cannot establish clinical addiction; a caution, not a deployed feature. | [S3] |
| 226 | RGB, cone responses and pigment models | **G** | Android | Color models underlie display rendering; not a psychology intervention. | [S9] |
| 227 | Simultaneous contrast | **G** | Android | Material palettes can create simultaneous contrast, but exact psycho-physical effect not tested. | [S9] |
| 228 | Chromatic adaptation | **N** | — | No verified chromatic-adaptation intervention. | — |
| 229 | Color harmony families | **F** | Android | Material palettes support related color roles and harmonious theming. | [S9] |
| 230 | Palette roles, light/dark variants and contrast validation | **F** | Android | Material provides color roles/theme variants; contrast validation requires a separate audit. | [S9] |
| 231 | CSS variables, OKLCH scales and designer decision matrices | **G** | Android | Material theming maps to token workflows; use of OKLCH CSS variables by Google apps is unverified. | [S9] |
| 232 | Red — color-family coverage | **F** | YouTube | The red YouTube brand is a visible hue example, not evidence red causes urgency or addiction. | — |
| 233 | Orange — color-family coverage | **N** | — | No independently supported orange-hue psychological strategy established. | — |
| 234 | Yellow — color-family coverage | **F** | Google ecosystem | Google brand includes yellow, with no universal behavioral meaning established. | — |
| 235 | Chartreuse / lime — color-family coverage | **N** | — | No distinct Google-wide chartreuse/lime brand psychology mapping established. | — |
| 236 | Green — color-family coverage | **F** | Maps | Green is used in traffic-related visual semantics; precise shades vary by platform. | [S8] |
| 237 | Mint — color-family coverage | **N** | — | No particular mint hue use as an independently established principle. | — |
| 238 | Teal — color-family coverage | **N** | — | No particular teal hue effect or product-specific intent established. | — |
| 239 | Cyan — color-family coverage | **N** | — | No distinct cyan-driven psychological effect established. | — |
| 240 | Blue — color-family coverage | **F** | Google ecosystem | Google blue appears in branding and action interfaces, but 'blue causes trust' is unverified. | — |
| 241 | Indigo — color-family coverage | **N** | — | No specific indigo hue psychology deployment verified. | — |
| 242 | Violet — color-family coverage | **N** | — | No specific violet hue psychology deployment verified. | — |
| 243 | Purple — color-family coverage | **F** | Gemini | Some Gemini brand treatments use purple-like gradients; no addictive effect established. | — |
| 244 | Magenta — color-family coverage | **N** | — | No specific magenta hue psychology deployment verified. | — |
| 245 | Pink — color-family coverage | **N** | — | No specific pink hue psychology deployment verified. | — |
| 246 | Brown — color-family coverage | **N** | — | No specific brown hue psychology deployment verified. | — |
| 247 | Beige — color-family coverage | **N** | — | No specific beige hue psychology deployment verified. | — |
| 248 | Cream — color-family coverage | **N** | — | No specific cream hue psychology deployment verified. | — |
| 249 | White — color-family coverage | **F** | Search | Search commonly presents a light/white canvas, without proof white itself improves trust. | [S1] |
| 250 | Gray — color-family coverage | **F** | Android | Material supports grey/neutral surfaces and text roles. | [S9] |
| 251 | Black — color-family coverage | **F** | Android | Dark surfaces and dark theme variants exist, without universal psychological meaning. | [S9] |
| 252 | Metallic gold — color-family coverage | **N** | — | No metallic-gold color-psychology strategy verified. | — |
| 253 | Metallic silver — color-family coverage | **N** | — | No metallic-silver color-psychology strategy verified. | — |
### Dark patterns, ethics, regulation and ethical retention

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 254 | Dark pattern taxonomy | **G** | Google ecosystem | Dark-pattern taxonomy is an audit framework, not evidence Google uses every listed tactic. | — |
| 255 | Vulnerability each exploits | **G** | Google ecosystem | Bias vulnerabilities can be assessed, but individual exploitation claims need direct evidence. | — |
| 256 | Hyper-engaging dark patterns (HEDPs) / addictive design | **I** | YouTube | Shorts continuous discovery and autoplay are cited in hyper-engagement discussions; not proof of addiction by themselves. | [S3] [S4] |
| 257 | Evidence on repeat-use mechanics | **F** | YouTube | YouTube explicitly documents autoplay, recommendations and user controls; behavioral effects require separate studies. | [S3] [S4] [S17] |
| 258 | Dark pattern harm evidence | **G** | Google ecosystem | Harm research in the source is not specifically evidence against Google products. | — |
| 259 | Regulation snapshot | **G** | Google ecosystem | Regulatory snapshots are context, not established current compliance findings. | — |
| 260 | Intentional friction | **F** | Gmail, YouTube | Undo Send and Shorts time limits introduce optional pauses/stop controls. | [S15] [S17] |
| 261 | Digital wellbeing and humane design | **F** | YouTube | Shorts daily limits, bedtime reminders and sleep timers are documented wellbeing tools. | [S17] [S18] [S19] |
| 262 | Ethical retention loop | **G** | Gmail | Nudges support returning to unfinished valuable tasks, consistent with ethical retention. | [S16] |
| 263 | Ethical retention rules | **G** | Google ecosystem | Ethical retention rules are an evaluative checklist; full internal compliance unknown. | — |
| 264 | Metrics beyond DAU and session length | **F** | YouTube | YouTube reports satisfaction surveys in recommendation signals beyond simple viewing duration. | [S3] |
| 265 | Designer ethics checklist | **G** | Google ecosystem | Designer ethics checklist is a recommended audit, not a verified internal process. | — |
| 266 | Rule of thumb | **G** | Google ecosystem | Rule-of-thumb principles should be checked against observed outcomes and harms. | — |
| 267 | Children, age-appropriate controls and wellbeing | **F** | YouTube | Autoplay off by default for users 13–17; bedtime reminders on by default for that age group. | [S4] [S18] |
| 268 | Transaction test and choice inconsistency | **N** | — | No direct Google-specific transaction-test outcome established. | — |
### Applied playbooks

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 269 | Pricing page | **G** | Play | Paid offers and Play subscriptions can be audited for choice and clarity; no concrete pricing-page psychology claim here. | — |
| 270 | Onboarding | **G** | Gmail, Gemini | First-use experiences may be simplified, but product-specific onboarding A/B results unavailable. | — |
| 271 | Paywall and trial end | **N** | — | No verified Google paywall-and-trial-ending pattern from the assessed sources. | — |
| 272 | Notifications and re-engagement | **F** | Gmail | Nudges prompt replying/follow-up to earlier email conversations. | [S16] |
| 273 | Search and results | **F** | Search | Autocomplete, contextual ranking, and results presentation directly support Search/result design analysis. | [S1] [S2] |
| 274 | AI feature surfaces | **F** | Gemini | Generative responses, source links, and warnings make AI surfaces suitable for trust analysis. | [S10] [S11] |
| 275 | Forms and settings | **F** | Gmail, Account | Settings allow users to control smart features and saved activity. | [S5] [S12] |
| 276 | Errors and empty states | **F** | Gmail | Undo Send is a concrete recovery affordance and Gmail offers explicit suggestions. | [S15] [S21] |
| 277 | Paywall & trial-ending | **N** | — | No verified paywall/trial-ending tactic identified. | — |
### Repeat-use mechanics and experimentation

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 278 | Notifications, interruptions and checking | **I** | Gmail, YouTube | Nudges and content suggestions may prompt checking; frequency and habit effects not established. | [S16] [S3] |
| 279 | Infinite scroll and stopping cues | **F** | YouTube | Shorts is a continuously scrollable vertical-video feed, with a daily use-limit control. | [S3] [S17] |
| 280 | Autoplay and continuation automation | **F** | YouTube | Autoplay of the next related video is documented, including opt-out and teen defaults. | [S4] |
| 281 | Personalised recommenders, filter bubbles and diversity | **F** | YouTube, Maps | Personalized recommendations use watch history/signals; Maps AI may use saved preferences when enabled. | [S3] [S13] |
### Accessibility and evidence interpretation

| # | Original principle | Status | Product(s) | Assessment | Evidence |
|---:|---|:---:|---|---|---|
| 282 | Accessibility beyond color and minimum conformance | **G** | Android | Material publishes accessibility support, but full conformance demands audits beyond color. | [S9] |
| 283 | Cognitive-digital research heterogeneity and attention control | **G** | Google ecosystem | User effects differ across ages, contexts and tasks; direct causal findings should not be inferred from feature matches. | — |

## Source register — Google primary sources

The material below supports **feature existence**, not inferred motivation or psychological effectiveness.

- [S1] [Google Search ranking and results](https://www.google.com/intl/en_us/search/howsearchworks/how-search-works/ranking-results/)
- [S2] [Google Search Autocomplete](https://blog.google/products-and-platforms/products/search/how-google-autocomplete-predictions-work/)
- [S3] [YouTube recommendation system](https://support.google.com/youtube/answer/16089387?hl=en-in)
- [S4] [YouTube Autoplay settings](https://support.google.com/youtube/answer/6327615)
- [S5] [Gmail smart feature controls](https://support.google.com/mail/answer/15604322)
- [S6] [Gmail Smart Reply](https://workspace.google.com/intl/en/features/smart-reply/)
- [S7] [Google Maps area busyness](https://support.google.com/maps/answer/11323117)
- [S8] [Google Maps navigation](https://support.google.com/maps/answer/3273406)
- [S9] [Google Material Design 3](https://m3.material.io/)
- [S10] [Gemini related sources](https://support.google.com/gemini/answer/14143489)
- [S11] [Gemini model response limitations](https://support.google.com/gemini/answer/16279220)
- [S12] [Google account Web & App Activity](https://support.google.com/accounts/answer/54068)
- [S13] [Google Maps personalized responses](https://support.google.com/maps/answer/16833938)
- [S14] [Google Play Points levels — India](https://support.google.com/googleplay/answer/9080348?co=GENIE.CountryCode%3DIN)
- [S15] [Gmail Undo Send](https://support.google.com/mail/answer/2819488)
- [S16] [Gmail follow-up nudges](https://support.google.com/mail/answer/6585)
- [S17] [YouTube Shorts daily limit](https://support.google.com/youtube/blog/382356516/a-new-way-to-manage-your-time-on-shorts?hl=en)
- [S18] [YouTube bedtime reminder](https://support.google.com/youtube/answer/9884905)
- [S19] [YouTube sleep timer](https://support.google.com/youtube/answer/15397997)
- [S20] [Gemini app operation](https://support.google.com/android/answer/13275745)
- [S21] [Gmail Smart Compose](https://support.google.com/mail/answer/9116836)

[S1]: https://www.google.com/intl/en_us/search/howsearchworks/how-search-works/ranking-results/
[S2]: https://blog.google/products-and-platforms/products/search/how-google-autocomplete-predictions-work/
[S3]: https://support.google.com/youtube/answer/16089387?hl=en-in
[S4]: https://support.google.com/youtube/answer/6327615
[S5]: https://support.google.com/mail/answer/15604322
[S6]: https://workspace.google.com/intl/en/features/smart-reply/
[S7]: https://support.google.com/maps/answer/11323117
[S8]: https://support.google.com/maps/answer/3273406
[S9]: https://m3.material.io/
[S10]: https://support.google.com/gemini/answer/14143489
[S11]: https://support.google.com/gemini/answer/16279220
[S12]: https://support.google.com/accounts/answer/54068
[S13]: https://support.google.com/maps/answer/16833938
[S14]: https://support.google.com/googleplay/answer/9080348?co=GENIE.CountryCode%3DIN
[S15]: https://support.google.com/mail/answer/2819488
[S16]: https://support.google.com/mail/answer/6585
[S17]: https://support.google.com/youtube/blog/382356516/a-new-way-to-manage-your-time-on-shorts?hl=en
[S18]: https://support.google.com/youtube/answer/9884905
[S19]: https://support.google.com/youtube/answer/15397997
[S20]: https://support.google.com/android/answer/13275745
[S21]: https://support.google.com/mail/answer/9116836

## Method and limitations

1. Parsed titles and numbers from the main **Numbered principles list** section in the supplied Markdown, not its 16 prefatory corrections or its repeated verbatim appendix.
2. Classified each entry against publicly visible or Google-documented product features; cited direct Google sources where the row relies on a technical or policy claim.
3. Set speculative neuroscience, addiction, controversial color effects and unverified commercial influence tactics to `I`, `G` or `N`, rather than claiming Google employs them.
4. No live A/B tests, proprietary internal datasets, source code audits, direct user sessions, or all-country product audits were performed. User experiences can differ.
5. The original file warns that its 283 entries include laws, heuristics, practices, controversies, research topics and colors; they are **not** 283 separately validated psychological effects.

## What a designer should learn from this comparison

- For **task success**, study Search query simplicity, relevance cues, autocomplete, Maps navigation and Gmail reminders.
- For **media discovery**, study YouTube ranking, satisfaction signals, Shorts navigation and explicit stop controls.
- For **visual systems**, study Material component hierarchy, motion, state semantics and accessibility testing.
- For **human-AI interfaces**, study Gemini limitations, grounding/source links, correction and user agency.
- For **ethical retention**, prefer genuine value, transparency and control over manufactured urgency or compulsive loops.
