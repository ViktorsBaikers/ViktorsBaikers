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

I'm a backend engineer from Latvia. I started with Ruby on Rails and moved down the stack from there. These days I write Rust for systems and tooling and Go for storage and networking, and I run my own servers on Docker and Linux.

I like software that is boring in production: you can predict it, watch it, and hand it to someone else. My Rust projects forbid `unsafe`, fail the build on `unwrap` or `panic`, and check dependencies with `cargo-deny`. Most of my tools started as fixes for workflows that annoyed me.

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

### What I'm working on

- [Rivect](https://github.com/ViktorsBaikers/Rivect) is my own AI coding CLI/TUI, written from scratch in Rust with no other agent underneath. Where most agents run a fixed pipeline, Rivect's event-driven core picks the next step from the task's goals, current state and evidence so far. A small question stays cheap, while a large feature gets a spec, TDD and a live todo list without the user asking. Each model call has its own model, effort level, budget and fallback, and the design aims for a 97 to 98% provider cache-read rate on warm runs. The plan also covers a code graph, LSP, version-aware docs, memory across sessions, and a process that learns from verified results. It's still in development. The working parts today are a fullscreen TUI, a headless JSON-RPC mode, a sandboxed executor that checks policy before it acts, and provider routing with fallback for OpenAI, Gemini, Alibaba and OpenAI-compatible APIs. API keys live in the OS keychain.
- [DevRites](https://github.com/ViktorsBaikers/DevRites) keeps AI agents from shipping half-baked code. Each feature moves through spec, plan, build, proof, review and ship, the state lives on disk, and the agent can't mark work done until proof is recorded. It works with Claude Code, Codex and other agents.
- [Looking Glass](https://github.com/ViktorsBaikers/looking-glass) is a self-hosted network diagnostics console: a Rust backend and Svelte UI in one container, with remote agents that enroll over an outbound tunnel.
- In my forks of Teldrive and rclone (cloud storage on top of Telegram), I added resumable multipart uploads with retries, cursor pagination, bot health diagnostics, and a release pipeline to GHCR and Docker Hub.

### What I know well

- Backend: Rails APIs and scrapers, NestJS on Bun, REST and JSON-RPC design, PostgreSQL, Redis, SQLite
- Systems: Rust CLIs and TUIs, sandboxing, strict lint and test checks, Go networking and storage clients
- Infrastructure: Docker and Compose, CapRover, CI/CD release pipelines, Terraform, Linux servers
- Hosting: WHMCS customization, billing and provisioning automation, seedboxes, qBittorrent and libtorrent tuning
- Media and embedded: Kodi, CoreELEC and Amlogic Linux builds

Ask me about AI coding workflows, Rust tooling, Rails backends or self-hosting.

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
| [Rivect](https://github.com/ViktorsBaikers/Rivect) | AI coding CLI/TUI written from scratch in Rust. An adaptive core chooses each step, with spec and TDD built in, per-call model and effort routing with fallback, and cache-aware token use. In development. |
| [DevRites](https://github.com/ViktorsBaikers/DevRites) | Keeps AI agents from shipping half-baked code. Every step from spec to ship is recorded on disk, and work counts as done only once proof exists. |
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

I'm open to backend, infrastructure and automation work. Open an issue on any of my repos to get in touch.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:cc0000,50:203a43,100:0f2027&height=110&section=footer" width="100%"/>

</div>
