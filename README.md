<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:cc0000&height=200&section=header&text=Viktors%20Baikers&fontSize=56&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Ruby%20on%20Rails%20%E2%80%A2%20Rust%20%E2%80%A2%20Go%20%E2%80%A2%20Self-Hosted%20Infrastructure&descAlignY=58&descSize=18" width="100%"/>

<a href="https://github.com/ViktorsBaikers">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&pause=1000&color=CC0000&center=true&vCenter=true&width=680&lines=I+ship+software+that+stays+up.;Rails+APIs+%E2%80%A2+Rust+systems+%E2%80%A2+Go+tooling;Building+a+terminal+AI+coding+agent+in+Rust;Making+AI+prove+its+code+before+it+ships;Self-hosting+everything+I+can" alt="Typing SVG" />
</a>

<br/>

<img src="https://img.shields.io/badge/Location-Latvia-9E3039?style=for-the-badge&logo=googlemaps&logoColor=white"/>
<img src="https://img.shields.io/badge/Focus-Backend%20%26%20Infra-0f2027?style=for-the-badge&logo=serverless&logoColor=white"/>
<img src="https://komarev.com/ghpvc/?username=ViktorsBaikers&style=for-the-badge&color=cc0000&label=Profile+Views"/>

</div>

---

## About me

I'm a backend engineer from Latvia. I started with **Ruby on Rails** and kept going down the stack: **Rust** for systems and tooling, **Go** for storage and networking, and **Docker/Linux** for everything I run myself.

I build software that is **boring in production**: predictable, observable, well tested and easy to hand off. I hold my own code to a strict bar. In Rust that means `unsafe` forbidden, `unwrap`/`panic` denied at compile time, and supply-chain checks with `cargo-deny`. When a workflow annoys me, I build the tool that fixes it, and then I use it every day.

```ruby
class ViktorsBaikers
  def initialize
    @location   = "Latvia"
    @roots      = %w[Ruby Rails]
    @daily      = %w[Rust Go TypeScript]
    @runs_on    = %w[Docker Linux self-hosted]
    @building   = %w[Rivect DevRites looking-glass]
    @motto      = "If it isn't proven, it isn't done."
  end
end
```

**What I'm working on**

- 🦀 **Rivect**: my own AI coding CLI/TUI, written from scratch in Rust. It is not a fork or a wrapper around another agent. Most agents run a fixed pipeline. Rivect has one adaptive, event-driven harness core that picks the next step from goals, state and evidence. Small tasks stay cheap, and big tasks get a spec, TDD and a live todo list automatically. Every model call gets its own model, effort level, budget and fallback, and the design targets a 97–98% provider cache-read rate on warm runs. It also plans for a unified code graph, LSP, version-aware docs, memory across sessions, and a process that learns from verified outcomes. *Actively in development.* Built so far: a fullscreen TUI and headless JSON-RPC, a sandboxed executor behind policy admission, and provider routing with fallback for OpenAI, Gemini, Alibaba and OpenAI-compatible APIs, with API keys in the OS keychain.
- 🛡️ **DevRites**: an engineering workflow that stops AI agents from shipping half-baked code. Every feature goes spec → plan → build → prove → review → ship, with state on disk and no "done" without proof. Works with Claude Code, Codex and other agents.
- 🌐 **Looking Glass**: a self-hosted network diagnostics console. Rust backend, Svelte UI, one container, and remote agents that enroll over an outbound tunnel.
- ☁️ **Teldrive / rclone**: my own forks of Telegram-backed cloud storage. I added resumable and retried multipart uploads, cursor pagination, bot health diagnostics, and a GHCR/Docker Hub release pipeline.

**What I know well**

- **Backend:** Rails APIs and scrapers, NestJS on Bun, REST and JSON-RPC design, PostgreSQL, Redis, SQLite
- **Systems:** Rust CLIs and TUIs, sandboxing, strict lint and test gates, Go networking and storage clients
- **Infrastructure:** Docker and Compose, CapRover, CI/CD release pipelines, Terraform, Linux servers
- **Hosting:** WHMCS customization, billing and provisioning automation, seedboxes, tuning qBittorrent and libtorrent
- **Media & embedded:** Kodi, CoreELEC and Amlogic Linux builds

**Ask me about:** AI coding workflows, Rust tooling, Rails backends, self-hosting, hosting automation.

---

## Tech stack

<div align="center">

**Languages**<br/>
<img src="https://skillicons.dev/icons?i=ruby,rust,go,ts,js,php,java,bash&theme=dark" />

**Frameworks & Runtime**<br/>
<img src="https://skillicons.dev/icons?i=rails,nodejs,bun,nestjs,react,nextjs,svelte&theme=dark" />

**Data & Infrastructure**<br/>
<img src="https://skillicons.dev/icons?i=postgres,redis,sqlite,docker,linux,nginx,cloudflare,terraform,githubactions&theme=dark" />

</div>

---

## Featured projects

<div align="center">

<a href="https://github.com/ViktorsBaikers/Rivect"><img src="https://img.shields.io/github/languages/top/ViktorsBaikers/Rivect?style=for-the-badge&logo=rust&label=Rivect&color=cc0000"/></a>
<a href="https://github.com/ViktorsBaikers/DevRites"><img src="https://img.shields.io/github/stars/ViktorsBaikers/DevRites?style=for-the-badge&logo=github&label=DevRites&color=203a43"/></a>
<a href="https://github.com/ViktorsBaikers/looking-glass"><img src="https://img.shields.io/github/languages/top/ViktorsBaikers/looking-glass?style=for-the-badge&logo=rust&label=Looking%20Glass&color=0f2027"/></a>

</div>

| Project | What it does |
| --- | --- |
| [**Rivect**](https://github.com/ViktorsBaikers/Rivect) | Native AI coding CLI/TUI, written from scratch in Rust. An adaptive harness core instead of fixed stages, built-in spec and TDD, per-call model and effort routing with fallback, and cache-aware token efficiency. Sandboxed, policy-gated and keychain-secured. *In active development.* |
| [**DevRites**](https://github.com/ViktorsBaikers/DevRites) | Stops AI agents from shipping half-baked code. Spec, plan, build, prove, review and ship, with every step recorded on disk and no "done" without proof. |
| [**Looking Glass**](https://github.com/ViktorsBaikers/looking-glass) | Self-hosted network diagnostics console. One container, a web UI, and remote agents that connect over an outbound tunnel. |

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

Open to backend, infrastructure and automation work. Open an issue on one of my repos or reach out through GitHub.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:cc0000,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>

</div>
