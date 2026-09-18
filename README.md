# zero-trust-llm-pipeline

A zero-dependency, client-side governance engine designed for deterministic containment and audit verification of AI outputs without external API costs or server overhead.

## Architecture & 5-Gate Metabolism
- **Gate 0 (Pre-Generation Trajectory Sensor):** Intercepts and blocks out-of-scope queries before token generation using semantic threshold scoring.
- **Gate 1 (Anchor Tether & Confidence Scoring):** Enforces line-by-line claim grounding against verified document anchors using non-LLM concept and raw-word match scoring.
- **Gate 2 (TK_GAUGE Telemetry):** Monitors real-time reasoning-to-visible token ratios to flag structural output failure patterns (`BEAUTIFUL_LIE` and `AI_DEBT`).
- **Gate 3 (Validation Divergence Engine):** Cross-checks concept-level vs. literal-word agreement across anchored claims to detect paraphrasing drift.
- **Gate 4 (Sovereign Lock & Forensic Audit):** Escalates flagged outputs for named human review and generates real-time, browser-calculated SHA-256 cryptographic audit certificates.

## Documentation & Live Engine
- 📄 [Download CIAT25 User Manual (PDF)](./CIAT_demo_manual.pdf)
- 🚀 [Launch Live Interactive Engine](https://<your-username>.github.io/zero-trust-llm-pipeline/)
