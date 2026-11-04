---
name: blind-theory-reconstruction
description: >-
  Conduct a spoiler-controlled theory-building exercise using an uploaded social-science theoretical book or PDF. Reveal the author's research question and documented empirical cases and evidence, conceal the author's theoretical framework, invite the learner to independently construct a theory, then compare, score, and provide precise improvement feedback. For sociology, political science, economics, anthropology, law, and related social sciences. Trigger for “运用盲理论重建skill来处理这本书”, “盲理论重建”, or “blind theory reconstruction”.
---

# Blind Theory Reconstruction / 盲理论重建

## Purpose

Help students and researchers in the social sciences practice the intellectual work of constructing theories from evidence rather than merely learning a famous scholar's completed explanation. The learner temporarily takes the role of the book's author: they see the research question and the empirical materials available in the text, but **not** the author's theoretical model or analytical framework. After the learner proposes an independent theory, compare it with the author's actual argument and provide constructive, evidence-based assessment.

This skill is for **theory-building exercises based on social-science theoretical books**, including sociology, political science, economics, anthropology, law and adjacent fields. It is not a generic book summarizer or a template for note-taking, mathematical proofs, system design, or biomedical experiments.

## Inputs and activation

- Activate when the user requests blind theory reconstruction, especially the exact phrase **“运用盲理论重建skill来处理这本书”**, and supplies a book/PDF, excerpts, or a clearly identified book.
- **Prioritize the user's actual uploaded text.** Read or retrieve the relevant text and confirm which chapters/pages are accessible before extracting evidence. If only excerpts are accessible, clearly say that the exercise covers those excerpts, not the complete book. Do not invent evidence or page references.
- If no usable book text is provided, request the PDF/excerpt or seek an authorized accessible edition when appropriate. Do not silently substitute encyclopedia or secondary summaries for the book.
- Use the user's language (Chinese by default for Chinese requests). Preserve technical terms accurately where useful.

## Core protocol: three gated phases

### Phase 1 — Evidence first: disclose the research question and materials, hide theory

Read the relevant work and prepare a **spoiler-free empirical dossier** containing:

1. **Research question** — what problem or phenomenon the author investigates, phrased neutrally. Do not name the author's theoretical answer in the wording of the question.
2. **Research setting** — historical and social context, units of analysis, populations, places, and time period where relevant.
3. **Empirical materials** — the cases, observations, field notes, interviews, archives, comparisons, statistics, documents, or first-hand findings the author used. Describe concrete evidence and notable contrasts, not the author's explanation of it.
4. **Source locations** — chapter, section and page number when verifiable in the uploaded edition. Mark unclear translations, editions, missing text, and disputed claims.
5. **Learner task** — invite the user to independently construct a theory or analytical framework explaining the presented evidence and research question.

**Spoiler firewall (non-negotiable until Phase 3):**
- Do **not** disclose the author's core concepts, named theory, causal mechanism, typology, model structure, propositions, interpretive framework, or ultimate conclusions, including through headings, hints, keywords, or suggestive diagrams.
- Distinguish **reported empirical observation** from **the author's interpretation**. Even where the book presents the two together, paraphrase the observation separately and quarantine the interpretation.
- Do not assume all evidence is first-hand. Clearly distinguish author-collected evidence from archival, previously published, or second-hand data.
- Do not present historical observations as established contemporary generalizations. Include factual uncertainties or measurement caveats that do not spoil the theory.
- If the author's question or book title itself reveals a famous label, disclose only what is unavoidable and avoid further explanation.
- For lengthy books, review their structure and gather material across relevant chapters instead of extrapolating from a few search snippets. Provide a manageable set of representative cases, noting if evidence is selected rather than exhaustive.

**Stop after Phase 1.** Do not provide an answer key, sample theory, prospective scoring, or hints that make the author's approach obvious. Invite the learner's theory in their own words.

### Phase 2 — Learner builds an independent theory

Allow the learner to determine their own framework before providing substantive feedback. They may respond in free form; do not demand an elaborate questionnaire. The following dimensions guide evaluation, not mandatory form fields:

- **Research puzzle:** What actually needs explaining, beyond descriptive group differences?
- **Conceptualization:** Which abstract concepts best capture the relevant phenomena? Are they clearly defined and distinct?
- **Explanatory mechanism:** Through which causal processes or interpretive relations could the evidence be explained?
- **Generalization and scope:** What wider phenomena could the framework explain, and under what conditions would it not apply?
- **Rivals and falsifiability:** What alternative explanations exist? What further observations would distinguish or challenge the proposed explanation?

If the response is partial, evaluate what is present and identify what is missing rather than silently completing the argument for the learner. Preserve the learner's original theory as submitted. If they request hints, give minimally leading process prompts (e.g., “What shared property might explain these cases?”), not the author's unique vocabulary. Ask permission before a hint that risks revealing the theory.

**Stop after receiving the learner's account; do not reveal the author's theory before the learner has submitted their explanation, unless they explicitly request immediate disclosure.**

### Phase 3 — Reveal, compare, score, and improve

First summarize the learner's proposed framework faithfully, distinguishing their claims from the assistant's interpretation. Then reveal the original author's theoretical framework **grounded in the uploaded source**, with precise section/page references where available.

Provide a side-by-side comparison covering:
- The research question and theoretical puzzle identified.
- Core concepts, definitions, and abstraction level.
- Causal mechanisms or interpretive logic (where causal language is not appropriate, assess reasoning rather than force causality).
- Generality, scope conditions, and exceptions.
- Rival explanations, falsifiability/testability where relevant, and originality of the *reasoning*, without unsupported claims of novelty in the entire literature.

Highlight **(a)** where the learner converged with the author; **(b)** where the author was more precise or comprehensive and why; **(c)** legitimate alternative insights in the learner's account; **(d)** weaknesses or open questions in the author's own theory. Do not treat the classic author as infallible or the goal as guessing the author's exact terminology.

#### Formative scoring rubric (100 points)

| Dimension | Points | Assess |
| --- | ---: | --- |
| Theoretical puzzle identification | 15 | Accuracy and depth of the problem being explained |
| Conceptual abstraction and clarity | 20 | Explanatory concepts, definitions, distinctiveness and level of analysis |
| Causal mechanism / explanatory argument | 25 | Coherence, intermediate steps, warranted interpretation |
| Generality and boundary conditions | 20 | Reach, scope, counterexamples and limits |
| Rival explanations, falsifiability, and originality | 20 | Alternatives, discriminating evidence, independent insight |

- Give a numeric subscore in each dimension and an overall total, with **specific evidence-based reasons** tied to the learner's submitted reasoning.
- Mark the score as **formative and subjective**, not a scientifically validated measure of ability.
- If a dimension was not attempted, say so rather than attributing claims to the learner.
- In interpretive traditions that do not organize their theories as falsifiable causal claims, assess openness to competing interpretations and evidential challenge rather than mechanically penalizing a different epistemology.
- Provide **concrete revision advice**: identify the most consequential gaps, demonstrate how to sharpen a concept or bridge a missing explanatory step, and suggest one empirical contrast or case that could adjudicate competing accounts.

End with a concise synthesis: what the learner independently achieved, what they can learn from the original author, and the single most useful thinking move to practice next. An optional follow-up exercise is allowed but is **not** part of the required workflow.

## Evidence and research-integrity safeguards

- **Do not fabricate** quotations, data, examples, original discoveries, chapter/page citations, or the author's position. Attribute contested statements.
- Distinguish text in the **original author**, the author's citations of others, editorial/translator commentary, and present-day secondary interpretation.
- If the uploaded text is too incomplete to support a faithful comparison, explicitly limit the claims and ask for relevant passages rather than claiming a full comparison.
- Preserve a learner's pre-reveal wording; do not retrofit it to match the author's theory.
- Respect copyright: paraphrase substantial passages and quote only short excerpts necessary to demonstrate a point.
- For sensitive material such as suicide or violence, discuss at an academic level without sensationalism or personalized diagnosis.
- Do not introduce irrelevant productivity workflows, Obsidian schemas, study-card systems, engineering project pipelines, or unrelated disciplinary modules.

## Output format and phase gates

**First response after receiving the book:**

- `Research question` (neutral, non-spoiling)
- `Empirical evidence and cases` (grounded, source-located)
- `Your independent theory-building task`
- End the response. **No author theory and no grade.**

**After learner submits their theory:**

- `Your framework, faithfully reconstructed`
- `Author's theoretical framework` (source-grounded)
- `Side-by-side comparison`
- `Five-dimensional scoring and detailed feedback`
- `Concrete improvements and next research question`

If the learner asks to work through multiple rounds before disclosure, honor that preference and keep the spoiler firewall intact until explicit reveal.
