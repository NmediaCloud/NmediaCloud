# Nanda Mohan

**Creative & Technical Director — animation production pipelines, VFX, and the systems underneath them.** Toronto.

Twenty-plus years in animation, lighting and VFX — trained as a character animator, ran the Disney–Pixar composition and layout track, spent two decades shipping series for broadcasters and OTTs. Now building AI-native production systems that collapse that pipeline into one toolchain.

I work at the seam between creative and engineering: the part where a story has to survive contact with a render farm, a delivery spec, and a deadline.

🔗 **[nmediaservices.com](https://www.nmediaservices.com)** · [LinkedIn](https://www.linkedin.com/in/mnkmars/) · [IMDb](https://www.imdb.com/name/nm12576040/) · [YouTube](https://www.youtube.com/@nmediaservices2014)

---

### 🎨 CreativeFlow — [`/creativeflow`](https://github.com/NmediaCloud/creativeflow)

A creative automation pipeline for social ad campaigns. One brief in; on-brand, localized creatives across 1:1, 9:16 and 16:9 out — reusing the product assets you already own, generating only what's missing.

```
brief.yaml ─► validate ─► resolve asset ─► localize copy ─► compose ─► comply ─► outputs
                          (reuse│generate)                  (1:1│9:16│16:9)  (brand│legal)
```

**Runs on a clean checkout with no API key.** The default image provider renders offline with Pillow, so `python cli.py run briefs/summer_hydration_launch.yaml` works immediately — no credentials, no spend. Swap in a real GenAI backend by changing one line of `.env`.

`Python` · `Streamlit` · `Pillow` · `pytest` · MIT

---

### 🎬 The animation production pipeline

An eleven-module system taking a project from client brief to finished reel — format-aware, cast-locked, model-agnostic. Story input, asset design, script development, episodic variants, storyboards, animatics, animation, comic generation, reel polish.

Each module is operator-runnable from a single browser tab, and every project file is the same project file. The private repo is the production system; the write-ups are public:

| | |
|---|---|
| [How the pipeline was built](https://www.nmediaservices.com/articles/Pipeline_Production_System.html) | The eleven panels, end to end |
| [MiroFish](https://www.nmediaservices.com/articles/MiroFish.html) | A million synthetic viewers test-screen a pitch in twelve minutes |
| [UGC Pipeline](https://www.nmediaservices.com/articles/UGC_Pipeline.html) | One spreadsheet row in, one finished video out — vision-graded QA |
| [At the Speed of Generation](https://www.nmediaservices.com/articles/podcast/ep01.html) | Podcast: twenty-five years in animation, and what changed |

---

### 🛠 What I build with

**Pipeline & automation** — Python, FastAPI, Flask, async job orchestration, prompt systems, model-agnostic provider layers
**Creative stack** — Maya, Blender, 3ds Max, Nuke, After Effects, Unreal, Unity
**Web & data** — React, Vite, Tailwind, Node, Pandas, analytics instrumentation
**Production** — motion capture and facial data, lighting, rendering, compositing, technical direction

---

### 📌 Selected credits

**VFX — PAW Patrol** ([IMDb](https://www.imdb.com/name/nm12576040/)) · animation and VFX across global animated series
**Utherverse** — [hired as 3D animation veteran](https://www.einpresswire.com/article/592919633/utherverse-hires-3d-animation-veteran-nandakumar-mohan-to-develop-full-motion-hd-animation-for-metaverse-platform) to develop full-motion HD animation for their metaverse platform
**[Stockflow.media](https://stockflow.media/)** — content platform shipping ready-to-use media assets and automated pipelines

---

<sub>Most production repositories here are private — client work and proprietary pipeline systems. Happy to walk through any of it. <b>Nanda@nmediaservices.com</b></sub>
