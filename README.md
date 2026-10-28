# Engida Lishan

Senior full-stack engineer with five years across fintech, commerce, and AI platforms. Most of my work is the part that has to stay correct after launch: release control, evaluation, caching, and the interfaces in front of them.

## Selected work

**Promptify** · [GitHub](https://github.com/engida32/promptify-skill) · Shell, MIT
Turns a rough prompt into a written brief before a terminal agent starts building, so work begins after you approve a file instead of after you approve a rewrite. One-command installer, idempotent, backs up whatever it replaces.

**Agent Workflow Kit** · [GitHub](https://github.com/engida32/agent-workflow-kit) · Python, standard library only
A resumable workflow for long tasks. State lives on disk, an independent checker decides when the work is done, and a run that loses its provider resumes at the same stage, even under a different model. Forty tests cover retries, fallback, and mid-turn resume.

**Pocket Approve** · [GitHub](https://github.com/engida32/pocket-approve) · Node 20+, MIT
Sends coding-agent permission requests to your phone and desktop, then returns the decision. It never approves anything on its own, and the terminal stays available as a fallback. A real bash permission was approved from a phone, a repeated tap was rejected, and 284 tests pass.

**Vector Search Studio** · [GitHub](https://github.com/engida32/vector-search-studio) · pgvector, React, TypeScript
Typo-tolerant semantic search over Supabase docs with no keyword matching. A `vector(384)` column, an HNSW cosine index, `<=>` distance queries, and a typed API through to the UI, with CI running typecheck, lint, and a no-Postgres smoke test.

**Payload Cache Service** · [GitHub](https://github.com/engida32/payload-cache-service) · FastAPI, PostgreSQL
A two-level cache that reuses both the transformed strings and the IDs of previously generated payloads, so a slow external transformer is called as little as possible. Thirty-nine tests cover hashing determinism and canonicalization, and a CLI exercises the service over HTTP.

**engida.devs.et** · [Site](https://engida.devs.et/) · Next.js App Router, Tailwind, shadcn/ui
Portfolio and case studies. Static export: pull requests run the full check suite without deploying, and a push to main deploys Pages, mirrors the same tested artifact to the custom domain over WebDAV, then verifies both sites.

*Also: [escalation-ocr-technical-demo](https://github.com/engida32/escalation-ocr-technical-demo), a two-part challenge in TypeScript. Restart-safe delayed escalation with one atomic claim per state change, and noisy OCR turned into validated JSON, each with a written approach journal.*

## Currently

Building small self-hosted tools for agent workflows, and open to senior full-stack and AI platform roles.

## Contact

[Email](mailto:engida32lishan@gmail.com) · [LinkedIn](https://linkedin.com/in/engida) · [GitHub](https://github.com/engida32) · [CV](https://engida.devs.et/cv/engida-lishan-cv.pdf)
