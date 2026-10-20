<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:cc0000&height=200&section=header&text=Viktors%20Baikers&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Staff%20Software%20Engineer%20%E2%80%A2%20AI%20Agents%20%E2%80%A2%20Full%20Stack%20%E2%80%A2%20Self-Hosted&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/ViktorsBaikers">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=CC0000&center=true&vCenter=true&width=680&lines=Staff+Software+Engineer+from+Riga;Banking%2C+AdTech+and+government+systems;Building+AI+agents+and+developer+tooling;Making+AI+prove+its+code+before+it+ships;Self-hosting+everything+I+can" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Location-Riga%2C%20Latvia-9E3039?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/Focus-Full%20Stack%20%26%20AI-0f2027?style=for-the-badge&logo=serverless&logoColor=white"/>
<img src="https://img.shields.io/badge/Open%20to-Relocation-203a43?style=for-the-badge"/>
<a href="https://www.linkedin.com/in/viksb/"><img src="https://img.shields.io/badge/LinkedIn-viksb-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
<img src="https://komarev.com/ghpvc/?username=ViktorsBaikers&style=for-the-badge&color=cc0000&label=Profile+Views"/>

</div>

---

## About me

I'm a Staff Software Engineer from Riga, Latvia. I've spent over a decade building and modernising applications for banking, AdTech and government. I work across front end, back end and DevOps, and I design the system architecture and integrations around them. In technical lead roles I've made the architecture decisions and optimised existing systems.

Lately most of my work is AI-driven development: I build AI agents, automation workflows and developer tooling that speed up engineering teams. I also want that AI to prove its code before it ships, which is why I built DevRites.

Outside work I write Rust and Go and self-host most of what I use on Docker and Linux. My Rust projects forbid `unsafe`, fail the build on `unwrap` or `panic`, and check dependencies with `cargo-deny`.

```ruby
class ViktorsBaikers
  def initialize
    @role       = "Staff Software Engineer"
    @location   = "Riga, Latvia"
    @roots      = %w[Ruby Rails]
    @daily      = %w[Go Rust TypeScript Svelte]
    @building   = %w[Boxset DevRites Rivect looking-glass]
    @open_to    = %w[relocation remote hybrid B2B]
    @motto      = "If it isn't proven, it isn't done."
  end
end
```

### Experience

Most recently I was a Staff Software Engineer at DotiDot, an e-commerce SaaS platform for multichannel advertising, where I introduced AI-assisted development to the team. Before that I led a team of 3 on Autentica's online banking platform for corporate customers, owning the architecture, the banking API and electronic ID integrations, and production incidents. Earlier I was tech lead on a government territorial planning system at CatchSmart and built cadastral systems for the Latvian State Land Service at Visma Consulting. I started out doing freelance web work in 2014.

Certificates: Claude Certified Developer: Foundations (Anthropic) · Ruby Association Certified Ruby Programmer Silver

The full history is on [LinkedIn](https://www.linkedin.com/in/viksb/).

### What I'm working on

- [Boxset](https://github.com/ViktorsBaikers/Boxset) is one self-hosted app for a movie, TV and anime library. It tracks wanted titles, finds releases through indexers, sends them to download clients, then imports, renames and upgrades the files and keeps media servers up to date. Anime gets its own numbering and metadata, and an existing setup can be imported or kept in two-way sync. The backend is Go on SQLite and the UI is SvelteKit with Tailwind. I'm building it milestone by milestone through DevRites, and it's still in development.
- [DevRites](https://github.com/ViktorsBaikers/DevRites) is a workflow for AI coding agents that lives in your repository. It takes a feature from spec and plan through code, recorded proof and a release decision, and nothing ships without proof and a human go-ahead. The state stays in `.devrites/`, so it survives a cleared chat or a switch of tools. It runs in Claude Code, Codex, omp, pi and Devin CLI, installs from npm, and has a site at [devrites.com](https://devrites.com).
- [Rivect](https://github.com/ViktorsBaikers/Rivect) is my AI coding CLI/TUI, written from scratch in Rust. Its event-driven core picks the next step from the task's goals and the evidence so far, so a small question stays cheap and a large feature gets a spec, TDD and a live todo list. It's in development; the fullscreen TUI, headless JSON-RPC mode, sandboxed executor and provider routing with fallback work today.
- [Looking Glass](https://github.com/ViktorsBaikers/looking-glass) is a self-hosted network diagnostics console: a Rust backend and Svelte UI in one container, with remote agents that enroll over an outbound tunnel.
- In my forks of Teldrive and rclone (cloud storage on top of Telegram), I added resumable multipart uploads with retries, cursor pagination, bot health diagnostics, and a release pipeline to GHCR and Docker Hub.

### What I know well

- Architecture: system design, enterprise integrations, banking APIs and electronic identification, technical leadership
- Full stack: Ruby on Rails, Go, Rust, Java, Node.js, TypeScript, React, Next.js, Svelte, REST, GraphQL and JSON-RPC
- AI: AI agents, LLM integration, automation workflows and developer tooling
- Data: PostgreSQL, Redis, SQLite
- DevOps: Docker and Compose, CI/CD release pipelines, Terraform, Linux servers, on-call production support
- Hosting and media: WHMCS automation, seedboxes, libtorrent tuning, Kodi and CoreELEC builds

Ask me about AI coding workflows, architecture, Rails and Go backends, or self-hosting.

---

## Tech stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=ruby,go,rust,java,ts,js,php,bash&theme=dark" />

**Frameworks & Runtime**<br/>
<img src="https://skillicons.dev/icons?i=rails,nodejs,bun,nestjs,react,nextjs,svelte,tailwind,vite&theme=dark" />

**Data & Infrastructure**<br/>
<img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,docker,linux,nginx,cloudflare,terraform,githubactions&theme=dark" />

</div>

---

## Featured projects

<div align="center">

<a href="https://github.com/ViktorsBaikers/Boxset"><img src="https://img.shields.io/badge/Boxset-Go%20%2B%20Svelte-cc0000?style=for-the-badge&logo=go&logoColor=white"/></a>
<a href="https://github.com/ViktorsBaikers/DevRites"><img src="https://img.shields.io/github/stars/ViktorsBaikers/DevRites?style=for-the-badge&logo=github&label=DevRites&color=203a43"/></a>
<a href="https://github.com/ViktorsBaikers/Rivect"><img src="https://img.shields.io/github/languages/top/ViktorsBaikers/Rivect?style=for-the-badge&logo=rust&label=Rivect&color=0f2027"/></a>
<a href="https://github.com/ViktorsBaikers/looking-glass"><img src="https://img.shields.io/github/languages/top/ViktorsBaikers/looking-glass?style=for-the-badge&logo=rust&label=Looking%20Glass&color=0f2027"/></a>

</div>

| Project | What it does |
| --- | --- |
| [Boxset](https://github.com/ViktorsBaikers/Boxset) | One self-hosted app for a movie, TV and anime library, from finding releases to organised files. Go and SQLite backend, SvelteKit UI. In development. |
| [DevRites](https://github.com/ViktorsBaikers/DevRites) | Workflow for AI coding agents. Every step from spec to ship is recorded in the repository, and nothing ships without proof and a human go-ahead. |
| [Rivect](https://github.com/ViktorsBaikers/Rivect) | AI coding CLI/TUI written from scratch in Rust, with an adaptive core, built-in spec and TDD, and per-call model routing with fallback. In development. |
| [Looking Glass](https://github.com/ViktorsBaikers/looking-glass) | Self-hosted network diagnostics console in one container, with remote agents that connect over an outbound tunnel. |

---

## GitHub stats

<div align="center">

<img width="100%" src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=ViktorsBaikers&theme=tokyonight" alt="Profile details" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/stats?username=ViktorsBaikers&theme=tokyonight" alt="Stats" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/most-commit-language?username=ViktorsBaikers&theme=tokyonight" alt="Most commit language" />

<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/repos-per-language?username=ViktorsBaikers&theme=tokyonight" alt="Repos per language" />
<img width="49%" src="https://github-profile-summary-cards.vercel.app/api/cards/productive-time?username=ViktorsBaikers&theme=tokyonight&utcOffset=3" alt="Productive time" />

<img src="https://streak-stats.demolab.com?user=ViktorsBaikers&theme=tokyonight&hide_border=true&background=0d1117" alt="Streak stats" />

</div>

---

<div align="center">

### Let's build something that stays up

I'm open to staff and lead roles in full-stack or AI engineering, on-site, hybrid or remote, and to B2B contracts. I'm based in Riga and open to relocating. Reach me on [LinkedIn](https://www.linkedin.com/in/viksb/).

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:cc0000,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>

</div>
