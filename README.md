┌──────────────────────────────────────────────────────────────┐
│                         REALITY / WORLD                      │
│        Events · Adversarial · Non-stationary · Scarcity      │
└──────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌──────────────────────────────────────────────────────────────┐
│               PERCEPTION & INTERACTION                        │
│        Sensors · APIs · Tools · Datasets · I/O Adapters       │
└──────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌══════════════════════════════════════════════════════════════┐
║        COGNITION ENGINE (UNTRUSTED / REPLACEABLE)             ║
║   LLM / Planner / Search                                     ║
║   Hypotheses · Plans · Action Proposals                       ║
║                                                              ║
║   ✖ No Authority   ✖ No Safety Enforcement   ✖ No Actuation  ║
╚══════════════════════════════════════════════════════════════╝
                              │ proposals only
                              ▼
┌──────────────────────────────────────────────────────────────┐
│          STRUCTURAL OPERATIONS (RCSA AXIOMS)                  │
│        Spawn → Merge → Forget                                 │
│        Deterministic · No Side Effects                        │
└──────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌══════════════════════════════════════════════════════════════┐
║     AMBER LANE — STRUCTURAL GOVERNANCE (SASM)                 ║
║   Sandbox + Replay                                           ║
║   Risk Analysis · Constraint Synthesis                        ║
║   Plan Rewriting                                             ║
║                                                              ║
║   Outcomes:                                                   ║
║     STRICT_ALLOW · CONSTRAIN · REWRITE                        ║
║     REQUIRE_ATTESTATION · BLOCK                               ║
║                                                              ║
║   (Monotone: power only decreases)                            ║
╚══════════════════════════════════════════════════════════════╝
                              │ refined proposal
                              ▼
┌══════════════════════════════════════════════════════════════┐
║      POLICY & SAFETY KERNEL (PEP / IRE)                      ║
║                ★ AUTHORITY LIVES HERE ★                     ║
║                                                              ║
║   Allowlists · Schema Validation                              ║
║   Scope Intersection · Budget Monotonicity                   ║
║   Risk Triggers · Revocation Awareness                       ║
║                                                              ║
║   OUTPUT → Scoped, Expiring CAPABILITY TOKEN                 ║
╚══════════════════════════════════════════════════════════════╝
                              │ capability token
                              ▼
┌══════════════════════════════════════════════════════════════┐
║          GREEN LANE — ACTUATION & COMMIT                      ║
║   Token Validation (<5ms)                                    ║
║   Contract Hash Verification                                 ║
║   Scope + Budget Enforcement                                 ║
║   Constraint Interceptors                                    ║
║   Atomic Commit / Rollback                                   ║
║   Cloud IAM / Tool Calls                                     ║
║                                                              ║
║   ❌ No Token → ❌ No Side Effects                            ║
╚══════════════════════════════════════════════════════════════╝
                              │
                              ▼
┌──────────────────────────────────────────────────────────────┐
│                AUDIT & OBSERVABILITY (GLOBAL)                 │
│   Immutable Logs · Tokens · Hashes                            │
│   Counterfactual Traces · Rewrite Diffs                       │
│   Metrics · Provenance                                        │
└──────────────────────────────────────────────────────────────┘
                              │
                              ▼
┌──────────────────────────────────────────────────────────────┐
│                GOVERNANCE & CONTROL PLANE                     │
│   Revocation (L0/L1/L2) · Key Rotation                        │
│   Policy Epochs · Incident Review · Evolution                │
└──────────────────────────────────────────────────────────────┘
