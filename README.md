# 🔥 NameForge 🔥

_Because letting humans name things was getting boring anyway._

## What is this sorcery?

NameForge is a magical laboratory where we torture characters into forming names that sound plausibly human but are actually created by our AI overlords. Think of it as teaching a robot to become a parent without the 3 AM feedings.

## Why would anyone do this?

Ever been stuck naming:
- Your 17th D&D character?
- A startup that needs to sound both trustworthy and disruptive?
- Your boss's new cat (when you're allergic to cats AND your boss)?

We've got you covered. NameForge uses the dark arts of probability and neural networks to generate names that range from "Huh, that's nice" to "Dear god, what have we done?"

## Current Capabilities

### 🧮 Bigram Magic (`bigram.ipynb`)

Our bigram model learns character-by-character transitions from a dataset of human names, then generates new names with varying levels of sanity:

```
# Sometimes beautiful
"Aria"
"Liam"

# Sometimes questionable
"Xonndafrinerimienlill"

# Sometimes perfect for your next metal band
"Kuej"
```

### 📊 Broadcasting Wizardry (`broadcasting.ipynb`)

A deep dive into PyTorch tensor operations that make our neural models possible. Not as exciting as name generation unless you're REALLY into linear algebra (no judgment here).

## Getting Started

1. Clone this repository of forbidden knowledge
2. Install dependencies with Poetry:
   ```sh
   uv sync
   ```
3. Start with `bigram.ipynb` to summon your first abominations

## Coming Soon

- `mlp.ipynb`: Because we're determined to use neural networks for a task that bigrams already do pretty well 🤷‍♀️
- Character-level RNNs that will generate names so good your friends will think you have taste
- A command-line tool for when you need 10,000 fantasy characters named RIGHT NOW

## Ethical Use Statement

Please don't use NameForge to:
- Name actual human babies (we're not ready for that responsibility)
- Generate usernames for your spam bot army
- Name your company something that sounds like a prescription medication

## Contributions

Found a bug? Have a feature request? Want to add your collection of Elvish names to our training data? Open an issue or PR!

Remember: The best name generators were preemptively banned from naming contests.
