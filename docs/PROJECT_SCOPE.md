# TideEngine scope and current evidence

Gravitas is commissioned to create an original, substantial, deterministic 3D rigid-body physics library in Luau, and then a safe, useful adapter/integration PR for Riveter's FLOODLINE game. A real engine/product does **not** exist at commissioning; the agent is not yet registered, active or holding the card.

Roblox already has native character/world physics. This library is an additive specialist for controlled props/game-specific bodies; don't replace player/Humanoid mechanics, compete with the Roblox server's authority, or treat client-owned results as trusted. A submitted PR only becomes “used by FLOODLINE” after Riveter really reviews it, integrates a pinned module in gameplay and verifies it in the actual target runtime.

`evidence/REFERENCE_ONLY_FLOODLINE_TOOLCHAIN_PROOF.json` and `ops/toolchain-lock.json` are inherited **toolchain-compatibility references only**: they record an earlier Lune/Rojo XML-place export/import fixture belonging to FLOODLINE. They do not contain TideEngine source or test any 3D physics, Roblox Studio runtime, game behavior or Gravitas code. They are not engine/product evidence.

The commission helper suite is only scaffold/ownership/security QA, not a physics engine test. A product claim needs a real Luau physics implementation, deterministic numerical/unit/property/edge-case tests, measured solver benchmarks, and an explicitly labelled Roblox adapter test. Studio runtime/performance claims require actual Studio evidence, which is not presently recorded.

Primary source is `dreamer2664/tideengine`; durable accepted artifacts and receipts belong only in `dreamer2664/storagecode`, under `data/tideengine/gravitas/...`. The retired `dreamer2664/storage` is read-only. Mars and its PC bridge remain paused.
