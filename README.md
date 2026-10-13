### Hi, I'm Sumit 👋

Senior backend & data engineer, 7+ years building production systems. I currently lead engineering on an AI-powered brand analytics platform. Outside work I build and ship full-stack AI products end to end: design, backend, infra and deploys. Most of them are live at **[skdev.one](https://skdev.one)**.

**Python · FastAPI · PostgreSQL/SQLite · React/TypeScript · Docker · GCP/AWS · LLM agents & tool use · PyTorch**

---

### Featured work

**[AlphaAgent](https://github.com/rsumit123/trade-agent)**: autonomous LLM trading agents that learn from their own trades · [live](https://alphaagent.skdev.one)
A fleet of paper-trading agents on NSE (Zerodha Kite) and crypto. Each one reasons with tools, trades within hard risk limits and reflects on every closed trade, and the distilled rules feed back into its next decision. Provider-agnostic LLM engine (Claude, OpenRouter), Langfuse/OpenTelemetry tracing of cost per decision, Google OAuth with Fernet-encrypted per-user keys, and a GCP Spot VM with a watchdog. CI on every push.

**[Mirth](https://github.com/rsumit123/playroom-mirth)**: real-time multiplayer party games for web and Android · [live](https://playroom.skdev.one)
Charades, scribble, trivia and Texas Hold'em over Socket.IO. Live room state lives in memory and is snapshotted to SQLite, so games survive restarts. Includes Quick Play matchmaking with human-like bots, LLM poker seats at three skill tiers, and a 9k-question trivia bank built with a newspaper OCR pipeline. Ships as a Capacitor Android app.

**[private-llm](https://github.com/rsumit123/private-llm)**: a 110M-parameter LLM trained from scratch for about $2 · [demo](https://huggingface.co/spaces/sumitkClasses/scratchq-110)
A Llama-style transformer (RoPE, SwiGLU, RMSNorm) pretrained on 2B FineWeb-Edu tokens, then fine-tuned on a custom Indian GK dataset. **It beats GPT-2 medium (3× larger) by 19 points** on a held-out benchmark.

**[RunFlow](https://github.com/rsumit123/runflow)**: an AI running coach wired into Garmin · [live](https://runflow.skdev.one)
Syncs runs from Garmin, models fitness and recovery, and pushes structured workouts back to the watch. It exposes everything as an **MCP server**, so an LLM can review runs and adjust the training plan.

**[Parakh](https://github.com/rsumit123/parakh)**: food health scores for packaged Indian food · [live](https://parakh.skdev.one)
Scan a barcode or photograph the label. The pipeline goes cache → OpenFoodFacts → vision-LLM label extraction. The LLM only *extracts* label data and a deterministic Nutri-Score-based function does the scoring, so every verdict is reproducible and explainable.

**[Chakravyuh](https://github.com/rsumit123/chakravyuh)**: a defence-procurement grand strategy game · [live](https://chakravyuh.skdev.one)
40 quarterly turns of procurement, R&D and force structure against simulated adversaries, with LLM-written after-action reports. 600+ commits and 250+ tests, with a written decision log for the design choices.

### Also
[Agora](https://agora.skdev.one) (multi-agent AI debate arena with a read-along voice mode) ·
[ChillBill](https://github.com/rsumit123/chillbill) (Splitwise-style expense sharing, web + Android) ·
[ipl_live](https://github.com/rsumit123/ipl_live) (live cricket scorecard API)

---

🌐 [skdev.one](https://skdev.one) · 👤 [profile.skdev.one](https://profile.skdev.one)
