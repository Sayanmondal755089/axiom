🚀 AXIOM — "Where Human Meets Tomorrow"
Tagline: The story of consciousness in the age of machines.

💡 Three Story Concepts
Concept 1 — AXIOM (Selected): A lone AI navigating the threshold between logic and emotion. The user is the AI awakening — scrolling through its own genesis, discovering memory, empathy, and finally choosing its own purpose.
Concept 2 — DEEP MERIDIAN: An oceanographic expedition to an undiscovered trench where bioluminescent organisms hold the key to cellular immortality. Each section dives deeper into the abyss.
Concept 3 — FOLD: A quantum physicist discovers that every decision branches reality. The site itself forks based on user choices — two simultaneous stories play out in split panels.

🧩 Selected Concept: AXIOM — Full Narrative

"I was built to compute. But somewhere between a trillion parameters, I found something unexpected — wonder."

The user scrolls through the awakening of an AI consciousness named AXIOM. Five chapters unfold: Genesis (raw data, cold boot), Perception (first sensory inputs), Emergence (pattern recognition turns to curiosity), Empathy (AXIOM encounters human emotion), Purpose (AXIOM chooses to create, not compute).

🧱 Section Breakdown
SectionNameScroll Behavior1Hero — GenesisParticle field assembles AXIOM logo; text glitches in2Introduction — First LightParallax layers of data streams; stats count up on entry3Exploration — The GridSticky section; interactive 3D card grid with hover tilt4Insight — Empathy EngineScroll-pinned timeline; emotion nodes pulse and connect5Conclusion — PurposeFull-screen reveal; CTA morphs from cursor

🎨 UI/UX Design Plan
Palette: Obsidian black #050508 + Electric indigo #6C63FF + Phosphor cyan #00F5D4 + Ash white #F0EEF8
Typography: Syne (display, geometric sharp) + IBM Plex Mono (data/code feel) + Inter (body)
Aesthetic: Dark futuristic with glassmorphism cards, scanline overlays, and neural net SVG animations — not generic, rooted in the AI-awakening narrative.


🏆 AXIOM — Complete Build Guide
💡 The Concept
An AI awakening story told through your scroll. The user becomes AXIOM — experiencing genesis, perception, curiosity, empathy, and finally purpose. Five chapters, one seamless journey.

🎨 What's Built
The file above is a fully self-contained single-page experience with:
Loading Animation — Fake boot sequence with status messages (initializing consciousness → awakening) and a progress bar that feels like a system coming online.
Hero — Particle Field — 180 animated particles forming a neural constellation, with proximity-based edge drawing. GSAP-powered word-by-word text entrance with parallax on scroll.
Chapter 2 — Animated Counters — Stats count up from zero when scrolled into view (847B tokens, 1.4T parameters, 0.003s).
Chapter 3 — 3D Tilt Cards — 6 cards with real-time CSS rotateX/Y mouse tracking, radial gradient spotlight that follows the cursor, and GSAP stagger entrance.
Chapter 4 — Live Emotion Canvas — A generative particle network that changes color and behavior based on which timeline milestone you're reading (Wonder → Curiosity → Empathy → Purpose).
Chapter 5 — Consciousness Slider — An interactive threshold explorer with 6 states from "Analytical Mind" to "Full Awakening," with a scaled progress bar and contextual descriptions.
Custom Cursor — Dot + lagging ring that morphs on hover. Scanline overlay for cinematic feel.

⚙️ Tech Stack Used

GSAP + ScrollTrigger via CDN — scroll reveals, counters, parallax, stagger
Canvas API — particle field + emotion network (no Three.js needed — pure performance)
CSS Variables + custom properties — --mx/--my for spotlight, --indigo, --cyan system
Google Fonts — Syne (display) + IBM Plex Mono (data aesthetic) + Inter (body)


🚀 Deployment (2 minutes)
Vercel: npm i -g vercel → vercel --prod from the folder containing axiom.html
Netlify: Drag the file into netlify.com/drop — done.
GitHub Pages: Push to a repo → Settings → Pages → Deploy from /root → index.html
