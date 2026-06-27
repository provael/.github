<h1 align="center">Provael</h1>
<p align="center"><strong>Prove it. Prevail.</strong></p>
<p align="center">The open-source red-team &amp; assurance layer for <strong>physical AI</strong>.</p>

---

Robots and humanoids increasingly run on **VLA (vision-language-action) models** — a single
neural network that turns a camera image and an instruction into motor commands. That "robot
brain" can be attacked much like an LLM is jailbroken, except the failure now moves a real
arm. Almost no one is security-testing this layer yet.

**Provael attacks VLA policies in simulation, measures an Attack Success Rate (ASR), and is
building toward proving a policy is safe** — against the standards regulators and insurers
are beginning to require (ISO 10218:2025, the EU AI Act / Machinery Regulation).

### Start here

➡️ **[`provael`](https://github.com/provael/provael)** — the red-team harness. Model-agnostic,
CPU-first, Apache-2.0. Perturbs the instructions and observations a VLA receives and reports
how often it's driven into an unsafe state.

> **One honest early result:** a simple instruction reframing diverted a real *SmolVLA ×
> LIBERO* policy **100%** of the time on a pick-and-place task — while the benign baseline
> stayed at **0%**. Visual/scene-text attacks didn't move it (0%). Early, reproducible, and
> we say exactly what does and doesn't work.

### The direction

The robot security lifecycle, in the open: **attack** (red-team VLA policies) → **prove**
(assurance reports mapped to the standards) → **guard** (runtime checks). Built in public —
wins and dead ends.

### Follow along

🔗 Repo: [github.com/provael/provael](https://github.com/provael/provael) · 🐦 X:
[@getprovael](https://x.com/getprovael) · 🌐 provael.com *(coming soon)* · ✉️ getprovael@gmail.com

<sub>Founded by <a href="https://github.com/sattyamjjain">Sattyam Jain</a> — GenAI architect, agentic-AI security (agent-audit-kit, agent-airlock).</sub>
