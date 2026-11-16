# The Designer's Complete Reference of Psychology Principles (through 2026)

**For Web Apps, SaaS Products & Mobile Apps** — 180+ principles, laws, biases, and effects, organized by design domain, with a concrete application note for each and a "watch out" where the principle overlaps with unethical (dark-pattern) use.

**Scope:** cognitive psychology, perception/Gestalt, memory, behavioral economics, motivation & habit design, persuasion & trust, time perception, social psychology, AI-era psychology (2023–2026), and design ethics.

---

## How to use this file

1. **Diagnose first.** Every usability or engagement problem maps to a human limitation: attention (§3), memory (§4), decision-making (§5–6), motivation (§7), emotion (§8), trust (§10), patience (§11).
2. **Apply, don't decorate.** Each entry has an **Apply** line with concrete web/SaaS/mobile patterns.
3. **Respect the Watch-out lines.** Many persuasion principles have a dark-pattern version; §14 covers the ethics and current regulation (FTC, EU DSA, EU AI Act).
4. **Combine, don't stack.** Real products win by combining 3–5 principles coherently (see §15 Playbooks), not by triggering every bias on one screen.

**TL;DR — the 20 highest-leverage principles for product designers:**
Hick's Law · Fitts's Law · Jakob's Law · Miller's Law / Working Memory · Cognitive Load · Progressive Disclosure · Recognition over Recall · Fitts + Thumb Zone · Doherty Threshold (perceived speed) · Aesthetic-Usability Effect · Peak-End Rule · Serial Position · Goal-Gradient + Endowed Progress · Loss Aversion · Defaults / Status Quo · Social Proof · Anchoring & Framing · Scarcity (honest) · Fogg B=MAP · Hooked Model · Trust Calibration (AI).

---

## Table of contents

- §1 Foundational UX Laws (the "Laws of UX" canon)
- §2 Gestalt Principles of Visual Perception
- §3 Attention & Perception
- §4 Memory & Learning
- §5 Decision-Making: Heuristics & Cognitive Biases
- §6 Behavioral Economics & Choice Architecture
- §7 Motivation, Habits & Engagement
- §8 Emotion, Aesthetics & Delight
- §9 Persuasion & Influence (Cialdini +)
- §10 Trust, Credibility & Error Handling
- §11 Time, Waiting & Perceived Performance
- §12 Social & Group Psychology
- §13 AI-Era Psychology (2023–2026)
- §14 Ethics: Dark Patterns & Deceptive Design
- §15 Applied Playbooks (pricing, onboarding, paywall, AI features…)
- §16 Master Index
- §17 Sources & Further Reading

---

## §1 Foundational UX Laws (the "Laws of UX" canon)

The research-backed canon popularized by Jon Yablonski's *Laws of UX* (lawsofux.com) and 70+ years of HCI research. These are the first principles every product designer should be able to recite.

### 1.1 Aesthetic-Usability Effect
- **What:** Users perceive attractive interfaces as *more usable* than they actually are, and tolerate minor flaws in them *(Kurosu & Kashimura, 1995)*.
- **Apply:** Invest early in visual polish, consistent typography, and brand-aligned aesthetics — beauty buys forgiveness for friction and boosts first impressions in trials and app-store screenshots.
- **Watch:** Polish can mask real usability failures; keep measuring task success separately from satisfaction.

### 1.2 Choice Overload (Paradox of Choice)
- **What:** More options raise decision effort and lower conversion and satisfaction *(Iyengar & Lepper's jam study, 2000: 24 jams → 3% purchase, 6 jams → 30%)*.
- **Apply:** Cap visible choices (3 pricing tiers, 6–9 nav items), use "recommended/Popular" defaults, progressive filters, and smart defaults instead of exhaustive lists.
- **Watch:** False scarcity of options ("only 3 left!") crosses into dark-pattern territory (§14).

### 1.3 Chunking
- **What:** People hold information better when it is grouped into meaningful chunks *(rooted in Miller's 7±2)*.
- **Apply:** Break long forms into steps; group settings into categories; format phone numbers, card numbers, and dates; chunk onboarding into 3–4 steps.

### 1.4 Cognitive Load
- **What:** Working memory has limited capacity; every element that must be parsed competes for it *(Sweller's Cognitive Load Theory, 1988)*.
- **Apply:** One primary action per screen; hide advanced options; use defaults; cut jargon; defer configuration to context ("ask at the moment of need").
- **Watch:** "Load" includes visual noise, dense text, and decision count — not just clicks.

### 1.5 Doherty Threshold
- **What:** Productivity soars when system response is under ~400 ms, so neither human nor computer waits on the other *(Doherty & Sørensen, IBM, 1988)*.
- **Apply:** Sub-400 ms perceived response via optimistic UI, skeleton screens, prefetching; use progress indicators beyond that; animate transitions ≥100 ms so changes are noticed.
- **Watch:** Never fake speed you can't honor — broken expectations damage trust more than honest load time.

### 1.6 Fitts's Law
- **What:** Time to acquire a target is a function of distance to and size of the target *(Fitts, 1954)*.
- **Apply:** Large touch targets (≥44×44 pt iOS, ≥48×48 dp Android), place primary actions within the thumb zone (bottom of mobile screens), make edges/corners "infinitely large" targets, keep related actions adjacent.

### 1.7 Flow
- **What:** Deep engagement occurs when challenge slightly exceeds skill, with clear goals and immediate feedback *(Csikszentmihalyi, 1990)*.
- **Apply:** For creation/coding/analytics tools: minimize interruptions, autosave, hide chrome in focus modes, instant feedback on every action, escape hatches from interruptions ("don't ask now").

### 1.8 Goal-Gradient Effect
- **What:** Effort accelerates as people approach a goal *(Hull, 1932; loyalty-card field study: Kivetz, Urminsky & Zheng, 2006)*.
- **Apply:** Show progress ("7 of 10 done"), place progress bars so the first segment fills fastest, sort onboarding so quick wins come first, show "X% to free shipping."

### 1.9 Hick's Law (Hick-Hyman Law)
- **What:** Decision time increases logarithmically with the number and complexity of choices *(Hick & Hyman, 1952)*.
- **Apply:** Reduce options per screen; progressive disclosure; smart search over mega-menus; break long processes into screens with one decision each.
- **Watch:** Cutting options entirely can violate Postel's Law (1.16) — power users need depth somewhere.

### 1.10 Jakob's Law
- **What:** Users spend most of their time on *other* sites and apps, so they prefer your product to work the same way as the ones they already know *(Jakob Nielsen)*.
- **Apply:** Follow platform conventions (bottom tab bar on iOS, hamburger/drawer patterns, cart top-right, standard iconography); innovate on the differentiating flows, not the basics.

### 1.11 Miller's Law
- **What:** The average person can hold ~7±2 items in working memory *(Miller, 1956)* — modern research revises this down to about 4 *(Cowan, 2001)*.
- **Apply:** Limit menus to ~5–7 top-level items; chunk longer lists; never require users to remember info from one screen to another (keep context visible).

### 1.12 Occam's Razor
- **What:** Among competing explanations, the simplest should be selected; by extension, avoid unnecessary complexity in solutions.
- **Apply:** Remove steps, fields, and options that don't earn their place; every element must justify the attention it costs.

### 1.13 Pareto Principle (80/20 Rule)
- **What:** ~80% of effects come from ~20% of causes; in software, most users use a small fraction of features.
- **Apply:** Surface the critical 20% of features; bury or cut the rest; prioritize fixing the top few error cases users actually hit.

### 1.14 Parkinson's Law
- **What:** Work expands to fill the time available for it.
- **Apply:** In productivity/task apps, default to short time estimates and let users extend; use "planned duration" nudges; show time-boxing affordances (Pomodoro-style).

### 1.15 Peak-End Rule
- **What:** People judge an experience by its most intense moment (peak) and its end, not its average *(Kahneman & Fredrickson, 1993)*.
- **Apply:** Engineer peak moments (celebrate completion, confetti on first success) and endings (success screens, "what next" guidance, warm cancellation flows). Never let a session end on an error.
- **Watch:** This is why end-of-trial and end-of-session screens are the highest-ROI screens to design.

### 1.16 Postel's Law (Robustness Principle)
- **What:** "Be liberal in what you accept, conservative in what you send" — forgiving input, strict output.
- **Apply:** Accept phone numbers with or without formatting, trim whitespace, auto-correct dates; validate on blur, not on keystroke; never punish format variance with errors.
- **Watch:** 2020s critique: over-tolerant *data* handling (not UI) can normalize bad data — validate strictly at persistence boundaries.

### 1.17 Serial Position Effect (Primacy & Recency)
- **What:** Items at the beginning (primacy) and end (recency) of a sequence are remembered best *(Murdock, 1962)*.
- **Apply:** Put the most important items first and last in nav, pricing feature lists, and onboarding steps; the middle is where recall dies.

### 1.18 Tesler's Law (Law of Conservation of Complexity)
- **What:** Every application has an irreducible amount of complexity; someone must absorb it — the system or the user.
- **Apply:** Move complexity into the system: smart defaults, automation, templates, "one click" versions of expert flows. Push complexity only to those who want it (advanced mode).
- **Watch:** Absorbed complexity still exists — don't hide so much that users can't build a mental model.

### 1.19 Von Restorff Effect (Isolation Effect)
- **What:** The item that differs most from its surroundings is the one remembered *(von Restorff, 1933)*.
- **Apply:** One accent color for the primary CTA; highlight the recommended plan; make the one thing that matters visually distinct — and only one.
- **Watch:** If everything is highlighted, nothing is (dark-pattern misuse: highlighting the expensive option while hiding the cheap one, §14).

### 1.20 Zeigarnik Effect
- **What:** People remember interrupted, incomplete tasks better than completed ones *(Zeigarnik, 1927)*.
- **Apply:** Show incomplete states ("Your profile is 60% complete"), persistent task lists, draft-saving, "resume where you left off." Completion drives re-engagement.

### 1.21 Paradox of the Active User
- **What:** Users immediately start trying to *do* things rather than reading docs or tutorials — they learn by doing *(Carroll & Rosson, 1987)*.
- **Apply:** No mandatory manuals: make the first task self-evident, teach features contextually at the moment of need, use empty states and inline tips instead of tours.
- **Watch:** Long forced onboarding tours are read by almost nobody — design for skip-and-succeed.

### 1.22 Selective Attention
- **What:** People attend to a subset of the environment and miss the rest, even prominent stimuli *(cocktail party effect; Cherry, 1953)*.
- **Apply:** Never rely on users noticing a small banner; use multiple channels (visual + email + push) for critical info; put what you need seen *in the task path*, not beside it.

### 1.23 Weber-Fechner Laws (Just Noticeable Difference)
- **What:** Perceived change is proportional to the baseline — a 10% price raise on a $5 plan feels different than on a $500 plan.
- **Apply:** Frame price increases in absolute vs relative terms strategically; make meaningful UI differences exceed the JND (bigger, brighter, distinct), and make background changes *below* the JND to avoid churn-inducing redesigns.

### 1.24 Progressive Disclosure
- **What:** Show only what's needed now; defer the rest until requested or relevant.
- **Apply:** Accordions, "advanced settings," step-by-step wizards, context-revealed features. The single most reliable technique against cognitive load in SaaS.

### 1.25 Recognition over Recall
- **What:** Recognizing something seen before is far easier than recalling it from memory (a core Nielsen heuristic).
- **Apply:** Icons + labels (not icons alone), recently used items, search suggestions, breadcrumbs, persistent navigation, autofill; never ask users to remember an ID, code, or prior screen.

### 1.26 Signal-to-Noise Ratio
- **What:** Relevant information divided by irrelevant information on a display; higher ratio = easier processing.
- **Apply:** Cut decorative elements from task-critical screens; every pixel of ornament must earn the attention it consumes. Noise includes badge spam, alert inflation, and marketing inserts inside workflows.

---

## §2 Gestalt Principles of Visual Perception

How the brain organizes visual input into groups and wholes *(Wertheimer, 1923; the Gestalt school)*. These are the grammar of layout — every grouping, card, and form in your product obeys or violates them.

### 2.1 Law of Proximity
- **What:** Objects near each other are perceived as a group.
- **Apply:** Group a label with its input (not input with the neighboring label); space between cards > space within cards; related actions cluster together.

### 2.2 Law of Similarity
- **What:** Items sharing visual traits (color, size, shape) are perceived as related.
- **Apply:** Consistent styling for all interactive elements; all "danger" actions share one look; visually distinguish but relate rows in a table.

### 2.3 Law of Closure
- **What:** The mind fills gaps to perceive complete forms.
- **Apply:** Use outlines and partial borders for light-weight UI; minimal logos/icons still read correctly; don't rely on closure for anything critical to comprehension.

### 2.4 Law of Continuity
- **What:** Elements arranged on a line/curve are perceived as related and continuous.
- **Apply:** Aligned rows/columns in data tables; stepper flows along one visual path; aligning form elements guides the eye through the intended order.

### 2.5 Law of Common Region
- **What:** Elements inside the same enclosed area are perceived as grouped.
- **Apply:** Cards, panels, and wells to group content; place destructive actions *outside* the region containing safe ones; use background tints to delimit sections.

### 2.6 Figure-Ground
- **What:** We perceive elements as either figure (focus) or ground (background); ambiguous figures flip.
- **Apply:** Modals with dimmed backdrop; elevate the active card; ensure sufficient contrast so the figure is never ambiguous; avoid busy backgrounds behind text.

### 2.7 Law of Prägnanz (Good Figure / Simplicity)
- **What:** Ambiguous stimuli are interpreted in the simplest form possible.
- **Apply:** Simple, regular shapes read faster; avoid ornate icons that can be misread; when a chart can be read two ways, restructure it so only one reading is possible.

### 2.8 Law of Uniform Connectedness
- **What:** Visually connected elements (lines, arrows, shared borders) are perceived as related.
- **Apply:** Draw the flow: connect steps with arrows/progress lines; connect toggles to what they control with proximity + shared container.

### 2.9 Synchrony (Common Fate / Parallelism)
- **What:** Elements moving together or changing at the same time are perceived as a group.
- **Apply:** Group animations (cards animate in together = one group); shared transition timing communicates relatedness; avoid accidental synchronous animations that imply false relationships.

---

## §3 Attention & Perception

### 3.1 Banner Blindness
- **What:** Users habitually ignore anything that looks like an ad or promotional banner *(Benway & Lane, 1998; confirmed by NN/g eye-tracking)*.
- **Apply:** Critical messages must not look like banners: inline them in the task flow, use system-level styling, or interrupt deliberately (with a dismiss path).
- **Watch:** The inverse is the dark pattern: styling *marketing* to look like system UI.

### 3.2 Change Blindness
- **What:** Large changes go unnoticed when they happen outside attention or without a visual transition *(Simons & Levin, 1998)*.
- **Apply:** Animate state changes; highlight what changed in lists/dashboards ("3 new rows"); never swap content in place silently.

### 3.3 Inattentional Blindness
- **What:** People miss a highly visible stimulus when attention is engaged elsewhere *(Simons & Chabris' "invisible gorilla," 1999)*.
- **Apply:** Don't place critical warnings where users are task-focused; interrupt for destructive confirmation; time interstitials to attention pauses (task completion), not mid-task.

### 3.4 Cocktail Party Effect (Selective Tuning)
- **What:** People can tune in to one stream and tune everything else out — but personally relevant cues (their name, their data) break through.
- **Apply:** Personalize notifications with the user's own data ("Your report is ready"), not generic copy; relevance is the attention filter.

### 3.5 Preattentive Processing (Pop-out)
- **What:** Color, size, orientation, and motion are processed in <200–250 ms before conscious attention — a unique dissimilar item "pops out" *(Treisman's feature-integration research)*.
- **Apply:** Use one preattentive attribute per critical element (a red badge, a moving element); pop-out fails when many items vary simultaneously ("where's Waldo" effect).

### 3.6 F-Pattern Reading (Web Scanning)
- **What:** Text-heavy pages are scanned in an F shape: top lines, then down the left edge *(NN/g eye-tracking, 2006)*.
- **Apply:** Front-load headings and the first two words of paragraphs/links; put key content and CTAs where the F lands; never assume full reading — bulleted, bolded, structured text survives scanning.

### 3.7 Z-Pattern & Gutenberg Diagram
- **What:** Sparse visual pages are scanned in a Z; the visual "dead corner" is bottom-left, the terminal focus is bottom-right.
- **Apply:** Logo/brand top-left, primary CTA top-right or bottom-right (the natural end), nothing critical in the dead zone.

### 3.8 Peripheral Vision & Mobile Thumb Zone
- **What:** Central (foveal) vision is sharp; peripheral is coarse but detects motion; on mobile, reachability maps to thumb arcs *(Steven Hoober's field research: ~49% one-thumb use)*.
- **Apply:** Primary actions and tab bars at the bottom on mobile; danger actions at the top (hard to reach accidentally); motion/notifications for the periphery, text for the center.

### 3.9 Visual Hierarchy & Visual Weight
- **What:** Size, color, contrast, position, and density assign relative importance; users process in weight order.
- **Apply:** One clear primary hierarchy per screen: heading > body > meta; control contrast discipline (primary CTA highest contrast on the page).

### 3.10 Mere Exposure Effect
- **What:** Repeated exposure increases liking *(Zajonc, 1968)*.
- **Apply:** Consistent brand elements across touchpoints compound affinity; familiarity of patterns (Jakob's Law) doubles as liking. New logos/colors should be introduced gradually.
- **Watch:** Fatigue is real — repeating one notification pattern until it's ignored is exposure without delight.

### 3.11 Curiosity Gap (Information-Gap Theory)
- **What:** Curiosity arises from a gap between what we know and want to know *(Loewenstein, 1994)*.
- **Apply:** Headlines/subject lines that open a specific gap ("The 3 settings most teams miss"), progress indicators of hidden value ("You have 4 unrevealed insights"), preview with locked remainder.
- **Watch:** Clickbait that doesn't close the gap destroys trust permanently.

### 3.12 Information Scent (Information Foraging)
- **What:** Users follow cues (link labels, icons, snippets) like animals following scent, judging whether the target is worth the cost *(Pirolli & Card, 1999)*.
- **Apply:** Labels must promise the destination precisely ("Billing & invoices," not "Account"); show result counts/previews; strengthen scent where users currently drop off.

### 3.13 Priming Effect
- **What:** Prior stimuli unconsciously shape subsequent responses (e.g., prices, imagery) — with the major caveat that many priming studies failed replication.
- **Apply (safe form):** Context-consistent imagery and copy (success imagery before an upgrade page); avoid implying causality you can't measure.

---

## §4 Memory & Learning

### 4.1 Working Memory Limits (~4 chunks)
- **What:** Modern estimates put working memory at about 4±1 chunks, not 7 *(Cowan, 2001)*.
- **Apply:** Design for 4: max 4 top actions, 4 onboarding steps per screen, 4 items per comparison row. Cross-reference Miller's Law (1.11) — plan for the stricter number.

### 4.2 Forgetting Curve
- **What:** Memory decays exponentially; most is lost within hours/days without reinforcement *(Ebbinghaus, 1885)*.
- **Apply:** Re-teach rarely used features contextually (empty states, tooltips on first re-encounter); spaced re-engagement emails; never assume learning from one exposure persists.

### 4.3 Spacing Effect
- **What:** Spaced repetition beats cramming for retention.
- **Apply:** In learning products (Duolingo model), schedule review sessions; in SaaS, drip feature education over the first weeks instead of one dump.

### 4.4 Testing Effect (Retrieval Practice)
- **What:** Actively retrieving information strengthens memory more than re-reading *(Roediger & Karpicke, 2006)*.
- **Apply:** Quizzes, "try it yourself" steps in onboarding, micro-challenges; make users *do* the feature once — it doubles retention of it.

### 4.5 Verbatim Effect
- **What:** People remember the gist/paraphrase, not exact wording.
- **Apply:** Design copy for gist: the headline must carry the full message alone; important specifics must be re-shown at the moment of action (amounts, dates), never assumed remembered.

### 4.6 Picture Superiority Effect
- **What:** Images are remembered far better than words *(Paivio; picture-superiority studies)*.
- **Apply:** Use diagrams over text for concepts, screenshots over descriptions for features, avatars/photos for people in social features.

### 4.7 Dual Coding Theory
- **What:** Combining verbal + visual channels increases encoding *(Paivio, 1971)*.
- **Apply:** Pair every abstract concept with an icon/diagram; onboarding videos with captions hit both channels; don't duplicate identical info in both channels — *complement* it.

### 4.8 Google Effect (Digital Amnesia)
- **What:** People forget information they know they can easily retrieve again *(Sparrow, Liu & Wegner, 2011)*.
- **Apply:** Don't fight it — support it: make anything findable again (searchable history, receipt archive, "recently viewed"). Friction to re-find what users expect to find is churn.

### 4.9 Misinformation Effect
- **What:** Post-event information distorts memory of the event *(Loftus)*.
- **Apply:** Confirmation dialogs must state what *will* happen, neutrally; don't let leading copy rewrite what users believe they did (matters in finance, deletion, permissions).

### 4.10 Scaffolding & Learning by Doing
- **What:** Skills grow with support that gradually withdraws (Vygotsky's zone of proximal development; consistent with the Paradox of the Active User, 1.21).
- **Apply:** Teach inside the real task (checklists in-context, pre-filled examples), withdraw help progressively (tooltips disappear after use), difficulty ramps in empty→basic→power states.

### 4.11 Generation Effect
- **What:** Self-generated answers are remembered better than read ones *(Slamecka & Graf, 1978)*.
- **Apply:** Make users type their goal during onboarding (not pick from a list) when retention of intent matters; let users name their projects/workspaces — it increases both memory and ownership (ties to IKEA Effect, 5.15).

---

## §5 Decision-Making: Heuristics & Cognitive Biases

System 1 (fast, automatic) drives most interface decisions; System 2 (slow, deliberate) is expensive and users avoid it *(Kahneman, "Thinking, Fast and Slow," 2011)*. These biases are not bugs to eliminate — they are the default settings you design around.

### 5.1 Anchoring Effect
- **What:** The first number seen skews all later judgments *(Tversky & Kahneman, 1974)*.
- **Apply:** Show the original price next to the discount; present the premium plan first on pricing pages; anchor with "from $X" before itemized features.
- **Watch:** Fake reference prices (inflated "was" prices) are regulated as deceptive pricing in many jurisdictions.

### 5.2 Availability Heuristic
- **What:** We judge likelihood by how easily examples come to mind.
- **Apply:** Recent, vivid events dominate perception — a recent outage outweighs months of uptime. Communicate reliability proactively (status pages, uptime badges) rather than letting the last incident define you.

### 5.3 Affect Heuristic
- **What:** Decisions ride on current feelings rather than analysis; positive affect shrinks perceived risk.
- **Apply:** Match emotional tone to decision stakes: playful tone for low-stakes choices; calm, data-forward tone for money, security, and deletion flows.

### 5.4 Framing Effect
- **What:** Logically identical options are judged differently by presentation: "90% success" vs "10% failure"; "save $50" vs "lose $50."
- **Apply:** Frame benefits positively by default ("keep your data" vs "don't lose your data"); for loss-framing (more motivating), use honestly: "You'll lose your streak if you skip today."

### 5.5 Loss Aversion
- **What:** Losses weigh roughly twice as much as equivalent gains *(Kahneman & Tversky, prospect theory, 1979)*.
- **Apply:** Free trials convert better framed as "what you'll lose when it ends" (list of locked features) than as "what you'll gain"; show what users already have at stake (data, setups, streaks) before plan downgrade prompts.
- **Watch:** Loss aversion is the engine of most dark patterns (fake countdowns, fear-based copy). Use real stakes only.

### 5.6 Status Quo Bias
- **What:** Inertia: the current state feels safest and is the default path *(Samuelson & Zeckhauser, 1988)*.
- **Apply:** Design the desired behavior *as* the status quo: auto-enroll in annual billing with a monthly toggle, preselect sensible settings, keep good flows frictionless and bad flows (delete, downgrade) deliberately considered.

### 5.7 Default Effect (Power of Defaults)
- **What:** Whatever is preselected wins overwhelmingly (organ-donation defaults; Johnson & Goldstein, 2003; "Nudge," Thaler & Sunstein, 2008).
- **Apply:** Smart defaults are your highest-leverage decision tool: default notification settings, plan selection, template choice, privacy levels (that still protect the user). Always visible + changeable.
- **Watch:** Defaults that serve the business against user interest (opt-out data sharing) are the definition of a manipulative nudge — and increasingly illegal (§14).

### 5.8 Decoy Effect (Asymmetric Dominance)
- **What:** Adding a third, clearly inferior option shifts choice toward the target *(Huber, Payne & Puto, 1982)*.
- **Apply:** Three-tier pricing where the middle plan is designed to dominate the decoy (similar price, more value) and be beaten only by the premium; decoys must be genuinely purchasable, not imaginary.

### 5.9 Confirmation Bias
- **What:** We seek and favor information that confirms existing beliefs.
- **Apply:** In analytics/dashboards, present disconfirming evidence proactively (show the segment where the campaign failed); in onboarding, don't just validate the user's plan — surface the missing step.

### 5.10 Negativity Bias
- **What:** Negative events, reviews, and feedback have greater psychological impact than positive ones *(Rozin & Royzman, 2001)*.
- **Apply:** One 3-star review outweighs ten 5-star ones in perception — surface review *volume* and response quality; in error states, lead with the fix, not the fault; moderate communities actively.

### 5.11 Optimism Bias
- **What:** People systematically overestimate their future behavior: "I'll definitely use this daily," "I'll finish this course."
- **Apply:** Annual plans, course purchases, and gym-model subscriptions exploit optimism honestly by designing *for* the return (re-engagement journeys), not just the purchase. In planning tools, counter with estimates from similar past projects.

### 5.12 Planning Fallacy
- **What:** People underestimate task duration even when they know past tasks ran late *(Kahneman & Tversky, 1979; Buehler et al., 1994)*.
- **Apply:** In project/task tools, prefill estimates from historical data; show buffer time; progress forecasts based on actual velocity, not stated plans.

### 5.13 Present Bias (Hyperbolic Discounting)
- **What:** Rewards now are vastly overweighted vs rewards later; costs later are underweighted.
- **Apply:** Make future rewards concrete and near ("Save 4 hours *this week*"); make future costs concrete and near ("Card charged in 3 days, click to change"); deliver immediate value in the first session — never "value in 3 weeks."

### 5.14 Sunk Cost Fallacy
- **What:** Past investment (time, money, data) irrationally increases commitment to continue *(Arkes & Blumer, 1985)*.
- **Apply:** Honest use: surface accumulated value at renewal ("Your workspace holds 1,200 tasks and 3 years of history") — legitimate information. Migration tooling ("import everything in one click") lowers switching cost for the *user's* benefit.
- **Watch:** Using sunk cost to trap users in unwanted subscriptions is a classic roach motel (§14).

### 5.15 IKEA Effect
- **What:** Products users partly create are valued far more *(Norton, Mochon & Ariely, 2012)*.
- **Apply:** Co-creation moments in onboarding: let users build their first dashboard/doc/workspace (pre-filled but editable); user-created templates, themes, automations raise switching costs *because the user made them* — that's legitimate retention.

### 5.16 Endowment Effect
- **What:** Ownership raises valuation *(Kahneman, Knetsch & Thaler, 1990)*.
- **Apply:** Trials that let users create real data (files, projects) convert better than trials on demo data; frame trial artifacts as "your workspace," "your reports."

### 5.17 Bandwagon Effect
- **What:** People adopt what others are adopting.
- **Apply:** "Join 40,000 teams," trending templates, "most popular plan" badges — with real, current numbers.

### 5.18 Survivorship Bias
- **What:** We learn from visible winners and ignore the invisible failures.
- **Apply:** In case studies and benchmarks, show base rates ("median outcome across all customers"), not just stars; in your own analytics, examine churned users' journeys, not just power users'.

### 5.19 Zero-Risk Bias
- **What:** People prefer eliminating a small risk entirely over reducing a large one.
- **Apply:** "Zero-knowledge" encryption, "we never sell your data" statements, 30-day money-back guarantees — removing one stated risk completely outperforms probabilistic reassurance.

### 5.20 Ambiguity Aversion
- **What:** Known odds are preferred over unknown odds (Ellsberg paradox).
- **Apply:** Remove ambiguity at decision points: exact price before checkout, exact delivery dates, "what happens after the trial" stated plainly. Hidden next-steps read as risk and stall conversion.

### 5.21 Information Bias
- **What:** We over-value more information even when it changes nothing.
- **Apply:** In dashboards, curate: fewer, decision-relevant metrics beat exhaustive feeds; offer "more detail" on demand rather than by default.

### 5.22 Dunning-Kruger Effect
- **What:** Low skill inflates confidence; experts underestimate themselves *(Kruger & Dunning, 1999)*.
- **Apply:** Beginners skip help because they overestimate competence — so embed guidance invisibly (inline validation, automatic fixes); never gate basic flows behind "read the docs first."

### 5.23 Curse of Knowledge
- **What:** Experts can't imagine not knowing what they know (Newton's tapper-listener study: ~2.5% of tunes guessed by listeners).
- **Apply:** Feature naming, empty states, and error copy written by the team are unintelligible to new users; test copy with people outside the team; label features by *user goals*, not internal architecture ("Send invoice," not "Use AR module").

### 5.24 Hindsight Bias
- **What:** After an outcome, "it was obvious all along" — memory rewrites prediction.
- **Apply:** In incident post-mortems and analytics reviews, compare against the *logged* forecast, not memory; in product retros, judge decisions with the information available then.

---

## §6 Behavioral Economics & Choice Architecture

### 6.1 Nudge Theory
- **What:** Small changes in how choices are presented reliably alter behavior without forbidding options *(Thaler & Sunstein, "Nudge," 2008)*.
- **Apply:** Every default, order, and frame is a nudge whether you chose it or not — audit them deliberately and set them in the user's interest (better defaults, safer preselections).

### 6.2 Choice Architecture & Friction Design
- **What:** The same options, ordered/packaged differently, produce different choices; friction is a design material.
- **Apply:** Map friction deliberately: *add* friction where errors are expensive (delete, transfer money — with undo), *remove* friction where value is clear (signup, upgrade). Friction asymmetry is the core skill of flow design.

### 6.3 Mental Accounting
- **What:** People categorize money into mental buckets ("monthly budget," "business spend") and treat them differently *(Thaler, 1985/1999)*.
- **Apply:** Price in the customer's accounting frame: per-user/per-month for team tools (fits "operating budget"), one-time for tools; show costs in the units users budget with ("$12/user/month, billed annually").

### 6.4 Zero-Price Effect
- **What:** "Free" is not just a low price — it's a different psychological regime; demand jumps disproportionately *(Shampanier, Mazar & Ariely, 2007)*.
- **Apply:** A genuinely free tier beats a cheap trial for driving adoption of network products; use free for one side of a marketplace; beware: zero attracts non-buyers too — design upgrade triggers from usage, not nagging.

### 6.5 Partitioned Pricing & Drip Pricing
- **What:** Splitting price into components changes perception — and adding mandatory fees late in checkout ("drip pricing") inflates drop-off and complaint rates *(Morwitz, Greenleaf & Johnson, 1998)*.
- **Apply:** Show the full, all-in price early and everywhere; itemize *with* the total visible. Regulatory note: drip pricing is under active enforcement (FTC junk-fees rulemaking; EU price-indication rules).

### 6.6 Bundling & Temptation Bundling
- **What:** Bundles hide individual prices and raise perceived value; pairing a "should" activity with a "want" activity increases follow-through *(Milkman, Minson & Volpp, 2014 — gym audiobook study)*.
- **Apply:** Bundle adjacent tools ("Editor + Storage"); pair desired-but-avoided behaviors with pleasures: listen to your show only at the gym, weekly report only with your coffee ritual; "cold turkey" commitments (hard blocking) work for high-willpower-needs cases.

### 6.7 Commitment Devices & Deadlines
- **What:** Voluntary pre-commitment (stakes, deadlines, public pledges) sharply raises goal completion *(Ariely & Wertenbroch, 2002)*.
- **Apply:** Let users set their own deadline ("I'll publish by Friday"), email-my-future-self, deposit/stake mechanics; commitment works best when *chosen*, not imposed.

### 6.8 Fresh Start Effect
- **What:** Temporal landmarks (Monday, new year, birthday) boost aspirational behavior and conversion *(Dai, Milkman & Riis, 2014)*.
- **Apply:** Time re-engagement campaigns to landmarks ("Start your fresh start this Monday"); "New year, new workspace" onboarding; year-in-review summaries as renewal moments.

### 6.9 Endowed Progress Effect
- **What:** Artificial advancement toward a goal increases completion *(Nunes & Drèze, 2006: car-wash cards pre-stamped completed 34% vs 19%)*.
- **Apply:** Start progress bars at 20% ("Step 1 of 5" pre-done), prefill profiles with imported data, "We've imported your contacts — finish in 2 clicks." Honest version: credit progress that reflects real work done *for* the user.
- **Watch:** Fabricated progress on things the user never did crosses into deception.

### 6.10 Effort Heuristic
- **What:** More apparent effort → higher perceived value *(Kruger et al., 2004)*.
- **Apply:** Show the craft: "hand-crafted report for you," render/processing steps visible, personalized computations ("analyzing your 340 data points…") — perceived effort raises willingness to pay and patience.

---

## §7 Motivation, Habits & Engagement

### 7.1 Fogg Behavior Model (B=MAP)
- **What:** Behavior happens when Motivation × Ability × Prompt converge at the same moment *(BJ Fogg, "Persuasive Technology," 2003; "Tiny Habits," 2019)*.
- **Apply:** For any target action, diagnose the missing ingredient: raise motivation (show value), lower ability cost (fewer steps), fix the prompt (right time, right place). Prompts after motivation peaks (post-win moments) work best.

### 7.2 Fogg's Six Ability Factors
- **What:** Simplicity = time, money, physical effort, brain cycles, social deviance, and non-routineness all being low.
- **Apply:** Checklist every flow against the six: How many minutes? What cost? Typing/holding effort? How much thinking? Does it feel socially odd? Is it familiar? Remove the *cheapest* to fix first.

### 7.3 Hooked Model (Trigger → Action → Variable Reward → Investment)
- **What:** Nir Eyal's four-phase habit loop for products ("Hooked," 2014): recurring triggers paired with actions leading to variable rewards and stored-value investment.
- **Apply:** Design the cycle for your product: external trigger (notification) → minimal action (one tap) → variable reward (new content/social/achievement) → investment (data created) that improves the *next* cycle and loads the next trigger.
- **Watch:** Eyal's own test: does the habit improve the user's life? (His follow-up: "Indistractable," 2019.) Products that fail that test are exploitation (§14).

### 7.4 Habit Loop (Cue → Routine → Reward)
- **What:** Habits form from context cues triggering routines rewarded consistently *(Duhigg, 2012; Wood & Neal's context-cue research)*.
- **Apply:** Anchor your product to existing routines ("with your morning coffee," calendar-adjacent); consistency of cue and reward matters more than reward size; context (same place, same time) is the strongest cue.

### 7.5 Variable Rewards
- **What:** Unpredictable rewards sustain engagement far more than fixed ones *(Skinner's operant conditioning)*; Eyal's three types: rewards of the tribe (social), the hunt (search/collection), the self (mastery/novelty).
- **Apply:** Vary the payload: new follower counts, fresh insights each Monday, rotating templates; fixed rewards habituate within days.
- **Watch:** This is the slot-machine mechanic — pair with real user value and controls (notification digests, session reminders), or it becomes a §14 item.

### 7.6 Investment & Stored Value
- **What:** Each cycle should load the next: user-added data, content, connections, preferences.
- **Apply:** Map your product's stored value (docs, integrations, history, reputation, customization) and make every session deepen at least one; stored value — not lock-in contracts — is durable retention.

### 7.7 Self-Determination Theory (Autonomy, Competence, Relatedness)
- **What:** Intrinsic motivation grows when three needs are met *(Deci & Ryan, 1985/2000)*.
- **Apply:** Autonomy: real choices, customization, opt-ins. Competence: progressive difficulty, visible skill growth, good defaults that make users feel smart. Relatedness: teams, sharing, community, co-editing. Products serving all three retain without reward inflation.

### 7.8 Overjustification Effect
- **What:** Extrinsic rewards can *destroy* intrinsic motivation *(Lepper, Greene & Nisbett, 1973 — children's drawing study)*.
- **Apply:** Don't pay users for what they already enjoy; use badges/points for behaviors that need a spark, and taper them as intrinsic value takes over; praise progress and mastery, not mere activity.

### 7.9 The Progress Principle
- **What:** Small, visible progress in meaningful work is the strongest daily motivator *(Amabile & Kramer, "The Progress Principle," 2011)*.
- **Apply:** Surface small wins: "3 tasks shipped today," weekly recap emails, momentum stats; protect users from setbacks (autosave, undo) — setbacks deflate motivation disproportionately.

### 7.10 Streaks & Loss-Framed Momentum
- **What:** Streak mechanics (Duolingo) weaponize loss aversion for consistency: the streak itself becomes the asset to protect.
- **Apply:** Offer streak freezes/repairs for genuine absence; celebrate milestone streaks; pair streak risk with the actual value ("keep your streak — 2 minutes today").
- **Watch:** Guilt-based streak shaming is a documented dark pattern adjacent to confirmshaming.

### 7.11 Gamification Elements (Points, Badges, Leaderboards)
- **What:** PBL systems can bootstrap engagement — and backfire: leaderboards demotivate the majority at the bottom; badges inflate worthless behavior.
- **Apply:** Use cooperative/relative-progress leaderboards (teams, past-self comparison); meaningful badges tied to competence (SDT 7.7); give points *meaning* (redeemable, status-bearing) or skip points entirely.

### 7.12 Customization & Ownership
- **What:** Configuring one's environment raises both ownership (endowment 5.16) and autonomy (7.7).
- **Apply:** Early customization moments (theme, workspace name, avatar) create investment cheaply; ship sane defaults so customization is optional delight, not a required chore.

---

## §8 Emotion, Aesthetics & Delight

### 8.1 Norman's Three Levels of Emotional Design
- **What:** Visceral (immediate appearance), behavioral (use and feel), reflective (meaning, memory, identity) *(Don Norman, "Emotional Design," 2004)*.
- **Apply:** Visceral: hero screens, app icons, motion polish. Behavioral: frictionless flows. Reflective: annual summaries ("Your year in review"), shareable artifacts, brand rituals. Products that hit only visceral churn after week one.

### 8.2 Micro-interactions & Delight
- **What:** Small functional moments (pull-to-refresh, like animations) carry personality and feedback.
- **Apply:** Animate state changes with purpose (success check, haptics on mobile); one delightful signature moment per core flow; delight must never add latency to critical paths (Doherty 1.5).

### 8.3 Personality & Humor (Voice)
- **What:** A consistent, human voice (Mailchimp's tone) raises memorability and tolerance.
- **Apply:** Define voice per context: playful in empty states and success; strictly clear in errors, billing, security. Humor in error messages must still explain the fix.

### 8.4 Color Psychology (use with caution)
- **What:** Colors carry learned associations (blue=trust/finance, red=alarm/urgency, green=success/go) — the evidence is contextual and culture-dependent, not universal.
- **Apply:** Use conventions users already know (Jakob's Law 1.10): red for destructive, green for confirm; semantic color consistency beats symbolic color cleverness; always pair color with text/icon (accessibility, color-blindness ~8% of men).

### 8.5 Emotional Contagion
- **What:** Emotional states transfer through design cues, copy, and other users' visible behavior.
- **Apply:** Positive framing in shared spaces (celebrations, supportive defaults in communities); calm, confident copy in onboarding; audit support-ticket flows — contagious frustration is real.

### 8.6 Peak-Moment Design
- **What:** Memorable experiences are engineered around elevation, insight, pride, and connection *(Chip & Dan Heath, "The Power of Moments," 2017)* — consistent with the Peak-End Rule (1.15).
- **Apply:** Deliberately build one peak per milestone: first-value moment celebration, milestone emails with personalized stats, upgrade moments ("you just did what used to take an hour").

### 8.7 Anticipation & Pre-Goal Attainment
- **What:** Anticipating a reward activates reward circuitry nearly as much as receiving it; anticipation windows are emotionally valuable *(Kahneman's "pleasures of anticipation")*.
- **Apply:** Announce upcoming features with visible progress ("shipping in 2 weeks"); waitlists with position numbers; scheduled deliveries (weekly report Mondays) create positive anticipation loops.

### 8.8 Cognitive Dissonance & Post-Purchase Reassurance
- **What:** After significant choices, people seek reassurance to resolve dissonance *(Festinger, 1957)*; unresolved doubt becomes refund/churn.
- **Apply:** Post-purchase confirmation must re-sell the decision ("Great choice — here's what happens next"), onboarding email within minutes, visible "what's included" recap; kill buyer's remorse before it kills the subscription.

---

## §9 Persuasion & Influence (Cialdini +)

Robert Cialdini's principles (*Influence*, 7th ed. 2021, now with **Unity** as the seventh) — the backbone of ethical conversion design.

### 9.1 Reciprocity
- **What:** We repay gifts, favors, and concessions *(Regan, 1971)*. Personalized and unexpected gifts are strongest.
- **Apply:** Free valuable tools/content before asking (calculators, templates, audits), surprise upgrades ("we added you Pro for a month"), personalized reports as gifts. Concession form: when user declines big ask, follow with the small one.

### 9.2 Commitment & Consistency
- **What:** Once committed (small public/effortful step), people align later behavior with it.
- **Apply:** Ask for small commitments first (goal selection in onboarding → plan recommendation), make commitments active and self-written ("I want to grow my newsletter"), reference them at decision points ("You told us your goal is X — Pro is the fit").

### 9.3 Social Proof
- **What:** We copy what similar others do, especially under uncertainty *(Asch conformity; Cialdini)*.
- **Apply:** Testimonials with faces/names/roles, usage counters, "teams like yours use X," live activity ("42 designers signed up this week"), reviews from the user's industry. Specificity beats volume ("used by 3,200 dental clinics" > "thousands").

### 9.4 Authority
- **What:** Credible expertise and badges increase compliance (Cialdini; the honest form of authority signaling, not the Milgram abuse).
- **Apply:** Certifications, "SOC 2," expert endorsements with credentials, data citations, team expertise pages. Authority must be verifiable — fake badges are fraud.

### 9.5 Liking
- **What:** We say yes to people/products we like: similarity, compliments, familiarity, shared goals.
- **Apply:** Match onboarding copy to the user's stated identity; human faces and founder voice; "people like you" personalization; politeness and micro-appreciation in microcopy ("Thanks for waiting").

### 9.6 Scarcity
- **What:** Scarce items seem more valuable *(Worchel, Lee & Adewole's cookie-jar studies, 1975)*.
- **Apply:** Honest scarcity only: real seat limits, genuine beta caps, true deadlines (price changes you actually make). Show *why* it's scarce.
- **Watch:** Fake countdown timers that reset are the canonical dark pattern — enforcement target (FTC actions, §14).

### 9.7 Unity (the 7th principle)
- **What:** Shared identity ("one of us": family, region, profession, fandom) is more powerful than liking *(Cialdini, "Pre-Suasion," 2016; Influence 7th ed., 2021)*.
- **Apply:** Speak in-group: "built for indie devs, by indie devs"; community brands, user-created conventions, insider language, regional/localized identity cues. Unity is the strongest lever in community-led growth.

### 9.8 Foot-in-the-Door
- **What:** Small initial compliance increases later larger compliance *(Freedman & Fraser, 1966)*.
- **Apply:** Free-tool → email → trial → paid ladders; micro-conversions in onboarding (name workspace → invite teammate → upgrade invite). Each step must deliver standalone value.

### 9.9 Door-in-the-Face
- **What:** A large request, refused, raises compliance with a smaller follow-up (Cialdini et al., 1975).
- **Apply:** Downsells after upgrade declines: "Enterprise?" → "Then Pro annual?" in-app offers; use sparingly — visible manipulation breeds distrust.

### 9.10 Fear Appeals (EPPM)
- **What:** Fear motivates only when paired with high perceived efficacy — a clear, doable action (Extended Parallel Process Model, Witte, 1992).
- **Apply:** Security/backup/compliance messaging: threat + "here's exactly what to do now" + proof it's easy. Fear without efficacy produces avoidance, not action.

---

## §10 Trust, Credibility & Error Handling

### 10.1 Stanford Web Credibility Guidelines
- **What:** Stanford Persuasive Tech Lab's research (Fogg et al.): real-world feel, ease of use, expertise, trust seals, professional polish drive credibility; typos, broken links, and hype destroy it fastest.
- **Apply:** Credibility audit: contact info visible, no dead ends, real photos over stock, accurate copy, updated copyright/dates, no overclaiming.

### 10.2 Trust Seals & Social Validation in Checkout
- **What:** Security badges and reviews measurably lift checkout completion — but effects vary; irrelevant or excessive badges can depress trust.
- **Apply:** One relevant seal near payment (payment provider, "SSL-secured"), reviews near the CTA, money-back guarantee stated exactly; don't carpet-checkout with ten badges.

### 10.3 Transparency & Honesty as Differentiator
- **What:** Visible reasoning, open pricing, public changelogs, and admitting limits raise long-term trust even when short-term conversion drops.
- **Apply:** Show "why" behind recommendations ("because you invoice monthly"), publish pricing without "Contact sales" gates where possible, admit outages with cause and fix.

### 10.4 Privacy Control & the Privacy Paradox
- **What:** Users say they care about privacy but behave otherwise — until trust is broken, then they overcorrect.
- **Apply:** Progressive permission (ask at context: mic when recording), plain-language data explanations, granular toggles, easy export/deletion. Control *perception* and reality must match; dark-pattern data grabs are the fastest trust destroyer.

### 10.5 Error Prevention (Poka-Yoke)
- **What:** Preventing errors beats fixing them *(Norman's design principles; industrial poka-yoke)*.
- **Apply:** Constrain inputs (date pickers over text), confirm destructive actions by consequence ("Deletes 3 projects"), undo everywhere, disable invalid options instead of erroring later.

### 10.6 Blame-Free Error Messages
- **What:** Errors written as user fault ("Invalid input!") raise frustration; system-accountability framing ("We couldn't reach the server") preserves trust.
- **Apply:** Formula: what happened (plain language) + why (briefly) + what to do now (one action) + escape ("Try again / Contact support"). Never blame, never jargon, never dead-end.

### 10.7 Service Recovery Paradox
- **What:** A well-handled failure can leave users *more* loyal than no failure at all — with limits (works once; catastrophic failures don't recover).
- **Apply:** Over-invest in failure journeys: instant acknowledgment, visible fix progress, compensation proportionate to harm ("sorry" credits); the recovery experience is a designed peak (1.15).

### 10.8 Consistency Builds Trust
- **What:** Reliability across time and touchpoints is the cognitive basis of trust: predictable = safe.
- **Apply:** Identical terms for identical things across product/emails/ads; don't redesign interaction patterns casually; changelog + deprecation notices when patterns must change.

### 10.9 Third-Party Validation
- **What:** Independent verification (certifications, press, app-store ratings, G2/Capterra) is trusted more than self-claims.
- **Apply:** Show verification with date ("SOC 2 Type II, audited 2025"), real rating distributions (not just 4.9 stars), embed review widgets on pricing pages.

### 10.10 Perceived Security
- **What:** Users judge security by signals (padlocks, masks, fingerprints) that may not correlate with actual security.
- **Apply:** Mask sensitive data by default, show session/device lists, display last-login, use explicit state ("Locked — 2FA on"). Signals must reflect real protections; decorative security is a deception (§14).

### 10.11 Progressive Permission & Trust Onboarding
- **What:** Asking for everything at signup (notifications, contacts, location) maximizes denial; contextual asks convert *(NN/g guidance)*.
- **Apply:** Ask at the moment of need with pre-ask rationale ("We'll need notifications to alert you when the build finishes — enable?"); make denial safe and revocable.

---

## §11 Time, Waiting & Perceived Performance

### 11.1 Nielsen's Response Time Limits
- **What:** 0.1 s = instant; 1 s = flow limit; 10 s = attention limit *(Nielsen, 1993; still the working standard; Core Web Vitals operationalize it)*.
- **Apply:** Budget interactions against these bands; beyond 1 s show state; beyond 10 s give progress + async option ("we'll email you when done").

### 11.2 Perceived Performance & Optimistic UI
- **What:** Users judge speed by perception; assuming success and rolling back on failure feels dramatically faster than waiting for confirmation.
- **Apply:** Optimistic updates for low-risk actions (like, send, add item), instant visual acknowledgment everywhere, prefetch likely-next content.
- **Watch:** Optimistic UI on payment/irreversible actions is a bug factory — confirm those.

### 11.3 Skeleton Screens vs Spinners
- **What:** Skeletons (shape-preserving placeholders) make waits feel shorter and set expectations; spinners communicate only "wait."
- **Apply:** Skeletons for content loads, spinners for sub-second actions, percentage/step indicators for long operations; skeletons must match final layout — layout shift after load undoes the benefit.

### 11.4 Progress Bar Psychology
- **What:** Perceived duration depends on bar behavior: smooth accelerating bars feel fastest; stalls are intolerable (perceptual research on progress-bar scaling, e.g., Chris Harrison et al., CMU).
- **Apply:** Never show a bar stuck at 90%; show real steps ("2 of 5"), combine bar + specific status text; if the tail is genuinely slow, shift perceived progress to remaining steps.

### 11.5 Operational Transparency
- **What:** Showing the work being done reduces perceived wait and raises value perception *(Buell & Norton's airport baggage-tracker field study, 2011)*.
- **Apply:** Let users watch the process: live render/scan/processing logs, map of courier, "an agent is reviewing your request" with progress; transparency converts waiting into engagement.

### 11.6 Maister's Principles of Waiting Lines
- **What:** Occupied time feels shorter; people want to start; anxiety makes waits feel longer; uncertain waits > known waits; unexplained > explained; unfair > fair; solo > group; more valuable service → longer tolerated waits *(David Maister, "The Psychology of Waiting Lines," 1985)*.
- **Apply:** Give users something to do during load (tips, previews), state expected wait explicitly ("usually 30–60 s"), show queue position, explain causes; never leave an unexplained spinner over 10 s.

### 11.7 Duration Neglect
- **What:** In retrospective judgment, duration matters little compared to peaks and ends (part of Peak-End research).
- **Apply:** Long mediocre onboarding with a strong ending beats short onboarding that trails off; add a finish ritual to long processes (summary of what was accomplished).

### 11.8 Explained Uncertainty
- **What:** Unknown-duration waits feel longest; honest ranges with reasons feel shorter.
- **Apply:** "3–5 min (your file is large)" beats "Processing…" forever-spinner; when delay exceeds the stated range, proactively explain ("still working — 200 pages found").

### 11.9 Gamified Waits
- **What:** Micro-interactions during mandatory waits (pull-to-refresh, playful loaders) convert dead time into engagement.
- **Apply:** Rotate tips/lore in loaders for repeated long operations; make progress tactile (haptics, springy motion); keep short waits clean — whimsy costs attention.

---

## §12 Social & Group Psychology

### 12.1 Conformity (Asch)
- **What:** People align with group answers even against their own eyes *(Asch, 1951)* — normative influence is powerful in visible communities.
- **Apply:** Community norms self-police when made visible (pinned rules, upvoted conduct); design group-setting defaults toward the behavior you want.
- **Watch:** Conformity pressure used to suppress legitimate dissent in communities is a moderation failure.

### 12.2 Social Comparison Theory
- **What:** We evaluate ourselves against others *(Festinger, 1954)* — upward comparison motivates or discourages depending on perceived attainability.
- **Apply:** Compare users to *attainable* targets: past self, cohort average, "next rank"; never expose raw leaderboards to the bottom decile without a relevant metric ("fastest progress this week").
- **Watch:** Upward comparison at scale has documented mental-health costs — design comparison with empathy.

### 12.3 FOMO (Fear of Missing Out)
- **What:** Anxiety about missing rewarding experiences drives checking behavior *(Przybylski et al., 2013)*.
- **Apply:** Honest use: real-time status ("3 seats left in this cohort"), visible activity of connections, limited-time real events.
- **Watch:** Manufactured FOMO (endless fake "X just bought!") is one of the most-reported dark-pattern categories.

### 12.4 Community & Belonging (Relatedness)
- **What:** Belonging is a core motivator (SDT 7.7; Baumeister & Leary's belongingness hypothesis, 1995).
- **Apply:** Give members identity (roles, badges, spaces), rituals (weekly threads), and visible mutual aid (answered-questions counts); onboard into community *before* asking contributions.

### 12.5 Collaboration & Shared Value
- **What:** Features with two-person value loops (invite, co-edit, share) create network retention.
- **Apply:** Design the invite moment inside the value moment ("Share this board — collaborators see changes live"), show collaborator presence, give non-users a graceful view-only landing.

### 12.6 Social Desirability Bias (in user research)
- **What:** Research participants report what sounds good, not what they do.
- **Apply:** Ask about past behavior, not future intent ("When did you last…?" not "Would you…?"); triangulate self-report with analytics; treat stated preferences as hypotheses.

---

## §13 AI-Era Psychology (2023–2026)

The newest domain: how people perceive, trust, and misuse AI-powered features. For any product shipping AI in 2025–2026, these are table stakes.

### 13.1 Algorithm Aversion
- **What:** People lose confidence in algorithmic advice much faster than in human advice after seeing the same error *(Dietvorst, Simmons & Massey, 2015)*.
- **Apply:** Design AI failure communication explicitly: frame accuracy honestly upfront ("right ~80% of the time — always review"), make error recovery one tap, never let the first user exposure be a high-stakes failure.

### 13.2 Algorithm Appreciation
- **What:** The countervailing finding: when advice is presented as machine-generated, people rate it *higher* than identical human advice *(Logg, Minson & Moore, 2019)*.
- **Apply:** In domains where your AI is genuinely strong (matching, forecasting, ranking), *labeled* AI output increases uptake; in judgment-heavy domains (health, hiring, law), the same label triggers aversion — calibrate disclosure per feature.

### 13.3 Automation Bias
- **What:** Over-trusting automated output: people accept machine answers with less scrutiny than human answers *(Skitka & Mosier, 1996)* — the opposite failure mode of aversion.
- **Apply:** Build verification into the flow: show sources/confidence, require confirmation for consequential outputs (payments, sends, deletions), occasional spot-check prompts ("does this summary look right?").
- **Watch:** This is the core liability of AI features in 2024–2026: confident, fluent, *wrong* output accepted silently.

### 13.4 Automation Complacency
- **What:** Prolonged high reliability breeds attention drift — monitoring collapses exactly when it's needed (aviation research, transferred to AI copilots).
- **Apply:** Vary the interaction (occasional checks, active feedback requests), avoid full auto-pilot modes for consequential flows; design "human checkpoints" that are meaningful, not ritual.

### 13.5 Trust Calibration
- **What:** The design goal is neither max trust nor min trust, but *appropriate* reliance *(Lee & See, 2004)* — trust proportional to actual system capability.
- **Apply:** Communicate capability boundaries ("great at summarizing, unreliable with numbers"), show uncertainty visually (confidence bars, source links), make it easy to reject and edit output — calibrated users become power users; miscalibrated users churn or get harmed.

### 13.6 ELIZA Effect
- **What:** Users attribute understanding and intent to even trivially simple conversational programs *(Weizenbaum, 1966)* — vastly amplified by modern LLMs.
- **Apply:** Empathy display raises disclosure and satisfaction (support bots) — but never simulate empathy you can't honor (crisis, legal, medical); route to humans explicitly when stakes cross the line.

### 13.7 Anthropomorphism of AI
- **What:** People apply social expectations (minds, feelings, accountability) to humanlike agents *(Epley, Waytz & Cacioppo, 2007)*.
- **Apply:** Humanlike personas raise engagement and tolerance, lower perceived risk of error; the level of anthropomorphism should match accountability: full persona for casual help, plainer interface where errors are costly.

### 13.8 Uncanny Valley
- **What:** Near-human representations trigger aversion at the "almost but not quite" point *(Mori, 1970)* — applies to avatars, voices, and chat styles.
- **Apply:** Stay stylized or clearly artificial rather than *almost* human; disclose bot identity early — disclosure + warmth outperforms the trust collapse after discovered deception.

### 13.9 AI Disclosure Effects
- **What:** Disclosing "this is an AI" shifts perception both ways (warmth/competence tradeoffs); field research (Luo et al., 2019) found chatbot disclosure effects wash out over time, with transparency preserving long-term trust.
- **Apply:** Disclose plainly and early ("AI assistant — I can make mistakes"); disclosure paired with capability statements ("drafts in seconds, verify before sending") beats both hiding and vague "AI-powered" badges.

### 13.10 Explainability & Mental Models of AI
- **What:** Users need a workable mental model of what the AI does; explanations ("based on your last 30 invoices") fix both trust and misuse.
- **Apply:** One-line "why" on every AI output, sources on facts, examples of what it can/can't do in empty states; avoid explaining model internals — explain *behavior* in user terms.

### 13.11 Uncertainty Communication for Generative AI
- **What:** LLM output is fluent at every confidence level, so fluency is not evidence; users can't tell confident-wrong from confident-right.
- **Apply:** Externalize confidence: citations, "low confidence" tags on low-support claims, hedged default copy ("this may be outdated — check"), structured output with checkable parts; visible uncertainty signaling is a top differentiator of trustworthy AI UX in 2025–2026.

### 13.12 Streaming, Interactivity & Perceived Intelligence
- **What:** Token-streamed responses feel faster and smarter than wait-then-show, even at equal latency; a visible "thinking" state also lowers abandonment.
- **Apply:** Stream by default, show interim "thinking" with cancelable state, render markdown progressively; never block the UI while generating — partial results + stop button is the current standard.

### 13.13 Co-Creation & Authorship
- **What:** AI-drafted content raises ownership ambiguity; users value drafts they *edited* more than drafts they *accepted* (IKEA Effect 5.15 transfers to AI).
- **Apply:** Position AI as draft partner ("edit anything"), keep human edits visible (suggest-changes diff), let users claim authorship in exports; this also raises perceived value of the output.

### 13.14 Manipulative AI & the Regulatory Wave
- **What:** Regulators now target AI-specific manipulation: EU AI Act (in force Aug 2024; prohibitions on manipulative/subliminal AI techniques applicable from Feb 2025), FTC enforcement against AI overclaiming ("Operation AI Comply," 2024).
- **Apply:** Never design AI that exploits emotion at vulnerable moments, fabricates urgency or personas deceptively, or overclaims capability ("100% accurate legal review" = enforcement risk). Compliance is now a design input, not an afterthought.

### 13.15 Conversational UX Psychology
- **What:** Chat interfaces trigger turn-taking expectations: fast first token, human-paced typing, graceful clarification, conversational error-tolerance norms.
- **Apply:** Acknowledge before answering ("Looking…"), ask one clarification question max, recover conversationally on failure ("I misread that — did you mean X?"), keep threads resumable; silence over ~10 s must be explained (§11).

---

## §14 Ethics: Dark Patterns & Deceptive Design

Coined by Harry Brignull, 2010; now a regulatory category, not just an ethics debate. The five strategy families per Gray et al. (2018): **Nagging, Obstruction, Sneaking, Interface Interference, Forced Action.**

### The pattern catalog (know them to avoid them)
1. **Roach Motel / Forced Continuity** — easy in, hard out; silent subscription renewal (the FTC "click-to-cancel" enforcement era).
2. **Sneak into Basket** — pre-added items/fees at checkout.
3. **Drip Pricing / Hidden Costs** — mandatory fees revealed late (§6.5).
4. **Confirmshaming** — guilt-tripped opt-outs ("No thanks, I hate saving money").
5. **Trick Questions** — double-negative opt-outs nobody parses.
6. **Misdirection** — visual weight pushing the business-preferred option; ghost buttons for "decline."
7. **Disguised Ads** — ads styled as content/system UI (the inverse of banner blindness 3.1).
8. **Privacy Zuckering** — tricking users into sharing more than they intend.
9. **Bait & Switch** — the advertised action does something else.
10. **Fake Urgency / Countdown Manipulation** — timers that reset; fake scarcity (9.6's evil twin).
11. **Price Comparison Prevention** — making plans structurally impossible to compare.
12. **Obstruction** — multi-step mazes for cancellation/deletion that the signup flow never imposes.
13. **Nagging** — repeated "dismissible" prompts that never stay dismissed.
14. **Interface Interference** — shading, contrast, and wording that make one choice look "wrong."
15. **Forced Action** — gating basic functionality behind unrelated demands (payments, sharing, ratings).
16. **AI-Specific (2024–2026)** — fake AI personas ("I'm your friend"), fabricated AI urgency, overclaiming accuracy, undisclosed synthetic humans.

### The regulatory reality (as of 2025–2026)
- **FTC (US):** dark-pattern enforcement across subscriptions ("click-to-cancel"), junk fees, and AI overclaiming; the Epic Games settlement (2022; $245M+ customer refunds for dark patterns) set the tone.
- **EU Digital Services Act:** Article 25 explicitly bans dark patterns on online platforms.
- **EU AI Act:** bans AI that manipulates through subliminal techniques or exploits vulnerabilities (prohibitions applicable from Feb 2025).
- **California CPRA and peers:** "dark patterns do not constitute consent."

### The designer's ethics checklist
1. **The mirror test:** would you be comfortable explaining this design to the user, on stage, by name?
2. **Symmetry test:** is leaving as easy as joining? Declining as clear as accepting?
3. **Informed test:** would the user still choose this knowing everything you know?
4. **Grandparent test:** could a distracted, non-expert user parse this screen correctly?
5. **Regulator test:** would this screenshot survive as an FTC/EU complaint exhibit?
6. Honest defaults, honest scarcity, honest urgency — the persuasion of §9 with truthful premises is design; the same mechanics on fabricated premises is a dark pattern.

---

## §15 Applied Playbooks

Five-minute recipes combining the principles above per surface.

### 15.1 Pricing page (SaaS)
- Anchor high → 3 tiers, recommended middle, decoy per 5.8; annual/monthly toggle with annual default and savings framing (5.4/5.6); social proof under plans (9.3); zero-risk line (5.19: money-back); full price visibility (6.5); one accent CTA (1.19).
- **Tripwires:** fake "was" prices, hidden seat math, comparison prevention.

### 15.2 Onboarding (first-run)
- B=MAP audit (7.1): one goal question → personalized empty state; progress bar starting ~20% via honest endowed progress (6.9); teach one feature by *doing* (4.4); first-value moment inside session one (5.13); celebrate completion (1.15); skip paths everywhere (1.21).
- **Tripwires:** forced tour, email gate before any value.

### 15.3 Paywall & trial-ending
- Show trial artifacts as user property (5.16: "your 14 documents"); loss-frame the concrete features lost (5.5) with the exact date; offer downgrade (not just cancel) as door-in-the-face (9.9); cancel flow = respectful, one screen, saves preferences (10.3), exit survey optional.
- **Tripwires:** cancellation mazes (§14.12), guilt copy, silent auto-charge.

### 15.4 Notifications & re-engagement
- Cue anchored to a routine (7.4), payload variable but valuable (7.5), personal data in the message (3.4), progressive permission (10.11), digest + quiet hours built in; kill-or-vary notifications whose open rate flatlines (habituation).
- **Tripwires:** fake-activity social notifications, streak-guilt without freezes.

### 15.5 Search & results
- Information scent in labels (3.12), query suggestions (recognition 1.25), result count + filters that reduce options progressively (1.2), chunked result cards (1.3), empty state teaches a better query, "did you mean" without blame (10.6).

### 15.6 AI feature surfaces
- Disclosure up front (13.9); streaming with cancel (13.12); uncertainty signals on facts (13.11); one-line "why" per output (13.10); verification affordances (13.3); human escalation for high stakes (13.6); capability examples in the empty state; overclaim nowhere (13.14).

### 15.7 Forms & settings
- Defaults carry the decisions (5.7); chunk into steps (1.3); validate on blur, forgive format (1.16); recognition aids (1.25); dangerous settings opt-in with plain-language consequences; progress saved (1.20).

### 15.8 Errors & empty states
- Blame-free message + one action (10.6); empty states as teachers with example content and one CTA (4.10); skeleton first (11.3); recovery over-investment (10.7); end every session — even a failed one — with a clear next step (1.15).

---

## §16 Master Index

**UX Laws:** Aesthetic-Usability 1.1 · Choice Overload 1.2 · Chunking 1.3 · Cognitive Load 1.4 · Doherty Threshold 1.5 · Fitts's Law 1.6 · Flow 1.7 · Goal-Gradient 1.8 · Hick's Law 1.9 · Jakob's Law 1.10 · Miller's Law 1.11 · Occam's Razor 1.12 · Pareto 1.13 · Parkinson's Law 1.14 · Peak-End 1.15 · Postel's Law 1.16 · Serial Position 1.17 · Tesler's Law 1.18 · Von Restorff 1.19 · Zeigarnik 1.20 · Paradox of Active User 1.21 · Selective Attention 1.22 · Weber-Fechner 1.23 · Progressive Disclosure 1.24 · Recognition over Recall 1.25 · Signal-to-Noise 1.26

**Gestalt:** Proximity 2.1 · Similarity 2.2 · Closure 2.3 · Continuity 2.4 · Common Region 2.5 · Figure-Ground 2.6 · Prägnanz 2.7 · Uniform Connectedness 2.8 · Synchrony 2.9

**Attention:** Banner Blindness 3.1 · Change Blindness 3.2 · Inattentional Blindness 3.3 · Cocktail Party 3.4 · Preattentive Processing 3.5 · F-Pattern 3.6 · Z-Pattern/Gutenberg 3.7 · Peripheral Vision/Thumb Zone 3.8 · Visual Hierarchy 3.9 · Mere Exposure 3.10 · Curiosity Gap 3.11 · Information Scent 3.12 · Priming 3.13

**Memory:** Working Memory (~4) 4.1 · Forgetting Curve 4.2 · Spacing Effect 4.3 · Testing Effect 4.4 · Verbatim Effect 4.5 · Picture Superiority 4.6 · Dual Coding 4.7 · Google Effect 4.8 · Misinformation Effect 4.9 · Scaffolding 4.10 · Generation Effect 4.11

**Biases:** Anchoring 5.1 · Availability 5.2 · Affect Heuristic 5.3 · Framing 5.4 · Loss Aversion 5.5 · Status Quo 5.6 · Default Effect 5.7 · Decoy 5.8 · Confirmation 5.9 · Negativity 5.10 · Optimism 5.11 · Planning Fallacy 5.12 · Present Bias 5.13 · Sunk Cost 5.14 · IKEA Effect 5.15 · Endowment 5.16 · Bandwagon 5.17 · Survivorship 5.18 · Zero-Risk 5.19 · Ambiguity Aversion 5.20 · Information Bias 5.21 · Dunning-Kruger 5.22 · Curse of Knowledge 5.23 · Hindsight 5.24

**Behavioral Economics:** Nudge 6.1 · Choice Architecture 6.2 · Mental Accounting 6.3 · Zero-Price 6.4 · Partitioned Pricing 6.5 · Bundling 6.6 · Commitment Devices 6.7 · Fresh Start 6.8 · Endowed Progress 6.9 · Effort Heuristic 6.10

**Motivation:** Fogg B=MAP 7.1 · Ability Factors 7.2 · Hooked Model 7.3 · Habit Loop 7.4 · Variable Rewards 7.5 · Investment/Stored Value 7.6 · Self-Determination Theory 7.7 · Overjustification 7.8 · Progress Principle 7.9 · Streaks 7.10 · Gamification PBL 7.11 · Customization/Ownership 7.12

**Emotion:** Norman's 3 Levels 8.1 · Micro-interactions 8.2 · Voice & Humor 8.3 · Color Psychology 8.4 · Emotional Contagion 8.5 · Peak Moments 8.6 · Anticipation 8.7 · Post-Purchase Reassurance 8.8

**Persuasion:** Reciprocity 9.1 · Commitment & Consistency 9.2 · Social Proof 9.3 · Authority 9.4 · Liking 9.5 · Scarcity 9.6 · Unity 9.7 · Foot-in-the-Door 9.8 · Door-in-the-Face 9.9 · Fear Appeals 9.10

**Trust:** Stanford Credibility 10.1 · Trust Seals 10.2 · Transparency 10.3 · Privacy Control 10.4 · Error Prevention 10.5 · Blame-Free Errors 10.6 · Service Recovery 10.7 · Consistency 10.8 · Third-Party Validation 10.9 · Perceived Security 10.10 · Progressive Permission 10.11

**Time:** Response Limits 11.1 · Optimistic UI 11.2 · Skeletons vs Spinners 11.3 · Progress Bars 11.4 · Operational Transparency 11.5 · Maister's Waiting Principles 11.6 · Duration Neglect 11.7 · Explained Uncertainty 11.8 · Gamified Waits 11.9

**Social:** Conformity 12.1 · Social Comparison 12.2 · FOMO 12.3 · Belonging 12.4 · Collaboration 12.5 · Social Desirability 12.6

**AI-Era:** Algorithm Aversion 13.1 · Algorithm Appreciation 13.2 · Automation Bias 13.3 · Automation Complacency 13.4 · Trust Calibration 13.5 · ELIZA Effect 13.6 · Anthropomorphism 13.7 · Uncanny Valley 13.8 · AI Disclosure 13.9 · Explainability 13.10 · Uncertainty Communication 13.11 · Streaming & Perceived Intelligence 13.12 · Co-Creation/Authorship 13.13 · Manipulative AI & Regulation 13.14 · Conversational UX 13.15

**Ethics:** 16 dark patterns + regulation + checklist — §14.

---

## §17 Sources & Further Reading

**Reference collections**
- Jon Yablonski, *Laws of UX* — lawsofux.com (updated catalog incl. Paradox of the Active User, Selective Attention, Cognitive Bias, Cognitive Load)
- Nielsen Norman Group — nngroup.com (F-pattern, banner blindness, response times, progressive disclosure, dark-pattern research)
- Harry Brignull, *Deceptive Patterns* (2023) — deceptive.design; Colin Gray et al., "The Dark (Patterns) Side of UX Design" (CHI 2018)
- Stanford Persuasive Tech Lab — Web Credibility Guidelines (Fogg et al.)

**Foundational books**
- Kahneman, *Thinking, Fast and Slow* (2011) · Thaler & Sunstein, *Nudge* (2008) · Ariely, *Predictably Irrational* (2008)
- Cialdini, *Influence: The Psychology of Persuasion* (7th ed., 2021 — Unity added) · *Pre-Suasion* (2016)
- Norman, *Emotional Design* (2004) & *The Design of Everyday Things* · Csikszentmihalyi, *Flow* (1990)
- Fogg, *Persuasive Technology* (2003) & *Tiny Habits* (2019) · Eyal, *Hooked* (2014) & *Indistractable* (2019)
- Duhigg, *The Power of Habit* (2012) · Heath & Heath, *The Power of Moments* (2017) · Amabile & Kramer, *The Progress Principle* (2011) · Maister, *The Psychology of Waiting Lines* (1985)

**Key papers**
- Miller (1956) "The Magical Number Seven" · Cowan (2001) working-memory capacity · Hick (1952) · Fitts (1954) · Doherty & Sørensen (1988) · Zeigarnik (1927) · von Restorff (1933) · Murdock (1962) serial position · Kurosu & Kashimura (1995) aesthetic-usability
- Iyengar & Lepper (2000) choice overload · Tversky & Kahneman (1974) anchoring · Kahneman & Tversky (1979) prospect theory · Huber, Payne & Puto (1982) decoy · Samuelson & Zeckhauser (1988) status quo · Thaler (1985/1999) mental accounting · Shampanier, Mazar & Ariely (2007) zero price · Morwitz, Greenleaf & Johnson (1998) partitioned pricing
- Hull (1932) goal gradient · Kivetz, Urminsky & Zheng (2006) · Nunes & Drèze (2006) endowed progress · Norton, Mochon & Ariely (2012) IKEA effect · Lepper, Greene & Nisbett (1973) overjustification · Deci & Ryan (1985/2000) SDT · Dai, Milkman & Riis (2014) fresh start · Milkman, Minson & Volpp (2014) temptation bundling · Ariely & Wertenbroch (2002) deadlines · Kruger et al. (2004) effort heuristic
- Buell & Norton (2011) operational transparency · Simons & Chabris (1999) · Simons & Levin (1998) · Zajonc (1968) mere exposure · Loewenstein (1994) information gap · Pirolli & Card (1999) information foraging · Rozin & Royzman (2001) negativity bias · Kruger & Dunning (1999) · Festinger (1954/1957) · Asch (1951) · Przybylski et al. (2013) FOMO · Sparrow, Liu & Wegner (2011) Google effect · Roediger & Karpicke (2006) testing effect · Slamecka & Graf (1978) generation effect · Witte (1992) EPPM · Lee & See (2004) trust in automation
- Dietvorst, Simmons & Massey (2015) algorithm aversion · Logg, Minson & Moore (2019) algorithm appreciation · Skitka & Mosier (1996) automation bias · Weizenbaum (1966) ELIZA · Mori (1970) uncanny valley · Epley, Waytz & Cacioppo (2007) anthropomorphism · Luo et al. (2019) chatbot disclosure

**Regulatory (2024–2026)**
- EU Digital Services Act, Art. 25 (dark patterns) · EU AI Act (2024; manipulative-AI prohibitions applicable Feb 2025) · FTC dark-pattern & AI-claim enforcement actions (2022–2025) · California CPRA (dark patterns ≠ consent)

---

*Compiled 2026-11-15. Coverage: 180+ principles across 15 domains. Every entry pairs the psychology with a concrete web/SaaS/mobile application and a misuse warning — persuasion with truthful premises is design; persuasion on fabricated premises is a dark pattern.*
