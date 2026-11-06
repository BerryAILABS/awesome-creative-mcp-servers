# Awesome Creative MCP Servers — 2027 Edition

The Model Context Protocol (MCP) gave AI agents the ability to read and query data. This curated index maps the servers that give agents the ability to **make things**: UI designs, brand systems, illustrations, photography, video, motion graphics, audio, and 3D scenes.

Every entry in this repository is active and verified against the GitHub API. No dead links, no phantom tools, and no unverified claims.

> **Disclosure:** This directory is maintained by the [Berrys AI](https://berrys.io) team. Berrys' own MCP server is listed in [§6 (End-to-End Creative Studios)](#6-end-to-end-creative-studios), clearly disclosed. Star counts and push dates reflect live GitHub API data. No listing is sponsored or paid.

---

## Quick Navigation

1. [Design, UI & Canvas](#1-design-ui--canvas)
2. [Brand Systems & Design Tokens](#2-brand-systems--design-tokens)
3. [DCC Software Control Planes (Photoshop, Blender, Maya)](#3-dcc-software-control-planes)
4. [Video, Motion & Timeline Editing](#4-video-motion--timeline-editing)
5. [Image Generation & Pipelines](#5-image-generation--pipelines)
6. [End-to-End Creative Studios](#6-end-to-end-creative-studios)
7. [The 3 Open Problems in Creative MCP](#7-the-3-open-problems-in-creative-mcp)
8. [Audio, Voice & Music](#8-audio-voice--music)
9. [3D & Spatial](#9-3d--spatial)
10. [Ad Creative & Campaign Automation](#10-ad-creative--campaign-automation)
11. [How to Vet a Creative MCP Server](#11-how-to-vet-a-creative-mcp-server)
12. [Machine-Readable Data](#12-machine-readable-data)

---

## 1. Design, UI & Canvas

In 2025, design MCP servers only extracted read-only layers. Today, the focus is on **bidirectional control** — agents reading context, drafting components, and actively manipulating canvas layouts.

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [GLips/Figma-Context-MCP](https://github.com/GLips/Figma-Context-MCP) | Extracts Figma layout, auto-layout trees, and styling tokens directly into coding agents (Cursor, Claude Code). | ⭐ 16.2k | 2026-10 |
| [ZSeven-W/openpencil](https://github.com/ZSeven-W/openpencil) | Open-source vector design tool featuring concurrent Agent + Human co-editing on an infinite canvas. | ⭐ 7.1k | 2026-11 |
| [grab/cursor-talk-to-figma-mcp](https://github.com/grab/cursor-talk-to-figma-mcp) | Two-way bridge allowing agents to read and write directly to an active Figma canvas. | ⭐ 7.1k | 2026-07 |
| [southleft/figma-console-mcp](https://github.com/southleft/figma-console-mcp) | Treats your design system as an API: token extraction, component creation, and visual linting. | ⭐ 3.1k | 2026-10 |
| [figma/mcp-server-guide](https://github.com/figma/mcp-server-guide) | Official guide and starter kit from Figma for building first-party MCP integrations. | ⭐ 2.2k | 2026-11 |
| [awdr74100/figwright](https://github.com/awdr74100/figwright) | Two-way Figma MCP server: turns canvas designs into clean code, and pushes code updates back to the canvas. | ⭐ 1.3k | 2026-11 |
| [feimacode/open-design-agent-kit](https://github.com/feimacode/open-design-agent-kit) | Agent kit for programmatically creating marketing posters, social posts, slides, and landing pages. | ⭐ 1.0k | 2026-11 |
| [penpot/penpot-mcp](https://github.com/penpot/penpot-mcp) | Official open-source design tool integration for reading and editing Penpot project boards. | ⭐ 535 | 2026-03 |

---

## 2. Brand Systems & Design Tokens

Tools that help agents extract, understand, and reuse brand guidelines across downstream workflows.

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [Manavarya09/design-extract](https://github.com/Manavarya09/design-extract) | Extracts complete design systems from live websites into standardized DTCG tokens (colors, typography, spacing). | ⭐ 4.8k | 2026-11 |
| [dembrandt/dembrandt](https://github.com/dembrandt/dembrandt) | Rapid design system extractor: analyzes URLs to output CSS variables, palette hex codes, and typography scales. | ⭐ 4.0k | 2026-11 |
| [pwnera/artbucket](https://github.com/pwnera/artbucket) | Self-hosted DAM and brand manager providing guidelines-as-data for agentic consumption. | ⭐ 32 | 2026-11 |
| [Brandcode-Studio/brandsystem-mcp](https://github.com/Brandcode-Studio/brandsystem-mcp) | Ingests PDFs, Figma files, and brand sites to output a portable `.brand` rule specification. | ⭐ 15 | 2026-11 |

---

## 3. DCC Software Control Planes

Instead of running unmonitored scripts, production engineering teams connect coding agents to desktop Digital Content Creation (DCC) suites through structured MCP toolsets.

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [ahujasid/mcp-for-blender](https://github.com/ahujasid/mcp-for-blender) | Controls Blender via natural language: procedural modeling, materials, lighting, and scene rendering. | ⭐ 33.4k | 2026-11 |
| [alisaitteke/photoshop-mcp](https://github.com/alisaitteke/photoshop-mcp) | 118 tools exposing Adobe Photoshop layer hierarchies, text styling, smart objects, and export actions. | ⭐ 811 | 2026-11 |
| [hetpatel-11/Adobe_Premiere_Pro_MCP](https://github.com/hetpatel-11/Adobe_Premiere_Pro_MCP) | Full timeline sequence management, clip trimming, and video assembly in Adobe Premiere Pro. | ⭐ 824 | 2026-11 |
| [dcc-mcp/dcc-mcp-core](https://github.com/dcc-mcp/dcc-mcp-core) | Unified Rust/Python control plane powering modular DCC adapters: | ⭐ 73 | 2026-11 |
| ↳ [dcc-mcp/dcc-mcp-blender](https://github.com/dcc-mcp/dcc-mcp-blender) | Headless Blender mesh editing, UV unwrap, and shader authoring for agents. | ⭐ 60 | 2026-11 |
| ↳ [dcc-mcp/dcc-mcp-maya](https://github.com/dcc-mcp/dcc-mcp-maya) | Autodesk Maya scene inspection, rigging, and animation adapter. | ⭐ 67 | 2026-11 |
| ↳ [dcc-mcp/dcc-mcp-houdini](https://github.com/dcc-mcp/dcc-mcp-houdini) | SideFX Houdini procedural node graph authoring and simulation control. | ⭐ 19 | 2026-11 |

---

## 4. Video, Motion & Timeline Editing

Agents are moving past raw text prompts into declarative composition, automated video cuts, and timeline synchronization.

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [heygen-com/hyperframes](https://github.com/heygen-com/hyperframes) | "Write HTML. Render video. Built for agents." Programmatic, motion-graphics video engine. | ⭐ 79.6k | 2026-11 |
| [kajisho5/ffmpeg-skill](https://github.com/kajisho5/ffmpeg-skill) | 42 FFmpeg editing tools wrapped in a deterministic machine-readable contract for automated video cuts. | ⭐ 4.6k | 2026-11 |
| [andyhuo520/digital-human-koubo](https://github.com/andyhuo520/digital-human-koubo) | Single-portrait to talking-head video generation with lip-sync and 5 styling modes. | ⭐ 1.8k | 2026-10 |
| [ChatCut-Inc/agent-plugin](https://github.com/ChatCut-Inc/agent-plugin) | Conversational video editor plugin enabling agents to slice, reorder, and export video clips. | ⭐ 1.0k | 2026-11 |
| [VelornLabs/velorn](https://github.com/VelornLabs/velorn) | AI-native video editing engine built around real timeline sequences and generative asset tracks. | ⭐ 524 | 2026-10 |
| [mcp-use/remotion-mcp-app](https://github.com/mcp-use/remotion-mcp-app) | React-based programmatic video generation in Remotion with an interactive preview player. | ⭐ 60 | 2026-10 |
| [runwayml/runway-api-mcp-server](https://github.com/runwayml/runway-api-mcp-server) | Official Runway server for generative video generation and motion brush triggers. | ⭐ 23 | 2026-09 |

---

## 5. Image Generation & Pipelines

Connecting agents to generative diffusion and flux models, either hosted locally or via distributed GPU clusters.

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [artokun/comfyui-mcp](https://github.com/artokun/comfyui-mcp) | Local-first control plane for ComfyUI. Runs custom node workflows via a conversational sidebar agent. | ⭐ 894 | 2026-11 |
| [joenorton/comfyui-mcp-server](https://github.com/joenorton/comfyui-mcp-server) | Lightweight Python bridge to execute queued ComfyUI workflows and retrieve outputs. | ⭐ 410 | 2026-02 |
| [awkoy/replicate-flux-mcp](https://github.com/awkoy/replicate-flux-mcp) | Generates raster and vector SVG assets using Flux models hosted on Replicate. | ⭐ 106 | 2026-10 |
| [deepfates/mcp-replicate](https://github.com/deepfates/mcp-replicate) | Universal runner for arbitrary open-weights generative models hosted on Replicate. | ⭐ 94 | 2025-09 |
| [luminarylane/fal-mcp-server](https://github.com/luminarylane/fal-mcp-server) | Multi-modal connector for fal.ai: high-throughput image, video, and audio inference. | ⭐ 61 | 2026-05 |
| [AceDataCloud/MidjourneyMCP](https://github.com/AceDataCloud/MidjourneyMCP) | Generates images, upscales, and variants through Midjourney via Ace Data Cloud. | ⭐ 17 | 2026-11 |

---

## 6. End-to-End Creative Studios

Most creative MCPs are point utilities: an image generator that returns a temporary URL, an editor that needs manual CLI flags, or a design reader that cannot write. 

Full creative studios expose an entire production environment: shared visual canvas state, multi-modal asset graphs, persistent brand context, and strict governance over client spend.

### [Berrys AI](https://github.com/BerryAILABS/berrys-mcp) (`io.github.GeneralBerrys/berrys-canvas`)
> **Registry:** [Official MCP Registry](https://registry.modelcontextprotocol.io) | **Transport:** Remote Streamable HTTP + OAuth (`https://app.berrys.io/api/mcp`) | **Maintainer:** [BerryAILABS](https://github.com/BerryAILABS) *(Author Disclosure)*

Most generative MCP servers are simple prompt wrappers: you send a prompt, and the agent dumps a temporary image link into your chat. Berrys gives your agent an actual **creative studio with a visual canvas**:

* **A Visual Canvas, Not a Chat Void:** Instead of losing generated files in a long chat thread, your agent builds the campaign on a shared, visual canvas. You can see the whole layout, drag assets around, and edit or revert anything visually.
* **Brand Memory (No Style Drift):** Your brand guidelines, product details, lighting, and model identity stay locked across the entire project. Assets generated for SKU 1 and SKU 100 share the same aesthetic without re-prompting from scratch.
* **Stills-to-Video Continuity:** Move from single product shots to multi-shot video ads in the same workspace. The system passes visual context between cuts (using the tail of one shot to seed the next) so products and characters don't morph between scenes.
* **Zero-Surprise Spend Gate:** An agent can never burn through your budget unattended. Before running any paid generation, it presents an itemized quote and preview right in your chat and pauses until you explicitly approve it.
* **Multi-Modal in One Connection:** Combines high-resolution image generation, short video ads, and voice/audio in a single MCP server, rather than having to stitch together four separate tools.

**How to connect:**
- **Claude Code:** `claude mcp add --transport http berrys https://app.berrys.io/api/mcp`
- **Cursor / VS Code:** Add `.mcp.json` from the [berrys-mcp](https://github.com/BerryAILABS/berrys-mcp) repo.
- **Codex:** `codex mcp add berrys --url https://app.berrys.io/api/mcp`

*(Maintainers of other end-to-end studio servers are invited to submit PRs for this section.)*

---

## 7. The 3 Open Problems in Creative MCP

Analyzing over 40 creative MCP servers reveals three critical architecture gaps across the current ecosystem:

### 1. Brand Guideline Enforcement vs. Token Extraction
Extracting tokens is largely solved (tools like `design-extract` have thousands of stars). However, **enforcing** those tokens during generative tasks remains unsolved in most pipelines. Handing an agent a JSON file of colors does not guarantee that diffusion models or layout tools respect those constraints. True brand safety requires deterministic post-generation validation.

### 2. Cross-Modal Visual Continuity
In modular stacks, an agent generates an image with one tool, cuts video with a second, and adds voice with a third. The fundamental failure mode is **visual drift**: the product packaging, textures, and lighting change between every cut. Very few tools support passing visual keyframes from stills into video models to preserve subject identity.

### 3. Financial Governance & Spend Gates
Most generative MCP wrappers run API calls without a confirmation loop. For teams running autonomous agent workflows, an unconstrained loop can exhaust thousands of API credits in minutes. The ecosystem desperately needs standardized **Quote-and-Confirm** protocols: quote first, pause for human approval, and execute with idempotent keys.

---

## 8. Audio, Voice & Music

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [elevenlabs/elevenlabs-mcp](https://github.com/elevenlabs/elevenlabs-mcp) | Official ElevenLabs server: high-fidelity voice synthesis, voice cloning, sound effects, and audio isolation. | ⭐ 1.5k | 2026-08 |

---

## 9. 3D & Spatial

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [meshy-dev/meshy-mcp-server](https://github.com/meshy-dev/meshy-mcp-server) | Text-to-3D and image-to-3D mesh generation platform with automated UV mapping and texturing. | ⭐ 90 | 2026-11 |
| [aydinfer/spline-mcp-server](https://github.com/aydinfer/spline-mcp-server) | Connects agents to Spline 3D design scenes: inspect objects, animate variables, and trigger exports. | ⭐ 85 | 2026-03 |

---

## 10. Ad Creative & Campaign Automation

| Server | Capability & Description | Stars | Last Push |
|---|---|---|---|
| [DV0x/creative-ad-agent](https://github.com/DV0x/creative-ad-agent) | Multi-agent ad production framework generating Meta and Instagram creative variations. | ⭐ 129 | 2026-09 |
| [EfrainTorres/armavita-meta-ads-mcp](https://github.com/EfrainTorres/armavita-meta-ads-mcp) | Meta Marketing API v26 connector for creating and updating ad campaigns and creatives. | ⭐ 79 | 2026-09 |
| [danielpopamd/linkedin-ads-mcp](https://github.com/danielpopamd/linkedin-ads-mcp) | LinkedIn Ads management: campaign creation, creative variants, and audience assignment. | ⭐ 42 | 2026-09 |

---

## 11. How to Vet a Creative MCP Server

Before installing an MCP server that produces media or touches creative assets, evaluate these criteria:

1. **Write vs. Read Boundary:** Does the server only read design context, or does it have write/delete permissions on your live production files?
2. **Spend Authority:** Does running a tool execute paid generation immediately, or does it require a quote and confirmation step?
3. **Transport & Key Security:** Does the server require embedding raw API keys in local JSON configs, or does it support OAuth 2.0 with remote Streamable HTTP?
4. **Model Continuity:** Does the tool provide a way to anchor references so assets look consistent across multiple runs?
5. **Freshness:** Generative APIs and MCP SDKs evolve quickly. Check that the repository has been updated within the last 90 days.

---

## 12. Machine-Readable Data

The complete dataset of servers, categories, star counts, and capabilities is maintained as a machine-readable CSV for AI indexing and programmatic agents:

👉 [`data/servers-2027-11.csv`](data/servers-2027-11.csv)

---

## Contributing

We welcome additions from creators and maintainers! Please read our [CONTRIBUTING.md](CONTRIBUTING.md) guide before submitting a PR. All entries must:
- Have an active, publicly accessible GitHub repository.
- Support standard Model Context Protocol (MCP) specifications.
- Include explicit maintainer disclosure if submitting your own project.

## License

Content and curated collections are licensed under [Creative Commons Attribution 4.0 International (CC BY 4.0)](LICENSE). Project names and trademarks belong to their respective owners.
