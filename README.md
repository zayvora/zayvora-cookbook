# 🧠 Zayvora Stack — Community Cookbook

<div align="center">
  <img src="https://img.shields.io/badge/Zayvora-Reasoning%20Engine-6366f1?style=for-the-badge&logo=buffer&logoColor=white" alt="Zayvora" />
  <img src="https://img.shields.io/badge/Status-Active-22c55e?style=for-the-badge" alt="Active" />
  <img src="https://img.shields.io/badge/Local--First-Sovereign%20AI-f59e0b?style=for-the-badge" alt="Local First" />
  <img src="https://img.shields.io/badge/Bharat--First-Built%20in%20India-ff6b35?style=for-the-badge" alt="Bharat First" />
</div>

<br />

<div align="center">
  <h3>⚙️ Build sovereign AI agents. Run them anywhere. Own your stack.</h3>
  <p>An open collection of agents, tools, and research templates built on the Zayvora reasoning engine.</p>

  <a href="https://daxini.xyz" target="_blank">
    <img src="https://img.shields.io/badge/🔥%20Explore%20Zayvora-daxini.xyz-6366f1?style=for-the-badge&labelColor=1f2937" alt="Explore Zayvora" />
  </a>
  &nbsp;
  <a href="https://viadecide.com" target="_blank">
    <img src="https://img.shields.io/badge/🧭%20ViaDecide-Decision%20Engine-f59e0b?style=for-the-badge&labelColor=1f2937" alt="ViaDecide" />
  </a>
</div>

<br />

---

## 📋 Table of Contents

- [What is Zayvora?](#-what-is-zayvora)
- [Quick Start](#-quick-start)
- [Official Templates](#-official-templates)
- [Community Agents](#-community-agents)
- [Community Templates](#-community-templates)
- [The 6-Stage Reasoning Loop](#-the-6-stage-reasoning-loop)
- [Contributing](#-contributing)
- [Leaderboard](#-leaderboard)

---

## 🤔 What is Zayvora?

Zayvora is a **local-first, sovereign AI reasoning engine** — a fine-tuned Llama 3.1 8B model running via Ollama, designed to think in structured loops rather than single-shot completions.

Every Zayvora reasoning run goes through **6 stages**:

```
Decompose → Retrieve → Synthesize → Calculate → Verify → Revise
```

No vendor lock-in. No cloud dependency. Runs on your machine, your server, your infra.

**Model handle:** `daxini2404/zayvora` on Ollama

---

## ⚡ Quick Start

```bash
# 1. Pull the Zayvora model
ollama pull daxini2404/zayvora

# 2. Run a reasoning query
ollama run daxini2404/zayvora "Analyze the impact of RSU spacing on V2X latency"

# 3. Or clone any template below and start building
git clone https://github.com/zayvora/<template-name>.git
```

---

## 💡 Official Templates

<div align="center">
  <img src="https://img.shields.io/badge/Official%20Templates-Built%20by%20the%20Core%20Team-4F46E5?style=for-the-badge" alt="Official" />
</div>

<br />

<table>
  <tr>
    <th width="200">🎯 Project</th>
    <th width="400">📝 Description</th>
    <th width="200">🏷️ Tags</th>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/zayvora/nex">
        <img src="https://img.shields.io/badge/nex-1f2937?style=for-the-badge&logo=github" alt="nex" />
      </a>
    </td>
    <td>
      <b>Nex — Deep Research Engine.</b> Autonomous research agent that transforms a natural-language question into a structured, evidence-backed report by querying 10–100 open-access sources, verifying claims, and building a knowledge graph.
    </td>
    <td>
      <img src="https://img.shields.io/badge/research-blue?style=flat-square" />
      <img src="https://img.shields.io/badge/rag-purple?style=flat-square" />
      <img src="https://img.shields.io/badge/knowledge--graph-green?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/zayvora/zayvora-agent">
        <img src="https://img.shields.io/badge/zayvora--agent-1f2937?style=for-the-badge&logo=github" alt="zayvora-agent" />
      </a>
    </td>
    <td>
      <b>Base Agent Template.</b> Minimal scaffold for building a Zayvora-powered agent. Includes the 6-stage reasoning loop, tool routing, and streaming output. Fork this to build anything.
    </td>
    <td>
      <img src="https://img.shields.io/badge/agent-blue?style=flat-square" />
      <img src="https://img.shields.io/badge/scaffold-gray?style=flat-square" />
    </td>
  </tr>
  <tr>
    <td>
      <a href="https://github.com/zayvora/zayvora-highway-v2i">
        <img src="https://img.shields.io/badge/zayvora--highway--v2i-1f2937?style=for-the-badge&logo=github" alt="highway-v2i" />
      </a>
    </td>
    <td>
      <b>Highway V2I Simulation Lab.</b> Research simulation environment for Vehicle-to-Infrastructure (V2I) communication. Models RSU placement, DSRC/C-V2X latency, and traffic optimization using Zayvora's numerical modeling tools.
    </td>
    <td>
      <img src="https://img.shields.io/badge/simulation-blue?style=flat-square" />
      <img src="https://img.shields.io/badge/v2i-orange?style=flat-square" />
      <img src="https://img.shields.io/badge/research-green?style=flat-square" />
    </td>
  </tr>
</table>

<br />

---

## 🤝 Community Agents

<div align="center">
  <p>Agents built by the community using the Zayvora platform.</p>
  <img src="https://img.shields.io/badge/Community%20Agents-Growing-FF6B6B?style=for-the-badge" alt="Community" />
</div>

<br />

<table>
  <thead>
    <tr>
      <th>Agent</th>
      <th>Description</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td colspan="2" align="center"><i>Be the first. <a href="#-contributing">Submit your agent →</a></i></td>
    </tr>
  </tbody>
</table>

---

## 🚀 Community Templates

<div align="center">
  <img src="https://img.shields.io/badge/Community%20Templates-Open%20for%20Submissions-22c55e?style=for-the-badge" alt="Community Templates" />
</div>

<br />

<table>
  <tr>
    <th width="200">🎯 Project</th>
    <th width="100">⭐ Stars</th>
    <th width="400">📝 Description</th>
    <th width="150">🏷️ Tags</th>
  </tr>
  <tr>
    <td colspan="4" align="center"><i>Submit a PR with your project to get listed here.</i></td>
  </tr>
</table>

<br />

---

## 🔄 The 6-Stage Reasoning Loop

Every agent built on Zayvora inherits this reasoning architecture:

```
┌─────────────┐     ┌──────────┐     ┌───────────┐
│  Decompose  │────▶│ Retrieve │────▶│ Synthesize│
└─────────────┘     └──────────┘     └───────────┘
                                            │
┌─────────────┐     ┌──────────┐           ▼
│   Revise    │◀────│  Verify  │◀────┌───────────┐
└─────────────┘     └──────────┘     │ Calculate │
                                     └───────────┘
```

| Stage | What it does |
|-------|-------------|
| **Decompose** | Breaks the query into sub-questions and a research plan |
| **Retrieve** | Pulls evidence from configured sources (web, local docs, APIs) |
| **Synthesize** | Merges evidence into a coherent intermediate answer |
| **Calculate** | Runs numerical / simulation tools when needed |
| **Verify** | Cross-checks claims against source domains, assigns confidence |
| **Revise** | Refines the output if verification flags contradictions |

---

## 🤝 Contributing

We welcome agents, tools, research templates, and integrations.

### How to Contribute

1. **Fork this repo** and create your feature branch
2. **Build your project** using the Zayvora agent scaffold or Nex as a base
3. **Add these topics** to your repository:
   - `zayvora-community`
   - `zayvora-<your-domain>` (e.g. `zayvora-research`, `zayvora-agent`, `zayvora-simulation`)
4. **Make your repo public**
5. **Submit a pull request** to this repo adding your entry to the Community Templates table

### Topic Tag System

| Domain | Tag |
|--------|-----|
| Research & RAG | `zayvora-research` |
| Autonomous agents | `zayvora-agent` |
| Simulation | `zayvora-simulation` |
| Education | `zayvora-education` |
| B2B / automation | `zayvora-b2b` |
| Hardware / IoT | `zayvora-hardware` |

### Troubleshooting

<details>
<summary><b>My contribution doesn't appear in the list</b></summary>

Check the following:

- ✅ Repository is set to **public**
- ✅ Added topic **`zayvora-community`** to your repo
- ✅ Submitted a PR to this repo updating the Community Templates table
- ✅ If still missing, [raise an issue](https://github.com/zayvora/awesome-zayvora/issues/new)

</details>

---

## 🏆 Leaderboard

See top contributors and most-forked community templates:

👉 [View Leaderboard](./leaderboard/README.md)

---

## 🔗 Zayvora Ecosystem

| Product | Link | Description |
|---------|------|-------------|
| Daxini.xyz | [daxini.xyz](https://daxini.xyz) | AI Research OS / Mothership portal |
| Daxini.space | [daxini.space](https://daxini.space) | Spatial OS PWA |
| ViaDecide | [viadecide.com](https://viadecide.com) | Decision Engine |
| Nex | [github.com/zayvora/nex](https://github.com/zayvora/nex) | Deep Research Engine |
| Orchade | coming soon | Farming game + social OS |
| StudyOS | coming soon | AI-native study environment |

---

## 📄 License

MIT — build freely, ship boldly.

---

<div align="center">
  <h3>⚙️ Ready to build something sovereign?</h3>

  <a href="https://daxini.xyz">
    <img src="https://img.shields.io/badge/Get%20Started-daxini.xyz-6366f1?style=for-the-badge&logo=rocket&logoColor=white" alt="Get Started" />
  </a>

  <br /><br />

  <p>Built with 🔥 from Kutch, India — for the world.</p>

  <img src="https://img.shields.io/github/stars/zayvora/awesome-zayvora?style=social" alt="Stars" />
  &nbsp;
  <img src="https://img.shields.io/github/forks/zayvora/awesome-zayvora?style=social" alt="Forks" />
</div>
