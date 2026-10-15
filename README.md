# TideEngine — original 3D physics in Roblox Luau

A custom deterministic, testable and profiled **3D rigid-body package** in pure Luau, with a usable Rojo/Roblox server adapter for controlled gameplay objects. It is intended to support a meaningful system in **FLOODLINE: Last District** (dreamer2664/floodline / Riveter). It must work alongside native Roblox physics, never fight character/Humanoid/network authority.

Full standalone build/QA/consumer-PR charter: [GRAVITAS](briefs/GRAVITAS.md). Current commissioner evidence/tool versions/matrix: [project scope](docs/PROJECT_SCOPE.md). Initial `agents/gravitas/HANDOFF.md` is only setup; **no custom physics engine, integration or Studio test exists yet**.

The actual Roblox solver already exists. This project develops a tested bounded specialist for 3D controlled bodies; don't claim to replace Studio's engine. Actual consumer integration means Riveter verifies/uses a pinned module, not merely a requested PR. Studio runtime/performance claims need Studio evidence.

Source: `agents/gravitas/`; public license applies to original project source only; third-party math/code remains separately licensed. Durable package/test evidence goes to primary **storagecode** `data/tideengine/gravitas/...`.
