# Team Charter

<!--
  HOW TO USE THIS FILE TONIGHT

  1. Fill every section. Delete each "> prompt" line as you answer it.
     A leftover prompt is an unanswered section, and your TA reads it that way.
  2. Get your TA to witness the charter and fill in the front matter BELOW,
     BEFORE anyone signs. Editing this file after signing invalidates every
     signature, because signatures are bound to the hash of this text.
  3. Only then: `make charter-hash`, and each member creates their own file in
     docs/charter/signatures/. See Workshop 04, Part 4.1.

  This is a living document. Amend it when it stops describing how your team
  actually works — and log the amendment at the bottom.
-->

| | |
|---|---|
| **Project group number** | PGxx |
| **Track** | Fast / Deep |
| **Members** | |
| **Agreed on** | 1 September 2026 |
| **Witnessed by (TA)** | |

---

## 1.1 Team Purpose and Ambition

> What are you trying to build, and how ambitious is it? A system that is correct, well-instrumented and modest beats one that is ambitious and half-finished — but a team that never commits to a level drifts toward whatever the loudest member last suggested.

**What we are aiming for:**

**Why that level:**

**Our capacity, honestly:**

> Module loads, competing commitments, how many hours a week this team realistically has. A heavy semester is a capacity fact, not a confession — and a charter that ignores it will be wrong by Week 7.

**Our risk tolerance:**

> Would you rather ship something modest that certainly works, or attempt something harder and accept it may not? There is no right answer, but there is a wrong outcome: five people who each assumed a different one.

*This will change once our decomposition is ratified. We will amend it then.*

---

## 1.2 Strengths Map

> Two columns, not one. The second is the half teams omit, and it is the one that stops components being allocated purely on the basis of what people have already done.

| Member | What I have done | What I want to learn |
|---|---|---|
| | | |
| | | |
| | | |
| | | |
| | | |
| | | |

> Be specific. "Python" tells the team nothing in Week 7. "Built a Flask API for a class project; never deployed one" tells them a lot.

---

## 1.3 Working Agreements

**Expected response time:** ____ hours

> 12, 24 or 48. Pick a number. "Reasonably promptly" is not a number, and it is the clause that decides whether silent slippage is visible.

**Meetings — when, where, how long:**

> You have roughly five unsupervised hours between blocks. Say what happens in them.

**Where we talk:**

**Where decisions get recorded:** `docs/decisions/`

> These are usually not the same place. A decision that exists only in a chat thread is a decision nobody can find in Week 11.

**How we decide when we disagree:**

> Consensus is not a decision rule; it is the absence of one. Name what happens when five or six people genuinely disagree and there is no obvious answer.

**Our definition of done.** A piece of work counts as finished when:

- [ ] it is documented well enough that the next person does not need the author
- [ ] it has been reviewed by someone who did not write it
- [ ] it is merged to `main`

> The four above are a **default**, offered because they are what most teams converge on. Adopt them, cut them, or replace them — but decide deliberately, because this list governs when a card may move to Done on your board, and your TA will ask you to point at it.

---

## 1.4 Roles

> Two different kinds of role, and they behave differently. Lecture B, Part 3.

### Coordination roles — these rotate

| Role | Who starts | Rotates |
|---|---|---|
| Project coordination | | |
| Meeting facilitation | | |
| Integration (owns the merge queue) | | |
| Documentation | | |
| Presentation | | |

> Starting points, not silos. Everyone should have run integration at least once by Week 13 — the person who has never merged six branches does not know what the contracts cost.

### Component ownership — this does not rotate

**Status: not yet assigned.**

Our decomposition is not ratified until Workshop 5, so we cannot assign components tonight. Once it is ratified we will amend this section, and that amendment will require every member's signature again.

We agree in advance that:

- each member owns exactly one component for the semester;
- component ownership is the unit of individual technical assessment and is not swapped for convenience;
- the decision layer and the control API are owned by the team, and ______________ convenes them;
- everyone engages with the data and with modelling, whatever they own. Owning monitoring is not a reason never to open the corpus.

---

## 1.5 Conflict and Accountability

> How you will handle problems early, which is the only time handling them is cheap. Your TA will read this section back to you if the team runs into trouble.

**If someone goes quiet — who notices, by when, and what happens:**

> "We would talk to them" is not a mechanism. A mechanism names who raises it, within how long, and what happens if that conversation does not resolve it.

**How concerns are raised:**

> Directly to the person, in the group channel, or through the coordinator?

**When the TA gets involved — and what must have been tried first:**

**When the instructor gets involved:**

**If ambition levels diverge:**

> One member wanting to do far more, or far less, than everyone else is the most common source of trouble in this course and the least often planned for. Say what happens.

---

## 1.6 Ways of Working in the Repository

> This section comes straight out of Week 3. You already have opinions about all of it. The six prevention measures are on your room handout.

**Branch naming convention:**

> Name branches for the work, not the person.

**Branch lifetime — how long before it must be merged or abandoned:**

**Who may merge to `main`:**

**Expected review turnaround:**

**How we merge:** merge commits. **Not squash.**

> This one is not yours to choose. Squashing collapses a branch into a single commit attributed to whoever pressed the button, and individual technical contribution is assessed from this repository's history. Workshop 04, Part 4.3.

**Our notebook rule:**

> Where does logic live? What may be committed as a notebook, and what is stripped before it is? You watched this fail for nearly everyone in Week 3 Part 4.

---

## Amendment log

> Every amendment invalidates all signatures and requires them all again. Log it here so the history is legible — this table is part of the signed text.

| Date | Section | What changed | Why |
|---|---|---|---|
| | | | |

---

**Signatures are not in this file.** Each member signs by creating their own file in `docs/charter/signatures/`, bound to the hash of this text. See Workshop 04, Part 4.1.
