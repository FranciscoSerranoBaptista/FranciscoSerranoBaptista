# Francisco Serrano Baptista

I build infrastructure for human development.

---

The question that occupies me: *Can we create systems that help people grow without reducing growth to a formula?*

I sit at an uncomfortable intersection—executive coach and AI engineer. Most days I'm not sure those two selves belong together. The coach in me knows that development is relational, emergent, resistant to optimization. The engineer wants to scale what works, to encode expertise into systems that reach beyond one-to-one conversations.

The tension is productive. I think.

## What I'm Building

### Oak9 — Developmental Intelligence Platform

A microservices ecosystem (~30 services) for AI-augmented coaching. Not a chatbot. Not a dashboard with an AI label. A cognitive infrastructure that holds the structural complexity of human development so coaches can hold the relational depth.

**The Knowledge Layer** — A poly-relational heterogeneous knowledge graph (`oak9-graph`) paired with LLMs as the foundational architecture. Developmental constructs—Kegan's orders, Torbert's action logics, Cook-Greuter's EDT, Dawson's Lectical levels—represented not as lookup tables but as relational structures that can hold contradiction, context dependency, and their own limits. A semantic search library (`oak9-library`, `oak9-bibliotheque`) surfaces resources through meaning, not just keywords.

**Developmental Assessment** — An agentic system (`stage`, `oak9-classification`, `oak9-developmental`) where 20+ specialized agents debate a client's developmental position across multiple frameworks. Advocates and critics. Structured confidence, not certainty. The system knows it's applying constructs and tries to say so. Built on Cook-Greuter's EDT and Dawson's Lectical frameworks, while remaining aware that every framework is a lens with a focal length.

**Enrichment & Orchestration** — A service orchestration layer (`oak9-orchestrator`) that manages enrichment cascades across the platform—feeding text through classification, synthesis (`oak9-synthesis`), plan generation (`oak9-plan`), and resource recommendations (`oak9-recommendations`) grounded in developmental context. Dependency-aware parallel processing so intelligence compounds across services rather than siloing.

**Privacy Architecture** — PII detection at 98.7% F1 across 5+ languages (`oak9-pii`, `oak9-anonymizer`), AES-256-GCM encryption, GDPR-compliant audit logging at 10k+ events/sec (`oak9-audit`), and a progressive disclosure system (`oak9-disclosure`) that controls how much analytical depth is surfaced and to whom. The data is intimate. The architecture treats it that way.

**Market & Leadership Intelligence** — A parallel intelligence layer tracking leadership transitions, sector pressure, and macro threats across European markets (`oak9-radar`, `oak9-pipeline`, `oak9-news`). Predictive analytics and capacity forecasting (`oak9-analytics`, `oak9-forecasting`). The knowledge graph connects geopolitical signals to coaching context—because development doesn't happen in a vacuum, and neither does leadership.

**Platform** — Multi-tenant Next.js application (`oak9-main`), shared infrastructure with Consul/Vault/Redis (`oak9-shared-infra`), Ory Kratos for identity (`oak9-identity`), PostgreSQL with pgvector (`oak9-databases`). The boring enterprise stuff that lets the interesting work happen safely.

### Adjacent Projects

**Social Listening & Research** — Tools for understanding how people talk about development in the wild. `deep-dialogue` processes conversational data at scale across platforms. `nightingale` analyzes leadership discourse on Reddit with AI-powered classification. `arcticshift` provides multi-source forum analysis with resumable processing. These feed the knowledge graph and ground the developmental models in how people actually make meaning—not just how theorists describe it.

**Hoopoe** — A learning platform for delivering coached developmental pathways with cohort management, progress tracking, and assessment. Named, like several projects here, after a bird from Attar's *Conference of the Birds*—a 12th-century Sufi poem about the stages of a journey toward self-knowledge. The naming is not accidental.

**Stage** — A standalone agentic system for estimating ego development stage from text. Multiple AI agents collaboratively evaluate evidence across Cook-Greuter and Dawson frameworks. The most direct expression of the core question: can a system assess development without flattening it?

## The Premise

Most AI in coaching falls into a familiar trap: it either replaces the coach with a chatbot (losing the relational core) or bolts AI onto existing practice as a feature (losing the rigor). Both assume the coach-client relationship is the unit of analysis.

I'm exploring a different frame. What if the unit isn't the relationship but the developmental ecology—the entire web of meaning-making that a person navigates across roles, contexts, and time? A skilled coach perceives fragments of this ecology in conversation. AI can hold more of it, longer, and surface patterns that exceed what any single human can track.

This isn't augmentation in the usual sense. It's closer to building a shared cognitive space where human judgment and computational pattern-recognition inform each other—where the AI doesn't pretend to understand development, but can hold the structural complexity while the coach holds the relational depth.

I'm aware this framing is itself a construction. Scaling intimacy may be a category error. But the alternative—keeping developmental support locked behind expensive one-to-one relationships—carries its own kind of violence. The question isn't whether to systematize, but what we're willing to notice about what gets lost when we do.

## Technical Approach

- LLMs paired with knowledge graphs as the foundational layer—representing developmental constructs as relational structures rather than flat classifications
- Agentic systems with adversarial validation (multiple perspectives, built-in doubt)
- Microservice orchestration with enrichment cascades and dependency-aware parallel processing
- Structured outputs with explicit uncertainty quantification
- RAG architectures grounded in domain-specific developmental corpora
- Privacy-by-design: PII detection, transcript encryption, progressive disclosure, GDPR audit trails
- Social listening pipelines that ground theoretical models in naturalistic language

Python. TypeScript. Anthropic Claude. PostgreSQL with pgvector. FastAPI. Next.js. Celery. Consul/Vault. The stack matters less than the epistemology—though the choice to ground everything in knowledge graphs rather than embeddings alone is itself an epistemological commitment: that development has structure worth preserving, not just similarity worth measuring.

## Current Questions

- What happens when the map becomes sophisticated enough that people mistake it for the territory—and how do you build that awareness into the system itself?
- If developmental frameworks are themselves stage-bound constructs, what does it mean to encode them computationally?
- Where is the boundary between holding complexity and aestheticizing it?
- What forms of knowing resist representation in any architecture—and what's the cost of building around that absence?
- Can infrastructure be designed to surface its own limitations, or does that require a kind of reflexivity that lives only in persons?
