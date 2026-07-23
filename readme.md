# Aaron Godoy
**Independent AI Researcher*
**West Sacramento, Ca**
**aaron.godoy.research@gmail.com**

# The Problem in One Sentence
LLMs don't read. They pattern-match. Feed a model a new book, and it ignores the text - defaulting to quotes
it memorized during training. This isn't "reasoning." It's stubborn statistical parroting.

### Why LLMs Don't Read | The Stubbornness Problem
In a controlled test, Gemini 3.1 Pro was given a PDF of Yuval Harari's Sapiens and asked for five key quotes. Despite full document access, the model returned the same five quotes it already knew from training—completely bypassing the provided text.

Same with instruction: tell it to avoid a specific concept, and it agrees—then quietly reintroduces it later.

This is parametric stubbornness. The model defaults to its training data even when better information is right in front of it. Chain‑of‑Thought becomes meaningless—just a probabilistic defense of training bias.

# The Solution: Rene‑Deskeptic
I'm architecting a framework that forces LLMs to doubt their own knowledge and forensically verify against provided context. The architecture integrates Cartesian doubt directly into the model's loss functions and inference protocols.

📄 One‑Page Research Brief → (https://github.com/Kikingodoy/Kikingodoy/blob/77097d6b3097fc086f767abbe95c7f1ae9ef5dbd/Rene-Deskeptic_Research_Brief_AaronGodoy.pdf)


* **Objective:** Reduce LLM hallucinations by mandating strict causal deduction and adversarial self-critique.
