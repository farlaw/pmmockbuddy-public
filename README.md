# PM Mock Buddy

An AI mock-interview coach for product managers.

Practice product sense, execution, metrics, strategy, and behavioral interviews with a follow-up and structured written feedback — not a blank ChatGPT tab.

**Web:** [pmmockbuddy.com](https://pmmockbuddy.com)  
**iOS:** [App Store](https://apps.apple.com/app/id6756758029)  
**Portfolio:** [kirillpm.com](https://kirillpm.com)

This public repository is a product case study. The production source stays private.

I designed and shipped PM Mock Buddy as a working product, using Lovable as an AI development collaborator.

---

## The problem

PM interview prep is high-context and hard to evaluate alone. Peer mocks are useful and scarce. Generic AI chat will happily produce a “perfect” answer without behaving like an interviewer: one question at a time, a real follow-up, time pressure, and critique that is specific enough to change the next rep.

I built PM Mock Buddy to sit between those two: more realistic than a prompt, more available than a friend who can run FAANG-style loops after work.

---

## What it does

1. Pick a **level**, **interviewer persona** (FAANG / startup / retail), **question types**, and **language**.
2. Answer by **voice** or **text**. Voice is transcribed; the answer stays editable.
3. Take **one follow-up** on the same question, the way a real interviewer would.
4. After the set, get a **structured feedback report** — per-question critique, not a single vague score.
5. Come back and run another loop.

Languages: English, Russian, Spanish, French.

---

## Product decisions

**Be an interviewer, not an answer key.** The loop is question → answer → follow-up → feedback. The product should not dump a model essay and call it practice.

**Voice had to work on a phone.** A PM mock that only types is a different product. Recording, transcription, and an always-editable transcript were treated as the experience, not a demo checkbox.

**Feedback has to be usable.** The output is a written report you can reread, not a conversational pep talk that disappears.

**Ship it where candidates already practice.** Same product on the web and iOS, with a limited free allowance and Pro on the App Store.

**AI is the interviewer and the coach — inside a fixed workflow.** Question selection, follow-ups, and feedback are model-assisted. The session structure, limits, and history are product rules.

---

## What this is not

Not a replacement for a strong human mock. Not a claim that the model “grades like Google.” Not an autonomous agent platform.

It is a practice partner for getting more high-quality reps between live interviews.

---

## How it was built

I designed the interview loop, the personas, the voice path, and what “good feedback” had to contain, then built and shipped the web and iOS product with Lovable as an AI coding collaborator.

---

## Screenshots

To add after a sanitization pass (no real emails, account names, or private transcripts):

1. Setup — level, persona, question types.
2. In-interview — question + voice/text answer.
3. Feedback report — structured critique after the session.

Existing App Store captures in this repo should be recaptioned or replaced; do not ship broken image links.

---

## Links

- Web: [pmmockbuddy.com](https://pmmockbuddy.com)
- App Store: [PM Mock Buddy](https://apps.apple.com/app/id6756758029)
- Portfolio: [kirillpm.com](https://kirillpm.com)
