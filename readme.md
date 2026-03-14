# Aaron Godoy
**Independent AI Researcher | Dual-Enrollment Scholar**
**West Sacramento, Ca**
**aaron.godoy.research@gmail.com**

# The Problem in One Sentence
LLMs don't read. They pattern-match. Feed a model a new book, and it ignores the text--defaulting to quotes
it memorized during training. This isn't "reasoning." It's stubborn statistical parroting.

### Why LLMs Don't Read | The Stubbornness Problem
In a controlled test, Gemini 3.1 Pro was given a PDF of Yuval Harari's Sapiens and asked for five key quotes. Despite full document access, the model returned the same five quotes it already knew from training—completely bypassing the provided text.

Same with instruction: tell it to avoid a specific concept, and it agrees—then quietly reintroduces it later.

This is parametric stubbornness. The model defaults to its training data even when better information is right in front of it. Chain‑of‑Thought becomes meaningless—just a probabilistic defense of training bias.

# The Solution: Rene‑Deskeptic
I'm architecting a framework that forces LLMs to doubt their own knowledge and forensically verify against provided context. The architecture integrates Cartesian doubt directly into the model's loss functions and inference protocols.

**Core Components:**

*Retro‑Search Distillation – Prunes reasoning traces from teacher models to eliminate overthinking while preserving accuracy (31% shorter chains, 7.7% better performance)*

*Epistemic Regret Minimization – Penalizes the model for being right for the wrong reasons by maintaining an explicit causal graph of beliefs*

*Adversarial Self‑Critique & Deep Truth Mode – Generates parallel reasoning tracks, then deploys a hostile critic to destroy all but the most robust logic*

📄 One‑Page Research Brief → (https://github.com/Kikingodoy/Kikingodoy/blob/77097d6b3097fc086f767abbe95c7f1ae9ef5dbd/Rene-Deskeptic_Research_Brief_AaronGodoy.pdf)


* **Objective:** Mitigate LLM hallucinations by mandating strict causal deduction and adversarial self-critique.

**Current Status**
✅ Architectural specifications complete

✅ Mathematical frameworks formalized (ERM loss, Empirical Distrust)

⏳ Seeking GPU sponsorship

⏳ Seeking academic mentorship for fine‑tuning and evaluation

### Academic Context
* **Institution:** Sacramento City College (Dual-Enrollment)
* **Focus:** Bridging the gap between philosophical frameworks (ethics, logic) and frontier computational scale.

### Contact & Collaboration
I'm open to communication with university researchers, AI safety labs, and tech companies focused on determinism and truth-grounded AI.
* **Email:** aaron.godoy.research@gmail.com
* **Location:** West Sacramento, CA
