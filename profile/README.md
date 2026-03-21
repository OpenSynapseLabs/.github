# Open Synapse Labs
**Intelligence that makes the world better.**

We build AI not to replace humanity — but to amplify it.  
Open Synapse Labs is developing sparse AI models, photonic chips, and EAP-driven robotics — engineered as one unified platform.

---

## Who is behind this

My name is Ilya Osovskoi. I'm 16 years old. I work alone.

I got interested in AI in autumn 2023 — I was studying GPT-2 and tried to build my own model called Zenith. I didn't have enough knowledge or resources back then. Two years later, in late 2025, I started over with a clearer vision. ARCHE3-7B was built over 2.5 months, with zero funding and no team.

**On the code:** ARCHE3-7B was written with the help of Gemini and Claude. I want to be direct about this — without AI coding assistance I could not have written this many scripts in this timeframe. But every algorithm, every architectural decision, every system design came from me. The dopamine learning system, the SmartRouter anti-collapse mechanisms, the ethical core, the photonic chip architecture — these are my ideas, translated into code with AI help.

This is not a bot account. This is not a scam. I'm not trying to take anyone's money.

**My only goal right now is to find a team.**

---

## What I'm building and why

I'm not interested in building another GPT wrapper. The direction is different:

- Intelligence that learns autonomously, not just from backpropagation
- Models that run on consumer hardware, not datacenters
- A photonic chip designed specifically for sparse expert inference
- Eventually: robotics and biotech — but one step at a time

I care about this because I think the way AI is currently being built — centralized, power-hungry, locked behind APIs — is wrong. Not wrong as in "I disagree", wrong as in it leads somewhere bad.

---

## What exists right now

| Project | Description | Status |
|---|---|---|
| **Arche3-7B** | Sparse MoE · 20,480 experts · consumer hardware · working prototype | 🟢 Done |
| **Arche3-35B** | Scaled architecture · VirtualHive · DopamineSystem v2 | 🔵 Architecture ready |
| **Arche3-86B Pro** | Lateral expert networks · internal vector · resonance filter | 🔵 Planned 2027 |
| **ArchePhoton-35 (QPU-1)** | Photonic chip · MZI matrix multiplication · GST phase-change memory | 🟡 Architecture + simulation done |
| **Synapse EAP-Body** | Humanoid robot · EAP musculature + Arche3 neural core | 🔵 Concept 2027+ |

---

## How the key algorithms work

**SmartRouter — anti-collapse routing** (from `hive_router.py`):

```python
# Four mechanisms that prevent routing collapse:
entropy_coeff:  float = 5e-3   # entropy bonus — penalizes peaked distributions
jitter_noise:   float = 1e-2   # noise during training — breaks degenerate paths
temperature:    float = 1.0    # softmax temperature
adaptive_temp:  bool  = True   # learnable temperature

# Aux loss combines both:
aux_loss = (balance_coeff * load_balance_loss
          + entropy_coeff * entropy_penalty)
```

Most MoE models collapse to using 5-10% of their experts. SmartRouter keeps the full 20,480 active.

**Dopamine Learning System** — autonomous curriculum:

```
reward(t) = α·novelty(t) + β·weakness(t) + γ·improvement(t) + δ·ethical_bonus(t)
```

The model decides what to study next based on this signal — not a fixed training schedule.

**Ethical Core** (from `arche3_ethical_core.py`):

```python
'human_protection': 1.0,  # hardwired, not a soft filter
```

Not a system prompt. Not a RLHF fine-tune. A hardwired constraint at the architecture level.

---

## About the code

ARCHE3-7B code is not public yet. I'm not comfortable releasing it while I have no team and no legal structure around the project. If you want to see the code — write to me, tell me who you are and what you need it for, and I'll share it directly.

This is not about secrecy for its own sake. The algorithms are the IP. The weights don't exist yet at scale. The code is the only thing I have right now.

Benchmarks and architecture documentation are fully public — see the repos below.

---

## What I'm looking for

A team. That's it.

Not investors — not yet. Not press. Not partnerships. People who understand what this is and want to build it.

Specifically:
- **ML Research Engineer** — MoE, sparse training, PyTorch, comfortable reading research papers
- **Photonic IC Designer** — MZI layout, GST/PCM memory, IMEC PDK experience
- **RTL / RISC-V Engineer** — custom core, SparseAdamW hardware implementation

This is seed stage. There's no salary right now. If that's a dealbreaker, that's completely fair — I understand. If you're the kind of person who needs to understand everything before committing, I'll answer every question.

📬 **opensynapselabs@proton.me**

---

## Roadmap

**Now → Summer 2026**
- ARCHE3-35B full training run
- ArchePhoton-35 tape-out preparation
- Provisional patent filing
- Seed round: $100–200k

**2027**
- First silicon: AP35-Ω1
- ARCHE3-35B running on photonic hardware
- Series A: $5–15M

**2028+**
- ARCHE3-86B Pro
- Synapse EAP-Body
- ARCHE3-200B Enterprise

---

## Note on availability

I'll be mostly offline for the next week. I'll respond to emails when I'm back.

---

## Links

- 📊 [Benchmarks — arche3-benchmarks](https://github.com/OpenSynapseLabs/arche3-benchmarks)
- 🏗 [Architecture — arche3-architecture](https://github.com/OpenSynapseLabs/arche3-architecture)
- 📄 [Preprint on Zenodo](https://doi.org/10.5281/zenodo.18738608)
- 🌐 [opensynapselabs.github.io](https://silksynapse.github.io/open-synapse-labs/)
- 📬 opensynapselabs@proton.me

---

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.18738608.svg)](https://doi.org/10.5281/zenodo.18738608)

*Built by a human. For humans.*
