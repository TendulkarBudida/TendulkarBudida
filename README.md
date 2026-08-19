# Tendulkar Budida — GitHub Profile README

## Copy this into your GitHub profile repository's README.md
> **Note**: The Vercel deployment is already live at `github-profile-deploy.vercel.app` — all images should render correctly.

---

# Tendulkar Budida

<img src="https://github-profile-deploy.vercel.app/api/banner" alt="Profile banner" width="100%" />

---

## About Me

<img src="https://github-profile-deploy.vercel.app/api/about" alt="About Me" width="100%" />

---

## Tech Stack

<img src="https://github-profile-deploy.vercel.app/api/tech-stack" alt="Tech Stack" width="100%" />

---

## Quick Stats

<img src="https://github-profile-deploy.vercel.app/api/stats" alt="Quick Stats" width="100%" />

---

## Connect

<img src="https://github-profile-deploy.vercel.app/api/links" alt="Connect" width="100%" />

### Links

[🌐 Portfolio](https://tendulkar.dev) • [💼 LinkedIn](https://linkedin.com/in/tendulkarbudida) • [💻 GitHub](https://github.com/tendulkarbudida) • [📄 Resume](https://tendulkar.dev/resume) • [✉️ Email](mailto:tendulkar@budida.dev)

---

### Featured Projects

- **[AI Agent Orchestrator](https://github.com/tendulkarbudida/agent-orchestrator)** — Multi-agent workflow engine with LangGraph
- **[RAG Pipeline Framework](https://github.com/tendulkarbudida/rag-pipeline)** — Production-ready retrieval-augmented generation
- **[Edge Compute Toolkit](https://github.com/tendulkarbudida/edge-toolkit)** — Low-latency serverless utilities
- **[DevEx CLI](https://github.com/tendulkarbudida/devex-cli)** — Developer experience automation tooling

---

> Built with Next.js + `@vercel/og` • Deployed on Vercel • Cyberpunk aesthetic by design

---

## Deployment Status ✅

**The Vercel deployment is already live!** 🎉

- **Deployment URL**: `https://github-profile-deploy.vercel.app`
- **All 5 API endpoints returning 200 OK**
- **Images render correctly via GitHub's Camo proxy**

### To use this profile:
1. Create a repository named `TendulkarBudida` (must match your GitHub username)
2. Copy the **entire markdown above** into that repo's `README.md`
3. Commit — GitHub will render the profile automatically

### If you want your own deployment:
1. Go to [github.com/TendulkarBudida/github-profile-deploy](https://github.com/TendulkarBudida/github-profile-deploy)
2. Fork the repository
3. Go to [vercel.com](https://vercel.com) → **Add New → Project** → Import your fork
4. Deploy — no configuration needed (Vercel auto-detects the `api/` folder)
5. Update the image URLs in this README to use your new deployment URL

---

## API Endpoints

| Endpoint | Size | Description |
|----------|------|-------------|
| `/api/banner` | 1500×900 | Hero banner with name, role, tagline, stats, tech tags |
| `/api/about` | 1500×600 | Bio, focus areas, interest tags |
| `/api/tech-stack` | 1500×1000 | 5 categories × 6 technologies each |
| `/api/stats` | 1500×400 | 4 metric cards (years, projects, production, AI) |
| `/api/links` | 1500×500 | 5 connect buttons + Markdown reminder |

All routes return valid PNG via `@vercel/og` with `runtime = 'nodejs'`.

---

## Local Development

```bash
cd github-profile-deploy
npm install
npm run dev
```

Then test endpoints at `http://localhost:3000/api/banner`, `/api/about`, etc.

---

## Customization

Edit the JSX/inline styles in `src/app/api/*/route.ts` to change colors, text, tags, spacing, etc. Every push to GitHub auto-redeploys on Vercel.