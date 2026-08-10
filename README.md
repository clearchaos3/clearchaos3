<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=28&pause=1000&color=10B981&center=true&vCenter=true&random=false&width=600&lines=Full-Stack+Developer;Native+macOS+Builder;Solo+Founder;Shipping+Products" alt="Typing SVG" />

# Ryan Lee

**Developer & Solo Founder** · St. Louis, MO

I build and ship products solo. No team, no funding, no excuses.

Every project below is real and shipped — live sites serving users, native apps running every day.

<a href="https://swarmtorrent.com"><img src="https://img.shields.io/badge/Swarm-live-10B981?style=for-the-badge" /></a>
<a href="https://movenumbers.com"><img src="https://img.shields.io/badge/MoveNumbers-live-10B981?style=for-the-badge" /></a>
<a href="https://taxtakehome.com"><img src="https://img.shields.io/badge/TaxTakeHome-live-10B981?style=for-the-badge" /></a>
<a href="https://noobikscube.com"><img src="https://img.shields.io/badge/Noobik's_Cube-live-10B981?style=for-the-badge" /></a>
<a href="https://stlwtf.com"><img src="https://img.shields.io/badge/STLWTF-live-10B981?style=for-the-badge" /></a>
<a href="https://localnewshero.com"><img src="https://img.shields.io/badge/Local_News_Hero-live-10B981?style=for-the-badge" /></a>
<a href="https://michiganisnotreal.com"><img src="https://img.shields.io/badge/Michigan_Is_Not_Real-live-10B981?style=for-the-badge" /></a>
<a href="https://github.com/clearchaos3/flipside"><img src="https://img.shields.io/badge/Flipside-native_macOS-10B981?style=for-the-badge" /></a>
<a href="https://github.com/clearchaos3/dl4-conductor"><img src="https://img.shields.io/badge/DL4_Conductor-native_macOS-10B981?style=for-the-badge" /></a>
<a href="https://github.com/clearchaos3/mf3d-cockpit"><img src="https://img.shields.io/badge/MF3D_Cockpit-native_macOS-10B981?style=for-the-badge" /></a>

</div>

---

### 🖥️ Native macOS

| Project | What It Does | Tech | Scale |
|---------|-------------|------|-------|
| **[Swarm](https://swarmtorrent.com)** | Native SwiftUI BitTorrent client — a fast, modern answer to Transmission's dated UI. Wraps libtorrent behind an Obj-C++ bridge; three-pane layout, live throughput graphs, SOCKS5 proxy with a real TCP **and** UDP test, fail-closed "require a VPN or proxy" guard, phone web remote (works anywhere via Tailscale), Sparkle auto-updates with delta patches. Signed, notarized, sandboxed. | Swift, SwiftUI, Objective-C++, libtorrent, Sparkle, Network.framework | Shipped 1.1 · DMG + Homebrew |
| **[Flipside](https://github.com/clearchaos3/flipside)** | Sampler/sequencer modeled on the classic 16-pad hardware-sampler workflow — chop samples and flip them into beats, driven by a Midi Fighter 64 + nanoKONTROL. 16 sequences × 8 banks, Chop mode, 16 Levels, Pad/Knob FX, Song mode | Swift, SwiftUI, AVAudioEngine, CoreMIDI | Full hardware-sampler workflow on a 64-pad grid |
| **[DL4 Conductor](https://github.com/clearchaos3/dl4-conductor)** | Turns a Mac into the brain for Line 6 DL4 MkII pedals over USB-C MIDI — a tempo-locked delay conductor with LFO-swept feedback, a MIDI-learn grid controller for dual loopers, and a phone looper remote | Swift, CoreMIDI, USB MIDI | Drives 2 pedals + 64-pad grid, phone remote |
| **[MF3D Cockpit](https://github.com/clearchaos3/mf3d-cockpit)** | Midi Fighter 3D arcade controller turned real-time mission control for parallel Claude Code sessions — 9 session pads with live status LEDs (thinking / waiting / done / failed), one-touch approvals, hold-to-talk dictation, self-learning tab mapping via the accessibility API, drag-drop web configurator. Spans two Macs over an ssh reverse tunnel | Hammerspoon (Lua), Swift, CoreMIDI, Python | 64 RGB pads · 4 banks · 2 machines |
| **Chop Shop** | Mashup IDE for Midi Fighter 3D/64 controllers. Chops any song into 1/8-note finger-drum pads by stem family with smart per-family slicing, beat-quantized pad editor, LED light-show builder with drag-to-paint + image-to-pixel-art, Ableton `.als` export | Swift, SwiftUI, Core Audio, CoreMIDI, Demucs | 64 pads live, 128-color LED control |

### 🌐 Web Products

| Project | What It Does | Tech | Scale |
|---------|-------------|------|-------|
| **[MoveNumbers](https://movenumbers.com)** | Cost-of-living comparison platform with SaaS layer for real estate agents — branded client portals, activity tracking, Stripe billing | Next.js, TypeScript, Supabase, Stripe, Vercel | 19,000+ cities, 2,800+ SEO pages |
| **[TaxTakeHome](https://taxtakehome.com)** | Take-home pay calculator — federal + all 50 states + FICA. Programmatic SEO across every salary × state combination | Next.js, TypeScript, Vercel | 2,800+ pages, 51 state tax engines |
| **[Noobik's Cube](https://noobikscube.com)** | Scan your Rubik's cube with your phone camera and get step-by-step solving instructions | Next.js, TypeScript, Tailwind, Vercel | Real-time color detection |
| **[STLWTF](https://stlwtf.com)** | Missouri situational awareness dashboard — live traffic cameras, police scanner, weather, crashes, news, air traffic | Vanilla JS, Vercel Serverless, Cloudflare Workers | 391 live cameras, 19 real-time data sources |
| **[Local News Hero](https://localnewshero.com)** | Drive a news van around your REAL city in photorealistic 3D. Chase breaking stories, go live on scene, beat rival stations. Vibe Jam 2026 entry | Three.js, TypeScript, Google 3D Tiles, Upstash Redis, Vercel | Works worldwide, global leaderboard |
| **[Michigan Is Not Real](https://michiganisnotreal.com)** | Satirical conspiracy site. Built in one night. Went viral. | Next.js, Tailwind, Vercel | Pure entertainment |

### 🧠 How I Think

- **Programmatic SEO** — I build sites that generate thousands of indexable pages from structured data
- **Native when it matters** — for real-time audio, MIDI hardware, and torrent engines, I go Swift + SwiftUI, not Electron
- **Ship daily** — I'd rather ship something imperfect today than something perfect never
- **Full-stack, full-ownership** — Design, frontend, backend, infra, DNS, SEO, code-signing, notarization — I do all of it

### 🔧 Stack

```
Languages    TypeScript · JavaScript · Python · Swift · Objective-C++ · SQL
Frontend     React · Next.js · Tailwind CSS · SwiftUI
Backend      Node.js · Supabase · PostgreSQL
Native       Swift · SwiftUI · Core Audio · AVAudioEngine · CoreMIDI · libtorrent · Sparkle
Ship         Vercel · Railway · AWS Lightsail · Cloudflare · notarized DMGs · Homebrew · Sparkle appcasts
Auth         Supabase Auth (RLS, server/client patterns)
SEO          Programmatic pages · Structured data · OG images · Sitemaps
```

### 📈 By The Numbers

- **11 products** shipped (6 web + 5 native macOS)
- **22,000+** programmatic SEO pages across sites
- **19,000+** US cities with cost-of-living data
- **391** live MoDOT traffic cameras streamed
- **50 states** + DC with full tax engines
- **1 torrent client** signed, notarized, auto-updating — distributed outside any app store
- **$0 in funding** — bootstrapped everything

### 💡 Philosophy

> Ship it. Get feedback. Fix it. Repeat. Perfect is the enemy of live.

I don't wait for gatekeepers. Websites rank on Google and serve real users; Mac apps ship as signed, notarized downloads with their own auto-update pipeline — no app store required.

---

<div align="center">

**Currently building the next thing.** Always.

📬 Reach me here on GitHub

</div>
