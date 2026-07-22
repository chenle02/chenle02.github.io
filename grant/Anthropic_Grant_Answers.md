# Le-AI-Lab — AI for Science: Application Answers

**Project title:** Verified-Informal Mathematics at Scale: Auditable AI-Assisted
Theorem Development for SPDEs

**Field:** Statistical physics (KPZ universality / surface growth), proven with
rigorous stochastic-PDE analysis · **Program:** Anthropic AI for Science — Claude
Science Cohort (Sept 1 – Dec 1, 2026) · **PI:** Le Chen, Auburn University ·
**Application page:** https://chenle02.github.io/grant/

Companion to `Anthropic_Grant.html`. Every factual claim traces to a real
artifact (Le Chen's CV / NSF awards, or a committed system in the Le-AI-Lab and
SPDEs-wiki repositories). No credential is invented; the founder-led structure is
stated plainly rather than dressed as a large staffed group. The science lives in
statistical physics — the surface-growth SPDEs of the KPZ universality class — and
the methodology contributed is trustworthy, AI-verified proof.

---

## Q0 — Website of organization or research group, link to Google Scholar or GitHub

Homepage (Auburn faculty page — publications + CV): https://webhome.auburn.edu/~lzc0090/index.html
· Google Scholar: https://scholar.google.com/citations?user=7CaQ23EAAAAJ&hl=en
· GitHub: https://github.com/chenle02
· ORCID: https://orcid.org/0000-0001-8010-136X
· LinkedIn: https://www.linkedin.com/in/chenle/
· Research group / application page: https://chenle02.github.io/grant/

*(Primary link to enter in the single-line form field:*
`https://webhome.auburn.edu/~lzc0090/index.html` *— the Auburn homepage, which
itself links to publications, CV, Google Scholar, ORCID, and GitHub.)*

---

## Q1 — Research team: expertise and credentials (scientific domain + AI/ML)

**Word count: 281**

Le-AI-Lab is a founder-led research laboratory. Its research team is the
principal investigator, the network of research coauthors he publishes with, and
the AI-orchestration system he designed and operates — a combination that carries
both deep domain authority and hands-on applied-AI engineering.

**Scientific-domain expertise.** Le Chen is Associate Professor in the Department
of Mathematics and Statistics at Auburn University. He earned his PhD in
mathematics from EPFL (Lausanne, Switzerland) under Robert C. Dalang, a leading
figure in stochastic analysis. His research specialty is the stochastic partial
differential equations of surface-growth physics — the stochastic heat and
parabolic Anderson models, KPZ universality, intermittency, and moment
asymptotics — precisely the analysis-heavy mathematical physics this proposal
targets. He has 40+ publications with a broad coauthor network and holds an active
NSF CAREER award (DMS-2443823, 2025–2030), a prior NSF research grant
(DMS-2246850), and Simons Foundation support. He serves as an NSF grant-review
panelist (2023, 2026).

**AI/ML expertise.** Le personally architected and runs a working, verified
AI-research operating system — an orchestrated ensemble of AI builders and
independent adversarial reviewers (Claude Opus alongside GPT, DeepSeek, Qwen,
and other frontier models), disciplined by measured verification gates, a
2,457-page machine-first knowledge graph (1,007 digested papers), and a
self-evolving memory of 713 skills, 601 harvested from lived sessions. This
system has run 236 instrumented, reviewer-gated proof rounds across 10
telemetry-bearing research projects (a "round" = one complete
cycle: builder draft, independent adversarial review, gate verdict, logged
entry; figures as of 2026-07-22, re-derivable from `content/papers/*.md`, the
methodology ledger, and each project's `experiments.tsv`). An earlier year as a
visiting scholar at Microsoft Research Asia grounds
the applied-ML instinct. The team therefore unites the person who knows *where to
aim* with the engineer who *built the instrument*.

---

## Q2 — Key team members using Claude Science (name, title, role)

**Le Chen** — Associate Professor in the Department of Mathematics and Statistics,
Auburn University; Founder, Board Chair, and Principal Investigator of Le-AI-Lab.
Within the broader research team of Q1, Le is the sole human operator **on this
grant project**. He sets the scientific targets (which SPDE theorems, conjectures,
and obstruction maps to attack), designs and runs the multi-agent verified-loop
that orchestrates Claude, adjudicates every reviewer-gated proof round, and is
responsible for all correctness and honesty of the outputs.

This is a founder-led laboratory: the "team" operating under Le is an AI
workforce he architected — Claude in the orchestrator and cold-reviewer roles,
alongside builder and adversary models — plus his standing network of research
coauthors, who validate specific results through normal referee and
collaboration channels. Continuity does not hang on one person's uptime: the
entire workflow is codified in version-controlled runbooks and 713 operational
skills, and the PI's current Auburn PhD advisee will be trained as a backup
operator in the cohort's first weeks (personnel supported by existing
university and grant resources — credits fund compute, not people). Claude
Science credits are used through this system; no other person holds the credit
account.

---

## Q3 — Research project (< 500 words)

**Word count: 476**

**Project: Verified-Informal Mathematics at Scale.**

**Scientific problem.** Most of research mathematics — including stochastic
partial differential equations (SPDEs), the field I work in under an active NSF
CAREER award — is *analysis-heavy* and cannot yet be checked by formal proof
assistants like Lean. These same SPDEs are the mathematical backbone of
surface-growth physics: the stochastic heat equation and KPZ equation govern how
randomly deposited matter builds a rough interface (sand-like *random* vs
snow-like *ballistic* deposition), and the resulting KPZ universality class — the
same universal fluctuation statistics behind crystal growth, flame and forest-fire
fronts, bacterial-colony and tumor margins — is important enough that Giorgio
Parisi shared the 2021 Nobel Prize in Physics for the underlying discoveries.
Trustworthy proofs here therefore feed directly into the reliability of models
the physical and life sciences run on. Frontier AI can draft such proofs
fluently, but a fluent draft that hides one weak step is worse than no proof at
all. The open question this project attacks is methodological and urgent: **can
AI-assisted theorem development in un-formalizable mathematics be made trustworthy
— auditable,
reproducible, and calibrated — rather than merely plausible?**

**Methodology and approach.** I run a role-separated, adversarial verified loop
already in production. Claude (Opus) orchestrates each round and reads it cold;
independent builder and adversary models attempt and attack the proof; a
verification gate accepts, forces rework, or marks the route blocked. A single
authority file (`Progress.md`) keeps every round honest, and per-round telemetry
logs the builder output, review, response, and gate verdict. The system carries a
non-negotiable operating guarantee — it never returns nothing: every problem
yields a **proof, a conditional reduction to a named hypothesis, or a mapped
obstruction**, each a citable, replayable artifact.

The 3-month cohort has three workstreams:
- **W1 — Theorem development in production.** Reviewer-gated proof waves on active
  SPDE problems (moment asymptotics, time-fractional Anderson models, rough-noise
  thresholds), producing submitted preprints with full audit trails.
- **W2 — Calibration against machine truth (the G9-F protocol).** On a small
  *formalizable* corner, Lean 4 serves as a ground-truth oracle to measure
  whether the adversarial gate ever accepts a false statement or rejects a true
  one — turning "trustworthy" from a claim into measured false-accept /
  false-reject behavior on a sealed-label statement bank, reported with honest
  small-sample confidence bounds. Auburn's Easley HPC cluster (~9,400 cores)
  supplies numerical gating where prelimit computation is the right oracle.
- **W3 — Knowledge-commons growth.** Vetted digests and obstruction maps are
  promoted from private staging into the public SPDEs-Bib layer, so credits
  convert into durable, reusable scientific infrastructure.

**Expected outcomes and deliverables.** (1) Submitted SPDE preprints whose proof
rounds carry auditable review trails; (2) a public methodology report
quantifying verified-informal reliability against the Lean oracle; (3) vetted
public knowledge-commons artifacts (digests, obstruction maps) on SPDEs-Bib.

**Timeline (Sept 1 – Dec 1, 2026).**
- **September:** W1 wave 1; W2 corpus selection and baselines.
- **October:** W1 wave 2; W2 Lean calibration runs.
- **November:** methodology report; W3 public promotion; final deliverables.

---

## Q4 — How Claude's capabilities will be used (≤ 300 words)

**Word count: 283**

Claude is the reasoning core of an already-integrated research workflow, not a
side tool: it performs three concrete jobs inside every proof round.

**Orchestration (Claude Opus).** Claude scopes each theorem — its claim,
dependencies, and stop conditions — supervises the round, routes work to builder
and adversary models, and advances the `Progress.md` authority file. It never
edits the proof it is judging, which keeps the reviewer independent of the author.

**Cold-reader adversarial review.** On high-value rounds, a fresh Claude instance
reads the proof with zero prior context and attacks the weakest step, exactly as
a skeptical referee would. This is where Claude's careful long-context reasoning
matters most: catching the plausible-looking but load-bearing gap that fluent AI
drafts hide.

**Calibration and synthesis.** In W2, Claude designs and orchestrates the blind
review panels whose accept/reject decisions are scored against a Lean-4 ground
truth. In W3, Claude synthesizes, reviews, and cold-reads knowledge-base pages
before they are promoted to the public commons.

**A live contest, not a vendor assumption.** Claude Opus currently leads
paper-development orchestration and high-value cold review. GPT-5.6 Sol has
emerged as a formidable challenger for long-horizon, cross-repository
orchestration, while GPT-5.4 High is our strongest current mathematical builder.
Le-AI-Lab judges these routes empirically — by defects caught, rework forced,
closure quality, latency, and cost. Anthropic support would let us test whether
Claude's scientific-judgment advantage persists when capacity no longer forces
fallback routing.

Integration is complete today: Claude runs through the lab's model switchboard
with per-round cost telemetry (`experiments.tsv`), role separation, and honest
deferment doctrine (if a proof cannot close, Claude returns a named hypothesis or
mapped obstruction, never a faked closure). Credits simply keep Claude in the
orchestrator and cold-review roles at full throughput for the cohort window.

---

## Q5 — Acceleration vs. existing methods (≤ 200 words)

**Word count: 156**

Existing tools force a false choice: Lean-style proof assistants give certainty
but cannot yet reach analysis-heavy mathematics like SPDEs, while a raw chatbot
reaches everything but certifies nothing. Claude inside the verified loop closes
that gap — it brings frontier reasoning to un-formalizable proofs *and* runs the
independent adversarial and cold-reader gates that make the output auditable, so
a single mathematician gets the throughput of a small proof-and-referee team.

Concretely, the system has already run 236 instrumented, reviewer-gated proof
rounds across 10 telemetry-bearing research projects; each round that a human
would need hours to draft, attack, and referee is compressed into a logged,
replayable cycle. Claude Science credits remove the single binding constraint on
this speedup: current throughput supply (the
$200/month plan's capacity) is exhausted roughly mid-week under the workload the
system can sustain — credits keep every round at full Claude orchestration and
cold-review quality for the entire cohort, turning a demonstrated method into
sustained scientific output.

---

## Q6 — Potential scientific impact (≤ 200 words)

**Word count: 197**

If successful, this project delivers both new statistical-physics mathematics and
a reusable standard for trustworthy AI-assisted reasoning. The immediate output is
submitted results on the surface-growth SPDEs — the stochastic heat and parabolic
Anderson models in the KPZ universality class — namely proofs, sharp conditional
reductions, and mapped obstructions, each carrying an auditable review trail a
referee can replay. Sharper theorems here deepen understanding of the fluctuation
statistics that govern real interface-growth physics — a field carrying the
discipline's highest honors: Nobel Prizes in Physics to Parisi (2021) and Anderson
(1977, the model's namesake) and a Fields Medal to Hairer (2014) for solving the
KPZ equation.

The larger impact is methodological. Most of the theoretical sciences live in the
analysis-heavy regime that formal proof assistants cannot yet reach. A *measured*,
calibrated standard for verified AI-assisted reasoning there — with false-accept /
false-reject behavior reported against a Lean ground truth — is transferable well
beyond SPDEs. Every run also compounds a public knowledge commons (SPDEs-Bib
digests, obstruction maps) and a self-evolving memory, so outputs are durable
infrastructure, not transient completions. The result is a template for how frontier AI can
extend, not just imitate, rigorous scientific reasoning where formal verification
does not yet exist.

---

## Q6b — Practical applications, societal benefits, and paths to scale (≤ 200 words)

**Word count: 190**

Yes — beyond the mathematics itself, the project's transferable asset is a
*measured standard for trustworthy AI-assisted reasoning* in domains where
formal proof cannot yet reach, which is directly relevant to the broader effort
to make AI reliable in high-stakes technical work — arguably its most practical
societal benefit. The path to scale is already demonstrated, not hypothetical:
the same verified-loop methodology is domain-agnostic (a mathematical field is a
plug-in "adapter," not a rebuild), and a second vertical — graph-theory / combinatorics
censuses on Auburn's HPC cluster — already runs on it, so extension to number
theory, PDE, and other analysis-heavy sciences is a configuration step rather than
new engineering. The mathematics also has concrete applied reach, per my NSF
CAREER program: the surface-growth SPDEs at the core of this work model deposition
and interface processes that matter in semiconductor and pharmaceutical
manufacturing, sediment transport and environmental management, and forest-fire
fronts — so trustworthy proofs raise the reliability of those downstream models.
That program already ships open science (the public SPDEs-Bib bibliography, the
pip-installable `tetris-ballistic` simulator), so this proposal's knowledge commons
— vetted digests, obstruction maps, reusable skills — extends an established
open-source record rather than starting one.

---

## Q7 — Short form fields (fill-in-the-blanks)

| Field | Answer |
|---|---|
| **Name of primary contact** | Le Chen |
| **Organization / institution** | Auburn University (Department of Mathematics and Statistics) — research group: Le-AI-Lab |
| **Position or title** | Associate Professor in the Department of Mathematics and Statistics |
| **Website / Scholar / GitHub** | Homepage: https://webhome.auburn.edu/~lzc0090/index.html · Google Scholar: https://scholar.google.com/citations?user=7CaQ23EAAAAJ&hl=en · GitHub: https://github.com/chenle02 · ORCID: https://orcid.org/0000-0001-8010-136X · LinkedIn: https://www.linkedin.com/in/chenle/ · Application page: https://chenle02.github.io/grant/ |
| **Where did you hear about this program?** | Directly from Anthropic's website — I was actively looking for grant opportunities, Anthropic's in particular, and found the AI for Science / Claude Science program myself. |
| **Project title** | Verified-Informal Mathematics at Scale: Auditable AI-Assisted Theorem Development for SPDEs |
| **Scientific field(s)** | **Tick Physics** (statistical physics — KPZ universality / surface growth) as the primary listed field, and add **Other: Mathematics** (Stochastic Partial Differential Equations / Probability) for the methodology. *Rationale: the scientific objects genuinely are statistical-physics models — the SPDEs of surface growth, in the KPZ universality class recognized by Parisi's 2021 Nobel Prize — so Physics is the honest listed home; Mathematics captures the rigorous-proof method.* |
| **Credits email (claude.ai account)** | chenle02@gmail.com — confirmed as Le Chen's **personal** Claude account (not under any Auburn enterprise or commercial agreement). |
| **Links to Scholar / academic profiles** | Google Scholar: https://scholar.google.com/citations?user=7CaQ23EAAAAJ&hl=en · ORCID: https://orcid.org/0000-0001-8010-136X · Homepage (publications + CV): https://webhome.auburn.edu/~lzc0090/index.html · GitHub: https://github.com/chenle02 · LinkedIn: https://www.linkedin.com/in/chenle/ |

---

## Q8 — Credit amount requested and its impact

**Requested amount: $30,000 in credits (the maximum award).**

The local multi-harness ledger records a 1.06T-token measured floor over 98 active
days (Oct 17, 2025 – Jul 22, 2026), including 1.04T cache-read tokens: about
10.82B tokens per active day and a ~1.97T-token six-month workload extrapolation.
These are workload-volume counts from heterogeneous local logs, not billed-token
equivalence or a complete multi-machine history. The old 62/38 provider snapshot
is therefore retired: current logs are dominated by Codex cache-read telemetry
and do not support an apples-to-apples provider-quality comparison. Current
Claude plan capacity is still exhausted roughly mid-week; the credit ask restores
enough Claude capacity for a matched, outcome-scored cohort test rather than
routing by availability.

The credits convert directly into scientific output, budgeted by workstream with
per-round cost telemetry (`experiments.tsv`) and cost-aware role routing (Opus
reserved for orchestration and high-value cold review; routine builders/adversaries
routed to cheaper capable models):

- **~50% — W1 theorem development:** orchestration, adversarial passes, and Claude
  cold reads per proof round → submitted SPDE preprints with audit trails.
- **~30% — W2 calibration:** blind panels and re-adjudication scored against the
  Lean-4 oracle → the public methodology report.
- **~20% — W3 knowledge commons:** digest waves, obstruction-map synthesis, and
  cold-reader audits → vetted public artifacts on SPDEs-Bib.

Because every round is logged and every artifact is durable (preprints, a
methodology report, public knowledge-base pages), $30,000 in credits funds not
transient completions but a quantified standard for trustworthy AI-assisted
mathematics — plus the concrete SPDE results and public infrastructure it produces.

---

## Q9 — Anything else for the review committee

The strongest point in this application is **feasibility**: this is not a proposal
to build a system, it is a request to keep an *already-running* one at full
quality. The verified loop has completed 236 instrumented, reviewer-gated proof
rounds orchestrated by Claude; the integration risk is near-zero because the
system already runs on Claude's current API — credits change throughput, not
architecture. The project is also trivially clean for biosecurity screening:
theoretical mathematics and statistical physics have no dual-use biological surface
— no biological data, no wet-lab protocols, no pathogen or gain-of-function models.

For a fuller picture of our fit for this program, I have prepared a short,
self-contained application page:

**https://chenle02.github.io/grant/**

It documents the system, the three-month plan, the evaluation-criteria answers,
and the real telemetry (token ledger, HPC census, knowledge-base and skill
metrics) behind every claim above.

---

> **Metrics provenance (as of 2026-07-22).** All quantitative claims are live,
> conservatively rounded, and re-derivable:
> - **1,007 digested papers / 2,457-page KB** — `rg -l '^digested: true$'
>   content/papers --glob '*.md' | wc -l` and `find content -name '*.md' | wc -l`
>   in `SPDEs-wiki`.
> - **713 skills, 601 learned (84%)** — `python3 bin/skills-moat-ledger.py --json`.
> - **236 proof rounds across 10 telemetry-bearing projects** — `python3
>   bin/methodology-ledger.py --json`; 79 are independent adversarial or
>   verification passes, 27 forced rework, and 33 recorded major issues.
> - **1.06T logged-token floor over 98 active days** — `python3
>   bin/token-usage-ledger.py --json`; includes 1.04T cache-read tokens and is a
>   local workload-volume floor, not billed-token equivalence.
