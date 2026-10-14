# Portfolio content (source of truth for the redesign)

Pulled from the live site https://vaishnavi220506.github.io/portfolio-website/ and `assets/resume-polished-final.pdf`.
All images, certificates and the resume PDF are in `content/assets/`.

## Identity & contact
- Full name: Devulapalli Naga Sri Vaishnavi (display name: Vaishnavi)
- Tagline: CSE student · builder · open source
- Email: vaishnaviharish2006@gmail.com · Phone: 8978970741
- GitHub: https://github.com/Vaishnavi220506 (@Vaishnavi220506, 22 public repositories)
- LinkedIn: https://linkedin.com/in/vaishnavi-d-9a42a9374
- Avatar: `github-avatar.jpg` · Hero background: `scenic-backdrop.jpg`

## Hero
- Heading: "Hello, I'm Vaishnavi"
- "I'm a Computer Science student at VIT Vellore building across AI/ML, computer vision, full-stack products, and developer tools. I like turning a rough idea into something people can actually use — and explain."
- Buttons: "See my projects", "Read my resume"
- Profile card: Devulapalli Naga Sri Vaishnavi · CSE @ VIT Vellore · stats: repositories (22) / PRs highlighted (10) / flagship builds (5)

## About — "A little context"
**Curious about how things work — and how to make them better.**
- I'm a CSE student at VIT Vellore, and I learn best by making. My projects move between AI systems, computer vision, web products, and tools that help people learn, work, or respond to real problems.
- I enjoy taking a project from the first sketch to a working version, then making it clearer through feedback. Readable code, simple interfaces, and useful outcomes matter to me more than making a demo look impressive for a minute.
- Open source is where that habit becomes a conversation. I contribute fixes, read unfamiliar code, and try to leave a project a little easier for the next person to work with.

Focus areas:
1. Machine learning — Deep learning, computer vision, transformers, and practical model building.
2. AI systems — Agent tooling, inference, evaluation, and reliable developer workflows.
3. Product engineering — Full-stack apps that make everyday problems easier to handle.
4. Open source — Learning in public, reviewing code, and contributing fixes upstream.

## Projects — "Selected work: The work behind the experiments."
Subtitle: "Explore the interfaces, then open a project to see the thinking behind it." · Link: All repositories → https://github.com/Vaishnavi220506?tab=repositories

1. **KAVACH** — 01 / Computer vision systems · image `kavach-front-page.png`
   - An explainable video-intelligence prototype that turns warehouse footage into tracked objects, evidence-backed safety events, and replayable incident records.
   - Detail: I built it around structured evidence first: YOLO perception, ByteTrack identities, temporal behaviour rules, SQLite incident history, and a grounded assistant that explains only what the evidence supports.
   - Highlights: YOLO + ByteTrack temporal tracking · Explainable behaviour and risk scoring · SQLite evidence replay + grounded assistant
   - Tags: Python, OpenCV, YOLO, FastAPI
   - Repo: https://github.com/Vaishnavi220506/kavach-video-intelligence · Live: https://forklift-safety-ai.vercel.app/
2. **STEMPulse** — 02 / Social impact product · (no screenshot; drawn visual "STEM / PATHWAYS / RETURN — Build confidence with evidence. 01 Learn · 02 Grow · 03 Restart")
   - A women-first STEM pathways platform for learning, opportunities, evidence-aware confidence, and career re-entry support.
   - Detail: The product maps people to a practical next step instead of treating confidence or career breaks as missing potential: profile evidence, skill freshness, opportunity matching, and a shortest-path plan.
   - Highlights: Learn, work, fund, and re-entry pathways · Evidence-aware confidence signals · Explainable opportunity matching
   - Tags: React, Python, FastAPI, Career UX
   - Repo: https://github.com/Vaishnavi220506/StemPulse
   - Built at WINS-AID AI Hackathon 2026 — Top 20 team.
3. **RescueLink** — 03 / Product engineering · image `rescue-first-screen.png`
   - A real-time emergency coordination platform that helps people request support, offer resources, and share trusted local updates.
   - Detail: I designed it around a calm response workspace: role-aware access, a clear request lifecycle, location-aware maps, community confirmation, and atomic volunteer claims.
   - Highlights: Location-aware requests and resources · Community-confirmed hazard reports · Atomic volunteer claims
   - Tags: React, TypeScript, Express, PostGIS (resume: + Vite, Socket.IO, Leaflet, PostgreSQL, Zod)
   - Repo: https://github.com/Vaishnavi220506/RescueLink · Live: https://rescue-link-clarity-loop-ai.vercel.app/
4. **ClarityLoop** — 04 / AI systems · image `clarity-project.png`
   - An open-source workspace that stress-tests a project idea before time, money, and effort are spent building it.
   - Detail: Six focused agents examine requirements, evidence, resources, risks, and scope before turning the result into confidence scores, tasks, and an honest project plan.
   - Highlights: Six-agent feasibility pipeline · Evidence and assumption tracking · Local Ollama or cloud Gemini support
   - Tags: Next.js, FastAPI, Gemini, Ollama
   - Repo: https://github.com/Vaishnavi220506/ClarityLoop-ai · Live: https://clarityloop-ai.vercel.app/
5. **RaceVerse** — 05 / Experimental ML · image `race-project.png`
   - A browser-based 3D racing prototype with procedural tracks, local multiplayer, AI opponents, and a trained racing policy.
   - Detail: Tracks are created from seeds, while the AI learns in a small simulator and runs locally in the browser. The project is a practical way to explore games, reinforcement learning, and interaction design together.
   - Highlights: Seeded procedural tracks · Local multiplayer and AI Arena · 50 unseen seeds evaluated
   - Tags: React, Babylon.js, Python, NumPy
   - Repo: https://github.com/Vaishnavi220506/RaceVerse · Live: https://raceverse.vercel.app/

## Open source — "Small fixes can make a big difference."
"I'm learning in public by working upstream. Here are a few contributions across AI, inference, accessibility, developer tooling, and compilers." (3 merged, more in review; the old site had a search box)

| Project | PR | Status | Description | Tags |
|---|---|---|---|---|
| ONNX (onnx/onnx) | [#8448](https://github.com/onnx/onnx/pull/8448) | Merged | Fixed custom callback lifetime handling in shape inference so callbacks remain valid for the full inference operation. (Resume: retained guarded callback ownership; regression coverage for short-lived registrations and GC.) | C++, ONNX, Memory safety |
| PyRIT (microsoft/PyRIT) | [#2356](https://github.com/microsoft/PyRIT/pull/2356) | Merged | Fixed stereo audio frequency conversion so multi-channel WAV input no longer causes NumPy broadcasting failures. (Resume: validated with 1,095 tests and Ruff checks.) | Python, NumPy, Audio |
| CrewAI (crewAIInc/crewAI) | [#6881](https://github.com/crewAIInc/crewAI/pull/6881) | Merged | Made the project's pre-commit hooks portable on Windows by removing Unix-only environment activation. (Resume: direct uv commands for Ruff, mypy, pip-audit, pytest, with regression coverage.) | Python, AI agents, Developer tools |
| AirLLM (lyogavin/airllm) | [#363](https://github.com/lyogavin/airllm/pull/363) | Open | Proposed support for PyTorch tokenizer inputs in the MLX generation pipeline. | PyTorch, MLX, Inference |
| OpenHands SDK (OpenHands/software-agent-sdk) | [#4878](https://github.com/OpenHands/software-agent-sdk/pull/4878) | Open | Proposed agent-server proxy support for cloud runtime requests. | TypeScript, Agentic systems, Cloud API |
| blind-assist (violetljj/blind-assist) | [#49](https://github.com/violetljj/blind-assist/pull/49) | Open | Proposed accessibility hardening for the default flow at large font sizes. | Android, Accessibility, UI |
| Ersilia model template (ersilia-os/eos-template) | [#95](https://github.com/ersilia-os/eos-template/pull/95) | Open | Proposed automatic model releases when generated outputs change. | GitHub Actions, Release automation, Python |
| Ersilia workflows (ersilia-os/ersilia-model-workflows) | [#7](https://github.com/ersilia-os/ersilia-model-workflows/pull/7) | Open | Proposed reusable workflow automation for model releases when outputs change. | GitHub Actions, CI/CD, Automation |
| vLLM (vllm-project/vllm) | [#56444](https://github.com/vllm-project/vllm/pull/56444) | Open | Proposed a bugfix for N-gram PLE with pipeline parallelism. | PyTorch, CUDA, Inference |
| vLLM (vllm-project/vllm) | [#56413](https://github.com/vllm-project/vllm/pull/56413) | Open | Proposed avoiding duplicate host allocation for UVA weights. | PyTorch, CUDA, Memory |

## Skills — "The toolkit: A stack that follows the problem."
"I don't collect tools for the sake of it. I pick the simplest set that helps an idea become clear, useful, and dependable."
- **Languages** (The tools I reach for to think clearly and build from first principles.): Python, C++, Java, JavaScript, TypeScript, C
- **Web & product** (A practical web toolkit for turning an idea into something people can use.): React, Next.js, Tailwind CSS, Node.js, Express, FastAPI, Vite, REST APIs, Streamlit
- **ML & data** (Libraries and ideas for experiments that stay grounded in real constraints.): PyTorch, Hugging Face, scikit-learn, OpenCV, Ultralytics YOLO, Transformers, NumPy, Pandas, Ollama
- **Tools & data** (The infrastructure around the code: shipping, testing, and making it dependable.): Git, GitHub Actions, Docker, PostgreSQL, PostGIS, MySQL, SQLite, SQLAlchemy, Vercel
- Extra from resume: Flask, HTML, CSS, Socket.IO, Neural Networks, CNNs, Autoencoders, Attention, Reinforcement Learning, Object Detection, ByteTrack / Multi-Object Tracking, Video Analytics, Image Processing, NLP, Generative AI, Explainable AI, Temporal Reasoning, Matplotlib, Jupyter

## Resume — "A quick resume view: Strong foundations, practical experiments, and a lot more to learn."
"I'm pursuing a B.Tech in Computer Science at VIT Vellore with a 9.05/10 CGPA. I've also completed IBM's Generative AI Career Education Program and keep building projects that connect theory with real use." · Button: Open full resume → `resume-polished-final.pdf`
- Cards: education — VIT Vellore, Computer Science · cgpa — 9.05/10, academic foundation · internship — IBM GenAI, career education · mindset — Keep learning, keep it useful
- Education: VIT Vellore, B.Tech CSE (SCOPE), CGPA 9.05/10 · Ascent Junior College, Visakhapatnam — Class XII (CBSE) 98.2% · Sri Prakash Vidyaniketan, Visakhapatnam — Class X (CBSE) 92.8%
- Internship: IBM Career Education Program — Generative AI Virtual Internship, May 2026 – July 2026

## Achievements / certificates — "A few milestones worth keeping."
"A few certificates from programs and challenges that have shaped my journey so far. Tap a card to open its verification page." · Footer line: "One milestone at a time"
1. **WINS-AID AI Hackathon 2026** — British Council · VIT Vellore — 02–03 Sep 2026 — Hackathon participation — `achievement-wins-aid.png` — https://lnkd.in/p/d7Sxt8tw
   - 24-hour Women in STEM Innovation Challenge, British Council-sponsored "Empowering Women in STEM With Applied AI and Digital Skills Development", SCORE, VIT Vellore. Top 20 team with STEMPulse.
2. **Advanced Generative AI** — IBM Career Education Program — 16 Jul 2026 — Professional certificate — `achievement-ibm.png` — https://courses.ibmcep.cognitiveclass.ai/certificates/e6e8e6d0defb451a8b27bf824cebcfda
3. **Adobe University Hackathon 2026** — Adobe · Unstop — 09 Aug 2026 — Hackathon participation — `achievement-adobe.png` — https://unstop.com/certificate-preview/a6807747-82df-43c7-8f64-bfcc3b6952f2

## Contact — "Say hello: Have an idea, a question, or a good problem?"
"I'm always happy to talk about thoughtful software, open source, AI systems, or what you're building next."
- Form fields: Your email, Your note → "Open email draft" (opens a Gmail compose to vaishnaviharish2006@gmail.com; fallback "Try email app")
- Footer: © 2026 Vaishnavi

## Old site's tech (for reference)
React + Vite + React Router, Tailwind + shadcn/Base UI components, deployed to GitHub Pages at /portfolio-website/.

## GitHub profile (checked 14 Oct 2026)
- Display name: Devulapalli Naga Sri Vaishnavi · 53 public repositories (own builds + forks used for contributions) · 5 followers
- Bio: CSE student at VIT learning AI/ML, Deep Learning and Generative AI; builds practical projects and contributes to open source.
- Pinned: RescueLink. Achievements: Pair Extraordinaire, Pull Shark ×2, Quickdraw, YOLO.
- Profile README lines: "CSE student at VIT Vellore, building things that solve real problems." · "Keep learning. Keep building. Keep it useful."
- Own (non-fork) repos: portfolio, portfolio-website, SmartSwap, ModelForge, kavach-video-intelligence, StemPulse, RescueLink, RaceVerse, ClarityLoop-ai, Bert-Visualizer, Transformer-from-scratch, CNN_BASICS, Vaishnavi220506 (profile README)

### New projects added to the site
6. **ModelForge** — C++17 tensor compiler with Guardian-APC+ per-pass validation. Site: https://vaishnavi220506.github.io/ModelForge/ · Repo: https://github.com/Vaishnavi220506/ModelForge
   - 99.2% of observable injected faults caught with 128 inputs (96 synthetic models, 2,160 faults) vs 75.0% uniform random; 88.2% with 8 inputs; shrink check caught 22/24 risky compressions vs 14.
7. **SmartSwap** — Windows background-interference measurement and mitigation (Windows Stall Index, cause attribution, mitigation ladder). Repo: https://github.com/Vaishnavi220506/SmartSwap
   - One hybrid-core laptop, synthetic workloads: WSI vs p95 latency Spearman ρ = 0.96; p95 cut 87–94% under CPU/mixed contention; 1,575/1,575 actions and 322/322 reverts verified.

## Open source — verified on GitHub (14 Oct 2026)
GitHub search `author:Vaishnavi220506 is:pr`: 78 PRs total → 35 merged (34 upstream + RaceVerse #1 in own repo), 27 open, 16 closed unmerged.
The old site's list was out of date: OpenHands #4878, ersilia-os/eos-template #95 and ersilia-model-workflows #7 are closed, not open.

Merged upstream (34) by project: Ultralytics 11 (#26652 #26627 #26597 #26548 #26521 #26474 #26454 #26420 #26406 #26306 #26285) · Kornia 7 (#5922 #5891 #5817 #5668 #5498 #5296 #5091) · OpenRig 3 (#1030 #662 #505) · Roboflow Supervision 2 (#2717 #2646) · Ponytail 2 (#1057 #1037) · ONNX #8448 · Microsoft PyRIT #2356 · CrewAI #6881 · MLflow #26300 · COLMAP #4842 · rea #2912 · google/skills_lint.dart #64 · VoiceStudio #2422 · OmniRoute #14594 → 14 projects.

Open / in review (27): vLLM #58847 #58517 #56444 #56413 · COLMAP #4858 #4857 #4851 · Kubernetes #142917 · OpenCV #30235 · HF Datasets #8787 · AWS CLI #10722 · LangChain.js #11756 · LiteLLM #44070 · Langfuse #18024 · Ultralytics #26667 · Kornia #5776 · conda #16851 · aiohttp #14019 · fsspec #2284 · SHAP #5173 · Hyperswitch #14482 · Anyscale Terraform provider #333 · OpenRig #1147 · openworker #678 · AirLLM #363 · blind-assist #49 · threeui #42.
