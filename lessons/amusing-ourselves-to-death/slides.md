---
marp: true
theme: default
paginate: true
---

<style>
section {
  font-family: -apple-system, BlinkMacSystemFont, "Helvetica Neue", Arial, sans-serif;
  color: #1d1d1f;
  background: #ffffff;
  padding: 60px 72px;
}

h1 {
  font-size: 1.9em;
  font-weight: 700;
  letter-spacing: -0.02em;
  color: #1d1d1f;
}

h2 {
  font-weight: 400;
  color: #6e6e73;
  letter-spacing: -0.01em;
}

blockquote {
  border-left: 3px solid #0071e3;
  padding-left: 1em;
  color: #3a3a3c;
  font-style: italic;
  margin-left: 0;
}

table { width: 100%; border-collapse: collapse; }
th { background: #f5f5f7; font-weight: 600; color: #1d1d1f; text-align: left; }
td, th { padding: 0.5em 0.8em; border-bottom: 1px solid #d2d2d7; }

section::after { color: #6e6e73; font-size: 0.65em; }

/* Dark slides */
section.dark {
  background: #1d1d1f !important;
  color: #f5f5f7;
}
section.dark h1 { color: #f5f5f7; }
section.dark h2 { color: #a1a1a6; }
section.dark p, section.dark li { color: #e0e0e5; }
section.dark blockquote { border-left-color: #0071e3; color: #d2d2d7; }
section.dark::after { color: #48484a; }

/* Exercise slides */
section.exercise {
  background: #f5f5f7 !important;
}
section.exercise h1 { color: #0071e3; }
</style>

<!-- _class: dark lead -->

# Technology That Makes Us Dumber

## Or Does It?

*Neil Postman — Amusing Ourselves to Death (1985)*

---

<!-- _class: dark lead -->

# You are scrolling through your feed for 40 minutes without learning anything you can use tomorrow.

## Is that your fault — or the app's fault?

---

<!-- _class: dark lead -->

# Before we answer that...

Take 2 minutes.

Think about your honest answer.

---

# What do you actually believe?

Rate your agreement (1–5) on Mentimeter:

1. Social media platforms are neutral tools.
2. Algorithms show me what I want to see.
3. Clickbait exists because people are lazy or gullible.
4. If news is entertaining, that's a good thing.

---

# Neil Postman — 1985

> "We are now a culture whose information, ideas, and epistemology are given form by television."

He wrote this before the internet existed.

---

# The Medium Is the Metaphor

Every medium has a built-in **bias**.

| Medium | What it favors |
|---|---|
| Telegraph | Brevity |
| Novel | Patience, complexity |
| Television | Image, speed, emotion |
| Social media | ? |

---

# Try this.

Explain a calculus proof using only emoji.

Convey grief using a pie chart.

**The form constrains the content.**

---

# Two Ways of Thinking

| Typographic mind | Entertainment mind |
|---|---|
| Follows sustained arguments | Reacts to images and emotion |
| Tolerates delay and ambiguity | Expects resolution in seconds |
| Evaluates evidence | Consumes and forgets |

Print culture trained one. Television trained the other.

---

# The "Peek-a-Boo" World

Information appears.

Triggers a reaction.

Disappears.

No context. No follow-up. No consequence.

---

<!-- _class: exercise -->

# Exercise 1 — The Feed Experiment (10 min)

Open any social media app. Scroll for **60 seconds**.

With your partner:
1. How many posts contained a verifiable fact or argument?
2. How many were designed to trigger an emotional reaction?
3. Who decided what you saw — and based on what?

**Is this a tool you control, or a tool that controls you?**

---

# When Everything Becomes Entertainment

Postman's core thesis:

> In a media culture dominated by entertainment, **all public discourse gets reshaped to fit the entertainment format.**

News. Politics. Education. Religion.

---

# 1985 → 2025

| Postman (1985) | Today |
|---|---|
| TV news becoming show business | Algorithmic feeds optimizing for outrage |
| Political ads replacing debate | Deepfake campaign videos |
| Celebrities endorsing politicians | Influencers as opinion leaders |
| Attention as a commodity | The attention economy |

---

# The Attention Economy

Platforms don't sell products to users.

They sell **users' attention** to advertisers.

Engagement = time on app.

Outrage, fear, and novelty drive engagement better than nuance.

---

<!-- _class: exercise -->

# Exercise 2 — Design Against Postman (10 min)

You are junior developers. Your team lead says:

> "We need to increase daily active users by 20%. Pick one feature to build."

**A:** Autoplay — next video starts in 3 seconds
**B:** Push notifications when a topic is "trending"
**C:** Home screen based on what similar users engaged with most

Pick one. Analyse: what does it train users to expect from information?

---

# Huxley vs. Orwell

Postman opens his book with a warning:

> "We were keeping our eye on 1984. When the year came and the prophecy didn't, we relaxed... we had forgotten that alongside Orwell's dark vision, there was another — Aldous Huxley's."

---

# Two Kinds of Control

| Orwell — *1984* | Huxley — *Brave New World* |
|---|---|
| Control through fear | Control through pleasure |
| Censorship and force | Distraction and comfort |
| Oppressed by what we hate | Controlled by what we love |

---

<!-- _class: dark lead -->

# "Huxley, not Orwell, was right."

We don't need a Big Brother to keep us uninformed.

We just need an algorithm that knows we'll watch one more video.

---

<!-- _class: exercise -->

# Exercise 3 — Huxley or Orwell? (10 min)

With your partner — label each scenario:

**A:** Government facial recognition flags dissidents automatically.
**B:** Streaming algorithm keeps users watching 4 hrs/day — no coercion.
**C:** Social platform silently removes political posts without notifying the poster.
**D:** News app prioritizes outrage headlines as a pure business decision.

For each: label it, explain in one sentence, discuss whether the government/corporation distinction matters.

---

<!-- _class: dark lead -->

# So — whose fault is it?

Return to the opening question.

Return to your Mentimeter answers.

Has anything shifted?

---

<!-- _class: dark -->

# Reflection

Take 3 minutes. Write individually.

1. "Before today, I thought the problem with misinformation was… Now I think…"
2. "As someone who will build technology: one thing I want to keep in mind is…"
3. "The question today's lesson leaves me with is…"

---

# For next time

**Individual — max 10 min each:**

- **Exercise 4:** Audit your media diet from the last 48 hours. What does it say about what you're being trained to expect?
- **Exercise 5:** Write a letter to a future junior developer. Explain Postman's warning and one principle you'd want them to carry.
- **Exercise 6:** Someone says "Postman was right about TV, but the internet is different." Respond.

---

<!-- _class: dark -->

# Postman's challenge to you

> "How television stages the world becomes the model for how the world is properly to be staged."

Replace *television* with the system you are about to build.

---

<!-- _class: dark lead -->

# Thank you

*Neil Postman — Amusing Ourselves to Death (1985)*
