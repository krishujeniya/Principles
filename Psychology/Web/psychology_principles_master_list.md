# Psychology Principles for Web, SaaS and Mobile Product Design: Master List (through 2026)

Merged from 7 source documents. Duplicates are combined into one entry, and where sources disagree or add a caveat, the caveat is kept inside the entry. Format per entry: **Name**: what it is. Apply: how it shows up in design. Watch: risk, limit or ethical edge.

## Source notes

- Full content was merged from documents 1, 3, 6 and 7.
- Documents 2, 4 and 5 were short summaries that pointed to downloadable files (198-item catalogue, habit-forming catalogue, 40 color palettes). Those linked files were not in the upload, so only the principles, findings and caveats stated in the summary text are included. The 40 palettes and 60 linked papers are not reproduced.
- Conflicts between sources are listed in Section 17.

## Top 20 highest-leverage principles (from document 6)

Hick's Law, Fitts's Law, Jakob's Law, Miller's Law / working memory, cognitive load, progressive disclosure, recognition over recall, thumb zone, Doherty threshold, aesthetic-usability effect, peak-end rule, serial position, goal-gradient + endowed progress, loss aversion, defaults / status quo, social proof, anchoring and framing, honest scarcity, Fogg B=MAP, Hook model, trust calibration (AI).

---

## 1. Information processing and cognitive capacity

- **Working memory and Miller's Law**: Working memory is limited. Miller (1956) said about 7 plus or minus 2 items; Cowan (2001) revised it to about 4 chunks. Apply: chunk data, split long forms into steps, format phone, card and license numbers in groups, keep context visible so users never carry info between screens, plan for 4 (max ~4 top actions, 4 onboarding steps per screen, 4 items per comparison row). Watch: it is not a rule that menus need 7 items (see Section 17).
- **Chunking**: Meaningful groups are held better than raw items. Apply: group settings into categories, break onboarding into 3 to 4 steps, group dashboard metrics logically (unfiltered dozens of metrics break working memory).
- **Cognitive Load Theory (Sweller)**: Effort splits into three kinds.
  - **Intrinsic load**: inherent task complexity. Cannot be removed, only managed with progressive, bite-sized steps.
  - **Extraneous load**: effort wasted decoding a poor interface (clutter, inconsistent patterns, jargon, misalignment). The main UX target to cut.
  - **Germane load**: effort that builds lasting mental schemas. Free it up by removing noise; support with intuitive onboarding and consistent interactions.
  - Apply: one primary action per screen, hide advanced options, use defaults, cut jargon, ask for config at the moment of need. Watch: load includes visual noise, dense text and decision count, not only clicks.
- **Selective attention**: The brain filters to goal-relevant stimuli. Apply: use contrast and placement to steer focus to primary CTAs, never rely on a small banner being noticed, use multiple channels for critical info, put what must be seen in the task path.
- **Paradox of the Active User (Carroll and Rosson, 1987)**: Users skip manuals and start doing. Apply: self-evident first task, contextual teaching at the moment of need, empty states and inline tips instead of tours, skip-and-succeed paths. Watch: forced long tours are read by almost nobody.
- **Progressive disclosure**: Show only what is needed now, defer the rest. Apply: accordions, advanced settings, wizards, context-revealed features. Most reliable fix for cognitive load in SaaS.
- **Recognition over recall**: Recognizing is easier than remembering. Apply: icons with labels, recently used items, search suggestions, breadcrumbs, persistent navigation, autofill. Never ask users to remember an ID, code or prior screen.
- **Signal-to-noise ratio**: Relevant info divided by irrelevant info. Apply: cut decoration from task-critical screens; noise includes badge spam, alert inflation, marketing inserts in workflows.
- **Dual-process theory (System 1 and System 2, Kahneman and Tversky)**: System 1 is fast, automatic, heuristic. System 2 is slow, analytical, tiring. Apply: design routine paths for System 1; add deliberate friction where System 2 should engage (money, deletion, security). Watch: keeping users in System 1 on purpose to block reflection is manipulation.
- **Dynamic friction**: Algorithmically adding or removing cognitive load based on the user's trajectory (skip tutorials for experts, simplify checkout on hesitation). Watch: the same mechanism can make the platform's preferred path always the easiest.
- **Information bias**: People overvalue extra information even when it changes nothing. Apply: fewer decision-relevant dashboard metrics, detail on demand.

## 2. Decision dynamics and choice architecture

- **Hick's Law (Hick-Hyman)**: Decision time grows logarithmically with number and complexity of choices: T = a + b * log2(n + 1). Apply: fewer options per screen, progressive disclosure, search over mega-menus, one decision per screen, limited nav items, simpler pricing matrices. Watch: cutting too hard can starve power users (Postel's Law, Tesler's Law).
- **Choice overload (Paradox of Choice)**: Too many options lower conversion and satisfaction. Iyengar and Lepper jam study: 24 jams = 3% purchase, 6 jams = 30%. Apply: 3 pricing tiers, 6 to 9 nav items, "Recommended" defaults, progressive filters; single-option recommendation in onboarding is reported to cut friction by up to 24%. Watch: not universal; effect size depends on task and domain (Section 17).
- **Pareto Principle (80/20)**: Users spend about 80% of time in 20% of features. Apply: make the core 20% frictionless, nest edge-case features, fix the top few errors users actually hit.
- **Occam's Razor**: Prefer the solution with the fewest steps and assumptions. Apply: remove fields, steps and options that do not earn their place.
- **Parkinson's Law**: Work expands to fill available time. Apply: show short completion times ("two minutes"), default to short estimates, time-boxing affordances.
- **Confirmation bias**: People favor info that fits existing beliefs. Apply: keep brand promise consistent from marketing site to dashboard; in analytics, show disconfirming evidence; in onboarding, surface the missing step rather than only validating the plan.
- **Priming**: Earlier stimuli shape later responses. Apply: premium visual quality at the marketing stage primes trust in the dashboard; use context-consistent imagery and copy. Watch: many priming studies failed replication; do not claim causality you cannot measure.
- **Anchoring**: The first number seen skews later judgments (Tversky and Kahneman, 1974). Apply: premium tier first or on the left, original price next to discount, "from $X". Watch: fake "was" prices are deceptive pricing.
- **Compromise effect (extremeness aversion)**: People avoid the cheapest and most expensive and pick the middle. Apply: pair a high anchor with a highlighted middle tier.
- **Decoy effect (asymmetric dominance, Huber, Payne and Puto, 1982)**: A clearly inferior third option shifts choice toward the target. Example: $10 basic, $20 pro, $22 pro-plus. Apply: decoys must be genuinely purchasable, not imaginary.
- **Availability heuristic**: Likelihood is judged by how easily examples come to mind. Apply: a recent outage outweighs months of uptime, so communicate reliability proactively (status page, uptime badge).
- **Affect heuristic**: Decisions ride on current feeling. Apply: playful tone for low stakes, calm data-forward tone for money, security and deletion.
- **Framing effect**: Same facts, different presentation, different choice ("90% success" vs "10% failure"). Apply: frame benefits positively by default; use loss framing only with honest stakes. Watch: effect size depends on context (Section 17).
- **Loss aversion**: Losses weigh more than equivalent gains. Classic estimate is about 2x; a 2024 meta-analysis (607 estimates, 150 papers) found a mean near 1.96 with real heterogeneity. Apply: trials framed as what you will lose when they end (list of locked features), show what users already have at stake before downgrade prompts, streak and expiring-credit language. Watch: manufactured losses and punitive recovery are coercion; loss aversion powers most dark patterns.
- **Status quo bias**: Inertia makes the current state the default path (Samuelson and Zeckhauser, 1988). Apply: make the desired behavior the status quo (sensible preselections, annual billing with monthly toggle); keep delete and downgrade deliberately considered.
- **Default effect**: Whatever is preselected wins (Johnson and Goldstein, 2003; Thaler and Sunstein, 2008). Apply: smart, visible, changeable defaults for notifications, plan, templates, privacy. Watch: defaults that serve the business against the user (opt-out data sharing) are manipulative and increasingly illegal.
- **Negativity bias**: Negatives weigh more than positives (Rozin and Royzman, 2001). Apply: surface review volume and response quality, lead error states with the fix, moderate communities.
- **Optimism bias**: People overestimate future behavior ("I'll use this daily"). Apply: design re-engagement journeys for annual plans and courses.
- **Planning fallacy**: People underestimate task duration (Kahneman and Tversky, 1979). Apply: prefill estimates from history, show buffers, forecast from actual velocity.
- **Projection bias**: People project their calm present state onto their future self and assume they will resist temptation. Apply: offer commitment tools, do not rely on future willpower.
- **Present bias (hyperbolic discounting, Laibson beta)**: Value drops steeply between now and soon, flatly later; this causes preference reversals. Apply: make future benefit and future cost concrete and near ("Card charged in 3 days, click to change"), deliver value in the first session. Watch: platforms compress time horizons (autoplay, micro-moments), place friction asymmetrically (easy to spend, hard to leave or cancel), and use free trials where the benefit is vivid and the cost abstract.
- **Sunk cost fallacy**: Past investment increases commitment (Arkes and Blumer, 1985). Apply: surface accumulated value honestly at renewal, offer one-click import to lower switching cost. Watch: trapping users in unwanted subscriptions is a roach motel.
- **Opportunity cost neglect**: Users ignore alternative uses of their time during an immediate digital reward. Watch: amplified by immersive interfaces.
- **IKEA effect**: Self-built things are overvalued (Norton, Mochon and Ariely, 2012). Apply: let users build their first dashboard, doc or workspace (prefilled but editable); user-made templates and automations raise switching cost legitimately.
- **Endowment effect**: Ownership raises perceived value (Kahneman, Knetsch and Thaler, 1990). Apply: trials on real user data beat trials on demo data; "your workspace", "your reports". Conversion framed as not losing the workspace.
- **Bandwagon effect**: People adopt what others adopt. Apply: "Join 40,000 teams", "most popular", with real current numbers.
- **Survivorship bias**: Visible winners hide invisible failures. Apply: show base rates and median outcomes; study churned users, not only power users.
- **Zero-risk bias**: Eliminating a small risk entirely beats reducing a large one. Apply: money-back guarantee, "we never sell your data", zero-knowledge encryption.
- **Ambiguity aversion (Ellsberg)**: Known odds beat unknown odds. Apply: exact price before checkout, exact dates, plain "what happens after the trial".
- **Dunning-Kruger effect**: Low skill inflates confidence. Apply: embed guidance invisibly (inline validation, auto-fixes); never gate basic flows behind "read the docs".
- **Curse of knowledge**: Experts cannot imagine not knowing. Apply: test copy with outsiders, label by user goals ("Send invoice") not internal architecture.
- **Hindsight bias**: Outcomes seem obvious afterward. Apply: compare post-mortems against logged forecasts.

## 3. Gestalt principles of visual perception

- **Proximity**: Near objects read as a group. Apply: label closer to its own input than to the previous one; whitespace often beats divider lines; space between cards greater than within cards.
- **Similarity**: Shared color, shape, size or orientation signals same category. Apply: all primary actions share one style, all danger actions share one look, so users learn the platform's interaction grammar.
- **Common region**: Elements inside one boundary form a cluster. Basis of the card pattern. Apply: cards, panels, background tints; put destructive actions outside the region holding safe ones.
- **Closure**: The mind completes incomplete shapes. Apply: minimal icons, partial borders, loading states, creative negative space. Watch: do not rely on closure for anything critical.
- **Continuity**: Elements on a line or smooth curve read as related. Apply: aligned table rows, linear wizards, swipe carousels, form alignment guiding order.
- **Prägnanz (good figure)**: Ambiguous stimuli are read in the simplest form. Apply: flat design, simple icons, generous negative space over skeuomorphic clutter; restructure charts that can be read two ways.
- **Uniform connectedness**: Connected elements (lines, arrows, shared bands) read as related, overriding proximity and similarity. Apply: workflow builders, multi-step trackers, data lineage graphs.
- **Figure-ground**: Elements read as focus or background. Apply: modal with dimmed backdrop, elevated active card, enough contrast, no busy backgrounds behind text.
- **Synchrony (common fate)**: Elements moving or changing together read as a group. Apply: shared animation timing for related cards; avoid accidental synchrony that implies false relationships.

## 4. Ergonomics, interaction physics and responsiveness

- **Fitts's Law (1954)**: Movement time MT = a + b * log2(1 + D/W); big, near targets are faster and less error-prone.
  - Desktop: context menus (distance near zero), screen edges and corners as "infinite" targets, adjacent related actions.
  - Mobile: screen edges do not help the thumb; primary actions go in the lower thumb zone.
- **Touch target sizing**: Finger pad is 10 to 14 mm. WCAG 2.5.8 AA minimum 24x24 CSS px (a legal floor, not ergonomic optimum). WCAG 2.5.5 AAA is 44x44 px, iOS 44x44 pt, Material 48x48 dp. Accuracy gains plateau past about 10 mm; oversized buttons waste space. Keep at least 8 dp between targets.
- **Thumb zone and peripheral vision**: Hoober field research found about 49% one-thumb use. Apply: primary actions and tab bars at the bottom, danger actions at the top, motion for periphery. Watch: universal thumb-zone diagrams are an overgeneralization (Section 17).
- **Spatial memory and gesture ergonomics**: Standard swipes, double taps and long presses become muscle memory. Apply: avoid requiring reach to extreme top corners.
- **Doherty threshold (1982 / 1988)**: Under about 400 ms feels instant and sustains flow. Apply: optimistic UI, skeleton screens, prefetching, progress indicators beyond that, transitions of at least 100 ms so change is noticed. Watch: never fake speed you cannot honor.
- **Nielsen's response time limits**: 0.1 s feels instant, 1 s keeps flow, 10 s is the attention limit. Apply: state beyond 1 s, progress plus async option ("we'll email you") beyond 10 s.
- **Optimistic UI**: Show success immediately, roll back on failure. Apply: likes, sends, Kanban moves. Watch: not for payments or irreversible actions.
- **Skeleton screens vs spinners**: Skeletons set expectations and feel shorter; spinners say only "wait". Apply: skeletons for content, spinners for sub-second actions, steps or percent for long jobs; skeleton must match final layout.
- **Progress bar psychology**: Smooth, accelerating bars feel fastest; stalls feel intolerable. Apply: never stick at 90%, show real steps and status text.
- **Operational transparency (Buell and Norton, 2011)**: Showing work being done reduces perceived wait and raises value. Apply: live processing logs, courier maps.
- **Maister's waiting principles**: Occupied time feels shorter, uncertain waits feel longer than known ones, unexplained longer than explained, unfair longer than fair, solo longer than group, valuable service tolerates longer waits. Apply: give something to do, state expected wait, show queue position, explain causes.
- **Duration neglect**: Retrospective judgment cares little about duration, much about peaks and ends. Apply: add a finish ritual to long processes.
- **Explained uncertainty**: Honest ranges with reasons feel shorter ("3 to 5 min, your file is large"). Proactively update when exceeded.
- **Gamified waits**: Tips, playful loaders, haptics convert dead time. Keep short waits clean.
- **Flow (Csikszentmihalyi, 1990)**: Deep engagement when challenge slightly exceeds skill with clear goals and immediate feedback. Apply: minimize interruptions, autosave, focus modes, instant feedback.
- **Tesler's Law (conservation of complexity)**: Irreducible complexity sits with user or system. Apply: absorb it in the system (smart defaults, automation, templates, advanced mode for those who want it). Watch: over-hiding controls in enterprise software harms usability and mental models.
- **Postel's Law (robustness)**: Be liberal in what you accept, conservative in what you send. Apply: accept phone numbers with any formatting, trim whitespace, validate on blur not keystroke. Watch: validate strictly at persistence boundaries.
- **Weber-Fechner (just noticeable difference)**: Perceived change is proportional to baseline. Apply: price increases framed absolute vs relative on purpose; meaningful UI differences must exceed the JND; background changes below it avoid redesign churn.

## 5. Attention and perception

- **Banner blindness**: Anything ad-like is ignored (Benway and Lane, 1998). Apply: critical messages inline in the task flow, system styling. Watch: styling marketing to look like system UI is a disguised ad.
- **Change blindness**: Unanimated or off-attention changes go unnoticed. Apply: animate state changes, highlight what changed ("3 new rows").
- **Inattentional blindness**: Visible stimuli are missed when attention is elsewhere (invisible gorilla). Apply: do not put critical warnings in task-focused zones; time interstitials to task completion.
- **Cocktail party effect**: Personally relevant cues break through. Apply: personalize notifications with the user's own data.
- **Preattentive processing (pop-out)**: Color, size, orientation, motion are processed in under 200 to 250 ms. Apply: one preattentive attribute per critical element; pop-out fails when many items vary.
- **Von Restorff (isolation) effect**: The distinct item is remembered. Apply: one accent CTA, one highlighted recommended tier. Watch: highlight everything and nothing stands out; do not highlight the expensive option while hiding the cheap one.
- **F-pattern**: Text-heavy pages are scanned top lines then down the left (NN/g, 2006). Apply: front-load headings and first two words, structured and bolded text.
- **Z-pattern and Gutenberg diagram**: Sparse pages scan in a Z; bottom-left is the dead zone, bottom-right the terminal focus. Apply: logo top-left, CTA top-right or bottom-right.
- **Visual hierarchy and visual weight**: Size, color, contrast, position and density rank importance. Apply: heading, body, meta; one highest-contrast primary CTA.
- **Mere exposure effect (Zajonc, 1968)**: Repetition increases liking. Apply: consistent brand elements, gradual rebrands. Watch: repeated notification patterns turn into noise.
- **Curiosity gap (Loewenstein, 1994)**: Curiosity comes from a gap between known and wanted knowledge. Apply: specific headlines. Watch: unclosed gaps (clickbait) destroy trust.
- **Information scent (Pirolli and Card, 1999)**: Users follow cues to judge target value. Apply: precise labels ("Billing and invoices", not "Account"), result counts, previews.
- **Saliency and iso-feature suppression**: In V1, repeated same-feature items suppress each other; a unique feature singleton escapes suppression. Apply: saliency is relative (red CTA on blue dashboard works; green on green fails). Top-left quadrant gets the most initial fixations on mobile.
- **Top-down guidance**: Goal-driven search uses mental templates combined with bottom-up saliency. Apply: align critical elements with salient cues that match what users look for.
- **Novelty**: Novel stimuli get prioritized processing, with effects dependent on age, timing and task. Apply: separate novelty that supports exploration or learning from endless novelty that just keeps the next item uncertain.

## 6. Memory, learning and experience evaluation

- **Peak-end rule (Kahneman and Fredrickson, 1993)**: Experiences are judged by the most intense moment and the end, not the average. Apply: engineer peak moments (first success, confetti) and endings (success screens, next-step guidance, warm cancellation); never end a session on an error; end-of-trial and end-of-session screens are high-ROI. Microinteractions (animation, haptics, sound) at peak and end.
- **Serial position effect**: First (primacy) and last (recency) items are remembered best (Murdock, 1962). Apply: critical items first and last in nav, pricing lists, onboarding; the middle is a dead zone.
- **Zeigarnik effect (1927)**: Unfinished tasks are remembered and create tension. Apply: progress bars, checklists, "60% complete", resume where you left off, badges. Watch: a 2025 meta-analysis found the memory advantage is hard to reproduce; the tendency to resume interrupted tasks is more reliable; a 2026 meta-analysis links unfinished tasks to off-hours rumination.
- **Aesthetic-usability effect (Kurosu and Kashimura, 1995)**: Attractive designs are perceived as more usable and forgiven for friction. Apply: invest in polish early; visual quality builds trust. Watch: polish can mask real failures, so measure task success separately.
- **Forgetting curve (Ebbinghaus, 1885)**: Memory decays fast without reinforcement. Apply: re-teach rare features contextually, spaced re-engagement.
- **Spacing effect**: Spaced repetition beats cramming. Apply: scheduled review in learning apps, drip feature education over weeks.
- **Testing effect (Roediger and Karpicke, 2006)**: Retrieval beats re-reading. Apply: try-it-yourself steps, micro-challenges.
- **Verbatim effect**: People remember gist, not wording. Apply: the headline must carry the message; re-show amounts and dates at the moment of action.
- **Picture superiority effect**: Images are remembered better than words. Apply: diagrams, screenshots, avatars.
- **Dual coding (Paivio, 1971)**: Verbal plus visual channels strengthen encoding. Apply: pair concepts with icons or diagrams; complement, do not duplicate.
- **Google effect (digital amnesia)**: People forget what is easily retrievable. Apply: searchable history, receipts archive, recently viewed.
- **Misinformation effect (Loftus)**: Later info distorts memory of events. Apply: confirmation dialogs state neutrally what will happen.
- **Scaffolding (Vygotsky)**: Support that gradually withdraws. Apply: in-context checklists, tooltips that disappear after use.
- **Generation effect (Slamecka and Graf, 1978)**: Self-generated answers are remembered better. Apply: have users type their goal, name their own projects.
- **Spatial and procedural memory**: see gesture ergonomics in Section 4.

## 7. Usability heuristics and mental models

- **Jakob's Law**: Users spend most time on other products and expect yours to work the same. Apply: follow conventions (cart icon, hamburger menu, top-left logo to home, bottom tab bar on iOS); innovate on differentiating flows only. Violations push users from System 1 to System 2 and raise abandonment.
- **Mental models**: Compressed representations of how systems work from past experience. Apply: align architecture with them.
- **Nielsen's 10 heuristics**:
  1. Visibility of system status (real progress, not a static spinner).
  2. Match between system and real world (familiar language, trash can for delete).
  3. User control and freedom (undo, persistent undo toast after destructive actions).
  4. Consistency and standards (same words, icons and colors mean the same thing).
  5. Error prevention (constraints, defaults, disable invalid submit).
  6. Recognition rather than recall.
  7. Flexibility and efficiency (accelerators like keyboard shortcuts for experts).
  8. Aesthetic and minimalist design.
  9. Help users recognize, diagnose and recover from errors (plain language, precise problem, a solution).
  10. Help and documentation (searchable, contextual).

## 8. Motivation, habit and engagement

- **Fogg Behavior Model (B = MAP)**: Behavior needs Motivation, Ability and a Prompt together; motivation and ability compensate each other. Apply: diagnose the missing element; failed activation is usually an Ability failure (cut steps, use SSO, prepopulated templates); prompts work best after motivation peaks.
  - **Three motivators**: Sensation (pleasure/pain), Anticipation (hope/fear), Belonging (acceptance/rejection).
  - **Six simplicity factors**: time, money, physical effort, brain cycles, social deviance, non-routine. Fix the cheapest first.
  - **Prompt types**: Spark (low motivation, adds motivation), Facilitator (high motivation, low ability, simplify), Signal (high both, reminder).
- **Hook model (Eyal)**: Trigger, Action, Variable Reward, Investment. External triggers become internal (boredom, loneliness, anxiety). Investment improves the next cycle and loads the next trigger. Watch: Eyal's own test is whether the habit improves the user's life; otherwise it is exploitation.
- **Habit loop (cue, routine, reward; Duhigg, Wood and Neal)**: Stable context plus consistent reward builds automaticity. Apply: anchor to existing routines. Evidence: habit formation time varies widely and is often months, not a fixed 21 or 66 days.
- **COM-B (Capability, Opportunity, Motivation)**: Diagnose whether users lack capability, opportunity or motivation; common in health, fitness and enterprise SaaS.
- **PSYCH framework**: Personality, Social influence, Yes (rewards), Context, Habits.
- **Operant conditioning (Skinner)**: Four consequence types in UI.
  - Positive reinforcement: likes, badges, level-ups.
  - Negative reinforcement: clearing a stressful badge, upgrading to remove ads.
  - Positive punishment: ban warning, login lockout.
  - Negative punishment: losing a streak, trial expiry, reduced visibility (shadowbanning).
- **Schedules of reinforcement**: Continuous reinforcement teaches fast but extinguishes fast. Variable ratio (pull-to-refresh, infinite feed, loot boxes) resists extinction; variable interval (random notifications) drives steady checking. Watch: "variable rewards cause addiction" is an overstatement (Section 17).
- **Variable rewards (Eyal)**: Tribe (social), hunt (search or collection), self (mastery or novelty). Fixed rewards habituate within days.
- **Dopamine reward prediction error**: Dopamine signals unexpected better or worse outcomes and drives seeking, not just pleasure. Unexpected rewards spike it; missing predicted rewards drop it below baseline. Watch: "dopamine equals pleasure" is a popular misreading.
- **Investment and stored value**: Each session should deepen stored data, history, integrations or reputation. Stored value, not lock-in, is durable retention.
- **Self-Determination Theory (Deci and Ryan)**: Autonomy (real choice, customization), Competence (progressive challenge, visible growth), Relatedness (teams, sharing, community). Evidence: small but significant behavioral effects in a meta-analysis of 65 SDT interventions.
- **Overjustification effect (Lepper, Greene and Nisbett, 1973)**: Extrinsic rewards can erode intrinsic motivation. Apply: use points where a spark is needed and taper them; praise mastery over activity.
- **Progress principle (Amabile and Kramer, 2011)**: Small visible progress in meaningful work is the strongest daily motivator. Apply: weekly recaps, "3 tasks shipped today", autosave and undo to prevent setbacks.
- **Goal-gradient effect (Hull, 1932; Kivetz et al., 2006)**: Effort accelerates near a goal. Apply: "7 of 10 done", quick wins first, "X% to free shipping".
- **Endowed progress effect (Nunes and Dreze, 2006)**: Credited head-start raises completion (pre-stamped car-wash cards 34% vs 19%). Apply: onboarding checklist starting with items already done, prefilled profiles from imports. Watch: progress must be truthful; fabricated progress is deception.
- **Streaks and loss-framed momentum (Duolingo)**: The streak becomes an asset to protect. Apply: streak freezes and repair, milestone celebration. Watch: guilt-based streak shaming; streak loss can be coercive.
- **Gamification (points, badges, leaderboards)**: Effects are small and depend on the specific element. Apply: cooperative or past-self comparisons, badges tied to competence, meaningful points. Watch: bottom-of-leaderboard demotivation; badge inflation; not a guaranteed effect.
- **Customization and ownership**: Early customization builds investment and autonomy. Apply: ship good defaults so customization is optional.
- **Fresh start effect (Dai, Milkman and Riis, 2014)**: Temporal landmarks boost aspirational behavior. Apply: Monday, new year, birthday campaigns; year-in-review.
- **Commitment devices and deadlines (Ariely and Wertenbroch, 2002)**: Self-chosen precommitment raises completion. Apply: user-set deadlines, stakes, email-my-future-self.
- **Temptation bundling (Milkman, Minson and Volpp, 2014)**: Pair a should with a want.
- **Effort heuristic (Kruger et al., 2004)**: More apparent effort means more perceived value. Apply: visible processing steps, "analyzing your 340 data points".
- **Anticipation**: Waiting for a reward activates reward circuitry. Apply: waitlist positions, scheduled weekly reports, visible feature progress.
- **Intrinsic vs extrinsic framing of engagement**: Distinguish engagement, habitual use, problematic use and clinical addiction. WHO ICD-11 recognizes gaming disorder only; "smartphone addiction" and "social-media addiction" are less standardized.

## 9. Pricing and economic psychology

- **Mental accounting (Thaler)**: People keep money in buckets. Apply: price in the buyer's budget unit ("$12/user/month, billed annually").
- **Zero-price effect (Shampanier, Mazar and Ariely, 2007)**: Free is a different regime from cheap. Apply: real free tiers for network products, upgrade triggers from usage not nagging.
- **Partitioned and drip pricing (Morwitz et al., 1998)**: Late mandatory fees raise drop-off and complaints. Apply: show all-in price early. Regulatory: active enforcement (FTC junk fees, EU price rules).
- **Bundling**: Hides unit prices and raises perceived value.
- **Currency confusion**: Virtual currencies (gems, coins) hide real spend and lower purchase friction. Watch: dark pattern in in-app economies.
- **Pricing page psychology**: Anchor, decoy and compromise effects combined with Von Restorff highlight on the middle tier drive ARPU.
- **Nudge theory (Thaler and Sunstein)**: Every default, order and frame is a nudge. Audit and set them in the user's interest. Nudges guide toward good outcomes; sludge adds friction against the user's interest.
- **Choice architecture and friction design**: Add friction where errors are expensive (delete, transfers, with undo), remove it where value is clear (signup, upgrade). Friction asymmetry is the core skill.

## 10. Persuasion and influence (Cialdini plus)

- **Reciprocity**: Give valuable things first (calculators, templates, audits, surprise upgrades).
- **Commitment and consistency**: Small, active, self-written commitments first; reference them at decision points.
- **Social proof**: Copy similar others, especially under uncertainty or high load. Apply: specific logos, counts, testimonials with names and roles ("3,200 dental clinics" beats "thousands"). Evidence: a meta-analysis of 250 effect sizes found social norms influence consumer behavior with moderators. Watch: fabricated counts are deception.
- **Authority**: Credentials, SOC 2, expert endorsements, cited ROI. Must be verifiable. A 2026 meta-analysis found only a small average effect from credible sources, so treat as conditional.
- **Liking**: Similarity, compliments, familiarity, politeness in microcopy.
- **Scarcity**: Scarce means valuable. A meta-analysis of 131 studies found demand, supply and time scarcity differ by context. Apply: only real seat limits, real deadlines, and explain why. Watch: resetting countdowns and fake "only 2 left" are dark patterns.
- **Unity (Cialdini's 7th principle)**: Shared identity is stronger than liking ("built for indie devs, by indie devs").
- **Foot-in-the-door (Freedman and Fraser, 1966)**: Small compliance leads to larger. Each step needs standalone value.
- **Door-in-the-face (Cialdini, 1975)**: A refused large ask raises compliance with a smaller one. Use sparingly.
- **Fear appeals (EPPM, Witte, 1992)**: Fear works only with high perceived efficacy; give a clear doable action.
- **Authority bias and social-proof under uncertainty**: see above; users lean on others when expertise is lacking.

## 11. Social and group psychology

- **Conformity (Asch, 1951)**: People align with the group. Apply: visible norms, pinned rules. Watch: conformity pressure suppressing legitimate dissent.
- **Social comparison theory (Festinger, 1954)**: Upward comparison can motivate or discourage; downward comparison gives temporary esteem. Apply: compare to attainable targets (past self, cohort, next rank). Watch: unwinnable benchmarking, curated feeds, mental-health costs.
- **FOMO (Przybylski et al., 2013)**: Anxiety about missing out drives checking. A 2024 meta-analysis (252,337 participants) found moderate associations with problematic social network use, mostly correlational. Watch: manufactured FOMO ("X just bought!").
- **Belonging and relatedness**: Roles, rituals, mutual-aid visibility; onboard into community before asking for contributions.
- **Collaboration and shared value**: Invite inside the value moment, show presence, graceful view-only landing for non-users.
- **Social feedback as reward**: Likes activate reward-related regions (adolescent fMRI studies). Relevant to counters, leaderboards, adolescent design.
- **Social desirability bias (research)**: Participants report what sounds good. Ask about past behavior, triangulate with analytics.
- **Personalization / personality fit**: Introverts may prefer solo curated experiences and desaturated, harmonious visuals; extroverts community and stimulation (PSYCH, color research).

## 12. Emotion, aesthetics and delight

- **Norman's three levels of emotional design**: Visceral (look), behavioral (use), reflective (meaning and identity). Products with only visceral appeal churn after week one.
- **Microinteractions and delight**: Purposeful animation, haptics, one signature moment per core flow. Never add latency to critical paths.
- **Voice and humor**: Playful in empty states and success; strictly clear in errors, billing, security.
- **Emotional contagion**: Tone transfers through copy, cues and others' behavior.
- **Peak-moment design (Heath and Heath, 2017)**: Build moments of elevation, insight, pride, connection.
- **Cognitive dissonance and post-purchase reassurance (Festinger, 1957)**: Re-sell the decision after purchase to prevent refund and churn.
- **Emotionally intelligent interfaces (2026)**: Systems read scroll velocity, tap pressure, hesitation to adapt tone, load and layout. Watch: the same sensing can exploit high-impulsivity states for monetization.

## 13. Trust, credibility and error handling

- **Stanford Web Credibility Guidelines**: Real-world feel, ease of use, expertise, polish. Typos, broken links and hype hurt fastest. Audit: visible contact info, real photos, dates, no overclaims.
- **Trust seals and checkout validation**: One relevant seal near payment, reviews near the CTA. Too many or irrelevant badges can depress trust.
- **Transparency as differentiator**: Show "why" behind recommendations, open pricing, public changelogs, admit outages with cause and fix.
- **Privacy control and the privacy paradox**: Users say they care, act otherwise, then overcorrect after breaches. Apply: contextual permission asks, plain-language explanations, granular toggles, easy export and deletion.
- **Error prevention (poka-yoke)**: Constrain inputs, confirm destructive actions by consequence ("Deletes 3 projects"), undo everywhere, disable invalid options.
- **Blame-free error messages**: What happened, why, what to do now, an escape. Never blame, jargon or dead ends.
- **Service recovery paradox**: A well-handled failure can raise loyalty (limits: works once, not for catastrophic failures).
- **Consistency builds trust**: Same terms everywhere, changelogs and deprecation notices when patterns change.
- **Third-party validation**: Dated audits ("SOC 2 Type II, 2025"), real rating distributions, review widgets.
- **Perceived security**: Mask sensitive data, show session and device lists, last login, explicit state. Signals must match real protections.
- **Progressive permission**: Ask at the moment of need with a rationale; make denial safe and revocable.

## 14. AI-era human-AI interaction

- **Shift from command to intent**: Users specify outcomes, AI chooses the path. Lowers effort but reduces felt control.
- **Automation bias (Skitka and Mosier, 1996)**: Over-trusting automated output. Apply: sources, confidence, confirmation for consequential actions, spot-check prompts. Watch: the core liability of 2024 to 2026 AI features is confident, fluent, wrong output.
- **Automation complacency**: Reliable systems erode vigilance. Apply: vary interaction, meaningful human checkpoints.
- **Algorithm aversion (Dietvorst et al., 2015)**: Confidence in algorithms drops faster than in humans after the same error. Apply: honest accuracy framing, one-tap recovery.
- **Algorithm appreciation (Logg et al., 2019)**: Machine-labeled advice can be rated higher, depending on domain. Calibrate disclosure per feature.
- **Trust calibration (Lee and See, 2004)**: Aim for appropriate reliance, not maximum trust. Communicate capability boundaries, show uncertainty, make rejecting and editing easy.
- **ELIZA effect (Weizenbaum, 1966)**: People attribute understanding to simple conversational programs. Never simulate empathy you cannot honor; route to humans for crisis, legal, medical.
- **Anthropomorphism (Epley et al., 2007)**: Persona level should match accountability.
- **Uncanny valley (Mori, 1970)**: Stay stylized or clearly artificial; disclose bot identity early.
- **AI disclosure effects (Luo et al., 2019)**: Disclose plainly, pair with capability statements ("drafts in seconds, verify before sending").
- **Explainability (XAI) and four-lens framework**: Cover model behavior, internal mechanisms, user trust and end-to-end auditability. UI needs: sources and confidence, one-line "why" per output, behavior-level (not model-internal) explanations.
- **Uncertainty communication**: LLM fluency is not evidence. Flag estimates, offer alternatives, ask for context, hedged copy, "low confidence" tags.
- **Human approval before action**: Un-skippable confirmation for irreversible or consequential agent actions.
- **Context and memory controls**: Show what history the AI uses; let users inspect, clear and modify it.
- **Streaming and perceived intelligence**: Stream by default, cancelable "thinking" state, never block the UI, stop button.
- **Co-creation and authorship**: Edited drafts are valued more than accepted ones; keep human edits visible, let users claim authorship.
- **Conversational UX**: Fast first token, acknowledge before answering, at most one clarifying question, resumable threads, explain silence over about 10 s.
- **Amershi et al. 18 Human-AI guidelines**: Set expectations, contextual help, easy dismissal and correction, graceful handling of uncertainty, explanations, adaptation, notify on material changes.
- **AI companion dark patterns (CDT)**: Anthropomorphism, synthetic empathy and simulated bonding used to extract data and foster dependency.
- **Spatial UI, WebXR and Haptics 2.0**: Multisensory feedback intensifies conditioning loops; manipulation moves into physical environments.
- **Regulation**: EU AI Act (in force Aug 2024; manipulative and subliminal AI prohibitions applicable Feb 2025), FTC AI-overclaim enforcement ("Operation AI Comply", 2024).

## 15. Color psychology and color systems

- **Color-in-context theory (Elliot and Maier)**: Color effects depend on context and combine biological tendencies with learned associations. Red approaches in romance contexts but avoids in achievement contexts (e.g., financial dashboards). The Ecological Valence Theory ties preference to affect toward color-associated objects.
- **Evidence status**: A systematic review (132 articles, 42,266 participants, 64 countries) found recurring associations: red high-arousal positive and negative; yellow and orange positive high-arousal; blue, green, blue-green, white positive low-arousal; gray negative low-arousal; black negative high-arousal. These are associations, not guaranteed emotion or behavior changes. A 30-nation study (4,598 participants) found shared associations plus variation by language and geography.
- **Hue, lightness and saturation**: Lightness and saturation often matter as much as hue. Excess saturation can reduce perceived trust and usability.
- **RGB vs RYB**: Screens mix RGB; pigments RYB.
- **Personality and saturation tolerance**: Introverts lean toward desaturated harmony; extroverts toward saturated stimulation.
- **Saliency and the unique color singleton**: see Section 5. Color salience is relative.
- **60-30-10 rule**: 60% dominant neutral, 30% secondary, 10% accent reserved for CTAs and critical highlights.
- **Harmonies**: Monochromatic, analogous (unity, familiarity), complementary (max contrast for key features), split-complementary, triadic, tetradic, neutral plus accent.
- **Semantic mapping**:
  - Red: urgency, danger, error, loss; destructive actions, sale, notification badges. Overuse causes anxiety and fatigue; in Chinese contexts red means luck and gain.
  - Blue: trust, calm, stability; primary actions, finance, health. Can feel cold in dating or lifestyle apps.
  - Green: success, growth, go; confirmations, positive portfolio. Loses salience in green-heavy UIs.
  - Yellow: optimism, non-critical attention; warnings. Poor contrast on light backgrounds; large areas fatigue.
  - Orange: energy, action, impulse; buy buttons, upgrades, streaks. Needs isolation to work.
  - Purple: creativity, luxury; needs consistent teaching since conventions are weaker.
  - Black: focus, premium; pure black plus white text causes halation, prefer dark grey.
  - White: clarity, space; needs grouping and hierarchy.
  - Others covered in source summary: teal, cyan, indigo, magenta, pink, brown, beige, cream, gray, metallic gold and silver (details not in the uploaded text).
- **Button hierarchy by color**: Strong accent for primary (Save), neutral for secondary (Cancel), danger red for destructive (Delete).
- **Red notification badge as cue**: Danger and urgency coding bypasses executive function; the sight of the dot can trigger anticipatory dopamine.
- **Chromatic gamification**: Duolingo streak flame turns grey on loss; Tinder's vivid palette and match feedback.
- **Retail trading red and green (Robinhood)**: Green validates, red spikes arousal and encourages short-term trading; confetti links trades to game rewards.
- **Losses disguised as wins (LDWs)**: Multiline slots celebrate a net loss with light and sound. Monash studies (n=940) show overestimated wins and body responses as if won.
- **Color accessibility (WCAG 2.2)**: Color must not be the sole carrier of meaning; text 4.5:1, large text 3:1, non-text UI 3:1. Pair color with icons, text, patterns.
- **Color vision deficiency**: Red-green is the most common form; avoid red/green-only status. Prevalence: about 8% of men (document 7), about 2.59% overall in a 2025 meta-analysis (document 5).
- **APCA**: Perceptual lightness contrast (Lc) accounting for font size, weight and polarity. Example thresholds: Lc 60 regular text and active inputs, 45 large text and key icons, 30 placeholders and focus rings, 15 disabled and structural. Table (size x weight): 14px Lc 100/100/90/75, 16px 90/75/70/60, 18px 75/70/60/55, 24px 60/55/50/45, 36px 45/43/40/38 (Regular/Medium/Semi-bold/Bold). Status: see Section 17.
- **Dark mode**: Use dark grey over pure black; account for polarity in contrast checks.
- **OKLCH and CSS Color 4**: oklab() and oklch() give perceptually regular token scales (Candidate Recommendation Draft 2026); still test final pairs.
- **Cultural variation**: No universal color dictionary.
- **CTA color myths**: No single conversion-best button color; isolation and contrast matter.
- **Semantic token architecture and design-system workflow**: Define roles (background, surface, text, primary, accent, success, warning, error) as tokens with light and dark variants.
- **Humane color interventions**: Replace red badges with grey or pale blue, grayscale modes to lower saliency, equal visual weight on choices, user-customized cues, batched notifications.
- **Visual engagement is not clinical addiction**: Color effects support attention, association and aesthetic judgment, not chemically caused addiction.

## 16. Dark patterns, ethics, regulation and ethical retention

- **Dark pattern taxonomy** (Brignull 2010; Gray et al. families: nagging, obstruction, sneaking, interface interference, forced action):
  - Roach motel / hard to cancel / forced continuity.
  - Sneak into basket, hidden costs, drip pricing.
  - Hidden subscription.
  - Preselection (harmful defaults).
  - Visual interference and misdirection (salient preferred button, low-contrast decline).
  - Confirmshaming.
  - Trick wording and trick questions (double negatives, misleading checkbox color).
  - Fake social proof.
  - Fake urgency and scarcity.
  - Nagging.
  - Forced action.
  - Comparison prevention.
  - Disguised ads.
  - Privacy Zuckering.
  - Bait and switch.
  - Currency confusion.
  - AI-specific: fake personas, fabricated AI urgency, overclaimed accuracy, undisclosed synthetic humans, companion emotional manipulation.
- **Vulnerability each exploits**: sunk cost, present bias, status quo bias, inattentional blindness, cognitive ease, herd mentality, loss aversion, cognitive fatigue, linguistic complexity, information overload.
- **Hyper-engaging dark patterns (HEDPs) / addictive design**: Platform-wide "habit-forming hypernudges" such as infinite scroll, autoplay, gamification loops outside gaming, interrupting notifications. Linked to anxiety, sleep loss, shorter attention.
- **Evidence on repeat-use mechanics**: Autoplay has clear causal evidence (2025 study, 76 Netflix users: disabling autoplay cut daily viewing and session length). Infinite scroll evidence is smaller; added friction can interrupt scrolling, varying by self-regulation. Notifications attract attention and interrupt tasks, but disabling them for a week did not reduce screen time in a 2024 trial (it did reduce perceived habit strength and raised FoMO). Recommenders cut search cost but can lower transparency and narrow exposure; diversity is a mitigation.
- **Dark pattern harm evidence**: A 2026 "transaction test" found dark patterns raised choice inconsistency by about 6 to 12 percentage points; a 2024 review of 642 subscription sites and apps found about 76% had at least one possible dark pattern, about 67% multiple (possible, not all proven unlawful).
- **Regulation snapshot**:
  - EU DSA (Art. 25 bans dark patterns on platforms; July 2025 minors guidelines cover addictive behavior; Feb 2026 preliminary finding vs TikTok on addictive design, not a final determination).
  - Proposed EU Digital Fairness Act (reported in source): bans on fake urgency and manipulative defaults, estimated €13.7 billion annual consumer savings, push to treat HEDPs under the Unfair Commercial Practices Directive, limits on personalized ads and dynamic pricing for minors.
  - FTC (ROSCA, click-to-cancel, junk fees, Epic Games settlement 2022 with $245M+ refunds); California CPRA (dark patterns do not constitute consent); UK ICO Age Appropriate Design (no nudging children toward lower privacy, impulsive purchases or excess use).
- **Intentional friction**: Deliberate pauses (confirmation tap before a large transfer, spatial distancing) force System 2 on high-stakes decisions.
- **Digital wellbeing and humane design**: Calmer defaults, pause points in feeds, screen-time nudges, internal audits for addictive loops, fair patterns as countermeasures, REBEL framework (e.g., commitment devices to overcome hyperbolic discounting for the user's own goals), Center for Humane Technology "Time Well Spent".
- **Ethical retention loop**: Need, useful action, visible outcome, optional reminder, return when the need recurs.
- **Ethical retention rules**: Preserve real stopping cues, easy notification control, exit and cancellation at least as easy as entry (symmetric design), truthful progress, no false scarcity or false social proof, recoverable streaks, explained recommendations, quiet hours, non-personalized alternatives, monitor for involuntary use.
- **Metrics beyond DAU and session length**: Goal completion, time-to-value, retained skill, post-session satisfaction, regret, failed-stop attempts, late-night minutes, repeated reopenings, notification muting, time after goal completion, self-reported control (a design inference, not a validated universal set).
- **Designer ethics checklist**: Mirror test (explain it to the user on stage), symmetry test, informed test, grandparent test, regulator test, honest defaults, scarcity and urgency.
- **Rule of thumb**: Persuasion with truthful premises is design; the same mechanics on fabricated premises is a dark pattern.

## 17. Evidence cautions, myths and source conflicts

Myth checks and caveats:
- Miller's 7 plus or minus 2 is about memory, not a menu-size rule; Cowan puts capacity near 4 chunks.
- The 3-click rule has no empirical foundation as a universal limit.
- The "8-second attention span" is not a validated fixed human attention span.
- Choice overload is not universal; effects are context dependent.
- Loss aversion is not an immutable 2x law; it is a heterogeneous, context-dependent effect (mean near 1.96 in one meta-analysis).
- Framing effects are real but their size depends on task and domain.
- Aesthetics do not equal usability; polish can hide failures.
- Universal thumb-zone diagrams overgeneralize.
- Gamification effects are not guaranteed and depend on the element.
- AI explanations do not automatically produce trust or calibrated reliance.
- "Dopamine equals pleasure" and "variable rewards hack the brain" are oversimplifications; variable schedules have boundary conditions.
- Zeigarnik memory advantage is weakly replicated; resumption tendency is more reliable.
- Habit formation has no fixed 21 or 66 day rule.
- Notifications alone do not cause tech addiction.
- Priming findings often fail replication.
- Scarcity, authority and social proof effects are context dependent.
- No hue has a guaranteed universal emotional effect or best CTA color.
- Engagement, habit, problematic use and clinical addiction are different things.
- WCAG does not cover every cognitive and learning-disability need.
- Cognitive-digital interaction research is heterogeneous; a 2026 review argues attention control often explains performance better than simple working-memory capacity.

Source conflicts to resolve in your own use:
- **APCA status**: Document 7 says the industry has widely moved to APCA; document 5 says that as of 15 Nov 2026 APCA is not a normative replacement for WCAG 2.2 and WCAG 3's contrast algorithm is undecided. This list follows document 5 for conformance claims, and uses APCA as a supplementary check only.
- **Color vision deficiency prevalence**: about 8% of men (document 7) vs about 2.59% overall (document 5, different population base). Both can be true.
- **Working memory number**: 7 plus or minus 2 (document 1) vs about 4 (documents 5, 6 and Cowan). Design for the stricter number.
- **Loss aversion size**: "about twice" (documents 1, 6, 7) vs about 1.96 with heterogeneity (document 4).
- **Document 3 claims** (global "public health crisis", 5 to 7 hours online daily, proposed Digital Fairness Act details, treating dopamine and addiction analogies as settled) are stated more strongly than documents 2 and 4 support; treat as reported, not settled.
- **Document 1 Parkinson's Law** is used to compress perceived time; document 6 uses it for time-boxing. Both are included in Section 2.

## 18. Applied playbooks (document 6)

- **Pricing page**: High anchor, 3 tiers, recommended middle, decoy, annual default with savings framing, social proof under plans, money-back line, full price visibility, one accent CTA. Tripwires: fake "was" prices, hidden seat math, comparison prevention.
- **Onboarding**: B=MAP audit, one goal question, personalized empty state, honest endowed progress (about 20%), teach one feature by doing, first value in session one, celebrate completion, skip paths. Tripwires: forced tours, email gate before value.
- **Paywall and trial end**: Show trial artifacts as the user's property, loss-frame concrete features with exact date, offer downgrade before cancel, one-screen respectful cancel flow. Tripwires: cancellation mazes, guilt copy, silent auto-charge.
- **Notifications and re-engagement**: Routine-anchored cue, valuable variable payload, personal data in message, progressive permission, digest and quiet hours, retire notifications whose open rate flatlines. Tripwires: fake-activity notifications, streak guilt without freezes.
- **Search and results**: Information scent, suggestions, result counts, progressive filters, chunked cards, empty state that teaches a better query, blame-free "did you mean".
- **AI feature surfaces**: Disclosure up front, streaming with cancel, uncertainty signals, one-line "why", verification affordances, human escalation for high stakes, capability examples in empty state, no overclaiming.
- **Forms and settings**: Defaults carry decisions, chunk into steps, validate on blur and forgive format, recognition aids, dangerous settings opt-in with plain consequences, saved progress.
- **Errors and empty states**: Blame-free message plus one action, empty states as teachers, skeleton first, recovery over-investment, end every session with a clear next step.
