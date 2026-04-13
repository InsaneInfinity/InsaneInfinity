# 👋 Hi, I'm Patryk — InsaneInfinity

I'm a **C# / .NET & Python developer** focused on high-performance backends, application security and simulation systems. I build things that push limits — WAFs, load testers, ballistic simulators — and I believe that standard solutions are never enough.

---

### 🛠️ Tech Stack

**Backend & Performance**
`C# (.NET 10)` `ASP.NET Core` `SocketsHttpHandler` `TPL / Async` `YARP`

**Security & Networking**
`WAF` `Redis Pub/Sub` `SignalR` `GeoIP (MaxMind)` `Browser Fingerprinting` `SHA-256`

**Python**
`Flask` `FastAPI` `ASGI Middleware` `Redis asyncio` `NumPy` `Regex DPI`

**Simulation & Science**
`Euler Integration` `ISA Atmosphere` `NASA SRTM` `Coriolis Effect` `Glasstone & Dolan`

**Tooling & Infrastructure**
`Docker` `Git` `Redis Streams` `Leaflet.js` `CesiumJS`

---

### 🚀 Projects

#### ⬡ [BALISTIC v6.0](https://github.com/InsaneInfinity/Balistic) — Ballistic Fire Control Simulator

`Python/Flask` `C# .NET 10` `Redis Streams` `NASA SRTM` `Leaflet.js` `CesiumJS`

Advanced ballistic simulator with **NASA SRTM terrain masking** — blast zones physically blocked by real mountains using a 72-ray horizon scan algorithm. Global elevation coverage (5700+ tiles), 195 weapon systems from 30+ countries, hybrid ballistic model (Euler+ISA for SRBM, analytic for ICBM), nuclear blast physics (Glasstone & Dolan 1977), radioactive fallout, Coriolis effect, CesiumJS 3D globe.

| | |
|---|---|
| 🏔️ Islamabad — Margalla Hills block NW blast wave | 🏜️ Las Vegas — Red Rock Canyon clips zones west |

#### 🛡️ Shield-X Ecosystem — Layer 7 WAF

A family of WAF tools built from scratch — each one runs standalone or as part of a larger hybrid stack.

| Repo | Stack | What it does |
|---|---|---|
| [ShieldX-L7-DeepDefense](https://github.com/InsaneInfinity/ShieldX-L7-DeepDefense) | C# + Python + Redis | Full hybrid WAF — .NET gateway + Python DPI engine + SignalR dashboard |
| [ShieldX-Proxy](https://github.com/InsaneInfinity/ShieldX-Proxy) | C# + Redis | Standalone .NET WAF — browser fingerprinting, bot scoring, GeoIP, global ban sync |
| [ShieldX-Python](https://github.com/InsaneInfinity/ShieldX-Python) | Python + Redis | Standalone Python WAF — body scanning, rate limiting, Log4Shell detection |

#### ⚡ [Xtreme-Load-Tester-Pro](https://github.com/InsaneInfinity/Xtreme-Load-Tester-Pro)

`C#` — High-concurrency HTTP stress testing engine. GET & POST support, 10k connections per server, HTTP/2, stealth delay, real-time RPS counter, p50/p95/max latency report.

---

### 📊 GitHub Stats

[![InsaneInfinity's GitHub stats](https://github-readme-stats.vercel.app/api?username=InsaneInfinity&show_icons=true&theme=tokyonight)](https://github.com/InsaneInfinity)
[![Top Langs](https://github-readme-stats.vercel.app/api/top-langs/?username=InsaneInfinity&layout=compact&theme=tokyonight)](https://github.com/InsaneInfinity)

---

### 📫 Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Patryk%20Grzes-0077B5?logo=linkedin)](https://www.linkedin.com/in/patryk-grzes-113b063b8/)
[![Dev.to](https://img.shields.io/badge/Dev.to-insaneinfinity-0A0A0A?logo=devdotto)](https://dev.to/insaneinfinity)

---

*"If it's not fast, it's not finished. If it's not automated, it's a waste of time."*
