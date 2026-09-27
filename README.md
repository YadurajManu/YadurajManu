<div align="center">
  <img src="assets/yaduraj-portrait.jpg" width="150" alt="Yaduraj Singh smiling in a red sweater" />
  <h1>Yaduraj Singh</h1>
  <p><strong>Software engineer · applied AI · systems that leave localhost</strong></p>
  <p>Dehradun / Greater Noida, India</p>
  <p>
    <a href="https://yaduraj.me">Portfolio</a> ·
    <a href="https://github.com/YadurajManu">GitHub</a> ·
    <a href="https://www.linkedin.com/in/yadurajenc">LinkedIn</a> ·
    <a href="mailto:yadurajsingham@gmail.com">yadurajsingham@gmail.com</a>
  </p>
  <img src="https://media.giphy.com/media/LmNwrBhejkK9EFP504/giphy.gif" width="68" alt="Typing cat sticker" />
</div>

```text
$ cat /etc/yaduraj
name       Yaduraj Singh
builds     infrastructure · AI products · research · real-time apps
approach   prototype → measure → ship → keep it running
location   India · open to remote collaboration

I like the part after “it works on my machine.”

 /\_/\
( o.o )  unofficial QA department
 > ^ <
```

## `featured/` — three things worth opening first

### 01 / [Fleet OS](https://github.com/YadurajManu/fleet-os) · systems & infrastructure

**One deploy target for the computers you already own.** I built a control plane, CLI, and outbound-only Go agents for coordinating containers across ARM/x86 machines and VPSs, including nodes behind NAT. Placement, health-gated rollouts, and delegated builds are part of the design. The project is under active development; the build/deploy path has been validated on Apple Silicon.

```text
                        ┌─ Raspberry Pi / ARM
[CLI] → [control plane] ─┼─ laptop / x86
           │            └─ VPS / cloud
           └─ placement · builds · rollouts · health
```

`Go` `TypeScript` `Docker` `BuildKit` `PostgreSQL`

[Source code](https://github.com/YadurajManu/fleet-os) · [Website & docs](https://fleet.plastikworld.xyz)

### 02 / [Microplastic detection research](https://doi.org/10.1109/IC3ECSBHI67834.2026.11469066) · applied ML

Coauthored an IEEE conference paper on a field-oriented microplastic detection system combining **YOLOv8-based microscopy, impedance measurements, and multispectral optical sensing**. My contributions were **model training and app/backend development**.

```text
microscopy ── YOLOv8 ──┐
impedance ─────────────┼── multimodal water-sample analysis
optical sensing ───────┘
```

[Read the paper / DOI](https://doi.org/10.1109/IC3ECSBHI67834.2026.11469066) · [IEEE Xplore](https://ieeexplore.ieee.org/document/11469066)

### 03 / [Tollgate](https://tollgate.yaduraj.me) · AI products

**An LLM API cost and usage layer.** Point an application's `base_url` at Tollgate to attribute spend to features, cache exact-match requests, enforce budgets, and detect runaway agents. Currently in private beta.

```text
app → Tollgate → model provider
        ├─ feature-level usage
        ├─ exact-match cache
        └─ budgets & alerts
```

[Open product](https://tollgate.yaduraj.me)

## `explore/` — projects by domain

| Domain | Project | What I built | Explore |
|:--|:--|:--|:--|
| Healthcare SaaS | **Aarogya Setu** | Multi-tenant hospital workflows for OPD/IPD, records, billing, and role-based access | [Live product](https://arogya.yaduraj.me) |
| Real-time web | **MuhDikhai** | Anonymous video chat with custom WebRTC signaling and peer lifecycle | [Source](https://github.com/YaduEnc/MuhDikhai) |
| Embedded AI | **SecondMind / CortX** | ESP32-S3 audio → speech recognition → local LLM → speech output | [Source](https://github.com/YaduEnc/CortX) |
| Mobile | **GBU Timetable** | iOS timetable and home-screen widgets for university students | [Source](https://github.com/YadurajManu/Timetable) |
| Health tech | **Maakosh** | Maternal and neonatal health app with wearable vitals | [Source](https://github.com/YadurajManu/MaaKosh) |
| Legal tech | **Bolonyay** | Multilingual legal aid, voice-assisted forms, and PDF filings | [Source](https://github.com/YadurajManu/Bolonyay-App) |
| Consumer web | **CineVerse** | Watchlists, ratings, reviews, and film discovery | [Live product](https://cine.yaduraj.me) |

## `toolbox/`

```text
systems    Go · Docker · BuildKit · Linux · Nginx · GitHub Actions
ai / data  Python · YOLOv8 · FastAPI · LLM APIs · Qdrant · Neo4j
web        TypeScript · React · Next.js · Node.js · PostgreSQL · Redis
real-time  WebRTC · Socket.io · ESP32-S3 · BLE · Opus
mobile     SwiftUI · Flutter
```

<details>
<summary><strong>activity/ — GitHub metrics</strong></summary>
<br />
<img src="https://raw.githubusercontent.com/YadurajManu/YadurajManu/main/metrics.svg" width="100%" alt="GitHub activity metrics" />
</details>

---

<div align="center">
  <p><strong>Have a hard problem, a weird device, or a service that only works on your laptop?</strong><br />I would like to hear about it.</p>
  <p>
    <a href="mailto:yadurajsingham@gmail.com">Email me</a> ·
    <a href="https://yaduraj.me">Portfolio</a> ·
    <a href="https://www.linkedin.com/in/yadurajenc">LinkedIn</a> ·
    <a href="https://instagram.com/yaduraj.doc">Instagram</a>
  </p>
  <img src="https://media.giphy.com/media/qgQUggAC3Pfv687qPC/giphy.gif" width="96" alt="Small coding sticker" />
  <p><sub>README deploy: successful. Production bugs: please file an issue.</sub></p>
</div>
