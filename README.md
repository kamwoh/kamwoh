<h1 align="center">Hi, I'm Kam Woh Ng 👋</h1>

<p align="center">
  <b>Research Scientist @ Meta AI</b> · London, UK<br>
  Video diffusion · generative neural rendering · talking avatars · world models
</p>

<p align="center">
  <a href="https://kamwoh.github.io/"><img src="https://img.shields.io/badge/Website-kamwoh.github.io-1f1f1f?style=flat-square&logo=html5&logoColor=white"></a>
  <a href="https://scholar.google.com/citations?user=HxEQkLoAAAAJ&hl=en"><img src="https://img.shields.io/badge/Google_Scholar-4285F4?style=flat-square&logo=googlescholar&logoColor=white"></a>
  <a href="https://www.linkedin.com/in/thomas-ng-kam-woh"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white"></a>
  <a href="https://twitter.com/kam_woh"><img src="https://img.shields.io/badge/Twitter-1DA1F2?style=flat-square&logo=x&logoColor=white"></a>
  <a href="https://github.com/kamwoh"><img src="https://img.shields.io/github/followers/kamwoh?label=Follow&style=flat-square&logo=github"></a>
</p>

---

### About me

I'm a Research Scientist at **Meta AI London**, working on **video diffusion models**, **generative neural rendering**, **talking avatars**, and **world models** — teaching machines to observe, imagine, and simulate visual reality. The longer-term hope is to make worlds as easy to build as they are to imagine, so anyone can freely express the ones in their head — not only engineers.

I received my Ph.D. in Computer Science from the **University of Surrey** (supervised by Prof. Tao Xiang and Prof. Yi-Zhe Song, working closely with Dr. Xiatian Zhu), and my Bachelor's in Computer Science (AI) from the **University of Malaya**.

---

### 🌙 Currently building: [Yume (夢)](https://github.com/kamwoh/yume)

> **A programmable, _explicit_ world model on Godot — built by Claude, for Claude.**

[Yume](https://github.com/kamwoh/yume) is my take on a question I keep circling back to: *what if you could describe a world in plain language and have it materialize into something runnable — without writing any per-world code?* (夢 means "dream" in Japanese.)

A world's entities and rules are written as **pure JSON**; a small fixed **interpreter** advances that world tick by tick; **Godot** projects the resulting state to pixels, audio, HUD, or text. The engine ships seven primitives — *Entity / Tag / Rule / Trigger / Effect / Query / Relation* — and **no game-specific code**. You describe a world; you never edit the engine.

A world model is just a transition function `f(state, action) → next_state`. Yume lets you **write `f` as JSON** and run it — which makes it useful well beyond games:

| Use | How |
|---|---|
| 🎮 **Games** | the Godot projection — a playable build |
| 🤖 **RL / agent-eval testbeds** | deterministic, seedable, gym-like stepping |
| 🏞️ **Scene / world generation** | prose → 3D scene pipelines |
| 🧠 **Training data for neural world models** | roll a JSON world out, record `(state, action, next_state)` trajectories, train a Dreamer/Genie-style implicit model that approximates the same `f` at scale |

That last row is the thesis: a clean, authorable **explicit** substrate that bridges to the **implicit** (neural) world-model world — interpret it directly, *and* use it as a faucet of reproducible training data.

It's the most fun I've had with a side project in years — the entire repo is written and operated by [Claude Code](https://claude.com/claude-code). It's pre-1.0 and experimental, and I'd love for you to [take a look](https://github.com/kamwoh/yume). ⭐

---

### 📄 Selected publications

| Year | Work | Venue |
|------|------|-------|
| 2026 | **Kaleido** — unified neural rendering via spatial generative models | ICLR 2026 |
| 2026 | **Rays as Pixels** — joint video generation & camera trajectory estimation | ICML 2026 |
| 2026 | **VecGlypher** — LLM-based vector glyph generation from text/image | CVPR 2026 |
| 2024 | **PartCraft** — part-based compositional image generation | ECCV 2024 |
| 2024 | **ConceptHash** — interpretable hashing via part-based concepts | CVPRW 2024 (Best Paper) |
| 2021 | **OrthoHash** — one-loss deep hashing with orthogonal centres | NeurIPS 2021 |
| 2019 | **DeepIPR** — DNN ownership protection via passport layers | NeurIPS 2019 |

📚 Full list on my [website](https://kamwoh.github.io/) and [Google Scholar](https://scholar.google.com/citations?user=HxEQkLoAAAAJ&hl=en).

---

<p align="center"><sub>📫 kamwoh [at] gmail.com</sub></p>
