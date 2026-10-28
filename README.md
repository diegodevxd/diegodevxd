### Hi, I'm Diego 👋

Computer Systems Engineering student (Universidad EPCA, León, México · expected 2028) working on **Linux kernel drivers**, **cloud-native infrastructure** and **full-stack web apps**.

📫 diegomancera.dev@gmail.com · 🌐 [diegomancera.vercel.app](https://diegomancera.vercel.app) · 💼 [LinkedIn](https://linkedin.com/in/diego-fernando-mancera-gomez)

🔎 Looking for **software engineering internships or junior roles** (kernel/systems or full-stack) — remote or on-site in León.

---

#### 🐧 Linux kernel — upstream fixes (C)

| Driver | Bug | Status |
|---|---|---|
| `ueagle-atm` (USB) | Slab out-of-bounds read: crafted descriptors made probe/disconnect disagree on device state | Mainline 7.2-rc5 · [CVE-2026-68344](https://www.cve.org/CVERecord?id=CVE-2026-68344) · [commit](https://git.kernel.org/torvalds/c/71132cedd1ecbc4032d76e9928c18a10f7e39b80) |
| `em28xx` (media) | syzbot-reported use-after-free on dual-TS devices; deferred audio-only extension registration | Mainline 7.3 · [CVE-2026-89892](https://www.cve.org/CVERecord?id=CVE-2026-89892) · [commit](https://git.kernel.org/torvalds/c/95f76f51937fdfb0fc1e14cae606b1ef574a56f3) |

#### ☸️ HAMi — GPU scheduler for Kubernetes (Go, CNCF Incubating)

- [#3106](https://github.com/Project-HAMi/HAMi/pull/3106) — Scheduler scoring used a different memory value than the one reserved for pods requesting `gpumem` + `gpumem-percentage`, mis-ranking GPUs.
- [#3313](https://github.com/Project-HAMi/HAMi/pull/3313) — Enflame backend read a mode code (`-1`) as a memory percentage, producing negative memory in scoring.

#### 🛠️ Projects

- **Cuentivo** — Android app for small shops to track customer credit (Flutter, Firebase, Gemini API via a custom gateway).
- **PDF Crop Studio** — Pixel-accurate PDF image extractor with text-layer auto-labeling and OCR fallback (Python).
- **CapiHw Labs** — 10+ production websites for clients (Next.js, Supabase, Stripe, Vercel, GitHub Actions).

#### 🧰 Stack

`C` `Go` `Python` `JavaScript` `TypeScript` `Dart` · `Linux kernel` `Kubernetes` `Git` `GitHub Actions` · `Next.js` `Supabase` `PostgreSQL` `Firebase` `Stripe`
